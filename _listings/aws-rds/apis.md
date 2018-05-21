---
name: AWS RDS
x-slug: aws-rds
description: Amazon Relational Database Service (Amazon RDS) makes it easy to set
  up, operate, and scale arelational databasein the cloud. It provides cost-efficient
  and resizable capacity while managing time-consuming database administration tasks,
  freeing you up to focus on your applications and business. Amazon RDS provides you
  six familiar database engines to choose from, includingAmazon Aurora,PostgreSQL,MySQL,MariaDB,Oracle,
  andMicrosoft SQL Server.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
x-kinRank: "10"
x-alexaRank: ""
tags: Clusters
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon RDS API Add Role To D B Cluster
  x-api-slug: amazon-rds-api
  description: Associates an Identity and Access Management (IAM) role from an Aurora
    DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=AddRoleToDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actionaddroletodbcluster-get-openapi.md
- name: Amazon RDS API Create D B Cluster
  x-api-slug: amazon-rds-api
  description: Creates a new Amazon Aurora DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actioncreatedbcluster-get-openapi.md
- name: Amazon RDS API Delete D B Cluster
  x-api-slug: amazon-rds-api
  description: The DeleteDBCluster action deletes a previously provisioned DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actiondeletedbcluster-get-openapi.md
- name: Amazon RDS API Describe D B Clusters
  x-api-slug: amazon-rds-api
  description: Returns information about provisioned Aurora DB clusters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusters
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actiondescribedbclusters-get-openapi.md
- name: Amazon RDS API Failover D B Cluster
  x-api-slug: amazon-rds-api
  description: Forces a failover for a DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=FailoverDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actionfailoverdbcluster-get-openapi.md
- name: Amazon RDS API Modify D B Cluster
  x-api-slug: amazon-rds-api
  description: Modify a setting for an Amazon Aurora DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actionmodifydbcluster-get-openapi.md
- name: Amazon RDS API Remove Role From D B Cluster
  x-api-slug: amazon-rds-api
  description: Disassociates an Identity and Access Management (IAM) role from an
    Aurora DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RemoveRoleFromDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actionremoverolefromdbcluster-get-openapi.md
- name: Amazon RDS API Restore D B Cluster From S3
  x-api-slug: amazon-rds-api
  description: Creates an Amazon Aurora DB cluster from data stored in an Amazon S3
    bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBClusterFromS3
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actionrestoredbclusterfroms3-get-openapi.md
- name: Amazon RDS API Restore D B Cluster To Point In Time
  x-api-slug: amazon-rds-api
  description: Restores a DB cluster to an arbitrary point in time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBClusterToPointInTime
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/actionrestoredbclustertopointintime-get-openapi.md
- name: Amazon RDS API
  x-api-slug: amazon-rds-api
  description: Amazon Relational Database Service (Amazon RDS) makes it easy to set
    up, operate, and scale arelational databasein the cloud. It provides cost-efficient
    and resizable capacity while managing time-consuming database administration tasks,
    freeing you up to focus on your applications and business. Amazon RDS provides
    you six familiar database engines to choose from, includingAmazon Aurora,PostgreSQL,MySQL,MariaDB,Oracle,
    andMicrosoft SQL Server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: :///
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clusters/master/_listings/aws-rds/openapi.md
x-common:
- type: x-articles
  url: https://aws.amazon.com/articles/Amazon-RDS
- type: x-blog
  url: https://aws.amazon.com/blogs/database/
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=291
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=293
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/AmazonRDS/latest/CommandLineReference/
- type: x-customer-highlights
  url: https://aws.amazon.com/rds/customers/
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonRDS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/rds/faqs/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=60
- type: x-getting-started
  url: https://aws.amazon.com/rds/getting-started/
- type: x-partners
  url: https://aws.amazon.com/rds/partners/
- type: x-pricing
  url: https://aws.amazon.com/rds/pricing/
- type: x-service-level-agreement
  url: https://aws.amazon.com/rds/sla/
- type: x-tools
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=294
- type: x-website
  url: https://aws.amazon.com/rds/
- type: x-whats-new
  url: https://aws.amazon.com/rds/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---