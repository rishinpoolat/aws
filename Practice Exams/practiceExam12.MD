# Practice Exam 12

Click on the **Answer** button for the correct answer and its explanation.


---

1. Which of the following components of the AWS Global Infrastructure consists of one or more discrete data centers interconnected through low latency links?
    - A. Availability Zone
    - B. Edge location
    - C. Region
    - D. Private networking

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

2. One benefit of On-Demand Amazon Elastic Compute Cloud (Amazon EC2) pricing is:
    - A. The ability to bid for a lower hourly cost.
    - B. Paying a daily rate regardless of time used.
    - C. Paying only for time used.
    - D. Pre-paying for instances and paying a lower hourly rate.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

3. What can assist in evaluating an application for migration to the cloud? (Select TWO)
    - A. AWS Trusted Advisor.
    - B. AWS Professional Services.
    - C. AWS Systems Manager.
    - D. AWS Partner Network (APN).
    - E. AWS Secrets Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
    </details>

4. A characteristic of edge locations is that they:
    - A. Host Amazon EC2 instances closer to users.
    - B. Help lower latency and improve performance for users.
    - C. Cache frequently changing data without reaching the origin server.
    - D. Refresh data changes daily.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

5. Which of the following are valid ways for a customer to interact with AWS services? (Select TWO)
    - A. Command line interface.
    - B. On-premises.
    - C. Software Development Kits.
    - D. Software-as-a-service.
    - E. Hybrid.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
    </details>

6. What is a value proposition of the AWS Cloud?
    - A. AWS is responsible for security in the AWS Cloud.
    - B. No long-term contract is required.
    - C. Provision new servers in days.
    - D. AWS manages user applications in the AWS Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Explanation:One of the key value propositions of the AWS Cloud is its pay-as-you-go pricing model, which means that you don't have to commit to long-term contracts or make significant upfront investments. With AWS, you can provision and use resources on-demand, and you only pay for what you actually consume, allowing you to scale up or down based on your needs without any long-term commitments.
      
      AWS is responsible for security in the AWS Cloud: This statement is partially correct. AWS is responsible for the security of the underlying cloud infrastructure, but customers are responsible for securing their applications, data, and resources running on AWS.
      
      Provision new servers in days: This option is not a value proposition of AWS Cloud. With AWS, you can provision new servers (EC2 instances) in minutes, not days, allowing for rapid scalability and deployment.
      
      AWS manages user applications in the AWS Cloud: This statement is incorrect. AWS provides the underlying infrastructure and services, but customers are responsible for managing and maintaining their applications running on AWS.
    </details>

7. A company is migrating an application that is running non-interruptible workloads for a three-year time frame. Which pricing construct would provide the MOST cost-effective solution?
    - A. Amazon EC2 Spot Instances.
    - B. Amazon EC2 Dedicated Instances.
    - C. Amazon EC2 On-Demand Instances.
    - D. Amazon EC2 Reserved Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Explanation: The most cost-effective pricing construct for migrating an application with non-interruptible workloads for a three-year time frame would be D. Amazon EC2 Reserved Instances.
      
      Amazon EC2 Reserved Instances provide a significant discount compared to On-Demand Instance pricing, making them cost-effective for long-term, steady-state usage. Here's why Reserved Instances are the best option in this scenario:
      
      A. Amazon EC2 Spot Instances: Spot Instances are suitable for workloads that can be interrupted or have flexible start and end times. They are not recommended for non-interruptible workloads or long-term, consistent usage due to the possibility of instance termination when the Spot price exceeds your maximum bid price.
      
      B. Amazon EC2 Dedicated Instances: Dedicated Instances are physically isolated EC2 instances, primarily used for compliance requirements or to address specific regulatory concerns. They are generally more expensive than other instance types and may not be the most cost-effective option for this use case.
      
      C. Amazon EC2 On-Demand Instances: On-Demand Instances are suitable for short-term, unpredictable workloads or when you don't have a long-term commitment. However, for a three-year time frame with non-interruptible workloads, On-Demand Instances can be more expensive compared to Reserved Instances.
      
      D. Amazon EC2 Reserved Instances: Reserved Instances are the most cost-effective option for long-term, steady-state usage. By purchasing Reserved Instances with a 3-year term, you can benefit from significant discounts (up to 72% compared to On-Demand pricing) for a consistent, non-interruptible workload. This commitment allows you to optimize costs while meeting your application's requirements.
    </details>

8. Which AWS service is used to track record, and audit configuration changes made to AWS resources?
    - A. AWS Shield.
    - B. AWS Config.
    - C. AWS IAM.
    - D. Amazon Inspector.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

