---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Restore D B Cluster To Point In Time
  version: 1.0.0
  description: Restores a DB cluster to an arbitrary point in time.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddRoleToDBCluster:
    get:
      summary: Add Role To D B Cluster
      description: Associates an Identity and Access Management (IAM) role from an
        Aurora DB cluster.
      operationId: addroletodbcluster
      x-api-path-slug: actionaddroletodbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The name of the DB cluster to associate the IAM role with
        type: string
      - in: query
        name: RoleArn
        description: The Amazon Resource Name (ARN) of the IAM role to associate with
          the Aurora DB cluster, for example            arn:aws:iam::123456789012:role/AuroraAccessRole
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=CreateDBCluster:
    get:
      summary: Create D B Cluster
      description: Creates a new Amazon Aurora DB cluster.
      operationId: createdbcluster
      x-api-path-slug: actioncreatedbcluster-get
      parameters:
      - in: query
        name: AvailabilityZones.AvailabilityZone.N
        description: A list of EC2 Availability Zones that instances in the DB cluster
          can be created in
        type: string
      - in: query
        name: BackupRetentionPeriod
        description: The number of days for which automated backups are retained
        type: string
      - in: query
        name: CharacterSetName
        description: A value that indicates that the DB cluster should be associated
          with the specified CharacterSet
        type: string
      - in: query
        name: DatabaseName
        description: The name for your database of up to 8 alpha-numeric characters
        type: string
      - in: query
        name: DBClusterIdentifier
        description: The DB cluster identifier
        type: string
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to associate            with
          this DB cluster
        type: string
      - in: query
        name: DBSubnetGroupName
        description: A DB subnet group to associate with this DB cluster
        type: string
      - in: query
        name: Engine
        description: The name of the database engine to be used for this DB cluster
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the database engine to use
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier for an encrypted DB cluster
        type: string
      - in: query
        name: MasterUsername
        description: The name of the master user for the DB cluster
        type: string
      - in: query
        name: MasterUserPassword
        description: The password for the master database user
        type: string
      - in: query
        name: OptionGroupName
        description: A value that indicates that the DB cluster should be associated
          with the specified option group
        type: string
      - in: query
        name: Port
        description: The port number on which the instances in the DB cluster accept
          connections
        type: string
      - in: query
        name: PreferredBackupWindow
        description: The daily time range during which automated backups are created        if
          automated backups are enabled        using the BackupRetentionPeriod parameter
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: ReplicationSourceIdentifier
        description: The Amazon Resource Name (ARN) of the source DB cluster if this
          DB cluster is created as a Read Replica
        type: string
      - in: query
        name: StorageEncrypted
        description: Specifies whether the DB cluster is encrypted
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of EC2 VPC security groups to associate with this DB cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DeleteDBCluster:
    get:
      summary: Delete D B Cluster
      description: The DeleteDBCluster action deletes a previously provisioned DB
        cluster.
      operationId: deletedbcluster
      x-api-path-slug: actiondeletedbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The DB cluster identifier for the DB cluster to be deleted
        type: string
      - in: query
        name: FinalDBSnapshotIdentifier
        description: The DB cluster snapshot identifier of the new DB cluster snapshot
          created when SkipFinalSnapshot      is set to false
        type: string
      - in: query
        name: SkipFinalSnapshot
        description: Determines whether a final DB cluster snapshot is created before
          the DB cluster is deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeDBClusters:
    get:
      summary: Describe D B Clusters
      description: Returns information about provisioned Aurora DB clusters.
      operationId: describedbclusters
      x-api-path-slug: actiondescribedbclusters-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The user-supplied DB cluster identifier
        type: string
      - in: query
        name: Filters.Filter.N
        description: A filter that specifies one or more DB clusters to describe
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous            DescribeDBClusters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=FailoverDBCluster:
    get:
      summary: Failover D B Cluster
      description: Forces a failover for a DB cluster.
      operationId: failoverdbcluster
      x-api-path-slug: actionfailoverdbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: A DB cluster identifier to force a failover for
        type: string
      - in: query
        name: TargetDBInstanceIdentifier
        description: The name of the instance to promote to the primary instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=ModifyDBCluster:
    get:
      summary: Modify D B Cluster
      description: Modify a setting for an Amazon Aurora DB cluster.
      operationId: modifydbcluster
      x-api-path-slug: actionmodifydbcluster-get
      parameters:
      - in: query
        name: ApplyImmediately
        description: A value that specifies whether the modifications in this request
          and      any pending modifications are asynchronously applied      as soon
          as possible, regardless of the      PreferredMaintenanceWindow setting for
          the DB cluster
        type: string
      - in: query
        name: BackupRetentionPeriod
        description: The number of days for which automated backups are retained
        type: string
      - in: query
        name: DBClusterIdentifier
        description: The DB cluster identifier for the cluster being modified
        type: string
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to use for the DB
          cluster
        type: string
      - in: query
        name: MasterUserPassword
        description: The new password for the master database user
        type: string
      - in: query
        name: NewDBClusterIdentifier
        description: The new DB cluster identifier for the DB cluster when renaming
          a DB cluster
        type: string
      - in: query
        name: OptionGroupName
        description: A value that indicates that the DB cluster should be associated
          with the specified option group
        type: string
      - in: query
        name: Port
        description: The port number on which the DB cluster accepts connections
        type: string
      - in: query
        name: PreferredBackupWindow
        description: The daily time range during which automated backups are created            if
          automated backups are enabled,            using the BackupRetentionPeriod
          parameter
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A lst of VPC security groups that the DB cluster will belong
          to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=RemoveRoleFromDBCluster:
    get:
      summary: Remove Role From D B Cluster
      description: Disassociates an Identity and Access Management (IAM) role from
        an Aurora DB cluster.
      operationId: removerolefromdbcluster
      x-api-path-slug: actionremoverolefromdbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The name of the DB cluster to disassociate the IAM role rom
        type: string
      - in: query
        name: RoleArn
        description: The Amazon Resource Name (ARN) of the IAM role to disassociate
          from the Aurora DB cluster, for example        arn:aws:iam::123456789012:role/AuroraAccessRole
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=RestoreDBClusterFromS3:
    get:
      summary: Restore D B Cluster From S3
      description: Creates an Amazon Aurora DB cluster from data stored in an Amazon
        S3 bucket.
      operationId: restoredbclusterfroms3
      x-api-path-slug: actionrestoredbclusterfroms3-get
      parameters:
      - in: query
        name: AvailabilityZones.AvailabilityZone.N
        description: A list of EC2 Availability Zones that instances in the restored
          DB cluster can be created in
        type: string
      - in: query
        name: BackupRetentionPeriod
        description: The number of days for which automated backups of the restored
          DB cluster are retained
        type: string
      - in: query
        name: CharacterSetName
        description: A value that indicates that the restored DB cluster should be
          associated with the specified CharacterSet
        type: string
      - in: query
        name: DatabaseName
        description: The database name for the restored DB cluster
        type: string
      - in: query
        name: DBClusterIdentifier
        description: The name of the DB cluster to create from the source data in
          the S3 bucket
        type: string
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to associate            with
          the restored DB cluster
        type: string
      - in: query
        name: DBSubnetGroupName
        description: A DB subnet group to associate with the restored DB cluster
        type: string
      - in: query
        name: Engine
        description: The name of the database engine to be used for the restored DB
          cluster
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the database engine to use
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier for an encrypted DB cluster
        type: string
      - in: query
        name: MasterUsername
        description: The name of the master user for the restored DB cluster
        type: string
      - in: query
        name: MasterUserPassword
        description: The password for the master database user
        type: string
      - in: query
        name: OptionGroupName
        description: A value that indicates that the restored DB cluster should be
          associated with the specified option group
        type: string
      - in: query
        name: Port
        description: The port number on which the instances in the restored DB cluster
          accept connections
        type: string
      - in: query
        name: PreferredBackupWindow
        description: The daily time range during which automated backups are created            if
          automated backups are enabled            using the BackupRetentionPeriod
          parameter
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: S3BucketName
        description: The name of the Amazon S3 bucket that contains the data used
          to create the Amazon Aurora DB cluster
        type: string
      - in: query
        name: S3IngestionRoleArn
        description: The Amazon Resource Name (ARN) of the AWS Identity and Access
          Management (IAM) role that authorizes        Amazon RDS to access the Amazon
          S3 bucket on your behalf
        type: string
      - in: query
        name: S3Prefix
        description: The prefix for all of the file names that contain the data used
          to create the Amazon Aurora DB cluster
        type: string
      - in: query
        name: SourceEngine
        description: The identifier for the database engine that was backed up to
          create the files stored in the            Amazon S3 bucket
        type: string
      - in: query
        name: SourceEngineVersion
        description: The version of the database that the backup files were created
          from
        type: string
      - in: query
        name: StorageEncrypted
        description: Specifies whether the restored DB cluster is encrypted
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of EC2 VPC security groups to associate with the restored
          DB cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=RestoreDBClusterToPointInTime:
    get:
      summary: Restore D B Cluster To Point In Time
      description: Restores a DB cluster to an arbitrary point in time.
      operationId: restoredbclustertopointintime
      x-api-path-slug: actionrestoredbclustertopointintime-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The name of the new DB cluster to be created
        type: string
      - in: query
        name: DBSubnetGroupName
        description: The DB subnet group name to use for the new DB cluster
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier to use when restoring an encrypted DB
          cluster from an encrypted DB cluster
        type: string
      - in: query
        name: OptionGroupName
        description: The name of the option group for the new DB cluster
        type: string
      - in: query
        name: Port
        description: The port number on which the new DB cluster accepts connections
        type: string
      - in: query
        name: RestoreToTime
        description: The date and time to restore the DB cluster to
        type: string
      - in: query
        name: SourceDBClusterIdentifier
        description: The identifier of the source DB cluster from which to restore
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: UseLatestRestorableTime
        description: A value that is set to true to restore the DB cluster to the
          latest       restorable backup time, and false otherwise
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A lst of VPC security groups that the new DB cluster belongs
          to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---