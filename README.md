# code-bank

###Project 

##Deploy Infrastructure as a code


###Project Overview

- Introduction to Cloudformation
- Understanding diagrams
- Infrastructure as Code (Convert Diagrams into code)
- Deploying services via Cloudfomation (aws cli)

###Prerequisite packages and tools


Version Control (Git)

Code Editor for YAML and JSON (Visual Studio Code)

Amazon Web Services account w/ (IAM user) created seperate from root user.

Github account w/ github desktop app



###Installation/set up environment


1. Create " Repository " via Github

2. Using Github desktop app " "open repository in visual studio code"

3. "_ add workspace_ " via Visual Studio Code

4. create shell Scripts (`./create.sh`) & (`./update.sh`) to deploy and update your cloudformation stack.

5. Configure AWS API user via AWS management console (set permission for **s3 read and write** access and grant **programmatic access** to get user's access key id and secret access key.

6. Open your bash terminal in VSC type  `aws configure` and configure **"aws cli"** w/ `Access Key ID` and `Secret access key`.



###Project Task's


1. Create network infrastucture ( _VPC, Subnets, routing tables, NAT gateways etc...._) using VSC editor to create a _.yml file_

2. Pass parameters to the network infrastructue via a _.json_ file.

3. Create a Server Infrastucture (_launch configuration, Elastic load balancer, and bastion host_) in VSC editor via a seperate _.yml_ file

4. Pass parameters to the Server infrastructue via a _.json_ file.

5. create cloudformation stack using `./create.sh` command in bash terminal to upload files and create cloudformation stack

6. update cloudformation stack using `./update.sh` command in bash terminal to upload updates to the created cloudformation stack

7. Check deployment status via AWS Management console `Cloudformation` interface.


###Clean-Up
