{
  "info": {
    "name": "Go.USA.gov API URL Clicks",
    "_postman_id": "447f4539-790e-404a-a8dd-6e0f3985c96b",
    "description": "Get the Number of Clicks on a Short URL",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "url",
      "item": [
        {
          "id": "2b993f09-3a20-4322-a819-90258e3e293a",
          "name": "urlClicks",
          "request": {
            "url": "http://go.usa.gov/api/clicks.json?shortUrl=shortUrl",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the Number of Clicks on a Short URL"
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
              "id": "8cb349a1-61dc-4e74-8171-b05ffc971243"
            }
          ]
        }
      ]
    }
  ]
}