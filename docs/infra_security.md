# 인프라 보안 (Infra Security)

AWS상의 전체 인프라에 대한 통제와 데이터 보호 수준을 향상시키고 위협에 노출되는 부분을 최소화시켜 주는 기능과 관련된 영역입니다. 이 영역에 해당하는 AWS 보안 서비스들에는 다음과 같은 것들이 있습니다.
 
	
## [Amazon Systems Manager](https://aws.amazon.com/ko/systems-manager/)

OS 패치, 안전한 시스템 이미지 생성, 안전한 OS설정 등의 작업을 비롯하여 Amazon EC2 및 온프레미스 환경의 구성 및 관리 편의성을 향상시켜주는 기능을 제공합니다. Amazon System Manager를 보안 관점에서 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Systems Manager의 보안](https://docs.aws.amazon.com/ko_kr/systems-manager/latest/userguide/security.html)
* [AWS Systems Manager Incident Manager의 보안](https://docs.aws.amazon.com/ko_kr/incident-manager/latest/userguide/security.html)
* GIT - [Amazon SSM Agent](https://github.com/aws/amazon-ssm-agent)
* GIT - [AwsApiActionDemo](https://github.com/nanalakshmanan/AwsApiActionDemo)
* GIT - [SSM Agent Toolkit - Windows](https://github.com/awslabs/aws-support-tools/tree/master/Systems%20Manager/SSMAgent-Toolkit-Windows)
* GIT - [SSM Agent Toolkit - Linux](https://github.com/awslabs/aws-support-tools/tree/master/Systems%20Manager/SSMAGENT-TOOLKIT-LINUX)
* GIT - [Operational Management: Inventory, Patching, and Compliance](https://github.com/aws-samples/aws-management-and-governance-samples/tree/master/AWSSystemsManager/CentralizedPatchManagement)
* 동영상 - [Manage Distribution of Software Packages with AWS Systems Manager Distributor](https://www.youtube.com/watch?v=AvQWkfgEQI8&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=8)
* 동영상 - [Aggregate and Resolve Operational Issues Using AWS Systems Manager OpsCenter](https://www.youtube.com/watch?v=r6ilQdxLcqY&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=22)
* Support - [AWS Systems Manager를 통해 SSH 터널을 사용하여 프라이빗 VPC 리소스에 액세스하려면 어떻게 해야 하나요?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/systems-manager-ssh-vpc-resources/)
* Support - [연결 끊김 상태의 관리형 인스턴스 문제 해결](https://aws.amazon.com/ko/premiumsupport/knowledge-center/ssm-connection-lost-status/)
* SUPPORT - [Systems Manager 자동화를 사용하여 Amazon EC2 인스턴스에서 인스턴스 메타데이터에 액세스하는 데 IMDSv2만 사용하도록 하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/ssm-ec2-enforce-imdsv2/?nc1=h_ls)
* Blog - [Replacing a Bastion Host with Amazon EC2 Systems Manager](https://aws.amazon.com/ko/blogs/mt/replacing-a-bastion-host-with-amazon-ec2-systems-manager/) _– System Manager의 Run Command를 활용하여 Bastion Host를 대체하는 방법_
* Blog - [Streaming AWS Systems Manager Run Command output to Amazon CloudWatch Logs](https://aws.amazon.com/blogs/mt/streaming-aws-systems-manager-run-command-output-to-amazon-cloudwatch-logs/)
* Blog - [New – AWS Systems Manager Session Manager for Shell Access to EC2 Instances](https://aws.amazon.com/ko/blogs/aws/new-session-manager/) _– System Manager의 Session Manager를 활용하여 인스턴스로 Shell세션을 만들수 있는 기능에 대한 소개를 하는 블로그_
* Blog - [Port Forwarding Using AWS System Manager Session Manager](https://aws.amazon.com/blogs/aws/new-port-forwarding-using-aws-system-manager-sessions-manager/)
* Blog - [Managing Secrets for Amazon ECS Applications Using Parameter Store and IAM Roles for Tasks](https://aws.amazon.com/blogs/compute/managing-secrets-for-amazon-ecs-applications-using-parameter-store-and-iam-roles-for-tasks/)
* Blog - [Manage Instances at Scale without SSH Access Using EC2 Run Command](https://aws.amazon.com/blogs/aws/manage-instances-at-scale-without-ssh-access-using-ec2-run-command/)
* Blog - [How to Remediate Amazon Inspector Security Findings Automatically](https://aws.amazon.com/blogs/security/how-to-remediate-amazon-inspector-security-findings-automatically/)
* Blog - [Preventing blacklisted applications with AWS Systems Manager and AWS Config](https://aws.amazon.com/blogs/mt/preventing-blacklisted-applications-with-aws-systems-manager-and-aws-config/)
* Blog - [Providing temporary instance permissions with AWS Systems Manager Automations](https://aws.amazon.com/blogs/mt/providing-temporary-instance-permissions-with-aws-systems-manager-automations/)
* Blog - [How do I create VPC endpoints so that I can use Systems Manager to manage private EC2 instances without internet access?](https://aws.amazon.com/premiumsupport/knowledge-center/ec2-systems-manager-vpc-endpoints/)
* Blog - [Build your own software asset governance platform on AWS](https://aws.amazon.com/blogs/mt/build-your-own-software-asset-governance-platform-on-aws/)
* Blog - [How to automate SCAP testing with AWS Systems Manager and Security Hub](https://aws.amazon.com/blogs/security/how-to-automate-scap-testing-with-aws-systems-manager-and-security-hub/)
* Blog - [How Moody’s uses AWS Systems Manager to patch servers across multiple cloud providers](https://aws.amazon.com/blogs/mt/how-moodys-uses-aws-systems-manager-to-patch-servers-across-multiple-cloud-providers/)
* Blog - [Resolve IT Incidents Faster with Incident Manager, a New Capability of AWS Systems Manager](https://aws.amazon.com/blogs/aws/resolve-it-incidents-faster-with-incident-manager-a-new-capability-of-aws-systems-manager/)
* Blog - [AWS Systems Manager Incident Manager integration with Amazon CloudWatch](https://aws.amazon.com/blogs/mt/aws-systems-manager-incident-manager-integration-amazon-cloudwatch/)
* Blog - [Creating contacts, escalation plans, and response plans in AWS Systems Manager Incident Manager](https://aws.amazon.com/blogs/mt/creating-contacts-escalation-plans-response-plans-aws-systems-manager-incident-manager/)
* Blog - [Configure Session Manager access for federated users using SAML session tags](https://aws.amazon.com/blogs/mt/configure-session-manager-access-for-federated-users-using-saml-session-tags/)
* Blog - [Configuring AWS Systems Manager Session Manager run as support for federated users using session tags](https://aws.amazon.com/ko/blogs/mt/configuring-aws-systems-manager-session-manager-support-federated-users-using-session-tags/)
* Blog - [Manage instances using AWS Systems Manager Quick Setup across AWS Organization](https://aws.amazon.com/blogs/mt/manage-instances-using-aws-systems-manager-quick-setup-across-aws-organization/)
* Blog - [New – Query for AWS Regions, Endpoints, and More Using AWS Systems Manager Parameter Store](https://aws.amazon.com/blogs/aws/new-query-for-aws-regions-endpoints-and-more-using-aws-systems-manager-parameter-store/)
* Blog - [How Rackspace uses AWS Systems Manager for instance patching across multi-cloud and hybrid environments](https://aws.amazon.com/ko/blogs/mt/how-rackspace-uses-aws-systems-manager-for-instance-patching-across-multi-cloud-and-hybrid-environments/)
* Blog - [Operational insights in Systems Manager OpsCenter help you identify duplicate issues and noisy event sources](https://aws.amazon.com/ko/blogs/mt/operational-insights-in-systems-manager-opscenter-help-you-identify-duplicate-issues-and-noisy-event-sources/)
* Blog - [How to automate incident response to security events with AWS Systems Manager Incident Manager](https://aws.amazon.com/blogs/security/how-to-automate-incident-response-to-security-events-with-aws-systems-manager-incident-manager/)
* Blog - [Centralized multi-account and multi-Region patching with AWS Systems Manager Automation](https://aws.amazon.com/blogs/mt/centralized-multi-account-and-multi-region-patching-with-aws-systems-manager-automation/)
* Blog - [Avoid zero-day vulnerabilities with same-day security patching using AWS Systems Manager](https://aws.amazon.com/blogs/mt/avoid-zero-day-vulnerabilities-same-day-security-patching-aws-systems-manager/)
* Blog - [Simplifying Active Directory domain join with AWS Systems Manager](https://aws.amazon.com/blogs/modernizing-with-aws/simplifying-active-directory-domain-join-with-aws-systems-manager/)



## [Amazon VPC(Virtual Private Cloud)](https://aws.amazon.com/ko/vpc/)

고객들이 본인의 AWS리소스들을 다른 고객과 완벽하게 분리된 환경에서 운영할 수 있도록 해주는 가상 사설 네트웍을 제공합니다. Amazon VPC를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [VPC 보안](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/secure-intro.html)
* [VPC 피어링에 대한 자격 증명 및 액세스 관리](https://docs.aws.amazon.com/ko_kr/vpc/latest/peering/security-iam.html)
* [What is Traffic Mirroring?](https://docs.aws.amazon.com/ko_kr/vpc/latest/mirroring/what-is-traffic-mirroring.html)
* [Identity and access management for VPC Reachability Analyzer](https://docs.aws.amazon.com/ko_kr/vpc/latest/reachability/identity-access-management.html)
* [Transit Gateway의 인증 및 액세스 제어](https://docs.aws.amazon.com/ko_kr/vpc/latest/tgw/transit-gateway-authentication-access-control.html)
* [Identity and access management for AWS Network Manager](https://docs.aws.amazon.com/vpc/latest/tgwnm/nm-security-iam.html)
* [VPC 엔드포인트 및 VPC 엔드포인트 서비스에 대한 ID 및 액세스 관리](https://docs.aws.amazon.com/ko_kr/vpc/latest/privatelink/vpc-endpoints-iam.html)
* [AWS Cloud WAN security](https://docs.aws.amazon.com/ko_kr/vpc/latest/cloudwan/cloudwan-security.html)
* 동영상 - [How can I search CloudTrail event history to determine how a security group or resource was changed?](https://www.youtube.com/watch?v=PDaw7WtOSKM)
* Best Practice - [Accessing VPC Endpoints From Remote Networks](https://d0.awsstatic.com/aws-answers/Accessing_VPC_Endpoints_from_Remote_Networks.pdf) _– 온프레미스 등 VPC 외부에서 VPC S3 Endpoint로의 안전하고 가용성 있는 접근 통로 구축에 대한 소개_
* Best Practice - [Controlling VPC Egress Traffic](https://d0.awsstatic.com/aws-answers/Controlling_VPC_Egress_Traffic.pdf) _– VPC Outbound 트래픽 제어에 대한 AWS 제공 기능들 및 파트너 솔루션에 대한 소개_
* Best Practice - [VPC Security Capabilities](https://d0.awsstatic.com/aws-answers/VPC_Security_Capabilities.pdf) _– VPC가 제공하는 각종 보안 기능들과 WAF, Shield 및 활용가능한 네트웍 파트너 솔루션들에 대한 소개_
* Best Practice - [Single Region Multi-VPC Connectivity](https://d0.awsstatic.com/aws-answers/AWS_Single_Region_Multi_VPC_Connectivity.pdf) _– 단일 리전에서 peering, DX 등을 이용하여 멀티 VPC에 대한 연결을 디자인 하기 위한 옵션들을 소개_
* Best Practice - [Multiple Region Multi-VPC Connectivity](https://d1.awsstatic.com/aws-answers/AWS_Multiple_Region_Multi_VPC_Connectivity.pdf) _– 멀티 리전에서 VPN, DX, WAN 등을 이용하여 멀티 VPC에 대한 연결을 디자인 하기 위한 옵션들을 소개_
* Best Practice - [AWS Global Transit Network](https://d1.awsstatic.com/aws-answers/aws-global-transit-network.pdf) _– 글로벌 Transit 네트워크를 구축할 수 있는 Cisco, Aviatrix 등 파트너 솔루션들에 대한 소개_
* 백서 - [Amazon Virtual Private Cloud Connectivity Options](https://d1.awsstatic.com/whitepapers/aws-amazon-vpc-connectivity-options.pdf?did=wp_card&trk=wp_card)
* Support - [내 VPC에서 NAT 게이트웨이를 통해 트래픽에 대한 최고 원인 제공자를 찾으려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/vpc-find-traffic-sources-nat-gateway/)
* Support - [NAT 게이트웨이에 대한 인바운드 인터넷 트래픽 분석](https://aws.amazon.com/ko/premiumsupport/knowledge-center/vpc-analyze-inbound-traffic-nat-gateway/)
* Quick Starts - [확장 가능한 모듈식 VPC 아키텍처](https://aws.amazon.com/ko/quickstart/architecture/vpc/)
* GIT - [aws-securitygroup-grapher](https://github.com/jeanlouisferey/aws-securitygroup-grapher)
* GIT - [aws-security-viz -- A tool to visualize aws security groups](https://github.com/anaynayak/aws-security-viz)
* GIT - [CloudMapper](https://github.com/duo-labs/cloudmapper) _- VPC상의 환경 구성에 대해 Visualize하는 툴_
* GIT - [aws-vpc-flow-log-appender](https://github.com/aws-samples/aws-vpc-flow-log-appender)
* Blog - [Analyzing VPC Flow Logs with Amazon Kinesis Firehose, Amazon Athena, and Amazon QuickSight](https://aws.amazon.com/blogs/big-data/analyzing-vpc-flow-logs-with-amazon-kinesis-firehose-amazon-athena-and-amazon-quicksight/)
* Blog - [Learn From Your VPC Flow Logs With Additional Meta-Data](https://aws.amazon.com/blogs/aws/learn-from-your-vpc-flow-logs-with-additional-meta-data/)
* Blog - [One to Many: Evolving VPC Design](https://aws.amazon.com/blogs/architecture/one-to-many-evolving-vpc-design/)
* Blog - [AWS networking capabilities give you choices for hybrid cloud connectivity, but which service works best for your use case?](https://aws.amazon.com/blogs/publicsector/aws-networking-capabilities-gives-you-choices-for-hybrid-cloud-connectivity-but-which-service-works-best-for-your-use-case/)
* Blog - [Automating AWS Transit Gateway attachments to a transit gateway in a central account](https://aws.amazon.com/blogs/networking-and-content-delivery/automating-aws-transit-gateway-attachments-to-a-transit-gateway-in-a-central-account/)
* Blog - [VPC sharing: A new approach to multiple accounts and VPC management](https://aws.amazon.com/blogs/networking-and-content-delivery/vpc-sharing-a-new-approach-to-multiple-accounts-and-vpc-management/)
* Blog - [How to Address the PCI DSS Requirements for Data Encryption in Transit Using Amazon VPC](https://aws.amazon.com/blogs/security/how-to-address-the-pci-dss-requirements-for-data-encryption-in-transit-using-amazon-vpc/)
* Blog - [New – VPC Ingress Routing – Simplifying Integration of Third-Party Appliances](https://aws.amazon.com/blogs/aws/new-vpc-ingress-routing-simplifying-integration-of-third-party-appliances/)
* Blog - [Overlay Multicast in Amazon Virtual Private Cloud](https://aws.amazon.com/articles/overlay-multicast-in-amazon-virtual-private-cloud/)
* Blog - [How to set up an outbound VPC proxy with domain whitelisting and content filtering](https://aws.amazon.com/blogs/security/how-to-set-up-an-outbound-vpc-proxy-with-domain-whitelisting-and-content-filtering/)
* Blog - [How to add DNS filtering to your NAT instance with Squid](https://aws.amazon.com/blogs/security/how-to-add-dns-filtering-to-your-nat-instance-with-squid/)
* Blog - [VPC Reachability Analyzer](https://aws.amazon.com/blogs/aws/new-vpc-insights-analyzes-reachability-and-visibility-in-vpcs/)
* Blog - [Securing ingress using security solutions and AWS Transit Gateway](https://aws.amazon.com/blogs/networking-and-content-delivery/securing-ingress-using-security-solutions-and-aws-transit-gateway/)
* Blog - [VPC sharing: key considerations and best practices](https://aws.amazon.com/blogs/networking-and-content-delivery/vpc-sharing-key-considerations-and-best-practices/)
* Blog - [Mirror production traffic to test environment with VPC Traffic Mirroring](https://aws.amazon.com/blogs/networking-and-content-delivery/mirror-production-traffic-to-test-environment-with-vpc-traffic-mirroring/)
* Blog - [Automating connectivity assessments with VPC Reachability Analyzer](https://aws.amazon.com/blogs/networking-and-content-delivery/automating-connectivity-assessments-with-vpc-reachability-analyzer/)
* Blog - [Automating service discovery using AWS Transit Gateway Multicast with IGMP](https://aws.amazon.com/blogs/networking-and-content-delivery/automating-service-discovery-using-aws-transit-gateway-multicast-with-igmp/)
* Blog - [Monitoring AWS Transit Gateway route limits using a serverless architecture](https://aws.amazon.com/blogs/networking-and-content-delivery/monitoring-aws-transit-gateway-route-limits-using-a-serverless-architecture/)
* Blog - [Integrating Network Connectivity Testing with Infrastructure Deployment](https://aws.amazon.com/blogs/networking-and-content-delivery/integrating-network-connectivity-testing-with-infrastructure-deployment/)
* Blog - [Easily Manage Security Group Rules with the New Security Group Rule ID](https://aws.amazon.com/ko/blogs/aws/easily-manage-security-group-rules-with-the-new-security-group-rule-id/)
* Blog - [Leveraging AWS PrivateLink for volumetric data processing](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/leveraging-aws-privatelink-for-volumetric-data-processing/)
* Blog - [Inspect Subnet to Subnet traffic with Amazon VPC More Specific Routing](https://aws.amazon.com/ko/blogs/aws/inspect-subnet-to-subnet-traffic-with-amazon-vpc-more-specific-routing/)
* Blog - [Building an egress VPC with AWS Transit Gateway and the AWS CDK](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/building-an-egress-vpc-with-aws-transit-gateway-and-the-aws-cdk/)
* Blog - [Analyze VPC Flow Logs with point-and-click Amazon Athena integration](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/analyze-vpc-flow-logs-with-point-and-click-amazon-athena-integration/)
* Blog - [How to solve Private IP exhaustion with Private NAT Solution](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/how-to-solve-private-ip-exhaustion-with-private-nat-solution/)
* Blog - [Scale traffic using multiple Interface Endpoints](https://aws.amazon.com/blogs/networking-and-content-delivery/scale-traffic-using-multiple-interface-endpoints/)
* Blog - [Integrating AWS Transit Gateway with AWS PrivateLink and Amazon Route 53 Resolver](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/integrating-aws-transit-gateway-with-aws-privatelink-and-amazon-route-53-resolver/)
* Blog - [How NLCHI provides hybrid access to their EHR system through AWS PrivateLink](https://aws.amazon.com/blogs/publicsector/how-nlchi-provides-hybrid-access-ehr-system-aws-privatelink/)
* Blog - [Amazon VPC Routing Enhancements Allow You to Inspect Traffic Between Subnets In a VPC](https://aws.amazon.com/blogs/aws/inspect-subnet-to-subnet-traffic-with-amazon-vpc-more-specific-routing/)
* Blog - [Automatically update security groups for Amazon CloudFront IP ranges using AWS Lambda](https://aws.amazon.com/blogs/security/automatically-update-security-groups-for-amazon-cloudfront-ip-ranges-using-aws-lambda/)
* Blog - [Automate Networking foundation in multi-account environments](https://aws.amazon.com/blogs/networking-and-content-delivery/automate-networking-foundation-in-multi-account-environments/)
* Blog - [Optimize performance and reduce costs for network analytics with VPC Flow Logs in Apache Parquet format](https://aws.amazon.com/ko/blogs/big-data/optimize-performance-and-reduce-costs-for-network-analytics-with-vpc-flow-logs-in-apache-parquet-format/)
* Blog - [Amazon VPC Network Access Analyzer](https://aws.amazon.com/ko/blogs/aws/new-amazon-vpc-network-access-analyzer/)
* Blog - [Automated VPC prefix list population for cross-Region and in-Region security group referencing](https://aws.amazon.com/blogs/networking-and-content-delivery/automated-vpc-prefix-list-population-for-cross-region-and-in-region-security-group-referencing/)
* Blog - [Reduce Cost and Increase Security with Amazon VPC Endpoints](https://aws.amazon.com/blogs/architecture/reduce-cost-and-increase-security-with-amazon-vpc-endpoints/)
* Blog - [Introduction to Traffic Mirroring to GWLB Endpoints as Target](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/introduction-to-traffic-mirroring-to-gwlb-endpoints-as-target/)
* Blog - [Introduction to Traffic Mirroring to GWLB Endpoints as Target](https://aws.amazon.com/blogs/networking-and-content-delivery/introduction-to-traffic-mirroring-to-gwlb-endpoints-as-target/)
* Blog - [Introducing VPC Flow Logs for AWS Transit Gateway](https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-vpc-flow-logs-for-aws-transit-gateway/)
* Blog - [Identifying publicly accessible resources with Amazon VPC Network Access Analyzer](https://aws.amazon.com/blogs/security/identifying-publicly-accessible-resources-with-amazon-vpc-network-access-analyzer/)
* Blog - [Introducing Amazon VPC Flow Logs to Kinesis Data Firehose](https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-amazon-vpc-flow-logs-kinesis-data-firehose/)

## [AWS Shield](https://aws.amazon.com/ko/shield/)

AWS 상의 워크로드 환경을 디도스 공격으로 부터 방어하는 관리형 디도스 방어 서비스입니다. AWS Shield를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Shield 의 보안](https://docs.aws.amazon.com/ko_kr/waf/latest/developerguide/shd-security.html)
* Best Practice - [Denial of Service Attack Mitigation on AWS](https://aws.amazon.com/ko/answers/networking/aws-ddos-attack-mitigation/) _– AWS 워크로드에 대한 디도스 방어 능력을 향상시키기 위한 아키텍쳐 설계 원칙들을 소개_
* TIP - [AWS Shield Engagement Lambda](https://s3.amazonaws.com/aws-shield-lambda/ShieldEngagementLambda.pdf) _- SRT 에스컬레이션 람다 함수_
* 동영상 [AWS Cloud 2017] - [AWS Shield를 통한 DDoS 대비 복원성 강한 AWS 보안 아키텍처 구성](https://www.youtube.com/watch?v=aetVvzrumIQ)
* 동영상 [AWS reInvent 2017] - [Automating DDoS Response in the Cloud (SID324)](https://www.youtube.com/watch?v=6pQ3j4IcpY8&feature=youtu.be&t=959) _- 리인벤트에 소개된 디도스 데모 영상_
* 동영상 - [Getting started with AWS Shield Advanced](https://www.youtube.com/watch?v=b1rOUehg4XA)
* 동영상 - [Validating your AWS Shield Advanced deployment and configuration](https://www.youtube.com/watch?v=LZSr0iLOblM)
* Blog - [How to Help Protect Dynamic Web Applications Against DDoS Attacks by Using Amazon CloudFront and Amazon Route 53](https://aws.amazon.com/ko/blogs/security/how-to-protect-dynamic-web-applications-against-ddos-attacks-by-using-amazon-cloudfront-and-amazon-route-53/)
* Blog - [How to defend games against DDoS attacks](https://aws.amazon.com/blogs/gametech/ddos/)
* Blog - [AWS 기반 게임 개발자를 위한 안내서 – 1부. DDoS 공격 방어 방법](https://aws.amazon.com/ko/blogs/korea/anti-ddos-for-game/)
* Blog - [Set up centralized monitoring for DDoS events and auto-remediate noncompliant resources](https://aws.amazon.com/blogs/security/set-up-centralized-monitoring-for-ddos-events-and-auto-remediate-noncompliant-resources/)
* Blog - [How to protect a self-managed DNS service against DDoS attacks using AWS Global Accelerator and AWS Shield Advanced](https://aws.amazon.com/blogs/security/how-to-protect-a-self-managed-dns-service-against-ddos-attacks-using-aws-global-accelerator-and-aws-shield-advanced/)
* Blog - [How to estimate your AWS WAF and AWS Shield Advanced cost?](https://aws.amazon.com/blogs/aws-cost-management/estimate-your-aws-waf-and-aws-shield-advanced-cost/)
* Blog - [AWS Shield threat landscape review: 2020 year-in-review](https://aws.amazon.com/blogs/security/aws-shield-threat-landscape-review-2020-year-in-review/)
* Blog - [Automatic Application Layer DDoS Mitigation](https://aws.amazon.com/ko/blogs/aws/aws-shield-advanced-update-automatic-application-layer-ddos-mitigation/)
* Blog - [Calculating data transfer leveraging Amazon VPC flow logs](https://aws.amazon.com/blogs/networking-and-content-delivery/calculating-data-transfer-leveraging-amazon-vpc-flow-logs/)

 

## [AWS WAF(Web Application Firewall)](https://aws.amazon.com/ko/waf/)

고객 웹 애플리케이션을 일반적인 웹 취약점 기반 공격들로 부터 보호하고 사용성과 보안을 향상시키는 기능을 제공합니다. AWS WAF를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다. AWS WAF API가 개선되었습니다. 이에따라, 기존 버전에 대한 안내는 아래에 Classic 이라는 Prefix를 붙여서 구분하였습니다.

**Bookmark**

* [AWS WAF 의 보안](https://docs.aws.amazon.com/ko_kr/waf/latest/developerguide/security.html)
* [AWS WAF 클래식의 보안](https://docs.aws.amazon.com/ko_kr/waf/latest/developerguide/classic-security.html)
* [MaxMind GeoIP2](https://www.maxmind.com/en/geoip2-city-database-accuracy) _- WAF GEO 기반 Rule에 사용되는 GeoIP정보 제공 싸이트_
* Support - [AWS WAF를 사용하여 사용자 에이전트 헤더가 포함되지 않은 HTTP 요청을 차단하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/waf-block-http-requests-no-user-agent/)
* EXT. - [Introduction to OWASP Top 10 2021(DRAFT FOR PEER REVIEW)](https://owasp.org/Top10/)
* GIT - [AWS WAF & TrendMicro DeepSecurity 연동](https://github.com/deep-security/aws-waf) _– DeepSecurity의 탐지 내역을 기반으로 WAF 룰셋과 연동하기_
* GIT - [How to use AWS WAF to filter incoming traffic from embargoed countries](https://github.com/aws-samples/aws-waf-embargoed-countries-ofac)
* GIT - [aws-waf-sample](https://github.com/aws-samples/aws-waf-sample)
* QuickStart - [AWS WAF Security Automations](https://aws.amazon.com/ko/solutions/implementations/aws-waf-security-automations/)
* Blog - [How to use AWS WAF to filter incoming traffic from embargoed countries](https://aws.amazon.com/blogs/security/how-to-use-aws-waf-to-filter-incoming-traffic-from-embargoed-countries/)
* Blog - [Creating web access control lists using Fortinet Managed Rules set from AWS Marketplace](https://aws.amazon.com/blogs/awsmarketplace/creating-web-access-control-lists-using-fortinet-managed-rules-set-from-aws-marketplace/)
* Blog - [Trimming AWS WAF logs with Amazon Kinesis Firehose transformations](https://aws.amazon.com/blogs/security/trimming-aws-waf-logs-with-amazon-kinesis-firehose-transformations/)
* Blog - [How to analyze AWS WAF logs using Amazon Elasticsearch Service](https://aws.amazon.com/blogs/security/how-to-analyze-aws-waf-logs-using-amazon-elasticsearch-service/)
* Blog - [Amazon API Gateway adds support for AWS WAF](https://aws.amazon.com/blogs/compute/amazon-api-gateway-adds-support-for-aws-waf/)
* Blog - [Protecting your API using Amazon API Gateway and AWS WAF — Part I](https://aws.amazon.com/blogs/compute/protecting-your-api-using-amazon-api-gateway-and-aws-waf-part-i/)
* Blog - [Protecting your API using Amazon API Gateway and AWS WAF — Part 2](https://aws.amazon.com/blogs/compute/protecting-your-api-using-amazon-api-gateway-and-aws-waf-part-2/)
* Blog - [How to Prevent Hotlinking by Using AWS WAF, Amazon CloudFront, and Referer Checking](https://aws.amazon.com/ko/blogs/security/how-to-prevent-hotlinking-by-using-aws-waf-amazon-cloudfront-and-referer-checking/) _– 외부 싸이트의 허가받지 않은 링킹(Hot Linking)을 탐지/보호하는 법_
* Blog - [Increase Security Posture and Troubleshoot Service Delivery with Splunk & New AWS WAF Full Logs Feature](https://www.splunk.com/blog/2018/09/10/increase-security-posture-and-troubleshoot-service-delivery-with-splunk-new-aws-waf-full-logs-feature.html)
* Blog - [Detect suspicious IP addresses with the Amazon SageMaker IP Insights algorithm](https://aws.amazon.com/blogs/machine-learning/detect-suspicious-ip-addresses-with-the-amazon-sagemaker-ip-insights-algorithm/)
* Blog - [Enabling serverless security analytics using AWS WAF full logs, Amazon Athena, and Amazon QuickSight](https://aws.amazon.com/blogs/security/enabling-serverless-security-analytics-using-aws-waf-full-logs/)
* Blog - [How to use Amazon GuardDuty and AWS Web Application Firewall to automatically block suspicious hosts](https://aws.amazon.com/blogs/security/how-to-use-amazon-guardduty-and-aws-web-application-firewall-to-automatically-block-suspicious-hosts/)
* Blog - [How to think about Zero Trust architectures on AWS](https://aws.amazon.com/blogs/publicsector/how-to-think-about-zero-trust-architectures-on-aws/)
* Blog - [Deploy a dashboard for AWS WAF with minimal effort](https://aws.amazon.com/blogs/security/deploy-dashboard-for-aws-waf-minimal-effort/)
* Blog - [Migrating your rules from AWS WAF Classic to the new AWS WAF](https://aws.amazon.com/blogs/security/migrating-rules-from-aws-waf-classic-to-new-aws-waf/)
* Blog - [Automatically updating AWS WAF Rule in real time using Amazon EventBridge](https://aws.amazon.com/blogs/security/automatically-updating-aws-waf-rule-in-real-time-using-amazon-eventbridge/)
* Blog - [Defense in depth using AWS Managed Rules for AWS WAF (part 1)](https://aws.amazon.com/blogs/security/defense-in-depth-using-aws-managed-rules-for-aws-waf-part-1/)
* Blog - [Deploying defense in depth using AWS Managed Rules for AWS WAF (part 2)](https://aws.amazon.com/blogs/security/deploying-defense-in-depth-using-aws-managed-rules-for-aws-waf-part-2/)
* Blog - [How to enhance Amazon CloudFront origin security with AWS WAF and AWS Secrets Manager](https://aws.amazon.com/blogs/security/how-to-enhance-amazon-cloudfront-origin-security-with-aws-waf-and-aws-secrets-manager/)
* Blog - [Field Notes: How to Identify and Block Fake Crawler Bots Using AWS WAF](https://aws.amazon.com/ko/blogs/architecture/field-notes-how-to-identify-and-block-fake-crawler-bots-using-aws-waf/)
* Blog - [Field Notes: How OLX Europe Fights Millions of Bots with AWS](https://aws.amazon.com/blogs/architecture/field-notes-how-olx-europe-fights-millions-of-bots-with-aws/)
* Blog - [How to estimate your AWS WAF and AWS Shield Advanced cost?](https://aws.amazon.com/blogs/aws-cost-management/estimate-your-aws-waf-and-aws-shield-advanced-cost/)
* Blog - [Reduce Unwanted Traffic on Your Website with New AWS WAF Bot Control](https://aws.amazon.com/blogs/aws/reduce-unwanted-traffic-on-your-web-site-with-aws-bot-control/)
* Blog - [Customize requests and responses with AWS WAF](https://aws.amazon.com/ko/blogs/security/customize-requests-and-responses-with-aws-waf/)
* Blog - [Automatically update AWS WAF IP sets with AWS IP ranges](https://aws.amazon.com/ko/blogs/security/automatically-update-aws-waf-ip-sets-with-aws-ip-ranges/)
* Blog - [The three most important AWS WAF rate-based rules](https://aws.amazon.com/blogs/security/three-most-important-aws-waf-rate-based-rules/)
* Blog - [How to improve visibility into AWS WAF with anomaly detection](https://aws.amazon.com/blogs/security/how-to-improve-visibility-into-aws-waf-with-anomaly-detection/)
* Blog - [How to customize behavior of AWS Managed Rules for AWS WAF](https://aws.amazon.com/blogs/security/how-to-customize-behavior-of-aws-managed-rules-for-aws-waf/)
* Blog - [Fine-tune and optimize AWS WAF Bot Control mitigation capability](https://aws.amazon.com/blogs/security/fine-tune-and-optimize-aws-waf-bot-control-mitigation-capability/)
* Blog - [Blocking application attacks using AWS WAF at scale](https://aws.amazon.com/blogs/architecture/dream11-blocking-application-attacks-using-aws-waf-at-scale/)
* Blog - [Analyzing AWS WAF Logs in Amazon CloudWatch Logs](https://aws.amazon.com/blogs/mt/analyzing-aws-waf-logs-in-amazon-cloudwatch-logs/)
* Blog - [Easily protect your AWS CDK-defined infrastructure with AWS WAFv2](https://aws.amazon.com/blogs/devops/easily-protect-your-aws-cdk-defined-infrastructure-with-aws-wafv2/)


## [AWS Firewall Manager](https://docs.aws.amazon.com/ko_kr/waf/latest/developerguide/fms-chapter.html)
AWS Firewall Manager는 여러 계정과 리소스의 AWS WAF, AWS Shield Advanced, EC2 Security Group의 관리 및 유지 보수 작업을 간소화합니다. Firewall Manager를 사용하여 멀티 어카운트 환경에서 AWS WAF 방화벽 규칙과 Shield Advanced 보호, 또는 Security Group 규칙을 한번에 동시에 설정합니다. AWS Firewall Manager를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다. 

**Bookmark**

* [AWS Firewall Manager의 보안](https://docs.aws.amazon.com/ko_kr/waf/latest/developerguide/fms-security.html)
* [Getting started with AWS Firewall Manager PaloAlto Cloud NGFW policies](https://docs.aws.amazon.com/waf/latest/developerguide/getting-started-fms-cloud-ngfw.html)
* Solution - [AWS Centralized WAF and VPC Security Group Management](https://docs.aws.amazon.com/ko_kr/solutions/latest/aws-centralized-waf-and-vpc-security-group-management/welcome.html)
* Solution - [AWS Organizations용 AWS Firewall Manager 자동화](https://aws.amazon.com/ko/solutions/implementations/aws-firewall-mgr-automations-for-aws-orgs/)
* Blog - [AWS Firewall Manager: Central Management for Your Web Application Portfolio](https://aws.amazon.com/blogs/aws/aws-firewall-manager-central-management-for-your-web-application-portfolio/)
* Blog - [Use AWS Firewall Manager and VPC security groups to protect your applications hosted on EC2 instances](https://aws.amazon.com/blogs/security/use-aws-firewall-manager-vpc-security-groups-to-protect-applications-hosted-on-ec2-instances/)
* Blog - [Automate AWS Firewall Manager onboarding using AWS Centralized WAF and VPC Security Group Management solution](https://aws.amazon.com/blogs/security/automate-aws-firewall-manager-onboarding-using-aws-centralized-waf-and-vpc-security-group-management-solution/)
* Blog - [Use AWS Firewall Manager to deploy protection at scale in AWS Organizations](https://aws.amazon.com/blogs/security/use-aws-firewall-manager-to-deploy-protection-at-scale-in-aws-organizations/)
* Blog - [AWS Firewall Manager helps automate security group management: 3 scenarios](https://aws.amazon.com/blogs/security/aws-firewall-manager-helps-automate-security-group-management-3-scenarios/)
* Blog - [Set up centralized monitoring for DDoS events and auto-remediate noncompliant resources](https://aws.amazon.com/blogs/security/set-up-centralized-monitoring-for-ddos-events-and-auto-remediate-noncompliant-resources/)
* Blog - [Centrally manage AWS WAF (API v2) and AWS Managed Rules at scale with Firewall Manager](https://aws.amazon.com/blogs/security/centrally-manage-aws-waf-api-v2-and-aws-managed-rules-at-scale-with-firewall-manager/)
* Blog - [Hands-on walkthrough of the AWS Network Firewall flexible rules engine – Part 1](https://aws.amazon.com/blogs/security/hands-on-walkthrough-of-the-aws-network-firewall-flexible-rules-engine/)
* Blog - [Hands-on walkthrough of the AWS Network Firewall flexible rules engine – Part 2](https://aws.amazon.com/blogs/security/hands-on-walkthrough-of-the-aws-network-firewall-flexible-rules-engine-part-2/)
* Blog - [Centrally manage AWS WAF (API v2) and AWS Managed Rules at scale with Firewall Manager](https://aws.amazon.com/blogs/security/centrally-manage-aws-waf-api-v2-and-aws-managed-rules-at-scale-with-firewall-manager/)
* Blog - [New – Cloud NGFW for AWS](https://aws.amazon.com/ko/blogs/aws/new-cloud-ngfw-for-aws/)
* Blog - [How to deploy AWS Network Firewall by using AWS Firewall Manager](https://aws.amazon.com/blogs/security/how-to-deploy-aws-network-firewall-by-using-aws-firewall-manager/)



## [AWS Network Firewall](https://aws.amazon.com/ko/network-firewall/)
AWS Network Firewall은 여러분들의 VPC와 VPC 상의 모든 리소스들에 대한 네트워크 보호기능을 쉽게 구성할 수 있도록 해주는 관리형 서비스입니다. AWS Network Firewall을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Security in AWS Network Firewall](https://docs.aws.amazon.com/ko_kr/network-firewall/latest/developerguide/security.html)
* EXT. - [Suricata Rule - 5.0.0](https://suricata.readthedocs.io/en/suricata-5.0.0/rules/index.html)
* EXT. - [Suricata Rule - Protocol Anomalies Detection](https://redmine.openinfosecfoundation.org/projects/suricata/wiki/Protocol_Anomalies_Detection)
* Ext. - [Trend Micro CloudOne - Share threat intelligence with AWS](https://cloudone.trendmicro.com/docs/network-security/share_threat_intel/)
* Ext. - [FortiGurad Labs. - Managed IPS Rules for AWS Network Firewall](https://www.fortinet.com/products/managed-ips-rules-for-aws)
* Solution - [AWS Network Firewall Deployment Automations for AWS Transit Gateway](https://aws.amazon.com/solutions/implementations/aws-network-firewall-deployment-automations-for-aws-transit-gateway/)
* Solution - [Dynamic Object and Rule Extensions for AWS Network Firewall](https://aws.amazon.com/solutions/implementations/dynamic-object-and-rule-extensions-aws-network-firewall/)
* GIT - [AWS Network Firewall CloudFormation Templates](https://github.com/aws-samples/aws-networkfirewall-cfn-templates)
* GIT - [AWS Network Firewall - Terraform Sample](https://github.com/aws-samples/aws-network-firewall-terraform)
* GIT - [AWS Network Firewall Automation Sample](https://github.com/aws-samples/aws-network-firewall-automation-examples)
* GIT - [aws-networkfirewall-cfn-templates](https://github.com/aws-samples/aws-networkfirewall-cfn-templates/tree/main/centralized_architecture)
* Ext. - [Emerging Threats Botnet Command and Control drop rules for suricata](https://rules.emergingthreats.net/blockrules/emerging-botcc.suricata.rules)
* Blog - [AWS Network Firewall – New Managed Firewall Service in VPC](https://aws.amazon.com/blogs/aws/aws-network-firewall-new-managed-firewall-service-in-vpc/)
* Blog - [Enforce your AWS Network Firewall protections at scale with AWS Firewall Manager](https://aws.amazon.com/blogs/security/enforce-your-aws-network-firewall-protections-at-scale-with-aws-firewall-manager/)
* Blog - [Automatically block suspicious traffic with AWS Network Firewall and Amazon GuardDuty](https://aws.amazon.com/blogs/security/automatically-block-suspicious-traffic-with-aws-network-firewall-and-amazon-guardduty/)
* Blog - [Use Contributor Insights to analyze AWS Network Firewall](https://aws.amazon.com/blogs/mt/use-contributor-insights-to-analyze-aws-network-firewall/)
* Blog - [Hands-on walkthrough of the AWS Network Firewall flexible rules engine](https://aws.amazon.com/ko/blogs/security/hands-on-walkthrough-of-the-aws-network-firewall-flexible-rules-engine/)
* Blog - [Deploy centralized traffic filtering using AWS Network Firewall](https://aws.amazon.com/blogs/networking-and-content-delivery/deploy-centralized-traffic-filtering-using-aws-network-firewall/)
* Blog - [Scaling threat prevention on AWS with Suricata](https://aws.amazon.com/blogs/opensource/scaling-threat-prevention-on-aws-with-suricata/)
* Blog - [Securely scale multi-account architecture with AWS Network Firewall and AWS Control Tower](https://aws.amazon.com/blogs/mt/scale-multi-account-architecture-aws-network-firewall-and-aws-control-tower/)
* Blog - [Migrating from Squid Web Proxy to AWS Network Firewall](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/migrating-from-squid-web-proxy-to-aws-network-firewall/)
* Blog - [Deployment models for AWS Network Firewall](https://aws.amazon.com/blogs/networking-and-content-delivery/deployment-models-for-aws-network-firewall/)
* Blog - [Deployment models for AWS Network Firewall with VPC routing enhancements](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/deployment-models-for-aws-network-firewall-with-vpc-routing-enhancements/)
* Blog - [Integrate AWS Network Firewall with your ISV Firewall Rulesets](https://aws.amazon.com/blogs/architecture/integrate-aws-network-firewall-with-your-isv-firewall-rulesets/)
* Blog - [Design your firewall deployment for Internet ingress traffic flows](https://aws.amazon.com/blogs/networking-and-content-delivery/design-your-firewall-deployment-for-internet-ingress-traffic-flows/)
* Blog - [Securing SAP with AWS Network Firewall: Part 1 – Architecture design patterns](https://aws.amazon.com/blogs/awsforsap/securing-sap-with-aws-network-firewall-part-1-architecture-design-patterns/)
* Blog - [인터넷을 통해 유입되는 트래픽을 보호하기 위한 AWS 기반 방화벽 배포방식 설계](https://aws.amazon.com/ko/blogs/korea/design-your-firewall-deployment-for-internet-ingress-traffic-flows/)


## [Route 53 Resolver DNS 방화벽](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall.html)

**Bookmark**

* [Route 53 Resolver DNS 방화벽의 작동 방식](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-overview.html)
* Blog - [How to Get Started with Amazon Route 53 Resolver DNS Firewall for Amazon VPC](https://aws.amazon.com/blogs/aws/how-to-get-started-with-amazon-route-53-resolver-dns-firewall-for-amazon-vpc/)
* Blog - [Secure your Amazon VPC DNS resolution with Amazon Route 53 Resolver DNS Firewall](https://aws.amazon.com/blogs/networking-and-content-delivery/secure-your-amazon-vpc-dns-resolution-with-amazon-route-53-resolver-dns-firewall/)
* Blog - [Using Route 53 Resolver DNS Firewall Logs with CloudWatch Contributor Insights and Anomaly Detection](https://aws.amazon.com/blogs/networking-and-content-delivery/using-route-53-resolver-dns-firewall-logs-with-cloudwatch-contributor-insights-and-anomaly-detection/)
 
 
## 인프라 보안과 관련된 기타 유용한 링크들

* [AWS 환경에 대한 침투테스트 승인 요청](https://aws.amazon.com/ko/security/penetration-testing/)
* [권장 스캐너 AMI 목록](https://aws.amazon.com/marketplace/search/results?searchTerms=pre-authorized+scanning&page=1&ref_=nav_search_box)
* 동영상 [AWS Summit Seoul 2018] - [다양한 솔루션으로 만들어가는 AWS 네트워크 보안](https://youtu.be/D9BiEQn7Avw)
* 동영상 [AWS Builders Online] - [AWS 네트워크 보안을 위한 계층별 보안 구성 모범 사례](https://www.youtube.com/watch?v=r84IuPv_4TI)
* GIT - [cloud-nuke](https://github.com/gruntwork-io/cloud-nuke#cloud-nuke) _- AWS 리소스들에 대한 일괄 삭제처리 기능 제공 CLI_
* Solution - [AWS Perspective](https://aws.amazon.com/solutions/implementations/aws-perspective/?did=sl_card)
* Blog - [Zero Trust architectures: An AWS perspective](https://aws.amazon.com/blogs/security/zero-trust-architectures-an-aws-perspective/)
* Blog - [Confidential computing: an AWS perspective](https://aws.amazon.com/ko/blogs/security/confidential-computing-an-aws-perspective/)
* Blog - [Creating a Multi-Region Application with AWS Services – Part 1, Compute and Security](https://aws.amazon.com/blogs/architecture/creating-a-multi-region-application-with-aws-services-part-1-compute-and-security/)
* Blog - [Reduce security risks from IaC drift in multi-Region AWS deployments with Terraform](https://aws.amazon.com/blogs/infrastructure-and-automation/reduce-security-risks-from-iac-drift-in-multi-region-aws-deployments-with-terraform/)

 

## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.



---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>