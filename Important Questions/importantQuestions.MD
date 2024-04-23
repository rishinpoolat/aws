# Important Questions

Click on the **Answer** button for the correct answer and its explanation.


---

1. A company is launching a new website which is expected to have highly variable levels of traffic. The website will run on Amazon EC2 and must be highly available.What is the most cost-effective approach?
    - A. Use the AWS CLI to launch and terminate Amazon EC2 instance to match demand.
    - B. Create an Amazon EC2 Auto Scaling group and configure an Elastic Load Balancer.
    - C. Determine the highest expected traffic and use an appropriate instance type.
    - D. Launch the website using an Amazon EC2 instance running on a dedicated host.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

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
      Correct Answer: B

      Explanation: AWS Elastic Beanstalk is designed to simplify the deployment and scaling of web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker. It automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring. Elastic Beanstalk provides a simple-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.
      
      Elastic Beanstalk supports the deployment of Node.js applications and offers step-by-step instructions for deploying Node.js web applications using the Elastic Beanstalk management console. It also provides walkthroughs for common tasks such as database integration and working with the Express framework .
      
      Moreover, Elastic Beanstalk automatically handles the deployment details such as capacity provisioning, load balancing, auto-scaling, and application health monitoring. It also allows for easy integration with other AWS services like Amazon RDS for database management and Amazon S3 for storage.
    </details>

3. A company is building a serverless workflow that cordinates multiple AWS services into a reliable application. They want a visual workflow that can track the status of each step in the application. Which AWS service would faciliate creating this kind of workflow?
    - A. Amazon Lambda.
    - B. AWS Step Functions.
    - C. Amazon SNS.
    - D. Amazon SQS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

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
      Correct Answer: D

      Explanation: Amazon FSx is designed to provide an easy and cost-effective way to launch, run, and scale feature-rich, high-performance file systems in the cloud. It supports a wide range of workloads with its reliability, security, scalability, and broad set of capabilities. Amazon FSx is built on the latest AWS compute, networking, and disk technologies to provide high performance and lower TCO. As a fully managed service, it handles hardware provisioning, patching, and backups, freeing you up to focus on your applications, your end users, and your business.
      
      Amazon FSx supports a broad set of enterprise Windows workloads with fully managed file storage built on Microsoft Windows Server. It has native support for Windows file system features and for the industry-standard Server Message Block (SMB) protocol to access file storage over a network. This compatibility and performance are particularly important when moving workloads that require Windows shared file storage, such as CRM, ERP, and .NET applications, as well as home .directories
    </details>

5. Which AWS service allows you to secrely share your AWS resources across AWS accounts or within your organisations, helping you to reduce operational overhead and to centrally manage access to the shared resources?
    - A. AWS Organisations.
    - B. AWS IAM.
    - C. AWS Service Catalog.
    - D. AWS Resource Access Manager(AWS RAM).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: D

      Explanation: AWS RAM simplifies the process of sharing resources across multiple AWS accounts, within your organization or organizational units (OUs), and with IAM roles and users for supported resource types. It enables you to securely share your resources across AWS accounts, streamline management of AWS resources within your organization from a central account, and reduce overhead and costs by creating resources once and sharing them across multiple accounts.
      
      AWS RAM helps in granting least privilege access to your shared resources, using managed permissions to grant only the permissions required to perform tasks on resources shared using AWS RAM. This ensures that resources shared by attaching a resource-based policy aren't visible in the same way as resources shared directly in the user's account, but instead, you have to discover and explicitly refer to the resource by its Amazon Resource Name (ARN).
    </details>

6. A company is looking to develop a conversational chatbot that can interact dynamically with its customers through a natural language interface. Which AWS service should be utilised to faciliate this?
    - A. Amazon Lex.
    - B. Amazon Transcribe.
    - C. Amazon Comprehend
    - D. Amazon Textract
    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: A
      Explanation: Amazon Lex is a service for building conversational interfaces into any application using voice and text. It provides the advanced deep learning functionalities of automatic speech recognition (ASR) for converting speech to text, and natural language understanding (NLU) to recognize the intent of the text. This enables the creation of applications with highly engaging user experiences and lifelike conversational interactions .
      
      Amazon Lex is powered by the same technology as Amazon Alexa, making it capable of understanding natural language speech and text input, recognizing the intent behind the input, and fulfilling the user intent by invoking the appropriate business function. This makes it an ideal choice for developing sophisticated, natural language chatbots into new and existing applications .
      
      Moreover, Amazon Lex simplifies the process of creating chatbots by guiding developers through the console to create their own chatbot in minutes. It requires only a few example phrases, and Amazon Lex builds a complete natural language model through which the bot can interact using voice and text to ask questions, get answers, and complete sophisticated tasks. This democratizes deep learning technologies, making them accessible to all developers.
    </details>

