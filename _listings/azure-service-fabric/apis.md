---
name: Azure Service Fabric
x-slug: azure-service-fabric
description: Service Fabric is a microservices platform used to build scalable, reliable,
  and easily managed applications for the cloud. Addressing the significant challenges
  in developing and managing cloud applications, Service Fabric allows developers
  and administrators to avoid solving complex infrastructure problems and focus instead
  on implementing mission-critical, demanding workloads.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Clusters
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/apis.md
specificationVersion: "0.14"
apis:
- name: ServiceFabricManagementClient - Clusters Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-patch
  description: Update cluster configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com//
  tags: Applications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-patch-openapi.md
- name: ServiceFabricManagementClient - Clusters Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-get
  description: Get cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com//
  tags: Applications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-get-openapi.md
- name: ServiceFabricManagementClient - Clusters Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-put
  description: Create cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com//
  tags: Applications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-put-openapi.md
- name: ServiceFabricManagementClient - Clusters Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-delete
  description: Delete cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com//
  tags: Applications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicefabricclustersclustername-delete-openapi.md
- name: ServiceFabricManagementClient - Clusters List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-servicefabricclusters-get
  description: List cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com//
  tags: Applications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidprovidersmicrosoft-servicefabricclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/azure-service-fabric/subscriptionssubscriptionidprovidersmicrosoft-servicefabricclusters-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.service.bus.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.service.fabric.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-fabric/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-fabric/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-fabric/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-fabric/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---