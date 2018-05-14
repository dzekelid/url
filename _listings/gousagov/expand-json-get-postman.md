{
  "info": {
    "name": "Go.USA.gov API Expand URL",
    "_postman_id": "a067b06b-2bac-43d7-97ed-9bf511dd72ff",
    "description": "Expand URL",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "url",
      "item": [
        {
          "id": "d8755041-9115-479a-a201-c1fe49d5240f",
          "name": "expandURL",
          "request": {
            "url": "http://go.usa.gov/api/expand.json?shortUrl=shortUrl",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Expand URL"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"shortUrl\": \"shortUrl\",\r\n    \"longUrl\": \"longUrl\",\r\n    \"dateCreated\": \"dateCreated\",\r\n    \"URLtitle\": \"URLtitle\",\r\n    \"URLdescription\": \"URLdescription\",\r\n    \"URLkeywords\": \"URLkeywords\",\r\n    \"user_clicks\": \"user_clicks\",\r\n    \"notes\": \"notes\"\r\n  }\r\n]",
              "status": "A successful response",
              "code": 200,
              "name": "Response_200",
              "id": "7291c223-924f-404a-82c5-c3efb0fb555a"
            }
          ]
        }
      ]
    }
  ]
}