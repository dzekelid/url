{
  "info": {
    "name": "Go.USA.gov API Shortening a URL",
    "_postman_id": "3d860500-3a35-4dd9-9343-a7db24b3c479",
    "description": "Shortening a URL",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "url",
      "item": [
        {
          "id": "b2fcdb21-938d-4cff-83dc-fd2d92749c65",
          "name": "shortenURL",
          "request": {
            "url": "http://go.usa.gov/api/shorten.json?longURL=longURL",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Shortening a URL"
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
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "57994046-9692-44c4-a65b-8725fa859533"
            }
          ]
        }
      ]
    }
  ]
}