swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/accounts/{accountId}/storeInfos/{videoId}/country/{country}:
    get:
      summary: Get Video Country
      description: |-
        Get a StoreInfo given its video id and country.

        See _Authentication and Authorization rules_ and
        _Get methods rules_ for more information about this method.
      operationId: playmoviespartner.accounts.storeInfos.country.get
      x-api-path-slug: v1accountsaccountidstoreinfosvideoidcountrycountry-get
      parameters:
      - in: path
        name: accountId
        description: REQUIRED
      - in: path
        name: country
        description: REQUIRED
      - in: path
        name: videoId
        description: REQUIRED
      responses:
        200:
          description: OK
      tags:
      - Country