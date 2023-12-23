# Cloud-learning-AWS

Cloud Computing (AWS/Azure/GCP/Oracle CLOUD)
 
To know about Cloud computing first we need to know why did cloud computing come into picture and what the IT industry used to follow before cloud was introduced. 


Also we need to know what is a data centre, hyper visor, virtual machine and how they are used. 


Data centres - 
 
 
A data center (or data centre) is a facility used to house computer systems and related components, such as telecommunications and storage systems. It generally includes redundant or backup power supplies, redundant data communications connections, environmental controls (e.g., air conditioning, fire suppression), and various security devices. Data centers are crucial for the continuous operation of computer systems and the storage, processing, and management of large amounts of data.
 
Key components and features of a data center include:
 
 Data centers house a large number of servers and computing equipment that perform various tasks, such as running applications, storing data, and processing requests.
 Data centers have extensive storage infrastructure to store and manage large volumes of data.
 Data centers are equipped with advanced networking hardware to facilitate communication and data transfer between servers, as well as between the data center and external networks.
Data centers play a central role in supporting the operations of organizations that rely on IT infrastructure. They can be owned and operated by the organizations themselves or by third-party providers(AWS/GCP/AZURE), offering colocation or cloud services to multiple clients. The design and management of data centers are critical to ensuring reliability, security, and efficiency in the delivery of IT services.
 
 

Hypervisor's -
 
 Hypervisors allow multiple virtual machines (VMs) to run on a single physical server, effectively utilizing the available CPU, memory, and storage resources. This consolidation reduces the need for a large number of physical servers, leading to cost savings and improved resource efficiency. 
so, generally if you have one PC (which is a physical server in Data centre. This physical server is not completely used in regards of CPU , Memory, storage resources. So instead of wasting these resources we already have we make use of these using hypervisors)
A hypervisor, also known as a virtual machine monitor (VMM), is a software or hardware component that enables the creation and management of virtual machines. It sits between the hardware and the operating systems, allocating resources and ensuring that multiple operating systems can run on a single physical machine without interfering with each other.
 
Virtual Machine's - 
 
A virtual machine is an emulation of a physical computer system. It runs an operating system and applications just like a physical machine but is hosted on a hypervisor. Multiple VMs can run on the same physical hardware, each operating independently. VMs provide isolation, flexibility, and resource optimization.
 



ON - PREMISES 
 
 
On-premises, also known as on-prem or on-site, refers to the traditional method of hosting and managing computing resources within the physical confines of an organization's premises or data centre. In this model, the organization owns, operates, and maintains its own hardware, software, and networking infrastructure. 
In this Organizations have their own control and can categorize however they want. 
some of the characteristics of on prem are  Control, Security, Upfront costs, Scalability.

Control -  Organizations have full control over their infrastructure, allowing them to customize and configure it based on their specific requirements.
 
Security -  Since the infrastructure is physically located on-site, organizations can implement security measures tailored to their needs. However, this also means they bear the responsibility for securing the entire environment.
 
Upfront Costs - On-premises infrastructure involves significant upfront capital expenditures for purchasing hardware, software licenses, and establishing the necessary facilities.
 
Scalability -  Scalability is often limited, as organizations need to anticipate future growth and purchase additional hardware in advance.
 
 
 
CLOUD COMPUTING SERVICES 
 
 
Cloud main agenda is  PAY-AS-YOU-GO-PRICING. The meaning is how much you use that much you pay. 

 
Cloud computing is a model for delivering computing services over the internet, eliminating the need for organizations to own, manage, and maintain physical infrastructure. These services include computing power, storage, databases, networking, software, analytics, and more. It is something like it is a virtual service where you need not do anything but the service provider does everything. Though there are some things the customer needs to do but still it is like a service which is introduced to make people life more easy. Since everything is done virtually we call it cloud computing. 
 
Characteristics :
 
On-Demand-Self-Services -Users can provision and manage computing resources as needed, without requiring human intervention from the service provider.
 
Broad Network  Access - Cloud services are accessible over the internet from a variety of devices such as laptops, smartphones, and tablets
 
 
Resource Pooling - Resources are shared among multiple users, and the cloud provider dynamically allocates and reallocates resources based on demand.
 
 
Rapid Elasticity - Resources can be scaled up or down quickly to accommodate changing workloads, providing flexibility and cost-efficiency.
 
 
 
Measured Service  - Cloud resources are metered, and users are billed based on their actual usage. This pay-as-you-go model offers cost control and efficiency.



**** In summary, on-premises involves maintaining physical infrastructure locally, while cloud computing delivers services over the internet with benefits such as scalability, cost efficiency, and flexibility.  ***


