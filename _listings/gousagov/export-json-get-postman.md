{
  "info": {
    "name": "Go.USA.gov API Export URLs",
    "_postman_id": "466ecef3-f84c-45b7-9fdd-2bde339bf5cc",
    "description": "Get a List of All Short URLs",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "url",
      "item": [
        {
          "id": "b0794a88-5cde-49ef-aa5b-761a3a14bc3a",
          "name": "exportURLs",
          "request": {
            "url": "http://go.usa.gov/api/export.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a List of All Short URLs"
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
              "id": "84c50f77-e069-4570-aea2-825939e4dfe6"
            }
          ]
        }
      ]
    }
  ]
}