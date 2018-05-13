{
  "info": {
    "name": "Halifax Bank Get Branches",
    "_postman_id": "627517df-c968-4765-9bcc-27d3e35b4b80",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "a93752be-2cb8-449d-b71f-2ba368bcd909",
          "name": "getBranches",
          "request": {
            "url": "http://api.halifax.co.uk/open-banking/v2.1/branches/",
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
              "id": "3c7db684-42b8-4d0f-858d-6515b27eeae5"
            }
          ]
        }
      ]
    }
  ]
}