9. Which feature of the AWS Cloud will support an international company’s requirement for low latency to all of its customers?
    - A. Fault tolerance.
    - B. Global reach.
    - C. Pay-as-you-go pricing.
    - D. High availability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

10. How can one AWS account use Reserved Instances from another AWS account?
    - A. By using Amazon EC2 Dedicated Instances.
    - B. By using AWS Organizations consolidated billing.
    - C. By using the AWS Cost Explorer tool.
    - D. By using AWS Budgets.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

11. What are the benefits of developing and running a new application in the AWS Cloud compared to on-premises? (Select TWO)
    - A. AWS automatically distributes the data globally for higher durability.
    - B. AWS will take care of operating the application.
    - C. AWS makes it easy to architect for high availability.
    - D. AWS can easily accommodate application demand changes.
    - E. AWS takes care of application security patching.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C, D
    </details>

12. Which of the following services falls under the responsibility of the customer to maintain operating system configuration, security patching, and networking?
    - A. Amazon RDS.
    - B. Amazon EC2.
    - C. Amazon ElastiCache.
    - D. AWS Fargate.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

13. AWS supports which of the following methods to add security to Identity and Access Management (IAM) users? (Select TWO)
    - A. Implementing Amazon Rekognition.
    - B. Using AWS Shield-protected resources.
    - C. Blocking access with Security Groups.
    - D. Using Multi-Factor Authentication (MFA).
    - E. Enforcing password strength and expiration.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E
    </details>

14. Which service provides a hybrid storage service that enables on-premises applications to seamlessly use cloud storage?
    - A. Amazon Glacier
    - B. AWS Snowball
    - C. AWS Storage Gateway
    - D. Amazon Elastic Block Storage (Amazon EBS)

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Explanation: The correct answer is C. AWS Storage Gateway.
      
      AWS Storage Gateway is a hybrid cloud storage service that provides on-premises applications with seamless access to virtually unlimited cloud storage from Amazon Simple Storage Service (Amazon S3). It enables organizations to integrate on-premises IT environments with the AWS Cloud for storage and data transfer.
      
      Amazon Glacier is a secure, durable, and low-cost cloud storage service for data archiving and long-term backup. It is designed for infrequently accessed data and does not provide seamless integration with on-premises applications.

      AWS Snowball is a petabyte-scale data transfer service that allows organizations to transfer large amounts of data into and out of the AWS Cloud using physical storage devices. It is primarily used for large-scale data migrations and is not designed for seamless integration with on-premises applications.
      
      Amazon EBS provides block-level storage volumes for use with Amazon EC2 instances. It is designed for low-latency, high-throughput workloads and does not provide a hybrid storage solution for on-premises applications.
      
      AWS Storage Gateway acts as a bridge between on-premises applications and AWS Cloud storage services like Amazon S3, allowing applications to utilize cloud storage seamlessly while keeping data on-premises or caching data locally for low-latency access. It supports various storage configurations, including file gateways, volume gateways, and tape gateways, to meet different requirements.
    </details>

15. Where should a company go to search software listings from independent software vendors to find, test, buy and deploy software that runs on AWS?
    - A. AWS Marketplace.
    - B. Amazon Lumberyard.
    - C. AWS Artifact.
    - D. Amazon CloudSearch.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

16. Which of the following is a component of the AWS Global Infrastructure?
    - A. Amazon Alexa.
    - B. AWS Regions.
    - C. Amazon Lightsail.
    - D. AWS Organizations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

17. Which Amazon EC2 pricing model adjusts based on supply and demand of EC2 instances?
    - A. On-Demand Instances.
    - B. Reserved Instances.
    - C. Spot Instances.
    - D. Convertible Reserved Instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

18. A company wants to migrate its applications to a VPC on AWS These applications will need to access on-premises resources. What combination of actions will enable the company to accomplish this goals? (Select TWO)
    - A. Use the AWS Service Catalog to identify a list of on-premises resources that can be migrated
    - B. Build a VPN connection between an on-premises device and a virtual private gateway in the new VPC
    - C. Use Amazon Athena to query data from the on-premises database servers
    - D. Connect the company’s on-premises data center to AWS using AWS Direct Connect
    - E. Leverage Amazon CloudFront to restrict access to static web content provided through the company’s on-premises web servers

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      Explanation: The correct combination of actions to enable the company to migrate its applications to a VPC on AWS while maintaining access to on-premises resources is:
      
      Explanation: Build a VPN connection between an on-premises device and a virtual private gateway in the new VPC: Establishing a VPN connection between the on-premises network and the VPC in AWS allows secure communication and access to on-premises resources from the applications running in the VPC. A virtual private gateway acts as the VPN endpoint on the AWS side.
      
      Connect the company's on-premises data center to AWS using AWS Direct Connect: AWS Direct Connect provides a dedicated network connection between the company's on-premises data center and AWS. This dedicated connection offers increased bandwidth, lower latency, and a more consistent network experience compared to Internet-based connections. It enables secure and reliable access to on-premises resources from the VPC.
      
      Incorrect:
      
      The AWS Service Catalog is a service that allows organizations to create and manage catalogs of approved products and services. It does not directly help in identifying on-premises resources for migration.
      
      Amazon Athena is an interactive query service that can be used to analyze data in Amazon S3. It does not provide a mechanism to directly access on-premises database servers.
      
      Amazon CloudFront is a content delivery network (CDN) service. While it can be used to restrict access to content, it does not directly enable access to on-premises resources from the VPC.
    </details>

