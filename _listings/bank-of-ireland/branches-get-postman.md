{
  "info": {
    "name": "Bank of Ireland Get Branches",
    "_postman_id": "c7b77d3a-adcb-4424-8197-27ec26b2e618",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "1e658300-3e1c-4269-b5f8-5102bb40fa17",
          "name": "getBranches",
          "request": {
            "url": "http://openapi.bankofireland.com/open-banking/v2.1/branches/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6233d8e5-62eb-4684-8e2d-cadd9c6557aa"
            }
          ]
        }
      ]
    }
  ]
}