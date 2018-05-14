{
  "info": {
    "name": "Google URL Shortener API Get Short URLs",
    "_postman_id": "a3b6a536-e567-4783-9f2a-e6a2e86ab65e",
    "description": "Expands a short URL or gets creation time and analytics.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "short url",
      "item": [
        {
          "id": "c1c8f6ea-8a52-4b69-98df-b7bb4227d098",
          "name": "urlshortener.url.get",
          "request": {
            "url": "http://www.googleapis.com/urlshortener/v1/url?projection=%7B%7D&shortUrl=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Expands a short URL or gets creation time and analytics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b5b4e64-26fa-426d-8a7a-ddcf1159ad1c"
            }
          ]
        }
      ]
    }
  ]
}