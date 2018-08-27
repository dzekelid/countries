---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Countryphonecodes
  version: 1.0.0
  description: Get api countryphonecodes.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/CountryPhoneCodes:
    get:
      summary: Get API Countryphonecodes
      description: Get api countryphonecodes.
      operationId: ApiCountryPhoneCodesGet
      x-api-path-slug: apicountryphonecodes-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Countryphonecodes
  /api/RestrictedCountries:
    get:
      summary: Get API Restrictedcountries
      description: Get api restrictedcountries.
      operationId: ApiRestrictedCountriesGet
      x-api-path-slug: apirestrictedcountries-get
      responses:
        200:
          description: OK
      tags:
      - Restrictedcountries
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