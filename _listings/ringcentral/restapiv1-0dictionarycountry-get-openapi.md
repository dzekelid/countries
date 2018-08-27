---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Country List
  description: "Returns all the countries available for calling.\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nAGW-401\nAuthorization header is not specified\n\n\n401\nOAU-129\nAccess
    token corrupted"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/dictionary/country:
    get:
      summary: Get Country List
      description: "Returns all the countries available for calling.\nUsage Plan Group\nLight\nError
        Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [perPage] value is invalid\n\n\n401\nAGW-401\nAuthorization header is not
        specified\n\n\n401\nOAU-129\nAccess token corrupted"
      operationId: listCountries
      x-api-path-slug: restapiv1-0dictionarycountry-get
      parameters:
      - in: query
        name: freeSoftphoneLine
        description: Specifies if free phone line for softphone is available for a
          country or not
      - in: query
        name: loginAllowed
        description: Specifies whether login with the phone numbers of this country
          is enabled or not
      - in: query
        name: numberSelling
        description: Specifies if RingCentral sells phone numbers of this country
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: signupAllowed
        description: Indicates whether signup/billing is allowed for a country
      responses:
        200:
          description: OK
      tags:
      - Country
      - List
  /restapi/v1.0/dictionary/country/{countryId}:
    get:
      summary: Get Country
      description: "Returns the information on a specific country.\nUsage Plan Group\nLight\nError
        Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-122\nMethod
        is brand specific\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n404\nCMN-102\nResource
        for parameter [countryId] is not found"
      operationId: loadCountry
      x-api-path-slug: restapiv1-0dictionarycountrycountryid-get
      parameters:
      - in: path
        name: countryId
        description: Internal identifier of a country
      responses:
        200:
          description: OK
      tags:
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