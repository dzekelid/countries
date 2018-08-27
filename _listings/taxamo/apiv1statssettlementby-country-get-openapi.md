---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 0
info:
  title: Taxamo Settlement By Country
  description: Settlement by country.
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/dictionaries/countries:
    get:
      summary: Countries
      description: Countries.
      operationId: getCountriesDict
      x-api-path-slug: apiv1dictionariescountries-get
      parameters:
      - in: query
        name: tax_supported
        description: Should only countries with tax supported be listed?
      responses:
        200:
          description: OK
      tags:
      - Countries
  /api/v1/stats/settlement/by_country:
    get:
      summary: Settlement By Country
      description: Settlement by country.
      operationId: getSettlementStatsByCountry
      x-api-path-slug: apiv1statssettlementby-country-get
      parameters:
      - in: query
        name: date_from
        description: Date from in yyyy-MM format
      - in: query
        name: date_to
        description: Date to in yyyy-MM format
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Country
  /api/v1/stats/transactions/by_country:
    get:
      summary: Settlement By Country
      description: Settlement by country.
      operationId: getTransactionsStatsByCountry
      x-api-path-slug: apiv1statstransactionsby-country-get
      parameters:
      - in: query
        name: date_from
        description: Date from in yyyy-MM format
      - in: query
        name: date_to
        description: Date to in yyyy-MM format
      - in: query
        name: global_currency_code
        description: Global currency code to use for conversion - in addition to countrys
          currency if rate is available
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Country
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