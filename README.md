# Create AWS account with two different EC2 instances. Development and production

## Overview

I this i am going to create a AWS account with two instance one for development which helps for development in any organization and second is for production where any user can access the service.


## AWS Account:
  To create AWS account we have to follow the steps.
- **Sreps:**
 1. Goto the url : https://us-east-1.console.aws.amazon.com/
 2. Click one: create new account and fille the details and verify.
    ![Screenshot from 2024-01-13 15-10-18](https://github.com/ashirvadpandey/two_instances/assets/72142699/68146306-a8e3-4b0c-9cf9-1f52ac5496d0)
 3. Fill the details for account verification.
    Congratulations your account has been created

## AWS Instances

### Development Instance

- **Instance Type:** Amazon linux
- **AMI:** Amazon Linux 2023 AMI
- **Security Groups:** awseb-e-eaueinjt4k-stack-AWSEBSecurityGroup-18H2QMSU0ZQHHsg-035f5d4d2e2120453
- **Access:**
1.Open an SSH client.

2.Locate your private key file. The key used to launch this instance is helo_world.pem

2.Run this command, if necessary, to ensure your key is not publicly viewable.
     chmod 400 "development.pem"

2.Connect to your instance using its Public DNS:
     ec2-54-173-139-100.compute-1.amazonaws.com
- **Screenshot:**
![Screenshot from 2024-01-13 14-59-17](https://github.com/ashirvadpandey/two_instances/assets/72142699/8190b358-5548-496f-aa10-7c9676e2000d)



### Production Instance

- **Instance Type:** Amazon linux
- **AMI:** Amazon Linux 2023 AMI
- **Security Groups:** awseb-e-eaueinjt4k-stack-AWSEBSecurityGroup-18H2QMSU0ZQHHsg-035f5d4d2e2120453
- **Access:**
1.Open an SSH client.

2.Locate your private key file. The key used to launch this instance is helo_world.pem

2.Run this command, if necessary, to ensure your key is not publicly viewable.
     chmod 400 "production.pem"

2.Connect to your instance using its Public DNS:
     ec2-3-227-8-232.compute-1.amazonaws.com
- **Screenshot:**
  ![image](https://github.com/ashirvadpandey/two_instances/assets/72142699/ff5905d6-35bb-4cc6-a166-09e21aed45c8)
