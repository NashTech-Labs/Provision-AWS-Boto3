# **How to Provision AWS Services from Boto3**

### What is Boto3

Boto3 is the Amazon Web Services (AWS) Software Development Kit (SDK) for Python which is maintained and published by Amazon Web Services. Boto3 allows Python developers to write software that makes use of services like Amazon S3 and Amazon EC2 as well as provision AWS Services from Boto3. It is complicated in many ways but it is a rich SDK for AWS.

# Provision AWS ECS and ECR from Boto3
### Prerequisites:

1) AWS IAM User

2) AWS CLI

3) Installation of Python and Boto3 on local.

### Script for provisioning ECS and ECR

Now we will write scripts for ECS, ECR, and IAM Role, Policies creation python script and two scripts that call these scripts in a single click for provisioning these AWS resources as well as deletion of these resources.

First, we write a script for provisioning AWS ECR with the name ecr.py. 

Creation of ECR Repo:

Now, we will write a script for the rest of AWS Resources same as ECR

Provisioning AWS ECS

In the ECS script, we are creating two things 

1) ECS Cluster

2) Task definition

Script for IAM role and policy creation.

Now, we will write Script for Values.

For the creation of AWS resources

Deletion of AWS resources

### Configure basic settings that the AWS CLI uses to interact with AWS as well as profile creation.

```
aws configure --profile boto3-aws

```
```
AWS ACCESS_KEY_ID={your_access_key_id}
AWS SECRET_KEY_ID={your_secret_key_id}

```
Now you can use this command to run your files.

```
RUN: python create_aws_resources.py


```


