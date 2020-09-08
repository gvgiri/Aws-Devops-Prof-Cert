# Hands on Practice for AWS DevOps Pro Certification


# Create an Org with multiple accounts 
### Apply a specific policy to an OU
### Note 

<details><summary>show</summary>
<p>

```bash
#Solution here.....
```
</p>
</details>


# CloudFormation
### Create VPC, 2 Subnets, 1 IGW,  1 NAT Gateway, Route Tables, 2 Security Groups, 2 EC2 Instances, S3 bucket (1 Stack)
### Crete 2 EC2 Instances  
### Create S3 bucket (1 Stack)
#### Variations: Nested Stacks: Passing on informtion to calling stack, Dedicated Hosts(EC2)

<details><summary>show</summary>
<p>

```bash
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/GettingStarted.Walkthrough.html

# Perform ECS blue/green deployments through CodeDeploy using AWS CloudFormation
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/blue-green.html
# Custom Resources - AWS Lambda-backed custom resources
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-custom-resources-lambda.html
```
</p>
</details>


# CodeCommit
## Junior Devlopers are not allowed to update master brach
## 
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>

# CodeDeploy
## Deploying to EC2
## Deploying to Serverless
## Deploying to Containers
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# CodePipeline
## Deploying to EC2
## Deploying to Serverless
## Deploying to Containers
## Jenkins Integrations
### Note 

<details><summary>show</summary>
<p>

```bash
https://docs.aws.amazon.com/codepipeline/latest/userguide/tutorials.html 
https://aws.amazon.com/blogs/devops/implementing-gitflow-using-aws-codepipeline-aws-codecommit-aws-codebuild-and-aws-codedeploy/

```
</p>
</details>


# CloudWatch Events - Automation
## Sub-Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>

# CloudTrail
## Reciving CloudTrail log files from Multiple AWS Accounts
## Integrity validation -digest file delivered every one hr
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>

# AWS Kinesis  
## Firehose
### Create and configure AWS Firehose to send data to S3 - use AWS dummy data  

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>

# CloudWatch 
## Metrics and creating alarms
### Alarm response action only SNS notification and ASG, For EC2 - restart, reccover, termiate etc
### Events - rules - Alarms are not valid source
### Install Unified Agent on EC2 instance and enable log collection for Apache, other custom apps installed on EC2 instance. Then save the configuration to SSM, and resuse the configuration to other EC2 instances.

<details><summary>show</summary>
<p>

```bash
< 1 min. 03 hours.  <-- custom metric
1 minute 15 days
5 minute 63 days
1 hour   15 months
```
</p>
</details>

# CloudWatch 
## Custom Metric
### Create a custom metric 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>

# CloudWatch 
## Export Metric to S3
### Note 

<details><summary>show</summary>
<p>

```bash
aws cloudwatch get-metric.....check the syntax

CloudWatch event to AWS Lambda
```
</p>
</details>

# CloudWatch 
## Logs
#### Export logs from Ec2(apache) to cloudwatch logs
#### create a metric filter and Alarm on CW-logs - example 404 error
#### Export CW-logs to S3 using subscription method
#### Other export log streams are Kinesis streams, data firehose, Lambda , ElasticSearch
### Note 

<details><summary>show</summary>
<p>

```bash
```
</p>
</details>

# CloudWatch - Events
## CW-Event - CloudTrail - API calls integration 
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>

# AWS X-Ray
### Sample Application install 
CloudWatch , SNS to notify wehen X-ray detcts elevated levels of latency

https://aws.amazon.com/blogs/devops/using-amazon-cloudwatch-and-amazon-sns-to-notify-when-aws-x-ray-detects-elevated-levels-of-latency-errors-and-faults-in-your-application/
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# AWS SSM Manager
## Hybrid environemtn setup
## Task Automation
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# AutoScaling
## Saling policies
## ALB, application slow start support
## Enable https on ALB
### Suspending and resuming scaling polcies
* suspended processes
### Cooldown period,  
## lifecycle Hooks
* Lambda enent test case 
## Termination policy
## Integrating SQS with ASG
* protectig instances from terminatiob vy auto scaling
## monitoring & notifications
## ASG CloudFormation creation policy
## ASG  cloudFormation, codeDeploy usecase


<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# DynamoDB Tables
## Tables, primary key, sort key, LSI, GSI, RCU, WCU computations, DAX
## DynamoDB Streams, Lambda function
## Global Tables, replication
## TTL -- go to epoch converter , Manage TTL
## DynamoDB patterns
* S3 metadata Index
* ElasticSearch
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# S3
## Events, Replication, lifecycle policy, S3 Encryption, Glacier, 
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Multi AZ, Multi region 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# CloudFormation StackSets
# Multi-Region Deployments - codeDeploy, codedeploy,cloudformation -- follow blog


<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# DR
## RTO, RPO
## backup and restore -- high RPO
## pilot light 
## warm standby
## Multi Site / Hot Site Approacg - (very low RTO, very expensive

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# DR DevOps CheckList 
## 
## EFS Backup, EFS to EFS Backup
## Backups and Multi-Region DR
## Elastic Beanstack Backups
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# On Premise Strategy with AWS
# AWS Organizations
## mutlti account strategies, multi account vs one account with multi vpc
## OU, Service control polocies(SCP)
## Moving accounts
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


# Template 
## Sub Heading
### Note 

<details><summary>show</summary>
<p>

```bash
Solution here.....
```
</p>
</details>


