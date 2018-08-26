{
  "info": {
    "name": "Dezrez Redact a Person by PersonId\r\nFirst request is just logged as an event \r\nSecond request must be by a branch admin and actually redacts the person",
    "_postman_id": "3100615f-c60d-4173-a691-23ddd9048ad9",
    "description": "Redact a person by personid\r\nfirst request is just logged as an event \r\nsecond request must be by a branch admin and actually redacts the person.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Redact",
      "item": [
        {
          "id": "9d8d9186-c247-4ec5-a197-175fb828a49c",
          "name": "People_RedactByidBynote",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/people/:id/redact"
              ],
              "query": [
                {
                  "key": "note",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Redact a person by personid\r\nfirst request is just logged as an event \r\nsecond request must be by a branch admin and actually redacts the person."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c32250b3-6deb-49c3-8f9c-a0d3927fd91b"
            }
          ]
        }
      ]
    }
  ]
}