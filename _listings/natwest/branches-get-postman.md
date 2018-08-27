{
  "info": {
    "name": "NatWest Get Branches",
    "_postman_id": "21fe24f1-467b-499b-a805-2f88cfa11da1",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "e1bdefc0-3a3b-4e31-bd7e-4866f62f160f",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/atms/",
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
          "id": "18e04e71-ce70-4505-b19d-57f9b49d368f"
        }
      ]
    },
    {
      "id": "022aef65-8075-4384-bc5b-5e0afc30a33d",
      "name": "getBranches",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/branches/",
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
          "id": "f0928d78-4a98-4152-9329-e15fa65e5567"
        }
      ]
    }
  ]
}