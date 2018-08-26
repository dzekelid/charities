{
  "info": {
    "name": "Org Hunter Get categories!",
    "_postman_id": "08be85e1-7ef1-4eea-8ab1-e4d6761517c9",
    "description": "This operation provides a list of categories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charity",
      "item": [
        {
          "id": "e290bc09-7382-4be9-aedd-3b3fad04aafd",
          "name": "postV1Categories",
          "request": {
            "url": "http://data.orghunter.com/v1/categories",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "This operation provides a list of categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6d4b0c3-4da7-450b-9de8-ca066b88b230"
            }
          ]
        }
      ]
    }
  ]
}