# Azure-DP-900

## Cloud Computing :cloud: 
It is the delivery of computing services over the internet. The services include are as follows  <br> 
:zap:Server  <br> 
:zap:storage  <br> 
:zap:database  <br> 
:zap:networking  <br> 
:zap:software  <br> 
:zap:analytics  <br> 
:zap:intelligence  <br> 
Cloud computing offers faster innovation, flexible resources and economies of scales.  <br>  




## Cloud Advantages :cloud:
:small_orange_diamond: Trade “capital expense” for “variable expense”  <br> 
:small_orange_diamond: Benefit from massive economies of scale  <br> 
:small_orange_diamond: Stop guessing capacity  <br> 
:small_orange_diamond: Stop spending money running and maintaining data centers  <br> 
:small_orange_diamond: Go global in minutes  <br> 
:small_orange_diamond: High availability : If one of the regions is down, you can serve the application from the other regions <br> 
:small_orange_diamond: Low latency : Serve users from the nearest region to them <br> 
:small_orange_diamond: Global footprint <br> 
:small_orange_diamond: Adhere to government regulation <br> 


## Benefits of Cloud  :cloud: 
:small_blue_diamond:  **High Availability** — The major cloud providers (Azure, AWS, GCP) have multiple data centers spread around throughout the world. Data and code stored in the cloud are copied to more than one data center. If anything happens to one data center, the data can be recovered from another data center.  <br> 
:small_blue_diamond: **Fault Tolerance** — In case there is any fault in the application or infrastructure, the service can continue to work by moving the work to other healthy servers.  <br> 
:small_blue_diamond: **Disaster Discover** — The data in the cloud can also get copied to other regions e.g. copy data from West US to East US. If there is natural disaster happened in West US and every data center goes down, the data center in East US will still have the copy of data.  <br> 
:small_blue_diamond: **Scalability** — The application running in the cloud can expand its size when there are more users in the system.  <br> 
:small_blue_diamond: **Elasticity** — The application running in the cloud can shrink its size when there are fewer users in the system. The users can also set automatic shutdown during the non-business hours to save money.  <br> 

## Availability Zones :cloud: 
Availability zones consists of one or more discrete data center. Each availability has independent & redundant power, networking & connectivity. It should also be noted that availability zones in a region are connected through low-latency links.


## Business benefits of cloud  :cloud: 
:small_blue_diamond: **Agility** - The machines in the cloud are ready for cloud users to fire when they need and power down when they are not required  <br> 

:small_blue_diamond: **Economies of scale** — Cloud is a shared pool of machines and services. As the number of customer grows, the cloud providers can cut down the cost and at same time increase quality of the services  <br> 

:small_blue_diamond: **Capital Expenditure (CapEx) vs Operational Expenditure (OpEx)** — Building a data center requires large capital investment for hardware as well as the facility. A data center will also require ongoing electricity and staffs cost for operation. By using cloud, the capital expenditure for building a data center is not required.  <br> 

:small_blue_diamond: **Consumption-based model (pay-as-you-go)** — The cloud users only need to pay what they use.  <br> 


## Types of Cloud Service Offering  :cloud: 

:large_blue_diamond: **IaaS (Infrastructure as a service)** - In this offering, cloud user will only use Infrastructure from cloud provider will be responsible for 
Virtualization, Hardware & Networking while cloud user will be responsible for os Upgrades and Patches, Database Software and Upgrades, Database Configuration( Table, 
Indexes, Views etc),Data, Scaling of Compute& Storage, Availability and Durability. <br> 

:large_blue_diamond: **PaaS (Platform as a service)** In this offering as compared to above Cloud provider is responsible for Virtualization, Hardware & Networking,
 Database Software and Upgrades,Scaling,Availability and Durability. Cloud User Will be responsible for Database Configuration( Table, 
Indexes, Views etc),Data. Example Azure SQL Database, Azure Cosmos DB etc.  <br> 

:large_blue_diamond: **SaaS (Software as a service)** In this offering cloud provider will be responsible for OS (Inc Upgrades & Patches), Application Runtime, Auto Scaling, Availability and Load balancing, Application code & Configuration. Cloud User will be responsible for Configuring the Software. <br> 

## Cloud Models  :cloud: 

:small_blue_diamond: **Public cloud** Public cloud is cloud computing that’s delivered via the internet and shared across organizations. <br> 

:small_blue_diamond: **Private cloud** Private cloud is cloud computing that is dedicated solely to your organization. <br> 

:small_blue_diamond: **Hybrid cloud** Hybrid cloud is an environment that uses both public and private clouds.. <br> 

