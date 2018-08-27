---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Countries
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - List countries by sales price
  x-api-slug: restitemssales-pricesidcountries-get
  description: Lists active countries for a sales price. The ID of the sales price
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountries-get-openapi.md
- name: plentymarkets REST-API - List shipping countries
  x-api-slug: restordersshippingcountries-get
  description: List shipping countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restordersshippingcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restordersshippingcountries-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of a country
  x-api-slug: restaccountinglocationslocationidcountriescountryidrevenue-accounts-get
  description: Get the revenue account configuration of a country. The ID of the accounting
    location that the country is associated with as well as the ID of the country
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts for a country of a webstore
  x-api-slug: restaccountinglocationswebstoreidcountryidposting-accounts-get
  description: Get all posting accounts for a country of a webstore.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationswebstoreidcountryidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Activate a country
  x-api-slug: restitemssales-pricesidcountries-post
  description: Activates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountries-post-openapi.md
- name: plentymarkets REST-API - Deactivate a country
  x-api-slug: restitemssales-pricesidcountriescountryid-delete
  description: Deactivates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations for one country of delivery
  x-api-slug: restvatlocationslocationidcountriescountryid-get
  description: Lists the VAT configurations for a country of delivery of one accounting
    location. The ID of the accounting location and the ID of the country of delivery
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of a country
  x-api-slug: restaccountinglocationslocationidcountriescountryidrevenue-accounts-get
  description: Get the revenue account configuration of a country. The ID of the accounting
    location that the country is associated with as well as the ID of the country
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts for a country of a webstore
  x-api-slug: restaccountinglocationswebstoreidcountryidposting-accounts-get
  description: Get all posting accounts for a country of a webstore.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationswebstoreidcountryidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Activate a country
  x-api-slug: restitemssales-pricesidcountries-post
  description: Activates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountries-post-openapi.md
- name: plentymarkets REST-API - Deactivate a country
  x-api-slug: restitemssales-pricesidcountriescountryid-delete
  description: Deactivates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations for one country of delivery
  x-api-slug: restvatlocationslocationidcountriescountryid-get
  description: Lists the VAT configurations for a country of delivery of one accounting
    location. The ID of the accounting location and the ID of the country of delivery
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations for one country of delivery
  x-api-slug: restvatlocationslocationidcountriescountryid-get
  description: Lists the VAT configurations for a country of delivery of one accounting
    location. The ID of the accounting location and the ID of the country of delivery
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Deactivate a country
  x-api-slug: restitemssales-pricesidcountriescountryid-delete
  description: Deactivates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-openapi.md
- name: plentymarkets REST-API - Activate a country
  x-api-slug: restitemssales-pricesidcountries-post
  description: Activates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restitemssales-pricesidcountries-post-openapi.md
- name: plentymarkets REST-API - Get all posting accounts for a country of a webstore
  x-api-slug: restaccountinglocationswebstoreidcountryidposting-accounts-get
  description: Get all posting accounts for a country of a webstore.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationswebstoreidcountryidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of a country
  x-api-slug: restaccountinglocationslocationidcountriescountryidrevenue-accounts-get
  description: Get the revenue account configuration of a country. The ID of the accounting
    location that the country is associated with as well as the ID of the country
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/countries/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---