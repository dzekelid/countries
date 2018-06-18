---
swagger: "2.0"
x-collection-name: UK National Archives Discovery
x-complete: 0
info:
  title: Getty Images Search API Get Countries
  description: Gets countries codes and names..
  version: "3.0"
host: api.gettyimages.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/countries:
    get:
      summary: Get Countries
      description: Gets countries codes and names..
      operationId: getV3Countries
      x-api-path-slug: v3countries-get
      parameters:
      - in: header
        name: Accept-Language
        description: Specifies the language of result values
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      responses:
        200:
          description: OK
      tags:
      - Countries
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