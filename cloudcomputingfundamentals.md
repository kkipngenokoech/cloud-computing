# cloud

it is not a cloud, it is just someone's else computer.

## cloud computing

it involves delivery of it resources:

1. database - storage
2. compute power - servers and networking
3. application
4. security

over the internet.

it is like a virtual data center that can be accessed via the internet.

## characteristics of cloud computing

1. pay-as-you-go
    -pay only for what you use and there's no long term contracts.
2. serverless
   - hardware is managed by cloud provider.
3. autoscaling
    - resources shrink and grow based on demand.
    - servers can be provisioned almost immediately

## types of cloud computing

### infrastructure as a service

the cloud provider supplies the server instance, storage and user management, how you are going to manage the server i.e aws, digital ocean, rackspace, iron mountain

## platform as a service

development tools are provided and hosted on provider's infrastructure,  they manage the hardware and the OS, all you do is deploy code, i.e GoDaddy, salesforce

## software as a service

delivers software applications over the internet and this softwares are managed by the service provider, i.e google's gmail, microsoft office 365

## common cloud providers

1. amazon web services - AWS - (it has 12 months free tier)
2. google cloud platform - GCP
3. microsoft azure

## AWS

1. analytics
   - quick sight
   - athena
   - redshift
2. Application integration
   - simple queue service (SQS)
   - Simple Notification Service (SNS)
3. Cost management
   - AWS Budgets
4. Compute Services
   - Elastic Cloud Compute (EC2)
   - Lambda
   - Elastic BeanStalk
5. Database Management services
   - MySql
   - Oracle
   - SQlServer
   - DynamoDB
   - MongoDB
6. Developer tools
   - Cloud 9
   - code pipeline
7. Security Services
   - key management service(KMS)
   - Shield
   - Identity and access Management
8. Additional services
   - Blockchain
   - Machine Learning
   - Computer Vision
   - Internet of Things
   - AV/VR

## AWS REGIONS

a region is a geographic locations on a map which has availability locations

regions are isolated and independent, and don't replicate across the regions.

### availability zone

an availability zone is an isolated location within a geographical region and is a physical data center within a specific region

failures are also independent.

## shared responsibility

so aws shares a responsibility with you:

this is what aws does for you:

1. it secures edge locations
2. monitors physical device security
3. provides physical access control to hardware/software
4. database patching
5. discarding physical storage devices

this is what aws expects you to do:

1. manage aws identity and Access Management
2. encrypt your data
3. preventing and detecting when an aws account has been compromised
4. restricting access to aws services to only those users who need it.
