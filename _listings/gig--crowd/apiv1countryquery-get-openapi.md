---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Country Query
  version: 1.0.0
  description: Get country query.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/country/{query}:
    get:
      summary: Get Country Query
      description: Get country query.
      operationId: getApiV1CountryQuery
      x-api-path-slug: apiv1countryquery-get
      parameters:
      - in: path
        name: query
      responses:
        200:
          description: OK
      tags:
      - Country
      - Query
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