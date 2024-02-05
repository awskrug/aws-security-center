# 거버넌스 및 탐지통제(Detective Control)

비지니스에 영향을 미치기 전에 고객 환경의 보안 이슈들을 식별하고, 전반적인 보안 수준을 향상시키고, 보안 위험도를 감소시키기 위한 기능과 관련된 영역입니다. 이 영역에 해당하는 AWS 보안 서비스들에는 다음과 같은 것들이 있습니다.
 
## [AWS CloudTrail](https://aws.amazon.com/ko/cloudtrail/)

AWS 어카운트의 거버넌스, 컴플라이언스, 운영 및 리스크 감사 기능을 제공합니다. AWS CloudTrail을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS CloudTrail의 보안](https://docs.aws.amazon.com/ko_kr/awscloudtrail/latest/userguide/WhatIsCloudTrail-Security.html)
* 가이드 - [Automatically re-enable AWS CloudTrail by using a custom remediation rule in AWS Config](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automatically-re-enable-aws-cloudtrail-by-using-a-custom-remediation-rule-in-aws-config.html)
* AWS Solutions - [Centralized Logging](https://aws.amazon.com/ko/solutions/centralized-logging/)
* GIT - [AWS CloudTrail Processing Library](https://github.com/aws/aws-cloudtrail-processing-library)
* GIT - [EnableAWSCloudTrail](https://github.com/cloud-automaton/automaton/blob/master/aws/events/EnableAWSCloudTrail.py)
* Blog - [Maximizing features and functionality in AWS CloudTrail](https://aws.amazon.com/ko/blogs/mt/maximizing-features-and-functionality-in-aws-cloudtrail/)
* Blog - [Visualize AWS Cloudtrail Logs Using AWS Glue and Amazon QuickSight](https://aws.amazon.com/blogs/big-data/streamline-aws-cloudtrail-log-visualization-using-aws-glue-and-amazon-quicksight/)
* Blog - [Visualizing AWS CloudTrail Events using Kibana](https://aws.amazon.com/ko/blogs/mt/visualizing-aws-cloudtrail-events-using-kibana/)
* Blog - [How to optimize AWS CloudTrail costs by using advanced event selectors](https://aws.amazon.com/blogs/mt/optimize-aws-cloudtrail-costs-using-advanced-event-selectors/)
* Blog - [Analyze Security, Compliance, and Operational Activity Using AWS CloudTrail and Amazon Athena](https://aws.amazon.com/blogs/big-data/aws-cloudtrail-and-amazon-athena-dive-deep-to-analyze-security-compliance-and-operational-activity/)
* Blog - [Restrict Access by member account to a centralized CloudTrail logging bucket](https://aws.amazon.com/blogs/mt/restrict-access-by-member-account-to-a-centralized-cloudtrail-logging-bucket/)
* Blog - [Using CloudTrail to identify unexpected behaviors in individual workloads](https://aws.amazon.com/blogs/security/using-cloudtrail-to-identify-unexpected-behaviors-in-individual-workloads/)
* Blog - [Announcing AWS CloudTrail Lake – a managed audit and security Lake](https://aws.amazon.com/ko/blogs/mt/announcing-aws-cloudtrail-lake-a-managed-audit-and-security-lake/)

 

## [AWS Config](https://aws.amazon.com/ko/config/)

AWS 리소스의 구성을 기록하고 점검하는 기능을 제공합니다. 컴플라이언스 감사, 보안 분석, 리소스 변경 이력 추적 및 조사 기능을 제공합니다. AWS Config를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Config의 보안](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/security.html)
* 동영상 [AWS Summit Seoul 2016] - [AWS 고급 보안 서비스를 통한 민첩한 보안 운영 전략](https://www.youtube.com/watch?v=lRGJZThgk-Q)
* 동영상 - [Remediate Non-Compliance Using AWS Config Rules and Custom SSM Document](https://www.youtube.com/watch?v=CyyNlyAHs0A&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=15)
* 동영상 - [Enforce Compliance with AWS Config](https://www.youtube.com/watch?v=X_fznJtSyV8&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=2)
* 동영상 - [Remediate Non-Compliance Using AWS Config Rules, AWS CloudWatch Events, & AWS Lambda Functions](https://www.youtube.com/watch?v=PD9S5xGC16g&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=10)
* GIT - [Config Rules Repository](https://github.com/awslabs/aws-config-rules) _- Sample Config Rules 저장소_
* GIT - [Config Rule Development Kit](https://github.com/awslabs/aws-config-rdk)
* GIT - [Engine for Compliance-as-code](https://github.com/awslabs/aws-config-engine-for-compliance-as-code)
* GIT - [Making Things Right With AWS Lambda and AWS Config Rules](https://github.com/aws-samples/aws-serverless-config-rules-workshop)
* GIT - [AWS Config Resource Schema](https://github.com/awslabs/aws-config-resource-schema)
* GIT - [RDKlib](https://github.com/awslabs/aws-config-rdklib) _- 람다 Layer에서 동작하는 Config Rule 배포 관리용 파이선_
* GIT - [aws-config-resource-schema](https://github.com/awslabs/aws-config-resource-schema)
* GIT - [RDKlib Add-On to RDK Workshop](https://github.com/awslabs/aws-config-rdklib/tree/master/rdklib_addon_to_rdk_workshop)
* GIT - [Config-Visualization at master](https://github.com/aws-samples/aws-management-and-governance-samples/tree/master/AWSConfig/AWS-Config-Visualization)
* Support - [How can I understand AWS Config billing by retrieving the number of configuration items recorded per month?](https://aws.amazon.com/premiumsupport/knowledge-center/retrieve-aws-config-items-per-month/)
* Support - [AWS Config를 사용하여 규정 미준수 AWS 리소스에 대한 알림 수신](https://aws.amazon.com/ko/premiumsupport/knowledge-center/config-resource-non-compliant/)
* Support - [AWS Config 조직 규칙에 대한 수정 작업 추가](https://aws.amazon.com/ko/premiumsupport/knowledge-center/add-config-remediation-actions/)
* Blog - [How to develop custom AWS Config rules using the Rule Development Kit](https://aws.amazon.com/blogs/mt/how-to-develop-custom-aws-config-rules-using-the-rule-development-kit/)
* Blog - [Amazon S3 bucket compliance using AWS Config Auto Remediation feature](https://aws.amazon.com/blogs/mt/aws-config-auto-remediation-s3-compliance/)
* Blog - [How to Automate Cloud Governance to Achieve Safety at Speed](https://aws.amazon.com/blogs/apn/how-to-automate-cloud-governance-to-achieve-safety-at-speed/)
* Blog - [Auto-populate instance details by integrating AWS Config with your ServiceNow CMDB](https://aws.amazon.com/blogs/mt/auto-populate-instance-details-by-integrating-aws-config-with-your-servicenow-cmdb/)
* Blog - [AWS Config RDK: Multi-account and multi-Region deployment](https://aws.amazon.com/blogs/mt/aws-config-rdk-multi-account-and-multi-region-deployment/)
* Blog - [AWS Config best practices](https://aws.amazon.com/blogs/mt/aws-config-best-practices/)
* Blog - [Ingest AWS Config data into Splunk with ease](https://aws.amazon.com/blogs/mt/ingest-aws-config-data-into-splunk-with-ease/)
* Blog - [How to query your AWS resource configuration states using AWS Config and Amazon Athena](https://aws.amazon.com/blogs/mt/how-to-query-your-aws-resource-configuration-states-using-aws-config-and-amazon-athena/)
* Blog - [How to Use AWS Config to Monitor for and Respond to Amazon S3 Buckets Allowing Public Access](https://aws.amazon.com/blogs/security/how-to-use-aws-config-to-monitor-for-and-respond-to-amazon-s3-buckets-allowing-public-access/)
* Blog - [Preventing blacklisted applications with AWS Systems Manager and AWS Config](https://aws.amazon.com/blogs/mt/preventing-blacklisted-applications-with-aws-systems-manager-and-aws-config/)
* Blog - [How to develop custom AWS Config rules using the Rule Development Kit](https://aws.amazon.com/blogs/mt/how-to-develop-custom-aws-config-rules-using-the-rule-development-kit/)
* Blog - [Introducing AWS Config Conformance Packs](https://aws-blogs-prod.amazon.com/mt/introducing-aws-config-conformance-packs/)
* Blog - [Integrating Third-Party Solutions to AWS Config Rule Evaluations](https://aws.amazon.com/blogs/apn/integrating-third-party-solutions-to-aws-config-rule-evaluations/)
* Blog - [Managing AWS Organizations accounts using AWS Config and AWS CloudFormation StackSets](https://aws.amazon.com/blogs/mt/managing-aws-organizations-accounts-using-aws-config-and-aws-cloudformation-stacksets/)
* Blog - [Deploy AWS Config Rules and Conformance Packs using a delegated admin](https://aws.amazon.com/blogs/mt/deploy-aws-config-rules-and-conformance-packs-using-a-delegated-admin/)
* Blog - [Managing aged access keys through AWS Config remediations](https://aws-blogs-prod.amazon.com/mt/managing-aged-access-keys-through-aws-config-remediations/)
* Blog - [How to use AWS Config to determine compliance of AWS KMS key policies to your specifications](https://aws.amazon.com/blogs/security/how-to-use-aws-config-to-determine-compliance-of-aws-kms-key-policies-to-your-specifications/)
* Blog - [Identifying resources with the most configuration changes using AWS Config](https://aws.amazon.com/blogs/mt/identifying-resources-most-configuration-changes-aws-config/)
* Blog - [AWS Config Rule Development Kit library: Build and operate rules at scale](https://aws.amazon.com/ko/blogs/mt/aws-config-rule-development-kit-library-build-and-operate-rules-at-scale/)
* Blog - [Using AWS Systems Manager OpsCenter and AWS Config for compliance monitoring](https://aws.amazon.com/ko/blogs/mt/using-aws-systems-manager-opscenter-and-aws-config-for-compliance-monitoring/)
* Blog - [AWS Organizations, AWS Config, and Terraform](https://aws.amazon.com/ko/blogs/mt/aws-organizations-aws-config-and-terraform/)
* Blog - [Using AWS Config for security analysis and resource administration](https://aws.amazon.com/ko/blogs/mt/using-aws-config-security-analysis-resource-administration/)
* Blog - [Building a Self-Service, Secure, & Continually Compliant Environment on AWS](https://aws.amazon.com/ko/blogs/architecture/building-a-self-service-secure-continually-compliant-environment-on-aws/)
* Blog - [Best practices for AWS Config conformance packs](https://aws.amazon.com/blogs/mt/best-practices-for-aws-config-conformance-packs/)
* Blog - [Understanding the differences between configuration history and configuration snapshot files in AWS Config](https://aws.amazon.com/blogs/mt/configuration-history-configuration-snapshot-files-aws-config/)
* Blog - [AWS Control Tower Detective Guardrails as an AWS Config Conformance Pack](https://aws.amazon.com/blogs/mt/aws-control-tower-detective-guardrails-as-an-aws-config-conformance-pack/)
* Blog - [How to auto-remediate internet accessible ports with AWS Config and AWS System Manager](https://aws.amazon.com/blogs/security/how-to-auto-remediate-internet-accessible-ports-with-aws-config-and-aws-system-manager/)
* Blog - [Using AWS Config custom resources to track any resource on AWS](https://aws.amazon.com/blogs/mt/using-aws-config-custom-resources-to-track-any-resource-on-aws/)
* Blog - [Set up an organization-wide aggregator in AWS Config using a delegated administrator account](https://aws.amazon.com/blogs/mt/org-aggregator-delegated-admin/)
* Blog - [Visualizing AWS Config data using Amazon Athena and Amazon QuickSight](https://aws.amazon.com/blogs/mt/visualizing-aws-config-data-using-amazon-athena-and-amazon-quicksight/)
* Blog - [Integrate across the Three Lines Model (Part 2): Transform AWS Config conformance packs into AWS Audit Manager assessments](https://aws.amazon.com/blogs/mt/integrate-across-the-three-lines-model-part-2-transform-aws-config-conformance-packs-into-aws-audit-manager-assessments/)
* Blog - [How to query your AWS resource configuration states using AWS Config and Amazon Athena](https://aws.amazon.com/blogs/mt/how-to-query-your-aws-resource-configuration-states-using-aws-config-and-amazon-athena/)
* Blog - [Deploy Conformance Packs across an Organization with Automatic Remediation](https://aws.amazon.com/blogs/mt/deploying-conformance-packs-across-an-organization-with-automatic-remediation/)
* Blog - [Manage custom AWS Config rules with remediations using conformance packs](https://aws.amazon.com/blogs/mt/manage-custom-aws-config-rules-with-remediations-using-conformance-packs/?nc1=b_rp)
* Blog - [Using OPA to create AWS Config rules](https://aws.amazon.com/ko/blogs/mt/using-opa-to-create-aws-config-rules/)
* Blog - [Implement AWS Config rule remediation with Systems Manager Change Manager](https://aws.amazon.com/ko/blogs/mt/implement-aws-config-rule-remediation-with-systems-manager-change-manager/)
* Blog - [Implementing a cross-account and cross-Region AWS Config status dashboard](https://aws.amazon.com/blogs/mt/implementing-a-cross-account-and-cross-region-aws-config-status-dashboard/)
* Blog - [Build an AWS Config Custom Rule to Optimize Amazon EBS Volume Types](https://aws.amazon.com/ko/blogs/mt/build-an-aws-config-custom-rule-to-optimize-amazon-ebs-volume-types/)
* Blog - [Identifying resources with the most configuration changes using AWS Config](https://aws.amazon.com/ko/blogs/mt/identifying-resources-most-configuration-changes-aws-config/)
* Blog - [How to Deploy AWS Config Conformance Packs Using Terraform](https://aws.amazon.com/ko/blogs/mt/how-to-deploy-aws-config-conformance-packs-using-terraform/)
* Blog - [Find Public IPs of Resources – Use AWS Config for Vulnerability Assessment](https://aws.amazon.com/blogs/architecture/find-public-ips-of-resources-use-aws-config-for-vulnerability-assessment/)
* Blog - [Automate AWS Config data visualization with AWS Systems Manager](https://aws.amazon.com/ko/blogs/mt/automate-aws-config-data-visualization-with-aws-systems-manager/)
* Blog - [Internet Facing Load Balancer 생성 탐지 및 제거](https://aws.amazon.com/ko/blogs/tech/internet-facing-load-balancer-%EC%83%9D%EC%84%B1-%ED%83%90%EC%A7%80-%EB%B0%8F-%EC%A0%9C%EA%B1%B0/)

 

## [Amazon CloudWatch](https://aws.amazon.com/ko/cloudwatch/)

AWS 리소스와 AWS상의 고객 애플리케이션들을 모니터링하기 위해 메트릭 수집, 로그 파일 모니터링, 경보 설정, 변경에 대한 자동화된 대응 등의 기능을 제공합니다. Amazon CloudWatch를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Amazon CloudWatch의 보안](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/monitoring/security.html)
* [Amazon CloudWatch Events의 보안](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/events/auth-and-access-control-cwe.html)
* [Amazon CloudWatch Logs의 보안](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/logs/security.html)
* 동영상 - [Monitor Resource Changes with Amazon CloudWatch Events](https://www.youtube.com/watch?v=-rQku_AeN_Y&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=4)
* 동영상 - [Collect Metrics and Logs from Amazon EC2 Instances with CloudWatch Agent](https://www.youtube.com/watch?v=vAnIhIwE5hY&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=1)
* 동영상 - [Monitor Performance of Amazon ECS Applications Using CloudWatch Container Insights](https://www.youtube.com/watch?v=LwM_oETkLAc&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=25)
* 동영상 - [Analyze Log Data with CloudWatch Log Insights](https://www.youtube.com/watch?v=2s2xcwm8QrM&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=7)
* GIT - [Amazon CloudWatch Log Centralizer](https://github.com/aws-samples/amazon-cloudwatch-log-centralizer)
* GIT - [cwe-monitor-secgrp](https://github.com/awslabs/cwe-monitor-secgrp)
* GIT - [Export-CloudWatch-Metrics](https://github.com/bjtox/CloudWatch-Metrics-to-s3)
* GIT - [Generic AWS CloudWatch to Spreadsheet Exporter](https://github.com/petezybrick/awscwxls)
* GIT - [One-Click Setup: CloudWatch Logs + Elasticsearch + Kibana](https://github.com/amazon-archives/cloudwatch-logs-subscription-consumer)
* GIT - [Fluent Bit Plugin for CloudWatch Logs](https://github.com/aws/amazon-cloudwatch-logs-for-fluent-bit)
* GIT - [Athena Cloudwatch Connector](https://aws.amazon.com/ko/blogs/security/how-to-automate-forensic-disk-collection-in-aws/)
* Partner - [Using AWS CloudWatch in Grafana](https://grafana.com/docs/features/datasources/cloudwatch/)
* Blog - [AWS 멀티 어카운트 환경을 위한 통합 로깅 방법](https://aws-preview.aka.amazon.com/ko/blogs/korea/central-logging-in-multi-account-environments/) _– 멀티 어카운트 상에서 CloudWatch Logs에서 발생하는 로그 스트림들을 로깅 어카운트의 지정된 S3버킷으로 취합하고 Athena로 질의하는 환경을 구성하는 블로그_
* Blog - [Logging Windows Amazon EC2 UserData activity in Amazon CloudWatch](https://aws.amazon.com/blogs/infrastructure-and-automation/logging-windows-amazon-ec2-userdata-activity-in-amazon-cloudwatch/)
* Blog - [Create a metric math alarm using Amazon CloudWatch](https://aws.amazon.com/blogs/mt/create-a-metric-math-alarm-using-amazon-cloudwatch/) _- 산술식 기반 메트릭 알람 설정 방법 설명_
* Blog - [Simplifying Apache server logs with Amazon CloudWatch Logs Insights](https://aws.amazon.com/blogs/mt/simplifying-apache-server-logs-with-amazon-cloudwatch-logs-insights/)
* Blog - [Understanding AWS Lambda behavior using Amazon CloudWatch Logs Insights](https://aws.amazon.com/blogs/mt/understanding-aws-lambda-behavior-using-amazon-cloudwatch-logs-insights/)
* Blog - [Stream Amazon CloudWatch Logs to a Centralized Account for Audit and Analysis](https://aws.amazon.com/blogs/architecture/stream-amazon-cloudwatch-logs-to-a-centralized-account-for-audit-and-analysis/)
* Blog - [Streaming AWS Systems Manager Run Command output to Amazon CloudWatch Logs](https://aws.amazon.com/blogs/mt/streaming-aws-systems-manager-run-command-output-to-amazon-cloudwatch-logs/)
* Blog - [Monitor your private internal endpoints 24×7 using CloudWatch Synthetics](https://aws.amazon.com/ko/blogs/mt/monitor-your-private-endpoints-using-cloudwatch-synthetics/)
* Blog - [Gain visibility into your Kubernetes spend with CloudZero and Amazon CloudWatch Container Insights]()
* Blog - [Sending CloudFront standard logs to CloudWatch Logs for analysis](https://aws.amazon.com/blogs/mt/sending-cloudfront-standard-logs-to-cloudwatch-logs-for-analysis/)
* Blog - [How to validate authentication using Amazon CloudWatch Synthetics – Part 2](https://aws.amazon.com/blogs/mt/how-to-validate-authentication-using-amazon-cloudwatch-synthetics-part-2/)
* Blog - [Share your Amazon CloudWatch Dashboards with anyone using AWS Single Sign-On](https://aws.amazon.com/blogs/mt/share-your-amazon-cloudwatch-dashboards-with-anyone-using-aws-single-sign-on/)
* Blog - [How to isolate signed-in users from guest users within Amazon CloudWatch RUM](https://aws.amazon.com/blogs/mt/how-to-isolate-signed-in-users-from-guest-users-within-amazon-cloudwatch-rum/)


## [Amazon GuardDuty](https://aws.amazon.com/ko/guardduty/)

AWS 어카운트와 워크로드를 보호하기 위한 지능화된 위협 탐지 및 상시 모니터링 기능을 제공합니다. Amazon GuardDuty를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Amazon GuardDuty 보안](https://docs.aws.amazon.com/ko_kr/guardduty/latest/ug/security.html)
* Support - [How can I configure a CloudWatch events rule for GuardDuty to send custom SNS notifications if specific AWS service event types trigger?](https://aws.amazon.com/premiumsupport/knowledge-center/guardduty-cloudwatch-sns-rule/)
* GIT - [amazon-guardduty-multiaccount-scripts](https://github.com/aws-samples/amazon-guardduty-multiaccount-scripts) _– CloudFormation Stackset 기능을 이용하여 멀티어카운트 및 멀티 리전 별로 GuardDuty 설정을 쉽게 해 주는 템플릿_
* GIT - [Amazon GuardDuty Tester](https://github.com/awslabs/amazon-guardduty-tester) _– 포트스캐닝, SSH Brute Force, RDP Brute Force, CrytoCurrency Mining Activity, DNS Exfiltration 등 5개의 테스팅을 수행하는 템플릿_
* GIT - [GDPatrol](https://github.com/ansorren/GDPatrol) _- GuardDuty 탐지건에 대해 심각도 기반 자동 대응_
* GIT - [amazon-guardduty-to-slack](https://github.com/aws-samples/amazon-guardduty-to-slack)
* GIT - [AWS GD2ACL](https://github.com/aws-samples/amazon-guardduty-waf-acl)
* GIT - [Amazon GuardDuty Threat Feed](https://github.com/aws-samples/amazon-guardduty-threat-feed)
* GIT - [Mitre ATT&CK® Mappings for Amazon GuardDuty](https://github.com/amrandazz/attack-guardduty-navigator)
* 동영상 [AWS Cloud 2018] - [인공지능 보안 위협 감지 서비스 Amazon GuardDuty를 포함한 AWS 보안 신규 기능 업데이트](https://www.youtube.com/watch?v=ZyOAHiia93Q)
* 외부 백서 - [FOREGENIX - Amazon GuardDuty Security Review](https://d1.awsstatic.com/certifications/foregenix_amazon_guardduty_security_review_07-2020.pdf)
* Blog - [Monitoring your security with GuardDuty in real time with Amazon Elasticsearch Service](https://aws.amazon.com/blogs/database/monitoring-your-security-with-guardduty-in-real-time-with-amazon-elasticsearch-service/)
* Blog - [How to Use Amazon Alexa to Get Amazon GuardDuty Statistics and Findings](https://aws.amazon.com/ko/blogs/security/how-to-use-amazon-alexa-to-get-amazon-guardduty-statistics-and-findings/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+AWSSecurity+%28AWS+Security+Blog%29) _– Alexa를 이용하여 GuardDuty의 통계 및 탐지 내역을 조회하는 블로그_
* Blog - [How to automate the import of third-party threat intelligence feeds into Amazon GuardDuty](https://aws.amazon.com/blogs/security/how-to-automate-import-third-party-threat-intelligence-feeds-into-amazon-guardduty/) _- 파트너 제공 위협IP 목록을 주기적으로 업데이트하는 방법에 대해 안내(샘플 : FireEye iSIGHT Threat Intelligence)_ 
* Blog - [How to use Amazon GuardDuty and AWS Web Application Firewall to automatically block suspicious hosts](https://aws.amazon.com/blogs/security/how-to-use-amazon-guardduty-and-aws-web-application-firewall-to-automatically-block-suspicious-hosts/) _- GuardDuty에서 탐지된 악성 IP들을 WAF 차단 규칙에 자동으로 반영하는 방법을 안내_
* Blog - [How to visualize Amazon GuardDuty findings: serverless edition](https://aws.amazon.com/blogs/security/how-to-visualize-amazon-guardduty-findings-serverless-edition/)
* Blog - [Visualizing Amazon GuardDuty findings](https://aws.amazon.com/blogs/security/visualizing-amazon-guardduty-findings/) _- GuardDuty의 탐지내역을 Kibana 기반 대시보드에 가시화해 주는 CloudFormation 템플릿을 소개하는 블로그_
* Blog - [New third-party test compares Amazon GuardDuty to network intrusion detection systems](https://aws.amazon.com/blogs/security/new-third-party-test-compares-amazon-guardduty-to-network-intrusion-detection-systems/)
* Blog - [How Security Operation Centers can use Amazon GuardDuty to detect malicious behavior](https://aws.amazon.com/blogs/security/how-security-operation-centers-can-use-amazon-guardduty-to-detect-malicious-behavior/)
* Blog - [Using Amazon GuardDuty to Protect Your S3 Buckets](https://aws.amazon.com/blogs/aws/new-using-amazon-guardduty-to-protect-your-s3-buckets/)
* Blog - [How you can use Amazon GuardDuty to detect suspicious activity within your AWS account](https://aws.amazon.com/blogs/security/how-you-can-use-amazon-guardduty-to-detect-suspicious-activity-within-your-aws-account/)
* Blog - [Automatically block suspicious traffic with AWS Network Firewall and Amazon GuardDuty](https://aws.amazon.com/blogs/security/automatically-block-suspicious-traffic-with-aws-network-firewall-and-amazon-guardduty/)
* Blog - [Automatically block suspicious DNS activity with Amazon GuardDuty and Route 53 Resolver DNS Firewall](https://aws.amazon.com/blogs/security/automatically-block-suspicious-dns-activity-with-amazon-guardduty-and-route-53-resolver-dns-firewall/)
* Blog - [New for Amazon GuardDuty – Malware Detection for Amazon EBS Volumes](https://aws.amazon.com/blogs/aws/new-for-amazon-guardduty-malware-detection-for-amazon-ebs-volumes/)

## [Amazon Inspector](https://aws.amazon.com/ko/inspector/)

AWS상에서 운영되는 애플리케이션 환경에 대해 보안과 규정 준수 수준을 향상시키기 위한 자동화된 보안 수준 점검 기능을 제공합니다. Amazon Inspector를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Security in Amazon Inspector](https://docs.aws.amazon.com/ko_kr/inspector/latest/user/security.html)
* [Amazon Inspector 클래식의 보안](https://docs.aws.amazon.com/ko_kr/inspector/latest/userguide/security.html)
* GIT - [AmazonInspectorAutoRemediation](https://github.com/awslabs/amazon-inspector-auto-remediate)
* 가이드 - [Automate security scans for cross-account workloads using Amazon Inspector and AWS Security Hub](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automate-security-scans-for-cross-account-workloads-using-amazon-inspector-and-aws-security-hub.html)
* Blog - [How to remediate Amazon Inspector Security Findings Automatically](https://aws.amazon.com/ko/blogs/security/how-to-remediate-amazon-inspector-security-findings-automatically/) _– Inspector의 발견내역에 따라 SNS 및 Lambda를 이용하여 자동 대응(예: yum update)하는 예제_
* Blog - [How to Simplify Security Assessment Setup Using Amazon EC2 Systems Manager and Amazon Inspector](https://aws.amazon.com/ko/blogs/security/how-to-simplify-security-assessment-setup-using-ec2-systems-manager-and-amazon-inspector/) _– AWS System Manager를 통해 Inspector를 설치/점검설정을 쉽게 하는 방법_
* Blog - [How to Patch, Inspect, and Protect Microsoft Windows Workloads on AWS—Part 1](https://aws.amazon.com/ko/blogs/security/how-to-patch-inspect-and-protect-microsoft-windows-workloads-on-aws-part-1/)
* Blog - [How to Patch, Inspect, and Protect Microsoft Windows Workloads on AWS—Part 2](https://aws.amazon.com/blogs/security/how-to-patch-inspect-and-protect-microsoft-windows-workloads-on-aws-part-2/)
* Blog - [How to Set Up Continuous Golden AMI Vulnerability Assessments with Amazon Inspector](https://aws.amazon.com/blogs/security/how-to-set-up-continuous-golden-ami-vulnerability-assessments-with-amazon-inspector/)
* Blog - [Amazon Inspector Update – Assessment Reporting, Proxy Support, and More](https://aws.amazon.com/blogs/aws/amazon-inspector-update-assessment-reporting-proxy-support-and-more/)
* Blog - [A simpler way to assess the network exposure of EC2 instances: AWS releases new network reachability assessments in Amazon Inspector](https://aws.amazon.com/blogs/security/amazon-inspector-assess-network-exposure-ec2-instances-aws-network-reachability-assessments/)
* Blog - [How to visualize multi-account Amazon Inspector findings with Amazon Elasticsearch Service](https://aws.amazon.com/blogs/security/how-to-visualize-multi-account-amazon-inspector-findings-with-amazon-elasticsearch-service/)
* Blog - [Sending Amazon Inspector’s Common Vulnerabilities and Exposures Findings to the ServiceNow SecOps Module](https://aws.amazon.com/blogs/apn/sending-amazon-inspector-common-vulnerabilities-and-exposures-findings-to-the-servicenow-secops-module/)
* Blog - [Improved, Automated Vulnerability Management for Cloud Workloads with a New Amazon Inspector](https://aws.amazon.com/ko/blogs/aws/improved-automated-vulnerability-management-for-cloud-workloads-with-a-new-amazon-inspector/)
* Blog - [Container scanning updates in Amazon ECR private registries using Amazon Inspector](https://aws.amazon.com/ko/blogs/containers/container-scanning-updates-in-amazon-ecr-private-registries-using-amazon-inspector/)


## [AWS Security Hub](https://aws.amazon.com/ko/security-hub/)

멀티 어카운트 환경에서 주요 보안 경보 및 규정 준수 상태에 대한 광범위하고 통합적인 뷰를 제공합니다. GuardDuty, Inspector, Macie 같은 AWS 보안 서비스뿐만 아니라 다른 파트너 제품과의 연동도 지원하며 각 서비스들이 탐지한 내역들에 대한 요약 및 통합 대쉬보드를 통해 상시 감사체계를 구축할 수 있도록 해줍니다. Security Hub를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Security Hub의 보안](https://docs.aws.amazon.com/ko_kr/securityhub/latest/userguide/security.html)
* GIT - [AWS Security Hub Multiaccount Scripts](https://github.com/awslabs/aws-securityhub-multiaccount-scripts)
* GIT - [aws-securityhub-to-email](https://github.com/aws-samples/aws-securityhub-to-email)
* GIT - [aws-securityhub-to-slack](https://github.com/aws-samples/aws-securityhub-to-slack)
* GIT - [Centralize SecurityHub](https://github.com/aws-samples/aws-control-tower-securityhub-enabler) _- 전체 Control Tower 어카운트들에 Security Hub 활성화_
* GIT - [About the AWS Security Hub to Splunk integration](https://github.com/splunk/splunk-for-securityHub)
* GIT - [security-hub-manager-solution](https://gitlab.aws.dev/awwicker/security-hub-manager-solution) _- 멀티 어카운트 설정 관리_
* GIT - [aws-security-hub-automated-response-and-remediation](https://github.com/awslabs/aws-security-hub-automated-response-and-remediation)
* GIT - [splunk/splunk-for-securityHub](https://github.com/splunk/splunk-for-securityHub)
* QuickStart - [AWS Security Hub Automated Response and Remediation](https://aws.amazon.com/ko/solutions/implementations/aws-security-hub-automated-response-and-remediation/)
* 가이드 - [Automate remediation for AWS Security Hub standard findings](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automate-remediation-for-aws-security-hub-standard-findings.html)
* 가이드 - [Automate security scans for cross-account workloads using Amazon Inspector and AWS Security Hub](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automate-security-scans-for-cross-account-workloads-using-amazon-inspector-and-aws-security-hub.html)
* Solution - [AWS Security Hub Automated Response and Remediation](https://aws.amazon.com/solutions/implementations/aws-security-hub-automated-response-and-remediation/?did=sl_card&trk=sl_card)
* Blog - [Announcing Cloud Custodian Integration with AWS Security Hub](https://aws.amazon.com/ko/blogs/opensource/announcing-cloud-custodian-integration-aws-security-hub/) _- 오픈소스인 CloudCustodian의 탐지내역들을 Security Hub와 연동하는 방법에 대한 안내_
* Blog - [How to Enable Custom Actions in AWS Security Hub](https://aws.amazon.com/ko/blogs/apn/how-to-enable-custom-actions-in-aws-security-hub/) _- CW Event의 Custom Action을 이용하여 이메일/Slack 통지 과정을 연계하는 내용을 설명_
* Blog - [Nine AWS Security Hub best practices](https://aws.amazon.com/blogs/security/nine-aws-security-hub-best-practices/)
* Blog - [Enabling Seamless Security and Compliance with Sumo Logic and AWS Security Hub](https://aws.amazon.com/blogs/apn/enabling-seamless-security-and-compliance-with-sumo-logic-and-aws-security-hub/)
* Blog - [How to Integrate AWS Security Hub Custom Actions with PagerDuty](https://aws.amazon.com/blogs/apn/how-to-integrate-aws-security-hub-custom-actions-with-pagerduty/)
* Blog - [Use AWS Fargate and Prowler to send security configuration findings about AWS services to Security Hub](https://aws.amazon.com/blogs/security/use-aws-fargate-prowler-send-security-configuration-findings-about-aws-services-security-hub/)
* Blog - [Automated Response and Remediation with AWS Security Hub](https://aws.amazon.com/ko/blogs/security/automated-response-and-remediation-with-aws-security-hub/) _- CIS Benchmark 기준 탐색건들에 대한 자동 대응 시나리오_
* Blog - [How to deploy the AWS Solution for Security Hub Automated Response and Remediation](https://aws.amazon.com/blogs/security/how-to-deploy-the-aws-solution-for-security-hub-automated-response-and-remediation/)
* Blog - [Monitoring AWS Certificate Manager Private CA with AWS Security Hub](https://aws.amazon.com/blogs/security/monitoring-aws-certificate-manager-private-ca-with-aws-security-hub/)
* Blog - [Integrating AWS CloudFormation security tests with AWS Security Hub and AWS CodeBuild reports](https://aws.amazon.com/blogs/security/integrating-aws-cloudformation-security-tests-with-aws-security-hub-and-aws-codebuild-reports/)
* Blog - [How to build a CI/CD pipeline for container vulnerability scanning with Trivy and AWS Security Hub](https://aws.amazon.com/blogs/security/how-to-build-ci-cd-pipeline-container-vulnerability-scanning-trivy-and-aws-security-hub/)
* Blog - [Aligning IAM policies to user personas for AWS Security Hub](https://aws.amazon.com/blogs/security/aligning-iam-policies-to-user-personas-for-aws-security-hub/)
* Blog - [How to set up a recurring Security Hub summary email](https://aws.amazon.com/blogs/security/how-to-set-up-a-recurring-security-hub-summary-email/)
* Blog - [How to import AWS Config rules evaluations as findings in Security Hub](https://aws.amazon.com/blogs/security/how-to-import-aws-config-rules-evaluations-findings-security-hub/)
* Blog - [Automating AWS Security Hub Alerts with AWS Control Tower lifecycle events](https://aws.amazon.com/blogs/mt/automating-aws-security-hub-alerts-with-aws-control-tower-lifecycle-events/)
* Blog - [Enabling AWS Security Hub integration with AWS Chatbot](https://aws.amazon.com/blogs/security/enabling-aws-security-hub-integration-with-aws-chatbot/)
* Blog - [How to set up a two-way integration between AWS Security Hub and ServiceNow](https://aws.amazon.com/blogs/security/how-to-set-up-two-way-integration-between-aws-security-hub-and-servicenow/)
* Blog - [Integrate across the Three Lines Model (Part 1): Build a custom automation of AWS Audit Manager with AWS Security Hub](https://aws.amazon.com/blogs/mt/integrate-across-the-three-lines-model-part-1-build-a-custom-automation-of-aws-audit-manager-with-aws-security-hub/)
* Blog - [How to create auto-suppression rules in AWS Security Hub](https://aws.amazon.com/ko/blogs/security/how-to-create-auto-suppression-rules-in-aws-security-hub/)
* Blog - [Visualize AWS Security Hub Findings using Analytics and Business Intelligence Tools](https://aws.amazon.com/blogs/architecture/visualize-aws-security-hub-findings-using-analytics-and-business-intelligence-tools/)
* Blog - [How to set up a two-way integration between AWS Security Hub and Jira Service Management](https://aws.amazon.com/ko/blogs/security/how-to-set-up-a-two-way-integration-between-aws-security-hub-and-jira-service-management/)
* Blog - [Correlate security findings with AWS Security Hub and Amazon EventBridge](https://aws.amazon.com/ko/blogs/security/correlate-security-findings-with-aws-security-hub-and-amazon-eventbridge/)
* Blog - [Automating AWS Security Hub Alerts with AWS Control Tower lifecycle events](https://aws.amazon.com/blogs/mt/automating-aws-security-hub-alerts-with-aws-control-tower-lifecycle-events/)
* Blog - [Enable Security Hub PCI DSS standard across your organization and disable specific controls](https://aws.amazon.com/ko/blogs/security/enable-security-hub-pci-dss-standard-across-your-organization-and-disable-specific-controls/)
* Blog - [How to set up a recurring Security Hub summary email](https://aws.amazon.com/ko/blogs/security/how-to-set-up-a-recurring-security-hub-summary-email/)
* Blog - [Automate security orchestration in AWS Security Hub with Trend Micro Cloud One](https://aws.amazon.com/blogs/publicsector/automate-security-orchestration-in-aws-security-hub-with-trend-micro-cloud-one/)
* Blog - [Automated security and compliance remediation at HDI](https://aws.amazon.com/ko/blogs/devops/automated-security-and-compliance-remediation-at-hdi/)
* Blog - [Continuous verification of network compliance using Amazon VPC Network Access Analyzer and AWS Security Hub](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/continuous-verification-of-network-compliance-using-amazon-vpc-network-access-analyzer-and-aws-security-hub/)
* Blog - [Continuous runtime security monitoring with AWS Security Hub and Falco](https://aws.amazon.com/ko/blogs/security/continuous-runtime-security-monitoring-with-aws-security-hub-and-falco/)
* Blog - [Automatically resolve Security Hub findings for resources that no longer exist](https://aws.amazon.com/ko/blogs/security/automatically-resolve-security-hub-findings-for-resources-that-no-longer-exist/)
* Blog - [Disabling Security Hub controls in a multi-account environment](https://aws.amazon.com/ko/blogs/security/disabling-security-hub-controls-in-a-multi-account-environment/)
* Blog - [How to use AWS Security Hub and Amazon OpenSearch Service for SIEM](https://aws.amazon.com/blogs/security/how-to-use-aws-security-hub-and-amazon-opensearch-service-for-siem/)
* Blog - [Best practices for cross-Region aggregation of security findings](https://aws.amazon.com/ko/blogs/security/best-practices-for-cross-region-aggregation-of-security-findings/)
* Blog - [AWS Security Hub을 통한 리전 간 보안이슈 통합 집계 모범 사례](https://aws.amazon.com/ko/blogs/korea/best-practices-for-cross-region-aggregation-of-security-findings/)
* Blog - [AWS Security Hub와 OpenSearch를 활용한 SIEM 구성 및 활용 방안](https://aws.amazon.com/ko/blogs/korea/how-to-use-aws-security-hub-and-amazon-opensearch-service-for-siem/)
* Blog - [Use Security Hub custom actions to remediate S3 resources based on Macie discovery results](https://aws.amazon.com/blogs/security/use-security-hub-custom-actions-to-remediate-s3-resources-based-on-macie-discovery-results/)
* Blog - [Use AWS Chatbot in Slack to remediate security findings from AWS Security Hub](https://aws.amazon.com/blogs/security/use-aws-chatbot-in-slack-to-remediate-security-findings-from-aws-security-hub/)
* Blog - [How to export AWS Security Hub findings to CSV format](https://aws.amazon.com/blogs/security/how-to-export-aws-security-hub-findings-to-csv-format/)
* Blog - [How to set up and track SLAs for resolving Security Hub findings](https://aws.amazon.com/blogs/security/how-to-set-up-and-track-slas-for-resolving-security-hub-findings/)
* Blog - [How to subscribe to the new Security Hub Announcements topic for Amazon SNS](https://aws.amazon.com/blogs/security/how-to-subscribe-to-the-new-security-hub-announcements-topic-for-amazon-sns/)


## [IoT Device Defender](https://aws.amazon.com/ko/iot-device-defender/?nc2=h_m1)

AWS IoT Device Defender는 여러 IoT 디바이스의 플릿을 보호할 수 있는 완전관리형 서비스입니다. AWS IoT Device Defender는 IoT 구성을 지속적으로 감사하여 보안 모범 사례를 벗어나지 않도록 합니다. IoT Device Defender의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS IoT Device Defender](https://docs.aws.amazon.com/ko_kr/iot/latest/developerguide/device-defender.html)
* GIT - [AWS IoT Device Defender Agent SDK (Python)](https://github.com/aws-samples/aws-iot-device-defender-agent-sdk-python)
* GIT - [AWS IoT Device Defender Workshop(re:Invent 2018)](https://github.com/aws-samples/aws-iot-device-defender-workshop)
* Blog - [AWS IoT Device Defender Announces ML Detect GA](https://aws.amazon.com/blogs/iot/ml-detect-for-device-defender/)
* Blog - [Implement security monitoring across OT, IIoT and cloud with AWS Security Hub](https://aws.amazon.com/blogs/iot/implement-security-monitoring-across-ot-iiot-and-cloud-with-aws-security-hub/)


## [VPC Flow Logs](https://docs.aws.amazon.com/ko_kr/AmazonVPC/latest/UserGuide/flow-logs.html)

VPC 상의 네트웍 인터페이스(NIC)별로 인바운드/아웃바운드 IP트래픽의 제어 결과에 대한 정보를 제공하며, Amazon CloudWatch Logs에 저장됩니다. VPC Flow Logs를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [VPC 흐름 로그](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/flow-logs.html)
* GIT - [aws-vpc-flow-log-appender](https://github.com/aws-samples/aws-vpc-flow-log-appender)
* Blog - [Analyzing VPC Flow Logs with Amazon Kinesis Firehose, Amazon Athena, and Amazon QuickSight](https://aws.amazon.com/blogs/big-data/analyzing-vpc-flow-logs-with-amazon-kinesis-firehose-amazon-athena-and-amazon-quicksight/)
* Blog - [Learn From Your VPC Flow Logs With Additional Meta-Data](https://aws.amazon.com/blogs/aws/learn-from-your-vpc-flow-logs-with-additional-meta-data/)
* Blog - [VPC Flow Logs – Log and View Network Traffic Flows](https://aws.amazon.com/ko/blogs/aws/vpc-flow-logs-log-and-view-network-traffic-flows/)
* Blog - [How to Visualize and Refine Your Network’s Security by Adding Security Group IDs to Your VPC Flow Logs](https://aws.amazon.com/ko/blogs/security/how-to-visualize-and-refine-your-networks-security-by-adding-security-group-ids-to-your-vpc-flow-logs/#more-3559)
* Blog - [Power data ingestion into Splunk using Amazon Kinesis Data Firehose](https://aws.amazon.com/blogs/big-data/power-data-ingestion-into-splunk-using-amazon-kinesis-data-firehose/) _- Splunk HEC과 Kinesis Firehose간 연계방안 설명을 VPC Flow Logs를 대상으로 안내_
* Blog - [Analyzing Amazon VPC Flow Log data with support for Amazon S3 as a destination](https://aws.amazon.com/blogs/mt/analyzing-vpc-flow-logs-got-easier-with-support-for-s3-as-a-destination/)
* Blog - [Using AWS Cost and Usage Reports and Cost Allocation Tags to understand VPC Flow Logs data ingestion costs in Amazon S3](https://aws.amazon.com/blogs/mt/using-aws-cost-usage-reports-cost-allocation-tags-to-understand-vpc-flow-logs-data-ingestion-costs-in-amazon-s3/)


## [Trusted Advisor - Security](https://aws.amazon.com/ko/premiumsupport/trustedadvisor/)

AWS의 모범사례 기준으로 보안 개선에 도움을 주는 무료 도구입니다.Trusted Advisor는 비용, 성능, 내결함성, 서비스 한도와 함께 보안 항목에 대한 점검을 수행하고 결과를 확인할 수 있습니다. Truseted Advisor 보안 점검 기능을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Trusted Advisor](https://docs.aws.amazon.com/ko_kr/awssupport/latest/user/trusted-advisor.html)
* [AWS Support의 보안](https://docs.aws.amazon.com/ko_kr/awssupport/latest/user/security.html)
* QuickStart - [AWS Limit Monitor](https://aws.amazon.com/ko/solutions/implementations/limit-monitor/)
* GIT - [Consigliere](https://github.com/newscorpaus/consigliere) _– 멀티 어카운트 환경 용 Trusted Advisor 대쉬보드_
* GIT - [Trusted Overload](https://github.com/beeva/trusted-overlord) _– 멀티 어카운트 환경 상의 Trusted Advisor Alarms, AWS Health Notification, AWS Support Cases 통합 뷰 제공_
* GIT - [Trusted Advisor Exposed Keys CloudWatch Event Monitor](https://github.com/aws/Trusted-Advisor-Tools/tree/master/ExposedAccessKeys) _– AWS 액세스 키가 유출되면 TA가 탐지하여 IAM으로 키를 삭제하고,해당 키로 실행된 이벤트들에 대한 요약을 CloudTrail상에서 분석하여 SNS로 전달_
* Blog - [View AWS Trusted Advisor recommendations at scale with AWS Organizations](https://aws.amazon.com/blogs/mt/organizational-view-for-trusted-advisor/)
* Blog - [Multi-account AWS Trusted Advisor summaries now available in AWS Systems Manager Explorer](https://aws.amazon.com/blogs/mt/multi-account-aws-trusted-advisor-summaries-now-available-aws-systems-manager-explorer/)




## AWS 서비스 별 로그와 감사 관련

CloudTrail상의 JSON 로그 외에도 다양한 AWS 서비스들이 자체적인 로깅 기능을 제공합니다. 관련하여 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Bastion Host Command History Logging](https://docs.aws.amazon.com/ko_kr/quickstart/latest/linux-bastion/bastion-logging.html) _– 리눅스 Bastions Host 퀵스타트 템플릿에 적용되어 있는 커맨드 히스토리 로깅_
* [Classic Load Balancer 액세스 로그](https://docs.aws.amazon.com/ko_kr/elasticloadbalancing/latest/classic/access-log-collection.html)
* [Cloudfront 액세스 로그](https://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/AccessLogs.html)
* [S3 액세스 로그](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/LogFormat.html)
* [ALB 액세스 로그](https://docs.aws.amazon.com/ko_kr/elasticloadbalancing/latest/application/load-balancer-access-logs.html)
* [RDS PostgreSQL DB 인스턴스에 대한 감사 로깅](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.PostgreSQL.CommonDBATasks.html#Appendix.PostgreSQL.CommonDBATasks.Auditing)
* [RDS MySQL 인스턴스에서 MariaDB 감사 플러그인 지원](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.MySQL.Options.AuditPlugin.html)
* [RDS MariaDB 감사 플러그인 지원](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.MariaDB.Options.html)
* [RDS Microsoft SQL Server 로그 작업](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.SQLServer.CommonDBATasks.Logs.html)
* [Amazon RDS 데이터베이스 로그 파일](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/USER_LogAccess.html) _- RDS Maria, MS SQL, mySQL, Oracle, postGre 에 대한 로그 파일 안내_
* [RDS Aurora MySQL DB 클러스터에서 고급 감사 사용하기](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/AuroraMySQL.Auditing.html)
* [RDS Aurora MySQL 데이터베이스 로그 파일](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/AuroraUserGuide/USER_LogAccess.Concepts.MySQL.html)
* [RDS Aurora PostgreSQL 데이터베이스 로그 파일](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/AuroraUserGuide/USER_LogAccess.Concepts.PostgreSQL.html)
* [RDS Oracle DB 인스턴스에 대한 공통 DBA 로그 작업](https://docs.aws.amazon.com/ko_kr/AmazonRDS/latest/UserGuide/Appendix.Oracle.CommonDBATasks.Log.html)
* [Redshift 감사 로깅](https://docs.aws.amazon.com/ko_kr/redshift/latest/mgmt/db-auditing.html)
* [AWS CloudTrail를 사용하여 DynamoDB 작업 로깅](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/logging-using-cloudtrail.html)
* [Auditing Amazon DocumentDB Events](https://docs.aws.amazon.com/documentdb/latest/developerguide/event-auditing.html)
* [ECS - Using the awslogs Log Driver](https://docs.aws.amazon.com/AmazonECS/latest/userguide/using_awslogs.html) _- CloudWatch Logs를 이용한 ECS 로깅_
* [Amazon EKS Control Plane Logging](https://docs.aws.amazon.com/eks/latest/userguide/control-plane-logs.html)
* [Athena AWS 서비스 로그 쿼리](https://docs.aws.amazon.com/ko_kr/athena/latest/ug/querying-AWS-service-logs.html) _- Athena를 이용하여 S3에 적재되는 CloudTrail, CloudFront, ELB, ALB, VPC Flow logs 에 대한 SQL기반 감사에 대한 안내_
* [Device Defender](https://docs.aws.amazon.com/ko_kr/iot/latest/developerguide/device-defender.html) _- AWS IoT 디바이스에 대한 감사/모니터링_
* [AWS Lambda 함수 로깅(Node.js)](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/nodejs-prog-model-logging.html)
* [AWS Lambda 함수 로깅(Python)](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/python-logging.html)
* [AWS Lambda 함수 로깅(Ruby)](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/ruby-logging.html)
* [AWS Lambda 함수 로깅(Java)](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/java-logging.html)
* [AWS Lambda 함수 로깅(Go)](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/go-programming-model-logging.html)
* [AWS Lambda 함수 로깅(C#)](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/dotnet-logging.html)
* Best Practice - [Native AWS Security-Logging Capabilities](https://aws.amazon.com/ko/answers/logging/aws-native-security-logging-capabilities/) _– CloudTrail, Config, Detailed Billing, S3, ELB, CloudFront, Redshift, RDS, VPC Flow Logs 등 각 서비스별 로그 기능에 대한 소개_
* Best Practice - [VPC Network Management and Monitoring](https://aws.amazon.com/ko/answers/networking/vpc-network-management-and-monitoring/) _– VPC Flow Log 등을 기반으로 VPC 모니터링을 위한 몇가지 방법을 소개_
* Best Practice - [Accessing VPC Endpoints From Remote Networks](https://aws.amazon.com/ko/answers/networking/accessing-vpc-endpoints-from-remote-networks/) _– 온프레미스 등 VPC 외부에서 VPC S3 Endpoint로의 안전하고 가용성 있는 접근 통로 구축에 대한 소개_
* Best Practice - [Centralized Logging](https://aws.amazon.com/ko/answers/logging/centralized-logging/) _– 로그 통합을 위한 AWS 및 파트너 솔루션에 대한 소개_
* Blog - [Aggregating Lambda@Edge Logs](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/aggregating-lambdaedge-logs/)
* Blog - [Centralized Container Logs with Amazon ECS and Amazon CloudWatch Logs](https://aws.amazon.com/ko/blogs/compute/centralized-container-logs-with-amazon-ecs-and-amazon-cloudwatch-logs/)





## [AWS Well-Architected Tool](https://aws.amazon.com/ko/well-architected-tool/?nc2=h_m1)

AWS Well-Architected Tool은 워크로드 상태를 검토하고 AWS 아키텍처 모범 사례와 비교하는 데 도움이 됩니다. AWS Well-Architected Tool의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Well-Architected Tool 보안](https://docs.aws.amazon.com/ko_kr/wellarchitected/latest/userguide/security.html)
* GIT - [AWS Well-Architected Security Labs](https://github.com/awslabs/aws-well-architected-labs/tree/master/Security)




## [Well-Architected Lenses](https://aws.amazon.com/ko/architecture/well-architected/?nc1=h_ls&wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc)

렌즈는 AWS Well-Architected가 기계 학습, 분석, 서버리스, 고성능 컴퓨팅(HPC), IoT(사물 인터넷) 및 금융 서비스 등 업종별, 기술 분야별로 제공하는 지침을 확장합니다. WS Well-Architected Lenses의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Management and Governance Lens](https://docs.aws.amazon.com/ko_kr/wellarchitected/latest/management-and-governance-lens/management-and-governance-lens.html)
* Blog - [Introducing the Games Industry Lens for the AWS Well-Architected Framework](https://aws.amazon.com/blogs/gametech/introducing-the-games-industry-lens-for-the-aws-well-architected-framework/)

 
## 거버넌스 및 탐지 통제와 관련된 기타 유용한 링크들

* [AWS 보안 감사 지침](https://docs.aws.amazon.com/ko_kr/general/latest/gr/aws-security-audit-guide.html)
* Best Practice - [Real-Time Insights on AWS Account Activity](https://aws.amazon.com/ko/answers/account-management/real-time-insights-account-activity/) _– AWS 어카운트 활동에 대한 준 실시간 모니터링을 위한 CloudTrail 로그 기반 대쉬보드 환경을 만들어 주는 솔루션_
* QuickStart - [Security and analytics with Palo Alto Networks and Splunk](https://aws.amazon.com/ko/quickstart/architecture/security-analytics-with-palo-alto-networks-and-splunk/) _– 팔로알토 VM시리즈 방화벽과 Splunk APP분석 환경간의 연동 템플릿을 제공하는 퀵스타트_
* QuickStart - [CI/CD Pipeline for AWS CloudFormation templates](https://aws.amazon.com/quickstart/architecture/cicd-taskcat/) _- 오픈소스인 TaskCat으로 CloudFormation 템플릿들을 테스팅하는 CodePipeline을 만들어 주는 퀵스타트_
* QuickStart - [Centralized Logging](https://aws.amazon.com/ko/solutions/implementations/centralized-logging/)
* [CIS Benchmark 시리즈](https://www.cisecurity.org/cis-benchmarks/) _- OS, Web, App, DB, DNS, Cloud 등 다양한 플랫폼에 대한 권장 설정들을 안내하는 백서를 다운받을 수 있는 싸이트_
* 동영상 [AWS Innovate 2017] - [보안 및 컴플라이언스 자동화](https://www.youtube.com/watch?v=UnT3QTDNF2c)
* 백서 - [SANS Institute - Packet Capture on AWS](https://www.sans.org/reading-room/whitepapers/detection/packet-capture-aws-37905) _- 외부 백서_
* GIT - [NCC Scout 2](https://nccgroup.github.io/Scout2/) _– 어카운트 단위로 EC2, IAM, RDS, S3에 대한 13가지 항목 점검 스크립트_
* GIT - [NCC Scout Suite](https://github.com/nccgroup/ScoutSuite)
* GIT – [Stelligent CFN_NAG](https://github.com/stelligent/cfn_nag) _– Ruby 기반으로 CloudFormation 템플릿의 보안점검 기능 제공 도구(IAM, S/G, Access Log활성화, Encryption적용 체크 등)_
* GIT – [CloudFormation Linter](https://github.com/aws-cloudformation/cfn-python-lint) _– Python 기반으로 CloudFormation 템플릿의 보안점검 기능 제공 도구_
* GIT – [AWS Security Benchmark](https://github.com/awslabs/aws-security-benchmark/) _– CIS AWS Benchmark상의 보안 항목들을 점검해주는 스크립트들_
* GIT - [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) _- CIS Benchmark 1.2 기준 보안 설정들을 어카운트 환경에 적용해 주는 테라폼 모듈_
* GIT - [Console Recorder](https://github.com/iann0036/AWSConsoleRecorder) _- AWS 관리 콘솔상의 작업을 Boto, CLI, AWS SDK, 자바스크립트, CloudFormation, CDK 코드 등으로 추출해 주는 브라우져 플러그인 프로젝트(지원되는 API 내역 확인 필)_
* GIT - [AWS Inventory](https://github.com/nccgroup/aws-inventory) _- 계정 내 모든 AWS 리소스들을 추출하여 목록화_
* GIT - [FSecure AWSPX](https://github.com/FSecureLABS/awspx)
* GIT - [CloudMapper](https://github.com/duo-labs/cloudmapper)
* GIT - [SIEM on Amazon Elasticsearch Service](https://github.com/aws-samples/siem-on-amazon-elasticsearch)
* Workshop - [ElasticSearch Log Analytic workshop](https://deh4m73phis7u.cloudfront.net/log-analytics/mainlab/)
* [ASECURE.CLOUD](https://asecure.cloud/) _- Step-by-step가이드, CloudFormation템플릿, CLI script, 블로그, 오픈소스 툴 안내_
* Blog - [How to Monitor Host-Based Intrusion Detection System Alerts on Amazon EC2 Instances](https://aws.amazon.com/ko/blogs/security/how-to-monitor-host-based-intrusion-detection-system-alerts-on-amazon-ec2-instances/) _– OSSEC(Open Source Security) HIDS의 로그를 기반으로 ElasticSearch, Kibana를 통해 가시화 시키는 예제_
* 동영상 [AWS Builders Online] - [보안 사고 예방을 위한 주요 AWS 모범 사례](https://www.youtube.com/watch?v=KGibV5yV9U8)
* 가이드 - [Centralized logging and multiple-account security guardrails](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/centralized-logging-and-multiple-account-security-guardrails.html)
* Solution - [중앙 집중식 로깅](https://aws.amazon.com/ko/solutions/implementations/centralized-logging/)
* Solution - [검증 가능한 조치 증거 저장소](https://aws.amazon.com/ko/solutions/implementations/verifiable-controls-evidence-store/) _- QLDB/DDB 사용_
* Blog - [Infoblox Inc. built a patent-pending homograph attack detection model for DNS with Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/infoblox-inc-built-a-patent-pending-homograph-attack-detection-model-for-dns-with-amazon-sagemaker/)
* Blog - [AWS Health Aware – Customize AWS Health Alerts for Organizational and Personal AWS Accounts](https://aws.amazon.com/blogs/mt/aws-health-aware-customize-aws-health-alerts-for-organizational-and-personal-aws-accounts/)
* Blog - [Optimizing cloud governance on AWS: Integrating the NIST Cybersecurity Framework, AWS Cloud Adoption Framework, and AWS Well-Architected](https://aws.amazon.com/ko/blogs/security/optimizing-cloud-governance-on-aws-integrating-the-nist-cybersecurity-framework-aws-cloud-adoption-framework-and-aws-well-architected/)
* Blog - [Introducing Assisted Log Enabler for AWS](https://aws.amazon.com/ko/blogs/opensource/introducing-assisted-log-enabler-for-aws/)
* Blog - [Introducing AWS Security Analytics Bootstrap](https://aws.amazon.com/ko/blogs/opensource/introducing-aws-security-analytics-bootstrap/)
* Blog - [Unshadow IT](https://aws.amazon.com/ko/blogs/enterprise-strategy/unshadow-it/)
* Blog - [Audit AWS service events with Amazon EventBridge and Amazon Kinesis Data Firehose](https://aws.amazon.com/blogs/big-data/audit-aws-service-events-with-amazon-eventbridge-and-amazon-kinesis-data-firehose/)
* Blog - [How to detect suspicious activity in your AWS account by using private decoy resources](https://aws.amazon.com/blogs/security/how-to-detect-suspicious-activity-in-your-aws-account-by-using-private-decoy-resources/)
* Blog - [AWS co-announces release of the Open Cybersecurity Schema Framework (OCSF) project](https://aws.amazon.com/blogs/security/aws-co-announces-release-of-the-open-cybersecurity-schema-framework-ocsf-project/)



## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.




---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>