# What-is-Platform-Engineering-and-how-it-fits-into-DevOps-and-Cloud-world

https://www.youtube.com/watch?v=ghzsBm8vOms

https://raw.githubusercontent.com/RodrigoMvs123/What-is-Platform-Engineering-and-how-it-fits-into-DevOps-and-Cloud-world/main/README.md

Platform Engineering

AWS
Kubernetes
Jenkins

Change Rules
DevOps
SRE
Cloud

What is Platform Engineering ?
Why was there a need for it ?
How does it compare to DevOps ?
How does it compare to Cloud ?

Why the need for a new rule?

Issue in traditional and DevOps teams

Problems with traditional way of work
Developers - Program the App
Operations workers - Deploy the App
Dev and Ops siloed departments
Dedicated operations teams for whole organization
Consistency across organization ( But inflexible and slow process )
Operations team waiting on developers to fix something in the application that affect the deployment or the application run time etc.

Devops solved issues in traditionals teams
Traditional teams with DevOps teams
Dev and Ops working together 
Less communication challenges 
Developing the application and running and operating the application 

1 DevOps team owns the application 
App - Application
Kubernetes - Runtime
Infrastructure 
Fast and flexible 

Team of Developers A
Team of Dedicated DevOps engineering 
CI/CD ( Creating the pipelines ) 
Writing Terraform scripts for ( Infrastructure code ) 
Speeding up kubernetes Cluster 
Configuring Log and Monitoring
Editing Security Scans     
Maintenance ( as tools envolve and new versions come out )
Managing Docker Repositories 
App - Develop Application 
Team of Developers B
App - Develop Application B
Same CI/CD workflow
Setup and Managed Kubernetes ( k8s ) Cluster
Configure all integrations with AWS Cloud 
Configure the Storage 
Security Scanning Steps
Monitoring all of secret management 

Same challenges and needs for their application
App Team A
GitLab
Hashi Korp Nomad
Terraform
Microsoft Azure

App Team B
Jenkins 
Amazon EKS
Pulumi 
Aws

Kubernetes Expert
Cloud Expert
Security Expert
Compliance Expert

Hard to scale

Infrastructure 
       Set up K8s Cluster
              Set up CI/CD Server
                     Add Security Checks 
                            …
Missing expert knowledged
Bugs

One Security, Compliance need to work with all those teams and tech stack ( Hard To help ) 


Inconsistency Across Organization
Team A      Team B       Team C            Team D   Team E                Team F
Terraform    Terraform   Google Cloud   Jenkins   Microsoft Azure   GitHub
Consul         AWS          Pulumi              AWS       Jenkins                HashiCorp Nomad 
GitLab         Istio            Fluentd             Istio
 
Google Cloud - Kubernetes - Infrastructure
AWS - Kubernetes - Infrastructure
Microsoft Azure - Kubernetes - Infrastructure
Expert frontend engineer should configure Kubernetes Cluster?

Autonomous DevOps Team
Fast and Flexible
Too Much Responsibility
High Cognitive Load
Inconsistencies 

Traditional Team
Infrastructure Managed and Secured
Slow, Inefficient Process
Limitations for Developers

Platform Engineering 
Standardize Usage of Tools
How does platform engineering solve the problem ? 

Platform Engineers 
Take tools for deploy and run the application ( Standardize the usage of tools ) 
Standardize “non-functional” requirements 
For Team A or Team B and so on 
Standardized CI/CD Solution
Standardized Kubernetes Solution
…

Non-Functional Requirements 
What are the non-functional requirements for delivering the app to the end users ?
App 
Version Control System ( VCS )
CI/CD
Run
Provision
Observe 
Secure
Connect
…

Separation of Responsibilities 
Tools:
GitLab
Kubernetes
Jenkins
Cloud Platforms
Databases
Admin                                          Users 
Operations                                   Usage
Set up and Maintenance 
Backups
Access
Secure
Plugins

