swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 1
info:
  title: AWS Redshift API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateCluster:
    get:
      summary: Create Cluster
      description: Creates a new cluster.
      operationId: createCluster
      x-api-path-slug: actioncreatecluster-get
      parameters:
      - in: query
        name: AdditionalInfo
        description: Reserved
        type: string
      - in: query
        name: AllowVersionUpgrade
        description: If true, major version upgrades can be applied during the maintenance            window
          to the Amazon Redshift engine that is running on the cluster
        type: string
      - in: query
        name: AutomatedSnapshotRetentionPeriod
        description: The number of days that automated snapshots are retained
        type: string
      - in: query
        name: AvailabilityZone
        description: The EC2 Availability Zone (AZ) in which you want Amazon Redshift
          to provision the            cluster
        type: string
      - in: query
        name: ClusterIdentifier
        description: A unique identifier for the cluster
        type: string
      - in: query
        name: ClusterParameterGroupName
        description: The name of the parameter group to be associated with this cluster
        type: string
      - in: query
        name: ClusterSecurityGroups.ClusterSecurityGroupName.N
        description: A list of security groups to be associated with this cluster
        type: string
      - in: query
        name: ClusterSubnetGroupName
        description: The name of a cluster subnet group to be associated with this
          cluster
        type: string
      - in: query
        name: ClusterType
        description: The type of the cluster
        type: string
      - in: query
        name: ClusterVersion
        description: The version of the Amazon Redshift engine software that you want
          to deploy on the            cluster
        type: string
      - in: query
        name: DBName
        description: The name of the first database to be created when the cluster
          is created
        type: string
      - in: query
        name: ElasticIp
        description: The Elastic IP (EIP) address for the cluster
        type: string
      - in: query
        name: Encrypted
        description: If true, the data in the cluster is encrypted at rest
        type: string
      - in: query
        name: EnhancedVpcRouting
        description: An option that specifies whether to create the cluster with enhanced
          VPC routing            enabled
        type: string
      - in: query
        name: HsmClientCertificateIdentifier
        description: Specifies the name of the HSM client certificate the Amazon Redshift
          cluster uses to           retrieve the data encryption keys stored in an
          HSM
        type: string
      - in: query
        name: HsmConfigurationIdentifier
        description: Specifies the name of the HSM configuration that contains the
          information the            Amazon Redshift cluster can use to retrieve and
          store keys in an HSM
        type: string
      - in: query
        name: IamRoles.IamRoleArn.N
        description: A list of AWS Identity and Access Management (IAM) roles that
          can be used by the            cluster to access other AWS services
        type: string
      - in: query
        name: KmsKeyId
        description: The AWS Key Management Service (KMS) key ID of the encryption
          key that you want to            use to encrypt data in the cluster
        type: string
      - in: query
        name: MasterUsername
        description: The user name associated with the master user account for the
          cluster that is being            created
        type: string
      - in: query
        name: MasterUserPassword
        description: The password associated with the master user account for the
          cluster that is being            created
        type: string
      - in: query
        name: NodeType
        description: The node type to be provisioned for the cluster
        type: string
      - in: query
        name: NumberOfNodes
        description: The number of compute nodes in the cluster
        type: string
      - in: query
        name: Port
        description: The port number on which the cluster accepts incoming connections
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range (in UTC) during which automated cluster
          maintenance can            occur
        type: string
      - in: query
        name: PubliclyAccessible
        description: If true, the cluster can be accessed from a public network
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tag instances
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of Virtual Private Cloud (VPC) security groups to be associated
          with the            cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DeleteCluster:
    get:
      summary: Delete Cluster
      description: Deletes a previously provisioned cluster.
      operationId: deleteCluster
      x-api-path-slug: actiondeletecluster-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The identifier of the cluster to be deleted
        type: string
      - in: query
        name: FinalClusterSnapshotIdentifier
        description: The identifier of the final snapshot that is to be created immediately
          before            deleting the cluster
        type: string
      - in: query
        name: SkipFinalClusterSnapshot
        description: Determines whether a final snapshot of the cluster is created
          before Amazon Redshift            deletes the cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeClusters:
    get:
      summary: Describe Clusters
      description: |-
        Returns properties of provisioned clusters including general cluster properties,
                    cluster database properties, maintenance and backup properties, and security and access
                    properties.
      operationId: describeClusters
      x-api-path-slug: actiondescribeclusters-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The unique identifier of a cluster whose properties you are requesting
        type: string
      - in: query
        name: Marker
        description: An optional parameter that specifies the starting point to return
          a set of response            records
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of response records to return in each call
        type: string
      - in: query
        name: TagKeys.TagKey.N
        description: A tag key or keys for which you want to return all matching clusters
          that are            associated with the specified key or keys
        type: string
      - in: query
        name: TagValues.TagValue.N
        description: A tag value or values for which you want to return all matching
          clusters that are            associated with the specified tag value or
          values
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeClusterVersions:
    get:
      summary: Describe Cluster Versions
      description: Returns descriptions of the available Amazon Redshift cluster versions.
      operationId: describeClusterVersions
      x-api-path-slug: actiondescribeclusterversions-get
      parameters:
      - in: query
        name: ClusterParameterGroupFamily
        description: The name of a specific cluster parameter group family to return
          details            for
        type: string
      - in: query
        name: ClusterVersion
        description: The specific cluster version to return
        type: string
      - in: query
        name: Marker
        description: An optional parameter that specifies the starting point to return
          a set of response            records
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of response records to return in each call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=ModifyCluster:
    get:
      summary: Modify Cluster
      description: Modifies the settings for a cluster.
      operationId: modifyCluster
      x-api-path-slug: actionmodifycluster-get
      parameters:
      - in: query
        name: AllowVersionUpgrade
        description: If true, major version upgrades will be applied automatically
          to the            cluster during the maintenance window
        type: string
      - in: query
        name: AutomatedSnapshotRetentionPeriod
        description: The number of days that automated snapshots are retained
        type: string
      - in: query
        name: ClusterIdentifier
        description: The unique identifier of the cluster to be modified
        type: string
      - in: query
        name: ClusterParameterGroupName
        description: The name of the cluster parameter group to apply to this cluster
        type: string
      - in: query
        name: ClusterSecurityGroups.ClusterSecurityGroupName.N
        description: A list of cluster security groups to be authorized on this cluster
        type: string
      - in: query
        name: ClusterType
        description: The new cluster type
        type: string
      - in: query
        name: ClusterVersion
        description: The new version number of the Amazon Redshift engine to upgrade
          to
        type: string
      - in: query
        name: ElasticIp
        description: The Elastic IP (EIP) address for the cluster
        type: string
      - in: query
        name: EnhancedVpcRouting
        description: An option that specifies whether to create the cluster with enhanced
          VPC routing            enabled
        type: string
      - in: query
        name: HsmClientCertificateIdentifier
        description: Specifies the name of the HSM client certificate the Amazon Redshift
          cluster uses to            retrieve the data encryption keys stored in an
          HSM
        type: string
      - in: query
        name: HsmConfigurationIdentifier
        description: Specifies the name of the HSM configuration that contains the
          information the            Amazon Redshift cluster can use to retrieve and
          store keys in an HSM
        type: string
      - in: query
        name: MasterUserPassword
        description: The new password for the cluster master user
        type: string
      - in: query
        name: NewClusterIdentifier
        description: The new identifier for the cluster
        type: string
      - in: query
        name: NodeType
        description: The new node type of the cluster
        type: string
      - in: query
        name: NumberOfNodes
        description: The new number of nodes of the cluster
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range (in UTC) during which system maintenance
          can occur, if            necessary
        type: string
      - in: query
        name: PubliclyAccessible
        description: If true, the cluster can be accessed from a public network
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of virtual private cloud (VPC) security groups to be associated
          with the            cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=RebootCluster:
    get:
      summary: Reboot Cluster
      description: Reboots a cluster.
      operationId: rebootCluster
      x-api-path-slug: actionrebootcluster-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The cluster identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters