# 침해 사고 대응 (Incident Response)

보안 침해사고 발생을 대비하여 얼마나 신속하게 정상적인 안전한 상태로 복귀할 수 있는지가 대응 계획의 중요한 부분이 됩니다. AWS에서는 다음과 같은 자동화된 도구와 모범사례를 제공합니다.

 
## [Amazon Detective](https://aws.amazon.com/ko/detective/?nc1=h_ls)

Amazon Detective는 탐지 내역이나 의심스러운 행위에 대한 직접적인 원인을 빠르게 식별하고, 분석할 수 있는 환경을 제공합니다. 관련하여 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Amazon Detective 보안](https://docs.aws.amazon.com/ko_kr/detective/latest/adminguide/security.html)
* GIT - [amazon-detective-multiaccount-scripts](https://github.com/aws-samples/amazon-detective-multiaccount-scripts)
* GIT - [AWS Security Analytics Bootstrap](https://github.com/awslabs/aws-security-analytics-bootstrap)
* Blog - [Investigate VPC flow with Amazon Detective](https://aws.amazon.com/blogs/security/investigate-vpc-flow-with-amazon-detective/)
* Blog - [Simplify setup of Amazon Detective with AWS Organizations](https://aws.amazon.com/ko/blogs/security/simplify-setup-of-amazon-detective-with-aws-organizations/)
* Blog - [Amazon Detective Supports Kubernetes Workloads on Amazon EKS for Security Investigations](https://aws.amazon.com/blogs/aws/amazon-detective-supports-kubernetes-workloads-on-amazon-eks-for-security-investigations/)


## [AWS Config Rules](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/evaluate-config.html)

고객 환경의 변경에 대응하여 자동화된 조치를 취할 수 있는 규칙을 생성할 수 있으며, 예를 들면, 해당 리소스를 격리하거나, 추가정보를 수집하고, 정상상태로 원복하는 설정을 적용할 수 있습니다. AWS Config Rules를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Config 관리형 규칙 목록](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/managed-rules-by-aws-config.html)
* [AWS CloudFormation 템플릿으로 AWS Config 관리형 규칙 만들기](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/aws-config-managed-rules-cloudformation-templates.html)
* [AWS Config 사용자 지정 규칙](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/evaluate-config_develop-rules.html)
* GIT – [Config 샘플 Custom Rule 저장소](https://github.com/awslabs/aws-config-rules)
* GIT – [Config Rule을 이용해서 멀티 어카운트 환경에 대한 규정 준수 확인용 룰셋](https://github.com/awslabs/aws-config-engine-for-compliance-as-code)
* 동영상 [AWS Summit Seoul 2016] - [AWS 고급 보안 서비스를 통한 민첩한 보안 운영 전략](https://www.youtube.com/watch?v=lRGJZThgk-Q)


## [CloudEndure Disaster Recovery](https://aws.amazon.com/ko/cloudendure-disaster-recovery/?nc1=h_ls)

CloudEndure Disaster Recovery는 물리적 서버, 가상 서버 및 클라우드 기반 서버를 AWS로 빠르고 안정적으로 복구함으로써 가동 중단 시간 및 데이터 손실을 최소화합니다. AWS CloudEndure Disaster Recovery를 보안 측면에서 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [CloudEndure Documentation](https://docs.cloudendure.com/CloudEndure%20Documentation.htm)
* 가이드 - [Configure SAML SSO from Microsoft Azure AD to CloudEndure Migration](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/configure-saml-sso-from-microsoft-azure-ad-to-cloudendure-migration.html)
* Blog - [Integrating CloudEndure Disaster Recovery into your security incident response plan](https://aws.amazon.com/blogs/security/integrating-cloudendure-disaster-recovery-into-your-security-incident-response-plan/)
* Blog - [Optimizing operational costs in CloudEndure Disaster Recovery](https://aws.amazon.com/blogs/storage/optimizing-operational-costs-in-cloudendure-disaster-recovery/)
* Blog - [How to perform non-disruptive CloudEndure Disaster Recovery tests on AWS](https://aws.amazon.com/blogs/storage/how-to-perform-non-disruptive-cloudendure-disaster-recovery-tests-on-aws/)
* Blog - [VMware vCenter Disaster Recovery using CloudEndure Disaster Recovery](https://aws.amazon.com/blogs/storage/vmware-vcenter-disaster-recovery-using-cloudendure-disaster-recovery/)
* Blog - [Disaster recovery insights with CloudEndure Disaster Recovery Factory](https://aws.amazon.com/blogs/storage/disaster-recovery-insights-with-cloudendure-disaster-recovery-factory/)
 
 
## 침해사고 대응과 관련된 기타 유용한 링크들

* Support - [내 AWS 계정이 해킹당한 것 같습니다.](https://aws.amazon.com/ko/premiumsupport/knowledge-center/potential-account-compromise/) _- AWS 계정이 해킹당했다고 연락을 받았거나 의심이 갈때 대응방법 안내 혹은 사전에 조치할 수 있는 모범 사례 등을 안내_
* Support - [How do I report abuse of AWS resources?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/report-aws-abuse/?nc1=h_ls) _- 스팸, 디도스, 스캐닝, 침입시도, 정보 탈취시도, 멀웨어 공격 등 다른 사용자의 AWS 리소스로 부터의 각종 침입 및 공격 시도에 대해 대응하는 절차를 안내_
* Support - [AWS 계정에서 무단 활동이 발견되면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/potential-account-compromise/)
* Solutions - [Automated Forensics Orchestrator for Amazon EC2](https://aws.amazon.com/solutions/implementations/automated-forensics-orchestrator-for-amazon-ec2/?did=sl_card&trk=sl_card)
* GIT – [GRR](https://github.com/google/grr) _- 구글이 만든 Python기반 IR 프레임웍_
* GIT - [LiMEaide](https://kd8bny.github.io/LiMEaide/) _- Linux 메모리 캡춰 툴_
* GIT - [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) _- Linux 메모리 캡춰 툴_
* GIT - [AWS Incident Response Runbook Samples](https://github.com/aws-samples/aws-incident-response-runbooks)
* GIT - [Awesome Threat Modeling](https://github.com/hysnsec/awesome-threat-modelling#threat-model-examples)
* GIT - [MITRE CTI](https://github.com/mitre/cti)
* GIT - [MITRE Caldera](https://github.com/mitre/caldera)
* GIT - [MITRE S3 Baseline](https://github.com/mitre/aws-s3-baseline)
* GIT - [MITRE AWS Foundation Baseline](https://github-dotcom.gateway.web.tr/mitre/aws-foundations-cis-baseline)
* GIT - [MITRE RDS Baseilne](https://github-dotcom.gateway.web.tr/mitre/aws-rds-crunchy-data-postgresql-9-stig-baseline)
* GIT - [Guardicore](https://github.com/guardicore/monkey)
* GIT - [Guardicore Lab's Repository](https://github.com/guardicore/labs_campaigns)
* GIT - [Amazon GuardDuty Tester](https://github.com/awslabs/amazon-guardduty-tester)
* GIT - [Log4jHotPatch](https://github.com/corretto/hotpatch-for-apache-log4j2)
* STIX - [STIX](https://oasis-open.github.io/cti-documentation/stix/intro.html)
* MITRE ATT&CK - [AWS Matrix](https://attack.mitre.org/matrices/enterprise/cloud/aws/)
* MITRE ATT&CK - [Att&ck Nivigator](https://mitre-attack.github.io/attack-navigator/enterprise/)
* GIT - [Amazon Web Services Security Control Mappings to MITRE ATT&CK](https://center-for-threat-informed-defense.github.io/security-stack-mappings/AWS/README.html#contents)
* GIT – [Threat Response](https://github.com/ThreatResponse) _- AWS 환경에 대한 포렌식 도구들_
* GIT - [Fargate IR](https://github.com/andrewkrug/fargate-ir) _- Fargate환경에 대한 IR구성 템플릿, PoC 레벨임_
* Ext. - [KISA 인터넷 보호나라 인터넷 침해사고 - 상담 및 신고](https://www.boho.or.kr/consult/hacking.do)
* Ext. - [KISA 인터넷 보호나라 인터넷 침해사고 - 신고 가이드 및 매뉴얼](https://www.krcert.or.kr/data/guideView.do?bulletin_writing_sequence=27050)
* 동영상 [AWS Summit Seoul 2020] - [AWS 환경에서의 위협 탐지 및 사냥](https://www.youtube.com/watch?v=iPKaylieTV8&t=46s)
* Blog - [How to get started with security response automation on AWS](https://aws.amazon.com/blogs/security/how-get-started-security-response-automation-aws/)
* Blog - [How to perform automated incident response in a multi-account environment](https://aws.amazon.com/blogs/security/how-to-perform-automated-incident-response-multi-account-environment/)
* Blog - [How to automate incident response in the AWS Cloud for EC2 instances](https://aws.amazon.com/blogs/security/how-to-automate-incident-response-in-aws-cloud-for-ec2-instances/)
* Blog - [How to approach threat modeling](https://aws.amazon.com/ko/blogs/security/how-to-approach-threat-modeling/)
* Blog - [Automate Amazon EC2 instance isolation by using tags](https://aws.amazon.com/blogs/security/automate-amazon-ec2-instance-isolation-by-using-tags/)
* Blog - [Creating contacts, escalation plans, and response plans in AWS Systems Manager Incident Manager](https://aws.amazon.com/blogs/mt/creating-contacts-escalation-plans-response-plans-aws-systems-manager-incident-manager/)
* Blog - [How to perform automated incident response in a multi-account environment](https://aws.amazon.com/ko/blogs/security/how-to-perform-automated-incident-response-multi-account-environment/)
* Blog - [Forensic investigation environment strategies in the AWS Cloud](https://aws.amazon.com/blogs/security/forensic-investigation-environment-strategies-in-the-aws-cloud/)
* Blog - [Apache Log4j2 보안 이슈 (CVE-2021-44228) 대응 공지](https://aws.amazon.com/ko/blogs/korea/aws-security-bulletins-cve-2021-44228/)
* Blog - [Apache Log4j용 핫패치 제공](https://aws.amazon.com/ko/blogs/korea/hotpatch-for-apache-log4j/)
* Blog - [Using AWS security services to protect against, detect, and respond to the Log4j vulnerability](https://aws.amazon.com/ko/blogs/security/using-aws-security-services-to-protect-against-detect-and-respond-to-the-log4j-vulnerability/)
* Blog - [Advice on mitigating the Apache log4j security issue for EKS, ECS, and Fargate customers](https://aws.amazon.com/ko/blogs/containers/advice-on-mitigating-the-apache-log4j-security-issue-for-eks-ecs-and-fargate-customers/)
* Blog - [AWS resources to address Apache Log4j vulnerabilities](https://aws.amazon.com/ko/blogs/publicsector/aws-resources-to-address-apache-log4j-vulnerabilities/)
* Blog - [Top 10 security best practices for securing backups in AWS](https://aws.amazon.com/ko/blogs/security/top-10-security-best-practices-for-securing-backups-in-aws/)
* Blog - [Automate and improve your security posture using AWS Backup and AWS PrivateLink](https://aws.amazon.com/ko/blogs/storage/use-aws-backup-and-aws-privatelink-for-automation-and-improved-security-posture/)
* Blog - [Journey to Adopt Cloud-Native Architecture Series #5 – Enhancing Threat Detection, Data Protection, and Incident Response](https://aws.amazon.com/blogs/architecture/journey-to-adopt-cloud-native-architecture-series-5-enhancing-threat-detection-data-protection-and-incident-response/)
* Blog - [Banking Trends 2022: Cyber vault and Ransomware](https://aws.amazon.com/ko/blogs/industries/banking-trends-2022-cyber-vault-and-ransomware/)
* Blog - [Welcoming the AWS Customer Incident Response Team](https://aws.amazon.com/blogs/security/welcoming-the-aws-customer-incident-response-team/)

## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.



---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>