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