19. A Cloud Practitioner must determine if any security groups in an AWS account have been provisioned to allow unrestricted access for specific ports What is the SIMPLEST way to do this?
    - A. Review the inbound rules for each security group in the Amazon EC2 management console to check for port 0.0.0.0/0.
    - B. Run AWS Trusted Advisor and review the findings.
    - C. Open the AWS IAM console and check the inbound rule filters for open access.
    - D. In AWS Config, create a custom rule that invokes an AWS Lambda function to review firewall rules for inbound access.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A

      Explanation: The simplest way to determine if any security groups in an AWS account have been provisioned to allow unrestricted access for specific ports is A. Review the inbound rules for each security group in the Amazon EC2 management console to check for port 0.0.0.0/0.
      
      Review the inbound rules for each security group in the Amazon EC2 management console to check for port 0.0.0.0/0: This is the simplest and most direct way to identify security groups with unrestricted access for specific ports. In the Amazon EC2 management console, you can navigate to the security group settings and review the inbound rules for each security group. If you see a rule with a source of 0.0.0.0/0 (or ::/0 for IPv6), it means that the security group allows inbound access from any IP address for the specified port(s). This approach is straightforward and does not require additional services or configurations.
      
      AWS Trusted Advisor is a service that provides recommendations to help optimize your AWS environment. While it can identify security group rules that allow unrestricted access, running Trusted Advisor and reviewing the findings is a more complex process than directly checking the security group rules in the EC2 console.
      
      The AWS Identity and Access Management (IAM) console is used for managing user access and permissions. It does not provide information about security group rules or inbound access configurations. Security group rules are managed and configured within the Amazon EC2 service.
      
      In AWS Config, create a custom rule that invokes an AWS Lambda function to review firewall rules for inbound access: While this approach is possible, it requires additional configuration and setup. AWS Config is a service that provides a detailed view of resource configurations, and you can create custom rules to evaluate resource configurations and trigger Lambda functions. However, this approach is more complex than simply reviewing the security group rules in the EC2 console, which is the simplest and most direct method.

    </details>

20. Which of the following security-related services does AWS offer? (Select TWO)
    - A. Multi-factor authentication physical tokens.
    - B. AWS Trusted Advisor security checks.
    - C. Data encryption.
    - D. Automated penetration testing.
    - E. Amazon S3 copyrighted content detection.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
    </details>

21. Which of the following services have Distributed Denial of Service (DDoS) mitigation features? (Select TWO)
    - A. AWS WAF.
    - B. Amazon DynamoDB.
    - C. Amazon EC2.
    - D. Amazon CloudFront.
    - E. Amazon Inspector.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
      
      Explanation: The services that have Distributed Denial of Service (DDoS) mitigation features are:
      
      AWS Web Application Firewall (WAF) provides DDoS mitigation capabilities by allowing you to define custom rules to filter and block malicious web traffic before it reaches your web applications. AWS WAF can help mitigate various types of DDoS attacks, such as SYN floods, UDP floods, and HTTP floods.
      
      Amazon DynamoDB is a fully managed NoSQL database service. It does not have built-in DDoS mitigation features.
      
      Amazon Elastic Compute Cloud (EC2) instances do not have built-in DDoS mitigation features. However, you can use other AWS services like AWS WAF or AWS Shield (not mentioned in the options) to protect your EC2 instances from DDoS attacks.
      
      Amazon CloudFront is a content delivery network (CDN) service that provides DDoS mitigation capabilities. CloudFront can automatically detect and mitigate various types of DDoS attacks, including network-level attacks and application-level attacks, helping to protect your web applications.
      
      Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It does not provide DDoS mitigation features.
    </details>

