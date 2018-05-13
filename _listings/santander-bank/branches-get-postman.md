{
  "info": {
    "name": "Santander Bank Get Branches",
    "_postman_id": "cea4e1b9-61f2-4642-ad53-b5c52e3feb6c",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "d1c73918-3dd3-428d-ae4e-8fb113e36212",
          "name": "getBranches",
          "request": {
            "url": "http://openapi.santander.co.uk/open-banking/v2.1/branches/",
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
              "id": "26e641fa-e51c-45cc-9516-85253a15b3ef"
            }
          ]
        }
      ]
    }
  ]
}