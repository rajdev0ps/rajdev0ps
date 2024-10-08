
## About Me
# Raj DevOps - Multi-Cloud Architect

  With a decade of experience in IT, I am a Multi-Cloud Architect with deep expertise in various cloud platforms and DevOps practices. My proficiency allows me to design and implement robust, scalable solutions 
  tailored to modern needs. I specialize in crafting sophisticated cloud architectures and modernizing applications

#### Technical Skills:
 - **Amazon Web Services(AWS)**
 - **Microsoft Azure**
 - **Terraform**
 - **Cloud Migration**
 - **Cloud Security**
 - **Cloud Cost Optimization**
 - **Azure Devops/Jenkins(CI-CD)**
 - **Python Automation**

 For any inquiries or collaborations, please contact me at www.linkedin.com/in/raj-deolekar

### Projects

1. Onpremise to Cloud Migration (Lift & Shift Approach) >> Later Scope modified to (Application Assessment)

    Migrated over 70 applications and 400+ Windows/Linux servers to AWS Cloud using AWS Server Migration Service.

   - Architecture overview
      ![Landing zone overview](projects/cloud-migration/architecture.jpeg)  
      
   - Account structure
      ![Account structure](projects/cloud-migration/organizations-units.jpeg)
      
   - IP Subnets & Availablity zones
      ![IP Subnets & Availablity zones](projects/cloud-migration/network-ip.PNG) 

  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------
       
2. AWS Backup Validation Solution
   
    Developed a customized AWS Backup Validation Solution that clones AWS VPC components and EC2 instances with the same attributes (NAME, IP, Subnet, Security Groups etc) using AWS Lambda, SQS, IAM roles, and   
    CloudFormation templates. This solution can be deployed across multiple accounts and regions using CloudFormation StackSets. As a result, customers achieved a significant reduction in manual validation time 
    and increased accuracy in DR drills.
 
    - Architecture
      ![Architecture](projects/cloud-migration/backup-validation.png)

    - Workflow
      ![Workflow](projects/cloud-migration/workflow.png)
      
    - UserInputfile-sample
      ![Workflow](projects/cloud-migration/BV-Userinputfile.jpg)

    - DB Workflow
      ![DB Workflow](projects/cloud-migration/bckp-6.png)

    - Step 1
      ![Step 1](projects/cloud-migration/bckp-1.png)
     
    - Step 2
      ![Step 2](projects/cloud-migration/bckp-2.png)

    - Step 3
      ![Step 3](projects/cloud-migration/bckp-3.png)

    - Step 4
      ![Step 4](projects/cloud-migration/bckp-4.png)

    - Step 5
      ![Step 5](projects/cloud-migration/bckp-5.png)
      
  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦---------------------------------------------------------------

3. Kubernetes EKS and AKS Architecture
   
     - AWS EKS Delievery Pipeline state
      ![EKS](projects/cloud-migration/aws-eks.jpg)

     - Azure AKS Delievery Pipeline state
      ![AKS](projects/cloud-migration/azure-aks.jpg)

     - How to do Helm based Deployments via ADO

            1. Checkout to your branch:
            	git checkout -b <your-branch-name>
            
            2. Pull the latest changes from the master/main branch to your local branch:
            	git pull origin master
            
            3. Navigate to the application folder and update values.yaml , chart.yaml
            	imageName or image tag and appVersion and version
        
            4. Push changes to repository
            	git add .
            	git commit -m "your message"
            	git push
   
            5. Create a Pull Request and once it is approved pipeline get trigger for that particular application
            
            6. Monitor the Azure DevOps Pipeline for any errors.

  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------  
          

4. Internal Mutli-Cloud Inventory
   
     Created an internal website for cloud inventory management across AWS and Azure, providing real-time infrastructure insights accessible to both technical and non-technical users. With further integration of      PowerAutomate, added features include real-time inventory fetching and customized downloads based on various filters and tags.
   
     **Benefits**
     - *Reduced the need for DevOps teams to log into each account to fetch inventory or get the status of VMs.*
     - *Allowed application teams to view and fetch the current inventory without DevOps team involvement.*
     - *This solution was developed in response to a recent Microsoft outage.*

      ![Internal Mutli-Cloud Inventory](projects/cloud-migration/cloud-inventory.png)
    
  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------

