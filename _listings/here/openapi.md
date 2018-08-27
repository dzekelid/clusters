swagger: "2.0"
x-collection-name: HERE
x-complete: 1
info:
  title: Weather API
  description: the-here-weather-api-provides-weather-forecasts-and-reports-on-current-weather-conditions-provides-information-on-severe-weather-alerts-provides-information-about-when-the-sun-and-moon-rise-and-set-and-the-phase-of-the-moonthis-example-set-works-with-version-1-2-4-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-comrestapisdocumentationweather
  version: 1.0.0
host: weather.cit.api.here.com
basePath: /weather/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1:
    get:
      summary: Venue Clusters within a Bounding Box
      description: |-
        *Request an overview of the number venues across a large area*

        A bounding box is specified using the `bbox` parameter in the request URL.



        * **bbox**  `bbox`
         \- A type of spatial filter. A bounding box specifies the top-right and bottom left corners of an area to search.    e.g. `52.515,13.377;52.134,13.978`

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
      operationId: V1Get3
      x-api-path-slug: v1-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: bbox
      responses:
        200:
          description: OK
      tags:
      - Venue
      - Clusters
      - Within
      - Bounding
      - Box