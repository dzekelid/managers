---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Delete Managers Managerid
  version: 1.0.0
  description: Delete managers managerid.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---