## Cloud Pricing  :cloud: 

:small_blue_diamond: **Pay as you go** -  User can pay for the services on Azure according to actual usage, billed per second, with no long-term commitment or upfront payments. This provides complete flexibility to increase or decrease resources as needed. Azure virtual machines (VMs) can be automatically scaled up and down using Azure's autoscaling features. 

:small_blue_diamond: **Reserved Instance** - Azure provides Reserved Virtual Machine Instances (RVMI) - Virtual machines that are pre-purchased for one or three years in a specific region. Committing to reserved instances in advance grant a discount of up to 72% compared to pay-as-you-go prices. Azure provides the option to replace reserved instances with others during the commitment term. It also allows users to cancel reserved instances before the end of the term, but this incurs an early termination fee.

:small_blue_diamond: **Spot Pricing** - Azure lets you buy unused computing power at a discount of up to 90% compared to pay-as-you-go prices. However, Spot instances can be interrupted on short notice, so they are considered to be suitable only for workloads that can tolerate disruptions. Azure provides Virtual Machine Scale Sets (VMSS), an autoscaling mechanism that lets you manage groups of VMs and add spot instances automatically according to predefined policies.

## Data Formats 
There are generally 3 types of Data Structure, which as follows below
1. **Structured Data** <br> 
      -Tables <br> 
       - Rows and Columns (Relational Table) <br> 
         - Example(mysql, mssql server) <br> 
2. **Semi-Structured Data** <br> 
      -Key-Value <br> 
       - Document(JSON) <br> 
        - Graph  <br> 
         - Example(Mongodb) <br> 
 3. **UnStructured Data** <br> 
      -Video <br> 
       - Audio <br> 
        - Image  <br> 
         - Text & Binary Files) <br> 

**Depending on the data structure, the data is stored in Relational database, NoSql database, Analytical database, Object/Block/File Storage** <br> 

**shared responsibility model** :on:

All the CSPs (Amazon web services(AWS),Microsoft Azure, Google Cloud Platform (GCP)) adhere and applies the shared responsibility model. The responsibility of the CSPs is to monitor and respond to the security threat related to the cloud itself and an underlying infrastructure. At the same time, Cloud User are supposed to protect the data and guard the asserts stored in the Cloud. <br>

Technically, The Shared Responsibility Model is a security and compliance framework that outlines the responsibilities of cloud service providers (CSPs) and customers for securing every aspect of the cloud environment, including hardware, infrastructure, endpoints, data, configurations, settings, operating system (OS), network
controls and access rights. <br>


**consumption-based mode** :chart:

Consumption based mode in cloud is relatively a new approach to add economical & cost visibility to the Users. We oftenly see this mode in Electical & Utility billing system. The CSPs track & monitor the resources utilized and bills them & most common term used by CSPs are as below <br>
-pay-as-you-go billing <br>
-metered billing <br>
-usage-based pricing <br>

*It should be noted that PaaS & IaaS often use consumption pricing to maintain cost advantage and profitability* <br>


## Azure Core architecture & Services :heavy_plus_sign:

