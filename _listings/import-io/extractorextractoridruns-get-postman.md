{
  "info": {
    "name": "import.io Get Extractor Extractorid Runs",
    "_postman_id": "c697f966-3e2f-4d03-85ab-d04369930674",
    "description": "Get a feed of the runs performed on an extractor.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extractor",
      "item": [
        {
          "id": "d1885c57-0c4a-464b-a4c2-3967f5957ed2",
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
              "id": "7dddd96e-b02d-42ab-8f33-c86ab2c15a25"
            }
          ]
        },
        {
          "id": "12ab5696-82c0-483b-a470-cf5e687daf4e",
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
              "id": "bd51484d-ee19-4121-bda1-af81262fffab"
            }
          ]
        },
        {
          "id": "97a26086-56bc-48df-a354-dd4cef24b4ab",
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
              "id": "cf689c4a-d3c7-483d-9bd2-252aac526091"
            }
          ]
        },
        {
          "id": "855ff2ef-b810-4f1a-b2c8-ec42385c5bf8",
          "name": "getExtractorExtractorRuns",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/runs"
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
            "description": "Get a feed of the runs performed on an extractor."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd52a2c9-29db-4f04-8c6f-cb18707fa02d"
            }
          ]
        }
      ]
    }
  ]
}