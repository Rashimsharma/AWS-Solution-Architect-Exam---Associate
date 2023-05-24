# AWS-Solution-Architect-Exam---Associate

Course Outline
CHAPTER 1: Introduction

CHAPTER 2: AWS Fundamentals
The Building Blocks of AWS: Availability Zones and Regions
Compute, Storage, Databases, and Networking
What Is the Well-Architected Framework?

CHAPTER 3
Identity and Access Management (IAM)
Securing the Root Account
Controlling Users' Actions with IAM Policy Documents
Permanent IAM Credentials
IAM Exam Tips
HANDS-ON LABCreate and Assume Roles in AWS
HANDS-ON LAB: Introduction to AWS Identity and Access Management (IAM)

CHAPTER 4
Simple Storage Service (S3)
S3 Overview
Securing Your Bucket with S3 Block Public Access
Hosting a Static Website Using S3
Versioning Objects in S3
S3 Storage Classes
Lifecycle Management with S3
S3 Object Lock and Glacier Vault Lock
Encrypting S3 Objects
Optimizing S3 Performance
Backing up Data With S3 Replication
HANDS-ON LAB: Set Up Cross-Region S3 Bucket Replication
HANDS-ON LAB: Create a Static Website Using Amazon S3
HANDS-ON LAB: Creating Amazon S3 Buckets, Managing Objects, and Enabling Versioning

CHAPTER 5
Elastic Compute Cloud (EC2)
EC2 Overview
Demo: Launching an EC2 Instance
AWS Command Line
Using Roles
Security Groups and Bootstrap Scripts
EC2 Metadata and User Data
Networking with EC2
Optimizing with EC2 Placement Groups
Solving Licensing Issues with Dedicated Hosts
Timing Workloads with Spot Instances and Spot Fleets
Deploying vCenter in AWS with VMware Cloud on AWS
Extending AWS Beyond the Cloud with AWS Outposts
EC2 Exam Tips
HANDS-ON LAB: EC2 Instance Bootstrapping
HANDS-ON LAB: Using EC2 Roles and Instance Profiles in AWS


CHAPTER 6
Elastic Block Storage (EBS) and Elastic File System (EFS)
EBS Overview
Volumes and Snapshots
Protecting EBS Volumes with Encryption
EC2 Hibernation
EFS Overview
FSx Overview
Amazon Machine Images: EBS vs. Instance Store
AWS Backup
HANDS-ON LAB Reduce Storage Costs with EFS

CHAPTER 7
Databases
Relational Database Service (RDS) Overview
Increasing Read Performance with Read Replicas
What Is Amazon Aurora?
DynamoDB Overview
When Do We Use DynamoDB Transactions?
Saving Your Data with DynamoDB Backups
Taking Your Data Global with DynamoDB Streams and Global Tables
Operating MongoDB-Compatible Databases in Amazon DocumentDB
Running Apache Cassandra Workloads with Amazon Keyspaces
Implementing Graph Databases Using Amazon Neptune
Leveraging Amazon Quantum Ledger Database (Amazon QLDB) for Ledger Databases
Analyzing Time-Series Data with Amazon Timestream
Databases Exam Tips
HANDS-ON LAB: Set Up a WordPress Site Using EC2 and RDS

CHAPTER 8
Virtual Private Cloud (VPC) Networking
VPC Overview
Demo: Provisioning a VPC - Part 1
Demo: Provisioning a VPC - Part 2
Using NAT Gateways for Internet Access
Protecting Your Resources with Security Groups
Controlling Subnet Traffic with Network ACLs
Private Communication Using VPC Endpoints
Building Solutions across VPCs with Peering
Network Privacy with AWS PrivateLink
Securing Your Network with VPN CloudHub
Connecting On-Premises with Direct Connect
Simplifying Networks with Transit Gateway
5G Networking with AWS Wavelength
VPC Networking Exam Tips
HANDS-ON LAB: Build Solutions across VPCs with Peering

CHAPTER 9
Route 53
Route 53 Overview
Register a Domain Name
Demo: Using a Simple Routing Policy
Demo: Using a Weighted Routing Policy
Demo: Using a Failover Routing Policy
Demo: Using a Geolocation Routing Policy
Demo: Using a Geoproximity Routing Policy
Demo: Using a Latency Routing Policy
Demo: Using a Multivalue Answer Routing Policy

CHAPTER 10
Elastic Load Balancing (ELB)
ELB Overview
Using Application Load Balancers
Extreme Performance with Network Load Balancers
Using the Classic Load Balancer
Getting "Stuck" with Sticky Sessions
Leaving the Load Balancer with Deregistration Delay
HANDS-ON LAB Use Application Load Balancers for Web Servers

CHAPTER 11
Monitoring
CloudWatch Overview
Application Monitoring with CloudWatch Logs
Monitoring with Amazon Managed Service for Prometheus and Amazon Managed Grafana
Monitoring Exam Tips
HANDS-ON LAB:Implement Advanced CloudWatch Monitoring for a Web Server
HANDS-ON LAB:Work with AWS VPC Flow Logs for Network Monitoring


CHAPTER 12
High Availability and Scaling
Horizontal vs. Vertical Scaling Overview
What Are Launch Templates and Launch Configurations?
Scaling EC2 Instances with Auto Scaling
Diving Deeper into Auto Scaling Policies
Scaling Relational Databases
Scaling Non-Relational Databases

