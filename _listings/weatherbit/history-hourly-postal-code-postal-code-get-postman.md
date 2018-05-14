{
  "info": {
    "name": "Weatherbit Get History Hourly Postal Code",
    "_postman_id": "dfd64745-925a-47c7-acab-a8a3ab43c9a9",
    "description": "Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "cfc8f481-29b2-4fa3-aa34-d10dc5922b42",
          "name": "returns-historical-observations--given-a-postal-code-limit-1-day-for-low-volume-plans-limit-7-days-f",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "history/hourly?postal_code=:postal_code"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "country",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "end_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "lang",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "units",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "postal_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns Historical Observations - Given a Postal Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeeb6b16-a37f-434c-b48a-6aab14f38f29"
            }
          ]
        }
      ]
    }
  ]
}