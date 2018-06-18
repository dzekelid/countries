---
swagger: "2.0"
x-collection-name: Open FinTech
x-complete: 1
info:
  title: Open FinTech
  description: openfintech-io-is-an-open-database-that-comprises-of-standardized-primary-data-for-fintech-industry--it-contains-such-information-as-geolocation-data-countries-cities-regions-organizations-currencies-national-digital-virtual-crypto-banks-digital-exchangers-payment-providers-psp-payment-methods-etc-it-is-created-for-communication-of-crossintegrated-microservices-on-one-language--this-is-achieved-through-standardization-of-entity-identifiers-that-are-used-to-exchange-information-among-different-services-
  version: "2017-08-24"
host: api.openfintech.io
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /countries:
    get:
      summary: List of countries
      description: Returns all available countries.
      operationId: countries.get
      x-api-path-slug: countries-get
      parameters:
      - in: query
        name: filter[region]
        description: Filtration by region
      - in: query
        name: filter[sub_region]
        description: Filtration by sub region
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || area
          | -area || population | -population || region | -region || sub_region |
          -sub_region |
      responses:
        200:
          description: OK
      tags:
      - Countries
  /countries/{id}:
    get:
      summary: Country by ID
      description: Returns country with specific ID.
      operationId: countries.id.get
      x-api-path-slug: countriesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Countries
---