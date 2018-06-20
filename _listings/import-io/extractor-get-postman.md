{
  "info": {
    "name": "import.io Get Extractor",
    "_postman_id": "7c90c5ec-259c-4d74-9c96-587f728ca017",
    "description": "Get the list of schedules for all your extractors.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extractor",
      "item": [
        {
          "id": "a099233c-3a93-4cff-911c-ff3729911f11",
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
              "id": "e6262456-23bb-487d-8b55-158ee7e3281f"
            }
          ]
        },
        {
          "id": "a8d23e56-e20b-44bb-a85b-3d6d463c1dcc",
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
              "id": "6d7b63bc-8eeb-4c8d-81cf-e93ced4ac8c4"
            }
          ]
        },
        {
          "id": "2416f799-3db1-4040-9380-ab82391abccd",
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
              "id": "8a3a32f0-09b2-41d6-b610-31a8de00bc42"
            }
          ]
        },
        {
          "id": "b31f852a-03e6-4558-b752-b92bf18740f1",
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
              "id": "2f9dc4da-04d5-4631-bd36-3f0777c3175c"
            }
          ]
        },
        {
          "id": "a4f0ed8a-e859-4a9d-a5e4-a36afefa322e",
          "name": "postExtractorExtractorCancel",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/cancel"
              ],
              "variable": [
                {
                  "id": "extractorId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Cancel an existing crawl.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10492d48-de7d-4cfb-8d7f-762e499d5c86"
            }
          ]
        },
        {
          "id": "9cfc6feb-6c31-41c2-a398-074b25f9f523",
          "name": "postExtractorExtractorStart",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/start"
              ],
              "query": [
                {
                  "key": "loginSessionId",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Launch a crawl from an extractor that a user owns.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ba36464-4451-47d2-b69d-a93a03880f09"
            }
          ]
        },
        {
          "id": "c1fed8d2-c29d-475a-aac1-84e8411026ff",
          "name": "getExtractor",
          "request": {
            "url": "http://schedule.import.io/extractor",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the list of schedules for all your extractors."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9a18044-7794-434a-8016-11565796f218"
            }
          ]
        }
      ]
    }
  ]
}