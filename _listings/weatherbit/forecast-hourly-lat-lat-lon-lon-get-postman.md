{
  "info": {
    "name": "Weatherbit Get Forecast Hourly Lat & Lon",
    "_postman_id": "06752298-8bf0-4759-966f-4881ae162910",
    "description": "**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast, where each point represents a one hour period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "a7199559-d3db-4101-806a-eefdee07a24b",
          "name": "required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/hourly?lat=:lat&lon=:lon"
              ],
              "query": [
                {
                  "key": "callback",
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
                  "id": "lat",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lon",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast, where each point represents a one hour period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "816401dc-d344-44a6-b604-803e640d9245"
            }
          ]
        }
      ]
    }
  ]
}