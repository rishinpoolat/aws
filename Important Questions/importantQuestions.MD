# Important Questions

Click on the **Answer** button for the correct answer and its explanation.



---

1. A company is launching a new website which is expected to have highly variable levels of traffic. The website will run on Amazon EC2 and must be highly available.What is the most cost-effective approach?
    - A. Use the AWS CLI to launch and terminate Amazon EC2 instance to match demand.
    - B. Create an Amazon EC2 Auto Scaling group and configure an Elastic Load Balancer.
    - C. Determine the highest expected traffic and use an appropriate instance type.
    - D. Launch the website using an Amazon EC2 instance running on a dedicated host.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Explanation: Using an auto scaling group allows you to automatically scale the number of EC2 instances based on traffic demand. This ensures that you have enough instances to handle high traffic periods while scaling down during low traffic periods, optimizing costs.

      Configuring an Elastic Load Balancer (ELB) distributes incoming traffic across multiple EC2 instances within the auto scaling group, ensuring high availability and fault tolerance. It also automatically routes traffic away from unhealthy instances, enhancing reliability.

      This approach dynamically adjusts resources based on demand, providing the necessary scalability and availability without manual intervention or over-provisioning of resources.

      Options A, C, and D involve manual intervention or static configurations, which may not efficiently handle highly variable traffic or provide the required high availability without incurring unnecessary costs. 

    </details>

2. User has limited knowledge of AWS Services, but wants to quickly deploy a scalable Node.js application in an Amazon VPC? Which service should be used to deploy the application?
    - A. AWS CloudFormation.
    - B. AWS Elastic Beanstalk.
    - C. Amazon EC2.
    - D. Amazon LightSail.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Explanation: AWS Elastic Beanstalk is designed to simplify the deployment and scaling of web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker. It automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring. Elastic Beanstalk provides a simple-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.
      
      Elastic Beanstalk supports the deployment of Node.js applications and offers step-by-step instructions for deploying Node.js web applications using the Elastic Beanstalk management console. It also provides walkthroughs for common tasks such as database integration and working with the Express framework .
      
      Moreover, Elastic Beanstalk automatically handles the deployment details such as capacity provisioning, load balancing, auto-scaling, and application health monitoring. It also allows for easy integration with other AWS services like Amazon RDS for database management and Amazon S3 for storage
    </details>

3. A company is building a serverless workflow that cordinates multiple AWS services into a reliable application. They want a visual workflow that can track the status of each step in the application. Which AWS service would faciliate creating this kind of workflow?
    - A. Amazon Lambda.
    - B. AWS Step Functions.
    - C. Amazon SNS.
    - D. Amazon SQS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Explanation: AWS Step Functions is a serverless workflow service that allows you to orchestrate AWS services into serverless workflows. It provides a visual interface for designing workflows, making it easier to create, visualize, and manage complex workflows. With Step Functions, you can define your workflows as state machines, which transform complex code into easy-to-understand statements and diagrams. This makes building and confirming that your application is implementing the desired functionality quicker and easier.
      
      Step Functions maintains the state of your application during execution, including tracking what step of execution it is in, and storing data that is moving between the steps of your workflow. This means you don't have to manage state yourself with data stores or by building complex state management into all of your tasks .
      
      Moreover, Step Functions offers real-time diagnostics and dashboards, integrates with Amazon CloudWatch and AWS CloudTrail, and logs every execution, including overall state, failed steps, inputs, and outputs. This allows for quick identification of issues and troubleshooting . 
    </details>

4. Which AWS Service provides fully managed third-party file systems, with native compatability and a rich feature set, to be used with a board range of AWS Services?
    - A. Amazon Elastic File System(EFS).
    - B. AWS Storage Gateway.
    - C. Amazon Simple Storage Service(S3).
    - D. Amazon FSx

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Explanation: Amazon FSx is designed to provide an easy and cost-effective way to launch, run, and scale feature-rich, high-performance file systems in the cloud. It supports a wide range of workloads with its reliability, security, scalability, and broad set of capabilities. Amazon FSx is built on the latest AWS compute, networking, and disk technologies to provide high performance and lower TCO. As a fully managed service, it handles hardware provisioning, patching, and backups, freeing you up to focus on your applications, your end users, and your business.
      
      Amazon FSx supports a broad set of enterprise Windows workloads with fully managed file storage built on Microsoft Windows Server. It has native support for Windows file system features and for the industry-standard Server Message Block (SMB) protocol to access file storage over a network. This compatibility and performance are particularly important when moving workloads that require Windows shared file storage, such as CRM, ERP, and .NET applications, as well as home directories
    </details>

