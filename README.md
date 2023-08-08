# Why Cloud computing?

Lets think about why there is a need to create something called cloud computing?

## Lets understand how normal Laptop works
Lets say we have our Laptop/Desktop machines and we are loading an Excel file of 1 MB file, it loads easily

Lets first understand how this file of 1 MD loads to a Laptop/Desktop machine.


File is present in HDD / SDD.
Once we load the file it will be bought from HDD to RAM, Why?
    because RAM is much faster than the storage device, which allows for quicker access to the file's content during use.

We need Computation: 
    To locate the file address
    To Load the data from HDD to RAM
    To respond to user interactions


What does Laptop/Desktop have?
Two components
    1. Hardware
    2. Software

1. Hardware
    Hard disk / SSD
    RAM
    Processor
        Network Card for internet
        Mother board combine all HDD RAM CPU
        Power circuit
        Cooling Fan
2. Software
    Operating System

Hard disk / SSD - Storage
RAM - Memory
Processor - CPU Cores - A CPU core is essentially a complete processing unit with its own arithmetic logic unit (ALU), control unit, and cache memory.

So, Just to load file we have seen following things

    Storage - Storing the File
    In Memory - Storing the File
    Compute - Process the File

Now what if I need to load an excel file that is of 2GB 
I have following configurations:
    HDD - 1 TB
    RAM - 4 GB
    Compute - Quad Cores

    Easily Load the file and perform changes


Now what if I need to load an excel file that is of 6GB 
I have following configurations:
    HDD - 1 TB - Possible
    RAM - 4 GB - Not possible
    Compute - Quad Cores

    Not possible

    So let me upgrade my Laptop
    HDD - 1 TB - Possible
    RAM - 8 GB - Possible
    Compute - Quad Cores

    Easily Load the file and perform changes



WHat if I need to process more than 10GB, 20 GB files.

So let me upgrade my laptop

Costly:
    HDD - 1 TB - Possible
    RAM - 24 GB GB - Possible
    Compute - Octa Cores

    Easily Load the file and perform changes

Let's say I want to process file monthly once.

Only 12 times in a year, Is upgrading my Laptop is a good approach?
What if I need to process more than 24 GB files, upgrading the laptop is a good approach?


More intuitive example:

Let's say I need to build a website

We need to write code to display a website
 HTML, CSS, JavaScript
 All these HTML files
 CSS files
 JavaScript files have to be stored in a computer
 HDD/SDD

Need a software the takes http request and find website files render it and then show the files - Nginx

Storage: 
    Holds the website files and assets, which are read by the web server for serving to clients.
    Holds the Nginx software
RAM: 
    Temporarily stores website files in memory to speed up processing and response times.
    Nginx starts - Loads configuration data, connection details, buffers, and other internal data.
CPU Cores: 
    Execute the web server software, handle incoming requests, and generate responses to serve the website content to clients.

https://localhost



My requirement is I need to keep my website globally accessible:
    Router - To route incomming traffic to point to local ip address 
    Set up Dynamic DNS - Route changing ip address to Domain name
    I need to keep my laptop/Desktop in running state

    Problems:
        What if the Power goes down?
        What if we need to update the servers?
        What if Natural disasters happen?
        WHat if there are millions of requests per second?



Maintaining a Sigle machine kept running has become a problem to address emerging technologies

So A group of Machines connected through Network resulting in Creation of Data Centers
    Organizations set up their own data centers or leased server spaces in data centers to host their websites and applications. This approach required purchasing and maintaining physical servers.

Only Huge Organissations use to have their own Data Centers
But for a start-up companies they need huge investment to start and maintain their own data center.

THis was the problem addressed clearly by Amazon in early 2000's


So, Amazon started on 1994 to sell books online and then slowly they added electronics, clothing, toys, home goods, and more. 
They were experience massive growth on the e-commerce giant to support expanding online retail products.

They had built & started maintanining a massive Infrastructure with thousands of servers, storage connected.


After builting they have observed that all the servers are not getting utilised properly.

They started Providing Infrastructure as Service


So any service offered in Cloud falls on these below basic components of computer:

1. Compute
2. In - Memory
3. Storage

Only 3 Components or combination of there 3 services are offered as Services in any cloud services




1. Compute:
Amazon Web Services:
EC2, Lambda, Batch, ECS, Fargate etc.,.

Google Cloud
Compute Engine, CLoud functions etc.,.

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










