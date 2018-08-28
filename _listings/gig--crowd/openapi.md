swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/managers/settings:
    get:
      summary: Get Managers Settings
      description: Get managers settings.
      operationId: getApiV1ManagersSettings
      x-api-path-slug: apiv1managerssettings-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Settings
  /api/v1/managers/search:
    get:
      summary: Get Managers Search
      description: Get managers search.
      operationId: getApiV1ManagersSearch
      x-api-path-slug: apiv1managerssearch-get
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: request.query
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Search
  /api/v1/managers/{managerId}/permissions:
    put:
      summary: Put Managers Managerid Permissions
      description: Put managers managerid permissions.
      operationId: putApiV1ManagersManagerPermissions
      x-api-path-slug: apiv1managersmanageridpermissions-put
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: managerId
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Managerid
      - Permissions
  /api/v1/managers/{managerId}:
    delete:
      summary: Delete Managers Managerid
      description: Delete managers managerid.
      operationId: deleteApiV1ManagersManager
      x-api-path-slug: apiv1managersmanagerid-delete
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: managerId
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Managerid
  /api/v1/managers/accept/{artistId}:
    post:
      summary: Post Managers Accept Artistid
      description: Post managers accept artistid.
      operationId: postApiV1ManagersAcceptArtist
      x-api-path-slug: apiv1managersacceptartistid-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Accept
      - Artistid
  /api/v1/managers/approve/{artistId}:
    post:
      summary: Post Managers Approve Artistid
      description: Post managers approve artistid.
      operationId: postApiV1ManagersApproveArtist
      x-api-path-slug: apiv1managersapproveartistid-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Approve
      - Artistid
  /api/v1/managers/combine/{oldid}/{newid}:
    post:
      summary: Post Managers Combine Old New
      description: Post managers combine old new.
      operationId: postApiV1ManagersCombineOldNew
      x-api-path-slug: apiv1managerscombineoldidnewid-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: newid
      - in: path
        name: oldid
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Combine
      - Old
      - New
  /api/v1/managers/reject/{artistId}/{reason}:
    post:
      summary: Post Managers Reject Artistid Reason
      description: Post managers reject artistid reason.
      operationId: postApiV1ManagersRejectArtistReason
      x-api-path-slug: apiv1managersrejectartistidreason-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: reason
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Reject
      - Artistid
      - Reason
  /api/v1/Managers:
    get:
      summary: Get Managers
      description: Get managers.
      operationId: getApiV1Managers
      x-api-path-slug: apiv1managers-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
    put:
      summary: Put Managers
      description: Put managers.
      operationId: putApiV1Managers
      x-api-path-slug: apiv1managers-put
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Managers
    post:
      summary: Post Managers
      description: Post managers.
      operationId: postApiV1Managers
      x-api-path-slug: apiv1managers-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        description: ','
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Managers