# AWS-EC2
Getting Started with Amazon EC2

•	Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.

•	Amazon EC2 offers the broadest and deepest compute platform with choice of processor, storage, networking, operating system, and purchase model. 
Familiarize Yourself with EC2 Instances

STEP 1:Log Into Your AWS Account

Log into the AWS Management Console and set up your root account. If you don’t already have an account, you will be prompted to create one.
With the AWS free tier, you can get 750 hours/month of select EC2 instances for free.

STEP 2:Launch Your Instance

Identify which instance type is best for your workload. For your first instance, we recommend a low cost, general purpose instance type: t2.micro, and Amazon Machine Image (AMI): Amazon Linux 2 AMI, which are both free-tier eligible.
Open the Amazon EC2 dashboard and choose “Launch Instance” to create your virtual machine.

STEP 3:Configure Your Instance

Here are some guidelines when setting up your first instance:

•	Security group: Create your own firewall rules or select the default VPC security group.

•	Storage: EC2 offers both magnetic disk and SSD storage. We recommend EBS gp2 volumes to start out with.

•	Choose "Launch Instances" to complete the set up.

* Note: We will use the key pair file (.pem) later.

STEP 4:Connect to Your Instance

After launching your instance, you can connect to it and use it the way you'd use a computer sitting in front of you. There are several ways to connect to the console depending on the operating system. We recommend using EC2 Instance Connect, an easy to use browser based client.

•	Select the EC2 instance you created and choose "Connect.“

•	Select “EC2 Instance Connect.”

•	Choose “Connect”. A window opens, and you are connected to your instance.

STEP 5:Terminate Your Instance

Amazon EC2 is free to start (learn more), but it is important that you terminate your instances to prevent additional charges. The EC2 instance and the data associated will be deleted.

Select the EC2 instance, choose "Actions", select "Instance State", and "Terminate".
________________________________________
 storage, tools that allow your application to scale based on demand, and fault-tolerant workloads for up to 90% off.
