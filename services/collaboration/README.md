# Collaboration

The collaboration service connects ocis with document servers such as Collabora, ONLYOFFICE or Microsoft using the WOPI protocol.

Since this service requires an external document server, it won't start by default when using `ocis server`. You must start it manually with the `ocis collaboration server` command.

Because the collaboration service needs to be started manually, the following prerequisite applies: On collaboration service startup, particular environment variables are required to be populated. If environment variables have a default like the `MICRO_REGISTRY_ADDRESS`, the default will be used, if not set otherwise. Use for all others the instance values as defined. If these environment variables are not provided or misconfigured, the collaboration service will not start up.

Required environment variables:
* `OCIS_URL`
* `OCIS_JWT_SECRET`
* `OCIS_REVA_GATEWAY`
* `MICRO_REGISTRY_ADDRESS`

## Requirements

The collaboration service requires the target document server (ONLYOFFICE, Collabora, etc.) to be up and running. Additionally, some Infinite Scale services are also required to be running in order to register the GRPC service for the `open in app` action in the webUI. The following internal and external services need to be available:

* External document server.
* The gateway service.
* The app-registry service.

If any of the named services above have not been started or are not reachable, the collaboration service won't start. For the binary or the docker release of Infinite Scale, check with the `ocis list` command if they have been started. If not, you must start them manually upfront before starting the collaboration service.

## WOPI Configuration

There are a few variables that you need to set:

* `COLLABORATION_APP_NAME`:\
  The name of the connected WebOffice app, which can be one of the following:\
  `Collabora`, `OnlyOffice`, `Microsoft365` or `MicrosoftOfficeOnline`.

* `COLLABORATION_APP_ADDR`:\
  The URL of the collaborative editing app (onlyoffice, collabora, etc).\
  For example: `https://office.example.com`.

* `COLLABORATION_APP_INSECURE`:\
  In case you are using a self signed certificate for the WOPI app you can tell the collaboration service to allow an insecure connection.

* `COLLABORATION_WOPI_SRC`:\
  The external address of the collaboration service. The target app (onlyoffice, collabora, etc) will use this address to read and write files from Infinite Scale.\
  For example: `https://wopi.example.com`.

The application can be customized further by changing the `COLLABORATION_APP_*` options to better describe the application.
