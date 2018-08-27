swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeEcsClusters:
    get:
      summary: Describe Ecs Clusters
      description: Describes Amazon ECS clusters that are registered with a stack.
      operationId: describeEcsClusters
      x-api-path-slug: actiondescribeecsclusters-get
      parameters:
      - in: query
        name: EcsClusterArns
        description: A list of ARNs, one for each cluster to be described
        type: string
      - in: query
        name: MaxResults
        description: To receive a paginated response, use this parameter to specify
          the maximum number      of results to be returned with a single call
        type: string
      - in: query
        name: NextToken
        description: If the previous paginated request did not return all of the remaining
          results,      the response objectsNextToken parameter value is set to a
          token
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Ecs
      - Clusters