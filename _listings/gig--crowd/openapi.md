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