7.  An application has a highly dynamic usage pattern. Which characteristica of the AWS Cloud make it cost-effective for this type of workload? (Select Two)
    - A. High Availability.
    - B. Strict Security.
    - C. Elasticity.
    - D. Pay-as-you-go Pricing.
    - E. Reliability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C,D

      Explanation: C. Elasticity: The ability to easily scale resources up or down based on demand is crucial for managing costs effectively. AWS offers a variety of services and features that allow for dynamic scaling, such as Auto Scaling for EC2 instances, which adjusts the number of instances based on the demand pattern. This ensures that you only pay for the resources you need, optimizing costs by reducing resource consumption during off-peak hours.
      
      D. Pay-as-you-go Pricing: AWS's flexible pricing model, including On-Demand Instances, Savings Plans, and Spot Instances, allows you to pay for compute capacity by the hour, with no minimum commitments required. This model encourages taking advantage of AWS's flexible pricing to scale compute resources according to demand, optimizing costs by reducing resource consumption during off-peak hours. Spot Instances, in particular, offer savings of up to 90% off On-Demand pricing, making them suitable for workloads that can tolerate using a fleet of servers where individual servers can come and go dynamically.
    </details>

8.  Which AWS Service or feature helps restrict the AWS services, resorces, and individual API actions the users and roles in each member account and access?
    - A. Amazon Cognito.
    - B. AWS Organisations.
    - C. AWS Shield.
    - D. AWS Firewall Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

      Explanation: C.AWS Organizations allows you to centrally manage and enforce policies for multiple AWS accounts. It provides a feature called Service Control Policies (SCPs) that you can use to manage permissions in your organization. SCPs are a type of organization policy that you can use to restrict the actions that can be called on AWS resources. By attaching an SCP to an organizational unit (OU) or an individual account, you can specify which actions are allowed or denied on the AWS resources in that OU or account. This helps in ensuring that users and roles in each member account have the appropriate level of access to AWS services and resources.
      
      For example, you can use SCPs to prevent users in member accounts from accessing certain API operations in the identity store, as shown in the provided example SCP that explicitly blocks access to the identity store and SSO directory actions. This level of control is crucial for maintaining security and compliance across your AWS environment.
    </details>

9.  An organisation is seeking a fully managed service to create and publish interactive dashboard that can be accessed from any device. Which AWS service would be the most appropriate choice for this requirement?
    - A. AWS Redshift.
    - B. Amazon QuickSight.
    - C. AWS Glue.
    - D. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

      Explanation: Amazon QuickSight is a fast, cloud-powered business intelligence service that makes it easy to deliver insights to everyone in your organization. It allows you to create and publish interactive dashboards that can be accessed from any device, including desktops, tablets, and smartphones. QuickSight dashboards can be embedded into applications using the Amazon QuickSight JavaScript SDK, enabling a seamless integration of data visualization into your applications.
      
      The service is designed to be easy to use, requiring no technical skills to create and publish dashboards. It supports a wide range of data sources, including AWS data services like Amazon RDS, Amazon Redshift, and Amazon S3, as well as on-premises databases and other cloud-based data sources. This flexibility makes it suitable for a wide range of business intelligence and analytics needs.
    </details>

10. Which AWS service helps you continuously audit your AWS usage to simplify how you can assess risk and compliance with regulations and industry standards?
    - A. AWS Config.
    - B. AWS Trusted Advisor.
    - C. AWS Artifact.
    - D. AWS Audit Manager.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: D

      Explanation: AWS Audit Manager is designed to help you continuously audit your AWS usage, simplifying the process of assessing risk and compliance with various regulations and industry standards. It provides a centralized dashboard where you can view and manage audit activities, track compliance with internal policies and external regulations, and identify areas for improvement. AWS Audit Manager supports a wide range of compliance frameworks and standards, making it easier to demonstrate compliance and reduce the risk of non-compliance.
    </details>

