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
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/apis.md
specificationVersion: "0.14"
apis:
- name: HDInsightManagementClient - Clusters Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-put
  description: Begins creating a new HDInsight cluster with the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-put-openapi.md
- name: HDInsightManagementClient - Clusters Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-patch
  description: Patch HDInsight cluster with the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-patch-openapi.md
- name: HDInsightManagementClient - Clusters Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-delete
  description: Begins deleting the specified HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-delete-openapi.md
- name: HDInsightManagementClient - Clusters Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-get
  description: Gets the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclustername-get-openapi.md
- name: HDInsightManagementClient - Clusters List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-hdinsightclusters-get
  description: Lists HDInsight clusters under the subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidprovidersmicrosoft-hdinsightclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-hdinsight/subscriptionssubscriptionidprovidersmicrosoft-hdinsightclusters-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.event.hubs.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.hdinsight.stack.network
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