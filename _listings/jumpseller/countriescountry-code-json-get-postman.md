{
  "info": {
    "name": "Jumpseller Get Countries Country Code",
    "_postman_id": "0dcc09bf-8433-47da-94ed-22abcdeea847",
    "description": "Retrieve a single country information..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "09348299-b2cf-4a13-87dc-cc9e679768b6",
          "name": "getCountriesCountryCode.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "countries/:country_code.json"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "country_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a single country information.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2fcf28a5-ff82-495e-ba3b-cc2f55310e4d"
            }
          ]
        }
      ]
    }
  ]
}