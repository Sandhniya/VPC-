Ex 4 Deployment and configuration of a Private Cloud in AWS
```
NAME: ANUBHARATHI SS
REG NO: 212223040017
Aim:
To set up of a Private Cloud in AWS.
Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.
```

```
Procedure:
Plan Your VPC:
● Determine your needs: ● Determine your needs: 

Define your use case, including application requirements, security needs, and compliance standards.
● Plan IP address ranges:
● Plan IP address ranges:

Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:

Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.
● Plan internet connectivity: ● Plan internet connectivity: 

Determine if you need public internet access and how to configure it.
● Define security: ● Define security: 

Plan your security groups, network ACLs, and access controls to ensure a secure environment.
Create Your VPC:
• Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources.

Deploying Resources:
• Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

Managing and Monitoring:
• Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

```

Output:

<img width="726" height="434" alt="image" src="https://github.com/user-attachments/assets/2f845e07-f148-4627-b88c-c39d59f83cc5" />

<img width="725" height="361" alt="image" src="https://github.com/user-attachments/assets/b4b71a57-2810-49ce-8254-16db6b15c695" />

<img width="733" height="416" alt="image" src="https://github.com/user-attachments/assets/cdfea737-a065-4b53-a52b-775aeb68ce16" />
<img width="745" height="360" alt="image" src="https://github.com/user-attachments/assets/0c998304-6a90-44b3-abdb-9d242ea8fa11" />
<img width="641" height="442" alt="image" src="https://github.com/user-attachments/assets/66ca9e03-bb17-4dcd-92f8-79181ea05281" />
<img width="733" height="383" alt="image" src="https://github.com/user-attachments/assets/7b548440-0ca0-4bf5-ae78-6fae68523c39" />
<img width="747" height="405" alt="image" src="https://github.com/user-attachments/assets/89bfc2e0-4382-440a-b6ec-3fe81d53bbce" />
<img width="730" height="454" alt="image" src="https://github.com/user-attachments/assets/74753be1-14ac-43db-bf65-722b1e85be11" />
<img width="733" height="369" alt="image" src="https://github.com/user-attachments/assets/43b5669a-8185-40b4-bf12-b8e102f03291" />
<img width="833" height="410" alt="image" src="https://github.com/user-attachments/assets/13adb67e-b9ea-4260-8951-316e37b51672" />
Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.




