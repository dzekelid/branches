{
  "info": {
    "name": "Bank of Scotland Get Branches",
    "_postman_id": "22d1bfa4-fbe6-4e07-a47f-b8e757eb3d53",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "ebcc2158-d5c7-4411-8c69-c3c2522ea18e",
          "name": "getBranches",
          "request": {
            "url": "http://api.bankofscotland.co.uk/open-banking/v2.1/branches/",
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
              "id": "1d5e72b4-fa0e-4897-92fe-1262880d7b6b"
            }
          ]
        }
      ]
    }
  ]
}