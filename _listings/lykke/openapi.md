---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
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
---