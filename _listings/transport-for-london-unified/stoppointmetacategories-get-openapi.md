---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Stop Point  Meta  Categories
  description: Gets the list of available stoppoint additional information categories.
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Line/Meta/DisruptionCategories:
    get:
      summary: Line  Meta  Disruption Categories
      description: Gets a list of valid disruption categories.
      operationId: Line_MetaDisruptionCategories
      x-api-path-slug: linemetadisruptioncategories-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Disruption
      - Categories
  /Place/Meta/Categories:
    get:
      summary: Place  Meta  Categories
      description: Gets a list of all of the available place property categories and
        keys..
      operationId: Place_MetaCategories
      x-api-path-slug: placemetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Meta
      - ""
      - Categories
  /Road/Meta/Categories:
    get:
      summary: Road  Meta  Categories
      description: Gets a list of valid roaddisruption categories.
      operationId: Road_MetaCategories
      x-api-path-slug: roadmetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Road
      - ""
      - Meta
      - ""
      - Categories
  /Search/Meta/Categories:
    get:
      summary: Search  Meta  Categories
      description: Gets the available search categories..
      operationId: Search_MetaCategories
      x-api-path-slug: searchmetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Search
      - ""
      - Meta
      - ""
      - Categories
  /StopPoint/Meta/Categories:
    get:
      summary: Stop Point  Meta  Categories
      description: Gets the list of available stoppoint additional information categories.
      operationId: StopPoint_MetaCategories
      x-api-path-slug: stoppointmetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - ""
      - Meta
      - ""
      - Categories
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