{
  "info": {
    "name": "Dezrez Get Branch administrators by its id.",
    "_postman_id": "2703ab49-08f8-4c34-8095-f12bfac8cb74",
    "description": "Get branch administrators by its id..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Branch",
      "item": [
        {
          "id": "d216ee00-5a98-48f1-a538-11096dd95a1d",
          "name": "Branch_AdministratorsByid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/branch/:id/administrators"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
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
            "description": "Get branch administrators by its id.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "149432ff-93b8-4d1f-b17b-29be7f13e704"
            }
          ]
        }
      ]
    }
  ]
}