5. Which AWS service allows you to secrely share your AWS resources across AWS accounts or within your organisations, helping you to reduce operational overhead and to centrally manage access to the shared resources?
    - A. AWS Organisations.
    - B. AWS IAM.
    - C. AWS Service Catalog.
    - D. AWS Resource Access Manager(AWS RAM).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Explanation: AWS RAM simplifies the process of sharing resources across multiple AWS accounts, within your organization or organizational units (OUs), and with IAM roles and users for supported resource types. It enables you to securely share your resources across AWS accounts, streamline management of AWS resources within your organization from a central account, and reduce overhead and costs by creating resources once and sharing them across multiple accounts.
      
      AWS RAM helps in granting least privilege access to your shared resources, using managed permissions to grant only the permissions required to perform tasks on resources shared using AWS RAM. This ensures that resources shared by attaching a resource-based policy aren't visible in the same way as resources shared directly in the user's account, but instead, you have to discover and explicitly refer to the resource by its Amazon Resource Name (ARN)
    </details>

6. A company is looking to develop a conversational chatbot that can interact dynamically with its customers through a natural language interface. Which AWS service should be utilised to faciliate this?
    - A. Amazon Lex.
    - B. Amazon Transcribe.
    - C. Amazon Comprehend
    - D. Amazon Textract
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
      Explanation: Amazon Lex is a service for building conversational interfaces into any application using voice and text. It provides the advanced deep learning functionalities of automatic speech recognition (ASR) for converting speech to text, and natural language understanding (NLU) to recognize the intent of the text. This enables the creation of applications with highly engaging user experiences and lifelike conversational interactions .
      
      Amazon Lex is powered by the same technology as Amazon Alexa, making it capable of understanding natural language speech and text input, recognizing the intent behind the input, and fulfilling the user intent by invoking the appropriate business function. This makes it an ideal choice for developing sophisticated, natural language chatbots into new and existing applications .
      
      Moreover, Amazon Lex simplifies the process of creating chatbots by guiding developers through the console to create their own chatbot in minutes. It requires only a few example phrases, and Amazon Lex builds a complete natural language model through which the bot can interact using voice and text to ask questions, get answers, and complete sophisticated tasks. This democratizes deep learning technologies, making them accessible to all developers
    </details>

7.  An application has a highly dynamic usage pattern. Which characteristica of the AWS Cloud make it cost-effective for this type of workload? (Select Two)
    - A. High Availability.
    - B. Strict Security.
    - C. Elasticity.
    - D. Pay-as-you-go Pricing.
    - E. Reliability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C,D

      Explanation: C. Elasticity: The ability to easily scale resources up or down based on demand is crucial for managing costs effectively. AWS offers a variety of services and features that allow for dynamic scaling, such as Auto Scaling for EC2 instances, which adjusts the number of instances based on the demand pattern. This ensures that you only pay for the resources you need, optimizing costs by reducing resource consumption during off-peak hours.
      
      D. Pay-as-you-go Pricing: AWS's flexible pricing model, including On-Demand Instances, Savings Plans, and Spot Instances, allows you to pay for compute capacity by the hour, with no minimum commitments required. This model encourages taking advantage of AWS's flexible pricing to scale compute resources according to demand, optimizing costs by reducing resource consumption during off-peak hours. Spot Instances, in particular, offer savings of up to 90% off On-Demand pricing, making them suitable for workloads that can tolerate using a fleet of servers where individual servers can come and go dynamically
    </details>

8.  Which AWS Service or feature helps restrict the AWS services, resorces, and individual API actions the users and roles in each member account and access?
    - A. Amazon Cognito.
    - B. AWS Organisations.
    - C. AWS Shield.
    - D. AWS Firewall Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Explanation: C.AWS Organizations allows you to centrally manage and enforce policies for multiple AWS accounts. It provides a feature called Service Control Policies (SCPs) that you can use to manage permissions in your organization. SCPs are a type of organization policy that you can use to restrict the actions that can be called on AWS resources. By attaching an SCP to an organizational unit (OU) or an individual account, you can specify which actions are allowed or denied on the AWS resources in that OU or account. This helps in ensuring that users and roles in each member account have the appropriate level of access to AWS services and resources.
      
      For example, you can use SCPs to prevent users in member accounts from accessing certain API operations in the identity store, as shown in the provided example SCP that explicitly blocks access to the identity store and SSO directory actions. This level of control is crucial for maintaining security and compliance across your AWS environment
    </details>

