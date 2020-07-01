# containers
Containers, lxc/lxd, docker, coreos
&nbsp;
&nbsp;
### docker/  course materials at github.com/docker-production-aws
#### How to create/deploy docker applications in AWS  
#### Goals:  Deploy microservices application to production using docker/AWS
- Infrastructure as Code  
- Automated deployments  
- Deploy using Ansible and CloudFormation  
- Custom provisioning tasks using AWS Lambda (managerless tool to run apps on demand)  
- Build/deploy Lambda functions written in python  
- Secure secrets managment  
- Infrastructure lifecycle management  
- Auto scaling (up or down) ECS applications  
- Create continuous delivery pipeline  
- Test, build, publish, deploy  
&nbsp;
&nbsp;
#### Process:  
- Install Java App  
 - Install sample java app  
 - Test and build  
 - run and interact with app  
- Create docker release images  
 - Run local docker workflow  
 - workflow tooling  
- Set up AWS access using console/cmdline  
 - Set up identity access & management (IAM)  
 - Enable multi factor authentication (MFA)  
- Running Docker Apps Using ECS  
 - EC2 container service   
 - Publish to EC2 registery (ECR)  
 - Create ECS cluster, task definition and service  
- Customize ECS Container Instances  
 - Create an Amazon Machine Image (AMI)  
 - Install ECS agent and Cloudwatch Logs agent  
- Deploy AWS infrastructure using Ansible an CloudFormation  
 - Create Ansible playbooks  
 - Integrate with CloudFormation  
 - Establish shared AWS resources  
- Architecting and preparting Apps for ECS  
 - App cluster discovery on AWS  
 - Customize container startup  
 - Generate configuration files dynamically  
- Defining ECS Apps using Ansible and CloudFormation
 - Create CloudFormation stack for the app  
 - Config supporting resources (dbs, loadbalancers, etc...the end-to-end infrast)  
- Deploying ECS Apps using Ansible and CloudFormation  
 - Define ECS resources using CloudFormation  
 - Deploy app to a dev environment  
- Create CloudFormation Custom Resources  
 - CloudFormation custom resources  
 - AWS Lambda  
 - Create an ECS task runner via python  
- Manage Secrets in AWS  
 - Secrets management solution   
 - Use AWS KMS and EC2 Parameter Store  
 - Inject Secrets into containers and other resources  
- Manage ECS Infrastructure Lifecycle  
 - Lifecycle management  
 - EC2 Auto scaling lifecycle hooks  
 - Create a lifecycle hook Lambda function  
- Auto Scaling ECS Apps  
 - ECS auto scaling challenges  
 - ECS capacity management  
 - App auto scaling  
- Contin Deliv using CodePipeline
 - Create a CD pipeline  
 - CodePipeline, CodeBuild, and CloudFormation  
 - Cont deploy to dev env  
 - Deploy to production env with approval  

 