11. A company is looking to centrally configure and manage firewall rules accross their AWS environment. Which AWS services can assist in applying firewall rules consistently across AWS VPCs and accounts? (Select Two)
    - A. AWS Web Application Firewall(AWS WAF).
    - B. AWS Firewall Manager.
    - C. Amazon Inspector.
    - D. AWS Network Firewall.
    - E. AWS Shield

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B,D

      Explanation: B. AWS Firewall Manager: AWS Firewall Manager allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It supports AWS Network Firewall, enabling you to manage firewall rules for your Amazon Virtual Private Cloud (VPCs) across your organization. Firewall Manager provides different firewall management models, including Distributed and Centralized, to suit various organizational needs .
      
      D. AWS Network Firewall: AWS Network Firewall is a managed service that makes it easy to deploy essential network protections for all of your Amazon Virtual Private Clouds (VPCs). It can filter traffic at the perimeter of your VPC, including filtering traffic going to and coming from an internet gateway, NAT gateway, over VPN, or AWS Direct Connect. Network Firewall is supported by AWS Firewall Manager, allowing for centralized management of firewall rules across VPCs and accounts.
    </details>
 
12. A finacial service firm wants to build a real time analytic platform where data can be streamed and analyzed on the fly. They are looking to use Apache, Kafka for this, but they want to avoid the overhead of managing the Kafka infrastuctue. Which AWS Service would be the best fit for this requirement?
    - A. Amazon SQS.
    - B. Amazon Kinesis.
    - C. Amazon MSK.
    - D. Amazon Redshift.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation: Amazon MSK (Managed Streaming for Apache Kafka) is a fully managed service that simplifies the setup, scaling, and management of Apache Kafka clusters. It allows you to build and run applications that use Apache Kafka to process streaming data without the need for Apache Kafka infrastructure management expertise. This means you can focus on developing your applications rather than managing the underlying Kafka infrastructure.
      
      Amazon MSK automatically provisions, configures, and manages the operations of your Apache Kafka cluster and Apache ZooKeeper nodes, making it easy to build and run production applications on Apache Kafka. It follows Apache Kafka’s deployment best practices, ensuring high availability, durable storage, and security of your data. Additionally, Amazon MSK Serverless is a cluster type that enables you to run Apache Kafka without having to manage and scale cluster capacity, automatically provisioning and scaling compute and storage resources as needed. 
    </details>

13. A Media company wants to find and subscribe to third party data sources to enrich their existing datasets with new insights. Which AWS service would be best fit for this requirement?
    - A. AWS Glue.
    - B. AWS Data Pipeline.
    - C. AWS Data Exchange.
    - D. AWS Redshift.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation: AWS Data Exchange allows organizations to find, subscribe to, and use third-party data in the cloud. It provides an extensive data set catalog, making it easy to discover and subscribe to over 3,500 third-party data sets. This service simplifies the process of integrating third-party data into your AWS environment, enabling you to enrich your existing datasets with new insights without the need to build bespoke data pipelines for every synchronous use case. AWS Data Exchange supports efficient data retrieval, streamlined data procurement, and simplifies governance and compliance when setting up access permissions by using AWS-native authentication . 
    </details>



14. A startup is developing a web application where users can find articles basef on various criteria such as keywords , authors, or topics, They seek an AWS service that can handle this function efficiently. Which service should they use?
    - A. Amazon OpenSearch Service.
    - B. Amazon SQS.
    - C. AWS Lambda.
    - D. Amazon EC2.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: A

      Explanation: Amazon OpenSearch Service (formerly known as Amazon Elasticsearch Service) is a fully managed service that makes it easy to deploy, secure, and run OpenSearch (formerly Elasticsearch) cost-effectively at scale. It is designed to help you secure, deploy, and run OpenSearch cost-effectively at scale. OpenSearch is a popular open-source search and analytics suite that can be used to build applications that offer search functionality, including full-text search, structured search, analytics, and more. It supports a wide range of search features such as highlighting, autocomplete, and geospatial search, making it suitable for applications like the one described . 
      
      Amazon OpenSearch Service is fully managed, meaning AWS handles the infrastructure, allowing you to focus on application development. It automatically scales your cluster's compute and storage resources based on the volume of data and search traffic, and it provides built-in security features to help protect your data.
    </details>

