---
swagger: "2.0"
x-collection-name: Import.io
x-complete: 0
info:
  title: import.io Post Extractor Extractorid Cancel
  version: "1.0"
  description: Cancel an existing crawl..
host: schedule.import.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /extractor/{extractorId}/csv/latest:
    get:
      summary: Get Extractor Extractorid Csv Latest
      description: Get the latest crawl run results as a csv.
      operationId: getExtractorExtractorCsvLatest
      x-api-path-slug: extractorextractoridcsvlatest-get
      parameters:
      - in: path
        name: extractorId
        description: the id of the extractor to start get the latest crawl run data
      responses:
        200:
          description: OK
      tags:
      - Extractor
      - ExtractorId
      - Csv
      - Latest
  /extractor/{extractorId}/json/latest:
    get:
      summary: Get Extractor Extractorid Json Latest
      description: Get the latest crawl run results as json.
      operationId: getExtractorExtractorJsonLatest
      x-api-path-slug: extractorextractoridjsonlatest-get
      parameters:
      - in: path
        name: extractorId
        description: The id of the extractor to start get the latest crawl run data
      responses:
        200:
          description: OK
      tags:
      - Extractor
      - ExtractorId
      - Json
      - Latest
  /extractor/{extractorId}:
    get:
      summary: Get Extractor Extractorid
      description: Query by extractor endpoint, adhoc runs only..
      operationId: getExtractorExtractor
      x-api-path-slug: extractorextractorid-get
      parameters:
      - in: path
        name: extractorId
        description: extractorId
      - in: query
        name: url
        description: url
      responses:
        200:
          description: OK
      tags:
      - Extractor
      - ExtractorId
  /extractor/{extractorId}/runs:
    get:
      summary: Get Extractor Extractorid Runs
      description: Get a feed of the runs performed on an extractor.
      operationId: getExtractorExtractorRuns
      x-api-path-slug: extractorextractoridruns-get
      parameters:
      - in: path
        name: extractorId
        description: The id of the extractor to start get the crawl run data
      responses:
        200:
          description: OK
      tags:
      - Extractor
      - ExtractorId
      - Runs
  /extractor/{extractorId}/cancel:
    post:
      summary: Post Extractor Extractorid Cancel
      description: Cancel an existing crawl..
      operationId: postExtractorExtractorCancel
      x-api-path-slug: extractorextractoridcancel-post
      parameters:
      - in: path
        name: extractorId
        description: extractorId
      responses:
        200:
          description: OK
      tags:
      - Extractor
      - ExtractorId
      - Cancel
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