5. Hybrid Cloud DR Architecture (AWS & Azure)
   
      The purpose of this engagement is to assess, consult, design, and perform activities that will enable the customer to host Disaster Recovery or a secondary datacenter for these applications and databases 
      on Amazon AWS.
    
      ![Hybrid Cloud DR Architecture](projects/cloud-migration/Cloud-Endure.jpg)
    
    
      ![Cloud-Endure Setup](projects/cloud-migration/Cloud-Endure-2.jpg)

      **Steps of AZURE to AWS Failover activity**

        1) Created a Default Project for Failover activity and Installed the CloudEndure Agent on Application(VM ScaleSet) server and on LNT-PRD-DB01 server and it started the replication on CloudEndure console.
        2) Configure the Blueprint for the server’s.
        3) Once the CloudEndure console shows “Continuous Data Replication”, we have started the Failover of servers one by one.
        4) Select the server and click on “Recovery Mode”, Sever is created on AWS with the same configuration mentioned on Blueprint.
        5) X team has tested the server one by one and checked the application and database and changed the DNS pointer to AWS Server.
        6) X team has checked all the servers and pointed the DNS to AWS Sever and shutdown the Azure servers. All the workload of the application got migrated to AWS servers.

  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------

6. Appstream Solution Architecture (AWS & Azure)
   
      Designed and deployed AppStream 2.0 as a SaaS solution for an internal application that collects sensitive biomedical data. This implementation replatformed Company X's legacy application to AWS Cloud on 
      AppStream 2.0 for over 200 users.
    
      ![Appstream](projects/cloud-migration/appstream.JPG)

  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------

7. Fresh AWS 3 Tier Account setup for Insurance Company
   
      Designed the AWS account structure and network architecture, including on-premises VPN connectivity. Implemented configurations for root account, security, shared services, production, and non-production 
      landing zones.
    
      ![MultiAccount](projects/cloud-migration/fresh-acct.jpg)

  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------

8. AWS Landscape for AEM Application this was before Transit gateway launch.
   
      Designed the AWS account structure and network architecture for AEM applications.
    
      ![AEM](projects/cloud-migration/aem-trans.jpg)


  ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦-------------------------------------------------------------

9. AWS Multi-Environment Infra provisioning via Terraform and CI-CD  [THIS IS NOT REAL WORLD EXAMPLE THIS LEARNING FROM UDEMY]
   
      The setup below demonstrates the deployment of DEV and STAGE AWS infrastructure via CI/CD using Terraform as Infrastructure as Code (IaC).
   
      ![terraform](projects/cloud-migration/terraform-on-aws-3.jpg)

      ![terraform2](projects/cloud-migration/terraform-on-aws.jpg)

      ![terraform3](projects/cloud-migration/terraform-on-aws-2.jpg)

      ![CI-CD](projects/cloud-migration/CI-CD-Pipeline.jpg)
   
      - Synk Software Composition Analysis
      ![Synk](projects/cloud-migration/Synk_Analysis.jpg)

      ![Synk-2](projects/cloud-migration/Synk_Analysis.2.jpg)

      - Checkov Infrastructure Scanning Tool
      ![Checkov](projects/cloud-migration/checkov-SCA-SAST.jpg)

      - Infracost Finosp-Governance-Cost Analysis for Terraform

      ![Infrac-1](projects/cloud-migration/Infrarcost-1.jpg)

      ![Infrac-1](projects/cloud-migration/Infrarcost-2.jpg)

      ![Infracost-1](projects/cloud-migration/Infrarcost-cost.jpg)

      ![Infracost-2](projects/cloud-migration/Infrarcost-finops.jpg)

      ![Infracost-3](projects/cloud-migration/Infrarcost-finops-tagging.jpg)

   ----------------------------------------------------✦✦✦--✦✦✦--✦✦✦------------------------------------------------------------- 
 
