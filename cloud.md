# CLOUD COMPUTING

Cloud computing is the on-demand delivery of computing services, such as servers, storage, databases, networking, software, analytics, and more, over the Internet ("the cloud"). This offers faster innovation, flexible resources, and economies of scale with a pay-as-you-go pricing model.

The cloud computing model is a paradigm shift from the traditional computing model, where businesses need to procure the hardware, maintain, secure, and upgrade it to keep their services up and running. With the cloud computing model, operational complexity shifts from organizations to cloud vendors who operate cloud platforms. Businesses focus on delivering customer value rather than being bogged down by operational concerns.

## cloud computing deployment models

Cloud deployment model refers to the way in which cloud computing services are provided and managed over the internet

they include:

1. Public cloud
2. Hybrid cloud
3. Private cloud
4. Community cloud
5. Multi-cloud

### public

Public clouds are owned and operated by third-party cloud service providers who deliver computing resources, such as storage, computing, etc., over the Internet. With this model, cloud service providers can provide a massive capacity of resources to run workloads for many customers in a shared model. We can think of this as a utility provider such as electricity. Consumers get connections over the shared infrastructure

![public cloud](/images/publiccloud.png)

Platforms such as Microsoft Azure, Amazon Web Services, and Google Compute Platform are prime examples of public clouds.

### private

rganization uses all the resources exclusively. It's a dedicated environment for a specific organization. It is akin to a traditional model of running infrastructure. However, the latest technological advancements, such as virtualization, application management, and automation, are used to make it easier to manage operations.

Private clouds can be of two types:

1. Hosted: They are offered by a third-party cloud provider.
2. Internal private clouds: They are maintained by an organization internally.

Helion Managed Private, Microsoft Azure Stack, and Red Hat OpenShift are some of the products in the private cloud space.

### Hybrid cloud

The hybrid cloud is a mix of public and private, where some resources are hosted in the public cloud, and some continue to run on an on-premises environment. Organizations often use this model to extend their on-premises infrastructure to the cloud to take advantage of cloud offerings while maintaining their line of business applications and systems internally. This option allows organizations to keep their data within their private and internal networks that can be accessed by services running in the public cloud in a controlled and secure manner.

The hybrid cloud model comes with its complexities from an infrastructure point of view that often involves securely connecting customers' on-premises environments to cloud platforms. Azure Stack, Azure Arc, AWS Outpost, and Google Anthos are some examples of the available hybrid clouds.

### community cloud

These models apply to individual organizations. However, in the real world, we have situations where businesses working in certain sectors have common requirements. Take the example of banks. They have to meet the operational and regulatory requirements, and they apply to all banks. Now imagine each bank has to set up its cloud environment to meet all of its regulatory requirements. Though certainly doable but it's inefficient and costly. Moreover, going to the public cloud route might not be feasible for security and compliance reasons. Setting up a private cloud could be costly and out of reach for small to medium businesses.

To solve such challenges, we have a notion of community clouds. In this model, organizations partner up together to set up a cloud environment that is shared among them. They typically share similar security, privacy, performance, and compliance requirements. The cloud is set up so that all operating businesses can leverage the work rather than each business setting its practices and policies. This makes it much more efficient and cost-effective for companies.

Community clouds are used by many businesses, such as banks, health and education sectors, and even governments.

### Multi-cloud 

Multi-cloud is a strategy where businesses can use cloud services from more than one cloud service provider. It could be that a company is using the Microsoft Office 365 suite of applications and Zoom or Salesforce. However, often, in the enterprise environment, multi-cloud means running platform-as-a-service (PaaS) or infrastructure-as-a-service (IaaS) from multiple cloud service providers such as AWS, GCP, or Azure

### cloud providers

#### first tier cloud providers

1. AWS - AMAZON WEB SERVICES by Amazon
2. Microsoft Azure by Microsoft
3. GCP - Google cloud platform

#### second tier cloud providers

1. IBM cloud
2. Alibaba cloud
3. Oracle cloud
4. Tencent cloud
5. Salesforce cloud


## ways of accessing cloud services

1. using a dashboard provided by the cloud provider
2. using command prompt
3. using an API provided by the cloud provider


## cloud regions and availability zones

cloud providers normally region out their data centers into regions and availability zones.

A cloud region is a geographical location where cloud providers have data centers to host their services. Cloud regions are typically spread across different countries or continents to provide customers with localized services and reduce latency.

An availability zone is a logical data center within a cloud region. It is designed to be an isolated location with its own power, cooling, and networking infrastructure. Availability zones are designed to be fault-tolerant and provide high availability, ensuring that services can continue to operate even if one availability zone goes down.

cloud regions are the physical locations where cloud providers host their services, while availability zones are logical data centers within a region that provide high availability and disaster recovery capabilities.

## Data center

A data center is a building, a dedicated space within a building, or a group of buildings used to house computer systems and associated components, such as telecommunications and storage systems

