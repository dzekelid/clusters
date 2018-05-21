---
swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 1
info:
  title: HDInsightManagementClient
  description: the-hdinsight-management-client
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
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}:
    put:
      summary: Clusters Create
      description: Begins creating a new HDInsight cluster with the specified parameters.
      operationId: Clusters_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclustername-put
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The cluster create request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters
    patch:
      summary: Clusters Update
      description: Patch HDInsight cluster with the specified parameters.
      operationId: Clusters_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclustername-patch
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The cluster patch request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters
    delete:
      summary: Clusters Delete
      description: Begins deleting the specified HDInsight cluster.
      operationId: Clusters_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclustername-delete
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters
    get:
      summary: Clusters Get
      description: Gets the specified cluster.
      operationId: Clusters_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclustername-get
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters:
    get:
      summary: Clusters List By Resource Group
      description: List the HDInsight clusters in a resource group.
      operationId: Clusters_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclusters-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters Resource Group
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/roles/{roleName}/resize
  : post:
      summary: Clusters Resize
      description: Begins a resize operation on the specified HDInsight cluster.
      operationId: Clusters_Resize
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclusternamerolesrolenameresize-post
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for the resize operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: roleName
        description: The constant value for the roleName
      responses:
        200:
          description: OK
      tags:
      - Clusters Resize
  /subscriptions/{subscriptionId}/providers/Microsoft.HDInsight/clusters:
    get:
      summary: Clusters List
      description: Lists HDInsight clusters under the subscription.
      operationId: Clusters_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosofthdinsightclusters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/changerdpsetting
  : post:
      summary: Clusters Change Rdp Settings
      description: Begins changing the RDP settings on the specified cluster.
      operationId: Clusters_ChangeRdpSettings
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclusternamechangerdpsetting-post
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The OS profile for RDP
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters Change Rdptings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/executeScriptActions
  : post:
      summary: Clusters Execute Script Actions
      description: Begins executing script actions on the specified HDInsight cluster.
      operationId: Clusters_ExecuteScriptActions
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosofthdinsightclustersclusternameexecutescriptactions-post
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for executing script actions
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Clusters Execute Script Actions
---