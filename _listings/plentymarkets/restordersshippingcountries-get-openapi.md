---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List shipping countries
  description: List shipping countries.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/sales_prices/{id}/countries:
    get:
      summary: List countries by sales price
      description: Lists active countries for a sales price. The ID of the sales price
        must be specified.
      operationId: getRestItemsSalesPricesCountries
      x-api-path-slug: restitemssales-pricesidcountries-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Countries
      - By
      - Sales
      - Price
  /rest/orders/shipping/countries:
    get:
      summary: List shipping countries
      description: List shipping countries.
      operationId: getRestOrdersShippingCountries
      x-api-path-slug: restordersshippingcountries-get
      parameters:
      - in: query
        name: active
        description: Returns only the active shipping countries
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Shipping
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