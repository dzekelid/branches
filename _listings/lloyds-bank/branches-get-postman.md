{
  "info": {
    "name": "Lloyds Bank Get Branches",
    "_postman_id": "156c6b98-1a8f-4e05-b2ef-64d0c6f77d66",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Branches",
      "item": [
        {
          "id": "fc37788e-0f24-4f70-9b82-e274a28f4efe",
          "name": "getBranches",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/branches/",
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
              "id": "e85ed5ff-5302-4bcc-89d0-f78581323c2d"
            }
          ]
        }
      ]
    }
  ]
}