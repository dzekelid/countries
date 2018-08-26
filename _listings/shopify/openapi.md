---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/countries.json:
    get:
      summary: Get a list of all countries
      description: Get a list of all countries.
      operationId: getAdminCountries.json
      x-api-path-slug: admincountries-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Countries
    post:
      summary: Create a country
      description: Create a country.
      operationId: postAdminCountries.json
      x-api-path-slug: admincountries-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Country
  /admin/countries/count.json:
    get:
      summary: Get a count of all countries
      description: Get a count of all countries.
      operationId: getAdminCountriesCount.json
      x-api-path-slug: admincountriescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Countries
  /admin/countries/444574734.json:
    put:
      summary: update a country
      description: Update a country.
      operationId: putAdminCountries444574734.json
      x-api-path-slug: admincountries444574734-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Country
    delete:
      summary: delete a country
      description: Delete a country.
      operationId: deleteAdminCountries444574734.json
      x-api-path-slug: admincountries444574734-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Delete
      - Country
  /admin/countries/261414723.json:
    get:
      summary: Show Country
      description: Show country.
      operationId: getAdminCountries261414723.json
      x-api-path-slug: admincountries261414723-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Show
      - Country
---