22. Which of the following AWS features enables a user to launch a pre-configured Amazon Elastic Compute Cloud (Amazon EC2) instance?
    - A. Amazon Elastic Block Store (Amazon EBS).
    - B. Amazon Machine Image.
    - C. Amazon EC2 Systems Manager.
    - D. Amazon AppStream 2.0.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

23. A solution that is able to support growth in users, traffic, or data size with no drop in performance aligns with which cloud architecture principle?
    - A. Think parallel.
    - B. Implement elasticity.
    - C. Decouple your components.
    - D. Design for failure.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

24. Which AWS Cloud benefit eliminates the need for users to try estimating future infrastructure usage?
    - A. Easy and fast deployment of applications in multiple Regions around the world.
    - B. Security of the AWS Cloud.
    - C. Elasticity of the AWS Cloud.
    - D. Lower variable costs due to massive economies of scale.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

25. What can users access from AWS Artifact?
    - A. AWS security and compliance documents.
    - B. A download of configuration management details for all AWS resources.
    - C. Training materials for AWS services.
    - D. A security assessment of the applications deployed in the AWS Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

26. Compared with costs in traditional and virtualized data centers, AWS has:
    - A. Greater variable costs and greater upfront costs.
    - B. Fixed usage costs and lower upfront costs.
    - C. Lower variable costs and greater upfront costs.
    - D. Lower variable costs and lower upfront costs.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

27. Which AWS service would a customer use with a static website to achieve tower latency and high transfer speeds?
    - A. AWS Lambda.
    - B. Amazon DynamoDB Accelerator.
    - C. Amazon Route 53.
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Explanation: Amazon CloudFront is a content delivery network (CDN) service provided by AWS. It is designed to deliver data, videos, applications, and APIs to users globally with low latency and high transfer speeds.
      
      AWS Lambda is a serverless computing service used for running code without provisioning or managing servers. It is not designed for content delivery or static website hosting.
      
      Amazon DynamoDB Accelerator: There is no such service offered by AWS. DynamoDB is a fully managed NoSQL database service, but it does not provide CDN capabilities for static website delivery.
      
      Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. While it can be used for routing traffic to AWS resources, it does not directly contribute to lower latency or high transfer speeds for static website delivery.

    </details>

28. How do Amazon EC2 Auto Scaling groups help achieve high availability for a web application?
    - A. They automatically add more instances across multiple AWS Regions based on global demand of the application.
    - B. They automatically add or replace instances across multiple Availability Zones when the application needs it.
    - C. They enable the application’s stalk: content to reside closer to end users.
    - D. They are able to distribute incoming requests across a tier of web server instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

29. Which of the following can limit Amazon Simple Storage Service (Amazon S3) bucket access to specific users?
    - A. A public and private key-pair.
    - B. Amazon Inspector.
    - C. AWS Identity and Access Management (IAM) policies.
    - D. Security Groups.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

30. How should a customer forecast the future costs for running a new web application?
    - A. Amazon Aurora Backtrack.
    - B. Amazon CloudWatch Billing Alarms.
    - C. AWS Simple Monthly Calculator.
    - D. AWS Cost and Usage report.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

31. Where are AWS compliance documents, such as an SOC 1 report, located?
    - A. Amazon Inspector.
    - B. AWS CloudTrail.
    - C. AWS Artifact.
    - D. AWS Certificate Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

32. Which of the following tasks is the responsibility of AWS?
    - A. Encrypting client-side data.
    - B. Configuring AWS Identity and Access Management (IAM) roles.
    - C. Securing the Amazon EC2 hypervisor.
    - D. Setting user password policies.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

33. Under the shared responsibility model which of the following areas are the customer’s responsibility? (Select TWO)
    - A. Firmware upgrades of network infrastructure.
    - B. Patching of operating systems.
    - C. Patching of the underlying hypervisor.
    - D. Physical security of data centers.
    - E. Configuration of the security group.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E
    </details>

34. A company is looking for a scalable data warehouse solution. Which of the following AWS solutions would meet the company’s needs?
    - A. Amazon Simple Storage Service (Amazon S3).
    - B. Amazon DynamoDB.
    - C. Amazon Kinesis.
    - D. Amazon Redshift.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

35. Much AWS services provide a way to extend an on-premises architecture to the AWS Cloud? (Select TWO)
    - A. Amazon EBS.
    - B. AWS Direct Connect.
    - C. Amazon CloudFront.
    - D. AWS Storage Gateway.
    - E. Amazon Connect.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
    </details>

36. What are the advantages of the AWS Cloud (Select TWO)
    - A. Fixed rate monthly cost.
    - B. No need to guess capacity requirements.
    - C. Increased speed to market.
    - D. Increased upfront capital expenditure.
    - E. Physical access to cloud data centers.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
    </details>

