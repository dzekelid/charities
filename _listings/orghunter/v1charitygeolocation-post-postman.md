{
  "info": {
    "name": "Org Hunter Get details!",
    "_postman_id": "f95e54fc-7316-41d7-a70b-143ac71f7fa1",
    "description": "This operation detail data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charity",
      "item": [
        {
          "id": "b25a312e-c34e-4918-b542-cc6b91bfad5f",
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
              "id": "408eb8c3-bdba-4918-bfe1-92e603c5f90f"
            }
          ]
        },
        {
          "id": "d9998daa-0941-49a0-a9ca-51670c496d86",
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
              "id": "df5e3f50-a0cf-4fa7-aedc-fcceae8b68b4"
            }
          ]
        },
        {
          "id": "f747c8c2-2be2-4f8c-b80b-1397d2df4025",
          "name": "postV1Charityfinancial",
          "request": {
            "url": "http://data.orghunter.com/v1/charityfinancial?ein=%7B%7D",
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
              "id": "6888533b-a252-4ba6-b089-17f1d8d1916d"
            }
          ]
        },
        {
          "id": "47ef11c6-aca2-426e-98d7-4dadffacffe8",
          "name": "postV1Charitygeolocation",
          "request": {
            "url": "http://data.orghunter.com/v1/charitygeolocation?ein=%7B%7D",
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
              "id": "cbb818ed-94b2-493b-b4f8-56ce344d6667"
            }
          ]
        }
      ]
    }
  ]
}