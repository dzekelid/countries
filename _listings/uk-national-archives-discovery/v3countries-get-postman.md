{
  "info": {
    "name": "Getty Images Search API Get Countries",
    "_postman_id": "cdedf13f-3c34-4668-a582-01f077b6a655",
    "description": "Gets countries codes and names..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "e73453e0-75d3-40e6-95d5-705352c89505",
          "name": "getV3Countries",
          "request": {
            "url": "http://api.gettyimages.com/v3/countries",
            "method": "GET",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Specifies the language of result values",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Provide access token in the format of Bearer {token}",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets countries codes and names.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "178cfa3b-6ca5-4bdd-8b1e-eceeb6e168a2"
            }
          ]
        }
      ]
    }
  ]
}