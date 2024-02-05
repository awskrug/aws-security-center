# 데이터 보안 (Data Security)

데이터에 대한 암호화 적용 및 안전한 접근 통제를 비롯하여 다양한 데이터 보안 기능을 제공하는 영역입니다. 이 영역에 해당하는 AWS 보안 서비스들에는 다음과 같은 것들이 있습니다.
 

## [AWS KMS(Key Management Service)](https://aws.amazon.com/ko/kms/)

데이터 암호화에 사용되는 키를 생성하고 관리하는 기능을 제공합니다. AWS KMS를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Key Management Service의 보안](https://docs.aws.amazon.com/ko_kr/kms/latest/developerguide/kms-security.html)
* [AWS KMS의 암호화 세부 정보 소개](https://docs.aws.amazon.com/ko_kr/kms/latest/cryptographic-details/intro.html)
* [NIST FIPS 140-2 AWS KMS Validation Certificate](https://csrc.nist.gov/projects/cryptographic-module-validation-program/Certificate/3139) _- FIPS 140-2 Overall level 2 인증서_
* [FIPS 140-2 Non-Proprietary Security Policy - AWS KMS HSM](https://csrc.nist.gov/csrc/media/projects/cryptographic-module-validation-program/documents/security-policies/140sp3009.pdf) _- KMS의 FIPS 인증 내역에 대한 문서_
* 동영상 [AWS Summit Seoul 2018] - [AWS KMS를 활용하여 안전한 AWS 환경을 구축하기 위한 전략](https://youtu.be/wjsEwusxMqE)
* GIT - [DIY code signing using AWS KMS and ACM Private CA](https://github.com/aws-samples/diy-code-signing-kms-private-ca)
* GIT - [aws-kms-pkcs11](https://github.com/JackOfMostTrades/aws-kms-pkcs11)
* 가이드 - [Monitor and remediate scheduled deletion of AWS KMS CMKs](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/monitor-and-remediate-scheduled-deletion-of-aws-kms-cmks.html)
* Blog - [Are KMS custom key stores right for you?](https://aws.amazon.com/ko/blogs/security/are-kms-custom-key-stores-right-for-you/) _- CloudHSM과 KMS를 합친 기능인 KMS Custom Key Store에 대해 설명_
* Blog - [How to Use the New AWS Encryption SDK to Simplify Data Encryption and Improve Application Availability](https://aws.amazon.com/ko/blogs/security/how-to-use-the-new-aws-encryption-sdk-to-simplify-data-encryption-and-improve-application-availability/)
* Blog - [Encrypting messages published to Amazon SNS with AWS KMS](https://aws.amazon.com/blogs/compute/encrypting-messages-published-to-amazon-sns-with-aws-kms/)
* Blog - [Control Access to Your Data with Slack Enterprise Key Management and AWS KMS](https://aws.amazon.com/blogs/apn/control-access-to-your-data-with-slack-enterprise-key-management-and-aws-kms/) _-Slack Enterprise Key Management환경과 AWS KMS간 연계를 설명_
* Blog - [How to Connect Directly to AWS Key Management Service from Amazon VPC by Using an AWS PrivateLink Endpoint](https://aws.amazon.com/blogs/security/how-to-connect-directly-to-aws-key-management-service-from-amazon-vpc-by-using-an-aws-privatelink-endpoint/)
* Blog - [Post-quantum TLS now supported in AWS KMS](https://aws.amazon.com/blogs/security/post-quantum-tls-now-supported-in-aws-kms/) _- S2N에 반영된 post-quantum 하이브리드 키교환 방식을 KMS의 퍼블릭 엔드포인트에 적용했다는 것을 알리는 블로그_
* Blog - [Digital signing with the new asymmetric keys feature of AWS KMS](https://aws.amazon.com/blogs/security/digital-signing-asymmetric-keys-aws-kms/)
* Blog - [Code signing using AWS Certificate Manager Private CA and AWS Key Management Service asymmetric keys](https://aws.amazon.com/blogs/security/code-signing-aws-certificate-manager-private-ca-aws-key-management-service-asymmetric-keys/)
* Blog - [Combining encryption and signing with AWS KMS asymmetric keys](https://aws.amazon.com/blogs/security/combining-encryption-and-signing-with-aws-asymmetric-keys/)
* Blog - [Round 2 post-quantum TLS is now supported in AWS KMS](https://aws.amazon.com/blogs/security/round-2-post-quantum-tls-is-now-supported-in-aws-kms/)
* Blog - [Demystifying KMS keys operations, bring your own key (BYOK), custom key store, and ciphertext portability](https://aws.amazon.com/blogs/security/demystifying-kms-keys-operations-bring-your-own-key-byok-custom-key-store-and-ciphertext-portability/)
* Blog - [How to verify AWS KMS asymmetric key signatures locally with OpenSSL](https://aws.amazon.com/blogs/security/how-to-verify-aws-kms-asymmetric-key-signatures-locally-with-openssl/)
* Blog - [Encrypt global data client-side with AWS KMS multi-Region keys](https://aws.amazon.com/ko/blogs/security/encrypt-global-data-client-side-with-aws-kms-multi-region-keys/)
* Blog - [Managing permissions with grants in AWS Key Management Service](https://aws.amazon.com/blogs/security/managing-permissions-with-grants-in-aws-key-management-service/)
* Blog - [How to sign Ethereum EIP-1559 transactions using AWS KMS](https://aws.amazon.com/blogs/database/how-to-sign-ethereum-eip-1559-transactions-using-aws-kms/)
* Blog - [How to protect HMACs inside AWS KMS](https://aws.amazon.com/ko/blogs/security/how-to-protect-hmacs-inside-aws-kms/)
 

## [AWS CloudHSM](https://aws.amazon.com/ko/cloudhsm/)

AWS상에서 고객 전용의 HSM(Hardware Security Module)을 관리형 서비스로 제공합니다. AWS CloudHSM을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS CloudHSM의 보안](https://docs.aws.amazon.com/ko_kr/cloudhsm/latest/userguide/security.html)
* [What Is AWS CloudHSM Classic?](https://docs.aws.amazon.com/cloudhsm/classic/userguide/cloud-hsm-overview.html)
* Support - [CloudHSM 클러스터를 다른 AWS 계정과 공유](https://aws.amazon.com/ko/premiumsupport/knowledge-center/cloudhsm-share-clusters/)
* 백서 - [Security of AWS CloudHSM Backups](https://d1.awsstatic.com/whitepapers/Security/security-of-aws-cloudhsm-backups.pdf)
* 백서 - [Migrating to AWS CloudHSM](http://s3.amazonaws.com/cloudhsmv2-software/CloudHsmClient/Docs/CloudHSMUpgradeGuide-latest.pdf)
* GIT - [aws-cloudhsm-jce-examples](https://github.com/aws-samples/aws-cloudhsm-jce-examples/tree/master/src/main/java/com/amazonaws/cloudhsm/examples)
* GIT - [aws-cloudhsm-pkcs11-examples](https://github.com/aws-samples/aws-cloudhsm-pkcs11-examples)
* GIT - [SSL Offloading to CloudHSM - Step by Step Guide](https://github.com/aws-samples/aws-reinvent2018-keeping-secrets/blob/master/SSL_Offloading_to_CloudHSM.md)
* Blog - [How to migrate a digital signing workload to AWS CloudHSM](https://aws.amazon.com/ko/blogs/security/how-to-migrate-a-digital-signing-workload-to-aws-cloudhsm/)
* Blog - [How to migrate your EC2 Oracle Transparent Data Encryption (TDE) database encryption wallet to CloudHSM](https://aws.amazon.com/ko/blogs/security/how-to-migrate-your-ec2-oracle-transparent-data-encryption-tde-database-encryption-wallet-to-cloudhsm/)
* Blog - [How to run AWS CloudHSM workloads on Docker containers](https://aws.amazon.com/ko/blogs/security/how-to-run-aws-cloudhsm-workloads-on-docker-containers/)
* Blog - [Security of Cloud HSMBackups](https://aws.amazon.com/ko/blogs/architecture/security-of-cloud-hsmbackups/)
* Blog - [How to Update AWS CloudHSM Devices and Client Instances to the Software and Firmware Versions Supported by AWS](https://aws.amazon.com/ko/blogs/security/how-to-update-aws-cloudhsm-devices-and-client-instances-to-the-software-and-firmware-versions-supported-by-aws/)
* Blog - [Understanding AWS CloudHSM Cluster Synchronization](https://aws.amazon.com/blogs/security/understanding-aws-cloudhsm-cluster-synchronization/)
* Blog - [Using AWS CloudHSM-backed certificates with Microsoft Internet Information Server](https://aws.amazon.com/ko/blogs/security/using-aws-cloudhsm-backed-certificates-with-microsoft-internet-information-server/) _- MS IIS에 SSL구성시 인증서 개인키를 CloudHSM에 보관 활용하는 방법_
* Blog - [How to clone an AWS CloudHSM cluster across regions](https://aws.amazon.com/blogs/security/how-to-clone-an-aws-cloudhsm-cluster-across-regions/) _- 멀티리전간 HSM 클러스터의 Cloning을 통해 가용성 제공 방안_
* Blog - [How to run AWS CloudHSM workloads on AWS Lambda](https://aws.amazon.com/blogs/security/how-to-run-aws-cloudhsm-workloads-on-aws-lambda/)
* Blog - [How to lower costs by automatically deleting and recreating HSMs](https://aws.amazon.com/blogs/security/how-to-lower-costs-by-automatically-deleting-and-recreating-hsms/)
* Blog - [How to deploy CloudHSM to securely share your keys with your SaaS provider](https://aws.amazon.com/blogs/security/how-to-deploy-cloudhsm-securely-share-keys-with-saas-provider/)
* Blog - [How to migrate symmetric exportable keys from AWS CloudHSM Classic to AWS CloudHSM](https://aws.amazon.com/blogs/security/migrate-symmetric-exportable-keys-aws-cloudhsm-classic-aws-cloudhsm/)
* Blog - [Signing executables with HSM-backed certificates using multiple Windows instances](https://aws.amazon.com/blogs/security/signing-executables-with-hsm-backed-certificates-using-multiple-windows-instances/)
* Blog - [Integrate CloudHSM PKCS #11 Library 5.0 with serverless workloads](https://aws.amazon.com/ko/blogs/security/integrate-cloudhsm-pkcs-11-library-5-0-with-serverless-workloads/)
* Blog - [CloudHSM best practices to maximize performance and avoid common configuration pitfalls](https://aws.amazon.com/blogs/security/cloudhsm-best-practices-to-maximize-performance-and-avoid-common-configuration-pitfalls/)
* Blog - [Migrate and secure your Windows PKI to AWS with AWS CloudHSM](https://aws.amazon.com/ko/blogs/security/migrate-and-secure-your-windows-pki-to-aws-with-aws-cloudhsm/)
* Blog - [Signing Data Using Keys Stored in AWS CloudHSM with Python](https://aws.amazon.com/blogs/apn/signing-data-using-keys-stored-in-aws-cloudhsm-with-python/)


## [Amazon Macie](https://aws.amazon.com/ko/macie/)

기계 학습(Machine Learning)기반으로 민감한 중요 데이터를 발견 및 분류하고 불법적인 유출을 방지하는 서비스입니다. Amazon Macie를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Security in Amazon Macie](https://docs.aws.amazon.com/ko_kr/macie/latest/user/security.html)
* [What Is Amazon Macie Classic?](https://docs.aws.amazon.com/macie/latest/userguide/what-is-macie.html)
* GIT - [Amazon Macie Activity Generator](https://github.com/aws-samples/amazon-macie-activity-generator) _– Amazon Macie 데모를 위해 time-series activities, noise addition, anomaly injection 등의 이벤트를 발생_
* Blog - [Classify sensitive data in your environment using Amazon Macie](https://aws.amazon.com/blogs/security/classify-sensitive-data-in-your-environment-using-amazon-macie/) _– Amazon Macie를 Custom하게 훈련(내부 규정이나 개인/기밀정보 패턴등을 Macie에게 학습)시키기 위해 샘플 데이터 셋을 만드는 방법에 대한 소개_
* Blog - [Discover sensitive data by using custom data identifiers with Amazon Macie](https://aws.amazon.com/blogs/security/discover-sensitive-data-by-using-custom-data-identifiers-with-amazon-macie/)
* Blog - [BBVA: Architecture for Large-Scale Macie Implementation](https://aws.amazon.com/blogs/architecture/bbva-architecture-for-large-scale-macie-implementation/)
* Blog - [Use Macie to discover sensitive data as part of automated data pipelines](https://aws.amazon.com/blogs/security/use-macie-to-discover-sensitive-data-as-part-of-automated-data-pipelines/)
* Blog - [Detecting sensitive data in DynamoDB with Macie](https://aws.amazon.com/blogs/security/detecting-sensitive-data-in-dynamodb-with-macie/)
* Blog - [Deploy an automated ChatOps solution for remediating Amazon Macie findings](https://aws.amazon.com/ko/blogs/security/deploy-an-automated-chatops-solution-for-remediating-amazon-macie-findings/)
* Blog - [Creating a notification workflow from sensitive data discover with Amazon Macie, Amazon EventBridge, AWS Lambda, and Slack](https://aws.amazon.com/ko/blogs/security/creating-a-notification-workflow-from-sensitive-data-discover-with-amazon-macie-amazon-eventbridge-aws-lambda-and-slack/)
* Blog - [Automate the archival and deletion of sensitive data using Amazon Macie](https://aws.amazon.com/blogs/big-data/automate-the-archival-and-deletion-of-sensitive-data-using-amazon-macie/)
* Blog - [Enabling data classification for Amazon RDS database with Macie](https://aws.amazon.com/ko/blogs/security/enabling-data-classification-for-amazon-rds-database-with-amazon-macie/)


## [AWS Secret Manager](https://aws.amazon.com/ko/secrets-manager/?nc1=h_ls)

DB암호, API키 같은 인증정보들을 안전하게 보관, 교체, 조회하는 기능을 제공합니다. 온프레미스나 3rd Party제품의 자격증명들도 이용할 수 있습니다. AWS Secret Manager를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Secrets Manager의 보안](https://docs.aws.amazon.com/ko_kr/secretsmanager/latest/userguide/security.html)
* GIT - [AWS Secrets Manager Rotation Lambda Function Samples](https://github.com/aws-samples/aws-secrets-manager-rotation-lambdas)
* GIT - [AWS Secrets Manager Java caching client](https://github.com/aws/aws-secretsmanager-caching-java)
* GIT - [AWS Secrets Manager JDBC Library](https://github.com/aws/aws-secretsmanager-jdbc)
* GIT - [AWS Secrets Manager Python caching client](https://github.com/aws/aws-secretsmanager-caching-python)
* GIT - [AWS Secrets Manager Caching Client for .NET](https://github.com/aws/aws-secretsmanager-caching-net)
* GIT - [AWS Secrets Manager Go Caching Client](https://github.com/aws/aws-secretsmanager-caching-go)
* GIT - [secret-sidecar](https://github.com/jicowan/secret-sidecar) _- ECS Secret들을 Secret Manager에 안전하게 보관/관리하는 샘플_ 
* GIT - [secret-sidecar](https://github.com/jicowan/secret-sidecar) _- Secret Manager와 EKS 연계_
* GIT - [AWS EKS Secrets injector](https://github.com/Mahendrasiddappa/eks-secret-injector) _- Secret Manager와 EKS 연계_
* GIT - [Native Secrets](https://github.com/mhausenblas/nase) _- Secret Manager와 EKS 연계_
* Support - [계정 간에 Secrets Manager 보안 공유](https://aws.amazon.com/ko/premiumsupport/knowledge-center/secrets-manager-share-between-accounts/)
* 가이드 - [Manage credentials using AWS Secrets Manager](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/manage-credentials-using-aws-secrets-manager.html)
* Blog - [Rotate Amazon RDS database credentials automatically with AWS Secrets Manager](https://aws.amazon.com/blogs/security/rotate-amazon-rds-database-credentials-automatically-with-aws-secrets-manager/)
* Blog - [How to rotate Amazon DocumentDB and Amazon Redshift credentials in AWS Secrets Manager](https://aws.amazon.com/blogs/security/how-to-rotate-amazon-documentdb-and-amazon-redshift-credentials-in-aws-secrets-manager/)
* Blog - [Enable password authentication for AWS Transfer for SFTP using AWS Secrets Manager](https://aws.amazon.com/blogs/storage/enable-password-authentication-for-aws-transfer-for-sftp-using-aws-secrets-manager/)
* Blog - [Improve availability and latency of applications by using AWS Secret Manager’s Python client-side caching library](https://aws.amazon.com/blogs/security/improve-availability-and-latency-of-applications-by-using-aws-secret-managers-python-client-side-caching-library/)
* Blog - [How to automate replication of secrets in AWS Secrets Manager across AWS Regions](https://aws.amazon.com/blogs/security/how-to-automate-replication-of-secrets-in-aws-secrets-manager-across-aws-regions/)
* Blog - [How to rotate a WordPress MySQL database secret using AWS Secrets Manager in Amazon EKS](https://aws.amazon.com/blogs/security/how-to-rotate-a-wordpress-mysql-database-secret-using-aws-secrets-manager-in-amazon-eks/)
* Blog - [How to use AWS Secrets Manager to securely store and rotate SSH key pairs](https://aws.amazon.com/blogs/security/how-to-use-aws-secrets-manager-securely-store-rotate-ssh-key-pairs/)
* Blog - [GoDaddy - Kubernetes External Secrets](https://kr.godaddy.com/engineering/2019/04/16/kubernetes-external-secrets/) _- EKS Secret들을 Secret Manager에 저장,관리하는 방법에 대한 GoDaddy 블로그_
* Blog - [How to use resource-based policies in the AWS Secrets Manager console to securely access secrets across AWS accounts](https://aws.amazon.com/blogs/security/how-to-use-resource-based-policies-aws-secrets-manager-console-to-securely-access-secrets-aws-accounts/)
* Blog - [Identify, arrange, and manage secrets easily using enhanced search in AWS Secrets Manager](https://aws.amazon.com/blogs/security/identify-arrange-manage-secrets-easily-using-enhanced-search-in-aws-secrets-manager/)
* Blog - [Use AWS Secrets Manager to simplify the management of private certificates](https://aws.amazon.com/ko/blogs/security/use-aws-secrets-manager-to-simplify-the-management-of-private-certificates/)
* Blog - [How to replicate secrets in AWS Secrets Manager to multiple Regions](https://aws.amazon.com/blogs/security/how-to-replicate-secrets-aws-secrets-manager-multiple-regions/)
* Blog - [Design patterns to access cross-account secrets stored in AWS Secrets Manager](https://aws.amazon.com/blogs/database/design-patterns-to-access-cross-account-secrets-stored-in-aws-secrets-manager/)
* Blog - [Manage your AWS DMS endpoint credentials with AWS Secrets Manager](https://aws.amazon.com/blogs/database/manage-your-aws-dms-endpoint-credentials-with-aws-secrets-manager/)
* Blog - [How to configure rotation windows for secrets stored in AWS Secrets Manager](https://aws.amazon.com/blogs/security/how-to-configure-rotation-windows-for-secrets-stored-in-aws-secrets-manager/)
* Blog - [Securely retrieving secrets with AWS Lambda](https://aws.amazon.com/blogs/compute/securely-retrieving-secrets-with-aws-lambda/)
 
 

## [AWS Certificate Manager](https://aws.amazon.com/ko/certificate-manager/)

AWS서비스들에 SSL/TLS 인증서를 무료로 발급, 관리해 주는 기능을 제공합니다. AWS Certification Manager를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Certificate Manager의 보안](https://docs.aws.amazon.com/ko_kr/acm/latest/userguide/security.html)
* [AWS::CertificateManager::Certificate](https://docs.aws.amazon.com/ko_kr/AWSCloudFormation/latest/UserGuide/aws-resource-certificatemanager-certificate.html)
* [Amazon Trust Services](https://www.amazontrust.com/repository/) _– Amazon Root CA에 대한 정보를 제공하는 싸이트_
* GIT - [s2n](https://github.com/awslabs/s2n)
* Blog - [ACM인증서 Certificate Transparency 지원](https://aws.amazon.com/ko/blogs/security/how-to-get-ready-for-certificate-transparency/)
* Blog - [How to use AWS Certificate Manager with AWS CloudFormation](https://aws.amazon.com/blogs/security/how-to-use-aws-certificate-manager-with-aws-cloudformation/)
* Blog - [How to deploy public ACM certificates across multiple AWS accounts and Regions using AWS CloudFormation StackSets](https://aws.amazon.com/blogs/security/how-to-deploy-public-acm-certificates-across-multiple-aws-accounts-and-regions-using-aws-cloudformation-stacksets/)
* Blog - [How to monitor expirations of imported certificates in AWS Certificate Manager (ACM)](https://aws.amazon.com/blogs/security/how-to-monitor-expirations-of-imported-certificates-in-aws-certificate-manager-acm/)
* Blog - [How to tune TLS for hybrid post-quantum cryptography with Kyber](https://aws.amazon.com/blogs/security/how-to-tune-tls-for-hybrid-post-quantum-cryptography-with-kyber/)


## [AWS Certificate Manager Private Certificate Authority](https://aws.amazon.com/ko/certificate-manager/private-certificate-authority/?nc1=h_ls)

사설 CA환경을 관리형으로 제공해 드리는 ACM의 서브 서비스입니다. AWS Certification Manager Private Certificate Authority를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Certificate Manager Private Certificate Authority의 보안](https://docs.aws.amazon.com/ko_kr/acm-pca/latest/userguide/security.html)
* GIT - [DIY code signing using AWS KMS and ACM Private CA](https://github.com/aws-samples/diy-code-signing-kms-private-ca)
* Blog - [Enabling SSL encrypted connections to Microsoft SQL Server using AWS Certificate Manager Private Certificate Authority](https://aws.amazon.com/ko/blogs/database/enabling-ssl-encrypted-connections-to-microsoft-sql-server-using-aws-certificate-manager-private-certificate-authority/)
* Blog - [How to host and manage an entire private certificate infrastructure in AWS](https://aws.amazon.com/ko/blogs/security/how-to-host-and-manage-an-entire-private-certificate-infrastructure-in-aws/)
* Blog - [Maintaining Transport Layer Security all the way to your container part 2: Using AWS Certificate Manager Private Certificate Authority](https://aws.amazon.com/ko/blogs/compute/maintaining-transport-layer-security-all-the-way-to-your-container-part-2-using-aws-certificate-manager-private-certificate-authority/)
* Blog - [Code signing using AWS Certificate Manager Private CA and AWS Key Management Service asymmetric keys](https://aws.amazon.com/blogs/security/code-signing-aws-certificate-manager-private-ca-aws-key-management-service-asymmetric-keys/)
* Blog - [Monitoring AWS Certificate Manager Private CA with AWS Security Hub](https://aws.amazon.com/blogs/security/monitoring-aws-certificate-manager-private-ca-with-aws-security-hub/)
* Blog - [Using ACM Private Certificate Authority in a multi-account environment by using IAM roles](https://aws.amazon.com/blogs/security/using-acm-private-certificate-authority-multi-account-environment-using-iam-roles/)
* Blog - [How to use AWS RAM to share your ACM Private CA cross-account](https://aws.amazon.com/ko/blogs/security/how-to-use-aws-ram-to-share-your-acm-private-ca-cross-account/)
* [AWS Certificate Manager Private Certificate Authority, 계정 간에 공유되는 CA에 대해 더 많은 유연성 지원 시작](https://aws.amazon.com/ko/about-aws/whats-new/2021/06/aws-certificate-manager-private-certificate-authority-now-supports-more-flexibility-for-cas-shared-across-accounts/)
* Blog - [How to Prepare for AWS’s Move to Its Own Certificate Authority](https://aws.amazon.com/blogs/security/how-to-prepare-for-aws-move-to-its-own-certificate-authority/#aws-comment-trigger-5777)
* Blog - [Create a portable root CA using AWS CloudHSM and ACM Private CA](https://aws.amazon.com/blogs/security/create-a-portable-root-ca-using-aws-cloudhsm-and-acm-private-ca/)
* Blog - [How to securely create and store your CRL for ACM Private CA](https://aws.amazon.com/blogs/security/how-to-securely-create-and-store-your-crl-for-acm-private-ca/)
* Blog - [How to create certificates with custom extensions using AWS Certificate Manager Private CA](https://aws.amazon.com/ko/blogs/security/how-to-create-certificates-with-custom-extensions-using-aws-certificate-manager-private-ca/)
* Blog - [How to secure an enterprise scale ACM Private CA hierarchy for automotive and manufacturing](https://aws.amazon.com/blogs/security/how-to-secure-an-enterprise-scale-acm-private-ca-hierarchy-for-automotive-and-manufacturing/)
* Blog - [How to incorporate ACM PCA into your existing Windows Active Directory Certificate Services](https://aws.amazon.com/blogs/security/how-to-incorporate-acm-pca-into-your-existing-windows-active-directory-certificate-services/)


## [AWS Site-to-Site VPN](https://docs.aws.amazon.com/ko_kr/vpc/latest/adminguide/Welcome.html)
기본적으로 Amazon VPC로 시작하는 인스턴스는 자체(원격) 네트워크와 통신할 수 없습니다. VPC에 가상 프라이빗 게이트웨이를 연결하고 사용자 지정 라우팅 테이블을 생성하며 보안 그룹 규칙을 업데이트하고 AWS Site-to-Site VPN(Site-to-Site VPN) 연결을 생성하여 VPC에서 원격 네트워크에 액세스하도록 할 수 있습니다. Site-to-Site VPN을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

* [AWS Site-to-Site VPN의 보안](https://docs.aws.amazon.com/ko_kr/vpn/latest/s2svpn/security.html)
* [고객 게이트웨이 디바이스](https://docs.aws.amazon.com/ko_kr/vpn/latest/s2svpn/your-cgw.html)
* Support - [VPN을 통한 BGP 문제 해결](https://aws.amazon.com/ko/premiumsupport/knowledge-center/troubleshoot-bgp-vpn/)
* Blog - [Scaling VPN throughput using AWS Transit Gateway](https://aws.amazon.com/blogs/networking-and-content-delivery/scaling-vpn-throughput-using-aws-transit-gateway/)
* Blog - [Improve VPN Network Performance of AWS Hybrid Cloud with Global Accelerator](https://aws.amazon.com/blogs/architecture/improve-vpn-network-performance-of-aws-hybrid-cloud-with-global-accelerator/)
* Blog - [How do I troubleshoot VPN tunnel inactivity or instability on my customer gateway device?](https://aws.amazon.com/premiumsupport/knowledge-center/vpn-tunnel-instability-inactivity/)
* Blog - [Simulating Site-to-Site VPN Customer Gateways Using strongSwan](https://aws.amazon.com/blogs/networking-and-content-delivery/simulating-site-to-site-vpn-customer-gateways-strongswan/)
* Blog - [Simulating Site-to-Site VPN customer gateways using strongSwan part 2: Certificate-based authentication](https://aws.amazon.com/blogs/networking-and-content-delivery/simulating-site-to-site-vpn-customer-gateways-using-strongswan-part-2-certificate-based-authentication/)
* Blog - [Introducing AWS Site-to-Site VPN Private IP VPNs](https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-aws-site-to-site-vpn-private-ip-vpns/)


## [AWS Client VPN](https://docs.aws.amazon.com/ko_kr/vpn/latest/clientvpn-admin/what-is.html)
AWS Client VPN은 AWS 리소스와 온프레미스 네트워크 리소스를 안전하게 액세스할 수 있게 해주는 관리형 클라이언트 기반 VPN 서비스입니다. AWS Client VPN을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

* [AWS Client VPN의 보안](https://docs.aws.amazon.com/ko_kr/vpn/latest/clientvpn-admin/security.html)
* Blog - [Authenticate AWS Client VPN users with SAML](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/authenticate-aws-client-vpn-users-with-saml/)
* Blog - [How to Integrate AWS Client VPN with Azure Active Directory](https://aws.amazon.com/blogs/apn/how-to-integrate-aws-client-vpn-with-azure-active-directory/)
* Blog - [Using Microsoft Active Directory MFA with AWS Client VPN](https://aws.amazon.com/blogs/networking-and-content-delivery/using-microsoft-active-directory-mfa-with-aws-client-vpn/)
* Blog - [Accessing an Amazon RDS instance remotely using AWS Client VPN](https://aws.amazon.com/blogs/database/accessing-an-amazon-rds-instance-remotely-using-aws-client-vpn/)
* Blog - [How to restrict IAM roles to access AWS resources from specific geolocations using AWS Client VPN](https://aws.amazon.com/ko/blogs/security/how-to-restrict-iam-roles-to-access-aws-resources-from-specific-geolocations-using-aws-client-vpn/)
* Blog - [Enforcing VPN access policies with AWS Client VPN connection handler](https://aws.amazon.com/blogs/networking-and-content-delivery/enforcing-vpn-access-policies-with-aws-client-vpn-connection-handler/)
* Blog - [보안성 높은 재택근무 환경을 위한 AWS 아키텍처 구성하기](https://aws-blogs-prod.amazon.com/korea/improving-security-architecture-controls-for-wfh/)
* Blog - [Building Multi-Region AWS Client VPN with Microsoft Active Directory and Amazon Route 53](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/building-multi-region-aws-client-vpn-with-microsoft-active-directory-and-amazon-route-53/)
* Blog - [Securely Connect your Mobile Device to your AWS environment with AWS Client VPN](https://aws.amazon.com/blogs/networking-and-content-delivery/securely-connect-your-mobile-device-to-your-aws-environment-with-aws-client-vpn/)


## [Server Side Encryption](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/serv-side-encryption.html)

AWS서비스가 관리하는 키, AWS KMS가 관리하는 키, 또는 고객이 관리하는 키 등을 이용하여 데이터를 암호화 할 수 있는 옵션 기능입니다. AWS Server Side Encryption을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Amazon S3가 관리하는 암호화 키(SSE-S3)를 사용하는 서버 측 암호화로 데이터 보호](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/UsingServerSideEncryption.html)
* [Amazon S3 인벤토리](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/storage-inventory.html) _– 버킷 또는 Prefix 단위로 암호화 설정 상태 표시_
* [Amazon DynamoDB Encryption at Rest](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/EncryptionAtRest.html) _– DynamoDB 저장 데이터에 대한 Server Side 암호화 방법_
* [SQS 서버 측 암호화](https://docs.aws.amazon.com/ko_kr/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-server-side-encryption.html)
* [Amazon EBS Encryption](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSEncryption.html)
* [Amazon RDS 리소스 암호화](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Overview.Encryption.html)
* [RDS Oracle TDE](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.Oracle.Options.AdvSecurity.html)
* [RDS MS-SQL TDE](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.SQLServer.Options.TDE.html)
* [Redshift로 암호화된 데이터 업로드](https://docs.aws.amazon.com/ko_kr/redshift/latest/dg/t_uploading-encrypted-data.html)
* [Athena 암호화 옵션 구성](https://docs.aws.amazon.com/ko_kr/athena/latest/ug/encryption.html)
* [RedShift - Changing Cluster Encryption](https://docs.aws.amazon.com/redshift/latest/mgmt/changing-cluster-encryption.html) - RedShift의 비 암호화 클러스터에 대해 KMS기반 암호화를 적용하는 방법, GDPR 이슈 대응




## [Encryption SDK](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/introduction.html)
AWS Encryption SDK 는 업계 표준과 모범사례를 따라서 누구나 쉽게 Client-side 암호화를 구현할 수 있도록 지원하는 암호화 라이브러리입니다. AWS Encryption SDK에 대한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [What is the AWS Encryption SDK?](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/introduction.html)
* [AWS Encryption SDK for C](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/c-language.html)
* [AWS Encryption SDK for Java](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/java.html)
* [AWS Encryption SDK for JavaScript](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/javascript.html)
* [AWS Encryption SDK for Python](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/python.html)
* [AWS Encryption SDK Command Line Interface](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/crypto-cli.html)
* [AWS Encryption SDK CLI Syntax and Parameter Reference](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/crypto-cli-reference.html)
* [Encryption SDK Data Key Caching](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/data-key-caching.html) _– KMS 암,복호화 Limit에 대한 대안으로 키를 캐슁하는 방법_
* [Data Key Caching Example](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/sample-cache-example.html)
* [How is the AWS Encryption SDK different from the AWS SDKs?](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/faq.html#aws-sdks)
* [How is the AWS Encryption SDK different from the Amazon S3 encryption client?](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/faq.html#s3-encryption-client)
* [How much overhead does the AWS Encryption SDK message format add to my encrypted data?](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/faq.html#overhead)
* [AWS Encryption SDK Algorithms Reference](https://docs.aws.amazon.com/ko_kr/encryption-sdk/latest/developer-guide/algorithms-reference.html)
* Blog - [How to decrypt ciphertexts in multiple regions with the AWS Encryption SDK in C](https://aws.amazon.com/blogs/security/how-to-decrypt-ciphertexts-multiple-regions-aws-encryption-sdk-in-c/)
* Blog - [AWS Encryption SDK: How to Decide if Data Key Caching Is Right for Your Application](https://aws.amazon.com/blogs/security/aws-encryption-sdk-how-to-decide-if-data-key-caching-is-right-for-your-application/) _- 어떤 경우에 제한적으로 EncryptionSDK를 사용해야 하는지에 대한 가이드_
* Blog - [How to Encrypt and Decrypt Your Data with the AWS Encryption CLI](https://aws.amazon.com/ko/blogs/security/how-to-encrypt-and-decrypt-your-data-with-the-aws-encryption-cli/) _– CLI형태로 암,복호화 기능 적용_
* Blog - [How to Use the New AWS Encryption SDK to Simplify Data Encryption and Improve Application Availability](https://aws.amazon.com/ko/blogs/security/how-to-use-the-new-aws-encryption-sdk-to-simplify-data-encryption-and-improve-application-availability/)
* Blog - [Improved client-side encryption: Explicit KeyIds and key commitment](https://aws.amazon.com/blogs/security/improved-client-side-encryption-explicit-keyids-and-key-commitment/)
* GIT - [AWS Encryption SDK for Java](https://github.com/aws/aws-encryption-sdk-java)
* GIT - [aws-encryption-sdk-cli](https://github.com/aws/aws-encryption-sdk-cli/)
* GIT - [aws-encryption-sdk-python](https://github.com/aws/aws-encryption-sdk-python)



## [DynamoDB Encryption Client](https://docs.aws.amazon.com/ko_kr/dynamodb-encryption-client/latest/devguide/what-is-ddb-encrypt.html)

**Bookmark**

* [Amazon DynamoDB 암호화 클라이언트란 무엇입니까?](https://docs.aws.amazon.com/ko_kr/dynamodb-encryption-client/latest/devguide/what-is-ddb-encrypt.html)



## [AWS Signer](https://docs.aws.amazon.com/ko_kr/signer/latest/developerguide/Welcome.html)

**Bookmark**

* [Security in AWS Signer](https://docs.aws.amazon.com/ko_kr/signer/latest/developerguide/security.html)
* Blog - [Code Signing, a Trust and Integrity Control for AWS Lambda](https://aws.amazon.com/blogs/aws/new-code-signing-a-trust-and-integrity-control-for-aws-lambda/)
* Blog - [Best practices and advanced patterns for Lambda code signing](https://aws.amazon.com/ko/blogs/security/best-practices-and-advanced-patterns-for-lambda-code-signing/)

 
## 데이터 보안과 관련된 기타 유용한 링크들

* [What is Cryptography?](https://docs.aws.amazon.com/crypto/latest/userguide/awscryp-whatis-toplevel.html)
* [Cryptography Concepts](https://docs.aws.amazon.com/crypto/latest/userguide/cryptography-concepts.html)
* [Cryptographic Algorithms](https://docs.aws.amazon.com/crypto/latest/userguide/concepts-algorithms.html)
* [AWS Cryptographic Services and Tools](https://docs.aws.amazon.com/crypto/latest/userguide/awscryp-service-toplevel.html)
* [DynamoDB Encryption Client](https://docs.aws.amazon.com/crypto/latest/userguide/awscryp-service-ddb-client.html)
* [Other AWS Services that use Cryptography](https://docs.aws.amazon.com/crypto/latest/userguide/awscryp-service-other.html)
* [How to Choose an Encryption Tool or Service](https://docs.aws.amazon.com/crypto/latest/userguide/awscryp-choose-toplevel.html)
* [AWS PKI Services](https://docs.aws.amazon.com/crypto/latest/userguide/awspki-overview.html)
* [What is Public Key Infrastructure?](https://docs.aws.amazon.com/crypto/latest/userguide/awspki-whatis-toplevel.html)
* [PKI Concepts](https://docs.aws.amazon.com/crypto/latest/userguide/pki-concepts.html)
* [AWS Public Key Infrastructure (PKI) Services and Tools](https://docs.aws.amazon.com/crypto/latest/userguide/awspki-service-toplevel.html)
* [Other AWS Services that use X.509 Public Key Certificates](https://docs.aws.amazon.com/crypto/latest/userguide/awspki-service-other.html)
* [How to Choose a PKI Service](https://docs.aws.amazon.com/crypto/latest/userguide/awspki-choose-toplevel.html)
* GIT - [Post-quantum cryptography for s2n](https://github.com/awslabs/s2n/tree/master/pq-crypto) _- post-quantum 하이브리드 키교환 방식 코드를 담고 있는 s2n GIT hub 링크_
* GIT - [encryption-workshop](https://gitlab.aws.dev/ramlop/encryption-workshop)
* 가이드 - [Scan Git repositories for sensitive information and security issues by using git-secrets](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/scan-git-repositories-for-sensitive-information-and-security-issues-by-using-git-secrets.html)
* Ext. Blog - [S3 Ransomware Part 1: Attack Vector](https://rhinosecuritylabs.com/aws/s3-ransomware-part-1-attack-vector/)
* Blog - [Architecting for database encryption on AWS](https://aws.amazon.com/blogs/security/architecting-for-database-encryption-on-aws/)
* Blog - [TLS 1.2 will be required for all AWS FIPS endpoints beginning March 31, 2021](https://aws.amazon.com/blogs/security/tls-1-2-required-for-aws-fips-endpoints/)
* Blog - [Ransomware mitigation: Top 5 protections and recovery preparation actions](https://aws.amazon.com/ko/blogs/security/ransomware-mitigation-top-5-protections-and-recovery-preparation-actions/)
* Blog - [Assess your security posture to identify and remediate security gaps susceptible to ransomware](https://aws.amazon.com/blogs/publicsector/assess-your-security-posture-identify-remediate-security-gaps-ransomware/)
* Blog - [The Five Ws episode 2: Data Classification whitepaper](https://aws.amazon.com/blogs/security/the-five-ws-episode-2-data-classification-whitepaper/)
* Blog - [Introducing s2n-quic, a new open-source QUIC protocol implementation in Rust](https://aws.amazon.com/blogs/security/introducing-s2n-quic-open-source-protocol-rust/)
* Blog - [TLS 1.2 to become the minimum TLS protocol level for all AWS API endpoints](https://aws.amazon.com/ko/blogs/security/tls-1-2-required-for-aws-endpoints/)
* Blog - [Preparing today for a post-quantum cryptographic future](https://www.amazon.science/blog/preparing-today-for-a-post-quantum-cryptographic-future)

## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.



---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>