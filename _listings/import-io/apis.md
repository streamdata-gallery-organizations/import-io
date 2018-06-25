---
name: Import.io
x-slug: import-io
description: Home Page - Import.io - Web Scraping, Data Extraction and Web Harvesting
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
x-kinRank: "9"
x-alexaRank: "87026"
tags: Import.io
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/apis.md
specificationVersion: "0.14"
apis:
- name: import.io Get Extractor Extractorid Csv Latest
  x-api-slug: import-io
  description: Get the latest crawl run results as a csv.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/csv/latest
  tags: Extractor,ExtractorId,Csv,Latest
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridcsvlatest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridcsvlatest-get-openapi.md
- name: import.io Get Extractor Extractorid Json Latest
  x-api-slug: import-io
  description: Get the latest crawl run results as json.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/json/latest
  tags: Extractor,ExtractorId,Json,Latest
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridjsonlatest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridjsonlatest-get-openapi.md
- name: import.io Get Extractor Extractorid
  x-api-slug: import-io
  description: Query by extractor endpoint, adhoc runs only..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}
  tags: Extractor,ExtractorId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractorid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractorid-get-openapi.md
- name: import.io Get Extractor Extractorid Runs
  x-api-slug: import-io
  description: Get a feed of the runs performed on an extractor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/runs
  tags: Extractor,ExtractorId,Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridruns-get-openapi.md
- name: import.io Post Extractor Extractorid Cancel
  x-api-slug: import-io
  description: Cancel an existing crawl..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/cancel
  tags: Extractor,ExtractorId,Cancel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridcancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridcancel-post-openapi.md
- name: import.io Post Extractor Extractorid Start
  x-api-slug: import-io
  description: Launch a crawl from an extractor that a user owns..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/start
  tags: Extractor,ExtractorId,Start
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridstart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractoridstart-post-openapi.md
- name: import.io Get Extractor
  x-api-slug: import-io
  description: Get the list of schedules for all your extractors.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor
  tags: Extractor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractor-get-openapi.md
- name: import.io Post Extractor
  x-api-slug: import-io
  description: Schedule and extractor to run at a specific time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor
  tags: Extractor
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractor-post-openapi.md
- name: import.io Delete Extractor Extractorid
  x-api-slug: import-io
  description: Delete an existing schedule.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/
  tags: Extractor,ExtractorId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractorid-delete-openapi.md
- name: import.io Get Extractor Extractorid
  x-api-slug: import-io
  description: Get the schedule of a particular extractor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io////extractor/{extractorId}/
  tags: Extractor,ExtractorId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/extractorextractorid-get-openapi.md
- name: import.io
  x-api-slug: import-io
  description: import.io is a service that allows users to find data sources on the
    web for extraction, use, connect to, and remix the data for websites and applications.The
    import.io API allows developers to access and integrate the functionality of import.io
    with other applications. Some example API methods include retrieving data, importing
    data, extracting data, and managing account information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1728-import-io.jpg
  humanURL: https://www.import.io/
  baseURL: https://schedule.import.io//
  tags: Import.io
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/import-io/master/_listings/import-io/openapi.md
x-common:
- type: x-blog
  url: http://blog.import.io/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/importio
- type: x-crunchbase
  url: https://crunchbase.com/organization/importio
- type: x-email
  url: legal@import.io
- type: x-email
  url: support@import.io
- type: x-email
  url: copyright@import.io
- type: x-email
  url: hello@import.io
- type: x-github
  url: https://github.com/import-io
- type: x-pricing
  url: https://www.import.io/standard-plans/
- type: x-twitter
  url: https://twitter.com/importio
- type: x-website
  url: https://www.import.io/
- type: x-website
  url: http://import.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---