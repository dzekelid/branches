{
  "info": {
    "name": "Danske Bank Get Branches",
    "_postman_id": "421abac1-e0fa-48b7-9966-97baee36e968",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "aabb2d9a-1783-4a8c-86fa-7154009e4518",
      "name": "getATMS",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/atms/",
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
          "id": "445f84f9-4f54-4fb0-a691-0612e5ce58e1"
        }
      ]
    },
    {
      "id": "5c3891fd-7b49-4cf2-830e-050935d9358b",
      "name": "getBranches",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/branches/",
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
          "id": "dda45a03-0853-4be1-8a2d-a2baaa6054eb"
        }
      ]
    }
  ]
}