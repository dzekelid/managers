swagger: "2.0"
x-collection-name: Azure Storage
x-complete: 1
info:
  title: StorSimpleSeries8000ManagementClient
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.StorSimple/managers:
    get:
      summary: Managers List
      description: Retrieves all the managers in a subscription.
      operationId: Managers_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-storsimplemanagers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}:
    get:
      summary: Managers Get
      description: Returns the properties of the specified manager name.
      operationId: Managers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
    put:
      summary: Managers Create Or Update
      description: Creates or updates the manager.
      operationId: Managers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The manager
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Managers
    delete:
      summary: Managers Delete
      description: Deletes the manager.
      operationId: Managers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/devices/{deviceName}/publicEncryptionKey
  : post:
      summary: Managers Get Device Public Encryption Key
      description: Returns the public encryption key of the device.
      operationId: Managers_GetDevicePublicEncryptionKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamedevicesdevicenamepublicencryptionkey-post
      parameters:
      - in: path
        name: deviceName
        description: The device name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/encryptionSettings/default
  : get:
      summary: Managers Get Encryption Settings
      description: Returns the encryption settings of the manager.
      operationId: Managers_GetEncryptionSettings
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameencryptionsettingsdefault-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/extendedInformation/vaultExtendedInfo
  : get:
      summary: Managers Get Extended Info
      description: Returns the extended information of the specified manager name.
      operationId: Managers_GetExtendedInfo
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
    put:
      summary: Managers Create Extended Info
      description: Creates the extended info of the manager.
      operationId: Managers_CreateExtendedInfo
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The manager extended information
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Managers
    delete:
      summary: Managers Delete Extended Info
      description: Deletes the extended info of the manager.
      operationId: Managers_DeleteExtendedInfo
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers
    patch:
      summary: Managers Update Extended Info
      description: Updates the extended info of the manager.
      operationId: Managers_UpdateExtendedInfo
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-patch
      parameters:
      - in: header
        name: If-Match
        description: Pass the ETag of ExtendedInfo fetched from GET call
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The manager extended information
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Managers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/regenerateActivationKey
  : post:
      summary: Managers Regenerate Activation Key
      description: Re-generates and returns the activation key of the manager.
      operationId: Managers_RegenerateActivationKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameregenerateactivationkey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Managers