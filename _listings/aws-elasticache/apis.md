---
name: AWS ElastiCache
x-slug: aws-elasticache
description: Amazon ElastiCache is a web service that makes it easy to deploy, operate,
  and scale an in-memory data store or cache in the cloud. The service improves the
  performance of web applications by allowing you to retrieve information from fast,
  managed, in-memory data stores, instead of relying entirely on slower disk-based
  databases. Amazon ElastiCache automatically detects and replaces failed nodes, reducing
  the overhead associated with self-managed infrastructures and provides a resilient
  system that mitigates the risk of overloaded databases, which slow website and application
  load times. Through integration with Amazon CloudWatch, Amazon ElastiCache provides
  enhanced visibility into key performance metrics associated with your Redis or Memcached
  nodes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
x-kinRank: "10"
x-alexaRank: ""
tags: Clusters
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon ElastiCache API Create Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: Creates a cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=CreateCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/actioncreatecachecluster-get-openapi.md
- name: Amazon ElastiCache API Delete Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: Deletes a previously provisioned cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DeleteCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/actiondeletecachecluster-get-openapi.md
- name: Amazon ElastiCache API Describe Cache Clusters
  x-api-slug: amazon-elasticache-api
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=DescribeCacheClusters
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: Amazon ElastiCache API Modify Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: Modifies the settings for a cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=ModifyCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/actionmodifycachecluster-get-openapi.md
- name: Amazon ElastiCache API Reboot Cache Cluster
  x-api-slug: amazon-elasticache-api
  description: |-
    Reboots some, or all, of the cache nodes
                within a provisioned cache cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: ://///?Action=RebootCacheCluster
  tags: Cache Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/actionrebootcachecluster-get-openapi.md
- name: Amazon ElastiCache API
  x-api-slug: amazon-elasticache-api
  description: Amazon ElastiCache is a web service that makes it easy to deploy, operate,
    and scale an in-memory data store or cache in the cloud. The service improves
    the performance of web applications by allowing you to retrieve information from
    fast, managed, in-memory data stores, instead of relying entirely on slower disk-based
    databases. Amazon ElastiCache automatically detects and replaces failed nodes,
    reducing the overhead associated with self-managed infrastructures and provides
    a resilient system that mitigates the risk of overloaded databases, which slow
    website and application load times. Through integration with Amazon CloudWatch,
    Amazon ElastiCache provides enhanced visibility into key performance metrics associated
    with your Redis or Memcached nodes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-elasticache/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/elasticache/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/elasticache/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticache/pricing/
- type: x-resources
  url: https://aws.amazon.com/elasticache/developer-resources/
- type: x-testimonials
  url: https://aws.amazon.com/elasticache/testimonials/
- type: x-website
  url: https://aws.amazon.com/elasticache/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---