---
swagger: "2.0"
x-collection-name: Bitly
x-complete: 1
info:
  title: Bitly User Metrics API
  description: the-bitly-user-metrics-api
  termsOfService: http://dev.bitly.com/best_practices.html
  version: v3
host: api-ssl.bitly.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/user/countries:
    get:
      summary: User Countries
      description: Returns aggregate metrics about the countries referring click traffic
        to all of the authenticated users Bitlinks.
      operationId: userCountries
      x-api-path-slug: v3usercountries-get
      parameters:
      - in: query
        name: limit
        description: 1 to 1000 (default=100)
      - in: query
        name: rollup
        description: Return data for multiple units rolled up to a single result instead
          of a separate value for each period of time
      - in: query
        name: timezone
        description: 'an integer hour offset from UTC (-14 to 14), or a timezone string
          default: America/New_York'
      - in: query
        name: unit
        description: 'minute, hour, day, week or month, default: day'
      - in: query
        name: units
        description: Successful response
      - in: query
        name: unit_reference_ts
        description: 'an epoch timestamp, indicating the most recent time for which
          to pull metrics, default: now'
      responses:
        200:
          description: OK
      tags:
      - User
      - Countries
---