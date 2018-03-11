---
swagger: "2.0"
info:
  title: Accelerated Mobile Pages (AMP) URL
  description: This API contains a single method, batchGet. Call this method to retrieve
    the AMP URL (and equivalent AMP Cache URL) for given public URL(s).
  contact:
    name: Google
    url: https://google.com
  version: v1
host: acceleratedmobilepageurl.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/ampUrls:batchGet:
    post:
      summary: ""
      description: |-
        Returns AMP URL(s) and equivalent
        [AMP Cache URL(s)](/amp/cache/overview#amp-cache-url-format)
      operationId: acceleratedmobilepageurl.ampUrls.batchGet
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - amp urls
definitions:
  AmpUrl:
    properties:
      ampUrl:
        description: This is a default description.
        type: post
      cdnAmpUrl:
        description: This is a default description.
        type: post
      originalUrl:
        description: This is a default description.
        type: post
  AmpUrlError:
    properties:
      errorCode:
        description: This is a default description.
        type: post
      errorMessage:
        description: This is a default description.
        type: post
      originalUrl:
        description: This is a default description.
        type: post
  BatchGetAmpUrlsRequest:
    properties:
      lookupStrategy:
        description: This is a default description.
        type: post
      urls:
        description: This is a default description.
        type: post
  BatchGetAmpUrlsResponse:
    properties:
      ampUrls:
        description: This is a default description.
        type: post
      urlErrors:
        description: This is a default description.
        type: post
x-collection-name: Accelerated Mobile Pages (AMP) URL
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---