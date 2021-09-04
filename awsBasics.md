**Amazon Web Services - AWS**


**Compute domain**

- EC2 - Elastic Compute Cloud : Infrastructure as service
    - raw server
    - select RAM, PROCESSOR, OS etc..
    - You can install any software, complete control
    - It can be any server like web server, database server
    - We can increase/decrease size of components easily

- Elastic Beanstalk : Platform as a service
    - A web application server
    - Pre-installed software, cannot upload/install new software
    - Tailored version of EC2 - so more automation & less control

- AWS Lambda : Serverless compute service
    - Run code without managing servers
    - More automation than Elastic Beanstalk

-  Elastic load balancer
    - Distributes incoming network traffic across multiple targets

- AWS Auto Scaling
    - Automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost

- Amazon Elastic Container Registry(ECR)
    - Fully-managed docker container registry
    - To store, manage and deploy docker container images

- Amazon Elastic Container Service(ECS)
    - Container orchestration service
    - Run and scale containerized applications


**Storage domain**

- Amazon Simple Storage Service(S3 bucket)
    - Object storage service
    - Scalable, 99.9% high availability & performance
 
- Amazon S3 Glacier
    - Secure, durable, extremely low-cost cloud storage service
    - Long-term backup
    - Takes time to create & retrieve data
    - Mostly for archiving data

- Amazon Elastic File System(EFS)
    - Like a network drive
    - Simple, scalable, elastic file system

- AWS Storage Gateway
    - Data security features between your on-premise IT environment and AWS storage infrastructure


**Database domain**

- Amazon Relational Database Service(RDS)
    - MySQl, Oracle, SQL Server, PostgreSQL etc.

- Amazon DynamoDB
    - Key-value document based database

- Amazon Redshift
    - Data warehouse service

- Amazon Elasticache
    - Cache servers


**Security domain**

- AWS Identity and Access Management(IAM)
    - Manage access to AWS services and resources securely

- AWS Key Management Service(KMS)
    - Create and manage keys and control the use of encryption across AWS services and applications


AWS Services - Management domain

- AWS CloudFormation
    - Provides a common language to describe and provision all the infrastructure resources in your cloud environment
    - We can write Architecture templates in Json format

- AWS OpsWorks
    - Configuration management service that provides managed instances
    - Chef and Puppet automation platforms

- AWS CloudTrail
    - Logging service
    - Monitoring

- AWS CloudWatch
    - Monitoring service
    - Can trigger alarm(eg. email) by monitoring resources/services


**AWS Services - Customer Engagement domain**

- Amazon Connect
    - Ready to deploy customer contact centre
    - IVR calls to agents

- Simple Email Service(SES)
    - Cloud-based email sending service
    - Marketing email, transactional emails

**
AWS Services - Application Integration domain**

- Amazon Simple Notification Service(SNS)
    - Pub/sub messaging services

- Amazon Simple Queue Service(SQS)
    - Fully managed message queuing service


**AWS Pricing models**

- Pay-as-you-go
    - Pay for what you use
- Save when you reserve
    - Reserve for long time, get discounted price
- Pay less by using more
- Spot pricing

