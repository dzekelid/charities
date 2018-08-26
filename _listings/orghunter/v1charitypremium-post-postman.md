{
  "info": {
    "name": "Org Hunter Get details!",
    "_postman_id": "424f2333-bfea-461f-bc08-489dac67123a",
    "description": "This operation detail data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Charity",
      "item": [
        {
          "id": "90231d97-cbb2-493c-ba4f-1b375a48c2c9",
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
              "id": "57652d7a-9f13-47a1-b20b-d215dddc593a"
            }
          ]
        },
        {
          "id": "cc2c3046-836d-420b-870e-846d8becbf5d",
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
              "id": "03c5be42-576b-4893-b048-68f5d5e7cfd7"
            }
          ]
        },
        {
          "id": "b40b7d93-6968-4a67-a106-ff6a8af2c068",
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
              "id": "d381a8df-76f8-4b05-9865-3f916e5b7c8e"
            }
          ]
        },
        {
          "id": "abe6bdad-f30e-47ff-b81b-61c6e35f4590",
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
              "id": "607a0bbe-5bb8-4336-8c95-77f8640da03f"
            }
          ]
        },
        {
          "id": "e75cff46-35ed-4478-8f50-f1f4d66b41a8",
          "name": "postV1Charitypremium",
          "request": {
            "url": "http://data.orghunter.com/v1/charitypremium?ein=%7B%7D",
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
              "id": "f90ee230-b1fc-4135-93be-b93a3903d320"
            }
          ]
        }
      ]
    }
  ]
}