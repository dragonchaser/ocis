## Scenarios from OCIS API tests that are expected to fail with OCIS storage

The expected failures in this file are from features in the owncloud/ocis repo.

#### [Downloading the archive of the resource (files | folder) using resource path is not possible](https://github.com/owncloud/ocis/issues/4637)

- [apiArchiver/downloadByPath.feature:25](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L25)
- [apiArchiver/downloadByPath.feature:26](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L26)
- [apiArchiver/downloadByPath.feature:43](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L43)
- [apiArchiver/downloadByPath.feature:44](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L44)
- [apiArchiver/downloadByPath.feature:47](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L47)
- [apiArchiver/downloadByPath.feature:73](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L73)
- [apiArchiver/downloadByPath.feature:163](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L163)
- [apiArchiver/downloadByPath.feature:164](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadByPath.feature#L164)

### [Downloaded /Shares tar contains resource (files|folder) with leading / in Response](https://github.com/owncloud/ocis/issues/4636)

- [apiArchiver/downloadById.feature:165](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadById.feature#L165)
- [apiArchiver/downloadById.feature:166](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiArchiver/downloadById.feature#L166)

### [Shared mount folder gets deleted when overwritten by a file from personal space](https://github.com/owncloud/ocis/issues/7208)

- [apiSpacesShares/copySpaces.feature:634](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/copySpaces.feature#L634)
- [apiSpacesShares/copySpaces.feature:652](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/copySpaces.feature#L652)

#### [PATCH request for TUS upload with wrong checksum gives incorrect response](https://github.com/owncloud/ocis/issues/1755)

- [apiSpacesShares/shareUploadTUS.feature:267](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/shareUploadTUS.feature#L267)
- [apiSpacesShares/shareUploadTUS.feature:286](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/shareUploadTUS.feature#L286)
- [apiSpacesShares/shareUploadTUS.feature:364](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/shareUploadTUS.feature#L364)

### [Settings service user can list other peoples assignments](https://github.com/owncloud/ocis/issues/5032)

- [apiAccountsHashDifficulty/assignRole.feature:27](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiAccountsHashDifficulty/assignRole.feature#L27)
- [apiAccountsHashDifficulty/assignRole.feature:28](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiAccountsHashDifficulty/assignRole.feature#L28)
- [apiGraph/assignRole.feature:30](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraph/assignRole.feature#L30)
- [apiGraph/assignRole.feature:31](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraph/assignRole.feature#L31)
- [apiGraph/assignRole.feature:32](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraph/assignRole.feature#L32)

#### [A User can get information of another user with Graph API](https://github.com/owncloud/ocis/issues/5125)

- [apiGraphUserGroup/getUser.feature:84](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L84)
- [apiGraphUserGroup/getUser.feature:85](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L85)
- [apiGraphUserGroup/getUser.feature:86](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L86)
- [apiGraphUserGroup/getUser.feature:87](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L87)
- [apiGraphUserGroup/getUser.feature:88](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L88)
- [apiGraphUserGroup/getUser.feature:89](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L89)
- [apiGraphUserGroup/getUser.feature:90](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L90)
- [apiGraphUserGroup/getUser.feature:91](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L91)
- [apiGraphUserGroup/getUser.feature:92](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L92)
- [apiGraphUserGroup/getUser.feature:93](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L93)
- [apiGraphUserGroup/getUser.feature:94](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L94)
- [apiGraphUserGroup/getUser.feature:95](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L95)
- [apiGraphUserGroup/getUser.feature:637](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L637)
- [apiGraphUserGroup/getUser.feature:638](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L638)
- [apiGraphUserGroup/getUser.feature:639](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L639)
- [apiGraphUserGroup/getUser.feature:640](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L640)
- [apiGraphUserGroup/getUser.feature:641](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L641)
- [apiGraphUserGroup/getUser.feature:642](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L642)
- [apiGraphUserGroup/getUser.feature:643](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L643)
- [apiGraphUserGroup/getUser.feature:644](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L644)
- [apiGraphUserGroup/getUser.feature:645](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L645)
- [apiGraphUserGroup/getUser.feature:646](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L646)
- [apiGraphUserGroup/getUser.feature:647](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L647)
- [apiGraphUserGroup/getUser.feature:648](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getUser.feature#L648)

#### [Normal user can get expanded members information of a group](https://github.com/owncloud/ocis/issues/5604)

- [apiGraphUserGroup/getGroup.feature:399](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getGroup.feature#L399)
- [apiGraphUserGroup/getGroup.feature:400](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getGroup.feature#L400)
- [apiGraphUserGroup/getGroup.feature:401](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getGroup.feature#L401)

#### [Same users can be added in a group multiple time](https://github.com/owncloud/ocis/issues/5702)

- [apiGraphUserGroup/addUserToGroup.feature:289](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L289)

#### [API requests from an unauthorized user should return 403](https://github.com/owncloud/ocis/issues/5938)

- [apiGraphUserGroup/addUserToGroup.feature:152](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L152)
- [apiGraphUserGroup/addUserToGroup.feature:153](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L153)
- [apiGraphUserGroup/addUserToGroup.feature:154](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L154)
- [apiGraphUserGroup/addUserToGroup.feature:188](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L188)
- [apiGraphUserGroup/addUserToGroup.feature:189](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L189)
- [apiGraphUserGroup/addUserToGroup.feature:190](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L190)
- [apiGraphUserGroup/createGroup.feature:42](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/createGroup.feature#L42)
- [apiGraphUserGroup/createGroup.feature:43](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/createGroup.feature#L43)
- [apiGraphUserGroup/createGroup.feature:44](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/createGroup.feature#L44)
- [apiGraphUserGroup/deleteGroup.feature:63](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/deleteGroup.feature#L63)
- [apiGraphUserGroup/deleteGroup.feature:62](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/deleteGroup.feature#L62)
- [apiGraphUserGroup/deleteGroup.feature:64](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/deleteGroup.feature#L64)
- [apiGraphUserGroup/editGroup.feature:35](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/editGroup.feature#L35)
- [apiGraphUserGroup/editGroup.feature:34](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/editGroup.feature#L34)
- [apiGraphUserGroup/editGroup.feature:36](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/editGroup.feature#L36)
- [apiGraphUserGroup/getGroup.feature:107](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getGroup.feature#L107)
- [apiGraphUserGroup/getGroup.feature:108](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getGroup.feature#L108)
- [apiGraphUserGroup/getGroup.feature:109](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/getGroup.feature#L109)
- [apiGraphUserGroup/removeUserFromGroup.feature:193](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/removeUserFromGroup.feature#L193)
- [apiGraphUserGroup/removeUserFromGroup.feature:194](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/removeUserFromGroup.feature#L194)
- [apiGraphUserGroup/removeUserFromGroup.feature:195](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/removeUserFromGroup.feature#L195)

#### [API requests for a non-existent resources should return 404](https://github.com/owncloud/ocis/issues/5939)

- [apiGraphUserGroup/addUserToGroup.feature:205](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L205)
- [apiGraphUserGroup/addUserToGroup.feature:206](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L206)
- [apiGraphUserGroup/addUserToGroup.feature:207](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L207)

### [Users are added in a group with wrong host in host-part of user](https://github.com/owncloud/ocis/issues/5871)

- [apiGraphUserGroup/addUserToGroup.feature:373](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L373)
- [apiGraphUserGroup/addUserToGroup.feature:387](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L387)

### [Adding the same user as multiple members in a single request results in listing the same user twice in the group](https://github.com/owncloud/ocis/issues/5855)

- [apiGraphUserGroup/addUserToGroup.feature:424](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiGraphUserGroup/addUserToGroup.feature#L424)

### [Shared file locking is not possible using different path](https://github.com/owncloud/ocis/issues/7599)

- [apiLocks/lockFiles.feature:187](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L187)
- [apiLocks/lockFiles.feature:188](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L188)
- [apiLocks/lockFiles.feature:189](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L189)
- [apiLocks/lockFiles.feature:305](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L305)
- [apiLocks/lockFiles.feature:306](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L306)
- [apiLocks/lockFiles.feature:307](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L307)
- [apiLocks/lockFiles.feature:358](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L358)
- [apiLocks/lockFiles.feature:359](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L359)
- [apiLocks/lockFiles.feature:360](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L360)
- [apiLocks/lockFiles.feature:361](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L361)
- [apiLocks/lockFiles.feature:362](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L362)
- [apiLocks/lockFiles.feature:363](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L363)
- [apiLocks/lockFiles.feature:391](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L391)
- [apiLocks/lockFiles.feature:392](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L392)
- [apiLocks/lockFiles.feature:393](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L393)
- [apiLocks/lockFiles.feature:394](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L394)
- [apiLocks/lockFiles.feature:395](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L395)
- [apiLocks/lockFiles.feature:396](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L396)
- [apiLocks/unlockFiles.feature:62](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L62)
- [apiLocks/unlockFiles.feature:63](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L63)
- [apiLocks/unlockFiles.feature:64](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L64)
- [apiLocks/unlockFiles.feature:168](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L168)
- [apiLocks/unlockFiles.feature:169](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L169)
- [apiLocks/unlockFiles.feature:170](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L170)
- [apiLocks/unlockFiles.feature:171](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L171)
- [apiLocks/unlockFiles.feature:172](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L172)
- [apiLocks/unlockFiles.feature:173](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L173)
- [apiLocks/unlockFiles.feature:195](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L195)
- [apiLocks/unlockFiles.feature:196](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L196)
- [apiLocks/unlockFiles.feature:197](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L197)
- [apiLocks/unlockFiles.feature:198](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L198)
- [apiLocks/unlockFiles.feature:199](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L199)
- [apiLocks/unlockFiles.feature:200](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L200)
- [apiLocks/unlockFiles.feature:222](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L222)
- [apiLocks/unlockFiles.feature:223](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L223)
- [apiLocks/unlockFiles.feature:224](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L224)
- [apiLocks/unlockFiles.feature:225](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L225)
- [apiLocks/unlockFiles.feature:226](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L226)
- [apiLocks/unlockFiles.feature:227](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L227)

#### [Trying to upload to a locked file gives 500](https://github.com/owncloud/ocis/issues/7638)

- [apiLocks/lockFiles.feature:324](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L324)
- [apiLocks/lockFiles.feature:325](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L325)
- [apiLocks/lockFiles.feature:326](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L326)
- [apiLocks/lockFiles.feature:327](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L327)
- [apiLocks/lockFiles.feature:328](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L328)
- [apiLocks/lockFiles.feature:329](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L329)
- [apiLocks/unlockFiles.feature:87](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L87)
- [apiLocks/unlockFiles.feature:88](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L88)
- [apiLocks/unlockFiles.feature:89](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L89)
- [apiLocks/unlockFiles.feature:90](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L90)
- [apiLocks/unlockFiles.feature:91](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L91)
- [apiLocks/unlockFiles.feature:92](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L92)
- [apiLocks/lockFiles.feature:435](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L435)
- [apiLocks/lockFiles.feature:436](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L436)
- [apiLocks/lockFiles.feature:437](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L437)
- [apiLocks/lockFiles.feature:438](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L438)
- [apiLocks/lockFiles.feature:439](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L439)
- [apiLocks/lockFiles.feature:440](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L440)
- [apiLocks/lockFiles.feature:479](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L479)
- [apiLocks/lockFiles.feature:480](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L480)
- [apiLocks/lockFiles.feature:481](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L481)
- [apiLocks/lockFiles.feature:482](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L482)
- [apiLocks/lockFiles.feature:483](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L483)
- [apiLocks/lockFiles.feature:484](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L484)

#### [Folders can be locked and locking works partially](https://github.com/owncloud/ocis/issues/7641)

- [apiLocks/lockFiles.feature:409](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L409)
- [apiLocks/lockFiles.feature:410](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L410)
- [apiLocks/lockFiles.feature:411](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L411)
- [apiLocks/lockFiles.feature:412](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L412)
- [apiLocks/lockFiles.feature:413](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L413)
- [apiLocks/lockFiles.feature:414](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L414)

### [Anonymous users can unlock a file shared to them through a public link if they get the lock token](https://github.com/owncloud/ocis/issues/7761)

- [apiLocks/unlockFiles.feature:42](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L42)
- [apiLocks/unlockFiles.feature:43](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L43)
- [apiLocks/unlockFiles.feature:44](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L44)
- [apiLocks/unlockFiles.feature:45](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L45)
- [apiLocks/unlockFiles.feature:46](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L46)
- [apiLocks/unlockFiles.feature:47](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L47)

### [Trying to unlock a shared file with sharer's lock token gives 500](https://github.com/owncloud/ocis/issues/7767)

- [apiLocks/unlockFiles.feature:114](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L114)
- [apiLocks/unlockFiles.feature:115](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L115)
- [apiLocks/unlockFiles.feature:116](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L116)
- [apiLocks/unlockFiles.feature:117](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L117)
- [apiLocks/unlockFiles.feature:118](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L118)
- [apiLocks/unlockFiles.feature:119](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L119)
- [apiLocks/unlockFiles.feature:141](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L141)
- [apiLocks/unlockFiles.feature:142](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L142)
- [apiLocks/unlockFiles.feature:143](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L143)
- [apiLocks/unlockFiles.feature:144](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L144)
- [apiLocks/unlockFiles.feature:145](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L145)
- [apiLocks/unlockFiles.feature:146](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/unlockFiles.feature#L146)

### [Anonymous user trying lock a file shared to them through a public link gives 405](https://github.com/owncloud/ocis/issues/7790)

- [apiLocks/lockFiles.feature:528](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L528)
- [apiLocks/lockFiles.feature:529](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L529)
- [apiLocks/lockFiles.feature:530](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L530)
- [apiLocks/lockFiles.feature:531](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L531)
- [apiLocks/lockFiles.feature:532](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L532)
- [apiLocks/lockFiles.feature:533](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L533)
- [apiLocks/lockFiles.feature:552](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L552)
- [apiLocks/lockFiles.feature:553](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L553)
- [apiLocks/lockFiles.feature:554](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L554)
- [apiLocks/lockFiles.feature:555](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L555)
- [apiLocks/lockFiles.feature:556](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L556)
- [apiLocks/lockFiles.feature:557](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiLocks/lockFiles.feature#L557)

### [blocksDownload link type is not implemented yet (sharing-ng)](https://github.com/owncloud/ocis/issues/7879)

- [apiSharingNgLinkShare/linkShare.feature:72](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L72)
- [apiSharingNgLinkShare/linkShare.feature:202](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L202)
- [apiSharingNgLinkShare/linkShare.feature:340](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L340)
- [apiSharingNgLinkShare/linkShare.feature:409](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L409)
- [apiSharingNgLinkShare/linkShare.feature:475](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L475)
- [apiSharingNgLinkShare/linkShare.feature:541](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L541)
- [apiSharingNgLinkShare/linkShare.feature:543](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L543)
- [apiSharingNgLinkShare/linkShare.feature:544](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L544)
- [apiSharingNgLinkShare/linkShare.feature:545](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L545)
- [apiSharingNgLinkShare/linkShare.feature:611](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L611)
- [apiSharingNgLinkShare/linkShare.feature:959](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L959)
- [apiSharingNgLinkShare/linkShare.feature:1105](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1105)
- [apiSharingNgLinkShare/linkShare.feature:1161](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1161)
- [apiSharingNgLinkShare/linkShare.feature:1162](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1162)
- [apiSharingNgLinkShare/linkShare.feature:1163](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1163)
- [apiSharingNgLinkShare/linkShare.feature:1268](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1268)
- [apiSharingNgLinkShare/linkShare.feature:1334](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1334)
- [apiSharingNgLinkShare/linkShare.feature:1478](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1478)
- [apiSharingNgLinkShare/linkShare.feature:1547](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1547)
- [apiSharingNgLinkShare/linkShare.feature:1597](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1597)
- [apiSharingNgLinkShare/linkShare.feature:1598](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1598)
- [apiSharingNgLinkShare/linkShare.feature:1599](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1599)
- [apiSharingNgLinkShare/linkShare.feature:1838](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1838)
- [apiSharingNgLinkShare/linkShare.feature:1978](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L1978)
- [apiSharingNgLinkShare/linkShare.feature:2032](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2032)
- [apiSharingNgLinkShare/linkShare.feature:2033](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2033)
- [apiSharingNgLinkShare/linkShare.feature:2034](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2034)
- [apiSharingNgLinkShare/linkShare.feature:2102](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2102)
- [apiSharingNgLinkShare/linkShare.feature:2169](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2169)
- [apiSharingNgLinkShare/linkShare.feature:2240](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2240)
- [apiSharingNgLinkShare/linkShare.feature:2421](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2421)
- [apiSharingNgLinkShare/linkShare.feature:2680](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2680)
- [apiSharingNgLinkShare/linkShare.feature:2734](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2734)
- [apiSharingNgLinkShare/linkShare.feature:2735](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2735)
- [apiSharingNgLinkShare/linkShare.feature:2736](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2736)
- [apiSharingNgLinkShare/linkShare.feature:2804](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2804)
- [apiSharingNgLinkShare/linkShare.feature:2890](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L2890)
- [apiSharingNgLinkShare/linkShare.feature:3258](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L3258)
- [apiSharingNgLinkShare/linkShare.feature:3380](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L3380)
- [apiSharingNgLinkShare/linkShare.feature:3507](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L3507)
- [apiSharingNgLinkShare/linkShare.feature:3634](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L3634)
- [apiSharingNgLinkShare/linkShare.feature:3762](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L3762)
- [apiSharingNgLinkShare/linkShare.feature:4030](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNgLinkShare/linkShare.feature#L4030)
- [apiSharingNg/removeAccessToDriveItem.feature:125](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDriveItem.feature#L125)
- [apiSharingNg/removeAccessToDriveItem.feature:141](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDriveItem.feature#L141)
- [apiSharingNg/removeAccessToDriveItem.feature:161](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDriveItem.feature#L161)
- [apiSharingNg/removeAccessToDriveItem.feature:179](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDriveItem.feature#L179)
- [apiSharingNg/removeAccessToDrive.feature:177](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDrive.feature#L177)
- [apiSharingNg/removeAccessToDrive.feature:206](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDrive.feature#L206)
- [apiSharingNg/removeAccessToDrive.feature:236](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSharingNg/removeAccessToDrive.feature#L236)

### [sharee (editor role) MOVE a file by file-id into same shared folder returns 403](https://github.com/owncloud/ocis/issues/7617)

- [apiSpacesDavOperation/moveByFileId.feature:466](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L466)
- [apiSpacesDavOperation/moveByFileId.feature:467](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L467)
- [apiSpacesDavOperation/moveByFileId.feature:489](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L489)
- [apiSpacesDavOperation/moveByFileId.feature:490](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L490)
- [apiSpacesDavOperation/moveByFileId.feature:725](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L725)
- [apiSpacesDavOperation/moveByFileId.feature:726](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L726)

### [MOVE a file into same folder with same name returns 404 instead of 403](https://github.com/owncloud/ocis/issues/1976)

- [apiSpacesShares/moveSpaces.feature:69](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/moveSpaces.feature#L69)
- [apiSpacesShares/moveSpaces.feature:70](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/moveSpaces.feature#L70)
- [apiSpacesShares/moveSpaces.feature:405](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesShares/moveSpaces.feature#L405)
- [apiSpacesDavOperation/moveByFileId.feature:86](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L86)
- [apiSpacesDavOperation/moveByFileId.feature:87](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L87)
- [apiSpacesDavOperation/moveByFileId.feature:204](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L204)
- [apiSpacesDavOperation/moveByFileId.feature:205](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L205)
- [apiSpacesDavOperation/moveByFileId.feature:206](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L206)
- [apiSpacesDavOperation/moveByFileId.feature:207](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L207)
- [apiSpacesDavOperation/moveByFileId.feature:208](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L208)
- [apiSpacesDavOperation/moveByFileId.feature:209](https://github.com/owncloud/ocis/blob/master/tests/acceptance/features/apiSpacesDavOperation/moveByFileId.feature#L209)


- Note: always have an empty line at the end of this file.
  The bash script that processes this file requires that the last line has a newline on the end.
