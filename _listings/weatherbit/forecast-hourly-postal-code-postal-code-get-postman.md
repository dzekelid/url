{
  "info": {
    "name": "Weatherbit Get Forecast Hourly Postla Code Code",
    "_postman_id": "10b346f2-74b2-4427-9029-da811295120e",
    "description": "**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast, where each point represents a one hour   period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "e8de50d7-c48b-45ac-9a74-7aae9be9c636",
          "name": "required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/hourly?postal_code=:postal_code"
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
                  "key": "hours",
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
            "description": "**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast, where each point represents a one hour   period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f57f438-b254-4d7a-a632-110a2ad4ae57"
            }
          ]
        }
      ]
    }
  ]
}