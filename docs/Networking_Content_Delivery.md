# Networking & Content Delivery
VPC에 대한 내용은 AWS 보안 서비스의 인프라 보안 영역에 있습니다. 이곳에서는 VPC를 제외한 다른 네트워크 및 컨텐츠 전송 서비스들과 관련된 보안 기능들에 대한 유용한 링크들을 제공합니다.


## [CloudFront](https://aws.amazon.com/ko/cloudfront/?nc2=h_m1)

Amazon CloudFront는 개발자 친화적 환경에서 짧은 지연 시간과 빠른 전송 속도로 데이터, 동영상, 애플리케이션 및 API를 전 세계 고객에게 안전하게 전송하는 고속 콘텐츠 전송 네트워크(CDN) 서비스입니다. CloudFront의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon CloudFront의 보안](https://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/security.html)
* GIT - [CloudJack - AWS Route53/CloudFront Vulnerability Assessment Utility](https://github.com/prevade/cloudjack#aws-route53cloudfront-vulnerability-assessment-utility) _- Route53과 CloudFront 간 설정 불일치를 통해 발생하는 서브도메인 하이제킹 취약점을 점검하는 스크립트_
* GIT - [peteragility/cf-auth: Cookieless Token AuthN/AuthZ Solution for HLS/DASH Streaming via Amazon CloudFront](https://github.com/peteragility/cf-auth)
* GIT - [egunda/secure-HLS: Rewriting manifest file to deliver HLS secure streaming](https://github.com/egunda/secure-HLS)
* 가이드 - [Check an Amazon CloudFront distribution for access logging, HTTPS, and TLS version](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/check-an-amazon-cloudfront-distribution-for-access-logging-https-and-tls-version.html)
* Blog - [Authorization@Edge using cookies: Protect your Amazon CloudFront content from being downloaded by unauthenticated users](https://aws.amazon.com/blogs/networking-and-content-delivery/authorizationedge-using-cookies-protect-your-amazon-cloudfront-content-from-being-downloaded-by-unauthenticated-users/)
* Blog - [Continually Enhancing Domain Security on Amazon CloudFront](https://aws.amazon.com/blogs/networking-and-content-delivery/continually-enhancing-domain-security-on-amazon-cloudfront/)
* Blog - [Aggregating Lambda@Edge Logs](https://aws.amazon.com/blogs/networking-and-content-delivery/aggregating-lambdaedge-logs/)
* Blog - [Analyze your Amazon CloudFront access logs at scale](https://aws.amazon.com/blogs/big-data/analyze-your-amazon-cloudfront-access-logs-at-scale/)
* Blog - [How to Enhance the Security of Sensitive Customer Data by Using Amazon CloudFront Field-Level Encryption](https://aws.amazon.com/blogs/security/how-to-enhance-the-security-of-sensitive-customer-data-by-using-amazon-cloudfront-field-level-encryption/)
* Blog - [How to enhance Amazon CloudFront origin security with AWS WAF and AWS Secrets Manager](https://aws.amazon.com/blogs/security/how-to-enhance-amazon-cloudfront-origin-security-with-aws-waf-and-aws-secrets-manager/)
* Blog - [Automatically update security groups for Amazon CloudFront IP ranges using AWS Lambda](https://aws.amazon.com/blogs/security/automatically-update-security-groups-for-amazon-cloudfront-ip-ranges-using-aws-lambda/)
* Blog - [Introducing CloudFront Functions – Run Your Code at the Edge with Low Latency at Any Scale](https://aws.amazon.com/blogs/aws/introducing-cloudfront-functions-run-your-code-at-the-edge-with-low-latency-at-any-scale/)
* Blog - [CloudFront Functions – A New Security Paradigm for CDN Edge Computing](https://aws.amazon.com/blogs/networking-and-content-delivery/cloudfront-functions-a-new-security-paradigm-for-cdn-edge-computing/)
* Blog - [Adding HTTP Security Headers Using Lambda@Edge and Amazon CloudFront](https://aws.amazon.com/blogs/networking-and-content-delivery/adding-http-security-headers-using-lambdaedge-and-amazon-cloudfront/)
* Blog - [Protect public clients for Amazon Cognito by using an Amazon CloudFront proxy](https://aws.amazon.com/blogs/security/protect-public-clients-for-amazon-cognito-by-using-an-amazon-cloudfront-proxy/)
* Blog - [Unpacking SNI-based SSL and dedicated IP SSL for Amazon CloudFront](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/unpacking-sni-based-ssl-and-dedicated-ip-ssl-for-amazon-cloudfront/)
* Blog - [Amazon CloudFront introduces Response Headers Policies](https://aws.amazon.com/blogs/networking-and-content-delivery/amazon-cloudfront-introduces-response-headers-policies/)
* Blog - [Secure and Cost-Effective Video Streaming using CloudFront signed URLs](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/secure-and-cost-effective-video-streaming-using-cloudfront-signed-urls/)
* Blog - [Secure content using CloudFront Functions](https://aws.amazon.com/ko/blogs/media/secure-content-using-cloudfront-functions/)
* Blog - [Protecting your media assets with token authentication](https://aws.amazon.com/ko/blogs/media/awse-protecting-your-media-assets-with-token-authentication/)
* Blog - [Serving SSE-KMS encrypted content from S3 using CloudFront](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/serving-sse-kms-encrypted-content-from-s3-using-cloudfront/)
* Blog - [How to protect sensitive data for its entire lifecycle in AWS](https://aws.amazon.com/ko/blogs/security/how-to-protect-sensitive-data-for-its-entire-lifecycle-in-aws/)
* Blog - [Amazon CloudFront Announces Cache and Origin Request Policies](https://aws.amazon.com/blogs/networking-and-content-delivery/amazon-cloudfront-announces-cache-and-origin-request-policies/)
* Blog - [Limit access to your origins using the AWS-managed prefix list for Amazon CloudFront](https://aws.amazon.com/blogs/networking-and-content-delivery/limit-access-to-your-origins-using-the-aws-managed-prefix-list-for-amazon-cloudfront/)
* Blog - [Amazon CloudFront introduces Origin Access Control (OAC)](https://aws.amazon.com/blogs/networking-and-content-delivery/amazon-cloudfront-introduces-origin-access-control-oac/)


## [Route 53](https://aws.amazon.com/ko/route53/?nc2=h_m1)

Amazon Route 53는 높은 가용성과 확장성이 뛰어난 클라우드 Domain Name System (DNS) 웹 서비스입니다. Route 53의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon Route 53의 보안](https://docs.aws.amazon.com/ko_kr/Route53/latest/DeveloperGuide/security.html)
* [Amazon Route 53 DNS and health checking in the AWS CLI Reference](https://docs.aws.amazon.com/cli/latest/reference/route53/index.html)
* [Security in Amazon Route 53 Application Recovery Controller](https://docs.aws.amazon.com/ko_kr/r53recovery/latest/dg/security.html)
* GIT - [CloudJack - AWS Route53/CloudFront Vulnerability Assessment Utility](https://github.com/prevade/cloudjack#aws-route53cloudfront-vulnerability-assessment-utility) _- Route53과 CloudFront 간 설정 불일치를 통해 발생하는 서브도메인 하이제킹 취약점을 점검하는 스크립트_
* Support - [How do I associate a Route 53 private hosted zone with a VPC on a different AWS account?](https://aws.amazon.com/premiumsupport/knowledge-center/private-hosted-zone-different-account/)
* Blog - [Log your VPC DNS queries with Route 53 Resolver Query Logs](https://aws.amazon.com/blogs/aws/log-your-vpc-dns-queries-with-route-53-resolver-query-logs/)
* Blog - [Extending your Control Tower Network security with Amazon Route 53 DNS Firewall](https://aws.amazon.com/blogs/mt/extending-your-control-tower-network-security-with-aws-route-53-dns-firewall/)
* Blog - [Using VPC Endpoints in Multi-Region Architectures with Route 53 Resolver ](https://aws.amazon.com/ko/blogs/architecture/using-vpc-endpoints-in-multi-region-architectures-with-route-53-resolver/)


## [Elastic Load Balancing](https://aws.amazon.com/ko/elasticloadbalancing/)

Elastic Load Balancing은 들어오는 애플리케이션 트래픽을 Amazon EC2 인스턴스, 컨테이너, IP 주소, Lambda 함수와 같은 여러 대상에 자동으로 분산시킵니다. Elastic Load Balancing은 단일 가용 영역 또는 여러 가용 영역에서 다양한 애플리케이션 부하를 처리할 수 있습니다. Elastic Load Balancing의 보안관련 기능들은 아래와 같습니다. 

**Bookmark**

* [Elastic Load Balancing의 보안](https://docs.aws.amazon.com/ko_kr/elasticloadbalancing/latest/userguide/security.html)
* [ELB 데모](https://network.exampleloadbalancer.com/)
* [What is a Gateway Load Balancer?](https://docs.aws.amazon.com/elasticloadbalancing/latest/gateway/introduction.html)
* Support - [How do I analyze my Application Load Balancer access logs using Athena?](https://aws.amazon.com/premiumsupport/knowledge-center/athena-analyze-access-logs/)
* Support - [ACM/SSL 인증서를 로드 밸런서에 연결](https://aws.amazon.com/ko/premiumsupport/knowledge-center/associate-acm-certificate-alb-nlb/)
* 가이드 - [Ensure AWS load balancers use secure listener protocols (HTTPS, SSL/TLS)](https://docs.aws.amazon.com/ko_kr/prescriptive-guidance/latest/patterns/ensure-aws-load-balancers-use-secure-listener-protocols-https-ssl-tls.html)
* Reference Arch. - [Architecture for Gateway Load Balancer – East/West Inspection](https://d1.awsstatic.com/architecture-diagrams/ArchitectureDiagrams/gateway-load-balancer-inspection-east-west-ra.pdf)
* Reference Arch. - [Architecture for Gateway Load Balancer – North/South Inspection](https://d1.awsstatic.com/architecture-diagrams/ArchitectureDiagrams/gateway-load-balancer-inspection-north-south-ra.pdf)
* GIT - [AWS CloudFormation samples for AWS Gateway Load Balancer (GWLB)](https://github.com/aws-samples/aws-gateway-load-balancer-code-samples/tree/main/aws-cloudformation)
* GIT - [Building an open-source(Suricata) IPS/IDS Service on Gateway Load Balancer](https://github.com/aws-samples/aws-gateway-load-balancer-suricata-ids-ips-nsm)
* GIT - [GLB : VPC Routing Enhancement Based Architectures](https://github.com/aws-samples/aws-gateway-load-balancer-code-samples/tree/main/aws-cloudformation/vpc_routing_enhancement_architectures)
* Blog - [Using a Network Load Balancer with the NGINX Ingress Controller on Amazon EKS](https://aws.amazon.com/blogs/opensource/network-load-balancer-nginx-ingress-controller-eks/)
* Blog - [How to securely publish Internet applications at scale using Application Load Balancer and AWS PrivateLink](https://aws.amazon.com/blogs/networking-and-content-delivery/how-to-securely-publish-internet-applications-at-scale-using-application-load-balancer-and-aws-privatelink/)
* Blog - [Introducing AWS Gateway Load Balancer – Easy Deployment, Scalability, and High Availability for Partner Appliances](https://aws.amazon.com/blogs/aws/introducing-aws-gateway-load-balancer-easy-deployment-scalability-and-high-availability-for-partner-appliances/)
* Blog - [Introducing AWS Gateway Load Balancer: Supported architecture patterns](https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-aws-gateway-load-balancer-supported-architecture-patterns/)
* Ext.Blog - [GeneveProxy - an AWS Gateway Load Balancer reference application](https://www.sentiatechblog.com/geneveproxy-an-aws-gateway-load-balancer-reference-application)
* Blog - [Scaling network traffic inspection using AWS Gateway Load Balancer](https://aws.amazon.com/blogs/networking-and-content-delivery/scaling-network-traffic-inspection-using-aws-gateway-load-balancer/)
* Blog - [Centralized inspection architecture with AWS Gateway Load Balancer and AWS Transit Gateway](https://aws.amazon.com/blogs/networking-and-content-delivery/centralized-inspection-architecture-with-aws-gateway-load-balancer-and-aws-transit-gateway/)
* Blog - [Integrate your custom logic or appliance with AWS Gateway Load Balancer](https://aws.amazon.com/blogs/networking-and-content-delivery/integrate-your-custom-logic-or-appliance-with-aws-gateway-load-balancer/)
* Blog - [Using static IP addresses for Application Load Balancers](https://aws.amazon.com/blogs/networking-and-content-delivery/using-static-ip-addresses-for-application-load-balancers/)
* Blog - [How to integrate third-party firewall appliances into an AWS environment](https://aws.amazon.com/blogs/networking-and-content-delivery/how-to-integrate-third-party-firewall-appliances-into-an-aws-environment/)
* Blog - [Best practices for deploying Gateway Load Balancer](https://aws.amazon.com/ko/blogs/networking-and-content-delivery/best-practices-for-deploying-gateway-load-balancer/)
* Blog - [Building an Open Source IDS IPS service for Gateway Load Balancer](https://aws.amazon.com/blogs/networking-and-content-delivery/building-an-open-source-ids-ips-service-for-gateway-load-balancer/)
* Blog - [Application Load Balancer-type Target Group for Network Load Balancer](https://aws.amazon.com/blogs/networking-and-content-delivery/application-load-balancer-type-target-group-for-network-load-balancer/)
* Blog - [Introduction to Traffic Mirroring to GWLB Endpoints as Target](https://aws.amazon.com/blogs/networking-and-content-delivery/introduction-to-traffic-mirroring-to-gwlb-endpoints-as-target/)



## [API Gateway](https://aws.amazon.com/ko/api-gateway/?nc2=h_m1)

Amazon API Gateway는 어떤 규모에서든 개발자가 API를 손쉽게 생성, 게시, 유지 관리, 모니터링 및 보안할 수 있게 해주는 완전관리형 서비스입니다. API Gateway의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Amazon API Gateway 보안](https://docs.aws.amazon.com/ko_kr/apigateway/latest/developerguide/security.html)
* GIT - [Serverless Security Workshop](https://github.com/aws-samples/aws-serverless-security-workshop)
* Support - [VPC에서 API Gateway API에 연결할 때 HTTP 403 Forbidden 오류가 발생하는 이유는 무엇입니까?](https://aws.amazon.com/ko/premiumsupport/knowledge-center/api-gateway-vpc-connections/)
* Blog - [Secure API Access with Amazon Cognito Federated Identities, Amazon Cognito User Pools, and Amazon API Gateway](https://aws.amazon.com/blogs/compute/secure-api-access-with-amazon-cognito-federated-identities-amazon-cognito-user-pools-and-amazon-api-gateway/)
* Blog - [How to Architect APIs for Scale and Security](https://aws.amazon.com/blogs/architecture/how-to-architect-apis-for-scale-and-security/)
* Blog - [Use AWS Lambda authorizers with a third-party identity provider to secure Amazon API Gateway REST APIs](https://aws.amazon.com/blogs/security/use-aws-lambda-authorizers-with-a-third-party-identity-provider-to-secure-amazon-api-gateway-rest-apis/)
* Blog - [Introducing mutual TLS authentication for Amazon API Gateway](https://aws.amazon.com/blogs/compute/introducing-mutual-tls-authentication-for-amazon-api-gateway/)
* Blog - [Automating mutual TLS setup for Amazon API Gateway](https://aws.amazon.com/blogs/compute/automating-mutual-tls-setup-for-amazon-api-gateway/)
* Blog - [Troubleshooting Amazon API Gateway with enhanced observability variables](https://aws.amazon.com/blogs/compute/troubleshooting-amazon-api-gateway-with-enhanced-observability-variables/)
* Blog - [Introducing IAM and Lambda authorizers for Amazon API Gateway HTTP APIs](https://aws.amazon.com/blogs/compute/introducing-iam-and-lambda-authorizers-for-amazon-api-gateway-http-apis/)
* Blog - [Accessing an AWS API Gateway via static IP addresses provided by AWS Global Accelerator](https://aws.amazon.com/blogs/networking-and-content-delivery/accessing-an-aws-api-gateway-via-static-ip-addresses-provided-by-aws-global-accelerator/)
* Blog - [How to secure API Gateway HTTP endpoints with JWT authorizer](https://aws.amazon.com/blogs/security/how-to-secure-api-gateway-http-endpoints-with-jwt-authorizer/)
* Blog - [Implementing mutual TLS for Java-based AWS Lambda functions](https://aws.amazon.com/blogs/compute/implementing-mutual-tls-for-java-based-aws-lambda-functions-2/)
* Blog - [Enriching Amazon Cognito features with an Amazon API Gateway proxy](https://aws.amazon.com/ko/blogs/architecture/enriching-amazon-cognito-features-with-an-amazon-api-gateway-proxy/)
* Blog - [Restricting access on HTTP API Gateway Endpoint with Lambda Authorizer](http://aws-security.kr.s3-website.ap-northeast-2.amazonaws.com/Networking_Content_Delivery/)



## [Direct Connect](https://aws.amazon.com/ko/directconnect/?nc2=h_m1)

AWS Direct Connect는 온프레미스에서 AWS로 전용 네트워크 연결을 쉽게 설정할 수 있는 클라우드 서비스 솔루션입니다. Direct Connect의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Direct Connect의 보안](https://docs.aws.amazon.com/ko_kr/directconnect/latest/UserGuide/security.html)


 
## [AWS App Mesh](https://aws.amazon.com/ko/app-mesh/?nc2=h_m1)

AWS App Mesh는 애플리케이션 수준의 네트워킹을 통해 서비스가 여러 유형의 컴퓨팅 인프라에서 서로 원활하게 통신할 수 있게 지원하는 서비스 메시입니다. AWS App Mesh의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [Security in AWS App Mesh](https://docs.aws.amazon.com/ko_kr/app-mesh/latest/userguide/security.html)
* GIT - [AWS App Mesh Roadmap](https://github.com/aws/aws-app-mesh-roadmap)
* GIT - [Configuring Mutual TLS with File Provided TLS Certificates](https://github.com/aws/aws-app-mesh-examples/tree/master/walkthroughs/howto-mutual-tls-file-provided)
* GIT - [Amazon EKS mutual TLS walkthrough with SPIRE](https://github.com/aws/aws-app-mesh-examples/tree/master/walkthroughs/howto-k8s-mtls-sds-based)
* Blog - [How to use ACM Private CA for enabling mTLS in AWS App Mesh](https://aws.amazon.com/ko/blogs/security/how-to-use-acm-private-ca-for-enabling-mtls-in-aws-app-mesh/)
* Blog - [Enabling mTLS in AWS App Mesh using SPIFFE/SPIRE in a multi-account Amazon EKS environment](https://aws.amazon.com/ko/blogs/containers/enabling-mtls-in-aws-app-mesh-using-spiffe-spire-in-a-multi-account-amazon-eks-environment/)
* Blog - [Three things to consider when implementing Mutual TLS with AWS App Mesh](https://aws.amazon.com/blogs/containers/three-things-to-consider-when-implementing-mutual-tls-with-aws-app-mesh/)

 
## [AWS Cloud Map](https://aws.amazon.com/ko/cloud-map/?nc2=h_m1)

AWS Cloud Map은 클라우드 리소스 검색 서비스입니다. AWS Cloud Map의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Cloud Map의 보안](https://docs.aws.amazon.com/ko_kr/cloud-map/latest/dg/security.html)

 
## [Global Accelerator](https://aws.amazon.com/ko/global-accelerator/?nc2=h_m1)

AWS Global Accelerator는 글로벌 사용자에게 제공하는 애플리케이션의 가용성과 성능을 개선하는 네트워킹 서비스입니다. Global Accelerator의 보안관련 기능들은 아래와 같습니다.

**Bookmark**

* [AWS Global Accelerator security](https://docs.aws.amazon.com/ko_kr/global-accelerator/latest/dg/security.html)
* Blog - [Analyzing and visualizing AWS Global Accelerator flow logs using Amazon Athena and Amazon QuickSight](https://aws.amazon.com/blogs/networking-and-content-delivery/analyzing-and-visualizing-aws-global-accelerator-flow-logs-using-amazon-athena-and-amazon-quicksight/)
* Blog - [Improve throughput for internet facing file transfers using AWS Global Accelerator and AWS Transfer Family services](https://aws.amazon.com/blogs/networking-and-content-delivery/improve-data-delivery-throughput-for-internet-facing-file-transfer-workloads-using-aws-global-accelerator-and-aws-transfer-family-services/)

## [AWS Cloud WAN](https://aws.amazon.com/ko/cloud-wan/?nc1=h_ls)

AWS Cloud WAN은 클라우드 및 온-프레미스 환경에서 실행되는 리소스를 연결하는 통합 된 글로벌 네트워크를 빌드, 관리 및 모니터링하는 데 사용할 수있는 관리되는 WAN (Wide Area Networking) 서비스입니다.

**Bookmark**

* [AWS Cloud WAN security](https://docs.aws.amazon.com/ko_kr/vpc/latest/cloudwan/cloudwan-security.html)
* Blog - [New – Cloud WAN : A Managed WAN Service](https://aws.amazon.com/blogs/aws/new-cloud-wan-a-managed-wan-service/) 
 
## Networking & Content Delivery과 관련된 기타 유용한 링크들

준비중.


## Remarks

* 이 사이트의 모든 내용은 바뀌거나 수정될 수 있습니다.
* 공식적인 상세한 내용은 http://aws.amazon.com 의 내용을 참조하십시오.
* 제공되는 내용에 이견이 있거나 잘못된 링크를 발견하시면, 관리자(gisunlim@amazon.com)에게 메일을 주시면 대단히 감사하겠습니다.


---

[개인 정보 보호 정책](https://aws.amazon.com/privacy/?nc1=f_pr) | [사이트 이용 약관](https://aws.amazon.com/terms/?nc1=f_pr) | © 2020, Amazon Web Services, Inc. 또는 자회사. All rights reserved. 


<script type="text/javascript" src="http://www.websitegoodies.com/counter.php?id=72613&color=%23183fd8"></script>