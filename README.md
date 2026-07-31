<div align="center">

  <h1>Ahmed Ashraf El-Sayed</h1>
  <h3>Junior Full Stack .NET Developer</h3>

  <p>
    I build modern backend applications using ASP.NET Core, Clean Architecture, CQRS, and AI integrations. I enjoy creating production-ready APIs and intelligent software powered by RAG, vector search, and tool calling.
  </p>

  <p>
    <a href="https://dev-ahmed-ashraf.vercel.app"><img src="https://img.shields.io/badge/Portfolio-dev--ahmed--ashraf.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
    <a href="https://linkedin.com/in/dev-ahmed-ashraf"><img src="https://img.shields.io/badge/LinkedIn-Ahmed_Ashraf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
    <a href="mailto:ahmedashraf01085@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedashraf01085@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
    <a href="https://github.com/Dev-Ahmed-Ashraf"><img src="https://img.shields.io/badge/Location-Cairo,%20Egypt%20(Remote%20Worldwide)-24292e?style=for-the-badge&logo=github&logoColor=white" alt="Location"></a>
  </p>

  <br />

</div>

---

### 👤 Professional Overview

I am a **Backend Engineer** with deep expertise in **.NET 8 / ASP.NET Core**, **Distributed Event-Driven Architectures**, and **AI System Engineering (RAG & Agent Tool Calling)**.

My engineering philosophy centers around **Clean Architecture**, **CQRS (MediatR)**, **Domain-Driven Design**, and robust distributed patterns like the **Transactional Outbox Pattern** and **Idempotent Webhooks**. I bridge modern cloud infrastructure (Azure, Docker, Bicep IaC) with bleeding-edge AI capabilities—enabling enterprise backends to process high-throughput workloads while integrating natural language intelligence.

* 💼 **Current Focus**: Designing fault-tolerant microservices, building asynchronous AI document ingestion pipelines (RAG), and deploying cloud-native .NET systems to Azure with automated GitHub Actions (OIDC).
* 🌍 **Work Mode**: Open to **International Remote Roles** and high-impact engineering contracts.

---

### 🧠 Core Competencies & Architecture Focus

```
 🌐 Cloud & IaC (Azure, Bicep, Docker, GitHub Actions CI/CD with OIDC)
 └── ⚡ Core Backend (.NET 8 REST APIs, Clean Architecture, CQRS, EF Core, SQL Server)
      └── 🔄 Distributed Systems (RabbitMQ, MassTransit, Outbox Pattern, Channel Background Queues)
           └── 🤖 AI Systems Engineering (Groq LLaMA 3.3, Qdrant Vector DB, Ollama, Tool-Calling Agents, RAG Pipelines)
```

---

### 🛠️ Technical Skills

| Skill Category | Tools & Technologies |
| :--- | :--- |
| **Backend Core** | `C#` `.NET 8 / ASP.NET Core` `ASP.NET MVC` `RESTful Web APIs` `MediatR` `FluentValidation` `AutoMapper` |
| **AI Systems & RAG** | `Groq API (LLaMA-3.3-70B)` `Qdrant Vector DB` `Ollama (nomic-embed-text)` `Agentic Tool Calling` `PDF RAG Pipelines` |
| **Distributed Systems** | `RabbitMQ` `MassTransit` `Transactional Outbox Pattern` `Background Services (IHostedService)` `Channel Queues` |
| **Cloud & DevOps** | `Microsoft Azure` `Bicep (IaC)` `Docker` `GitHub Actions (OIDC CI/CD)` `Azure Container Registry` `Azure Key Vault` |
| **Data & Databases** | `SQL Server` `T-SQL` `Entity Framework Core` `LINQ` `Stored Procedures` `Database Indexing & Transactions` |
| **Security & Quality** | `JWT Auth + Refresh Tokens` `RBAC & Claims Authorization` `OpenID Connect (OIDC)` `Serilog` `xUnit` `Moq` |

---

### 🚀 Featured Projects

<div align="center">
  <br />
</div>

#### 1. 🤖 [AI Product Intelligence Platform](https://github.com/Dev-Ahmed-Ashraf/ProductManagement)
> **Enterprise Product Management Platform powered by Groq LLaMA 3.3, Qdrant Vector DB & Angular 21**

* **Architecture**: Clean Architecture + CQRS (MediatR), ASP.NET Core 8, Angular 21, SQL Server.
* **AI Tool Calling**: Autonomous AI Agent powered by Groq LLaMA 3.3 with 10-loop tool execution for creating products, filtering data, and knowledge querying via natural language.
* **RAG Pipeline**: Asynchronous PDF ingestion queue using `IBackgroundTaskQueue` channel, text extraction via `PdfPig`, vector embedding generation via local Ollama (`nomic-embed-text`), and vector similarity search in `Qdrant`.
* **Security & Reliability**: 9 granular claims-based permissions, JWT authentication with refresh token rotation, and status lifecycle auditing.
* 🛠️ `ASP.NET Core 8` `Angular 21` `Groq LLaMA 3.3` `Qdrant` `Ollama` `Clean Architecture` `CQRS`

