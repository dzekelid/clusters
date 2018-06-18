---
name: Azure HDInsight
x-slug: azure-hdinsight
description: Azure HDInsight is a Hadoop-based service that brings an Apache Hadoop
  solution to the cloud. Gain the full value of big data with a cloud-based data platform
  that manages data of any type and size.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Clusters
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/apis.md
specificationVersion: "0.14"
apis:
- name: Azure HDInsight API Clusters Create
  x-api-slug: azure-hdinsight-api
  description: Begins creating a new HDInsight cluster with the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-put-openapi.md
- name: Azure HDInsight API Clusters Update
  x-api-slug: azure-hdinsight-api
  description: Patch HDInsight cluster with the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-patch-openapi.md
- name: Azure HDInsight API Clusters Delete
  x-api-slug: azure-hdinsight-api
  description: Begins deleting the specified HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-delete-openapi.md
- name: Azure HDInsight API Clusters Get
  x-api-slug: azure-hdinsight-api
  description: Gets the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-get-openapi.md
- name: Azure HDInsight API Clusters List By Resource Group
  x-api-slug: azure-hdinsight-api
  description: List the HDInsight clusters in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters
  tags: Clusters Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclusters-get-openapi.md
- name: Azure HDInsight API Clusters Resize
  x-api-slug: azure-hdinsight-api
  description: Begins a resize operation on the specified HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/roles/{roleName}/resize
  tags: Clusters Resize
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamerolesrolenameresize-post-openapi.md
- name: Azure HDInsight API Clusters List
  x-api-slug: azure-hdinsight-api
  description: Lists HDInsight clusters under the subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.HDInsight/clusters
  tags: Clusters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidprovidersmicrosoft-hdinsightclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidprovidersmicrosoft-hdinsightclusters-get-openapi.md
- name: Azure HDInsight API Clusters Change Rdp Settings
  x-api-slug: azure-hdinsight-api
  description: Begins changing the RDP settings on the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/changerdpsetting
  tags: Clusters Change Rdptings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamechangerdpsetting-post-openapi.md
- name: Azure HDInsight API Clusters Execute Script Actions
  x-api-slug: azure-hdinsight-api
  description: Begins executing script actions on the specified HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/executeScriptActions
  tags: Clusters Execute Script Actions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameexecutescriptactions-post-openapi.md
- name: Azure HDInsight API
  x-api-slug: azure-hdinsight-api
  description: Azure HDInsight is a Hadoop-based service that brings an Apache Hadoop
    solution to the cloud. Gain the full value of big data with a cloud-based data
    platform that manages data of any type and size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/hdinsight/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/hdinsight/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/hdinsight/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/hdinsight/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---