15. Which AWS service provides a cloud based integrated development environment(IDE) that lets you erite, run, and debug your code with just a browser, without needig to install any software or configuration server?
    - A. AWS CodeStar.
    - B. Amazon WorkSpaces.
    - C. AWS CodeBuild.
    - D. AWS Cloud9.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: D

      Explanation: AWS Cloud9 is a fully managed cloud IDE that provides a rich code-editing experience with support for several programming languages and runtime debuggers, along with a built-in terminal. It allows developers to write, run, and debug applications directly in their browser, without the need for installing or maintaining a local IDE. This service is particularly useful for developers working on AWS, as it comes prepackaged with essential tools for popular programming languages and provides a seamless experience for developing serverless applications. 
      
      AWS Cloud9 supports over 40 programming languages, including Node.js (JavaScript), Python, PHP, Ruby, Go, and C++. It includes features such as syntax highlighting, outline view, code hinting, code completion, application runners, and step-through debugging for many popular programming languages. Additionally, AWS Cloud9 environments come preinstalled with the AWS CLI, which is authenticated with the permissions of the logged-in AWS user automatically, enabling you to run interactive CLI commands against AWS services from the built-in terminal window in Cloud9 without any additional configuration .
    </details>

16. Which AWS service faciliates building secure and scalable mobile and web applications, offering features such as real-time updates and offline functionalites?(Select Two)
    - A. AWS Lambda.
    - B. AWS AppSync.
    - C. AWS Amplify.
    - D. AWS CodeDeploy.
    - E. Amazon API Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B, C

      Explanation:  B. AWS AppSync: AWS AppSync is a serverless backend for mobile, web, and enterprise applications. It makes it easy to build data-driven applications by handling securely all the application data management tasks such as online and offline data access, data synchronization, and data manipulation across multiple data sources. AWS AppSync uses GraphQL, an API query language designed to build client applications by providing an intuitive and flexible syntax for describing their data requirement. 
      
      C. AWS Amplify: AWS Amplify makes it easy to create, configure, and implement scalable mobile applications powered by AWS. It seamlessly provisions and manages your mobile backend and provides a simple framework to easily integrate your backend with your iOS, Android, Web, and React Native frontends. Amplify also automates the application release process of both your front-end and back-end, allowing you to deliver features faster. It supports offline data synchronization, storage, or data sharing across multiple users, which is crucial for mobile applications that require cloud services for actions that can’t be done directly on the device.
    </details>

17. A small buisness owner who is not tech-savvy is looking to find AWS certified experts for a short-term project. They need a service that can help them connect with professionals who can offer advice and help implement AWS solutions quickly. Which AWS Service should they use?
    - A. AWS Trainig and Certification.
    - B. AWS IQ.
    - C. AWS Support.
    - D. AWS Marketplace.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

      Explanation:  AWS IQ is designed to help businesses connect with AWS Certified third-party experts for project work. It allows organizations of any size, including small and medium-sized businesses, to quickly and securely find, engage, and pay AWS Certified experts for hands-on help. All experts on AWS IQ have active AWS Associate, Professional, or Specialty Certifications and are ready to assist with project work. AWS IQ is integrated with your AWS account and your AWS bill, allowing you to grant, monitor, and control access to your AWS Account for the experts you engage. You can also pay the expert at the conclusion of each project milestone, making it a convenient and secure way to access expert advice and help with implementing AWS solutions.
    </details>

18. Which AWS service supports an in-memory data structure store, compatible with Redis, that delivers sub-millisecond latency for use cases such as caching, session stores and real time analytics?
    - A. Amazon DynamoDB.
    - B. Amazon RDS.
    - C. Amazon MemoryDB.
    - D. Amazon RedShift.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation:  Amazon MemoryDB for Redis is a Redis-compatible, durable, in-memory database that delivers ultra-fast performance and Multi-AZ durability. It is designed to provide microsecond read latency and single-digit millisecond write latency, making it suitable for applications that require high throughput and low latency. MemoryDB stores your entire database in-memory and uses a durable, Multi-AZ transactional log, so you can use it as an ultra-fast, primary database. It is used for various purposes including user content data stores, session management, geospatial indexing, chat and message queues, real-time streaming, fraud detection, streaming IoT device data, and more.
    </details>