Basically when they say cloud they think there will not be any data centres or physical equipment required or are initialized but in generally there are physical data centres present in cloud as well but are organized and constructed by the cloud services like (AWS/ GCP/ azure etc)
There are so many cloud service providers - AWS (Amazon Web Services ) , GCP (Google Cloud Provider ) , AZURE , ORACLE. 
Now let us see the most used cloud service provider these days which is AWS - Amazon Web Service. 


AWS (AMAZON WEB SERVICES) 

Why cloud computing?
When your using on premises setup for your company, this requires a large amount of space for the data centre to store the physical servers, infrastructure, data storage, security ,etc  and also takes huge amount of money even though if you won't be using the total resources you pay for. 
Suppose take an EXAMPLE you wanted to start an e-commerce website like Flipkart and you buy the physical servers, storage data bases, infrastructure , etc and now your e-commerce website is up and running but you had a flash sale where the customers went so high than you imagined and your physical server can't operate because of the load, so now you buy one more physical server to debug this problem and this works fine and the flash sale is over now the 2nd physical server you bought if of no use until or unless something again happens. So to eradicate problems like these cloud came into picture. You can use PAY-AS-YOU-GO-PRICING  agenda of cloud and reduce your cost. So in this same example when you need an extra server for load balancing you will creating an ec2 instance (ec2 is like a virtual server / instance which in terms of AWS) and help your 1st server with 2nd, so after your load balancing / flash sale is done you kill the ec2 so you won't needs to use to later. Again if you want you will be starting new one. It's that easy in cloud. Also you get your server instantly through internet. 

 

Cloud service and deployment methods provide different levels of flexibility, control and management 

 
Service models in cloud computing refer to the different types of services or layers that are offered by cloud service providers. These models define the level of abstraction and control that users have over the computing resources. The three primary service models are :

1. Infrastructure as a Service (IaaS) 
IaaS provides virtualized computing resources over the internet. Users can rent virtual machines, storage, and networking components. This model gives users more control over the operating system, applications, and configurations.
Use case : Suitable for organizations that need scalable and flexible infrastructure without the burden of managing physical hardware. Users have the freedom to install and run their own software.
2. Platform as a Service (Paas)
 PaaS offers a platform that allows customers to develop, run, and manage applications without dealing with the complexities of underlying infrastructure. The platform typically includes development tools, databases, and middleware.
Use case :  Ideal for developers who want to focus on coding and application development without the need to manage the underlying infrastructure. It streamlines the application deployment process.
3. Software as a Service (Saas) 
SaaS delivers software applications over the internet on a subscription basis. Users access the software through a web browser without needing to install or maintain it locally.
Use case : Commonly used for applications such as email, customer relationship management (CRM), and collaboration tools. SaaS eliminates the need for users to handle software maintenance and updates.


Deployment models in cloud computing define where the cloud infrastructure is located, who manages it, and how it is shared. The three main deployment models are:


1. Public Cloud 
Resources are owned and operated by a third-party cloud service provider and are made available to the general public. Multiple customers share the same infrastructure, benefiting from cost efficiencies and scalability.

2. Private Cloud
Resources are used exclusively by a single organization. The infrastructure may be hosted on-premises or by a third-party provider. Private clouds offer greater control, security, and customization.
 
3. Hybrid Cloud
Combines elements of both public and private clouds. It allows data and applications to be shared between them. Hybrid cloud provides greater flexibility, allowing organizations to leverage public cloud resources for scalability while retaining sensitive data on-premises.
 


AWS provides over 175 services and is one of the most used cloud service till date. 
These services include compute,  storage, databases, analytics, networking, developer tools, business applications, management tools, machine learning, Internet of things, and security. 
 
AWS  Benefits 

Performance 
Availability 
Security
Reliability
Scalability
Low Cost

 
 
AWS Global Infrastructure 
 
 The main components of AWS global infrastructure are regions, availability zones,  and edge locations. 

A region consists of availability zones and these availability zones consists of edge locations. 

Region(us-east-1) - A physical location  around the world where data centres are clustered together. A group of logical data centres are called availability zones. Each AWS region consists of multiple, isolated and physically separate availability zones within a geographic area. The pricing across each region differs. 
 
Availability Zone - An Availability Zone (AZ) is a distinct location within an AWS region that is engineered to be isolated from failures in other Availability Zones. AWS designed Availability Zones to provide high availability and fault tolerance to ensure that applications and data remain available and resilient in the face of various failures, such as hardware failures, network issues, or power outages.


Edge location -  These are a powerful way to enhance the performance, availability, security of the product. 


EXAMPLE - AN E- COMMERCE Website  

Region - The use case of this is that when your e-commerce website is a global website you need to set it up in different regions (suppose in INDIA , USA) for your global customers to reach. 
Availability zone - Suppose you have multiples customers using the website and load balancing is required because of the traffic to the server. So if one availability zone fails the other one gets activated instantly. 
Edge locations - Edge Locations, in conjunction with CloudFront, offer a powerful way to enhance the performance, availability, and security of your e-commerce website by caching content closer to end-users and optimizing the delivery of dynamic and static assets. They are especially valuable for global applications with a diverse user base.


  
 







AWS Shared Responsibility Model 
 
 it is a security model that is used to protect cloud environments that use AWS services. 
It is divided into 2 parts, 1. AWS is responsible for the security of the cloud and 2. Customer is responsible for the security in the cloud. 

1. Customer responsibility - Responsible for the security of everything that they create and put in AWS cloud
2. AWS responsibility - it manages security OF the cloud specifically physical infra that hosts your resources. (physical security of data centres, hardware and software, network infra, virtualization infra)

 

AWS Well- Architected Framework 

Designed to help you build most secure, high performing, resilient , efficient  and most cost-efficient infra possible in cloud. 
It provides an ideal approach which u can use. This is based on 6 principles. (Operational Excellence, Security, Reliability, Performance efficiency, Cost optimization )

AWS Well- Architected Tool is a free tool which helps you review state of your workloads. It compares them to latest features of the framework and asks you some questions on your workload and help  you in building your architecture. 


Cost and Billing - Pricing models  1. Pay as you go 
2. Save when you reserve 3. Pay less by using more. 
 
 
*****
Whatever the services you take from cloud you need a way to interact with the resources. So you can interact with the resources using many ways, but the main ways to interact with cloud will be 
1. Using Management console (
 AWS Management Console is a web-based user interface that allows you to access and manage AWS resources using a graphical interface.)
2.  AWS CLI 
The AWS CLI is a command-line tool that provides a set of commands for managing AWS services. It allows you to automate tasks and interact with AWS from the command line.
3. AWS SDK's
AWS SDKs are available for various programming languages (e.g., Python, Java, JavaScript, .NET) and provide APIs to interact with AWS services programmatically.
4. AWS Cloud 9 (Aws cloud 9 ) 
It is a AWS Cloud9 is a tool used to interact with your AWS resources. This is specifically designed for AWS Cloud. 
 
*****
 
 
Let us deep dive into AWS Core services 
 
Amazon S3(Simple Storage Service )
Amazon EC2(Elastic Compute Cloud)
Amazon VPC(Virtual Private Cloud)
Amazon RDS (Relational Database Service)
Amazon IAM (Identity and Access Management)
AWS Lambda (Serverless) 
Amazon Cloud Watch 
 
 
 
Amazon S3(Simple Storage Service )
 
S3 is an object storage service, meaning it stores data as objects rather than traditional file hierarchies. Each object consists of data, a key (unique within a bucket), and metadata.
Objects in S3 are stored in containers called buckets. A bucket has a globally unique name within the S3 namespace. You can create multiple buckets to organize and control access to your objects.
Objects are the basic units of storage in S3. An object can be a file, image, video, or any other type of data. Each object has a key (a unique identifier within a bucket) and a URL (Uniform Resource Locator) for access.
 
 
Amazon EC2 (Elastic Compute Cloud)
 
Amazon EC2 (Elastic Compute Cloud) is a web service provided by Amazon Web Services (AWS) that allows users to rent virtual servers on which they can run their applications. EC2 instances provide scalable compute capacity in the cloud and are a fundamental building block for many cloud-based applications.
EC2 instances are virtual servers that run on physical hardware hosted in AWS data centers. Users can choose from a variety of instance types based on their specific requirements, including compute power, memory, storage, and networking capacity.
EC2 offers a wide range of instance types optimized for different use cases. These include general-purpose instances, compute-optimized instances, memory-optimized instances, storage-optimized instances, and more.
EC2 instances can be launched in different geographic regions around the world. Each region consists of multiple isolated locations called Availability Zones. Choosing the right region and availability zone can impact latency, redundancy, and data residency.
Auto Scaling allows users to automatically adjust the number of EC2 instances in a fleet based on demand.
 
 
 
 
Amazon VPC(Virtual Private Cloud)
 
