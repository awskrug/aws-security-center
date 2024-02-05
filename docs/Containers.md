# Containers

## [ECR](https://aws.amazon.com/ko/ecr/?nc2=h_m1)

Amazon Elastic Container Registry(ECR)는 개발자가 Docker 컨테이너 이미지를 손쉽게 저장, 관리 및 배포할 수 있게 해주는 완전관리형 Docker 컨테이너 레지스트리입니다. ECR의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon Elastic Container Registry의 보안](https://docs.aws.amazon.com/ko_kr/AmazonECR/latest/userguide/security.html)
* GIT - [Clair : static analysis tool for container](https://github.com/quay/clair)
* GIT - [Anchore](https://anchore.com/opensource/) _- 이미지에 대한 취약점 스캐닝 및 SW BOM 생성_
* GIT - [truffleHog](https://github.com/trufflesecurity/truffleHog) _- 이미지 상의 Secret 패턴 탐색_
* GIT - [hadolint](https://github.com/hadolint/hadolint)
* GIT - [dockerfile-lint](https://github.com/projectatomic/dockerfile_lint)
* GIT - [Containers Roadmap](https://github.com/aws/containers-roadmap)
* Blog - [Setting up AWS PrivateLink for Amazon ECS, and Amazon ECR](https://aws.amazon.com/blogs/compute/setting-up-aws-privatelink-for-amazon-ecs-and-amazon-ecr/)
* Blog - [AWS PrivateLink ECR cross account Fargate deployment](https://aws.amazon.com/blogs/containers/aws-privatelink-ecr-cross-account-fargate-deployment/)
* Blog - [Samsung Builds a Secure Developer Portal with Fargate and ECR](https://aws.amazon.com/ko/blogs/architecture/samsung-builds-a-secure-developer-portal-with-fargate-and-ecr/)
* Blog - [How to build a CI/CD pipeline for container vulnerability scanning with Trivy and AWS Security Hub](https://aws.amazon.com/blogs/security/how-to-build-ci-cd-pipeline-container-vulnerability-scanning-trivy-and-aws-security-hub/)
* Blog - [Native Container Image Scanning in Amazon ECR](https://aws.amazon.com/blogs/containers/amazon-ecr-native-container-image-scanning/)
* Blog - [Automating image compliance for Amazon EKS using Amazon Elastic Container Registry and AWS Security Hub](https://aws.amazon.com/ko/blogs/containers/automating-image-compliance-for-amazon-eks-using-amazon-elastic-container-registry-and-aws-security-hub/)
* Blog - [Introducing cross-account Amazon ECR access for AWS Lambda](https://aws.amazon.com/blogs/compute/introducing-cross-account-amazon-ecr-access-for-aws-lambda/)




## [ECS](https://aws.amazon.com/ko/ecs/?nc2=h_m1)

Amazon Elastic Container Service(ECS)는 확장성이 뛰어난 고성능 컨테이너 오케스트레이션 서비스로서, Docker 컨테이너를 지원하며 AWS에서 컨테이너식 애플리케이션을 쉽게 실행하고 확장 및 축소할 수 있습니다. ECS의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon Elastic Container Service의 보안](https://docs.aws.amazon.com/ko_kr/AmazonECS/latest/developerguide/security.html)
* [Fargate의 보안](https://docs.aws.amazon.com/ko_kr/AmazonECS/latest/userguide/security.html)
* [Using Bottlerocket with Amazon ECS](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-bottlerocket.html)
* GIT - [Docker Bench for Security](https://github.com/docker/docker-bench-security)
* GIT - [clair - static analysis of vulnerability in docker](https://github.com/coreos/clair)
* GIT - [LUNAR](https://github.com/lateralblast/lunar) _- CIS 기준으로 Linux, Docker 등을 보안 점검하는 스크립트_
* GIT - [secret-sidecar](https://github.com/jicowan/secret-sidecar) _- ECS Secret들을 Secret Manager에 안전하게 보관/관리하는 샘플_
* GIT - [Pumba: Chaos testing tool for Docker](https://github.com/alexei-led/pumba/)
* GIT - [Fargate IR](https://github.com/andrewkrug/fargate-ir) _- Fargate환경에 대한 IR구성 템플릿, PoC 레벨임_
* GIT - [Containers Roadmap](https://github.com/aws/containers-roadmap)
* GIT - [secret-sidecar](https://github.com/jicowan/secret-sidecar) _- Secret Manager와 ECS 연계_
* GIT - [AWS Bottlerocket OS](https://github.com/bottlerocket-os/bottlerocket)
* GIT - [Using a Bottlerocket AMI with Amazon ECS](https://github.com/bottlerocket-os/bottlerocket/blob/develop/QUICKSTART-ECS.md)
* GIT - [Bottlerocket - Security Guidance](https://github.com/bottlerocket-os/bottlerocket/blob/develop/SECURITY_GUIDANCE.md)
* GIT - [Bottlerocket - Security Features](https://github.com/bottlerocket-os/bottlerocket/blob/develop/SECURITY_FEATURES.md)
* GIT - [Bottlerocket - Roadmaps](https://github.com/orgs/bottlerocket-os/projects/1?card_filter_query=label%3Asecurity)
* Ext. - [Docker and SELinux](http://www.projectatomic.io/docs/docker-and-selinux/)
* Ext. - [Using OpenSCAP with Docker](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/security_guide/sect-using_openscap_with_docker)
* Ext. - [How to protect a Windows 2016 Docker engine with TLS](https://stefanscherer.github.io/protecting-a-windows-2016-docker-engine-with-tls/)
* 가이드 - [Access container applications privately on Amazon ECS by using AWS Fargate, AWS PrivateLink, and a Network Load Balancer](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/access-container-applications-privately-on-amazon-ecs-by-using-aws-fargate-aws-privatelink-and-a-network-load-balancer.html)
* 가이드 - [Access container applications privately on Amazon ECS by using AWS PrivateLink and a Network Load Balancer](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/access-container-applications-privately-on-amazon-ecs-by-using-aws-privatelink-and-a-network-load-balancer.html)
* 가이드 - [Rotate credentials without restarting containers](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/rotate-credentials-without-restarting-containers.html)
* Blog - [Managing Secrets for Amazon ECS Applications Using Parameter Store and IAM Roles for Tasks](https://aws.amazon.com/blogs/compute/managing-secrets-for-amazon-ecs-applications-using-parameter-store-and-iam-roles-for-tasks/)
* Blog - [Maintaining Transport Layer Security All the Way to Your Container: Using the Network Load Balancer with Amazon ECS](https://aws.amazon.com/blogs/compute/maintaining-transport-layer-security-all-the-way-to-your-container-using-the-network-load-balancer-with-amazon-ecs/)
* Blog - [Maintaining Transport Layer Security all the way to your container part 2: Using AWS Certificate Manager Private Certificate Authority](https://aws.amazon.com/blogs/compute/maintaining-transport-layer-security-all-the-way-to-your-container-part-2-using-aws-certificate-manager-private-certificate-authority/)
* Blog - [Centralized Container Logs with Amazon ECS and Amazon CloudWatch Logs](https://aws.amazon.com/ko/blogs/compute/centralized-container-logs-with-amazon-ecs-and-amazon-cloudwatch-logs/)
* Blog - [Introducing atomic scan – Container vulnerability detection](https://developers.redhat.com/blog/2016/05/02/introducing-atomic-scan-container-vulnerability-detection/)
* Blog - [Detect vulnerabilities in the Docker images in your applications](https://aws.amazon.com/blogs/publicsector/detect-vulnerabilities-in-the-docker-images-in-your-applications/)
* Blog - [Anatomy of CVE-2019-5736: A runc container escape!](https://aws.amazon.com/blogs/compute/anatomy-of-cve-2019-5736-a-runc-container-escape/)
* Blog - [Access Private applications on AWS Fargate using Amazon API Gateway PrivateLink](https://aws.amazon.com/blogs/compute/access-private-applications-on-aws-fargate-using-amazon-api-gateway-privatelink/)
* Blog - [Setting up AWS PrivateLink for Amazon ECS, and Amazon ECR](https://aws.amazon.com/blogs/compute/setting-up-aws-privatelink-for-amazon-ecs-and-amazon-ecr/)
* Blog - [Securing credentials using AWS Secrets Manager with AWS Fargate](https://aws.amazon.com/blogs/compute/securing-credentials-using-aws-secrets-manager-with-aws-fargate/)
* Blog - [Samsung Builds a Secure Developer Portal with Fargate and ECR](https://aws.amazon.com/blogs/architecture/samsung-builds-a-secure-developer-portal-with-fargate-and-ecr/)
* Blog - [How to Run ECS Windows Task with group Managed Service Account (gMSA)](https://aws.amazon.com/ko/blogs/containers/how-to-run-ecs-windows-task-with-group-managed-service-account-gmsa/)
* Blog - [Using Amazon ECS Exec to access your containers on AWS Fargate and Amazon EC2](https://aws.amazon.com/blogs/containers/new-using-amazon-ecs-exec-access-your-containers-fargate-ec2/)
* Blog - [Security features of Bottlerocket, an open source Linux-based operating system](https://aws.amazon.com/ko/blogs/opensource/security-features-of-bottlerocket-an-open-source-linux-based-operating-system/)
* Blog - [Bottlerocket, A Year in the Life](https://aws.amazon.com/blogs/containers/bottlerocket-a-year-in-the-life/)
* Blog - [Control access to Amazon Elastic Container Service resources by using ABAC policies](https://aws.amazon.com/blogs/security/control-access-to-amazon-elastic-container-service-resources-by-using-abac-policies/)
* Blog - [Announcing NVIDIA GPU support for Bottlerocket on Amazon ECS](https://aws.amazon.com/blogs/containers/announcing-nvidia-gpu-support-for-bottlerocket-on-amazon-ecs/)
* Blog - [Securing Amazon Elastic Container Service applications using Application Load Balancer and Amazon Cognito](https://aws.amazon.com/blogs/containers/securing-amazon-elastic-container-service-applications-using-application-load-balancer-and-amazon-cognito/)
* Blog - [Providing controlled internet access through centralised proxy servers using AWS Fargate and PrivateLink](https://aws.amazon.com/blogs/networking-and-content-delivery/providing-controlled-internet-access-through-centralised-proxy-servers-using-aws-fargate-and-privatelink/)


 
## [EKS](https://aws.amazon.com/ko/eks/?nc2=h_m1)

Amazon Elastic Kubernetes Service(EKS)를 사용하면 AWS에서 Kubernetes를 사용하여 컨테이너식 애플리케이션을 손쉽게 배포, 관리 및 확장할 수 있습니다. EKS의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon EKS의 보안](https://docs.aws.amazon.com/ko_kr/eks/latest/userguide/security.html)
* [Deep Learning Containers](https://docs.aws.amazon.com/ko_kr/eks/latest/userguide/deep-learning-containers.html)
* 백서 - [The definitive Guide to Securing Kubenetes](https://cdn2.hubspot.net/hubfs/1665891/Assets/The%20Definitive%20Guide%20to%20Securing%20Kubernetes.pdf)
* 백서 - [Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/security/docs/)
* 외부 백서 - [O'Reilly - Kubenetes Security](https://kubernetes-security.info/)
* 외부 백서 - [Kubernetes Security White Papaer](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2019/findings/Kubernetes%20White%20Paper.pdf)
* 백서 - [Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/)
* GIT - [Kubernetes Security on AWS](https://github.com/freach/kubernetes-security-best-practice/blob/master/AWS.md)
* GIT - [public roadmap for AWS container services (ECS, ECR, Fargate, and EKS)](https://github.com/aws/containers-roadmap)
* GIT - [Kubernetes Security - Best Practice Guide](https://github.com/freach/kubernetes-security-best-practice)
* GIT - [AWS IAM Authenticator for Kubernetes](https://github.com/kubernetes-sigs/aws-iam-authenticator)
* GIT - [kube-monkey : randomly deletes Kubernetes (k8s) pods](https://github.com/asobti/kube-monkey)
* GIT - [kube-bench](https://github.com/aquasecurity/kube-bench) _- Kube worker node 보안 점검_
* GIT - [Containers Roadmap](https://github.com/aws/containers-roadmap)
* GIT - [secret-sidecar](https://github.com/jicowan/secret-sidecar) _- Secret Manager와 EKS 연계_
* GIT - [AWS EKS Secrets injector](https://github.com/Mahendrasiddappa/eks-secret-injector) _- Secret Manager와 EKS 연계_
* GIT - [Native Secrets](https://github.com/mhausenblas/nase) _- Secret Manager와 EKS 연계_
* GIT - [AWS Bottlerocket OS](https://github.com/bottlerocket-os/bottlerocket)
* GIT - [Using a Bottlerocket AMI with Amazon EKS](https://github.com/bottlerocket-os/bottlerocket/blob/develop/QUICKSTART-EKS.md)
* GIT - [Bottlerocket - Security Guidance](https://github.com/bottlerocket-os/bottlerocket/blob/develop/SECURITY_GUIDANCE.md)
* GIT - [Bottlerocket - Security Features](https://github.com/bottlerocket-os/bottlerocket/blob/develop/SECURITY_FEATURES.md)
* GIT - [Bottlerocket - Roadmaps](https://github.com/orgs/bottlerocket-os/projects/1?card_filter_query=label%3Asecurity)
* GIT - [Simulator](https://github.com/kubernetes-simulator/simulator)
* GIT - [aws-privateca-issuer](https://cert-manager.github.io/aws-privateca-issuer/)
* QuickStart - [HashiCorp Vault on Amazon EKS](https://aws.amazon.com/quickstart/architecture/eks-vault/)
* QuickStart - [Federated Kubernetes Clusters Using Amazon EKS and KubeFed](https://aws.amazon.com/ko/solutions/implementations/federated-amazon-eks-clusters-on-aws/?nc1=h_ls)
* Ext. - [Cloud Native Security Tutorial at KubeCon EU 2020 by Liz Rice & Michael Hausenblas](https://tutorial.kubernetes-security.info/)
* Ext. -[Using AWS KMS for application secrets in Kubernetes](https://medium.com/@mtreacher/using-aws-kms-for-application-secrets-in-kubernetes-149ffb6b4073)
* Ext. - [On Securing the Kubernetes Dashboard](https://blog.heptio.com/on-securing-the-kubernetes-dashboard-16b09b1b7aca)
* Ext. - [11 Ways (Not) to Get Hacked](https://kubernetes.io/blog/2018/07/18/11-ways-not-to-get-hacked/)
* Ext. - [Securing the Base Infrastructure of a Kubernetes Cluster](https://blog.giantswarm.io/securing-the-base-infrastructure-of-a-kubernetes-cluster/)
* Ext. - [Securing the Configuration of Kubernetes Cluster Components](https://www.giantswarm.io/blog/securing-the-configuration-of-kubernetes-cluster-components)
* Ext. -[Single Sign-On for Kubernetes: Dashboard Experience](https://thenewstack.io/single-sign-on-for-kubernetes-dashboard-experience/)
* Ext. - [Provider agnostic authentication and authorization in Kubernetes](https://banzaicloud.com/blog/k8s-rbac/)
* Support - [How do I terminate HTTPS traffic on Amazon EKS workloads with ACM?](https://aws.amazon.com/premiumsupport/knowledge-center/terminate-https-traffic-eks-acm/)
* 가이드 - [Access container applications privately on Amazon EKS using AWS PrivateLink and a Network Load Balancer](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/access-container-applications-privately-on-amazon-eks-using-aws-privatelink-and-a-network-load-balancer.html)
* 가이드 - [Configure mutual TLS authentication for applications running on Amazon EKS](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/configure-mutual-tls-authentication-for-applications-running-on-amazon-eks.html)
* 가이드 - [Rotate credentials without restarting containers](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/rotate-credentials-without-restarting-containers.html)
* Blog - [Using Pod Security Policies with Amazon EKS Clusters](https://aws.amazon.com/blogs/opensource/using-pod-security-policies-amazon-eks-clusters/)
* Blog - [Driving Continuous Security and Configuration Checks for Amazon EKS with Alcide Advisor](https://aws.amazon.com/blogs/apn/driving-continuous-security-and-configuration-checks-for-amazon-eks-with-alcide-advisor/)
* Blog - [How to rotate a WordPress MySQL database secret using AWS Secrets Manager in Amazon EKS](https://aws.amazon.com/blogs/security/how-to-rotate-a-wordpress-mysql-database-secret-using-aws-secrets-manager-in-amazon-eks/)
* Blog - [Secure a Kubernetes Cluster with Pod Security Policies](https://docs.bitnami.com/kubernetes/how-to/secure-kubernetes-cluster-psp/)
* Blog - [Securing Amazon EKS Using Lambda and Falco](https://aws.amazon.com/blogs/opensource/securing-amazon-eks-lambda-falco/)
* Blog - [Introducing fine-grained IAM roles for service accounts](https://aws.amazon.com/ko/blogs/opensource/introducing-fine-grained-iam-roles-service-accounts/)
* Blog - [GoDaddy - Kubernetes External Secrets](https://kr.godaddy.com/engineering/2019/04/16/kubernetes-external-secrets/) _- EKS Secret들을 Secret Manager에 저장,관리하는 방법에 대한 GoDaddy 블로그_
* Blog - [Keep your Kubernetes secrets in git with Kubesec](https://blog.stack-labs.com/code/keep-your-kubernetes-secrets-in-git-with-kubesec/) _- Kubernetes Secret들을 안전하게 저장, 관리하는 KubeSec에 대한 소개 블로그_
* Blog - [Using Gatekeeper as a drop-in Pod Security Policy replacement in Amazon EKS](https://aws.amazon.com/blogs/containers/using-gatekeeper-as-a-drop-in-pod-security-policy-replacement-in-amazon-eks/)
* Blog - [Manage Amazon EKS with Okta SSO](https://aws.amazon.com/blogs/containers/manage-amazon-eks-with-okta-sso/)
* Blog - [Integrating LDAP/AD Users to Kubernetes RBAC with the AWS-IAM-Authenticator Community Project](https://aws.amazon.com/blogs/opensource/integrating-ldap-ad-users-kubernetes-rbac-aws-iam-authenticator-project/)
* Blog - [Automating image compliance for Amazon EKS using Amazon Elastic Container Registry and AWS Security Hub](https://aws.amazon.com/ko/blogs/containers/automating-image-compliance-for-amazon-eks-using-amazon-elastic-container-registry-and-aws-security-hub/)
* Blog - [Introducing OIDC identity provider authentication for Amazon EKS](https://aws.amazon.com/blogs/containers/introducing-oidc-identity-provider-authentication-amazon-eks/)
* Blog - [Using EKS encryption provider support for defense-in-depth](https://aws.amazon.com/blogs/containers/using-eks-encryption-provider-support-for-defense-in-depth/)
* Blog - [Implementing Runtime security in Amazon EKS using CNCF Falco](https://aws.amazon.com/blogs/containers/implementing-runtime-security-in-amazon-eks-using-cncf-falco/)
* Blog - [Securing Kubernetes applications with AWS App Mesh and cert-manager](https://aws.amazon.com/blogs/containers/securing-kubernetes-applications-with-aws-app-mesh-and-cert-manager/)
* Blog - [How to use AWS Secrets & Configuration Provider with your Kubernetes Secrets Store CSI driver](https://aws.amazon.com/blogs/security/how-to-use-aws-secrets-configuration-provider-with-kubernetes-secrets-store-csi-driver/)
* Blog - [TLS-enabled Kubernetes clusters with ACM Private CA and Amazon EKS](https://aws.amazon.com/blogs/security/tls-enabled-kubernetes-clusters-with-acm-private-ca-and-amazon-eks-2/)
* Blog - [How to automate Amazon EKS preventative controls in CI/CD using CDK and OPA/Conftest](https://aws.amazon.com/blogs/containers/how-to-automate-amazon-eks-preventative-controls-in-ci-cd-using-cdk-and-opa-conftest/)
* Blog - [Protecting your Amazon EKS web apps with AWS WAF](https://aws.amazon.com/ko/blogs/containers/protecting-your-amazon-eks-web-apps-with-aws-waf/)
* Blog - [Amazon EKS adds native support for Bottlerocket in Managed Node Groups](https://aws.amazon.com/ko/blogs/containers/amazon-eks-adds-native-support-for-bottlerocket-in-managed-node-groups/)
* Blog - [Provisioning and Securing Bottlerocket OS-Based Amazon EKS Clusters Using Nirmata Kubernetes Platform](https://aws.amazon.com/blogs/apn/provisioning-and-securing-bottlerocket-os-based-amazon-eks-clusters-using-nirmata-kubernetes-platform/)
* Blog - [How to use Application Load Balancer and Amazon Cognito to authenticate users for your Kubernetes web apps](https://aws.amazon.com/ko/blogs/containers/how-to-use-application-load-balancer-and-amazon-cognito-to-authenticate-users-for-your-kubernetes-web-apps/)
* Blog - [Secure end-to-end traffic on Amazon EKS using TLS certificate in ACM, ALB, and Istio](https://aws.amazon.com/blogs/containers/secure-end-to-end-traffic-on-amazon-eks-using-tls-certificate-in-acm-alb-and-istio/)
* Blog - [Bottlerocket support for NVIDIA GPUs](https://aws.amazon.com/blogs/containers/bottlerocket-support-for-nvidia-gpus/)
* Blog - [Building a multi-tenant Kubeflow environment on Amazon EKS using Amazon Cognito and ADFS](https://aws.amazon.com/blogs/opensource/building-a-multi-tenant-kubeflow-environment-on-amazon-eks-using-amazon-cognito-and-adfs/)
* Blog - [Diving into IAM Roles for Service Accounts](https://aws.amazon.com/blogs/containers/diving-into-iam-roles-for-service-accounts/)
* Blog - [Implement a central ingress Application Load Balancer supporting private Amazon Elastic Kubernetes Service VPCs](https://aws.amazon.com/blogs/networking-and-content-delivery/implement-a-central-ingress-application-load-balancer-supporting-private-amazon-elastic-kubernetes-service-vpcs/)
* Blog - [A quick path to Amazon EKS single sign-on using AWS SSO](https://aws.amazon.com/blogs/containers/a-quick-path-to-amazon-eks-single-sign-on-using-aws-sso/)
* Blog - [How to automate Amazon EKS preventative controls in CI/CD using CDK and OPA/Conftest](https://aws.amazon.com/ko/blogs/containers/how-to-automate-amazon-eks-preventative-controls-in-ci-cd-using-cdk-and-opa-conftest/)
* Blog - [Leverage AWS secrets stores from EKS Fargate with External Secrets Operator](https://aws.amazon.com/ko/blogs/containers/leverage-aws-secrets-stores-from-eks-fargate-with-external-secrets-operator/)
* Blog - [Building STIG-compliant AMIs for Amazon EKS](https://aws.amazon.com/blogs/containers/building-stig-compliant-amis-for-amazon-eks/)
* Blog - [Leveraging CNI custom networking alongside security groups for pods in Amazon EKS](https://aws.amazon.com/blogs/containers/leveraging-cni-custom-networking-alongside-security-groups-for-pods-in-amazon-eks/)
* Blog - [Build repeatable, secure, and extensible end-to-end machine learning workflows using Kubeflow on AWS](https://aws.amazon.com/blogs/machine-learning/build-repeatable-secure-and-extensible-end-to-end-machine-learning-workflows-using-kubeflow-on-aws/)


## [App Runner](https://aws.amazon.com/ko/apprunner/)

AWS App Runner는 개발자가 사전 인프라 경험 없이도 컨테이너화된 웹 애플리케이션 및 API를 대규모로 빠르게 배포할 수 있도록 지원하는 완전관리형 서비스입니다. App Runner의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [앱 러너의 보안](https://docs.aws.amazon.com/ko_kr/apprunner/latest/dg/security.html)


## [AWS App2Container](https://aws.amazon.com/ko/app2container/)

AWS App2Container(A2C)는 .NET과 Java 애플리케이션을 컨테이너화된 애플리케이션으로 현대화하는 명령줄 도구입니다. AWS App2Container의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in AWS App2Container](https://docs.aws.amazon.com/ko_kr/app2container/latest/UserGuide/sec-a2c-chapter.html)
* Blog - [Migrate your Applications to Containers at Scale](https://aws.amazon.com/blogs/architecture/migrate-your-applications-to-containers-at-scale/)


 
## 	Containers와 관련된 기타 유용한 링크들

* Blog - [Advice on mitigating the Apache log4j security issue for EKS, ECS, and Fargate customers](https://aws.amazon.com/ko/blogs/containers/advice-on-mitigating-the-apache-log4j-security-issue-for-eks-ecs-and-fargate-customers/)
* Blog - [Cryptographic Signing for Containers](https://aws.amazon.com/ko/blogs/containers/cryptographic-signing-for-containers/)


## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.


---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>