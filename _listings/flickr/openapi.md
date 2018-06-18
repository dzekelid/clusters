---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.tags.getClusters:
    get:
      summary: Tags Get Clusters
      description: Returns a list of tag clusters for the given tag.
      operationId: getRestMethodFlickr.tags.getclusters
      x-api-path-slug: restmethodflickr-tags-getclusters-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: tag
        description: The tag to fetch clusters for
      responses:
        200:
          description: OK
      tags:
      - Tags
      - GetClusters
---