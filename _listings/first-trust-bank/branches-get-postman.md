{
  "info": {
    "name": "First Trust Bank (Open Banking) Get Branches",
    "_postman_id": "ea09aed4-3501-4aa0-a1e7-e049212f9140",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "cb447631-8e55-4943-a459-68ea953dfdc4",
          "name": "getBranches",
          "request": {
            "url": "http://openapi.firsttrustbank.co.uk/open-banking/v2.1/branches/",
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
              "id": "50c32c21-0646-4cfd-b795-6a7dda625275"
            }
          ]
        }
      ]
    }
  ]
}