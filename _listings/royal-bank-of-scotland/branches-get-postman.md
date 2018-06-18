{
  "info": {
    "name": "Royal Bank of Scotland Get Branches",
    "_postman_id": "9d96e975-989e-4564-b8f4-bb52720acb9a",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "a41fa366-3b84-4025-af51-197386d5dbc0",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/atms/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8519267a-5ce7-4a13-81b9-71a5102161b9"
        }
      ]
    },
    {
      "id": "a827ad47-79f7-43e1-9e0b-aa9875fd0c21",
      "name": "getBranches",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/branches/",
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
          "id": "53a05ee9-2a52-4baf-be32-96b223282921"
        }
      ]
    }
  ]
}