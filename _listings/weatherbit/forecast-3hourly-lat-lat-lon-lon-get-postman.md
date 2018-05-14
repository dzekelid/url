{
  "info": {
    "name": "Weatherbit Get Forecast 3hourly Lat & Lon",
    "_postman_id": "d11b928d-8bce-4477-b46a-f664dd8f4856",
    "description": "Returns a 3-hourly forecast, where each point represents a three hour   period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "ad5c9389-4857-460a-ab7d-7ed1923f431a",
          "name": "returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/3hourly?lat=:lat&lon=:lon"
              ],
              "query": [
                {
                  "key": "callback",
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
            "description": "Returns a 3-hourly forecast, where each point represents a three hour   period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d30dbc11-5e88-4bbe-9f34-8235cf25576f"
            }
          ]
        }
      ]
    }
  ]
}