1. **Regional** - When you deploy the resource in the cloud, you were asked on which region to deploy the resources. In simple term, Region is a geographical location that contain atleast one or multiple datacenter that are nearby and grouped together with a low-latency network. <br>
2. **Regional Pairs** - In an unpredicted event like natural disasters, civil unrest, power outages, or physical network outages the services can be interrupted. Therefore in order to reduce the likeihood of the distuptions, Most azure region are paired with another region within the same geography ((such as the US, Europe, or Asia) at least 300 miles away, this method allow for the replication of the resources across geography. Examples of region pairs in Azure are West US paired
with East US and South-East Asia paired with East Asia. Because the pair of regions are directly connected and far enough apart to be isolated from regional disasters,
you can use them to provide reliable services and data redundancy  <br>
3. **Sovereign regions** - Sovereign regions are instances of azure that are isolated from the main instance of Azure. Sovereign regions are used for compliance or legal purposes. Example US DoD Central, US Gov Virginia,China East, China North  <br> 

## Azure Resources & the Resources group :link:

1. **Resource** - Resource is the basic building block of Azure. Anything you create, provision, deploy etc is the resource. VMs, Virtual networks, databases, cognitive services are all considered resources within Azure.  <br> 
2. **Resource Group** - Resource Group is like a shopping cart made of different item & grouped together. It simply means grouping of resources. When you create a resource, you’re required to place it into a resource group. A resource group can be single resources or multiple resources. A point to be noted, a resource group cannot be nested into another resource group eg. group A cannot be placed inside group B. <br> 

## Relational Database 
:small_blue_diamond: - Relational Database consistes of two types, OLTP (Online Transaction processing system ) and OLAP ( Online analytical processing) <br> 
:small_blue_diamond: - Example of OLTP databases is SQL Database, Azure Postgresql, Example of OLAP databases is Synapse analytics <br> 
:small_blue_diamond: - OLTP db use row storage which is efficient for processing small transactions whereas OLAP use columnar storage which executes single queries across mulltiple nodes helps in executing efficently complex queries. <br> 

## Semi Structured Data
:small_blue_diamond: - Data has some structure but uniformed. Semi-Structured data is stored in NoSQL databases & it has flexible schema.  <br> 
:small_blue_diamond: - Azure cosmos DB is preferred services for Semi Structured data.  <br> 
:small_blue_diamond: - Services for semi structure are as follows Document(Azure Cosmos DB SQL API & MondoDB API), Key- Value(Azure Cosmos DB Table API, Azure Table storage), Graph (Azure Cosmos DB Gremlin API), Column Family( Azure Cosmos DB Cassandra API)  <br> 

## Un-Structured Data
:small_blue_diamond: - Unstructured data doesn't have any structure like Audiofile, Videofile, Binary files  <br>
:small_blue_diamond: - Block Storage(Azure Disk), File Storage(Azure Files), Object Storage(Azure Blob Storage)  <br>


## Azure SQL Database- Purchase Model 

**VCore-based**
-Choose between provisioned or serverless compute <br>
- Higher compute, memory, I/O and storage limits <br>
- Supports BYOL <br>
- Serverless compute Database is paused during inactive periods (You'll be billed for storage during inactive periods) <br>

**DTU-based**
-Bundled compute and storage packages <br>
-Assign DTUs(relative-Double Resources) <br>
-Recommended for small and medium size db <br>


## Azure SQL Managed Instance

-It is Fully Managed Service for MS-SQL & has hundred percent compatibility for SQL-Server <br>
- Azure sql managed instance is recommended when migrating on premise SQL Server to Azure <br>
-Avaialble with Vcore purchase model  <br>

*It should be noted that Azure SQL Database doesn't have Cross-database Queries,transaction within SQL Server Instance, Database Mail & SQL Agent & Native Virtual Network support* <br>

*SSAS, SSRS, Polybase are not supported in both SQL Database & SQL Managed Instance* <br>

## Azure Cosmos DB
- It's Fully Managed NoSQL Database Service <br>
- It Automatically replicates data across multiple Azure region <br>
- It has feature of automatic scaling, Serverless compute & storage, multi-region write <br>
- Data can be transferred to any region of choice <br>
- On Azure Portal, Click on Azure Cosmos DB, Databases, Container <br>

## Azure Cosmos DB- Logical and Physical Partitions
- Each container is horizontally partitioned in an Azure region & it's is distributed to all Azure region associated with the Cosmos DB account <br>
- Items in a container is divided into logical partitions based on Partition Key <br>
- Cosmos DB take care of Categorizing logical partitions into physical partitions <br>

## Azure Storage
Below are list of Core Storage Services: <br>
1. **Azure Disks** -  Block Storage(hard disks) for Azure VMs <br>
2. **Azure Files** - File Share for Cloud and On-Premises  <br>
3. **Azure Blobs** - Object store for text and binary data  <br>
4. **Azure Queues** - Decouple application using messaging  <br>
5. **Azure Tables** - NoSQL store  <br>

*Except Azure Disk, all the remaining services require storage account*  <br>

## Data Redundancy Options within Azure Storage 
1. **LRS (Locally redundant storage)** - It is least expensive and three synchronous copies in same datacenter  <br>
2. **ZRS (Zone-redundant storage)**  - Three synchronous copies in three AZs in the primary region  <br> 
3. **GRS (Geo-redundant storage)** - LRS + Asynchronous copy to secondary region(three more copies using LRS) <br>
4. **GRS (Geo-Zone-redundant storage)** - ZRS + Asynchronous copy to secondary region(three more copies using LRS) <br>

## Categories within Data Analysis 
1. **Descriptive Analytics** - What's happening ?, based on historical/Current Data, monitor status (of KPIs) and generate alert ex: Generate report <br>
2. **Diagnostic Analytics** - Why is something happening ?, Take finding from descriptive analytics and dig deeper ex: why did sales dip last month ? <br>
3. **Predictive Analytics** - What will happen ?, Predict probability based on historical data, mitigate risk & identify opportiunities Ex: Forecast demand sales <br>














