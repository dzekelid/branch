{
  "info": {
    "name": "Dezrez Get a list of portal configurations for the brand within a branch.",
    "_postman_id": "2b1e7c3e-888a-4206-9abb-7c7c71e70839",
    "description": "Get a list of portal configurations for the brand within a branch..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "60f46dab-7ab3-4f7f-9ae7-1b0aa5b3ad0f",
          "name": "Agency_PortalConfigurationsBypageSizeBypageNumber",
          "request": {
            "url": "http://api.dezrez.com/api/agency/portalconfigurations?pageNumber=%7B%7D&pageSize=%7B%7D",
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
            "description": "Get a list of portal configurations for the brand within a branch.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b668960c-595d-4d1e-8ff6-094e2a38602c"
            }
          ]
        }
      ]
    }
  ]
}