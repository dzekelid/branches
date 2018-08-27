{
  "info": {
    "name": "Barclays Get Branches",
    "_postman_id": "ce97c7af-0bdc-4522-8032-73011113d5c9",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Branches",
      "item": [
        {
          "id": "9195cec5-4c98-493d-83dc-3c47cce6833b",
          "name": "getBranches",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/branches/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7957e47-6446-4a5f-944b-28007ab96710"
            }
          ]
        }
      ]
    }
  ]
}