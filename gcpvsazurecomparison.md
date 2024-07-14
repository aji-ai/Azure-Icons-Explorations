## Marketplace
| Google Cloud service     | Azure service       | Description                                                                                      |
|--------------------------|---------------------|--------------------------------------------------------------------------------------------------|
| Google Cloud Marketplace | Azure Marketplace   | Easy-to-deploy and automatically configured third-party applications, including single virtual machine or multiple virtual machine solutions. |

## Data Platform

### Database

#### Relational Database
| Type                   | Google Cloud service | Azure service                                                                                  | Azure service description                                                                                                              |
|------------------------|----------------------|------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Relational database    | Cloud SQL - SQL Server | Azure SQL family                                                                                | Azure SQL family of SQL Server database engine products in the cloud                                                                   |
|                        |                      | Azure SQL Database                                                                              | Fully managed platform as a service (PaaS) database engine                                                                             |
|                        |                      | Azure SQL Managed Instance                                                                      | Intelligent, scalable cloud database service that combines SQL Server database engine compatibility with fully managed platform as a service |
|                        |                      | SQL Server on Azure VM                                                                          | SQL Server IaaS deployed on Azure Windows or Linux VM                                                                                  |
|                        |                      | Azure SQL Edge                                                                                  | Optimized relational database engine geared for IoT and edge deployments                                                               |
| Cloud SQL MySQL & PostgreSQL |                | Azure Database for MySQL (Single & Flexible Server), Azure Database for PostgreSQL (Single & Flexible Server) | Managed relational database service where resiliency, security, scale, and maintenance are primarily handled by the platform             |

#### Horizontally Scalable Relational Database
| Google Cloud service | Azure service                                                      | Description                                                                                                        |
|----------------------|--------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| Cloud Spanner        | Azure Cosmos DB for NoSQL, Azure PostgreSQL Hyperscale (Citus)     | Globally-distributed database system that limitlessly scales horizontally. Supports multiple APIs and data models.  |

#### NoSQL
| Google Cloud service         | Azure service                                    | Description                                                                                                                     |
|------------------------------|--------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| Cloud Bigtable               | Azure Table storage                              | Highly scalable NoSQL key-value store for rapid development using massive semi-structured datasets.                             |
| Cloud Firestore              | Azure Cosmos DB                                  | Globally distributed, multi-model database that natively supports multiple data models.                                         |
| Firebase Realtime Database   | Azure Cosmos DB change feed                      | Change feed in Azure Cosmos DB is a persistent record of changes to a container in the order they occur.                         |

#### In-memory
| Google Cloud service | Azure service        | Description                                                                                         |
|----------------------|----------------------|-----------------------------------------------------------------------------------------------------|
| Cloud Memorystore    | Azure Cache for Redis| Secure data cache and messaging broker providing high throughput and low-latency access to data for applications. |

### Data Warehouse
| Google Cloud service | Azure service              | Description                                                                                                                |
|----------------------|----------------------------|----------------------------------------------------------------------------------------------------------------------------|
| BigQuery             | Azure Synapse Analytics, SQL Server Big Data Clusters, Azure Databricks | Cloud-based Enterprise Data Warehouse (EDW) using Massively Parallel Processing (MPP) to quickly run complex queries across petabytes of data. |

### Data Orchestration and ETL
| Google Cloud service | Azure service                         | Description                                                                                             |
|----------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------|
| Cloud Data Fusion    | Azure Data Factory, Azure Synapse Analytics | Processes and moves data between different compute and storage services, as well as on-premises data sources at specified intervals. |

### Big Data and Analytics
#### Big Data Processing
| Google Cloud service | Azure service                                | Description                                 |
|----------------------|----------------------------------------------|---------------------------------------------|
| Dataproc             | Azure HDInsight, Azure Synapse Analytics, Azure Databricks | Managed Apache Spark-based analytics platform. |

### Analytics and Visualization
| Google Cloud service | Azure service           | Description                                                                                                               |
|----------------------|-------------------------|---------------------------------------------------------------------------------------------------------------------------|
| Cloud Dataflow       | Azure Databricks        | Managed platform for streaming batch data based on Open Source Apache products.                                            |
| Data Studio, Looker  | Power BI                | Business intelligence tools that build visualizations, perform ad hoc analysis, and develop business insights from data.   |
| Cloud Search         | Azure Search            | Delivers full-text search and related search analytics and capabilities.                                                   |
| BigQuery             | SQL Server Analysis Services | Provides a serverless non-cloud interactive query service that uses standard SQL for analyzing databases.                   |

### Time Series & IoT Data
| Google Cloud service | Azure service                     | Description                                                                                      |
|----------------------|-----------------------------------|--------------------------------------------------------------------------------------------------|
| BigQuery             | Azure Data Explorer, Azure Cosmos DB | Fully managed, low latency, and distributed big data analytics platform optimized for log and time series data. |

### AI and Machine Learning
| Google Cloud service            | Azure service                                    | Description                                                                                         |
|---------------------------------|--------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Vertex AI                       | Azure Machine Learning                           | Cloud service to train, deploy, automate, and manage machine learning models.                       |
| TensorFlow                      | ML.NET, ONNX (Open Neural Network Exchange)      | Open-source and cross-platform machine learning frameworks.                                         |
| Vision AI                       | Azure Cognitive Services Computer Vision         | Visual data processing to label content, extract text, recognize subjects, and moderate content.     |
| Natural Language AI             | Azure Cognitive Services Text Analytics, Azure Cognitive Services Language Understanding (LUIS) | Advanced natural language processing and machine learning-based service to build natural language understanding into apps. |
| Speech-to-Text                  | Azure Cognitive Services Speech To Text          | Convert audio into text from various sources with customizable models.                              |
| AutoML Tables – Structured Data | Azure ML - Automated Machine Learning, ML.NET Model Builder | Automate time-consuming tasks of model development and provide an easy-to-use interface for building custom machine learning models. |
| AutoML Vision                   | Azure Cognitive Services Custom Vision           | Customize and embed state-of-the-art computer vision for specific domains.                          |
| AutoML Video Intelligence       | Azure Video Analyzer                             | Extract insights from videos to enhance discovery and engagement.                                   |
| Dialogflow                      | Azure Cognitive Services QnA Maker               | Build, train, and publish sophisticated bots using various content sources.                         |
| AI Platform Notebooks           | Azure Notebooks                                  | Develop and run code from anywhere with Jupyter notebooks on Azure.                                 |
| Deep Learning VM Image          | Data Science Virtual Machines                    | Pre-configured environments for Data Science and AI Development in the cloud.                       |
| Deep Learning Containers        | GPU support on Azure Kubernetes Service (AKS)    | Compute-intensive workloads in Kubernetes with GPU-enabled node pools.                              |
| Data Labeling Service           | Azure ML - Data Labeling                         | Manage labeling projects to coordinate data, labels, and team members.                              |
| AI Platform Training            | Azure ML – Compute Targets                       | Designated compute resource/environment for training scripts or service deployment.                 |
| AI Platform Predictions         | Azure ML - Deployments                           | Deploy machine learning models as web services or to Azure IoT Edge devices.                        |
| Continuous Evaluation           | Azure ML – Data Drift                            | Monitor for data drift between training and inference datasets.                                     |
| What-If Tool                    | Azure ML – Model Interpretability                | Ensure machine learning model compliance with policies, standards, and regulations.                 |
| Cloud TPU                       | Azure ML – FPGA (Field Programmable Gate Arrays) | FPGAs for compute-intensive workloads with a combination of programmability and performance.        |
| Kubeflow                        | Machine Learning Operations (MLOps)              | DevOps for machine learning to increase model development and deployment pace.                      |
| Dialogflow                      | Microsoft Bot Framework                          | Build and connect intelligent bots that interact with users using various services.                 |

### Data Catalog & Governance
| Google Cloud service | Azure service         | Description                                                                                              |
|----------------------|-----------------------|----------------------------------------------------------------------------------------------------------|
| Dataplex             | Microsoft Purview     | Comprehensive portfolio of products spanning data governance, data security, and risk and compliance solutions. |

## Compute

### Virtual Servers
| Google Cloud service       | Azure service                   | Description                                                                                                |
|----------------------------|---------------------------------|------------------------------------------------------------------------------------------------------------|
| Compute Engine             | Azure Virtual Machines          | Virtual servers for deploying, managing, and maintaining OS and server software with flexible instance types. |
| Sole-tenant nodes          | Azure Dedicated Host            | Host VMs on hardware dedicated only to your project.                                                       |
| Batch                      | Azure Batch                      | Run large-scale parallel and high-performance computing applications efficiently in the cloud.             |
| Compute Engine Autoscaler  | Azure virtual machine scale sets | Automatically change the number of VM instances based on defined metrics and thresholds.                   |
| Cloud GPUs                 | GPU Optimized VMs                | GPU-optimized VM sizes for compute-intensive, graphics-intensive, and visualization workloads.             |
| VMware Engine              | Azure VMware Solution            | Redeploy and extend VMware-based enterprise workloads to Azure seamlessly.                                 |

### Containers and Container Orchestrators
| Google Cloud service      | Azure service                       | Description                                                                                                  |
|---------------------------|-------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Cloud Run                 | Azure Container Apps                | Fastest and simplest way to run a container in Azure without provisioning VMs or higher-level orchestration.  |
| Artifact Registry (beta)  | Azure Container Registry            | Store Docker formatted images for creating container deployments on Azure.                                    |
| Kubernetes Engine (GKE)   | Azure Kubernetes Service (AKS)      | Deploy orchestrated containerized applications with Kubernetes and simplify cluster management and monitoring.|
| Kubernetes Engine Monitoring | Azure Monitor container insights | Monitor the performance of container workloads deployed to various environments.                             |
| Anthos Service Mesh       | Open Service Mesh (OSM)             | Lightweight and extensible cloud-native service mesh for managing, securing, and observing microservice environments. |

## Functions
|

 Google Cloud service | Azure service       | Description                                                                                      |
|----------------------|---------------------|--------------------------------------------------------------------------------------------------|
| Cloud Functions      | Azure Functions     | Integrate systems and run backend processes in response to events or schedules without provisioning or managing servers. |

## DevOps and Application Monitoring
| Google Cloud service           | Azure service                         | Description                                                                                                   |
|--------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Operations (formerly Stackdriver) | Azure Monitor                       | Comprehensive solution for collecting, analyzing, and acting on telemetry from cloud and on-premises environments. |
| Cloud Trace                    | Azure Monitor                         | Comprehensive solution for collecting, analyzing, and acting on telemetry from cloud and on-premises environments. |
| Cloud Debugger                 | Azure Monitor                         | Comprehensive solution for collecting, analyzing, and acting on telemetry from cloud and on-premises environments. |
| Cloud Profiler                 | Azure Monitor                         | Comprehensive solution for collecting, analyzing, and acting on telemetry from cloud and on-premises environments. |
| Cloud Source Repositories      | Azure Repos, GitHub Repos             | Cloud service for collaborating on code development.                                                           |
| Cloud Build                    | Azure Pipelines, GitHub Actions       | Fully managed build service that supports continuous integration and deployment.                               |
| Artifact Registry              | Azure Artifacts, GitHub Packages      | Integrated package management for CI/CD pipelines.                                                             |
| Cloud Developer Tools          | Azure Developer Tools                 | Collection of tools for building, debugging, deploying, diagnosing, and managing multiplatform scalable apps and services. |
| Gcloud SDK                     | Azure CLI                             | Command-line interface for creating and managing Azure resources.                                              |
| Cloud Shell                    | Azure Cloud Shell                     | Interactive, authenticated, browser-accessible shell for managing Azure resources.                              |
| PowerShell on Google Cloud     | Azure PowerShell                      | Cmdlets for managing Azure resources directly from the PowerShell command line.                                |
| Cloud Deployment Manager       | Azure Automation, Azure Resource Manager | Cloud-based automation and configuration service for consistent management across environments.                   |

## Internet of Things (IoT)
| Google Cloud service        | Azure service                      | Description                                                                                                         |
|-----------------------------|------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Cloud IoT Core              | Azure Event Grid MQTT broker, Azure IoT Hub | Gateways for managing bidirectional communication with IoT devices, securely and at scale.                         |
| Cloud Pub/Sub               | See Messaging and eventing section | Process and route streaming data to a subsequent processing engine or to a storage or database platform.            |
| Edge TPU                    | Azure IoT Edge, Azure IoT Operations | Deploy cloud intelligence directly on IoT devices to run in on-premises scenarios.                                  |

## Management
| Google Cloud service | Azure service       | Description                                                                                              |
|----------------------|---------------------|----------------------------------------------------------------------------------------------------------|
| Cloud Billing        | Azure Billing API   | Services to help generate, monitor, forecast, and share billing data for resource usage by time, organization, or product resources. |
| Cloud Console        | Azure portal        | Unified management console that simplifies building, deploying, and operating your cloud resources.      |
| Operations (formerly Stackdriver) | Azure Monitor | Comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments. |
| Cost Management      | Microsoft Cost Management | Helps you understand your Azure invoice, manage billing accounts and subscriptions, control spending, and optimize resource use. |

## Messaging and Eventing
| Google Cloud service | Azure service       | Description                                                                                              |
|----------------------|---------------------|----------------------------------------------------------------------------------------------------------|
| Cloud Pub/Sub        | Azure Service Bus   | Cloud-based message-oriented middleware technologies including reliable message queuing and durable publish/subscribe messaging. |
| Cloud Pub/Sub        | Azure Event Grid    | Fully managed event routing service for uniform event consumption using a publish/subscribe model.       |
| Cloud Pub/Sub        | Azure Event Hubs    | Real-time data ingestion and microbatching service for building dynamic data pipelines and integrating with other Azure services. |

## Networking
| Area                     | Google Cloud service                 | Azure service                      | Description                                                                                                 |
|--------------------------|---------------------------------------|------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Cloud virtual networking | Virtual Private Network (VPC)         | Azure Virtual Network (Vnet)       | Isolated, private environment in the cloud with control over IP address range, subnets, route tables, and network gateways. |
| DNS management           | Cloud DNS                             | Azure DNS                          | Manage DNS records using the same credentials as other Azure services.                                       |
|                          |                                       | Azure Traffic Manager              | DNS-based load balancer for optimal traffic distribution across global Azure regions.                        |
| Internal DNS             |                                       | Azure Private DNS                  | Manages and resolves domain names in the virtual network without the need for a custom DNS solution.        |
| Hybrid Connectivity      | Cloud Interconnect                    | Azure ExpressRoute                 | Establishes a private network connection to the cloud provider, not over the Internet.                      |
|                          | Cloud VPN Gateway                     | Azure Virtual Network Gateway      | Connects Azure virtual networks to other Azure virtual networks or customer on-premises networks.           |
|                          | Cloud router                          | Azure Virtual Network Gateway      | Enables dynamic routes exchange using BGP.                                                                  |
| Load balancing           | Network Load Balancing, Cloud Load Balancing | Azure Load Balancer, Azure Front door, Azure Application Gateway, Azure Traffic Manager | Load balancing traffic at layer 4 (TCP/UDP) and layer 7 (HTTP/HTTPS).                                          |
| Content delivery network | Cloud CDN                             | Azure CDN                          | Distributed network of servers for efficiently delivering web content.                                      |
| Firewall                 | Firewall rules                        | Application security groups, Network Security groups, Azure Firewall | Define network security policies based on VM groups and filter network traffic.                            |
| Web Application Firewall | Cloud Armor                           | Application Gateway - Web Application Firewall, Front door – Azure Web Application Firewall, CDN – Azure Web Application Firewall | Centralized protection of web applications from common exploits and vulnerabilities.                     |
| NAT Gateway              | Cloud NAT                             | Azure NAT Gateway                  | Outbound NAT translations for internet connectivity for virtual networks.                                   |
| Private Connectivity to PaaS | Private Service Connect          | Azure Private Link                 | Access Azure PaaS Services and customer-owned/partner services over a private endpoint in your virtual network. |
| Telemetry                | VPC Flow logs                         | NSG Flow logs                      | View information about ingress and egress IP traffic through an NSG.                                         |
| Firewall Rules Logging   |                                       | NSG Flow logs                      | View information about ingress and egress IP traffic through an NSG.                                         |
|                          | Operations (formerly Stackdriver)     | Azure Monitor                      | Comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments. |
| Network Intelligence Center |                                   | Azure Network Watcher              | Tools to monitor, diagnose, view metrics, and enable/disable logs for resources in an Azure virtual network. |
| Other Connectivity Options | Direct Interconnect, Partner Interconnect, Carrier Peering | Azure S2S VPN, Azure P2S VPN      | Secure connection to your virtual network from individual client computers or connections between networks. |

## Security and Identity
| Area                      | Google Cloud service                | Azure service                         | Description                                                                                                              |
|---------------------------|--------------------------------------|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| Authentication and authorization | Cloud Identity               | Microsoft Entra ID                    | Enterprise identity service with single sign-on and multifactor authentication.                                           |
| Identity platform         |                                      | Azure Active Directory B2C            | Identity management service for consumer-facing applications.                                                            |
| Multifactor authentication | Multifactor authentication         | Microsoft Entra multifactor authentication | Safeguard access to data and applications with a simple sign-in process.                                                |
| RBAC                      | Identity and Access Management      | Azure role-based access control       | Manage access to Azure resources with role-based access control (RBAC).                                                  |
| ABAC                      | Identity and Access Management      | Azure attribute-based access control  | Authorization system that defines access based on attributes.                                                            |
| Zero trust                | Chrome Enterprise Premium           | Microsoft Entra Conditional Access    | Tool to bring signals together, make decisions, and enforce organizational policies.                                     |
| Resource management       | Resource Manager                    | Azure Resource Manager                | Management layer for creating, updating, and deleting resources in your Azure account.                                   |
| Encryption                | Cloud KMS, Secret Manager           | Azure Key Vault                       | Manage, create, and control encryption keys stored in hardware security modules (HSM).                                   |
| Data-at-rest encryption   | Encryption at rest                  | Azure Storage Service Encryption - encryption by default | Protect and safeguard data with encryption at rest.                                                                     |
| Data in-use               | Confidential Computing              | Azure Confidential Computing          | Encrypt data in-use.                                                                                                     |
| Hardware security module (HSM) | Cloud HSM                       | Azure Dedicated HSM                   | Cryptographic key storage in Azure with high availability and FIPS 140-2 Level 3 certified hardware security modules (HSMs). |
| Data loss prevention (DLP) | Cloud Data Loss Prevention         | Microsoft Purview Information Protection | Discover, classify, and protect sensitive information.                                                                 |
| Security                  | Security Command Center, Web Security Scanner | Microsoft Defender for Cloud          | Cloud-native application protection platform (CNAPP) with security measures and practices to protect cloud-based applications. |
| Threat detection          | Event Threat Detection              | Microsoft Defender for Identity       | Cloud-based security solution for identity monitoring.                                                                   |
| SIEM                      | Chronicle                           | Microsoft Sentinel                    | Cloud-native security information and event manager (SIEM) platform with built-in AI for analyzing large volumes of data. |
| Container security        | Container Security                  | Container Security in Microsoft Defender for Cloud | Azure-native solution for securing containers.                                                                        |
| Artifact Registry         |                                      | Azure Container Registry             

 | Managed, private Docker registry service for storing and managing private Docker container images and related artifacts. |

## Storage

### Object Storage
| Google Cloud service               | Azure service          | Description                                                                                                              |
|------------------------------------|------------------------|--------------------------------------------------------------------------------------------------------------------------|
| Cloud Storage, Cloud Storage for Firebase | Azure Blob storage   | Object storage service for use cases including cloud applications, content distribution, backup, archiving, and big data analytics. |

### Block Storage
| Google Cloud service  | Azure service      | Description                                                                                             |
|-----------------------|--------------------|---------------------------------------------------------------------------------------------------------|
| Persistent Disk, Local SSD | Azure managed disks | SSD storage optimized for I/O intensive read/write operations for high-performance Azure virtual machine storage. |

### File Storage
| Google Cloud service   | Azure service                | Description                                                                  |
|------------------------|------------------------------|------------------------------------------------------------------------------|
| Filestore              | Azure Files, Azure NetApp Files | File-based storage and hosted NetApp Appliance Storage.                       |
| Google Drive           | OneDrive For Business        | Cloud storage and file sharing solution for businesses.                       |

## Bulk Data Transfer
| Google Cloud service      | Azure service               | Description                                                                                 |
|---------------------------|-----------------------------|---------------------------------------------------------------------------------------------|
| Transfer Appliance        | Azure Import/Export         | Data transport solution using secure disks and appliances to transfer large amounts of data. |
| Transfer Appliance        | Azure Data Box              | Petabyte- to exabyte-scale data transport solution using secure data storage devices.        |

## Application Services
| Google Cloud service     | Azure service           | Description                                                                                             |
|--------------------------|-------------------------|---------------------------------------------------------------------------------------------------------|
| App Engine               | Azure App Service       | Managed hosting platform providing easy-to-use services for deploying and scaling web applications.      |
| Apigee                   | Azure API Management    | Turnkey solution for publishing APIs to external and internal consumers.                                 |

## Miscellaneous

### Workflow
| Google Cloud service | Azure service    | Description                                                                                                              |
|----------------------|------------------|--------------------------------------------------------------------------------------------------------------------------|
| Composer             | Azure Logic Apps | Serverless technology for connecting apps, data, and devices anywhere, whether on-premises or in the cloud.              |

### Enterprise Application Services
| Google Cloud service | Azure service     | Description                                                                                   |
|----------------------|-------------------|-----------------------------------------------------------------------------------------------|
| G Suite              | Microsoft 365     | Fully integrated cloud service providing communications, email, document management in the cloud. |

### Gaming
| Google Cloud service | Azure service  | Description                                                               |
|----------------------|----------------|---------------------------------------------------------------------------|
| Game Servers         | Azure PlayFab  | Managed services for hosting dedicated game servers.                      |

### Hybrid
| Google Cloud service | Azure service  | Description                                                               |
|----------------------|----------------|---------------------------------------------------------------------------|
| Anthos               | Azure Arc      | Simplify complex and distributed environments across on-premises, edge, and multi-cloud. |

### Blockchain
| Google Cloud service | Azure service                 | Description                                                              |
|----------------------|-------------------------------|--------------------------------------------------------------------------|
| Digital Asset        | Azure Confidential Ledger     | Tamperproof, unstructured data store hosted in trusted execution environments. |

### Monitoring
| Google Cloud service | Azure service                   | Description                                                                                |
|----------------------|---------------------------------|--------------------------------------------------------------------------------------------|
| Cloud Monitoring     | Application Insights            | Service providing visibility into the performance, uptime, and overall health of cloud-powered applications. |

### Logging
| Google Cloud service | Azure service     | Description                                                                                 |
|----------------------|-------------------|---------------------------------------------------------------------------------------------|
| Cloud Logging        | Log Analytics     | Service for real-time log management and analysis.                                          |

## Migration Tools

### App Migration to Containers
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| Migrate for Anthos          | Azure Migrate: App Containerization tool         | Modernize your application by migrating it to AKS or App Services containers. |

### Migration of Virtual Machines
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| Migrate for Compute Engine  | Azure Migrate: Server Migration tool             | Migrate servers from anywhere to Azure.                                  |

### VMware Migration
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| Google Cloud VMware Engine  | Azure VMware Solution                            | Move or extend on-premises VMware environments to Azure.                 |

### Migration of Databases
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| Database Migration Service  | Azure Database Migration Service                 | Enable seamless migrations from multiple database sources to Azure data platforms with minimal downtime. |

### Migration Programs
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| Google Cloud Rapid Assessment & Migration Program (RAMP) | Azure Migration and Modernization Program | Learn how to move your apps, data, and infrastructure to Azure using a proven cloud migration and modernization approach. |

### Server Assessment
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
|                             | Movere                                           | Increases business intelligence by accurately presenting entire IT environments within a single day. |

### Database Assessment
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
|                             | Data Migration Assistant                         | Helps pinpoint potential problems blocking migration and identifies unsupported features and new beneficial features. |

### Web App Assessment and Migration
| Google Cloud service        | Azure service                                    | Description                                                             |
|-----------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
|                             | Web app migration assistant                      | Assess on-premises web apps and migrate them to Azure.                  |