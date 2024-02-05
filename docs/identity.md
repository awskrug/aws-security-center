# 사용자 관리 (Identity Management)

AWS가 제공하는 서비스들과 리소스에 대해 어떤 작업을 수행할 수 있는지를 사용자 별로 정의하고, 권한을 통제할 수 있는 기능과 관련된 영역입니다. 이 영역에 해당하는 AWS 보안 서비스들에는 다음과 같은 것들이 있습니다. 
 

## [AWS IAM(Identity and Access Management)](https://aws.amazon.com/ko/iam/)

사용자 별로 AWS 서비스들과 리소스에 대한 접근을 안전하게 통제(인증/인가)하는 기능을 제공합니다. AWS IAM을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [IAM 및 AWS STS의 보안](https://docs.aws.amazon.com/ko_kr/IAM/latest/UserGuide/security.html)
* [AWS 서비스에 사용되는 작업, 리소스 및 조건 키](https://docs.aws.amazon.com/ko_kr/service-authorization/latest/reference/reference_policies_actions-resources-contextkeys.html)
* [Welcome to the AWS Security Token Service API Reference](https://docs.aws.amazon.com/ko_kr/STS/latest/APIReference/welcome.html)
* [Welcome to the AWS IAM Access Analyzer](https://docs.aws.amazon.com/ko_kr/access-analyzer/latest/APIReference/Welcome.html)
* 동영상 [AWS Summit Seoul 2018] - [클라우드 여정을 성공적으로 수행하기 위한 AWS IAM 활용 전략](https://youtu.be/e1lV4lyNWGg)
* 동영상 [AWS Summit Seoul 2019] - [IAM 정책을 잘 알아야 AWS 보안도 쉬워진다. 이것은 꼭 알고 가자!](https://www.youtube.com/watch?v=iPKaylieTV8&t=46s)
* External - [Complete AWS IAM Reference](https://iam.cloudonaut.io/)
* Support - [Create Cloudwatch Event rule to notify me root user account was used](https://aws.amazon.com/premiumsupport/knowledge-center/root-user-account-cloudwatch-rule/)
* Support - [일시 중지된 AWS 계정 다시 활성화](https://aws.amazon.com/ko/premiumsupport/knowledge-center/reactivate-suspended-account/)
* Support - [Why did I receive an "AccessDenied" or "Invalid information" error trying to assume a cross-account IAM role?](https://aws.amazon.com/premiumsupport/knowledge-center/iam-assume-role-error/)
* Solution - [Automated Account Configuration](https://aws.amazon.com/ko/solutions/implementations/automated-account-configuration/)
* 가이드 - [Automatically rotate IAM user access keys](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/automatically-rotate-iam-user-access-keys.html)
* 가이드 - [Send a notification when an IAM user is created](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/send-a-notification-when-an-iam-user-is-created.html)
* GIT - [CloudTracker](https://github.com/duo-labs/cloudtracker) _- CloudTrail 로그 기반으로 한번도 사용 안한 권한에 대해 리포팅하는 툴_
* GIT - [Principal Mapper](https://github.com/nccgroup/PMapper) _- IAM User와 Role 간의 관계를 가시화_
* GIT - [git-secrets](https://github.com/awslabs/git-secrets) _- git에 AccessKeypair가 유출되었는지를 Scanning_
* GIT - [Gitleaks](https://github.com/zricethezav/gitleaks) _- git에 AccessKeypair가 유출되었는지를 Scanning_
* GIT - [cred_scanner](https://github.com/disruptops/cred_scanner) _- git에 AccessKeypair가 유출되었는지를 Scanning_
* GIT - [SKYARK](https://github.com/cyberark/SkyArk) _- IAM 특권 User를 식별하고 Cloudtrail상에 기록된 중요 IAM action들을 분석하는 툴_
* GIT - [AWS KERBEROS STS](https://github.com/commercehub-oss/kerb-sts) _- SAML IdP 기반으로 커베로스 인증하면 1시간 짜리 STS토큰이 발급되어 CLI를 이용할 수 있게 만들어 주는 스크립트 예제_
* GIT - [List of AWS Service Principals](https://gist.github.com/shortjared/4c1e3fe52bdfa47522cfe5b41e5d6f22)
* GIT - [assume-aws-role](https://github.com/jbuck/assume-aws-role)
* GIT - [Aardvark](https://github.com/Netflix-Skunkworks/aardvark)
* GIT - [Repokid](https://github.com/Netflix/repokid)
* GIT - [BLESS - Bastion's Lambda Ephemeral SSH Service](https://github.com/Netflix/bless)
* GIT - [iamlive](https://github.com/iann0036/iamlive)
* GIT - [parliament](https://github.com/duo-labs/parliament/) _- IAM 정책 구문오류 분석_
* Blog - [Use YubiKey security key to sign into AWS Management Console with YubiKey for multi-factor authentication](https://aws.amazon.com/blogs/security/use-yubikey-security-key-sign-into-aws-management-console/)
* Blog - [Monitor and Notify on AWS Account Root User Activity](https://aws.amazon.com/ko/blogs/mt/monitor-and-notify-on-aws-account-root-user-activity/)
* Blog - [Setting permissions to enable accounts for upcoming AWS Regions](https://aws.amazon.com/blogs/security/setting-permissions-to-enable-accounts-for-upcoming-aws-regions/) _- 신규 도입 리전에 대한 IAM 활성화/비활성화 기능을 설명하는 블로그_
* Blog - [Create fine-grained session permissions using IAM managed policies](https://aws.amazon.com/blogs/security/create-fine-grained-session-permissions-using-iam-managed-policies/)
* Blog - [How to automate SAML federation to multiple AWS accounts from Microsoft Azure Active Directory](https://aws.amazon.com/blogs/security/how-to-automate-saml-federation-to-multiple-aws-accounts-from-microsoft-azure-active-directory/)
* Blog - [Introducing fine-grained IAM roles for service accounts](https://aws.amazon.com/blogs/opensource/introducing-fine-grained-iam-roles-service-accounts/)
* Blog - [Working backward: From IAM policies and principal tags to standardized names and tags for your AWS resources](https://aws.amazon.com/blogs/security/working-backward-from-iam-policies-and-principal-tags-to-standardized-names-and-tags-for-your-aws-resources/)
* Blog - [Create fine-grained session permissions using IAM managed policies](https://aws.amazon.com/blogs/security/create-fine-grained-session-permissions-using-iam-managed-policies/)
* Blog - [How to centralize and automate IAM policy creation in sandbox, development, and test environments](https://aws.amazon.com/blogs/security/how-to-centralize-and-automate-iam-policy-creation-in-sandbox-development-and-test-environments/)
* Blog - [Automate analyzing your permissions using IAM access advisor APIs](https://aws.amazon.com/blogs/security/automate-analyzing-permissions-using-iam-access-advisor/)
* Blog - [Simplify granting access to your AWS resources by using tags on AWS IAM users and roles](https://aws.amazon.com/blogs/security/simplify-granting-access-to-your-aws-resources-by-using-tags-on-aws-iam-users-and-roles/)
* Blog - [Add Tags to Manage Your AWS IAM Users and Roles](https://aws.amazon.com/blogs/security/add-tags-to-manage-your-aws-iam-users-and-roles/)
* Blog - [Delegate permission management to developers by using IAM permissions boundaries](https://aws.amazon.com/blogs/security/delegate-permission-management-to-developers-using-iam-permissions-boundaries/)
* Blog - [How to Rotate Access Keys for IAM Users](https://aws.amazon.com/blogs/security/how-to-rotate-access-keys-for-iam-users/)
* Blog - [Use IAM to share your AWS resources with groups of AWS accounts in AWS Organizations](https://aws.amazon.com/blogs/security/iam-share-aws-resources-groups-aws-accounts-aws-organizations/)
* Blog - [Unit testing IAM policies across multiple accounts](https://aws.amazon.com/blogs/devops/unit-testing-iam-policies-across-multiple-accounts/)
* Blog - [AWS IAM introduces updated policy defaults for IAM user passwords](https://aws.amazon.com/blogs/security/aws-iam-introduces-updated-policy-defaults-for-iam-user-passwords/)
* Blog - [Easily control the naming of individual IAM role sessions](https://aws.amazon.com/blogs/security/easily-control-naming-individual-iam-role-sessions/)
* Blog - [Enhance programmatic access for IAM users using a YubiKey for multi-factor authentication](https://aws.amazon.com/blogs/security/enhance-programmatic-access-for-iam-users-using-yubikey-for-multi-factor-authentication/)
* Blog - [New! Streamline existing IAM Access Analyzer findings using archive rules](https://aws.amazon.com/blogs/security/new-streamline-existing-iam-access-analyzer-findings-using-archive-rules/)
* Blog - [How to automatically archive expected IAM Access Analyzer findings](https://aws.amazon.com/blogs/security/how-to-automatically-archive-expected-iam-access-analyzer-findings/)
* Blog - [New IAMCTL tool compares multiple IAM roles and policies](https://aws.amazon.com/blogs/security/new-iamctl-tool-compares-multiple-iam-roles-and-policies/)
* Blog - [How to use trust policies with IAM roles](https://aws.amazon.com/blogs/security/how-to-use-trust-policies-with-iam-roles/)
* Blog - [Techniques for writing least privilege IAM policies](https://aws.amazon.com/blogs/security/techniques-for-writing-least-privilege-iam-policies/)
* Blog - [Add defense in depth against open firewalls, reverse proxies, and SSRF vulnerabilities with enhancements to the EC2 Instance Metadata Service](https://aws.amazon.com/blogs/security/defense-in-depth-open-firewalls-reverse-proxies-ssrf-vulnerabilities-ec2-instance-metadata-service/)
* Blog - [Identify unused IAM roles and remove them confidently with the last used timestamp](https://aws.amazon.com/blogs/security/identify-unused-iam-roles-remove-confidently-last-used-timestamp/)
* Blog - [How to scale your authorization needs by using attribute-based access control with S3](https://aws.amazon.com/blogs/security/how-to-scale-authorization-needs-using-attribute-based-access-control-with-s3/)
* Blog - [Validate access to your S3 buckets before deploying permissions changes with IAM Access Analyzer](https://aws.amazon.com/blogs/security/validate-access-to-your-s3-buckets-before-deploying-permissions-changes-with-iam-access-analyzer/)
* Blog - [Reset Your AWS Root Account’s Lost MFA Device Faster by Using the AWS Management Console](https://aws.amazon.com/blogs/security/reset-your-aws-root-accounts-lost-mfa-device-faster-by-using-the-aws-management-console/)
* Blog - [IAM Access Analyzer makes it easier to implement least privilege permissions by generating IAM policies based on access activity](https://aws.amazon.com/blogs/security/iam-access-analyzer-makes-it-easier-to-implement-least-privilege-permissions-by-generating-iam-policies-based-on-access-activity/)
* Blog - [How to relate IAM role activity to corporate identity](https://aws.amazon.com/ko/blogs/security/how-to-relate-iam-role-activity-to-corporate-identity/)
* Blog - [How to use AWS IAM Access Analyzer API to automate detection of public access to AWS KMS keys](https://aws.amazon.com/ko/blogs/security/how-to-use-aws-iam-access-analyzer-api-to-automate-detection-of-public-access-to-aws-kms-keys/)
* Blog - [Review last accessed information to identify unused EC2, IAM, and Lambda permissions and tighten access for your IAM roles](https://aws.amazon.com/ko/blogs/security/review-last-accessed-information-to-identify-unused-ec2-iam-and-lambda-permissions-and-tighten-access-for-iam-roles/)
* Blog - [How to implement SaaS tenant isolation with ABAC and AWS IAM](https://aws.amazon.com/ko/blogs/security/how-to-implement-saas-tenant-isolation-with-abac-and-aws-iam/)
* Blog - [Use IAM to share your AWS resources with groups of AWS accounts in AWS Organizations](https://aws.amazon.com/ko/blogs/security/iam-share-aws-resources-groups-aws-accounts-aws-organizations/)
* Blog - [IAM makes it easier for you to manage permissions for AWS services accessing your resources](https://aws.amazon.com/ko/blogs/security/iam-makes-it-easier-to-manage-permissions-for-aws-services-accessing-resources/)
* Blog - [How to use trust policies with IAM roles](https://aws.amazon.com/ko/blogs/security/how-to-use-trust-policies-with-iam-roles/)
* Blog - [Automate resolution for IAM Access Analyzer cross-account access findings on IAM roles](https://aws.amazon.com/ko/blogs/security/automate-resolution-for-iam-access-analyzer-cross-account-access-findings-on-iam-roles/)
* Blog - [Use IAM Access Analyzer to generate IAM policies based on access activity found in your organization trail](https://aws.amazon.com/ko/blogs/security/use-iam-access-analyzer-to-generate-iam-policies-based-on-access-activity-found-in-your-organization-trail/)
* Blog - [Managing temporary elevated access to your AWS environment](https://aws.amazon.com/blogs/security/managing-temporary-elevated-access-to-your-aws-environment/)
* Blog - [Journey to Adopt Cloud-Native Architecture Series: #4 – Governing Security at Scale and IAM Baselining](https://aws.amazon.com/ko/blogs/architecture/journey-to-adopt-cloud-native-architecture-series-4-governing-security-at-scale-and-iam-baselining/)
* Blog - [Managing temporary elevated access to your AWS environment](https://aws.amazon.com/ko/blogs/security/managing-temporary-elevated-access-to-your-aws-environment/)
* Blog - [How Setting Up IAM Users and IAM Roles Can Help Keep Your Startup Secure](https://aws.amazon.com/blogs/startups/how-setting-up-iam-users-and-iam-roles-can-help-keep-your-startup-secure/)
* Blog - [How to integrate AWS STS SourceIdentity with your identity provider](https://aws.amazon.com/ko/blogs/security/how-to-integrate-aws-sts-sourceidentity-with-your-identity-provider/)
* Blog - [How to control access to AWS resources based on AWS account, OU, or organization](https://aws.amazon.com/ko/blogs/security/how-to-control-access-to-aws-resources-based-on-aws-account-ou-or-organization/)
* Blog - [How to control access to AWS resources based on AWS account, OU, or organization](https://aws.amazon.com/blogs/security/how-to-control-access-to-aws-resources-based-on-aws-account-ou-or-organization/)
* Blog - [Extend AWS IAM roles to workloads outside of AWS with IAM Roles Anywhere](https://aws.amazon.com/blogs/security/extend-aws-iam-roles-to-workloads-outside-of-aws-with-iam-roles-anywhere/)
* Blog - [Eligible customers can now order a free MFA security key](https://aws.amazon.com/blogs/security/eligible-customers-can-now-order-a-free-mfa-security-key/)
* Blog - [How to centralize findings and automate deletion for unused IAM roles](https://aws.amazon.com/blogs/security/how-to-centralize-findings-and-automate-deletion-for-unused-iam-roles/)
* Blog - [Announcing an update to IAM role trust policy behavior](https://aws.amazon.com/blogs/security/announcing-an-update-to-iam-role-trust-policy-behavior/)


## [AWS Organizations](https://aws.amazon.com/ko/organizations/)

복수개의 AWS 어카운트들을 정책기반으로 관리할 수 있는 기능을 제공합니다. AWS Organization을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Organizations의 보안](https://docs.aws.amazon.com/ko_kr/organizations/latest/userguide/security.html)
* [Security in AWS Account Management](https://docs.aws.amazon.com/ko_kr/accounts/latest/reference/security.html)
* Best Practice - [AWS Multiple Account Security Strategy](https://aws.amazon.com/ko/answers/account-management/aws-multi-account-security-strategy/) _– 멀티 어카운트 환경을 효율적으로 관리하기 위한 모범사례 및 관리 전략_
* Best Practice - [Establishing your best practice AWS environment](https://aws.amazon.com/organizations/getting-started/best-practices/)
* Support - [AWS Organizations의 조직 간에 계정을 이동하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/organizations-move-accounts/)
* Support - [Amazon Web Services 계정은 어떻게 해지합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/close-aws-account/?nc1=h_ls)
* 동영상 [AWS Summit Seoul 2017] - [멀티 어카운트 환경의 보안과 가시성을 높이기 위한 전략](https://www.youtube.com/watch?v=y4qvMJCXDyQ)
* GIT - [access-analyzer at master](https://github.com/aws-samples/aws-iam-permissions-guardrails/tree/master/access-analyzer)
* Blog - [New! Set permission guardrails confidently by using IAM access advisor to analyze service-last-accessed information for accounts in your AWS organization](https://aws.amazon.com/blogs/security/set-permission-guardrails-using-iam-access-advisor-analyze-service-last-accessed-information-aws-organization/)
* Blog - [How to Use Service Control Policies in AWS Organizations](https://aws.amazon.com/blogs/security/how-to-use-service-control-policies-in-aws-organizations/)
* Blog - [An easier way to control access to AWS resources by using the AWS organization of IAM principals](https://aws.amazon.com/ko/blogs/security/control-access-to-aws-resources-by-using-the-aws-organization-of-iam-principals/)
* Blog - [How to use service control policies to set permission guardrails across accounts in your AWS Organization](https://aws.amazon.com/blogs/security/how-to-use-service-control-policies-to-set-permission-guardrails-across-accounts-in-your-aws-organization/) _- SCP에 추가된 Resouce, NotAction, Condition에 대한 설명_
* Blog - [Best Practices for Organizational Units with AWS Organizations](https://aws.amazon.com/blogs/mt/best-practices-for-organizational-units-with-aws-organizations/)
* Blog - [How to use AWS Organizations to simplify security at enormous scale](https://aws.amazon.com/blogs/security/how-to-use-aws-organizations-to-simplify-security-at-enormous-scale/)
* Blog - [Building a Shared Account Structure Using AWS Organizations](https://aws.amazon.com/blogs/architecture/field-notes-building-a-shared-account-structure-using-aws-organizations/)
* Blog - [Best practices for creating and managing sandbox accounts in AWS](https://aws.amazon.com/blogs/mt/best-practices-creating-managing-sandbox-accounts-aws/)
* Blog - [Cost Reporting Based on AWS Organizations Account ID Tags](https://aws.amazon.com/blogs/aws-cost-management/cost-reporting-based-on-aws-organizations-account-id-tags/)
* Blog - [Simplifying permissions management at scale using tags in AWS Organizations](https://aws.amazon.com/blogs/mt/simplifying-permissions-management-at-scale-using-tags-in-aws-organizations/)
* Blog - [Use IAM to share your AWS resources with groups of AWS accounts in AWS Organizations](https://aws.amazon.com/ko/blogs/security/iam-share-aws-resources-groups-aws-accounts-aws-organizations/)
* Blog - [How to perform automated incident response in a multi-account environment](https://aws.amazon.com/ko/blogs/security/how-to-perform-automated-incident-response-multi-account-environment/)
* Blog - [Managing the account lifecycle in account-per-tenant SaaS environments on AWS](https://aws.amazon.com/blogs/mt/managing-the-account-lifecycle-in-account-per-tenant-saas-environments-on-aws/)
* Blog - [Update the alternate security contact across your AWS accounts for timely security notifications](https://aws.amazon.com/ko/blogs/security/update-the-alternate-security-contact-across-your-aws-accounts-for-timely-security-notifications/)
* Blog - [Migrating accounts between AWS Organizations with consolidated billing to all features](https://aws.amazon.com/blogs/mt/migrating-accounts-between-aws-organizations-with-consolidated-billing-to-all-features/)
* Blog - [Field Notes: Building Multi-Region and Multi-Account Tools with AWS Organizations](https://aws.amazon.com/ko/blogs/architecture/field-notes-building-multi-region-and-multi-account-tools-with-aws-organizations/)
* Blog - [Securing resource tags used for authorization using a service control policy in AWS Organizations](https://aws.amazon.com/blogs/security/securing-resource-tags-used-for-authorization-using-service-control-policy-in-aws-organizations/)
* Blog - [Programmatically managing alternate contacts on member accounts with AWS Organizations](https://aws.amazon.com/blogs/mt/programmatically-managing-alternate-contacts-on-member-accounts-with-aws-organizations/)
* Blog - [Implement AWS resource tagging strategy using AWS Tag Policies and Service Control Policies (SCPs)](https://aws.amazon.com/ko/blogs/mt/implement-aws-resource-tagging-strategy-using-aws-tag-policies-and-service-control-policies-scps/)
* Blog - [Identity Guide – Preventive controls with AWS Identity – SCPs](https://aws.amazon.com/ko/blogs/mt/identity-guide-preventive-controls-with-aws-identity-scps/)
* Blog - [AWS Organizations now provides a simple, scalable and more secure way to close your member accounts](https://aws.amazon.com/ko/blogs/mt/aws-organizations-now-provides-a-simple-scalable-and-more-secure-way-to-close-your-member-accounts/)
* Blog - [Get more out of service control policies in a multi-account environment](https://aws.amazon.com/blogs/security/get-more-out-of-service-control-policies-in-a-multi-account-environment/)


## [AWS Resource Access Manager](https://docs.aws.amazon.com/ko_kr/ram/latest/userguide/what-is.html)

멀티 어카운트 환경에서 어카운트 간 리소스 공유관리 기능을 제공합니다. Resource Access Manager를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS RAM의 보안](https://docs.aws.amazon.com/ko_kr/ram/latest/userguide/security.html)
* 동영상 - [youtube - AWS RAM Console Demo](https://www.youtube.com/watch?v=KL9SICG52zY)
* Blog - [VPC sharing: A new approach to multiple accounts and VPC management](https://aws.amazon.com/blogs/networking-and-content-delivery/vpc-sharing-a-new-approach-to-multiple-accounts-and-vpc-management/)
* Blog - [One to Many: Evolving VPC Design](https://aws.amazon.com/blogs/architecture/one-to-many-evolving-vpc-design/)
* Blog - [Control VPC sharing in an AWS multi-account setup with service control policies](https://aws.amazon.com/ko/blogs/security/control-vpc-sharing-in-an-aws-multi-account-setup-with-service-control-policies/)



## [AWS IAM Identity Center(Single Sign-On)](https://aws.amazon.com/ko/iam/identity-center/?nc1=h_ls)

AWS콘솔과 SAML 2.0을 지원하는 비지니스 애플리케이션들에 대한 중앙 관리형 싱글 사인 온(SSO)서비스를 제공합니다(IDP역할). AWS IAM Identity Center을 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Single Sign-On 의 보안](https://docs.aws.amazon.com/ko_kr/singlesignon/latest/userguide/security.html)
* [Welcome to the AWS SSO Identity Store API Reference Guide](https://docs.aws.amazon.com/ko_kr/singlesignon/latest/IdentityStoreAPIReference/welcome.html)
* [Welcome to the AWS SSO OpenID Connect (OIDC) API Reference Guide](https://docs.aws.amazon.com/ko_kr/singlesignon/latest/OIDCAPIReference/Welcome.html)
* [Welcome to the AWS SSO Portal API Reference Guide](https://docs.aws.amazon.com/ko_kr/singlesignon/latest/PortalAPIReference/Welcome.html)
* [Tutorial: Azure AD integration with AWS](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/amazon-web-service-tutorial) _- Microsoft 싸이트, Azure AD와 AWS SSO 간 연계_
* 동영상 [AWS Cloud 2018] - [인공지능 보안 위협 감지 서비스 Amazon GuardDuty를 포함한 AWS 보안 신규 기능 업데이트](https://www.youtube.com/watch?v=ZyOAHiia93Q)
* 동영상 [AWS Unboxing Online Seminar] - [AWS Single Sign-On (SSO) 서비스 집중 탐구](https://www.youtube.com/watch?v=DJlt1v4Gya8)
* 동영상 [AWS] - [Demo of AWS Single Sign-On (SSO) with Azure Active Directory](https://www.youtube.com/watch?v=FbNkDjX5efE)
* Blog - [How to create and manage users within AWS Single Sign-On](https://aws.amazon.com/ko/blogs/security/how-to-create-and-manage-users-within-aws-sso/) _- AWS SSO의 AD그룹/사용자를 Organization에 맵핑/관리하는 방법을 안내_
* Blog - [How to retrieve short-term credentials for CLI use with AWS Single Sign-on](https://aws.amazon.com/ko/blogs/security/aws-single-sign-on-now-enables-command-line-interface-access-for-aws-accounts-using-corporate-credentials/)
* Blog - [AWS Single Sign-On integration with SAP Fiori in S/4HANA](https://aws.amazon.com/blogs/awsforsap/aws-single-sign-on-integration-with-sap-fiori-in-s-4hana/)
* Blog - [Enabling federation with AWS Single Sign-On and Amazon Connect](https://aws.amazon.com/blogs/contact-center/enabling-federation-with-aws-single-sign-on-and-amazon-connect/)
* Blog - [How to enable secure access to Kibana using AWS Single Sign-On](https://aws.amazon.com/blogs/security/how-to-enable-secure-access-to-kibana-using-aws-single-sign-on/)
* Blog - [The Next Evolution in AWS Single Sign-On](https://aws.amazon.com/blogs/aws/the-next-evolution-in-aws-single-sign-on/) _- Azure AD와 AWS SSO 간의 연동_
* Blog - [Enabling AWS Single Sign-On Service (SSO) Integration with Databricks Control Plane](https://aws.amazon.com/blogs/apn/aws-single-sign-on-service-integration-with-databricks-control-plane/)
* Blog - [Single Sign-On between Okta Universal Directory and AWS](https://aws.amazon.com/blogs/aws/single-sign-on-between-okta-universal-directory-and-aws/)
* Blog - [How to use G Suite as an external identity provider for AWS SSO](https://aws.amazon.com/blogs/security/how-to-use-g-suite-as-external-identity-provider-aws-sso/)
* Blog - [On-Demand SCIM provisioning of Azure AD to AWS SSO with PowerShell](https://aws.amazon.com/blogs/security/on-demand-scim-provisioning-of-azure-ad-to-aws-sso-with-powershell/)
* Blog - [Get ready for upcoming changes in the AWS Single Sign-On user sign-in process](https://aws.amazon.com/blogs/security/get-ready-upcoming-changes-aws-single-sign-on-user-sign-in-process/)
* Blog - [Onboarding Amazon SageMaker Studio with AWS SSO and Okta Universal Directory](https://aws.amazon.com/blogs/machine-learning/onboarding-amazon-sagemaker-studio-with-aws-sso-and-okta-universal-directory/)
* EXT. Blog - [AWS IAM Privilege Escalation – Methods and Mitigation](https://rhinosecuritylabs.com/aws/aws-privilege-escalation-methods-mitigation/)
* Blog - [New – Attribute-Based Access Control with AWS Single Sign-On](https://aws.amazon.com/blogs/aws/new-attributes-based-access-control-with-aws-single-sign-on/)
* Blog - [How to bulk import users and groups from CSV into AWS SSO](https://aws.amazon.com/blogs/security/how-to-bulk-import-users-and-groups-from-csv-into-aws-sso/)
* Blog - [How to delegate management of identity in AWS Single Sign-On](https://aws.amazon.com/blogs/security/how-to-delegate-management-of-identity-in-aws-single-sign-on/)
* Blog - [How AWS SSO Active Directory sync enhances AWS application experiences](https://aws.amazon.com/blogs/security/how-aws-sso-active-directory-sync-enhances-aws-application-experiences/)
* Blog - [Federate Amazon Redshift access with Microsoft Azure AD single sign-on](https://aws.amazon.com/blogs/big-data/federate-amazon-redshift-access-with-microsoft-azure-ad-single-sign-on/)
* Blog - [Using AWS SSO with Microsoft Azure AD to federate to AWS GovCloud (US)](https://aws.amazon.com/blogs/publicsector/using-aws-sso-microsoft-azure-ad-federate-aws-govcloud-us/)
* Blog - [Field Notes: Integrating Active Directory Federation Service with AWS Single Sign-On](https://aws.amazon.com/ko/blogs/architecture/field-notes-integrating-active-directory-federation-service-with-aws-single-sign-on/)
* Blog - [Build an end-to-end attribute-based access control strategy with AWS SSO and Okta](https://aws.amazon.com/ko/blogs/security/build-an-end-to-end-attribute-based-access-control-strategy-with-aws-sso-and-okta/)
* Blog - [Federated Access to AWS Single Sign-On with CyberArk Workforce Identity](https://aws.amazon.com/ko/blogs/apn/federated-access-to-aws-single-sign-on-with-cyberark-workforce-identity/)
* Blog - [How to enable secure seamless single sign-on to Amazon EC2 Windows instances with AWS SSO](https://aws.amazon.com/blogs/security/how-to-enable-secure-seamless-single-sign-on-to-amazon-ec2-windows-instances-with-aws-sso/)
* Blog - [Authenticate AWS Client VPN users with AWS Single Sign-On](https://aws.amazon.com/blogs/security/authenticate-aws-client-vpn-users-with-aws-single-sign-on/)
* Blog - [Use new account assignment APIs for AWS SSO to automate multi-account access](https://aws.amazon.com/blogs/security/use-new-account-assignment-apis-for-aws-sso-to-automate-multi-account-access/)
* Blog - [Configure AWS SSO ABAC for EC2 instances and Systems Manager Session Manager](https://aws.amazon.com/ko/blogs/security/configure-aws-sso-abac-for-ec2-instances-and-systems-manager-session-manager/)
* Blog - [Integrating Dropbox with AWS SSO for governed file sharing in an AWS Control Tower environment](https://aws.amazon.com/ko/blogs/awsmarketplace/integrating-dropbox-with-aws-sso-for-governed-file-sharing-in-an-aws-control-tower-environment/)
* Blog - [Field Notes: Integrating Active Directory Federation Service with AWS Single Sign-On](https://aws.amazon.com/ko/blogs/architecture/field-notes-integrating-active-directory-federation-service-with-aws-single-sign-on/)
* Blog - [Securing AWS Accounts with Azure Active Directory Federation](https://aws.amazon.com/ko/blogs/apn/securing-aws-accounts-with-azure-active-directory-federation/)
* Blog - [Getting started with AWS SSO delegated administration](https://aws.amazon.com/blogs/security/getting-started-with-aws-sso-delegated-administration/)
* Blog - [Scale your workforce access management with AWS IAM Identity Center (previously known as AWS SSO)](https://aws.amazon.com/blogs/security/scale-your-workforce-access-management-with-aws-iam-identity-center-previously-known-as-aws-sso/)
* Blog - [How to use customer managed policies in AWS IAM Identity Center for advanced use cases](https://aws.amazon.com/blogs/security/how-to-use-customer-managed-policies-in-aws-single-sign-on-for-advanced-use-cases/)
* Blog - [Manage permission sets and account assignments in AWS IAM Identity Center with a CI/CD pipeline](https://aws.amazon.com/blogs/infrastructure-and-automation/manage-permission-sets-and-account-assignments-in-aws-iam-identity-center-with-a-ci-cd-pipeline/)
* Blog - [Accelerate AWS IAM Identity Center (Successor to AWS Single Sign-On) Implementation using AWS Cloud Development Kit (AWS CDK)](https://aws.amazon.com/blogs/opensource/accelerate-aws-single-sign-on-sso-implementation-using-aws-cloud-development-kit-aws-cdk/)
* Blog - [Integrate AWS IAM Identity Center (successor to AWS Single Sign-On) with AWS Lake Formation fine-grained access controls](https://aws.amazon.com/blogs/big-data/integrate-aws-iam-identity-center-successor-to-aws-single-sign-on-with-aws-lake-formation-fine-grained-access-controls/)
* Blog - [Announcing new AWS IAM Identity Center APIs to manage users and groups at scale](https://aws.amazon.com/blogs/security/announcing-new-aws-iam-identity-center-apis-to-manage-users-and-groups-at-scale/)


## [AWS Control Tower](https://aws.amazon.com/ko/controltower/)

엔터프라이즈 고객들을 위해, AWS의 멀티 어카운트를 위한 각종 모범사례를 기반으로, 안전하고 Well-architected된 멀티 어카운트 환경을 자동으로 구성해 주는 서비스입니다. AWS Organization, Single Sign-On, Config, Service Catalog 등 멀티어카운트 환경을 효율적이고 확장성 있게 관리하는 데 필요한 각종 서비스들이 자동으로 구성됩니다. AWS Control Tower를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Control Tower 의 보안](https://docs.aws.amazon.com/ko_kr/controltower/latest/userguide/security.html)
* 동영상 - [Provisioning Users in AWS Control Tower Using AWS SSO](https://www.youtube.com/watch?v=y_n9xN5mg1g&list=PLhr1KZpdzukcaA06WloeNmGlnM_f1LrdP&index=27)
* 동영상 - [AWS Control Tower를 통한 클라우드 보안 및 거버넌스 설계](https://www.youtube.com/watch?v=LMBSWl9Uo-4)
* 사례 - [AWS 고객사례 라인게임즈](https://aws.amazon.com/ko/solutions/case-studies/line-games/)
* GIT - [Centralize SecurityHub](https://github.com/aws-samples/aws-control-tower-securityhub-enabler) _- 전체 어카운트에 Security Hub 활성화_
* QucikStart - [Customizations for AWS Control Tower](https://aws.amazon.com/ko/solutions/implementations/customizations-for-aws-control-tower/)
* QuickStart - [Cloud One Conformity AWS Control Tower integration](https://aws.amazon.com/quickstart/architecture/trend-micro-cloud-one-conformity/)
* Blog - [Enabling self-service provisioning of AWS resources with AWS Control Tower](https://aws.amazon.com/blogs/mt/enabling-self-service-provisioning-of-aws-resources-with-aws-control-tower/)
* Blog - [How to Detect and Mitigate Guardrail Violation with AWS Control Tower](https://aws.amazon.com/blogs/mt/how-to-detect-and-mitigate-guardrail-violation-with-aws-control-tower/)
* Blog - [AWS Control Tower Detective Guardrails as an AWS Config Conformance Pack](https://aws.amazon.com/blogs/mt/aws-control-tower-detective-guardrails-as-an-aws-config-conformance-pack/)
* Blog - [Enroll existing AWS accounts into AWS Control Tower](https://aws.amazon.com/blogs/architecture/field-notes-enroll-existing-aws-accounts-into-aws-control-tower/)
* Blog - [Monitoring resources in an AWS Control Tower environment using Splunk from AWS Marketplace](https://aws.amazon.com/blogs/awsmarketplace/monitoring-resources-in-an-aws-control-tower-environment-using-splunk-from-aws-marketplace/)
* Blog - [VPC Flow Log automation using AWS Control Tower LifeCycle](https://aws.amazon.com/blogs/mt/vpc-flow-log-with-aws-control-tower-lifecycle/)
* Blog - [How to get read-only visibility into the AWS Control Tower console](https://aws.amazon.com/blogs/security/how-to-get-read-only-visibility-into-aws-control-tower-console/)
* Blog - [Enabling guardrails in new AWS Regions the AWS Control Tower supports](https://aws.amazon.com/blogs/field-notes/enabling-guardrails-in-new-aws-regions-the-aws-control-tower-supports/)
* Blog - [Extend a self-managed Active Directory to AWS Control Tower](https://aws.amazon.com/blogs/mt/extend-a-self-managed-active-directory-to-aws-control-tower/)
* Blog - [Self-service VPCs in AWS Control Tower using AWS Service Catalog](https://aws.amazon.com/blogs/mt/self-service-vpcs-in-aws-control-tower-using-aws-service-catalog/)
* Blog - [How managed service providers can use AWS Control Tower to provide services](https://aws.amazon.com/blogs/mt/how-managed-service-providers-can-use-aws-control-tower-to-provide-services/)
* Blog - [Enabling Amazon GuardDuty in AWS Control Tower using Delegated Administrator](https://aws.amazon.com/blogs/mt/automating-amazon-guardduty-deployment-in-aws-control-tower/)
* Blog - [Managing the multi-account environment using AWS Organizations and AWS Control Tower](https://aws.amazon.com/blogs/mt/managing-the-multi-account-environment-using-aws-organizations-and-aws-control-tower/)
* Blog - [Securely scale multi-account architecture with AWS Network Firewall and AWS Control Tower](https://aws.amazon.com/blogs/mt/scale-multi-account-architecture-aws-network-firewall-and-aws-control-tower/)
* Blog - [Extend AWS Control Tower governance using AWS Config Conformance Packs](https://aws.amazon.com/blogs/mt/extend-aws-control-tower-governance-using-aws-config-conformance-packs/)
* Blog - [How to automate the creation of multiple accounts in AWS Control Tower](https://aws.amazon.com/ko/blogs/mt/how-to-automate-the-creation-of-multiple-accounts-in-aws-control-tower/)
* Blog - [Enabling AWS IAM Access Analyzer on AWS Control Tower accounts](https://aws.amazon.com/blogs/mt/enabling-aws-identity-and-access-analyzer-on-aws-control-tower-accounts/)
* Blog - [Enroll Existing AWS Accounts into AWS Control Tower](https://aws.amazon.com/ko/blogs/architecture/field-notes-enroll-existing-aws-accounts-into-aws-control-tower/)
* Blog - [Migrating custom Landing Zone with RAM to AWS Control Tower](https://aws.amazon.com/ko/blogs/mt/migrating-custom-landing-zone-with-ram-to-aws-control-tower/)
* Blog - [Use AWS Control Tower to deploy AWS Quick Starts to multiple accounts](https://aws.amazon.com/blogs/infrastructure-and-automation/deploy-aws-quick-start-to-multiple-accounts-using-aws-control-tower/)
* Blog - [New for AWS Control Tower – Region Deny and Guardrails to Help You Meet Data Residency Requirements](https://aws.amazon.com/ko/blogs/aws/new-for-aws-control-tower-region-deny-and-guardrails-to-help-you-meet-data-residency-requirements/)
* Blog - [Field Notes: Clear Unused AWS SSO Mappings Automatically During AWS Control Tower Upgrades](https://aws.amazon.com/blogs/architecture/field-notes-clear-unused-aws-sso-mappings-automatically-during-aws-control-tower-upgrades/)
* Blog - [Field Notes: Perform Automations in Ungoverned Regions During Account Launch Using AWS Control Tower Lifecycle Events](https://aws.amazon.com/ko/blogs/architecture/field-notes-perform-automations-in-ungoverned-regions-during-account-launch-using-aws-control-tower-lifecycle-events/)
* Blog - [Automate multi account data access in AWS using Couchbase and AWS Control Tower](https://aws.amazon.com/ko/blogs/awsmarketplace/automate-multi-account-data-access-in-aws-using-couchbase-and-aws-control-tower/)
* Blog - [Automate multi account identity governance in AWS using Ermetic and AWS Control Tower](https://aws.amazon.com/blogs/awsmarketplace/automate-multi-account-identity-governance-in-aws-using-ermetic-and-aws-control-tower/)
* Blog - [Migrate AWS Landing Zone solution to AWS Control Tower](https://aws.amazon.com/blogs/mt/migrate-aws-landing-zone-solution-to-aws-control-tower/)
* Blog - [AWS Control Tower Best Practices for AWS Solution Providers](https://aws.amazon.com/ko/blogs/apn/aws-control-tower-best-practices-for-aws-solution-providers/)
* Blog - [Supporting Data Residency Requirements by Extending AWS Control Tower Governance to Non-supported Regions](https://aws.amazon.com/blogs/mt/supporting-data-residency-requirements-by-extending-aws-control-tower-governance-to-non-supported-regions/)
* Blog - [Unified multi-account security and compliance with Sysdig Secure and AWS Control Tower](https://aws.amazon.com/ko/blogs/awsmarketplace/unified-multi-account-security-compliance-sysdig-secure-aws-control-tower/)
* Blog - [Managing AWS account lifecycle in AWS Control Tower using the Account Close API](https://aws.amazon.com/ko/blogs/mt/managing-aws-account-lifecycle-in-aws-control-tower-using-the-account-close-api/)
* Blog - [Delegate account factory creation to parts of your organization with AWS Control Tower](https://aws.amazon.com/blogs/mt/delegate-account-factory-creation-to-parts-of-your-organization-with-aws-control-tower/)
* Blog - [IP Address Management for AWS Control Tower](https://aws.amazon.com/blogs/networking-and-content-delivery/ip-address-management-for-aws-control-tower/)
* Blop - [AWS Cloud WAN and Amazon VPC IPAM with AWS Control Tower](https://aws.amazon.com/blogs/networking-and-content-delivery/aws-cloudwan-and-amazon-ipam-with-aws-control-tower-customizations/)
* Blog - [Customize AWS Config resource tracking in AWS Control Tower environment](https://aws.amazon.com/blogs/mt/customize-aws-config-resource-tracking-in-aws-control-tower-environment/)


## [Amazon Cognito](https://aws.amazon.com/ko/cognito/)

고객의 웹 및 모바일 애플리케이션 환경을 위한 사용자 등록, 인증, 접근제어 기능을 제공합니다. Amazon Cognito를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [Amazon Cognito의 보안](https://docs.aws.amazon.com/ko_kr/cognito/latest/developerguide/security.html)
* API - [SetUICustomization](https://docs.aws.amazon.com/ko_kr/cognito-user-identity-pools/latest/APIReference/API_SetUICustomization.html) _- Cognito User Pool을 이용하는 빌트인 App의 인증 화면에 대한   Logo, CSS 커스터마이징 API_
* [Authenticate Users Using an Application Load Balancer](https://docs-aws.amazon.com/ko_kr/elasticloadbalancing/latest/application/listener-authenticate-users.html) _- ALB에서 OIDC나 Cognito User Pool을 이용하여 모든 요청자에 대해 인증하는 방법 안내_
* 동영상 [AWS Summit Seoul 2018] - [Serverless 개발에서의 인증 완벽 가이드](https://youtu.be/E9iIZ65cRug)
* GIT - [aws-cognito-apigw-angular-auth](https://github.com/aws-samples/aws-cognito-apigw-angular-auth)
* GIT - [AWS Lambda SAP OAuth Token Generator](https://github.com/aws-samples/aws-lambda-sap-oauth)
* GIT - [Amazon Cognito sample application for Node.js](https://github.com/aws-samples/cognito-sample-nodejs)
* GIT - [Amazon Cognito Sync Manager for JavaScript](https://github.com/aws/amazon-cognito-js)
* GIT - [Identity and Access Control for Custom Enterprise Applications](https://github.com/aws-samples/amazon-cognito-example-for-external-idp) _- CUP와 OpenID, SAML, Social IDP 간의 연계 샘플_
* GIT - [JWT 토큰을 이용한 빌트인 로그인과 애플리케이션간의 연동 과정에 대한 데모](https://github.com/arronharden/cognito-demo-ui)
* GIT - [Okta : Integrating IdP Sign In with Cognito](https://github.com/aws-samples/amazon-cognito-example-for-external-idp/blob/master/docs/OktaInstructions.md)
* GIT - [Angular Lib for OpenID Connect & OAuth2](https://github.com/damienbod/angular-auth-oidc-client)
* GIT - [cognito-learning: Learning how Cognito implements the OAuth flows](https://github.com/waymousa/cognito-learning)
* QucikStart - [Cognito User Profiles Export Reference Architecture](https://aws.amazon.com/ko/solutions/implementations/cognito-user-profiles-export-reference-architecture/)
* Support - [Okta를 Amazon Cognito 사용자 풀의 SAML 자격 증명 공급자로 설정하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/cognito-okta-saml-identity-provider/)
* Support - [Auth0을 Amazon Cognito 사용자 풀의 SAML 자격 증명 공급자로 설정하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/auth0-saml-cognito-user-pool/)
* Support - [Amazon Cognito 사용자 풀에서 SAML 자격 증명 공급자로서 AD FS를 설정하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/cognito-ad-fs-saml/)
* Support - [OneLogin을 Amazon Cognito 사용자 풀의 SAML 자격 증명 공급자로 설정하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/cognito-saml-onelogin/)
* Support - [How can I decode and verify the signature of an Amazon Cognito JSON Web Token?](https://aws.amazon.com/premiumsupport/knowledge-center/decode-verify-cognito-json-token/)
* Support - [How do I enable TOTP as a multi-factor authentication for Amazon Cognito user pools?](https://aws.amazon.com/premiumsupport/knowledge-center/cognito-user-pool-totp-mfa/)
* Support - [Remember devices in an Amazon Cognito user pool](https://aws.amazon.com/premiumsupport/knowledge-center/cognito-user-pool-remembered-devices/)
* QuickStart - [Amazon Cognito를 사용한 SaaS 자격 증명 및 격리](https://aws.amazon.com/ko/quickstart/saas/identity-with-cognito/)
* Solution - [Multi-Region User Pools](https://aws.amazon.com/solutions/multi-region-user-pools/?did=sl_card&trk=sl_card) _- 멀티 리전상에서 Cognito를 구성하는 CFN 템플릿_
* Solution - [Cognito User Profiles Export Reference Architecture](https://docs.aws.amazon.com/ko_kr/solutions/latest/cognito-user-profiles-export-reference-architecture/architecture-overview.html)
* 가이드 - [Access AWS services from an ASP.NET Core app using Amazon Cognito identity pools](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/securityandcompliance-pattern-list.html)
* Blog - [How to Set Up Player Authentication with Amazon Cognito](https://aws.amazon.com/blogs/gametech/how-to-set-up-player-authentication-with-amazon-cognito/)
* Blog - [Implementing passwordless email authentication with Amazon Cognito](https://aws.amazon.com/blogs/mobile/implementing-passwordless-email-authentication-with-amazon-cognito/)
* Blog - [Understanding Amazon Cognito user pool OAuth 2.0 grants](https://aws.amazon.com/blogs/mobile/understanding-amazon-cognito-user-pool-oauth-2-0-grants/)
* Blog - [Building ADFS Federation for your Web App using Amazon Cognito User Pools](https://aws.amazon.com/blogs/mobile/building-adfs-federation-for-your-web-app-using-amazon-cognito-user-pools/)
* Blog - [Serverless File Upload with AWS Cognito and S3](https://blog.hipolabs.com/serverless-file-upload-with-aws-cognito-and-s3-da17115d73e8)
* Blog - [AWS Cognito User Pool Access Token Invalidation](https://dzone.com/articles/aws-cognito-user-pool-access-token-invalidation-1)
* Blog - [Secure API Access with Amazon Cognito Federated Identities, Amazon Cognito User Pools, and Amazon API Gateway](https://aws.amazon.com/blogs/compute/secure-api-access-with-amazon-cognito-federated-identities-amazon-cognito-user-pools-and-amazon-api-gateway/)
* Blog - [Now generally available: Amazon Cognito Authentication Extension Library](https://aws.amazon.com/blogs/developer/now-generally-available-amazon-cognitoauthentication-extension-library/)
* Blog - [Migrating Users to Amazon Cognito User Pools](https://aws.amazon.com/blogs/mobile/migrating-users-to-amazon-cognito-user-pools/)
* Blog - [Simplify Login with Application Load Balancer Built-in Authentication](https://aws.amazon.com/blogs/aws/built-in-authentication-in-alb/) _- ALB 사용자 인증 기능에 대한 데모 싸이트 및 기능 구성을 설명_
* Blog - [Use Amazon QuickSight Federated Single Sign-On with Amazon Cognito User Pools](https://aws.amazon.com/blogs/big-data/use-amazon-quicksight-federated-single-sign-on-with-amazon-cognito-user-pools/) _- API G/W, Lambda를 이용하여 Cognito User Pool과 QuickSight간 SAML2.0 기반 SSO연동을 설명하는 블로그_
* Blog - [Role-based access control using Amazon Cognito and an external identity provider](https://aws.amazon.com/ko/blogs/security/role-based-access-control-using-amazon-cognito-and-an-external-identity-provider/)
* Blog - [How to configure Duo multi-factor authentication with Amazon Cognito](https://aws.amazon.com/blogs/security/how-to-configure-duo-multi-factor-authentication-with-amazon-cognito/)
* Ext. Blog - [Setup AWS Cognito User Pool with an Azure AD identity provider to perform single sign-on (SSO) authentication in mobile app (Part 1)](https://medium.com/@zippicoder/setup-aws-cognito-user-pool-with-an-azure-ad-identity-provider-to-perform-single-sign-on-sso-7ff5aa36fc2a)
* Ext. Blog - [Cognito Wiki](https://www.cognito.wiki/)
* Blog - [How to implement password-less authentication with Amazon Cognito and WebAuthn](https://aws.amazon.com/blogs/security/how-to-implement-password-less-authentication-with-amazon-cognito-and-webauthn/)
* Blog - [How to add authentication to a single-page web application with Amazon Cognito OAuth2 implementation](https://aws.amazon.com/blogs/security/how-to-add-authentication-single-page-web-application-with-amazon-cognito-oauth2-implementation/)
* Blog - [Managing SaaS Identity Through Custom Attributes and Amazon Cognito](https://aws.amazon.com/ko/blogs/apn/managing-saas-identity-through-custom-attributes-and-amazon-cognito/)
* [이제 Amazon Cognito에서 Amazon SNS에서 SMS Sandbox를 지원합니다](https://aws.amazon.com/ko/about-aws/whats-new/2021/06/amazon-cognito-now-supports-sms-sandbox-from-amazon-sns/)
* Blog - [Building fine-grained authorization using Amazon Cognito, API Gateway, and IAM](https://aws.amazon.com/es/blogs/security/building-fine-grained-authorization-using-amazon-cognito-api-gateway-and-iam/)
* Blog - [How to Use Cognito Pre-Token Generation trigger to Customize Claims In ID Tokens](https://aws.amazon.com/blogs/mobile/how-to-use-cognito-pre-token-generators-to-customize-claims-in-id-tokens/)
* Blog - [Implementing passwordless email authentication with Amazon Cognito](https://aws.amazon.com/blogs/mobile/implementing-passwordless-email-authentication-with-amazon-cognito/)
* Blog - [Protect public clients for Amazon Cognito by using an Amazon CloudFront proxy](https://aws.amazon.com/blogs/security/protect-public-clients-for-amazon-cognito-by-using-an-amazon-cloudfront-proxy/)
* Blog - [How to set case sensitivity in the Amazon Cognito console](https://aws.amazon.com/blogs/security/how-to-set-case-sensitivity-in-the-amazon-cognito-console/)
* Blog - [Implement OAuth 2.0 device grant flow by using Amazon Cognito and AWS Lambda](https://aws.amazon.com/blogs/security/implement-oauth-2-0-device-grant-flow-by-using-amazon-cognito-and-aws-lambda/)
* Blog - [How to set up Amazon Cognito for federated authentication using Azure AD](https://aws.amazon.com/blogs/security/how-to-set-up-amazon-cognito-for-federated-authentication-using-azure-ad/)
* Blog - [Extending Amazon Cognito with Email OTP for 2FA using Amazon SES](https://aws.amazon.com/ko/blogs/mobile/extending-amazon-cognito-with-email-otp-for-2fa-using-amazon-ses/)
* Blog - [How to set up Amazon Cognito for federated authentication using Azure AD](https://aws.amazon.com/ko/blogs/security/how-to-set-up-amazon-cognito-for-federated-authentication-using-azure-ad/)
* Blog - [Implement OAuth 2.0 device grant flow by using Amazon Cognito and AWS Lambda](https://aws.amazon.com/ko/blogs/security/implement-oauth-2-0-device-grant-flow-by-using-amazon-cognito-and-aws-lambda/)
* Blob - [Tracking and Remembering Devices Using Amazon Cognito Your User Pools](https://aws.amazon.com/ko/blogs/mobile/tracking-and-remembering-devices-using-amazon-cognito-your-user-pools/)
* Blog - [Understanding Amazon Cognito user pool OAuth 2.0 grants](https://aws.amazon.com/ko/blogs/mobile/understanding-amazon-cognito-user-pool-oauth-2-0-grants/)
* Blog - [Enriching Amazon Cognito features with an Amazon API Gateway proxy](https://aws.amazon.com/ko/blogs/architecture/enriching-amazon-cognito-features-with-an-amazon-api-gateway-proxy/)
* Blog - [Amazon Cognito launches support for in-Region integration with Amazon SES and Amazon SNS](https://aws.amazon.com/ko/blogs/security/amazon-cognito-launches-support-for-in-region-integration-with-amazon-ses-and-amazon-sns/)
* Blog - [Use Amazon Cognito to add claims to an identity token for fine-grained authorization](https://aws.amazon.com/blogs/security/use-amazon-cognito-to-add-claims-to-an-identity-token-for-fine-grained-authorization/)
* Blog - [Web application access control patterns using AWS services](https://aws.amazon.com/blogs/architecture/web-application-access-control-patterns-using-aws-services/)

## [AWS Directory Service](https://aws.amazon.com/ko/directoryservice/)

AWS가 제공하는 관리형 MS Active Directory 환경을 제공합니다. AWS Directory Service를 이용하는데 참고할 만한 유용한 내용들은 아래와 같습니다.

**Bookmark**

* [AWS Directory Service의 보안](https://docs.aws.amazon.com/ko_kr/directoryservice/latest/admin-guide/security.html)
* [Join an EC2 instance to your AWS Managed Microsoft AD directory](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/ms_ad_join_instance.html)
* MS AD - [AWS Managed Microsoft AD](https://docs.aws.amazon.com/ko_kr/directoryservice/latest/admin-guide/directory_microsoft_ad.html)
* AD Connector - [Active Directory Connector](https://docs.aws.amazon.com/ko_kr/directoryservice/latest/admin-guide/directory_ad_connector.html)
* Simple AD - [Simple Active Directory](https://docs.aws.amazon.com/ko_kr/directoryservice/latest/admin-guide/directory_simple_ad.html)
* Cloud Directory - [Logging AWS Directory Service API Calls Using CloudTrail](https://docs.aws.amazon.com/ko_kr/directoryservice/latest/devguide/cloudtrail_logging.html)
* 백서 - [Active Directory Domain Services on AWS - Design and planning guide](https://d1.awsstatic.com/whitepapers/adds-on-aws.pdf?did=wp_card&trk=wp_card)
* Forum - [Run Your Microsoft SharePoint and SQL Server Always On Availability Groups in the AWS Cloud More Easily by Using AWS Directory Service for Microsoft Active Directory ](https://forums.aws.amazon.com/ann.jspa?annID=4636)
* GIT - [AmazonCloudDirectory Sample](https://github.com/aws-samples/amazon-cloud-directory-sample)
* GIT - [aws-azure-login](https://github.com/sportradar/aws-azure-login)
* QuickStart - [Duo MFA(on Radius Proxy) with AWS Directory Service](https://aws.amazon.com/quickstart/architecture/duo-mfa/) _- Duo MFA 제품을 써서 AWS DS에 MFA를 쉽게 구성할 수 있게 해주는 퀵스타트_
* 가이드 - [Authenticate Microsoft SQL Server on Amazon EC2 using AWS Directory Service](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/authenticate-microsoft-sql-server-on-amazon-ec2-using-aws-directory-service.html)
* Support - [AD FS를 사용하여 Active Directory 사용자에게 API 또는 AWS CLI에 대한 액세스 권한을 부여하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/adfs-grant-ad-access-api-cli/)
* Blog - [How to Set Up SSO to the AWS Management Console for Multiple Accounts by Using AD FS and SAML 2.0](https://aws.amazon.com/ko/blogs/security/how-to-set-up-sso-to-the-aws-management-console-for-multiple-accounts-by-using-ad-fs-and-saml-2-0/)
* Blog - [How to seamlessly domain join Amazon EC2 instances to a single AWS Managed Microsoft AD Directory from multiple accounts and VPCs](https://aws.amazon.com/pt/blogs/security/how-to-domain-join-amazon-ec2-instances-aws-managed-microsoft-ad-directory-multiple-accounts-vpcs/)
* Blog - [How to Enable LDAPS for Your AWS Microsoft AD Directory](https://aws.amazon.com/ko/blogs/security/how-to-enable-ldaps-for-your-aws-microsoft-ad-directory/)
* Blog - [How AWS Managed Microsoft AD Helps to Simplify the Deployment and Improve the Security of Active Directory–Integrated .NET Applications](https://aws.amazon.com/blogs/security/how-aws-managed-microsoft-ad-helps-to-simplify-the-deployment-and-improve-the-security-of-active-directory-integrated-net-applications/)
* Blog - [How to prompt users to reset their AWS Managed Microsoft AD passwords proactively](https://aws.amazon.com/blogs/security/how-to-prompt-users-to-reset-their-aws-managed-microsoft-ad-passwords-proactively/)
* Blog - [How to Enable the Use of Remote Desktops by Deploying Microsoft Remote Desktop Licensing Manager on AWS Microsoft AD](https://aws.amazon.com/blogs/security/how-to-enable-the-use-of-remote-desktops-by-deploying-microsoft-remote-desktop-licensing-manager-on-aws-microsoft-ad/)
* Blog - [How to Migrate Your Microsoft Active Directory Users to Simple AD or AWS Managed Microsoft AD](https://aws.amazon.com/blogs/security/how-to-migrate-your-microsoft-active-directory-users-to-simple-ad/)
* Blog - [How to migrate your on-premises domain to AWS Managed Microsoft AD using ADMT](https://aws.amazon.com/blogs/security/how-to-migrate-your-on-premises-domain-to-aws-managed-microsoft-ad-using-admt/)
* Blog - [How to Access the AWS Management Console Using AWS Microsoft AD and Your On-Premises Credentials](https://aws.amazon.com/blogs/security/how-to-access-the-aws-management-console-using-aws-microsoft-ad-and-your-on-premises-credentials/)
* Blog - [Use attribute-based access control with AD FS to simplify IAM permissions management](https://aws.amazon.com/blogs/security/attribute-based-access-control-ad-fs-simplify-iam-permissions-management/)
* Blog - [How to rapidly develop applications on Amazon Cloud Directory with Managed Schema](https://aws.amazon.com/blogs/database/rapidly-develop-applications-on-amazon-cloud-directory-with-managed-schema/)
* Blog - [How to Search More Efficiently in Amazon Cloud Directory](https://aws.amazon.com/blogs/security/how-to-search-more-efficiently-in-amazon-cloud-directory/)
* Blog - [New Cloud Directory API Makes It Easier to Query Data Along Multiple Dimensions](https://aws.amazon.com/blogs/security/new-cloud-directory-api-makes-it-easier-to-query-data-along-multiple-dimensions/)
* Blog - [How to Create an Organizational Chart with Separate Hierarchies by Using Amazon Cloud Directory](https://aws.amazon.com/blogs/security/how-to-create-an-organizational-chart-with-separate-hierarchies-by-using-amazon-cloud-directory/)
* Blog - [How to improve LDAP security in AWS Directory Service with client-side LDAPS](https://aws.amazon.com/blogs/security/how-to-improve-ldap-security-in-aws-directory-service-with-client-side-ldaps/)
* Blog - [Seamlessly Join a Linux Instance to AWS Directory Service for Microsoft Active Directory](https://aws.amazon.com/blogs/aws/seamlessly-join-a-linux-instance-to-aws-directory-service-for-microsoft-active-directory/)
* Blog - [How to configure an LDAPS endpoint for Simple AD](https://aws.amazon.com/blogs/security/how-to-configure-ldaps-endpoint-for-simple-ad/)
* Blog - [How to Configure Even Stronger Password Policies to Help Meet Your Security Standards by Using AWS Directory Service for Microsoft Active Directory](https://aws.amazon.com/it/blogs/security/how-to-configure-even-stronger-password-policies-to-help-meet-your-security-standards-by-using-aws-directory-service-for-microsoft-active-directory/)
* Blog - [Enable Office 365 with AWS Managed Microsoft AD without user password synchronization](https://aws.amazon.com/blogs/security/enable-office-365-with-aws-managed-microsoft-ad-without-user-password-synchronization/)
* Blog - [Multi-Region Replication Now Enabled for AWS Managed Microsoft Active Directory](https://aws.amazon.com/blogs/aws/multi-region-replication-now-enabled-for-aws-managed-microsoft-active-directory/)
* Blog - [How to Enable Your Users to Access Office 365 with AWS Managed Microsoft AD](https://aws.amazon.com/ko/blogs/security/how-to-enable-your-users-to-access-office-365-with-aws-microsoft-active-directory-credentials/)
* Blog - [Manage your AWS Directory Service credentials using AWS Secrets Manager](https://aws.amazon.com/blogs/security/manage-your-aws-directory-service-credentials-using-aws-secrets-manager/)
* Blog - [Everything you wanted to know about trusts with AWS Managed Microsoft AD](https://aws.amazon.com/blogs/security/everything-you-wanted-to-know-about-trusts-with-aws-managed-microsoft-ad/)
* Blog - [Securely extend and access on-premises Active Directory domain controllers in AWS](https://aws.amazon.com/blogs/security/securely-extend-and-access-on-premises-active-directory-domain-controllers-in-aws/)
* Blog - [Integrate Okta to Extend Active Directory Infrastructure into AWS](https://aws.amazon.com/ko/blogs/architecture/integrate-okta-to-extend-active-directory-infrastructure-into-aws/)
* Blog - [Build a strong identity foundation that uses your existing on-premises Active Directory](https://aws.amazon.com/blogs/security/build-a-strong-identity-foundation-that-uses-your-existing-on-premises-active-directory/)

 
## 사용자 관리와 관련된 기타 유용한 링크들

* [AWS 보안 자격 증명](https://docs.aws.amazon.com/ko_kr/general/latest/gr/aws-security-credentials.html)
* [AWS 계정 루트 사용자 자격 증명과 IAM 사용자 자격 증명의 비교](https://docs.aws.amazon.com/ko_kr/general/latest/gr/root-vs-iam.html)
* [AWS 계정 루트 사용자 자격 증명이 필요한 AWS 작업](https://docs.aws.amazon.com/ko_kr/general/latest/gr/aws_tasks-that-require-root.html)
* [보안 자격 증명 이해 및 가져오기](https://docs.aws.amazon.com/ko_kr/general/latest/gr/aws-sec-cred-types.html)
* [AWS 계정 식별자](https://docs.aws.amazon.com/ko_kr/general/latest/gr/acct-identifiers.html)
* [AWS 액세스 키 관리를 위한 모범 사례](https://docs.aws.amazon.com/ko_kr/general/latest/gr/aws-access-keys-best-practices.html)
* [AWS 계정 루트 사용자 사용자의 액세스 키 관리](https://docs.aws.amazon.com/ko_kr/general/latest/gr/managing-aws-access-keys.html)
* Best Practice - [AWS Secure Initial Account Setup](https://aws.amazon.com/ko/answers/security/aws-secure-account-setup/) _– AWS 어카운트를 최초 생성했을때 체크하거나 고려해야 될 여러가지 보안 설정, 기능들에 대한 소개_
* [AWS 리전 관리](https://docs.aws.amazon.com/ko_kr/general/latest/gr/rande-manage.html)
* Support - [내 계정을 다른 사람 또는 기업에 양도하려면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/transfer-aws-account/?nc1=h_ls)
* Support - [AWS 계정에서 무단 활동이 발견되면 어떻게 해야 합니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/potential-account-compromise/)
* [Real-Time Insights on AWS Account Activity](https://docs.aws.amazon.com/ko_kr/solutions/latest/real-time-insights-account-activity/welcome.html) _– CloudTrail상의 콘솔 로그인 이벤트들을 바탕으로 각종 통계치와 비정상적인 이벤트들을 추출하여 대쉬보드로 보여주는 템플릿_
* [AWS Best Practice: Azure AD SAML Authentication Configuration for AWS Console](https://blog.flux7.com/aws-best-practice-azure-ad-saml-authentication-configuration-for-aws-console) _- 외부 싸이트, Azure AD와 AWS 콘솔간 SAML 기반 인증 연계 방법_
* [AWS Landing Zone](https://aws.amazon.com/ko/answers/aws-landing-zone/) _- AWS가 권장하는 모범사례 기반으로 안전한 멀티 어카운트 환경을 구성하기 위한 솔루션을 소개_
* GIT - [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) _- CIS Benchmark 1.2 기준이 적용된 AWS account 환경을 만들어 주는 테라폼_
* GIT - [AWS Secure Environment Accelerator](https://github.com/aws-samples/aws-secure-environment-accelerator#aws-secure-environment-accelerator)
* [Centrify  : Adding and configuring a Custom SAML application](https://docs.centrify.com/Content/Applications/AppsCustom/AddConfigSAML.htm) _- 외부 문서_
* [G-Suite : Set up your own custom SAML application](https://support.google.com/a/answer/6087519?hl=en) _- 외부 문서_
* [PING Identity : Add or update a SAML application](https://documentation.pingidentity.com/pingone/employeeSsoAdminGuide/index.shtml#enableAppWithoutURL.html) _- 외부 문서_
* Blog - [How to automate SAML federation to multiple AWS accounts from Microsoft Azure Active Directory](https://aws.amazon.com/blogs/security/how-to-automate-saml-federation-to-multiple-aws-accounts-from-microsoft-azure-active-directory/)
* Blog - [Zero Trust architectures: An AWS perspective](https://aws.amazon.com/blogs/security/zero-trust-architectures-an-aws-perspective/)
* Blog - [Approaches for authenticating external applications in a machine-to-machine scenario](https://aws.amazon.com/blogs/security/approaches-for-authenticating-external-applications-in-a-machine-to-machine-scenario/)
* Blog - [Essential security for everyone: Building a secure AWS foundation](https://aws.amazon.com/blogs/security/essential-security-for-everyone-building-a-secure-aws-foundation/)
* Blog - [Automatically tag new AWS resources based on identity or role](https://aws.amazon.com/blogs/mt/auto-tag-aws-resources/)
* Blog - [How to think about Zero Trust architectures on AWS](https://aws.amazon.com/ko/blogs/publicsector/how-to-think-about-zero-trust-architectures-on-aws/)
* Blog - [Defining an AWS Multi-Account Strategy for a Digital Bank](https://aws.amazon.com/blogs/industries/defining-an-aws-multi-account-strategy-for-a-digital-bank/)
* Blog - [Enhance programmatic access for IAM users using a YubiKey for multi-factor authentication](https://aws.amazon.com/blogs/security/enhance-programmatic-access-for-iam-users-using-yubikey-for-multi-factor-authentication/)
* Blog - [Top 10 security items to improve in your AWS account](https://aws.amazon.com/ko/blogs/security/top-10-security-items-to-improve-in-your-aws-account/)
* Blog - [Essential security for everyone: Building a secure AWS foundation](https://aws.amazon.com/ko/blogs/security/essential-security-for-everyone-building-a-secure-aws-foundation/)
* Blog - [How UnitedHealth Group Improved Disaster Recovery for Machine-to-Machine Authentication](https://aws.amazon.com/blogs/architecture/how-unitedhealth-group-improved-disaster-recovery-for-machine-to-machine-authentication/)
* Blog - [Establishing a data perimeter on AWS](https://aws.amazon.com/blogs/security/establishing-a-data-perimeter-on-aws/)


## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.



---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>x