37. How can the AWS Cloud increase user workforce productivity after migration from an on-premises data center?
    - A. Users do not have to wait for infrastructure provisioning.
    - B. The AWS Cloud infrastructure is much faster than an on-premises data center infrastructure.
    - C. AWS takes over application configuration management on behalf of users.
    - D. Users do not need to address security and compliance issues.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: A
    </details>

38. Which of the following services could be used to deploy an application to servers running on-premises? (Select TWO)
    - A. AWS Elastic Beanstalk.
    - B. AWS OpsWorks.
    - C. AWS CodeDeploy.
    - D. AWS Batch.
    - E. AWS X-Ray.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C

      Explanation: AWS CodeDeploy is a deployment service that automates application deployments to various compute services, including Amazon EC2 instances and on-premises servers. It supports deployments to both AWS resources and on-premises instances by installing a CodeDeploy agent on the target servers. This service can be used to deploy applications to on-premises servers, making it a valid choice for this question.
      
      AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. It allows you to use code-defined configurations to automate the deployment and management of applications, including on-premises servers. By installing the OpsWorks Agent on your on-premises servers, you can use OpsWorks to deploy applications to those servers.
      
      The other options are not suitable for deploying applications to on-premises servers:
      
      Elastic Beanstalk is a service for deploying and scaling web applications and services on AWS resources, such as EC2 instances. It does not support deploying applications to on-premises servers.
      
      AWS Batch is a batch computing service that efficiently runs batch jobs across AWS resources, such as EC2 instances. It is not designed for deploying applications to on-premises servers.
      
      AWS X-Ray is a service that provides analytics and debugging capabilities for distributed applications. It helps developers analyze and debug production, distributed applications by collecting data about requests and responses. It does not provide deployment capabilities for on-premises servers.

    </details>

39. What is an example of agility in the AWS Cloud?
    - A. Access to multiple instance types.
    - B. Access to managed services.
    - C. Using Consolidated Billing to produce one bill.
    - D. Decreased acquisition time for new compute resources.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: D
    </details>

40. Which AWS security service protects applications from distributed denial of service attacks with always-on detection and automatic inline mitigations?
    - A. Amazon Inspector.
    - B. AWS Web Application Firewall (AWS WAF).
    - C. Elastic Load Balancing (ELB).
    - D. AWS Shield.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Explanation: AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS from DDoS attacks.Its features are:

      Always-on Detection: AWS Shield continuously monitors traffic patterns and automatically detects malicious traffic flows that could represent a DDoS attack.

      Automatic Inline Mitigations: When AWS Shield identifies a potential DDoS attack, it automatically mitigates the attack by filtering malicious traffic without any manual intervention required.

      Elastic and Scalable: AWS Shield can automatically scale to absorb and mitigate even the largest DDoS attacks, providing protection against high-traffic volume attacks.

      Protection for Web Applications and Other Resources: AWS Shield can protect various AWS resources, including Elastic Load Balancing, Amazon CloudFront, Amazon Route 53, and Elastic IP addresses, ensuring comprehensive protection for web applications and other services.
      
      Others are incorrect because:

      Amazon Inspector is a security service that helps assess and improve the security posture of applications deployed on AWS by automatically scanning for vulnerabilities and deviations from best practices.
      
      AWS WAF is a web application firewall that helps protect web applications from common web exploits and bots. While it can mitigate certain types of application-level DDoS attacks, it does not provide comprehensive DDoS protection at the network and transport levels.
      
      Elastic Load Balancing is a load balancing service that distributes incoming traffic across multiple targets, such as EC2 instances. While it can contribute to DDoS resilience by distributing traffic, it does not provide dedicated DDoS protection or automatic inline mitigations.

    </details>

41. Which of the following are advantages of AWS consolidated billing? (Choose two)
    - A. The ability to receive one bill for multiple accounts.
    - B. Service limits increasing by default in all accounts.
    - C. A fixed discount on the monthly bill.
    - D. Potential volume discounts, as usage in all accounts is combined.
    - E. The automatic extension of the master account’s AWS support plan to all accounts.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
    </details>

42. A company is considering using AWS for a self-hosted database that requires a nightly shutdown for maintenance and cost-saving purposes. Which service should the company use?
    - A. Amazon Redshift.
    - B. Amazon DynamoDB.
    - C. Amazon Elastic Compute Cloud (Amazon EC2) with Amazon EC2 instance store.
    - D. Amazon EC2 with Amazon Elastic Block Store (Amazon EBS).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