Amazon VPC (Virtual Private Cloud) is a service provided by Amazon Web Services (AWS) that allows users to create isolated and secure network environments in the cloud. With Amazon VPC, you can define and control a virtual network, including IP address ranges, subnets, route tables, and network gateways. This enables you to host AWS resources in a logically isolated section of the AWS Cloud.
An Internet Gateway (IGW) allows resources within a VPC to connect to the internet. Public subnets typically have a route to the IGW for outbound internet access.
Network Address Translation (NAT) gateways and NAT instances allow private subnets to initiate outbound traffic to the internet while preventing inbound traffic from reaching them.
Virtual Private Network (VPN) connections provide secure communication between your on-premises data center and your VPC. This allows you to extend your data center into the cloud securely.
VPC endpoints enable you to privately connect your VPC to supported AWS services, such as Amazon S3 and DynamoDB, without the need for public internet access.
 
 
 
Amazon RDS (Relational Database Service)
 
Amazon RDS (Relational Database Service) is a managed relational database service provided by Amazon Web Services (AWS). It makes it easier to set up, operate, and scale a relational database in the cloud. Amazon RDS supports various database engines, such as MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB.
Amazon RDS automates routine database tasks, such as hardware provisioning, database setup, patching, and backups. This allows developers to focus on application development rather than database management.
Amazon RDS automatically takes daily backups of your database, and you can also configure the retention period. Backups are stored in Amazon S3 and can be used for point-in-time recovery.
Amazon RDS can generate event notifications for various database events, such as instance failures, backups, and security group changes. These notifications can be sent to Amazon SNS topics for alerting.
Amazon RDS is suitable for a wide range of applications, including web applications, mobile backends, e-commerce platforms, and enterprise applications.
 
 
 
 
Amazon IAM (Identity and Access Management)
 
Amazon IAM (Identity and Access Management) is a web service provided by Amazon Web Services (AWS) that enables secure control over access to AWS resources. IAM allows you to manage users, groups, roles, and their permissions to securely access AWS services and resources.
IAM users are entities representing individuals or applications that interact with AWS services. Each user has a unique name and credentials associated with it.
Groups are collections of IAM users. Instead of attaching policies directly to users, you can add users to groups and attach policies to groups, making it easier to manage permissions at scale.
IAM roles are similar to users but are not associated with a specific person or set of credentials. Roles are assumed by users, applications, or AWS services to obtain temporary security credentials with defined permissions.
IAM is a fundamental component of AWS security, providing a centralized and granular way to manage access to AWS resources. By following the principle of least privilege, you can ensure that users, applications, and services have only the permissions they need to perform their tasks, enhancing the security posture of your AWS environment.
 
 
 
AWS Lambda (Serverless) 
 
AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). It allows you to run code without provisioning or managing servers, making it easier to build scalable and cost-effective applications. With Lambda, you can execute code in response to events, such as changes to data in an Amazon S3 bucket, updates to a DynamoDB table, or HTTP requests via Amazon API Gateway.
AWS Lambda follows a serverless computing model, where you only pay for the compute time your code consumes. There's no need to worry about server provisioning, maintenance, or scaling.
Lambda functions are triggered by events, which can come from various AWS services or custom sources. Common triggers include changes to data in Amazon S3, messages in Amazon SNS or Amazon SQS, and HTTP requests through Amazon API Gateway.
Lambda automatically scales your functions in response to the number of incoming events.
 
 
Amazon Cloud Watch 
 
Amazon CloudWatch is a monitoring and observability service provided by Amazon Web Services (AWS). It allows you to collect, monitor, and analyze data from various AWS resources and applications in real-time. CloudWatch provides insights into the performance, health, and operational status of your AWS infrastructure.
CloudWatch collects and stores time-series data in the form of metrics. Metrics represent various aspects of your AWS resources, such as CPU utilization, network traffic, and error rates.
 


 # Kubernetes 

 Kubernetes also called k8s is a cointainer orchestration platform which is mainly used to managed containerized applications for enterprise level.
 It is a Devops tool which is used in microservices, container applications etc. 
 Mainly used for automating the deployment, scaling, and management of containerized applications. 

 # DOCKER VS K8S 
  Docker is primarily a containerization platform, while Kubernetes is a container orchestration platform that manages the deployment and operation of containerized applications at scale. They can be used together to provide a comprehensive solution for developing, packaging, and managing containerized applications in a production environment.
  Basically there are so many disadvantages for enterprises to use docker. Some of the main drawbacks are SECURITY, AUTO HEALING, AUTO SCALING, SINGLE HOST, etc like this there are so many drawbacks to use docker in a enterprise level. So we use Docker and k8s as combination in enterprise. 