9.  An organisation is seeking a fully managed service to create and publish interactive dashboard that can be accessed from any device. Which AWS service would be the most appropriate choice for this requirement?
    - A. AWS Redshift.
    - B. Amazon QuickSight.
    - C. AWS Glue.
    - D. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B

      Explanation: Amazon QuickSight is a fast, cloud-powered business intelligence service that makes it easy to deliver insights to everyone in your organization. It allows you to create and publish interactive dashboards that can be accessed from any device, including desktops, tablets, and smartphones. QuickSight dashboards can be embedded into applications using the Amazon QuickSight JavaScript SDK, enabling a seamless integration of data visualization into your applications.
      
      The service is designed to be easy to use, requiring no technical skills to create and publish dashboards. It supports a wide range of data sources, including AWS data services like Amazon RDS, Amazon Redshift, and Amazon S3, as well as on-premises databases and other cloud-based data sources. This flexibility makes it suitable for a wide range of business intelligence and analytics needs
    </details>

10. Which AWS service helps you continuously audit your AWS usage to simplify how you can assess risk and compliance with regulations and industry standards?
    - A. AWS Config.
    - B. AWS Trusted Advisor.
    - C. AWS Artifact.
    - D. AWS Audit Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D

      Explanation: AWS Audit Manager is designed to help you continuously audit your AWS usage, simplifying the process of assessing risk and compliance with various regulations and industry standards. It provides a centralized dashboard where you can view and manage audit activities, track compliance with internal policies and external regulations, and identify areas for improvement. AWS Audit Manager supports a wide range of compliance frameworks and standards, making it easier to demonstrate compliance and reduce the risk of non-compliance.
    </details>

11. A company is looking to centrally configure and manage firewall rules accross their AWS environment. Which AWS services can assist in applying firewall rules consistently across AWS VPCs and accounts? (Select Two)
    - A. AWS Web Application Firewall(AWS WAF).
    - B. AWS Firewall Manager.
    - C. Amazon Inspector.
    - D. AWS Network Firewall.
    - E. AWS Shield

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B,D

      Explanation: B. AWS Firewall Manager: AWS Firewall Manager allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It supports AWS Network Firewall, enabling you to manage firewall rules for your Amazon Virtual Private Cloud (VPCs) across your organization. Firewall Manager provides different firewall management models, including Distributed and Centralized, to suit various organizational needs .
      
      D. AWS Network Firewall: AWS Network Firewall is a managed service that makes it easy to deploy essential network protections for all of your Amazon Virtual Private Clouds (VPCs). It can filter traffic at the perimeter of your VPC, including filtering traffic going to and coming from an internet gateway, NAT gateway, over VPN, or AWS Direct Connect. Network Firewall is supported by AWS Firewall Manager, allowing for centralized management of firewall rules across VPCs and accounts
    </details>
 


11.  A company is looking to centrally configure and manage firewall rules accross their AWS environment. Which AWS services can assist in applying firewall rules consistently across AWS VPCs and accounts? (Select Two)
    - A. AWS Web Application Firewall(AWS WAF).
    - B. AWS Firewall Manager.
    - C. Amazon Inspector.
    - D. AWS Network Firewall.
    - E. AWS Shield
 
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D

      Explanation: B. AWS Firewall Manager: AWS Firewall Manager allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It supports AWS Network Firewall, enabling you to manage firewall rules for your Amazon Virtual Private Cloud (VPCs) across your organization. Firewall Manager provides different firewall management models, including Distributed and Centralized, to suit various organizational needs .
      
      D. AWS Network Firewall: AWS Network Firewall is a managed service that makes it easy to deploy essential network protections for all of your Amazon Virtual Private Clouds (VPCs). It can filter traffic at the perimeter of your VPC, including filtering traffic going to and coming from an internet gateway, NAT gateway, over VPN, or AWS Direct Connect. Network Firewall is supported by AWS Firewall Manager, allowing for centralized management of firewall rules across VPCs and accounts
    </details>

 

12.   A finacial service firm wants to build a real time analytic platform where data can be streamed and analyzed on the fly. They are looking to use Apache, Kafka for this, but they want to avoid the overhead of managing the Kafka infrastuctue. Which AWS Service would be the best fit for this requirement.
    - A. Amazon SQS.
    - B. Amazon Kinesis.
    - C. Amazon MSK.
    - D. Amazon Redshift.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C

      Explanation: Amazon MSK (Managed Streaming for Apache Kafka) is a fully managed service that simplifies the setup, scaling, and management of Apache Kafka clusters. It allows you to build and run applications that use Apache Kafka to process streaming data without the need for Apache Kafka infrastructure management expertise. This means you can focus on developing your applications rather than managing the underlying Kafka infrastructure.
      
      Amazon MSK automatically provisions, configures, and manages the operations of your Apache Kafka cluster and Apache ZooKeeper nodes, making it easy to build and run production applications on Apache Kafka. It follows Apache Kafka’s deployment best practices, ensuring high availability, durable storage, and security of your data. Additionally, Amazon MSK Serverless is a cluster type that enables you to run Apache Kafka without having to manage and scale cluster capacity, automatically provisioning and scaling compute and storage resources as needed 
    </details>