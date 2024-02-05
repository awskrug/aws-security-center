# Database

## [RDS](https://aws.amazon.com/ko/rds/?nc2=h_m1)

Amazon Relational Database Service(RDS)를 사용하면 클라우드에서 관계형 데이터베이스를 간편하게 설정, 운영 및 확장할 수 있습니다. RDS의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon RDS의 보안](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/UsingWithRDS.html)
* [Amazon Aurora의 보안](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/AuroraUserGuide/UsingWithRDS.html)
* Support - [사용자가 자신의 IAM 자격 증명을 사용하여 Amazon RDS MySQL DB 인스턴스에 대해 인증할 수 있도록 하려면 어떻게 해야 하나요?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/users-connect-rds-iam/)
* 가이드 - [Automatically remediate unencrypted Amazon RDS DB instances and clusters](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automatically-remediate-unencrypted-amazon-rds-db-instances-and-clusters.html)
* 가이드 - [Enable transparent data encryption in Amazon RDS for SQL Server](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/enable-transparent-data-encryption-in-amazon-rds-for-sql-server.html)
* 가이드 - [Encrypt an existing Amazon RDS for PostgreSQL DB instance](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/encrypt-an-existing-amazon-rds-for-postgresql-db-instance.html)
* 가이드 - [Enforce automatic tagging of Amazon RDS databases at launch](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/enforce-automatic-tagging-of-amazon-rds-databases-at-launch.html)
* 가이드 - [Monitor Amazon Aurora for instances without encryption](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/monitor-amazon-aurora-for-instances-without-encryption.html)
* Blog - [IAM role-based authentication to Amazon Aurora from serverless applications](https://aws.amazon.com/blogs/database/iam-role-based-authentication-to-amazon-aurora-from-serverless-applications/)
* Blog - [Applying best practices for securing sensitive data in Amazon RDS](https://aws.amazon.com/blogs/database/applying-best-practices-for-securing-sensitive-data-in-amazon-rds/)
* Blog - [Performing SQL database client-side encryption for multi-Region high availability](https://aws.amazon.com/blogs/database/performing-sql-database-client-side-encryption-for-multi-region-high-availability/)
* Blog - [Securing data in Amazon RDS using AWS KMS encryption](https://aws.amazon.com/blogs/database/securing-data-in-amazon-rds-using-aws-kms-encryption/)
* Blog - [Select the right encryption options for Amazon RDS and Amazon Aurora database engines](https://aws.amazon.com/blogs/database/selecting-the-right-encryption-options-for-amazon-rds-and-amazon-aurora-database-engines/)
* Blog - [How to use IAM multifactor authentication with Amazon RDS](https://aws.amazon.com/blogs/database/using-iam-multifactor-authentication-with-amazon-rds/)
* Blog - [Working with RDS and Aurora PostgreSQL logs: Part 1](https://aws.amazon.com/blogs/database/working-with-rds-and-aurora-postgresql-logs-part-1/)
* Blog - [Working with RDS and Aurora PostgreSQL logs: Part 2](https://aws.amazon.com/blogs/database/working-with-rds-and-aurora-postgresql-logs-part-2/)
* Blog - [Using IAM authentication to connect with pgAdmin Amazon Aurora PostgreSQL or Amazon RDS for PostgreSQL](https://aws.amazon.com/blogs/database/using-iam-authentication-to-connect-with-pgadmin-amazon-aurora-postgresql-or-amazon-rds-for-postgresql/)
* Blog - [Customizing security parameters on Amazon RDS for SQL Server](https://aws.amazon.com/blogs/database/customizing-security-parameters-on-amazon-rds-for-sql-server/)
* Blog - [Setting up passwordless login from Amazon EC2 Windows and Linux instances to Amazon RDS Oracle database instances](https://aws.amazon.com/blogs/database/setting-up-passwordless-login-from-amazon-ec2-windows-and-linux-instances-to-amazon-rds-oracle-database-instances/)
* Blog - [SSL connection to an Amazon Aurora PostgreSQL database from a C++ application using Visual Studio](https://aws.amazon.com/blogs/database/ssl-connection-to-an-amazon-aurora-postgresql-database-from-a-c-application-using-visual-studio/)
* Blog - [Architecting for database encryption on AWS](https://aws.amazon.com/blogs/security/architecting-for-database-encryption-on-aws/)
* Blog - [Preparing on-premises and AWS environments for external Kerberos authentication for Amazon RDS](https://aws.amazon.com/blogs/database/preparing-on-premises-and-aws-environments-for-external-kerberos-authentication-for-amazon-rds/)
* Blog - [Using external Kerberos authentication with Amazon RDS for Oracle](https://aws.amazon.com/blogs/database/using-external-kerberos-authentication-with-amazon-rds-for-oracle/)
* Blog - [Using external Kerberos authentication with Amazon Aurora PostgreSQL](https://aws.amazon.com/blogs/database/using-external-kerberos-authentication-with-amazon-aurora-postgresql/)
* Blog - [Accessing an Amazon RDS instance remotely using AWS Client VPN](https://aws.amazon.com/blogs/database/accessing-an-amazon-rds-instance-remotely-using-aws-client-vpn/)
* Blog - [Configuring and using Oracle Connection Manager on Amazon EC2 for Amazon RDS for Oracle](https://aws.amazon.com/blogs/database/configuring-and-using-oracle-connection-manager-on-amazon-ec2-for-amazon-rds-for-oracle/)
* Blog - [SCRAM Authentication in RDS for PostgreSQL 13](https://aws.amazon.com/blogs/database/scram-authentication-in-rds-for-postgresql-13/)
* Blog - [Managed disaster recovery with Amazon RDS for Oracle cross-Region automated backups – Part 1](https://aws.amazon.com/blogs/database/managed-disaster-recovery-with-amazon-rds-for-oracle-cross-region-automated-backups-part-1/)
* Blog - [Managed disaster recovery with Amazon RDS for Oracle cross-Region automated backups – Part 2](https://aws.amazon.com/blogs/database/part-2-managed-disaster-recovery-with-amazon-rds-for-oracle-xrab/)
* Blog - [Validate Native Network Encryption on Amazon RDS for Oracle](https://aws.amazon.com/ko/blogs/database/validate-native-network-encryption-on-amazon-rds-for-oracle/)
* Blog - [Architect a Managed Disaster Recovery on Amazon RDS for SQL Server: Part 1](https://aws.amazon.com/blogs/database/part-1-architect-a-managed-disaster-recovery-on-amazon-rds-for-sql-server/)
* Blog - [Architect a Managed Disaster Recovery on Amazon RDS for SQL Server: Part 2](https://aws.amazon.com/blogs/database/part-2-architect-a-managed-disaster-recovery-on-amazon-rds-for-sql-server/)
* Blog - [How to encrypt Amazon Aurora using AWS KMS and your own CMK](https://aws.amazon.com/ko/blogs/database/encrypting-amazon-aurora-using-aws-kms-and-your-own-cmk/)
* Blog - [Cross-Region, cross-account disaster recovery using Amazon Aurora Global Database](https://aws.amazon.com/ko/blogs/database/cross-region-cross-account-disaster-recovery-using-amazon-aurora-global-database/)
* Blog - [Use Amazon RDS Proxy with read-only endpoints](https://aws.amazon.com/ko/blogs/database/use-amazon-rds-proxy-with-read-only-endpoints/)
* Blog - [IAM authentication with Amazon RDS for MariaDB](https://aws.amazon.com/blogs/database/iam-authentication-with-amazon-rds-for-mariadb/)
* Blog - [Auditing for highly regulated industries using Amazon Aurora PostgreSQL](https://aws.amazon.com/blogs/database/auditing-for-highly-regulated-industries-using-amazon-aurora-postgresql/)
* Blog - [Security auditing in Amazon RDS for Oracle: Part 1](https://aws.amazon.com/ko/blogs/database/part-1-security-auditing-in-amazon-rds-for-oracle/)
* Blog - [Security auditing in Amazon RDS for Oracle: Part 2](https://aws.amazon.com/ko/blogs/database/part-2-security-auditing-in-amazon-rds-for-oracle/)
* Blog - [Securely connect to an Amazon RDS or Amazon EC2 database instance remotely with your preferred GUI](https://aws.amazon.com/blogs/database/securely-connect-to-an-amazon-rds-or-amazon-ec2-database-instance-remotely-with-your-preferred-gui/)
* Blog - [TDE certificate rotation on Amazon RDS for SQL Server](https://aws.amazon.com/ko/blogs/database/tde-certificate-rotation-on-amazon-rds-for-sql-server/)
* Blog - [Multi-user secrets rotation for Amazon RDS](https://aws.amazon.com/ko/blogs/database/multi-user-secrets-rotation-for-amazon-rds/)
* Blog - [Migrate TDE-enabled SQL Server databases to Amazon RDS for SQL Server](https://aws.amazon.com/ko/blogs/database/migrate-tde-enabled-sql-server-databases-to-amazon-rds-for-sql-server/)
* Blog - [How to use Amazon RDS and Amazon Aurora with a static IP address](https://aws.amazon.com/blogs/database/how-to-use-amazon-rds-and-amazon-aurora-with-a-static-ip-address/)
* Blog - [Access Amazon RDS across VPCs using AWS PrivateLink and Network Load Balancer](https://aws.amazon.com/blogs/database/access-amazon-rds-across-vpcs-using-aws-privatelink-and-network-load-balancer/)
* Blog - [Use Amazon RDS Proxy to provide access to RDS databases across AWS accounts](https://aws.amazon.com/blogs/database/use-amazon-rds-proxy-to-provide-access-to-rds-databases-across-aws-accounts/)


## [DynamoDB](https://aws.amazon.com/ko/dynamodb/?nc2=h_m1)

Amazon DynamoDB는 어떤 규모에서도 10밀리초 미만의 성능을 제공하는 키-값 및 문서 데이터베이스입니다. DynamoDB의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon DynamoDB의 보안](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/security.html)
* GIT - [Client-side Encryption(Java) for Amazon DynamoDB](https://github.com/aws/aws-dynamodb-encryption-java)
* 가이드 - [Help enforce DynamoDB tagging](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/help-enforce-dynamodb-tagging.html)
* Blog - [Understanding Amazon DynamoDB encryption by using AWS Key Management Service and analysis of API calls with Amazon Athena](https://aws.amazon.com/blogs/database/understanding-amazon-dynamodb-encryption-by-using-aws-key-management-service-and-analysis-of-api-calls-with-amazon-athena/)
* Blog - [Best practices for securing sensitive data in AWS data stores](https://aws.amazon.com/blogs/database/best-practices-for-securing-sensitive-data-in-aws-data-stores/)
* Blog - [How to Configure a Private Network Environment for Amazon DynamoDB Using VPC Endpoints](https://aws-preview.aka.amazon.com/ko/blogs/database/how-to-configure-a-private-network-environment-for-amazon-dynamodb-using-vpc-endpoints/)
* Blog - [Client-side Encryption for Amazon DynamoDB](https://aws.amazon.com/ko/blogs/developer/client-side-encryption-for-amazon-dynamodb/)
* Blog - [Bring your own encryption keys to Amazon DynamoDB](https://aws.amazon.com/blogs/database/bring-your-own-encryption-keys-to-amazon-dynamodb/)
* Blog - [Securing Amazon RDS and Aurora PostgreSQL database access with IAM authentication](https://aws.amazon.com/blogs/database/securing-amazon-rds-and-aurora-postgresql-database-access-with-iam-authentication/)
* Blog - [Multi-tenant data isolation with PostgreSQL Row Level Security](https://aws.amazon.com/blogs/database/multi-tenant-data-isolation-with-postgresql-row-level-security/)
* Blog - [Amazon DynamoDB now supports audit logging and monitoring using AWS CloudTrail](https://aws.amazon.com/blogs/database/amazon-dynamodb-now-supports-audit-logging-and-monitoring-using-aws-cloudtrail/)
* Blog - [Using CloudTrail data events with Athena and CloudWatch to create an audit trail for DynamoDB tables events](https://aws.amazon.com/blogs/mt/using-cloudtrail-data-events-with-athena-and-cloudwatch-to-create-an-audit-trail-for-dynamodb-tables-events/)
* Blog - [Introducing DML auditing for Amazon DocumentDB (with MongoDB compatibility)](https://aws.amazon.com/blogs/database/introducing-dml-auditing-for-amazon-documentdb-with-mongodb-compatibility/)



## [ElastiCache](https://aws.amazon.com/ko/elasticache/?nc2=h_m1)

Amazon ElastiCache는 완전관리형 Redis 및 Memcached를 제공합니다. ElastiCache의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon ElastiCache Redis의 보안](https://docs.aws.amazon.com/ko_kr/AmazonElastiCache/latest/red-ug/redis-security.html)
* [Amazon ElastiCache Memcached의 보안](https://docs.aws.amazon.com/ko_kr/AmazonElastiCache/latest/mem-ug/memcached-security.html) 
* 가이드 - [Monitor ElastiCache clusters for security groups](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/monitor-elasticache-clusters-for-security-groups.html)
* 가이드 - [Monitor Amazon ElastiCache clusters for at-rest encryption](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/monitor-amazon-elasticache-clusters-for-at-rest-encryption.html)
* Blog - [Open Sourcing Encryption in Transit for Redis](https://aws.amazon.com/blogs/opensource/open-sourcing-encryption-in-transit-redis/)
* Blog - [Amazon ElastiCache for Redis Is Now a HIPAA Eligible Service and You Can Use It to Power Real-Time Healthcare Applications](https://aws.amazon.com/blogs/security/now-you-can-use-amazon-elasticache-for-redis-a-hipaa-eligible-service-to-power-real-time-healthcare-applications/)
* Blog - [Manage AWS ElastiCache for Redis access with Role-Based Access Control, AWS Secrets Manager, and IAM](https://aws.amazon.com/blogs/database/manage-aws-elasticache-for-redis-access-with-role-based-access-control-aws-secrets-manager-and-iam/)



## [Neptune](https://aws.amazon.com/ko/neptune/?nc2=h_m1)

Amazon Neptune은 빠르고 안정적인 완전관리형 그래프 데이터베이스 서비스로, 상호연결성이 높은 데이터 집합을 활용하는 애플리케이션을 손쉽게 구축 및 실행할 수 있습니다. Neptune의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon Neptune의 보안](https://docs.aws.amazon.com/ko_kr/neptune/latest/userguide/security.html)
* Blog - [How LifeOmic’s JupiterOne simplifies security and compliance operations with Amazon Neptune](https://aws.amazon.com/blogs/database/how-lifeomics-jupiterone-simplifies-security-and-compliance-operations-with-amazon-neptune/)
* Blog - [Visualize your AWS Infrastructure with Amazon Neptune and AWS Config](https://aws.amazon.com/blogs/database/visualize-your-aws-infrastructure-with-amazon-neptune-and-aws-config/)
* Blog - [Fine Grained Access Control for Amazon Neptune data plane actions](https://aws.amazon.com/ko/blogs/database/fine-grained-access-control-for-amazon-neptune-data-plane-actions/)

 
## [Amazon Redshift](https://aws.amazon.com/ko/redshift/?nc2=h_m1)

Amazon Redshift는 속도가 빠른 완전관리형 데이터 웨어하우스로, 모든 데이터를 표준 SQL 및 기존 BI(비즈니스 인텔리전스) 도구를 사용하여 간편하고 비용 효율적으로 분석할 수 있습니다. Amazon Redshift의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon Redshift의 보안](https://docs.aws.amazon.com/ko_kr/redshift/latest/mgmt/iam-redshift-user-mgmt.html)
* 가이드 - [Ensure an Amazon Redshift cluster is encrypted upon creation](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/ensure-an-amazon-redshift-cluster-is-encrypted-upon-creation.html)
* Blog - [Protect and Audit PII data in Amazon Redshift with DataSunrise Security](https://aws.amazon.com/blogs/big-data/protect-and-audit-pii-data-in-amazon-redshift-with-datasunrise-security/)
* Blog - [How to enable cross-account Amazon Redshift COPY and Redshift Spectrum query for AWS KMS–encrypted data in Amazon S3](https://aws.amazon.com/blogs/big-data/how-to-enable-cross-account-amazon-redshift-copy-and-redshift-spectrum-query-for-aws-kms-encrypted-data-in-amazon-s3/)
* Blog - [Federate Database User Authentication Easily with IAM and Amazon Redshift](https://aws.amazon.com/ko/blogs/big-data/federate-database-user-authentication-easily-with-iam-and-amazon-redshift/)
* Blog - [Create an Amazon Redshift Data Warehouse That Can Be Securely Accessed Across Accounts](https://aws.amazon.com/blogs/big-data/create-an-amazon-redshift-data-warehouse-that-can-be-securely-accessed-across-accounts/)
* Blog - [Achieve finer-grained data security with column-level access control in Amazon Redshift](https://aws.amazon.com/blogs/big-data/achieve-finer-grained-data-security-with-column-level-access-control-in-amazon-redshift/)
* Blog - [Federate Amazon Redshift access with Microsoft Azure AD single sign-on](https://aws.amazon.com/blogs/big-data/federate-amazon-redshift-access-with-microsoft-azure-ad-single-sign-on/)
* Blog - [Restrict Amazon Redshift Spectrum external table access to Amazon Redshift IAM users and groups using role chaining](https://aws.amazon.com/blogs/big-data/restrict-amazon-redshift-spectrum-external-table-access-to-amazon-redshift-iam-users-and-groups-using-role-chaining/)
* Blog - [Federate access to your Amazon Redshift cluster with Active Directory Federation Services (AD FS): Part 1](https://aws.amazon.com/blogs/big-data/federate-access-to-your-amazon-redshift-cluster-with-active-directory-federation-services-ad-fs-part-1/)
* Blog - [Federate access to your Amazon Redshift cluster with Active Directory Federation Services (AD FS): Part 2](https://aws.amazon.com/blogs/big-data/federate-access-to-your-amazon-redshift-cluster-with-active-directory-federation-services-ad-fs-part-2/)
* Blog - [Federating single sign-on access to your Amazon Redshift cluster with PingIdentity](https://aws.amazon.com/blogs/big-data/federating-single-sign-on-access-to-your-amazon-redshift-cluster-with-pingidentity/)
* Blog - [Enabling multi-factor authentication for an Amazon Redshift cluster using Okta as an identity provider](https://aws.amazon.com/blogs/big-data/enabling-multi-factor-authentication-for-an-amazon-redshift-cluster-using-okta-as-an-identity-provider/)
* Blog - [Federating Amazon Redshift access from OneLogin](https://aws.amazon.com/blogs/big-data/federating-amazon-redshift-access-from-onelogin/)
* Blog - [Automating DBA tasks on Amazon Redshift securely using AWS IAM, AWS Lambda, Amazon EventBridge, and stored procedures](https://aws.amazon.com/blogs/big-data/automating-dba-tasks-on-amazon-redshift-securely-using-aws-iam-aws-lambda-amazon-eventbridge-and-stored-procedures/)
* Blog - [Enable private access to Amazon Redshift from your client applications in another VPC](https://aws.amazon.com/blogs/big-data/enable-private-access-to-amazon-redshift-from-your-client-applications-in-another-vpc/)
* Blog - [Amazon Redshift identity federation with multi-factor authentication](https://aws.amazon.com/blogs/big-data/amazon-redshift-identity-federation-with-multi-factor-authentication/)
* Blog - [Federated authentication to Amazon Redshift using AWS Single Sign-On](https://aws.amazon.com/ko/blogs/big-data/federated-authentication-to-amazon-redshift-using-aws-single-sign-on/)
* Blog - [Security considerations for Amazon Redshift cross-account data sharing](https://aws.amazon.com/blogs/big-data/security-considerations-for-amazon-redshift-cross-account-data-sharing/)
* Blog - [Federate Amazon Redshift access with SecureAuth single sign-on](https://aws.amazon.com/blogs/big-data/federate-amazon-redshift-access-with-secureauth-single-sign-on/)
* Blog - [Cybersecurity Awareness Month: Learn about the job zero of securing your data using Amazon Redshift](https://aws.amazon.com/blogs/big-data/cybersecurity-awareness-month-learn-about-the-job-zero-of-securing-your-data-using-amazon-redshift/)
* Blog - [Use the default IAM role in Amazon Redshift to simplify accessing other AWS services](https://aws.amazon.com/blogs/big-data/use-the-default-iam-role-in-amazon-redshift-to-simplify-accessing-other-aws-services/)
* Blog - [Use the default IAM role in Amazon Redshift to simplify accessing other AWS services](https://aws.amazon.com/ko/blogs/big-data/use-the-default-iam-role-in-amazon-redshift-to-simplify-accessing-other-aws-services/)
* Blog - [Data Tokenization with Amazon Redshift and Protegrity](https://aws.amazon.com/ko/blogs/apn/data-tokenization-with-amazon-redshift-and-protegrity/)
* Blog - [Federate access to Amazon Redshift using the JDBC browser plugin for Single Sign-on authentication with Microsoft Azure Active Directory](https://aws.amazon.com/ko/blogs/big-data/federate-access-to-amazon-redshift-using-the-jdbc-browser-plugin-for-single-sign-on-authentication-with-microsoft-azure-active-directory/)
* Blog - [Set up cross-account audit logging for your Amazon Redshift cluster](https://aws.amazon.com/ko/blogs/big-data/set-up-cross-account-audit-logging-for-your-amazon-redshift-cluster/)
* Blog - [Federated access to Amazon Redshift clusters in AWS China Regions with Active Directory Federation Services](https://aws.amazon.com/ko/blogs/big-data/federated-access-to-amazon-redshift-clusters-in-aws-china-regions-with-active-directory-federation-services/)
* Blog - [Integrate Amazon Redshift native IdP federation with Microsoft Azure AD and Power BI](https://aws.amazon.com/blogs/big-data/integrate-amazon-redshift-native-idp-federation-with-microsoft-azure-ad-and-power-bi/)
* Blog - [Simplify management of database privileges in Amazon Redshift using role-based access control](https://aws.amazon.com/blogs/big-data/simplify-management-of-database-privileges-in-amazon-redshift-using-role-based-access-control/)
* Blog - [Integrate Amazon Redshift native IdP federation with Microsoft Azure AD and Power BI](https://aws.amazon.com/ko/blogs/big-data/integrate-amazon-redshift-native-idp-federation-with-microsoft-azure-ad-and-power-bi/)
* Blog - [Simplify management of database privileges in Amazon Redshift using role-based access control](https://aws.amazon.com/ko/blogs/big-data/simplify-management-of-database-privileges-in-amazon-redshift-using-role-based-access-control/)
* Blog - [Integrate Amazon Redshift native IdP federation with Microsoft Azure AD using a SQL client](https://aws.amazon.com/ko/blogs/big-data/integrate-amazon-redshift-native-idp-federation-with-microsoft-azure-ad-using-a-sql-client/)
* Blog - [Share data securely across Regions using Amazon Redshift data sharing](https://aws.amazon.com/ko/blogs/big-data/share-data-securely-across-regions-using-amazon-redshift-data-sharing/)
* Blog - [Secure data movement across Amazon S3 and Amazon Redshift using role chaining and ASSUMEROLE](https://aws.amazon.com/ko/blogs/big-data/secure-data-movement-across-amazon-s3-and-amazon-redshift-using-role-chaining-and-assumerole/)
* Blog - [Federate access to Amazon Redshift query editor V2 with Active Directory Federation Services (AD FS): Part 3](https://aws.amazon.com/blogs/big-data/federate-access-to-amazon-redshift-query-editor-v2-with-active-directory-federation-services-ad-fs-part-3/)
* Blog - [Federate single sign-on access to Amazon Redshift query editor v2 with Okta](https://aws.amazon.com/blogs/big-data/federate-single-sign-on-access-to-amazon-redshift-query-editor-v2-with-okta/)
* Blog - [Use AWS CloudWatch as a destination for Amazon Redshift Audit logs](https://aws.amazon.com/blogs/big-data/using-aws-cloudwatch-as-destination-for-amazon-redshift-audit-logs/)
* Blog - [Achieve fine-grained data security with row-level access control in Amazon Redshift](https://aws.amazon.com/blogs/big-data/achieve-fine-grained-data-security-with-row-level-access-control-in-amazon-redshift/)
* Blog - [Accelerate resize and encryption of Amazon Redshift clusters with Faster Classic Resize](https://aws.amazon.com/blogs/big-data/accelerate-resize-and-encryption-of-amazon-redshift-clusters-with-faster-classic-resize/)
* Blog - [Integrate Amazon Redshift row-level security with Amazon Redshift native IdP authentication](https://aws.amazon.com/blogs/big-data/integrate-amazon-redshift-row-level-security-with-amazon-redshift-native-idp-authentication/)
* Blog - [Fine-grained entitlements in Amazon Redshift: A case study from TrustLogix](https://aws.amazon.com/blogs/big-data/fine-grained-entitlements-in-amazon-redshift-a-case-study-from-trustlogix/)

 
## [Amazon QLDB](https://aws.amazon.com/ko/qldb/?nc2=h_m1)

Amazon QLDB는 완전관리형 원장 데이터베이스로, 중앙의 신뢰할 수 있는 기관이 소유하는 투명하고, 변경 불가능하며, 암호화 방식으로 검증 가능한 트랜잭션 로그를 제공합니다. Amazon QLDB의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in Amazon QLDB](https://docs.aws.amazon.com/ko_kr/qldb/latest/developerguide/security.html)
* Solutions - [Tamper Proof Quality Data Using Amazon QLDB](https://aws.amazon.com/solutions/implementations/tamper-proof-quality-data-using-amazon-qldb/)
* Blog - [Real-world cryptographic verification with Amazon QLDB](https://aws.amazon.com/ko/blogs/database/real-world-cryptographic-verification-with-amazon-qldb/)
* Blog - [How fEMR Delivers Cryptographically Secure and Verifiable Medical Data with Amazon QLDB](https://aws.amazon.com/ko/blogs/architecture/how-femr-delivers-cryptographically-secure-and-verifiable-emr-medical-data-with-amazon-qldb/)
* Blog - [How Shinsegae International enhances customer experience and prevents counterfeiting with Amazon QLDB](https://aws.amazon.com/blogs/database/how-shinsegae-international-enhances-customer-experience-and-prevents-counterfeiting-with-amazon-qldb/)

 
## [Amazon DocumentDB](https://aws.amazon.com/ko/documentdb/?nc2=h_m1)

Amazon DocumentDB(MongoDB 호환)는 MongoDB 워크로드를 지원하는 빠르고, 확장 가능하며, 가용성이 높은 완전관리형 문서 데이터베이스 서비스입니다. Amazon DocumentDB의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [DocumentDB의 보안](https://docs.aws.amazon.com/ko_kr/documentdb/latest/developerguide/security.html)
* Blog - [Introducing role-based access control for Amazon DocumentDB (with MongoDB compatibility)](https://aws.amazon.com/blogs/database/introducing-role-based-access-control-for-amazon-documentdb-with-mongodb-compatibility/)
* Blog - [Evaluate Amazon DocumentDB (with MongoDB compatibility) configurations using AWS Config](https://aws.amazon.com/blogs/database/evaluate-amazon-documentdb-with-mongodb-compatibility-configurations-using-aws-config/)
* Blog - [Introducing Amazon DocumentDB (with MongoDB compatibility) user-defined roles for access control](https://aws.amazon.com/blogs/database/introducing-amazon-documentdb-with-mongodb-compatibility-user-defined-roles-for-access-control/)


## [Amazon Keyspaces](https://aws.amazon.com/ko/keyspaces/)

Amazon Keyspaces는 고가용성의 확장 가능한 관리형 Apache Cassandra 호환 데이터베이스 서비스입니다. Amazon Keyspaces의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in Amazon Keyspaces (for Apache Cassandra)](https://docs.aws.amazon.com/ko_kr/keyspaces/latest/devguide/security.html)



## [Amazon MemoryDB for Redis](https://aws.amazon.com/ko/memorydb/)

Amazon MemoryDB for Redis는 초고속 성능을 위한 Redis 호환, 내구성, 인메모리 데이터베이스 서비스입니다. Amazon MemoryDB for Redis의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [MemoryDB security](https://docs.aws.amazon.com/ko_kr/memorydb/latest/devguide/memorydb-security.html)
* [Security in MemoryDB for Redis](https://docs.aws.amazon.com/ko_kr/memorydb/latest/devguide/security.html)

## [Amazon Timestream](https://aws.amazon.com/ko/timestream/)

IoT 및 운영 애플리케이션으로 제공되는 확장이 용이한 고속 서버리스 시계열 데이터베이스 서비스인 Amazon Timestream에서는 관계형 데이터베이스에 비해 최대 10배나 저렴한 비용으로 1,000배 더 빠르게 매일 수조 건의 이벤트를 쉽게 저장하고 분석할 수 있습니다. Amazon Timestream의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [What Is Amazon Timestream?](https://docs.aws.amazon.com/ko_kr/timestream/latest/developerguide/what-is-timestream.html)
* [Security in Timestream](https://docs.aws.amazon.com/ko_kr/timestream/latest/developerguide/security.html)

 
## Database과 관련된 기타 유용한 링크들

준비중.


## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.



---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>