It can be docker or any other container platform we can use but docker is the most famous one. 
So, the main 4 drawbacks of Docker are handled by K8s. Which are
AUTO SCALING, SECURITY, AUTO HEALING, SINGLE HOST
Let us see how :

In k8s the main thing is kubernetes cluster, so in general kubernetes is installed as a cluster
In Kubernetes (K8s), a cluster refers to the collection of nodes that work together to run containerized applications. It is the fundamental unit in Kubernetes and consists of two main components:
Master Node(s): This is the control plane of the cluster, responsible for managing and coordinating the overall cluster activities. The master node(s) includes components such as the API server, etcd (a distributed key-value store for configuration data), controller manager, and scheduler.

Worker Node(s): These are the machines (physical or virtual) where containers are actually deployed and run. Each worker node runs a container runtime (such as Docker or containerd) and a set of Kubelet, which is responsible for ensuring that containers are running in a Pod.

A Pod is the smallest and simplest unit in the Kubernetes object model, and it represents a single instance of a running process in a cluster.

If you run k8s as a cluster (in production it is installed as a cluster) we can suppose there is a docker container which is about to get killed because there is no memory space so what this cluster will do is allocate another node using virtualization concept memory and make the container work. This is how a k8s is beneficial as a cluster
But generally as a developer k8s is not installed as cluster instead as a single node. (developer environment)

Using replica set we can get rid of one of the main drawbacks of docker which is auto scaling.  ReplicaSets are used for maintaining the desired number of copies of a set of Pods, typically for scaling and ensuring the availability of a specific application.
There is something called pod auto scaler as well but that is very advanced. 

Third drawback is auto healing, which k8s handles very well. Let's say a container or a pod goes down and incase of docker we need to check using commands and check logs what happened. But in k8s there is something called as API server where when a pod or container is about to get killed or about to be getting down as soon as k8s knows this k8s starts a new pod for this . 

Fourth drawback is Enterprise level - So, k8s is basically a tool originated from a tool of Google borg. K8s is a enterprise level itself because it ensures security, network, firewall, etc. 


# K8S ARCHITECTURE 
The k8s architecture is basically of 2 :
1. Control Plane
The control plane is responsible for managing and controlling the overall state of the Kubernetes cluster. It acts as the brain of the system, making global decisions about the cluster (e.g., scheduling), as well as detecting and responding to cluster events (e.g., starting up a new pod when a deployment's replicas field is unsatisfied).
2. Data plane 
The data plane is responsible for handling the network traffic of the application workloads. It consists of nodes (worker machines) that run containers and manage the networking between them.

In summary, the control plane manages and orchestrates the overall state of the Kubernetes cluster, while the data plane handles the execution of containerized applications and the networking between them. The separation allows for better scalability, fault isolation, and modular development and maintenance of the Kubernetes system.

Worker nodes consists of pod, container runtime, kubelet, kube proxy
A Pod is the smallest and simplest unit in the Kubernetes object model. It represents a single instance of a running process in a cluster and can contain one or more containers. Containers within a Pod share the same network namespace and can communicate with each other using localhost.
A Container Runtime is the software responsible for running containers within a Pod. Kubernetes supports various container runtimes, including Docker, containerd, and others. The container runtime is responsible for pulling container images, creating and managing container processes, and handling aspects of container lifecycle, such as starting, stopping, and restarting containers.
Kubelet is an agent that runs on each node in the Kubernetes cluster. It is responsible for ensuring that containers are running in a Pod. 
Kube-Proxy is a network proxy that runs on each node in the cluster. It is responsible for maintaining network rules that allow communication to and from Pods from within the cluster.
In summary, a Pod is the basic unit of deployment, a Container Runtime manages the execution of containers, Kubelet ensures that Pods are running on nodes, and Kube-Proxy handles networking and basic load balancing for services within the cluster. 

The control plane in Kubernetes consists of several components that work together to manage and control the overall state of the cluster.
The API server is the central management point for the entire Kubernetes cluster. It exposes the Kubernetes API and is responsible for receiving and handling requests from users, operators, and other components.
etcd is a distributed key-value store that is used to store configuration data and the state of the entire Kubernetes cluster. It ensures consistency and reliability in maintaining cluster configuration information.
The Controller Manager watches the state of the cluster through the API server. It is responsible for regulating the state of various objects in the cluster, such as deployments, nodes, and pods.
The Scheduler is responsible for making decisions about where to deploy Pods based on resource availability, constraints, and other factors. It schedules the workload onto available worker nodes in the cluster.


 
 
 
 
 
 
 
 
 
 
 
 
 







 
 
 
 
 
 
 
 
 
 
 


 
 
 
 
 
 
