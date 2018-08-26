---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 1
info:
  title: RingCentral Connect Platform API Explorer
  description: this-is-an-interactive-api-explorer-for-the-ringcentral-connect-platform--to-use-this-service-you-will-need-to-have-a-developer-account---links--a-hrefhttpsnetstorage-ringcentral-comdpwapiexplorerrcplatform-basic-ymlv20180514092722-target-blankringcentral-api-specaspannbspnbspopenapi-fka-swagger-formatnbspnbspnbspnbspspana-hrefhttpsgithub-comoaiopenapispecification-target-blanklearn-more-about-openapia
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
---