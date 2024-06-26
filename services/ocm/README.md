# OCM

The `ocm` service provides federated sharing functionality based on the [sciencemesh](https://sciencemesh.io/) and [ocm](https://github.com/cs3org/OCM-API) HTTP APIs. Internally the `ocm` service consists of the following services and endpoints:

External HTTP APIs:
* sciencemesh: serves the API for the invitation workflow
* ocmd: serves the API for managing federated shares

Internal GRPC APIs:
* ocmproviderauthorizer: manages the list of trusted providers and verifies requests
* ocminvitemanager: manages the list and state of invite tokens
* ocmshareprovider: manages ocm shares on the sharer
* ocmcore: used for creating federated shares on the receiver side
* authprovider: authenticates webdav requests using the ocm share tokens

## Trust Between Instances

The `ocm` services implements an invitation workflow which needs to be followed before creating federated shares. Invitations are limited to trusted instances, however.

The list of trusted instances is managed by the `ocmproviderauthorizer` service. The only supported backend currently is `json` which stores the list in a json file on disk.

Example `ocmproviders.json` file:
```
[
    {
        "name": "Example",
        "full_name": "Example provider",
        "organization": "Owncloud",
        "domain": "example.com",
        "homepage": "https://example.com",
        "services": [
            {
                "endpoint": {
                    "type": {
                        "name": "OCM",
                        "description": "example.com Open Cloud Mesh API"
                    },
                    "name": "example.com - OCM API",
                    "path": "https://example.com/ocm/",
                    "is_monitored": true
                },
                "api_version": "0.0.1",
                "host": "example.com"
            }
        ]
    }
]
```

## Invitation Workflow

Before sharing a resource with a remote user this user has to be invited by the sharer.

In order to do so a POST request is sent to the `generate-invite` endpoint of the sciencemesh API. The generated token is passed on to the receiver, who will then use the `accept-invite` endpoint to accept the invitation. As a result remote users will be added to the `ocminvitemanager` on both sides. See [invitation flow](invitation_flow) for the according sequence diagram.

The data backend of the `ocminvitemanager` is configurable. The only supported backend currently is `json` which stores the data in a json file on disk.

## Creating Shares

OCM Shares are currently created using the ocs API, just like regular shares. The difference is the share type, which is 6 (ShareTypeFederatedCloudShare) in this case, and a few additional parameters required for identifying the remote user.

See [Create share flow](create_share_flow) for the according sequence diagram.

The data backends of the `ocmshareprovider` and `ocmcore` services are configurable. The only supported backend currently is `json` which stores the data in a json file on disk.
