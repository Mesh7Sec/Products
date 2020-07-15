# Mesh7 Cloud Application Security Observability (CASO) for AWS

## Install Mesh7 CASO BYOL for AWS
- [Topology](#Topology)
- [Pre-Install](#Pre-Install)
- [Install](#Install)
- [Post-Install](#Post-Install)

## Topology
![Topology](documentation/images/topology.png)

## Pre-Install
#### 1. Subscription to AWS Marketplace Mesh7 CASO BYOL offering
Please ensure that you have a valid subscription to Mesh7 CASO BYOL offering on AWS Marketplace.

#### 2. Reach out Mesh7 support to get Mesh7 License
Please send an email to Mesh7 Support at support@mesh7.com to obtain Mesh7 License.

ToDo: what info will the customer need to send to Mesh7
      Which email should be used.

## Install

#### 1. Download Mesh7 CASO CloudFormation template

#### 2. Create CloudFormation Stack

######   a. Navigate to Stacks under CloudFormation Pane, and click on ‘Create Stack’
![stack1](documentation/images/stack1.png)
######   b. Upload controller-kma-install-cft.yaml template to create a CloudFormation Stack, and click ‘Next’.
![stack2](documentation/images/stack2.png)
######   c. Give the stack a name, and enter the requested input parameters
![stack3](documentation/images/stack3.png)
![stack4](documentation/images/stack4.png)
![stack5](documentation/images/stack5.png)

######   d. Agree to create an IAM user and resources, and Click ‘Create Stack’
![stack6](documentation/images/stack6.png)
######   e. Get installation data after Stack completes successfully

## Post Install

#### Login to Mesh7 Controller

###### a. Get IP of Mesh7 Adaptor EC2 instance
![stack7](documentation/images/stack7.png)

###### a. Get domain name of Mesh7 Controller UI
![getdomain](documentation/images/get-controller-ui-domain.png)

###### b. Login to Mesh7 Controller UI
![login](documentation/images/mesh7-ui.png)