[📦 Repository](https://github.com/Dev-Ahmed-Ashraf/ProductManagement) • [🌐 Live Demo](https://dev-ahmed-ashraf.vercel.app/)

---

#### 2. 🏨 [Production-Grade Hotel Booking Platform API](https://github.com/Dev-Ahmed-Ashraf/Hotel-Booking-API)
> **Modular Enterprise Backend with 40+ Endpoints, Stripe Payments & Azure IaC**

* **API Core**: Designed and implemented 40+ RESTful endpoints across 7 core domain modules (Hotels, Rooms, Availability, Bookings, Reviews, Payments, Offers).
* **Payment Reliability**: Integrated Stripe payment processing with idempotent `PaymentIntent` creation and webhook handlers to guarantee transaction consistency.
* **Infrastructure & CI/CD**: Provisioned Azure infrastructure (App Service, Azure SQL, ACR, Key Vault) using Bicep Infrastructure-as-Code. Built automated GitHub Actions CI/CD pipelines deploying Docker containers via OpenID Connect (OIDC) and Azure Managed Identities.
* 🛠️ `.NET 8` `CQRS` `EF Core` `Stripe Webhooks` `Docker` `Azure Bicep` `GitHub Actions (OIDC)` `Serilog`

[📦 Repository](https://github.com/Dev-Ahmed-Ashraf/Hotel-Booking-API)

---

#### 3. 📨 [Distributed Event-Driven Notifications Microservice](https://github.com/Dev-Ahmed-Ashraf/Notifications-Microservice)
> **High-Throughput Distributed Messaging Service with MassTransit & RabbitMQ**

* **Event-Driven Messaging**: Built a multi-channel notifications microservice (In-App, Email, Push) consuming domain events across microservice boundaries.
* **Fault Tolerance**: Implemented the Transactional Outbox Pattern to guarantee message persistence before publishing. Engineered retry policies, dead-letter queues, and background processing workers.
* **Code Quality**: Applied CQRS, FluentValidation, EF Core, and Stored Procedures for high data processing efficiency.
* 🛠️ `ASP.NET Core` `RabbitMQ` `MassTransit` `Outbox Pattern` `Background Services` `SQL Server` `Docker`

[📦 Repository](https://github.com/Dev-Ahmed-Ashraf/Notifications-Microservice)

---

#### 4. 🛒 [Full-Stack E-Commerce Platform](https://github.com/Dev-Ahmed-Ashraf/ECommerce-Platform)
> **Scalable E-Commerce Backend & Web Application**

* **Core Features**: Comprehensive e-commerce solution supporting product catalogs, shopping carts, order processing, wishlist features, and multi-tier administration.
* **Access Control**: ASP.NET Identity with role-based authorization for 3 distinct personas (Administrators, Managers, Customers).
* **Performance**: Optimized LINQ queries, EF Core data access layer, and AJAX-driven client interactions to minimize page load latency.
* 🛠️ `ASP.NET Core MVC` `EF Core` `SQL Server` `ASP.NET Identity` `AJAX` `Bootstrap`

[📦 Repository](https://github.com/Dev-Ahmed-Ashraf/ECommerce-Platform)

---

### 📊 GitHub Activity & Performance

<div align="center">

  <img height="185" src="https://github-readme-stats.vercel.app/api?username=Dev-Ahmed-Ashraf&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Ahmed's GitHub Stats" />
  &nbsp;&nbsp;
  <img height="185" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dev-Ahmed-Ashraf&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

</div>

<br />

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dev-Ahmed-Ashraf&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="95%" />
</div>

---

### 📫 Get In Touch

I am actively open to discussing **remote backend opportunities**, **AI systems architecture consulting**, and **technical collaborations**.

* 📧 **Email**: [ahmedashraf01085@gmail.com](mailto:ahmedashraf01085@gmail.com)
* 💼 **LinkedIn**: [linkedin.com/in/dev-ahmed-ashraf](https://linkedin.com/in/dev-ahmed-ashraf)
* 🌐 **Portfolio**: [dev-ahmed-ashraf.vercel.app](https://dev-ahmed-ashraf.vercel.app/)
* 📍 **Location**: Cairo, Egypt (Operating on UTC+2 / UTC+3, flexible working hours for US/EU teams)

---

<div align="center">
  <p><i>"Building robust backends today; shaping intelligent distributed systems for tomorrow."</i></p>
</div>
