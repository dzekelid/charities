{
  "info": {
    "name": "Org Hunter Get details!",
    "_postman_id": "745bd66f-08f1-4b3e-95b3-880c51b4f94b",
    "description": "This operation detail data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charity",
      "item": [
        {
          "id": "15fa63e9-35c1-44de-9648-6ac6a4cb768c",
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
              "id": "ff894e77-9925-42fc-bc2c-484294eac485"
            }
          ]
        },
        {
          "id": "57d4595b-c6b7-45e2-b9ff-6522c19227a8",
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
              "id": "d3acbf81-eac3-4b8c-bcf3-bb46874dbacf"
            }
          ]
        },
        {
          "id": "5df79736-6d39-4bc7-99c1-485a436d1edb",
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
              "id": "044933b9-3362-4cba-b4e8-a5c658c0b1c2"
            }
          ]
        }
      ]
    }
  ]
}