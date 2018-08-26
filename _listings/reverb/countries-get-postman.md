{
  "info": {
    "name": "reverb Get Countries",
    "_postman_id": "1fdfcd6a-4c34-4cbf-b83e-212110e93519",
    "description": "Retrieve a list of country codes with corresponding subregions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "fef517c9-6d1e-4c2a-8928-c04057a5f3f7",
          "name": "getCountries",
          "request": {
            "url": "http://api.reverb.com/api/countries",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list of country codes with corresponding subregions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcefcbe7-d9cf-4fcf-a27f-077f2ab49b52"
            }
          ]
        }
      ]
    }
  ]
}