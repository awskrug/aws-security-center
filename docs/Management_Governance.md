# Management & Governance
AWS Orgnization, CloudWatch, CloudTrail, Config, Trusted Advisor, Control Tower, System Manager에 대한 내용은 AWS 보안 서비스의 각 보안 영역들에 포함되어 있습니다. 그 외의 관리 및 거버닝 서비스들이 제공하는 보안 기능에 대한 유용한 링크들은 아래에서 참조하실 수 있습니다.


## [AWS Auto Scaling](https://aws.amazon.com/ko/autoscaling/?nc2=h_m1)

AWS Auto Scaling은 애플리케이션을 모니터링하고 용량을 자동으로 조정하여, 최대한 저렴한 비용으로 안정적이고 예측 가능한 성능을 유지합니다. AWS Auto Scaling의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon EC2 Auto Scaling의 보안](https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/security.html)




## [CloudFormation](https://aws.amazon.com/ko/cloudformation/?nc2=h_m1)

AWS CloudFormation에서는 클라우드 환경 내 인프라 리소스를 모두 설명하고 프로비저닝할 수 있도록 공통 언어를 제공합니다. CloudFormation의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS CloudFormation의 보안](https://docs.aws.amazon.com/ko_kr/AWSCloudFormation/latest/UserGuide/security.html)
* [Asia Pacific (Seoul) Region 샘플 템플릿](https://docs.aws.amazon.com/ko_kr/AWSCloudFormation/latest/UserGuide/cfn-sample-templates-ap-northeast-2.html)
* AWS Solutions - [AWS CloudFormation Validation Pipeline](https://aws.amazon.com/solutions/aws-cloudformation-validation-pipeline/)
* Quickstart - [CI/CD Pipeline for AWS CloudFormation templates](https://aws.amazon.com/quickstart/architecture/cicd-taskcat/) _- 오픈소스인 TaskCat으로 CloudFormation 템플릿들을 테스팅하는 CodePipeline을 만들어 주는 퀵스타트_
* 동영상 - [Manage Compliance Across Accounts with AWS CloudFormation StackSets](https://www.youtube.com/watch?v=ZzD9I8ur6lg&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=21)
* 가이드 - [Ensure that AWS CloudFormation stacks are launched from authorized S3 buckets](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/ensure-that-aws-cloudformation-stacks-are-launched-from-authorized-s3-buckets.html)
* GIT - [CloudFormation Macro / Transform Examples](https://github.com/KablamoOSS/cfn-macros?utm_campaign=ServerlessOps%20-%20Syndication&utm_content=76863108&utm_medium=social&utm_source=twitter)
* GIT - [taskcat : testing CFN template](https://github.com/aws-quickstart/taskcat)
* GIT - [CloudFormation Linter : Validation of CFN template](https://github.com/aws-cloudformation/cfn-python-lint) _– Python 기반으로 CloudFormation 템플릿의 보안점검 기능 제공 도구_
* GIT - [stelligent CFN_NAG : security check](https://github.com/stelligent/cfn_nag) _– Ruby 기반으로 CloudFormation 템플릿의 보안점검 기능 제공 도구(IAM, S/G, Access Log활성화, Encryption적용 체크 등)_
* GIT - [AWS Cloud Development Kit (AWS CDK)](https://github.com/aws/aws-cdk)
* [CDK Workshop](https://cdkworkshop.com/)
* GIT - [CloudFormation Public Coverage Roadmap](https://github.com/aws-cloudformation/aws-cloudformation-coverage-roadmap)
* GIT - [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard)
* Blog - [Working with the AWS Cloud Development Kit and AWS Construct Library](https://aws.amazon.com/blogs/developer/working-with-the-aws-cloud-development-kit-and-aws-construct-library/)
* Blog - [Multiple-account, multiple-Region AWS CloudFormation](https://aws.amazon.com/blogs/infrastructure-and-automation/multiple-account-multiple-region-aws-cloudformation/)
* Blog - [How to implement the principle of least privilege with CloudFormation StackSets](https://aws.amazon.com/blogs/security/how-to-implement-the-principle-of-least-privilege-with-cloudformation-stacksets/)
* Blog - [Validate IAM policies in CloudFormation templates using IAM Access Analyzer](https://aws.amazon.com/ko/blogs/security/validate-iam-policies-in-cloudformation-templates-using-iam-access-analyzer/)
* Blog - [Policy-as-Code for Securing AWS and Third-Party Resource Types](https://aws.amazon.com/ko/blogs/mt/policy-as-code-for-securing-aws-and-third-party-resource-types/)


## [OpsWorks](https://aws.amazon.com/ko/opsworks/?nc2=h_m1)

AWS OpsWorks는 Chef 및 Puppet의 관리형 인스턴스를 제공하는 구성 관리 서비스입니다. OpsWorks의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS OpsWorks Stacks 보안 및 권한](https://docs.aws.amazon.com/ko_kr/opsworks/latest/userguide/workingsecurity.html)
* [AWS OpsWorks Configuration Management(CM)의 보안](https://docs.aws.amazon.com/ko_kr/opsworks/latest/userguide/security-opscm.html)




## [Service Catalog](https://aws.amazon.com/ko/servicecatalog/?nc2=h_m1)

AWS Service Catalog를 사용하는 조직은 AWS에서 사용이 승인된 IT 서비스 카탈로그를 생성하고 관리할 수 있습니다. Service Catalog의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Service Catalog의 보안](https://docs.aws.amazon.com/ko_kr/servicecatalog/latest/adminguide/security.html)
* Best Practice - [AWS Service Catalog Validation Pipeline](https://aws.amazon.com/ko/answers/devops/aws-service-catalog-validation-pipeline/) _– AWS Code시리즈를 이용하여 Service Catalog Product 템플릿의 자동화된 검증을 위한 환경을 만들어 주는 솔루션_
* 동영상 - [Automate Account Creation Using AWS Service Catalog](https://www.youtube.com/watch?v=PPybKJubMeY&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=30)
* GIT - [aws-service-catalog-factory](https://github.com/awslabs/aws-service-catalog-factory#aws-service-catalog-factory) _- 멀티 리전을 지원하는 SC 포트폴리오를 구성_
* GIT - [aws-service-catalog-puppet](https://github.com/awslabs/aws-service-catalog-puppet) _- 멀티 어카운트 / 멀티 리전 환경에 SC Product을 배포_
* Blog - [Automate account creation, and resource provisioning using AWS Service Catalog, AWS Organizations, and AWS Lambda](https://aws.amazon.com/blogs/mt/automate-account-creation-and-resource-provisioning-using-aws-service-catalog-aws-organizations-and-aws-lambda/)
* Blog - [Secure cloud assets using AWS Service Catalog’s Attribute Based Access Control](https://aws.amazon.com/blogs/mt/secure-cloud-assets-using-aws-service-catalogs-attribute-based-access-control/)



## [AWS License Manager](https://aws.amazon.com/ko/license-manager/?nc2=h_m1)

AWS License Manager를 사용하면 AWS 및 온프레미스 서버에서 Microsoft, SAP, Oracle 및 IBM 같은 소프트웨어 공급업체의 라이선스를 더 쉽게 관리할 수 있습니다. AWS License Manager의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS License Manager의 보안](https://docs.aws.amazon.com/ko_kr/license-manager/latest/userguide/security.html)
* 동영상 - [Manage Licenses Across Multiple AWS Accounts with AWS License Manager](https://www.youtube.com/watch?v=BjiX41VKZ_c&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=28)
* 동영상 - [Enforce License Rules with AWS License Manager](https://www.youtube.com/watch?v=XXld4atfQ-0&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=29)
* 동영상 - [Manage Software Licenses with AWS License Manager](https://www.youtube.com/watch?v=ikL5Axehutk&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=20)



## [Personal Health Dashboard](https://aws.amazon.com/ko/premiumsupport/technology/personal-health-dashboard/?nc2=h_m1)

AWS Personal Health Dashboard는 AWS에 고객에게 영향을 미칠 수 있는 이벤트가 발생할 때 알림 및 해결 지침을 제공합니다. Personal Health Dashboard의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Health의 보안](https://docs.aws.amazon.com/ko_kr/health/latest/ug/security.html)


## [AWS Chatbot](https://aws.amazon.com/ko/chatbot/?nc2=h_m1)

AWS Chatbot은 Slack 채널 및 Amazon Chime 채팅방을 통해 AWS 리소스를 쉽게 모니터링하고 상호 작용하도록 지원하는 대화형 에이전트입니다. AWS Chatbot의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in AWS Chatbot](https://docs.aws.amazon.com/ko_kr/chatbot/latest/adminguide/security.html)


## [AWS Compute Optimizer](https://aws.amazon.com/ko/compute-optimizer/?nc1=h_ls)

AWS Compute Optimizer는 과거 사용이력 메트릭들을 분석하는 기계학습기반을 이용하여 비용을 절감하고 성능을 향상시킬수 있는 최적화된 컴퓨트 리소스들을 제안해 드리는 서비스입니다. Compute Optimizer의 보안 관련 기능들은 아래와 같습니다.

**Bookmark**

* [Controlling Access with AWS Identity and Access Management](https://docs.aws.amazon.com/ko_kr/compute-optimizer/latest/ug/security-iam.html)



## [Resource Group](https://docs.aws.amazon.com/ko_kr/ARG/latest/userguide/welcome.html)

리소스 그룹을 사용하여 AWS 리소스를 정리할 수 있습니다. 리소스 그룹을 사용하여 많은 리소스에 대한 작업을 한번에 관리하고 자동화할 수 있습니다. Resource Group의 보안 관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Resource Groups의 보안](https://docs.aws.amazon.com/ko_kr/ARG/latest/userguide/security.html)



## [Service Quotas](https://docs.aws.amazon.com/ko_kr/servicequotas/latest/userguide/intro.html)

Service Quotas은 한 곳에서 100개가 넘는 AWS 서비스에 대한 할당량을 관리하는 데 도움이 되는 AWS 서비스입니다. 할당량 값을 조회하는 것과 함께 Service Quotas 콘솔에서 할당량 증가를 요청할 수도 있습니다. Service Quotas의 보안 관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in Service Quotas](https://docs.aws.amazon.com/ko_kr/servicequotas/latest/userguide/security.html)




## [Proton](https://aws.amazon.com/ko/proton/)

AWS Proton은 컨테이너 및 서버리스 애플리케이션을 위한 최초의 완전관리형 애플리케이션 배포 서비스입니다. 플랫폼 엔지니어링 팀은 AWS Proton을 사용하여 인프라 프로비저닝, 코드 배포, 모니터링, 업데이트에 필요한 각종 도구를 연결하고 조정할 수 있습니다. Proton의 보안 관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in Proton](https://docs.aws.amazon.com/proton/latest/adminguide/ag-security.html)
* GIT - [AWS Proton sample templates](https://github.com/aws-samples/aws-proton-sample-templates)



## [AWS Fault Injection Simulator](https://aws.amazon.com/fis/)

AWS Fault Injection Simulator는 장애를 주입하고 어떤 일이 발생하는지 볼 수 있도록 하여 AWS 워크로드에 대한 통제 된 실험을 수행하는 데 도움이 되는 AWS 서비스입니다. 이를 통해 시스템이 다양한 유형의 오류에 어떻게 반응하는지 배우고, 오류 모드를 더 잘 이해할 수 있습니다. AWS Fault Injection Simulator는 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Fault Injection Simulator의 보안](https://docs.aws.amazon.com/ko_kr/fis/latest/userguide/security.html)
* Blog - [AWS Fault Injection Simulator 정식 출시 – 제어된 장애 주입 실험을 통한 복원력 향상 (서울 리전 포함)](https://aws.amazon.com/ko/blogs/korea/aws-fault-injection-simulator-use-controlled-experiments-to-boost-resilience/)


## [AWS Resilience Hub](https://aws.amazon.com/resilience-hub/)

AWS Resilience Hub 는 여러분의 AWS 어플리케이션의 Resiliency 를 정의하고 유효성을 검증하고 추적하기 위한 통합된 환경을 제공합니다. 

* [Security in AWS Resilience Hub](https://docs.aws.amazon.com/resilience-hub/latest/userguide/security.html)

## [AWS AppConfig](https://docs.aws.amazon.com/ko_kr/appconfig/)

AWS AppConfig를 사용하여 애플리케이션 구성을 어떤 크기의 애플리케이션에든 신속하게 배포할 수 있습니다. AWS AppConfig는 제어된 배포를 지원하며 검증 및 모니터링 기능을 기본으로 포함하고 있습니다.  

* [AWS AppConfig의 보안](https://docs.aws.amazon.com/ko_kr/appconfig/latest/userguide/appconfig-security.html)

## [AWS Backint Agent for SAP HANA](https://docs.aws.amazon.com/ko_kr/backint/)

AWS Resilience Hub 는 여러분의 AWS 어플리케이션의 Resiliency 를 정의하고 유효성을 검증하고 추적하기 위한 통합된 환경을 제공합니다. 

* [Migrating SAP HANA to AWS : Security](https://docs.aws.amazon.com/ko_kr/sap/latest/sap-hana/migrating-hana-security.html)
* [SAP HANA on AWS Operations : Security](https://docs.aws.amazon.com/ko_kr/sap/latest/sap-hana/hana-ops-security.html)

## [AWS Data Lifecycle Manager](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/snapshot-lifecycle.html)

Amazon 데이터 수명 주기 관리자에서는 AWS 리소스의 수명 주기를 관리할 수 있습니다. 수명 주기 정책을 생성하여 특정 리소스에 대한 작업을 자동화합니다.

* [IAM](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/dlm-prerequisites.html)

## [AWS Health](https://docs.aws.amazon.com/ko_kr/health/latest/ug/what-is-aws-health.html)

AWS Health는 사용자의 AWS 인프라에 영향을 미칠 수 있는 이벤트에 대한 맞춤형 정보를 제공하고, 예정된 변경 사항을 안내하고, 사용자의 AWS 리소스 및 계정에 영향을 미치는 문제를 신속하게 해결할 수 있게 합니다. 

* [AWS Health의 보안](https://docs.aws.amazon.com/ko_kr/health/latest/ug/security.html)

## [AWS Launch Wizard](https://aws.amazon.com/ko/launchwizard/)

AWS Launch Wizard는 개별 AWS 리소스를 수동으로 식별하고 프로비저닝하지 않고도 AWS 리소스를 Microsoft SQL Server Always On 및 HANA 기반 SAP 시스템과 같은 서드 파티 애플리케이션용으로 크기 조정, 구성 및 배포하는 과정으로 안내합니다.  

* [AWS Launch Wizard security](https://docs.aws.amazon.com/ko_kr/launchwizard/latest/userguide/launch-wizard-security.html)

## [AWS Managed Grafana](https://aws.amazon.com/ko/grafana/)

Amazon Managed Grafana는 Grafana Labs와 협력하여 개발한 오픈 소스 Grafana용 완전관리형 서비스입니다. Grafana는 지표가 저장된 위치에 관계없이 지표를 쿼리하고, 시각화하고, 알리고, 이해할 수 있도록 지원하는 널리 사용되는 오픈 소스 분석 플랫폼입니다.

* [Security in Amazon Managed Grafana](https://docs.aws.amazon.com/grafana/latest/userguide/security.html)
* Blog - [Setting up Amazon Managed Grafana cross-account data source using customer managed IAM roles](https://aws.amazon.com/ko/blogs/opensource/setting-up-amazon-managed-grafana-cross-account-data-source-using-customer-managed-iam-roles/)
* Blog - [Fine-grained access control in Amazon Managed Grafana using Grafana Teams](https://aws.amazon.com/blogs/mt/fine-grained-access-control-in-amazon-managed-grafana-using-grafana-teams/)
* Blog - [Authenticating with Amazon Managed Grafana Using Open Source Keycloak on Amazon EKS](https://aws.amazon.com/blogs/opensource/authenticating-with-amazon-managed-grafana-using-open-source-keycloak-on-amazon-eks/)


## [AWS Managed Service for Prometheus](https://aws.amazon.com/ko/prometheus/)

Amazon Managed Service for Prometheus(AMP)는 대규모의 컨테이너형 애플리케이션 및 인프라를 쉽게 모니터링할 수 있는 새로운 Prometheus 호환 모니터링 및 알림 서비스입니다. 

* [Security in Amazon Managed Service for Prometheus](https://docs.aws.amazon.com/prometheus/latest/userguide/security.html)

## [AWS Tag Editor](https://docs.aws.amazon.com/ko_kr/ARG/latest/userguide/tag-editor.html)

태그란 AWS 리소스를 식별하고 정리할 때 사용할 수 있는 메타데이터 역할을 하는 단어 또는 문구입니다. 리소스에는 최대 50개 사용자 적용 태그가 포함될 수 있습니다. 또한 읽기 전용 시스템 태그가 포함될 수 있습니다. 각 태그는 키와 하나의 값(선택 사항)으로 구성됩니다. 

* [AWS 리소스에 태그 지정](https://docs.aws.amazon.com/ko_kr/ARG/latest/userguide/tagging.html)

## Management & Governance과 관련된 기타 유용한 링크들

* 동영상 - [Manage Security Configurations with Chef InSpec](https://www.youtube.com/watch?v=eyMjXEwuygc&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=18)
* 동영상 - [Run Automations Across Multiple AWS Regions and Accounts](https://www.youtube.com/watch?v=HA59eSImPaw&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=14)
* 동영상 - [Maintain Compliance with Ansible Playbooks](https://www.youtube.com/watch?v=jANYuCqnJEI&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=11)
* Solutions - [Tag Tamer](https://aws.amazon.com/solutions/implementations/tag-tamer/?did=sl_card&trk=sl_card)

## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.

---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 



<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>