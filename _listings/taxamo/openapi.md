swagger: "2.0"
x-collection-name: Taxamo
x-complete: 1
info:
  title: Taxamo
  description: taxamos-elegant-suite-of-apis-and-comprehensive-reporting-dashboard-enables-digital-merchants-to-easily-comply-with-eu-regulatory-requirements-on-tax-calculation-evidence-collection-tax-return-creation-and-data-storage-
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