CHAPTER 13
Decoupling Workflows
Decoupling Workflows Overview
Messaging with SQS
Sidelining Messages with Dead-Letter Queues
Ordered Messages with SQS FIFO
Delivering Messages with SNS
Fronting Applications with API Gateway
Executing Batch Workloads Using AWS Batch
Brokering Messages with Amazon MQ
Coordinating Distributed Apps with AWS Step Functions
Ingesting Data from SaaS Applications to AWS with Amazon AppFlow

CHAPTER 14
Big Data
Exploring Large Redshift Databases
Processing Data with EMR (Elastic MapReduce)
Streaming Data with Kinesis
Amazon Athena and AWS Glue
Visualizing Data with QuickSight
Moving Transformed Data Using AWS Data Pipeline
Implementing Amazon Managed Streaming for Apache Kafka (Amazon MSK)
Analyzing Data with Amazon OpenSearch Service

CHAPTER 15
Serverless Architecture
Serverless Overview
Computing with Lambda
Leveraging the AWS Serverless Application Repository
Container Overview
Running Containers in ECS or EKS
Removing Servers with Fargate
Amazon EventBridge (CloudWatch Events)
Storing Custom Docker Images in Amazon Elastic Container Registry (Amazon ECR)
Using Open-Source Kubernetes in Amazon EKS Distro
Orchestrating Containers Outside AWS Using Amazon ECS Anywhere and Amazon EKS Anywhere
Auto Scaling Databases On Demand with Amazon Aurora Serverless
Using AWS X-Ray for Application Insights
Deploying GraphQL Interfaces in AWS AppSync
Serverless Architecture Exam Tips
HANDS-ON LAB: Triggering AWS Lambda from Amazon SQS

CHAPTER 16
Security
DDoS Overview
Logging API Calls with CloudTrail
Protecting Applications with Shield
Filtering Traffic with AWS WAF
Guarding Your Network with GuardDuty
Centralizing WAF Management via AWS Firewall Manager
Monitoring S3 Buckets with Macie
Securing Operating Systems with Inspector
Managing Encryption Keys with KMS and CloudHSM
Storing Your Secrets in Secrets Manager
Storing Your Secrets in Parameter Store
Temporarily Sharing S3 Objects Using Presigned URLs or Cookies
Advanced IAM Policy Documents
AWS Certificate Manager
Auditing Continuously with AWS Audit Manager
Downloading Compliance Documents from AWS Artifact
Authenticating Access with Amazon Cognito
Analyzing Root Cause Using Amazon Detective
Protecting VPCs with AWS Network Firewall
Leveraging AWS Security Hub for Collecting Security Data
HANDS-ON LAB: Using Secrets Manager to Authenticate with an RDS Database Using Lambda

CHAPTER 17
Automation
Why Do We Automate?
CloudFormation
Elastic Beanstalk
Systems Manager
Automation Exam Tips
HANDS-ON LAB: Getting Started with CloudFormation

CHAPTER 18
Caching
Caching Overview
Global Caching with CloudFront
Caching Your Data with ElastiCache and DAX
Fixing IP Caching with Global Accelerator


CHAPTER 19
Governance
Managing Accounts with Organizations
Sharing Resources with AWS RAM
Setting Up Cross-Account Role Access
Inventory Management with AWS Config
Offloading Active Directory to Directory Service
Exploring with Cost Explorer
Using AWS Budgets
Optimizing Costs with AWS Cost and Usage Reports
Reducing Compute Spend Using Savings Plans and AWS Compute Optimizer
Auditing with Trusted Advisor
Enforcing Account Governance via AWS Control Tower
Managing Software Licenses in AWS with AWS License Manager
Monitoring Health Events in the AWS Personal Health Dashboard
Standardizing Deployments Using AWS Service Catalog and AWS Proton
Optimizing Architectures with the AWS Well-Architected Tool
HANDS-ON LAB
Using AWS Tags and Resource Groups

CHAPTER 20
Migration
Migrating Data with AWS Snow Family
Storage Gateway
AWS DataSync
AWS Transfer Family
Moving to the Cloud with Migration Hub
Migrating Workloads to AWS Using AWS Application Discovery Service or AWS Application Migration Service (AWS MGN)
Migrating Databases from On-Premises to AWS with AWS Database Migration Service (AWS DMS)
Replicating and Tracking Migrations with AWS Migration Hub and AWS Server Migration Service (AWS SMS)

CHAPTER 21
Front-End Web and Mobile
Front-End Web and Mobile Overview
Quickly Deploying Web Apps with AWS Amplify
Testing App Services Using AWS Device Farm
Engaging Customers with Amazon Pinpoint


CHAPTER 22
Machine Learning
Machine Learning Overview
Analyzing Text Using Amazon Comprehend, Amazon Kendra, and Amazon Textract
Predicting Time-Series Data Using Amazon Forecast
Protecting Accounts with Amazon Fraud Detector
Working with Text and Speech Using Amazon Polly, Amazon Transcribe, and Amazon Lex
Analyzing Images via Amazon Rekognition
Leveraging Amazon SageMaker to Train Learning Models
Translating Content into Different Languages with Amazon Translate
Machine Learning Exam Tips





