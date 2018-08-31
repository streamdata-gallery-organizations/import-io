{
  "info": {
    "name": "import.io Get Extractor Extractorid",
    "_postman_id": "85c9a795-17a2-49db-9c5e-a7da6ac9d986",
    "description": "Query by extractor endpoint, adhoc runs only..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extractor",
      "item": [
        {
          "id": "ed492687-ce52-4584-868d-07d77097fac3",
          "name": "getExtractorExtractorCsvLatest",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/csv/latest"
              ],
              "variable": [
                {
                  "id": "extractorId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the latest crawl run results as a csv."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e79073f-4132-42b9-8ded-b930d5bdd6cb"
            }
          ]
        },
        {
          "id": "b1cd5cbd-4640-490b-9347-64f2fa23f3a4",
          "name": "getExtractorExtractorJsonLatest",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/json/latest"
              ],
              "variable": [
                {
                  "id": "extractorId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the latest crawl run results as json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "348e9984-7f6f-4c12-9251-447d6ed39958"
            }
          ]
        },
        {
          "id": "c6bcceac-0787-4a73-b560-770b019426ca",
          "name": "getExtractorExtractor",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId"
              ],
              "query": [
                {
                  "key": "url",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "extractorId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Query by extractor endpoint, adhoc runs only.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c0853f0-16e2-4f41-bfd0-be4455571c85"
            }
          ]
        }
      ]
    }
  ]
}