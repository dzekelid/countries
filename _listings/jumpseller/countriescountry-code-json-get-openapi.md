---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Get Countries Country Code
  description: Retrieve a single country information..
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /countries.json:
    get:
      summary: Get Countries
      description: Retrieve all countries..
      operationId: getCountries.json
      x-api-path-slug: countries-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
      - Json
  /countries/{country_code}.json:
    get:
      summary: Get Countries Country Code
      description: Retrieve a single country information..
      operationId: getCountriesCountryCode.json
      x-api-path-slug: countriescountry-code-json-get
      parameters:
      - in: path
        name: country_code
        description: ISO3166 Country Code
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
      - Country
      - Code
      - Json
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