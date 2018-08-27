swagger: "2.0"
x-collection-name: Transavia
x-complete: 1
info:
  title: Routes API v3
  description: returns-all-available-routes
  version: 1.0.0
host: tst.api.transavia.com
basePath: /v3/routes
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /countrycode/{countryCode}:
    get:
      summary: Get Country Codes
      description: Retrieve airports by country code.
      operationId: countrycode.countryCode.get
      x-api-path-slug: countrycodecountrycode-get
      parameters:
      - in: path
        name: countryCode
        description: Comma-separated list of country codes (2-character ISO 3166-1)
      responses:
        200:
          description: OK
      tags:
      - Airports
      - Countrycode