---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: 'Entertainment Express '
  description: Browse regions by country.
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Common/Countries/:
    get:
      summary: Returns a list of countries.
      description: List of Countries, ISO codes and Country IDs used throughout the
        API.
      operationId: GetCountries
      x-api-path-slug: commoncountries-get
      responses:
        200:
          description: OK
      tags:
      - Common
      - Countries
  /Analytics/Country/:
    get:
      summary: Get Viewers by Country.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsViewersByCountry
      x-api-path-slug: analyticscountry-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - Country
  /TvMedia/lineups/browse/{CountryID}:
    get:
      summary: ""
      description: Browse regions by country.
      operationId: GetTvMediaRegions
      x-api-path-slug: tvmedialineupsbrowsecountryid-get
      parameters:
      - in: path
        name: CountryID
        description: Country abbreviation
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
      - CountryID
  /TvMedia/lineups/browse/{CountryID}/{RegionID}:
    get:
      summary: ""
      description: Get service areas for a specific country and region.
      operationId: GetTvMediaServiceAreas
      x-api-path-slug: tvmedialineupsbrowsecountryidregionid-get
      parameters:
      - in: path
        name: CountryID
        description: Country abbreviation
      - in: path
        name: RegionID
        description: Region abbreviation
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
      - CountryID
      - RegionID
  /TvMedia/lineups/browse/{CountryID}/{RegionID}/{AreaID}:
    get:
      summary: ""
      description: Get lineups by AreaID.
      operationId: GetTvMediaLineupsByAreaID
      x-api-path-slug: tvmedialineupsbrowsecountryidregionidareaid-get
      parameters:
      - in: path
        name: AreaID
        description: Service area ID
      - in: path
        name: CountryID
        description: Country abbreviation
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: LineupType
        description: Filter by lineup type, valid types are OTA, SAT, CAB, IPTV
      - in: query
        name: ProviderId
        description: Filter by provider ID
      - in: path
        name: RegionID
        description: Region abbreviation
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
      - CountryID
      - RegionID
      - AreaID
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