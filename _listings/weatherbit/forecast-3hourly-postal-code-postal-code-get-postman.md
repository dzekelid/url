{
  "info": {
    "name": "Weatherbit Get Forecast 3hourly Postla Code Code",
    "_postman_id": "f3634ed8-1656-4ab0-9fd7-3783fb82d5b5",
    "description": "Returns a 3-hourly forecast, where each point represents a three hour period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "34731036-9ef0-482e-a0b8-06b67b95ef91",
          "name": "returns-a-3hourly-forecast-where-each-point-represents-a-three-hour-period-every-point-has-a-datetim",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/3hourly?postal_code=:postal_code"
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
                  "key": "days",
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
            "description": "Returns a 3-hourly forecast, where each point represents a three hour period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4168851-a335-4a11-93d9-7d61477af691"
            }
          ]
        }
      ]
    }
  ]
}