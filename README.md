# Why Cloud computing?

Lets think about why there is a need to create something called cloud computing?

## Lets understand how normal Laptop works
Lets say we have our Laptop/Desktop machine and we are loading an Excel file of 1 MB file.

Lets first understand how this file of 1 MB loads into a Laptop/Desktop machine.


Generally, File is stored in ( Hard disk ) HDD / SDD.

Once we load the file it will be bought from HDD to RAM, Why?
- Because RAM is much faster than the storage device, which allows for quicker access to the file's content during use.

To load a file, it uses Compute engine, why? 
- To locate the file address
- To Load the data from HDD to RAM
- To respond to user interactions


A Laptop/Desktop machine has below 2 components:
1. Hardware
2. Software

### 1. Hardware
Important components
- Hard disk / SSD
- RAM
- Processor


Other hardware components include
        Network Card for internet,
        Mother board (combine all, i.e HDD, RAM & CPU),
        Power circuit,
        Cooling Fan.
### 2. Software
    Operating System

So, Just to load a file we have seen following things:

- Storage => HDD  - Storing the File
- In Memory => RAM - Storing the File (for fast operations)
- Compute => CPU Cores - Process the File

A CPU core is essentially a complete processing unit with its own arithmetic logic unit (ALU), control unit, and cache memory. A single Laptop/Desktop machine can have multiple CPU cores like dual core, quad core, octa core etc.,.

## Scenario - 01
Now, Lets consider a scenario where an excel file is to loaded that is of 2GB of size 

Laptop/Desktop Machine basic configurations:
- HDD - 1 TB
- RAM - 4 GB
- CPU Quad Core

With above configurations, 2GB file can be loaded and processed easily.

## Scenario - 02
Now, Lets consider a scenario where I need to load an excel file that is of 6GB.

Laptop/Desktop Machine basic configurations:
- HDD - 1 TB
- RAM - 4 GB
- CPU Quad Core

With RAM - 4GB cannot load a file of 6GB

So, upgrade the configurations
- HDD - 1 TB
- RAM - 8 GB
- CPU Quad Core

With above upgraded configurations, 6GB file can be loaded and processed easily, since we have upgraded RAM size from 4GB to 8GB.


## Scenario - 03

WHat if I need to process more than 10GB, 20 GB files.

So, **AGAIN** upgrade the configurations
- HDD - 1 TB
- RAM - 24 GB
- CPU Octa Core

After upgrading configurations **AGAIN** 10GB, 20GB files can be loaded and processed easily, since we have upgraded RAM size from 8GB to 24 GB.

## Scenario - 04
Let's say I want to process a 30 GB file monthly once.

Then we need to process this file 12 times a year.

Is upgrading a Laptop/Desktop Machine a good approach?

- ``obviusly not``



## Another example: Scenario of building a web application

Let's say a website needs to be built.

We need to write code to display a website using HTML, CSS, JavaScript. All these HTML files, CSS files, JavaScript files have to be stored in a computer HDD/SDD.

Lets see how a Laptop/Desktop machine needs internally:

#### Storage: 
- HardDisk (HDD) holds the website files and assets, which are read by the web server for serving to clients.

#### RAM: 
- RAM temporarily stores website files in memory to speed up processing and response times.

#### CPU Cores: 
- CPU cores actually execute the web server software, handle incoming requests, and generate responses to serve the website content to local host https://localhost.


## Scenario - 05
Lets consider this website needs to be accessible globally:
- Then Laptop/Desktop machine should always be in running state. Then below are the problems faced:

##### Problems:
        What if the Power goes down?
        What if we need to update the servers?
        What if Natural disasters happen?
        WHat if there are millions of requests per second?



Maintaining a Single machine kept running has become a problem to address emerging technologies.

So a group of Machines connected through a Network has resulted in Creation of **Data Centers**.

Organizations started setting up their own data centers or leased server spaces in data centers to host their websites and applications. This approach required purchasing and maintaining physical servers.

Only Huge Organisations use to have their own Data Centers.
But for a start-up companies they need huge investment to start and maintain their own data center.

THis was the problem addressed clearly by Amazon in early 2000's


So, Amazon started on 1994 to sell books online and then slowly they added electronics, clothing, toys, home goods, and more. 
They were experience massive growth on the e-commerce giant to support expanding online retail products.

They had built & started maintanining a massive Infrastructure with thousands of servers, storage connected.


After builting they have observed that all the servers are not getting utilised properly.
example to be added

They started Providing Infrastructure as a Service ( IAAS )


So any service offered in Cloud falls on these below basic components of computer:

1. Compute
2. In - Memory
3. Storage

Only 3 Components or combination of there 3 components are offered as Services in any cloud providers.




1. Compute:
Service provider - Amazon
Service Name - Amazon Web Services - EC2, Lambda, Batch, ECS, Fargate etc.,.

Service provider - Google
Service Name  Compute Engine, CLoud functions etc.,.

Microsoft Azure
Virtual Machines, Azure functions, Azure Batch etc.,.

2. In - Memory
AWS
Elasticache, DynamoDB Accelerator, Lambda with Provisioned Concurrency, Aurora Serverless, Managed Streaming for Kafka

Google CLoud:
Memorystore for Redis, loud Memorystore for Memcached

Microsoft Azure:
Azure Cache for Redis, Azure SQL Database In-Memory OLTP, Azure Analysis Services (In-Memory Analytics) etc.,.

3. Storage:
AWS:
AWs S3, Elastic Block Store, Elastic File System 

Google CLoud:
Google Cloud Storage, Google Persistent Disk, Google Cloud Filestore

Microsoft Azure:
Azure Blob Storage, Azure Files, Azure Disk Storage


### Advanatges of using Cloud computing:


Cloud computing offers several advantages over traditional data centers, making it an attractive choice for businesses and organizations. Here are some key advantages of cloud over traditional data centers:

Cost Savings:
Cloud computing eliminates the need for upfront capital investments in hardware, networking, and data center infrastructure. Instead, users pay for cloud services on a pay-as-you-go basis, which can be more cost-effective, especially for smaller businesses or startups.

Scalability and Flexibility:
Cloud services can quickly scale up or down based on demand, allowing businesses to easily adapt to changing needs. This scalability is often challenging and expensive to achieve in traditional data centers.

High Availability and Redundancy:
Cloud providers offer multiple data centers in various geographic regions. Data redundancy and replication across these regions ensure high availability and fault tolerance, reducing the risk of data loss and downtime.
