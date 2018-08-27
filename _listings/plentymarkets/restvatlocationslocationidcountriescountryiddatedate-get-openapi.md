---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get a VAT configuration for a country in a location.
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
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
    post:
      summary: Activate a country
      description: Activates a country for a sales price.
      operationId: postRestItemsSalesPricesCountries
      x-api-path-slug: restitemssales-pricesidcountries-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/countries
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Country
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
  /rest/orders/currencies/{currencyIso}/countries:
    get:
      summary: List countries for a currency
      description: List countries for a currency. The ISO 4271 code of the currency
        must be specified.
      operationId: getRestOrdersCurrenciesCurrencyisoCountries
      x-api-path-slug: restorderscurrenciescurrencyisocountries-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: currencyIso
      responses:
        200:
          description: OK
      tags:
      - List
      - Countriesa
      - Currency
  /rest/accounting/locations/{locationId}/countries/{countryId}/revenue_accounts:
    get:
      summary: Get the revenue account configuration of a country
      description: Get the revenue account configuration of a country. The ID of the
        accounting location that the country is associated with as well as the ID
        of the country must be specified.
      operationId: getRestAccountingLocationsLocationCountriesCountryRevenueAccounts
      x-api-path-slug: restaccountinglocationslocationidcountriescountryidrevenue-accounts-get
      parameters:
      - in: path
        name: countryId
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Revenue
      - Account
      - Configuration
      - Of
      - Country
  /rest/accounting/locations/{webstoreId}/{countryId}/posting_accounts:
    get:
      summary: Get all posting accounts for a country of a webstore
      description: Get all posting accounts for a country of a webstore.
      operationId: getRestAccountingLocationsWebstoreCountryAddingAccounts
      x-api-path-slug: restaccountinglocationswebstoreidcountryidposting-accounts-get
      parameters:
      - in: query
        name: $webstoreId
        description: The ID of the webstore
      - in: path
        name: countryId
      - in: path
        name: webstoreId
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accountsa
      - Country
      - Of
      - Webstore
  /rest/items/sales_prices/{id}/countries/{countryId}:
    delete:
      summary: Deactivate a country
      description: Deactivates a country for a sales price.
      operationId: deleteRestItemsSalesPricesCountriesCountry
      x-api-path-slug: restitemssales-pricesidcountriescountryid-delete
      parameters:
      - in: path
        name: countryId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Country
  /rest/orders/currencies/countries/{countryId}:
    get:
      summary: Get a currency for a country
      description: Get a currency for a country. The ID of the country must be specified.
      operationId: getRestOrdersCurrenciesCountriesCountry
      x-api-path-slug: restorderscurrenciescountriescountryid-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: countryId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Currencya
      - Country
  /rest/stores/{plentyId}/locations:
    get:
      summary: Get the ID of an accounting location of a country
      description: Gets the ID of an accounting location of a country. The plenty
        ID of the client and the ID of the country must be specified.
      operationId: getRestStoresPlentyLocations
      x-api-path-slug: reststoresplentyidlocations-get
      parameters:
      - in: query
        name: countryId
        description: The ID of the country of the accounting location
      - in: path
        name: plentyId
      responses:
        200:
          description: OK
      tags:
      - ID
      - Of
      - Accounting
      - Location
      - Of
      - Country
  /rest/vat/locations/{locationId}/countries/{countryId}:
    get:
      summary: List VAT configurations for one country of delivery
      description: Lists the VAT configurations for a country of delivery of one accounting
        location. The ID of the accounting location and the ID of the country of delivery
        must be specified.
      operationId: getRestVatLocationsLocationCountriesCountry
      x-api-path-slug: restvatlocationslocationidcountriescountryid-get
      parameters:
      - in: query
        name: columns[]
        description: The attributes of the VAT configuration
      - in: path
        name: countryId
      - in: path
        name: locationId
      - in: query
        name: with[]
        description: The relations to load with the VAT object
      responses:
        200:
          description: OK
      tags:
      - List
      - VAT
      - Configurationsone
      - Country
      - Of
      - Delivery
  /rest/vat/locations/{locationId}/countries/{countryId}/date/{date}:
    get:
      summary: Get a VAT configuration for a country in a location.
      description: Gets the VAT configuration found by matching the given location,
        delivery country and date of validity.
      operationId: getRestVatLocationsLocationCountriesCountryDateDate
      x-api-path-slug: restvatlocationslocationidcountriescountryiddatedate-get
      parameters:
      - in: query
        name: columns[]
        description: The attributes of the VAT configuration
      - in: path
        name: countryId
      - in: path
        name: date
      - in: path
        name: locationId
      - in: query
        name: startDate
        description: The date of validity
      - in: query
        name: with[]
        description: The relations to load with the VAT object
      responses:
        200:
          description: OK
      tags:
      - VAT
      - Configurationa
      - Country
      - In
      - Location
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