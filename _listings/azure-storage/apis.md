---
name: Azure Storage
x-slug: azure-storage
description: Azure Storage offers non-relational data storage including Blob Storage,
  Table Storage, Queue Storage, and Files.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Managers
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Storage API Managers List
  x-api-slug: azure-storage-api
  description: Retrieves all the managers in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.StorSimple/managers
  tags: Managers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidprovidersmicrosoft-storsimplemanagers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidprovidersmicrosoft-storsimplemanagers-get-openapi.md
- name: Azure Storage API Managers List By Resource Group
  x-api-slug: azure-storage-api
  description: Retrieves all the managers in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers
  tags: Managers Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagers-get-openapi.md
- name: Azure Storage API Managers Get
  x-api-slug: azure-storage-api
  description: Returns the properties of the specified manager name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}
  tags: Managers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-get-openapi.md
- name: Azure Storage API Managers Create Or Update
  x-api-slug: azure-storage-api
  description: Creates or updates the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-put-openapi.md
- name: Azure Storage API Managers Delete
  x-api-slug: azure-storage-api
  description: Deletes the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagername-delete-openapi.md
- name: Azure Storage API Managers Get Device Public Encryption Key
  x-api-slug: azure-storage-api
  description: Returns the public encryption key of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/devices/{deviceName}/publicEncryptionKey
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamedevicesdevicenamepublicencryptionkey-post-openapi.md
- name: Azure Storage API Managers Get Encryption Settings
  x-api-slug: azure-storage-api
  description: Returns the encryption settings of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/encryptionSettings/default
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameencryptionsettingsdefault-get-openapi.md
- name: Azure Storage API Managers Get Extended Info
  x-api-slug: azure-storage-api
  description: Returns the extended information of the specified manager name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/extendedInformation/vaultExtendedInfo
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-get-openapi.md
- name: Azure Storage API Managers Create Extended Info
  x-api-slug: azure-storage-api
  description: Creates the extended info of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/extendedInformation/vaultExtendedInfo
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-put-openapi.md
- name: Azure Storage API Managers Delete Extended Info
  x-api-slug: azure-storage-api
  description: Deletes the extended info of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/extendedInformation/vaultExtendedInfo
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-delete-openapi.md
- name: Azure Storage API Managers Update Extended Info
  x-api-slug: azure-storage-api
  description: Updates the extended info of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/extendedInformation/vaultExtendedInfo
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameextendedinformationvaultextendedinfo-patch-openapi.md
- name: Azure Storage API Managers Get Activation Key
  x-api-slug: azure-storage-api
  description: Returns the activation key of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/listActivationKey
  tags: Managers Activation Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamelistactivationkey-post-openapi.md
- name: Azure Storage API Managers Get Private Encryption Key
  x-api-slug: azure-storage-api
  description: Returns the symmetric encrypted private encryption key of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/listPrivateEncryptionKey
  tags: Managers Private Encryption Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamelistprivateencryptionkey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamelistprivateencryptionkey-post-openapi.md
- name: Azure Storage API Managers Get Public Encryption Key
  x-api-slug: azure-storage-api
  description: Returns the symmetric encrypted public encryption key of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/listPublicEncryptionKey
  tags: Managers Public Encryption Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamelistpublicencryptionkey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernamelistpublicencryptionkey-post-openapi.md
- name: Azure Storage API Managers Regenerate Activation Key
  x-api-slug: azure-storage-api
  description: Re-generates and returns the activation key of the manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.StorSimple/managers/{managerName}/regenerateActivationKey
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-storsimplemanagersmanagernameregenerateactivationkey-post-openapi.md
- name: Azure Storage API
  x-api-slug: azure-storage-api
  description: Azure Storage offers non-relational data storage including Blob Storage,
    Table Storage, Queue Storage, and Files.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com//
  tags: Managers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/managers/master/_listings/azure-storage/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/storage/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/storage/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/storage/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/storage/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---