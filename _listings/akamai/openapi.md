---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config-media-live/v1/live/utils/countries:
    get:
      summary: List Countries
      description: List Countries
      operationId: configmedialivev1liveutilscountries
      x-api-path-slug: configmedialivev1liveutilscountries-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Countries
  /config-media-security/v1/security/countries:
    get:
      summary: List Countries
      description: List Countries
      operationId: configmediasecurityv1securitycountries
      x-api-path-slug: configmediasecurityv1securitycountries-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Countries
---