19. In the AWS Cloud Adoption Framework , which perspective focuses on identifying capability gaps and helping your organisation align its readliness for cloud adoption?
    - A. Envision.
    - B. Align.
    - C. Launch.
    - D. Scale.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

      Explanation:  The Align phase is crucial for identifying capability gaps across the six AWS CAF perspectives (Business, People, Governance, Platform, Security, and Operations), identifying cross-organizational dependencies, and surfacing stakeholder concerns and challenges. This phase is designed to create strategies for improving cloud readiness, ensure stakeholder alignment, and facilitate relevant organizational change management activities.
    </details>

20. Which of the following statements is correct about Amazon S3 cross-region replication?
    - A. Both source and destination S3 buckets must have versioning disabled.
    - B. The source and destination S3 buckets cannot be in different AWS Regions.
    - C. S3 buckets configured for cross-region replication can be owned by a single AWS account or by differebt accounts.
    - D. The source s3 bucket owner must have the source and destination AWS Regions disabled for their account.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation:  Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. Buckets that are configured for object replication can be owned by the same AWS account or by different accounts. You can copy objects between different AWS Regions or within the same Region.
      
      Both source and destination buckets must have versioning enabled. The source bucket owner must have the source and destination AWS Regions enabled for their account. The destination bucket owner must have the destination Region-enabled for their account.
    </details>

21. A Cloud Practitioner requires point-in-time recovery (PITR) for an Amazon DynamoDB table. Who is responsible for configuring and performing backups?
    - A. AWS is responsible for both tasks.
    - B. The customer is responsible for configuring and AWS is responsible for performing backups.
    - C. The customer is responsible for both tasks.
    - D. AWS is responsible for configuring and the user is responsible for performing backups.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: B

      Explanation:  Point-in-time recovery (PITR) provides continuous backups of your DynamoDB table data. When enabled, DynamoDB maintains incremental backups of your table for the last 35 days until you explicitly turn it off. It is a customer responsibility to enable PITR on and AWS is responsible for actually performing the backups.
    </details>

22. Under the AWS shared responsibility model, which of the following is an example of security in the AWS Cloud?
    - A. Managing edge locations.
    - B. Physical security.
    - C. Firewall configuration.
    - D. Global Infrastructure.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation:  Firewall configuration is an example of “security in the cloud”. This is the customer’s responsibility, not an AWS responsibility.
    </details>

23. A user has an AWS account with a Business-level AWS Support plan and needs assistance with handling a production service disruption Which action should the user take?
    - A. Contact the dedicated Technical Account Manager.
    - B. Contact the dedicated AWS concierge Support Team.
    - C. Open a buisness-critical system down support case.
    - D. Open a production system down support case.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: D

      Explanation:  The Business support plan provides a service level agreement (SLA) of < 1 hour for production system down support cases. 
      The dedicated TAM only comes with the Enterprise support plan.
      The concierge support team only comes with the Enterprise support plan.
      The business-critical system down support only comes with the Enterprise support plan.
    </details>

24. A company needs to publish messages to a thousands of subscribers simultaneously using a push mechanism. Which AWS service should the company use?
    - A. AWS Step Functions.
    - B. Amazon Simple Workflow Service (SWF).
    - C. Amazon Simple Notification Service (Amazon SNS).
    - D. Amazon Simple Queue Service (Amazon SQS).


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation:  Amazon SNS is a publisher/subscriber notification service that uses a push mechanism to publish messages to multiple subscribers. Amazon SNS enables you to send messages or notifications directly to users with SMS text messages to over 200 countries, mobile push on Apple, Android, and other platforms or email (SMTP).
      SQS is a message queue service used for decoupling applications.
      SWF is a workflow orchestration service, not a messaging service.
      AWS Step Functions is a serverless workflow orchestration service for modern applications.
    </details>

25. AWS are able to continue to reduce their pricing due to:?
    - A. Pay-as-you-go pricing.
    - B. AWS global infrastructure.
    - C. Economies of Scale.
    - D. Reserved instance pricing.


    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct Answer: C

      Explanation:  By using cloud computing, you can achieve a lower variable cost than you can get on your own. Because usage from hundreds of thousands of customers is aggregated in the cloud, providers such as AWS can achieve higher economies of scale, which translates into lower pay as-you-go prices.
      The global infrastructure is the basis of the AWS platform but it is not the reason prices continue to reduce.
      This pricing model is a benefit but not the reason unit prices are reducing.
      "Reserved instance pricing" is incorrect. This pricing model results in savings for customers in specific areas but not the reason for the overall reduction in prices.
    </details>