Kubernetes Cluster
Provisioning 
Network
Access - Security
Permissions - Security
Loadbalancer - Cluster

Self-Sufficient DevOps teams do both
Individual app teams decide on how to operate

Platform teams takes over admin side
Operations ( Selecting the Standardized Tools )
                   ( Set up with best practices ) 

Less Workload for App Teams 
Less Cognitive Load

Platform 
Default 
Developer Teams - AWS
                             - Kubernetes
                             - Jenkins  

How do teams access these services ?

Self-Service Platform 
Google Cloud
Kubernetes MySQL
User friendly interface ( UI, API )

Platform ( IDP ) 
Internal Developer Platform
Interface for Interaction 
Provisioned, secured services
Platform as a Service ( PaaS ) - For internal developers 
Platform Engineers build the IDP - Abstracting away the complexity 

In place to log into AWS Cloud ( EKS ) 
They use the K  ( AKS ) - Platform ( IDP Internal Developer Platform )
Flexible and Fast 
No operations work

Platform Engineers
Keep the platform flexible
Freedom of choice         Team A 
GitLab                 circleci  ( no limitation )
Circleci
Set up and configure with best practices 
Integrate into the platform

Consistency Across Organization
Flexibility with Infrastructure as a Code

Freedom in tool Selection
Flexibility in usage of the Tool

Infrastructure as Code Templates
Configuration as Code Templates
Backed in best practices configurations
Keep flexibility

Product Team ( Python ) 
Pipeline as a Code ( Platform ) 
Python 
Jenkins 
Security, Compliance steps already pre-configured 

Implement Concept Successfully 

How to approach implementing the IDP ( Internal Developer Platform ) 

Agile approach 
Small steps that immediately add value 

Hard to Migrate ( Platform Engineer ) 
If Developers are Using:
Outdated Technologies 
Old Versions  
So,
Consider product team´s status quo
Help then slowly move to the platform

Treat IDP ( Internal Developer Platform ) as a Product 
Platform as a Service
Developed over time
Continuous improvements 
Developers 
App
Develop the Application

Platform Engineers 
Develop the platform

Developers 
New features, bug fixes
Improvements…
 
Platform Engineers 
Manage, update versions of services
Add new services… 
Developing an internal platform ( IDP ) 
            App v1.0, App v2.0, App v3.0… ( Develop an app one feature at a time )
Identify common Tools ( Platform Engineer ) 
Jenkins 
GitLab
Kubernetes…

Building trusting relationship with app teams
Facilitating instead of blocking 
Clear responsibility
Tools and technologies 

Internal Developer Platform 
Use pre-configured services via IDP
Best practices backed into it 
VCS
CI
Repository
Run 
Connect
Secure
Provision 

Platform versus DevOps

Platform team taking over operations 
            Set up and operate the cluster 
            How to create terraform modules for infrastructure
            CI/CD template from the platform

App teams using tools and integrate 
How to deploy the apps 
Create correctly configured manifest files 
How to use the IaC modules
Extend the pipeline for app specific configurations 

Platform Engineer 
Cloud
Kubernetes
Monitoring 
Security
Compliance
Development 

Developers 
Using instead of operating 
More focused work

Platform Engineer
Do DevOps and Cloud Engineering tasks 
Move DevOps Engineers from the product teams and form separate platform team
Developers doing DevOps work in App teams

You need a DevOps process for both !
Application DevPos Team
Platform DevOps Team

Platform versus Cloud Engineer

Cloud Engineers
Cloud Migrations
Set up hybrid cloud infrastructure
Storage and backup in cloud
Monitor cloud costs
Map company needs and requirements to cloud set up ( Cloud Infrastructure )
Expert for Cloud Services
AWS
Google Cloud
Microsoft Azure

Platform Engineer
Wide range of knowledge 
Self-service platform for internal team 
Platform as a Service



