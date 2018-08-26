{
  "info": {
    "name": "Org Hunter Get details!",
    "_postman_id": "d39c7709-24f7-4221-8ec9-ad3728798d12",
    "description": "This operation detail data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charity",
      "item": [
        {
          "id": "8dc7c2c6-bb05-4cf2-aa8b-39615c46c1b6",
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
              "id": "e8602d74-fb03-40e2-8095-68fef9305175"
            }
          ]
        },
        {
          "id": "2c307e18-85c8-42d0-88e4-d7c2e4e2590a",
          "name": "postV1Charitybasic",
          "request": {
            "url": "http://data.orghunter.com/v1/charitybasic?ein=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "This operation detail data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f5ce21e-d076-4450-abd9-1c6451a377ae"
            }
          ]
        }
      ]
    }
  ]
}