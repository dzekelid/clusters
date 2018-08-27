---
name: AWS Redshift
x-slug: aws-redshift
description: Amazon Redshift is a fast, fully managed, petabyte-scaledata warehousethat
  makes it simple and cost-effective to analyze all your data using your existing
  business intelligence tools. Start small for $0.25 per hour with no commitments
  and scale to petabytes for $1,000 per terabyte per year, less than a tenth the cost
  of traditional solutions. Customers typically see 3x compression, reducing their
  costs to $333 per uncompressed terabyte per year.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Clusters
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Redshift API - Create Cluster
  x-api-slug: actioncreatecluster-get
  description: Creates a new cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
  humanURL: https://aws.amazon.com/redshift/
  baseURL: :///
  tags: Amazon Web Services, Data, Data Warehouse, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/actioncreatecluster-get-openapi.md
- name: AWS Redshift API - Delete Cluster
  x-api-slug: actiondeletecluster-get
  description: Deletes a previously provisioned cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
  humanURL: https://aws.amazon.com/redshift/
  baseURL: :///
  tags: Amazon Web Services, Data, Data Warehouse, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/actiondeletecluster-get-openapi.md
- name: AWS Redshift API - Describe Clusters
  x-api-slug: actiondescribeclusters-get
  description: |-
    Returns properties of provisioned clusters including general cluster properties,
                cluster database properties, maintenance and backup properties, and security and access
                properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
  humanURL: https://aws.amazon.com/redshift/
  baseURL: :///
  tags: Amazon Web Services, Data, Data Warehouse, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/actiondescribeclusters-get-openapi.md
- name: AWS Redshift API - Describe Cluster Versions
  x-api-slug: actiondescribeclusterversions-get
  description: Returns descriptions of the available Amazon Redshift cluster versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
  humanURL: https://aws.amazon.com/redshift/
  baseURL: :///
  tags: Amazon Web Services, Data, Data Warehouse, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/actiondescribeclusterversions-get-openapi.md
- name: AWS Redshift API - Modify Cluster
  x-api-slug: actionmodifycluster-get
  description: Modifies the settings for a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
  humanURL: https://aws.amazon.com/redshift/
  baseURL: :///
  tags: Amazon Web Services, Data, Data Warehouse, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/actionmodifycluster-get-openapi.md
- name: AWS Redshift API - Reboot Cluster
  x-api-slug: actionrebootcluster-get
  description: Reboots a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRedshift.png
  humanURL: https://aws.amazon.com/redshift/
  baseURL: :///
  tags: Amazon Web Services, Data, Data Warehouse, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-redshift/actionrebootcluster-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.rds.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.redshift.stack.network
- type: x-best-practices
  url: https://aws.amazon.com/redshift/developer-resources/#best-practices
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/redshift/index.html
- type: x-customer-success
  url: https://aws.amazon.com/redshift/customer-success/
- type: x-documentation
  url: http://docs.aws.amazon.com/redshift/latest/APIReference/
- type: x-events
  url: https://aws.amazon.com/redshift/events/
- type: x-faq
  url: https://aws.amazon.com/redshift/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/redshift/getting-started/
- type: x-partners
  url: https://aws.amazon.com/redshift/partners/
- type: x-pricing
  url: https://aws.amazon.com/redshift/pricing/
- type: x-website
  url: https://aws.amazon.com/redshift/
- type: x-whats-new
  url: https://aws.amazon.com/redshift/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---