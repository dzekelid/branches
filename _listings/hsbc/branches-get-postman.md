{
  "info": {
    "name": "HSBC Get Branches",
    "_postman_id": "ae2d2ebc-b0f1-46e6-92de-e35574ae891c",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "c8c300b8-1ae5-451f-9a6c-06a8a4c11f3d",
          "name": "getBranches",
          "request": {
            "url": "http://api.hsbc.com/open-banking/v2.1/branches/",
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
              "id": "cd758991-1583-4c2d-a317-b7c47d1636e2"
            }
          ]
        }
      ]
    }
  ]
}