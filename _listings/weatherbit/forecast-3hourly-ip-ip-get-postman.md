{
  "info": {
    "name": "Weatherbit Get Forecast 3hourly IP",
    "_postman_id": "f89796b6-f68c-48c6-80f9-cb1e97fe5c67",
    "description": "Returns a 3-hourly forecast, where each point represents a three hour   period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "9906b9ae-5853-4b08-9f91-b67c47a99a66",
          "name": "returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/3hourly?ip=:ip"
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
                  "id": "ip",
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
              "id": "55bbd0ef-283b-41cb-af36-5f4f1d68870b"
            }
          ]
        }
      ]
    }
  ]
}