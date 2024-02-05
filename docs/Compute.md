# Compute

## [EC2](https://aws.amazon.com/ko/ec2/?nc2=h_m1)

Amazon Elastic Compute Cloud(EC2)는 안전하고 크기 조정이 가능한 컴퓨팅 파워를 클라우드에서 제공하는 웹 서비스입니다. EC2의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon EC2의 보안 - Linux](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-security.html)
* [Amazon EC2의 보안 - Windows](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ExamplePolicies_EC2.html)
* [Security - Nitro Enclaves](https://docs.aws.amazon.com/ko_kr/enclaves/latest/user/security.html)
* [Amazon EC2 Auto Scaling의 보안](https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/security.html)
* [Security - VM Import/Export](https://docs.aws.amazon.com/ko_kr/vm-import/latest/userguide/security.html)
* [Recycle Bin](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/recycle-bin.html)
* GIT - [AMIFinder](https://github.com/sebsto/AMIFinder)
* GIT - [ec2-security-groups-dumper](https://github.com/percolate/ec2-security-groups-dumper)
* GTI - [DumpsterDiver](https://github.com/securing/DumpsterDiver) _- 볼륨상의 중요 정보 패턴, 파일 타입 등에 대한 탐색하는 툴_
* GIT - [Netflix Bless : Short Term(수분) SSH 인증서 발급을 위한 람다 함수](https://github.com/Netflix/bless) _– SSH 인증서 유효기간을 수분으로 제한하여 발급하는 람다 함수_
* GIT - [LUNAR](https://github.com/lateralblast/lunar) _- CIS 기준으로 Linux, Docker 등을 보안 점검하는 스크립트_
* GIT - [DumpsterDiver](https://github.com/securing/DumpsterDiver) _- 볼륨상의 중요 정보 패턴, 파일 타입 등에 대한 탐색하는 툴_
* GIT - [Chaos Monkey : randomly terminates virtual machine instances and containers](https://github.com/netflix/chaosmonkey)
* GIT - [AWS Bottlerocket OS](https://github.com/bottlerocket-os/bottlerocket)
* GIT - [Getting started with AWS Graviton](https://github.com/aws/aws-graviton-getting-started/blob/master/README.md)
* GIT - [AWS Nitro Enclaves Certificate Manager Sample](https://github.com/aws-samples/aws-nitro-enclaves-certificate-manager-sample)
* GIT - [Nitro Enclaves Samples](https://github.com/aws/aws-nitro-enclaves-samples)
* 가이드 - [Check for single-host network entries in security group ingress rules for IPv4 and IPv6](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/check-for-single-host-network-entries-in-security-group-ingress-rules-for-ipv4-and-ipv6.html)
* 가이드 - [Ensure that an IAM profile is associated with an EC2 instance](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/ensure-that-an-iam-profile-is-associated-with-an-ec2-instance.html)
* 가이드 - [Monitor EC2 instance key pairs using AWS Config](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/monitor-ec2-instance-key-pairs-using-aws-config.html)
* 가이드 - [Allow EC2 instances write access to S3 buckets in AMS accounts](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/allow-ec2-instances-write-access-to-s3-buckets-in-ams-accounts.html)
* 가이드 - [Automatically attach an AWS managed policy for Systems Manager to EC2 instance profiles using Cloud Custodian and AWS CDK](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automatically-attach-an-aws-managed-policy-for-systems-manager-to-ec2-instance-profiles-using-cloud-custodian-and-aws-cdk.html)
* 가이드 - [Check EC2 instances for mandatory tags at launch](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/check-ec2-instances-for-mandatory-tags-at-launch.html)
* 가이드 - [Ensure that Amazon EC2 instances launch only in approved AWS Regions](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/ensure-that-amazon-ec2-instances-launch-only-in-approved-aws-regions.html)
* QuickStart - [AWS 기반 Linux 배스천 호스트](https://aws.amazon.com/ko/quickstart/architecture/linux-bastion/)
* QuickStart - [AWS의 원격 데스크톱 게이트웨이](https://aws.amazon.com/ko/quickstart/architecture/rd-gateway/)
* QuickStart - [Windows Server Update Services on AWS](https://aws.amazon.com/ko/quickstart/architecture/windows-server-update-services/)
* 동영상 - [Manage Patching for your Amazon Machine Images](https://www.youtube.com/watch?v=h5cq462pvAU&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=3)
* 동영상 - [Patching for your Amazon EC2 Instances](https://www.youtube.com/watch?v=ABtwRb9BFY4&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=5)
* Support - [Amazon EC2 인스턴스 시작 후 Windows 관리자 암호 검색](https://aws.amazon.com/ko/premiumsupport/knowledge-center/retrieve-windows-admin-password/)
* Workshop - [Nitro Enclaves Workshop](https://nitro-enclaves.workshop.aws/en/)
* Blog - [Creating an opportunistic IPSec mesh between EC2 instances](https://aws.amazon.com/blogs/security/creating-an-opportunistic-ipsec-mesh-between-ec2-instances/)
* Blog - [Automating notifications when AMI permissions change](https://aws.amazon.com/blogs/compute/automating-notifications-when-ami-permissions-change/)
* Blog - [How to Monitor Host-Based Intrusion Detection System Alerts on Amazon EC2 Instances](https://aws.amazon.com/ko/blogs/security/how-to-monitor-host-based-intrusion-detection-system-alerts-on-amazon-ec2-instances/) _– OSSEC(Open Source Security) HIDS의 로그를 기반으로 ElasticSearch, Kibana를 통해 가시화 시키는 예제_
* Blog(EXT) - [How to enable broadcast and multicast support on Amazon (AWS) EC2](https://www.buckhill.co.uk/blog/how-to-enable-broadcast-and-multicast-support-on-amazon-aws-ec2/2#a-software)
* Blog - [Seamlessly Join a Linux Instance to AWS Directory Service for Microsoft Active Directory](https://aws.amazon.com/blogs/aws/seamlessly-join-a-linux-instance-to-aws-directory-service-for-microsoft-active-directory/)
* Blog - [AWS Nitro Enclaves – Isolated EC2 Environments to Process Confidential Data](https://aws.amazon.com/blogs/aws/aws-nitro-enclaves-isolated-ec2-environments-to-process-confidential-data/)
* Blog - [How to automate incident response in the AWS Cloud for EC2 instances](https://aws.amazon.com/blogs/security/how-to-automate-incident-response-in-aws-cloud-for-ec2-instances/)
* Blog - [Automate domain join for Amazon EC2 instances from multiple AWS accounts and Regions](https://aws.amazon.com/blogs/security/automate-domain-join-for-amazon-ec2-instances-multiple-aws-accounts-regions/)
* Blog - [Add defense in depth against open firewalls, reverse proxies, and SSRF vulnerabilities with enhancements to the EC2 Instance Metadata Service](https://aws.amazon.com/ko/blogs/security/defense-in-depth-open-firewalls-reverse-proxies-ssrf-vulnerabilities-ec2-instance-metadata-service/)
* Blog - [Automating copying encrypted Amazon EBS snapshots across AWS accounts](https://aws.amazon.com/blogs/storage/automating-copying-encrypted-amazon-ebs-snapshots-across-aws-accounts/)
* Blog - [How to share encrypted AMIs across accounts to launch encrypted EC2 instances](https://aws.amazon.com/blogs/security/how-to-share-encrypted-amis-across-accounts-to-launch-encrypted-ec2-instances/)
* Blog - [How to confirm your automated Amazon EBS snapshots are still created after the TLS 1.2 uplift on AWS FIPS endpoints](https://aws.amazon.com/blogs/security/tls-1-2-confirm-your-connections/)
* Blog - [Use VPC endpoints with Amazon Timestream](https://aws.amazon.com/ko/blogs/database/use-vpc-endpoints-with-amazon-timestream/)
* Blog - [Use EC2 Instance Connect to provide secure SSH access to EC2 instances with private IP addresses](https://aws.amazon.com/blogs/security/use-ec2-instance-connect-to-provide-secure-ssh-access-to-ec2-instances-with-private-ip-addresses/)
* Blog - [Automating Amazon EBS snapshot and AMI management using Amazon DLM](https://aws.amazon.com/blogs/storage/automating-amazon-ebs-snapshot-and-ami-management-using-amazon-dlm/)
* Blog - [Confidential computing: an AWS perspective](https://aws.amazon.com/blogs/security/confidential-computing-an-aws-perspective/)
* Blog - [New – Attribute-Based Instance Type Selection for EC2 Auto Scaling and EC2 Fleet](https://aws.amazon.com/ko/blogs/aws/new-attribute-based-instance-type-selection-for-ec2-auto-scaling-and-ec2-fleet/)
* Blog - [Deploying SQL Server Always Encrypted with secure enclaves on Amazon EC2 bare metal instances](https://aws.amazon.com/ko/blogs/modernizing-with-aws/sql-server-always-encrypted-with-secure-enclaves/)
* Blog - [Why and how customers achieve FIPS-Compliance for .NET Workloads on AWS](https://aws.amazon.com/blogs/modernizing-with-aws/why-and-how-customers-achieve-fips-compliance-for-net-workloads-on-aws/)
* Blog - [Introducing Unified ID 2.0 Private Operator Services on AWS Using Nitro Enclaves](https://aws.amazon.com/blogs/industries/introducing-unified-id-2-0-private-operator-services-on-aws-using-nitro-enclaves/)
* Blog - [Use AWS Nitro Enclaves to perform computation of multiple sensitive datasets](https://aws.amazon.com/ko/blogs/compute/leveraging-aws-nitro-enclaves-to-perform-computation-of-multiple-sensitive-datasets/)
* Blog - [How to Use a CIS Hardened Image to Set Up an Amazon EC2 Mac Instance](https://aws.amazon.com/blogs/apn/how-to-use-a-cis-hardened-image-to-set-up-an-amazon-ec2-mac-instance/)
* Blog - [An AWS perspective on securely managing Windows Server infrastructure at scale](https://aws.amazon.com/blogs/modernizing-with-aws/aws-perspective-securely-managing-windows-server-infrastructure-scale/)


## [Lightsail](https://aws.amazon.com/ko/lightsail/?nc2=h_m1)

Amazon Lightsail은 간단한 VPS(가상 프라이빗 서버) 솔루션이 필요한 개발자, 소규모 비즈니스, 학생 및 다른 사용자가 AWS를 시작할 수 있는 가장 쉬운 방법입니다. Lightsail의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Lightsail 문서](https://lightsail.aws.amazon.com/ls/docs/ko_kr/all)
* Blog - [Deploying an Nginx-based HTTP/HTTPS load balancer with Amazon Lightsail](https://aws.amazon.com/blogs/compute/deploying-an-nginx-based-http-https-load-balancer-with-amazon-lightsail/)
* Blog - [Add defense in depth against open firewalls, reverse proxies, and SSRF vulnerabilities with enhancements to the EC2 Instance Metadata Service](https://aws.amazon.com/blogs/security/defense-in-depth-open-firewalls-reverse-proxies-ssrf-vulnerabilities-ec2-instance-metadata-service/)
* Blog - [Securely extend and access on-premises Active Directory domain controllers in AWS](https://aws.amazon.com/ko/blogs/security/securely-extend-and-access-on-premises-active-directory-domain-controllers-in-aws/)
* Blog - [Deep dive into NitroTPM and UEFI Secure Boot support in Amazon EC2](https://aws.amazon.com/ko/blogs/compute/deep-dive-into-nitrotpm-and-uefi-secure-boot-support-in-amazon-ec2/)

 
## [Lambda](https://aws.amazon.com/ko/lambda/?nc2=h_m1)

AWS Lambda를 사용하면 서버를 프로비저닝하거나 관리할 필요 없이 코드를 실행할 수 있습니다. Lambda의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Lambda의 보안](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/lambda-security.html)
* GIT - [Firecracker](https://github.com/firecracker-microvm/firecracker)
* GIT - [LambdaGuard - Lambda Audit Tool](https://github.com/Skyscanner/LambdaGuard) _- SonarQube를 이용해 람다 함수에 대한 정적분석 기능 제공_
* GIT - [AWS Lambda SAP OAuth Token Generator](https://github.com/aws-samples/aws-lambda-sap-oauth)
* Support - [Connect a Lambda function to a dedicated VPC](https://aws.amazon.com/es/premiumsupport/knowledge-center/lambda-dedicated-vpc/)
* Blog - [Best Practices for Developing on AWS Lambda](https://aws.amazon.com/blogs/architecture/best-practices-for-developing-on-aws-lambda/)
* Blog - [Automating the discovery of unused AWS Lambda functions](https://aws.amazon.com/blogs/mt/automating-the-discovery-of-unused-aws-lambda-functions/)
* Blog - [Gain Visibility into the Execution of Your AWS Lambda functions with AWS CloudTrail](https://aws.amazon.com/blogs/mt/gain-visibility-into-the-execution-of-your-aws-lambda-functions-with-aws-cloudtrail/)
* Blog - [Announcing improved VPC networking for AWS Lambda functions](https://aws.amazon.com/blogs/compute/announcing-improved-vpc-networking-for-aws-lambda-functions/)
* Blog - [Firecracker - Secure and fast microVMs for serverless computing](https://firecracker-microvm.github.io/)
* Blog - [Using AWS Lambda IAM condition keys for VPC settings](https://aws.amazon.com/blogs/compute/using-aws-lambda-iam-condition-keys-for-vpc-settings/)
* Blog - [Introducing AWS Lambda Extensions – In preview](https://aws.amazon.com/blogs/compute/introducing-aws-lambda-extensions-in-preview/)
* Blog - [Using AWS Lambda extensions to send logs to custom destinations](https://aws.amazon.com/blogs/compute/using-aws-lambda-extensions-to-send-logs-to-custom-destinations/)
* Blog - [New – Code Signing, a Trust and Integrity Control for AWS Lambda](https://aws.amazon.com/blogs/aws/new-code-signing-a-trust-and-integrity-control-for-aws-lambda/)
* Blog - [Performance and functionality improvements for AWS Lambda extensions](https://aws.amazon.com/blogs/compute/performance-and-functionality-improvements-for-aws-lambda-extensions/)
* Blog - [Introducing AWS SAM Pipelines: Automatically generate deployment pipelines for serverless applications](https://aws.amazon.com/blogs/compute/introducing-aws-sam-pipelines-automatically-generate-deployment-pipelines-for-serverless-applications/)
* Blog - [Announcing AWS Lambda Function URLs: Built-in HTTPS Endpoints for Single-Function Microservices](https://aws.amazon.com/blogs/aws/announcing-aws-lambda-function-urls-built-in-https-endpoints-for-single-function-microservices/)
* Blog - [Scaling AWS Lambda permissions with Attribute-Based Access Control (ABAC)](https://aws.amazon.com/blogs/compute/scaling-aws-lambda-permissions-with-attribute-based-access-control-abac/)
* Blog - [Building AWS Lambda governance and guardrails](https://aws.amazon.com/blogs/compute/building-aws-lambda-governance-and-guardrails/)

 
## [Batch](https://aws.amazon.com/ko/batch/?nc2=h_m1)

AWS Batch를 사용하면 개발자, 과학자 및 엔지니어가 AWS에서 수많은 배치 컴퓨팅 작업을 효율적으로 손쉽게 실행할 수 있습니다. Batch의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Batch의 보안](https://docs.aws.amazon.com/ko_kr/batch/latest/userguide/security.html)
* Blog - [Datavant Uses Batch to De-Identify Health Data](https://aws.amazon.com/blogs/startups/batch-deidentify-health-data/)

 
## [Elastic Beanstalk](https://aws.amazon.com/ko/elasticbeanstalk/?nc2=h_m1)

AWS Elastic Beanstalk는 Java, .NET, PHP, Node.js, Python, Ruby, Go, Docker를 사용하여 Apache, Nginx, Passenger, IIS와 같은 친숙한 서버에서 개발된 웹 애플리케이션 및 서비스를 간편하게 배포하고 조정할 수 있는 서비스입니다. Elastic Beanstalk의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Elastic Beanstalk 보안](https://docs.aws.amazon.com/ko_kr/elasticbeanstalk/latest/dg/security.html)
* Blog - [How to Control TLS Ciphers in Your AWS Elastic Beanstalk Application by Using AWS CloudFormation](https://aws.amazon.com/blogs/security/how-to-control-tls-ciphers-in-your-aws-elastic-beanstalk-application-by-using-aws-cloudformation/)
* GIT - [Elastic Beanstalk Roadmap](https://github.com/aws/elastic-beanstalk-roadmap)

 
## [Serverless Application Repository](https://aws.amazon.com/ko/serverless/serverlessrepo/?nc2=h_m1)

AWS Serverless Application Repository는 서버리스 애플리케이션용 관리형 리포지토리입니다. Serverless Application Repository의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Serverless Application Repository의 보안](https://docs.aws.amazon.com/ko_kr/serverlessrepo/latest/devguide/security.html)


## [EC2 Image Builder](https://aws.amazon.com/ko/image-builder/?nc1=h_ls)

EC2 Image Builder는 EC2 리눅스, 윈도우즈 서버의 이미지를 생성, 관리, 공유, 검증, 배포하는 부분을 간편하게 해 주는 서비스입니다. EC2 Image Builder의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in EC2 Image Builder](https://docs.aws.amazon.com/ko_kr/imagebuilder/latest/userguide/image-builder-security.html)
* Blog - [Quickly build STIG-compliant Amazon Machine Images using Amazon EC2 Image Builder](https://aws.amazon.com/ko/blogs/security/quickly-build-stig-compliant-amazon-machine-images-using-amazon-ec2-image-builder/)
* Blog - [Deploying CIS Level 1 hardened AMIs with Amazon EC2 Image Builder](https://aws.amazon.com/blogs/devops/deploying-cis-level-1-hardened-amis-with-amazon-ec2-image-builder/)



## [Launch Wizard for SQL Server](https://aws.amazon.com/launchwizard/) 

Launch Wizard for SQL Server는 EC2상에 고가용성의 SQL 서버환경을 구성, 배포를 간편하게 수행할 수 있도록 해주는 서비스입니다. Launch Wizard의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Launch Wizard Security](https://docs.aws.amazon.com/ko_kr/launchwizard/latest/userguide/launch-wizard-security.html)


## [Outposts](https://aws.amazon.com/ko/outposts/)

AWS Outposts는 네이티브 AWS 서비스, 인프라 및 운영 모델을 사실상 모든 데이터 센터, 코로케이션 공간 또는 온프레미스 시설로 옮길 수 있습니다. Outposts의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Outposts 에서의 보안](https://docs.aws.amazon.com/ko_kr/outposts/latest/userguide/security.html)
* Blog - [Managing and Securing AWS Outposts Instances using AWS Systems Manager, Amazon Inspector, and Amazon GuardDuty](https://aws.amazon.com/ko/blogs/compute/managing-and-securing-aws-outposts-instances-using-aws-systems-manager-amazon-inspector-and-amazon-guardduty/)



## [Wavelength](https://aws.amazon.com/ko/wavelength/)

AWS Wavelength Zone은 AWS 컴퓨팅 및 스토리지 서비스를 통신 서비스 공급자(CSP) 데이터 센터의 5G 네트워크 엣지에 포함하여 5G 디바이스에서의 애플리케이션 트래픽이 통신 네트워크 내의 Wavelength Zone에서 실행되는 애플리케이션 서버로 전송될 수 있도록 하는 AWS 인프라 배포 환경입니다. AWS Wavelength의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in AWS Wavelength](https://docs.aws.amazon.com/ko_kr/wavelength/latest/developerguide/security.html)



## [ParallelCluster](https://docs.aws.amazon.com/ko_kr/parallelcluster/latest/ug/what-is-aws-parallelcluster.html)

AWS ParallelCluster는 AWS 클라우드에서 HPC(고성능 컴퓨팅) 클러스터를 배포하고 관리할 수 있는 AWS 지원 오픈 소스 클러스터 관리 도구입니다. ParallelCluster의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS ParallelCluster의 보안](https://docs.aws.amazon.com/ko_kr/parallelcluster/latest/ug/security.html)


## [AWS End-of-Support Migration Program (EMP) for Windows Server](https://docs.aws.amazon.com/ko_kr/emp/latest/userguide/emp-what-is.html)

Windows Server용 AWS EMP(End-of-Support Migration Program)는 코드를 리팩터링하지 않고 Windows Server 2003, 2008 및 2008 R2에서 AWS의 최신 지원 버전으로 레거시 애플리케이션을 마이그레이션합니다. AWS End-of-Support Migration Program (EMP) for Windows Server의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [What Is AWS End-of-Support Migration Program (EMP) for Windows Server?](https://docs.aws.amazon.com/ko_kr/emp/latest/userguide/emp-what-is.html)
* [Security in AWS End-of-Support Migration Program (EMP) for Windows Server](https://docs.aws.amazon.com/ko_kr/emp/latest/userguide/emp-security.html)
 
 
## [AWS SAM](https://docs.aws.amazon.com/ko_kr/parallelcluster/latest/ug/what-is-aws-parallelcluster.html)

AWS Serverless Application Model(AWS SAM)은 AWS에서 서버리스 애플리케이션을 구축하는 데 사용할 수 있는 오픈 소스 프레임워크입니다. 이 프레임워크는 서버리스 애플리케이션을 정의하기 위한 템플릿 사양과 명령줄 인터페이스(CLI) 도구를 제공합니다. AWS SAM의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Serverless Application Model(AWS SAM)란 무엇입니까?](https://docs.aws.amazon.com/ko_kr/serverless-application-model/latest/developerguide/what-is-sam.html)


## Compute과 관련된 기타 유용한 링크들

* 백서 - [Serverless Application Lens](https://d1.awsstatic.com/whitepapers/architecture/AWS-Serverless-Applications-Lens.pdf) _- Well-Architected 프레임웍 기준으로 서버리스 아키텍쳐를 설계하는 방법에 대한 안내, 2019년 12월_
* GIT - [Sessions With SAM](https://github.com/aws-samples/sessions-with-aws-sam)
* Blog - [AWS Secure Environment Accelerator (ASEA) connectivity with VMware Cloud on AWS](https://aws.amazon.com/blogs/publicsector/aws-secure-environment-accelerator-connectivity-with-vmware-cloud-on-aws/)


## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.


---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>