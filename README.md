# Ex.2 Cloud Storage Creation (S3) and Launching an EC2 Instance in AWS

## NAME: SWETHA A
## REG NO: 212223220114

### Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

### Procedure

a) Steps to Create a First S3 Bucket
Sign in to AWS Management Console

Go to: https://console.aws.amazon.com/s3
Open the S3 Service

Search for S3 in the search bar and open it.
Create Bucket

Click the Create bucket button.
Configure Bucket Settings

Bucket name: Choose a globally unique name.
AWS Region: Select the region where you want to store your data.
Object Ownership

Choose:
ACLs disabled (recommended) — Bucket owner has full control.
ACLs enabled — Control access via access control lists.
Block Public Access Settings

By default, public access is blocked. Leave it as-is unless you need public access.
Bucket Versioning (Optional)

Choose whether to enable versioning for objects in the bucket.
Encryption (Optional)

Select encryption options: SSE-S3, SSE-KMS, or none.
Advanced Settings (Optional)

Add tags, configure logging, etc.
Create the Bucket

Click Create bucket at the bottom of the page.
b) Steps to Launch an EC2 Instance
Go to the EC2 Dashboard in AWS Console.
Click on Launch Instance.
Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
Select an Instance Type (e.g., t2.micro for Free Tier).
Create or Choose a Key Pair for SSH access.
Configure Network Settings (use default VPC/subnet).
Configure Storage (default root volume is fine).
Review and Launch
Review settings and click Launch Instance.
Wait for the instance to enter the running state.

c) Connect to Your EC2 Instance
Linux Users: Use SSH command with your .pem key.
Windows Users: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)
Go to EC2 Instances.
Select your instance → Instance State → Terminate.

### Snapshots

Snap Shot 1: Simple Storage Service (S3)
image

![Screenshot 2025-05-22 132557](https://github.com/user-attachments/assets/194ebd0b-8f62-4ae4-8628-6d5a21118a0d)


Snap Shot 2: EC2 (Elastic Compute Cloud) – Instance
image

![image](https://github.com/user-attachments/assets/a168a876-f929-4f5f-af0b-ce000522ba85)



Result
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.
