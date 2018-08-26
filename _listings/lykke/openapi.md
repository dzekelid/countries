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
---