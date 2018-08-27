swagger: "2.0"
x-collection-name: Azure Service Fabric
x-complete: 1
info:
  title: ServiceFabricManagementClient
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters/{clusterName}:
    patch:
      summary: Clusters Update
      description: Update cluster configuration
      operationId: Clusters_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters which contains the property value and property
          name which used to update the cluster configuration
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clusters
    get:
      summary: Clusters Get
      description: Get cluster resource
      operationId: Clusters_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters
    put:
      summary: Clusters Create
      description: Create cluster resource
      operationId: Clusters_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Put Request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clusters
    delete:
      summary: Clusters Delete
      description: Delete cluster resource
      operationId: Clusters_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /subscriptions/{subscriptionId}/providers/Microsoft.ServiceFabric/clusters:
    get:
      summary: Clusters List
      description: List cluster resource
      operationId: Clusters_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-servicefabricclusters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters