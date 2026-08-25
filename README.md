# Azure Data Fundamentals (DP-900) Project – Data Technician Bootcamp

In this repository, I showcase the workbook, lab evidence and supporting materials I completed during the **Azure Data Fundamentals module of the Data Technician Bootcamp**, covering concepts aligned with **Microsoft Azure DP-900**.

## ☁️ Project Overview

During this project, I explored how organisations can store, process, integrate and analyse data using **Microsoft Azure and Microsoft Fabric**.

I developed an understanding of cloud computing fundamentals while working across relational, non-relational and analytical data services.

My practical activities included **Azure SQL Database, Azure Storage, Azure Cosmos DB, Microsoft Fabric, data ingestion, batch processing and stream processing**.

## 🔄 My Cloud Data Architecture

```mermaid
flowchart LR
    A[📁 Data Sources] --> B[🔄 Data Ingestion]

    B --> C[🗄️ Azure SQL Database]
    B --> D[📦 Azure Storage]
    B --> E[🌐 Cosmos DB]
    B --> F[🏞️ Fabric Lakehouse]

    C --> G[📊 Analytics]
    D --> G
    E --> G
    F --> G

    G --> H[📈 Power BI]
    H --> I[💡 Business Insights]
```

## 🛠️ Skills I Demonstrated

### ☁️ Cloud Computing Fundamentals

I developed an understanding of:

* Cloud computing
* Scalability
* Flexibility
* Reliability
* Pay-as-you-go services
* On-premises versus cloud computing

### 🏗️ Cloud Service Models

I explored:

* **IaaS** – Infrastructure as a Service
* **PaaS** – Platform as a Service
* **SaaS** – Software as a Service

### 🌐 Cloud Deployment Models

I learned about:

* Public cloud
* Private cloud
* Hybrid cloud

### 🗄️ Relational Data

Using **Azure SQL Database**, I explored:

* Tables
* Schemas
* Primary keys
* Foreign keys
* Relationships
* Structured data
* Relational data models

### 📦 Non-Relational Data

I also explored:

* Azure Storage Account
* Blob Storage
* Table Storage
* Azure Cosmos DB
* NoSQL concepts
* Structured, semi-structured and unstructured data

### 🏞️ Analytical Workloads

I developed an understanding of:

* Microsoft Fabric
* Fabric Lakehouse
* Data lakes
* Data warehouses
* Fact and dimension tables
* Analytical modelling

### ⚡ Data Ingestion

I explored different approaches to moving data into analytical platforms, including:

* Batch ingestion
* Stream processing
* Eventstreams
* Azure Data Factory
* CSV
* JSON
* Parquet

## 📈 Key Project Activities

### 🧪 Azure Data Labs

I completed practical exercises exploring:

* Azure SQL Database
* Azure Storage
* Azure Cosmos DB
* Microsoft Fabric
* Power BI

These labs helped me understand which Azure services are most appropriate for different types of data and workloads.

### 🐾 Paws & Whiskers Azure Data Solution

I developed an Azure data proposal for a growing retail pet shop that needed to improve how it managed:

* 🧾 Sales
* 👤 Customers
* 📦 Inventory
* 🏷️ Products
* 🚚 Suppliers
* 🎟️ Loyalty information

My proposed workflow included:

```mermaid
flowchart LR
    A[📑 Existing Data]
    --> B[📦 Azure Blob Storage]
    --> C[🔄 Azure Data Factory]
    --> D[🗄️ Azure SQL Database]
    --> E[📊 Power BI]
```

This helped me think about how several Azure services can be combined into a single data architecture.

### ⚡ Batch vs Streaming

I compared two different approaches to processing data:

```mermaid
flowchart TD
    A[📥 Incoming Data]

    A --> B[📦 Batch Processing]
    A --> C[⚡ Stream Processing]

    B --> D[Process data in groups]
    C --> E[Process data as it arrives]

    D --> F[📊 Historical Analysis]
    E --> G[📈 Near Real-Time Analysis]
```

### 🏞️ Microsoft Fabric Lakehouse

I explored how the Lakehouse approach combines concepts from:

**Data Lakes + Data Warehouses**

to support analytical workloads involving different types of data.

## 💡 Working Across Azure Services

One of the most important things I learned was that a modern data solution rarely relies on a single service.

I learned to think about which tool is most appropriate depending on:

* Data structure
* Data volume
* Processing requirements
* Real-time requirements
* Analytical requirements
* Scalability
* Security

## 🎯 Learning Outcomes

By completing this project, I developed an understanding of:

* Microsoft Azure
* Cloud computing
* IaaS, PaaS and SaaS
* Azure SQL Database
* Azure Storage
* Azure Cosmos DB
* Microsoft Fabric
* Lakehouse architecture
* Eventstreams
* Azure Data Factory
* Batch processing
* Stream processing
* Data lakes
* Data warehouses
* Data modelling
* Power BI

## 💻 Tools I Used

`Microsoft Azure` `DP-900` `Azure SQL Database` `Azure Storage` `Azure Cosmos DB` `Microsoft Fabric` `Lakehouse` `Eventstreams` `Azure Data Factory` `Power BI`

## 📁 Project Contents

```text
📦 Azure-Data-Fundamentals
 ┣ ☁️ Azure workbook
 ┣ 🗄️ Azure SQL exercises
 ┃ ┗ 🗄️ 01 - Explore Azure SQL Database
 ┣ 📦 Storage exercises
 ┃ ┗ 📦 02 - Explore Azure Storage
 ┣ 🐾 Azure Cosmos DB exercises
 ┃ ┗ 🐾 03 - Explore Azure Cosmos DB
 ┣ 🏞️ Microsoft Fabric exercises
 ┃ ┗ 🏞️ 04 - Explore data analytics in Microsoft Fabric
 ┣ 📊 Power BI exercises
 ┃ ┗ 📊 05 - Explore fundamentals of data visualization with Power BI
 ┣ 🐾 Paws & Whiskers proposal and example of data visualisation
 ┗ 📄 README.md

```
