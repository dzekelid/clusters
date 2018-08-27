swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/proxy/clusters/report:
    get:
      summary: Clusters Report
      description: Get Clusters report
      operationId: getClustersReportUsingGET
      x-api-path-slug: v1proxyclustersreport-get
      parameters:
      - in: query
        name: analysisId
        description: Analysis Id
      - in: query
        name: dataSourceName
        description: Data Source name
      - in: query
        name: filterOnlyUsedToCluster
        description: Filter Anomalies used to set create Clusters
      - in: query
        name: fromAnomaly
        description: Filter from Anomaly in Analysis
      - in: query
        name: toAnomaly
        description: Filter to Anomaly in Analysis
      - in: query
        name: withMinClusterSize
        description: Get only Clusters with minimum size
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Clusters
      - Report