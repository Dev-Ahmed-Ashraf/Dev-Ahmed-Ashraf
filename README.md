<div align="center">

  <h1>Ahmed Ashraf El-Sayed</h1>
  <h3>Full Stack .NET & AI Systems Engineer</h3>

  <p>
    Building production-grade enterprise applications, event-driven backends, and AI-powered systems using <b>ASP.NET Core 8</b>, <b>Angular</b>, <b>Azure</b>, and <b>RAG / Tool-Calling AI Workflows</b>.
  </p>

  <p>
    <a href="https://dev-ahmed-ashraf.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-dev--ahmed--ashraf.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
    <a href="https://linkedin.com/in/dev-ahmed-ashraf"><img src="https://img.shields.io/badge/LinkedIn-Ahmed_Ashraf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
    <a href="mailto:ahmedashraf01085@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedashraf01085@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
    <a href="https://github.com/Dev-Ahmed-Ashraf"><img src="https://img.shields.io/badge/Location-Cairo,%20Egypt%20(Remote%20Worldwide)-24292e?style=for-the-badge&logo=github&logoColor=white" alt="Location"></a>
  </p>

  <br />

</div>

---

### 👤 Professional Summary

I am a **Full Stack .NET Developer & AI Systems Engineer** with hands-on experience building enterprise web applications, microservices, and AI-driven solutions. 

My backend philosophy relies on **Clean Architecture**, **CQRS (MediatR)**, and **Domain-Driven Design**. I specialize in bridging traditional high-throughput .NET backends with modern AI capabilities—including **Retrieval-Augmented Generation (RAG)**, **Qdrant Vector Databases**, **Ollama embeddings**, and **Autonomous LLM Tool Calling (Groq LLaMA 3.3)**.

* 💼 **Current Focus**: Architecting asynchronous RAG ingestion pipelines, resilient event-driven microservices with RabbitMQ & MassTransit, and deploying containerized Azure applications with automated CI/CD.
* 🌍 **Target Roles**: Open to **Full-Time Remote Roles** worldwide & high-impact engineering contracts.

---

### 🛠️ Technical Skills

| Category | Technologies & Tools |
| :--- | :--- |
| **Backend Core** | `C#` `.NET 8 / ASP.NET Core` `ASP.NET MVC` `RESTful APIs` `Entity Framework Core` `LINQ` |
| **AI Engineering** | `LLM Integration` `Groq LLaMA 3.3` `RAG Pipelines` `Tool Calling` `Qdrant Vector DB` `Ollama (nomic-embed-text)` `Semantic Search` |
| **Architecture & Design** | `Clean Architecture` `CQRS (MediatR)` `Microservices` `Event-Driven Architecture` `Outbox Pattern` `FluentValidation` `AutoMapper` |
| **Distributed Systems** | `RabbitMQ` `MassTransit` `Background Processing (IHostedService / Channels)` `Dead-Letter Handling` |
| **Cloud & DevOps** | `Microsoft Azure (App Service, ACR, SQL DB, Key Vault)` `Azure Bicep (IaC)` `Docker` `GitHub Actions (OIDC)` `Azure DevOps` |
| **Frontend & UI** | `Angular` `TypeScript` `RxJS` `Tailwind CSS` `JavaScript` `AJAX` |
| **Database & Security** | `SQL Server` `T-SQL` `Stored Procedures` `Indexing` `JWT + Refresh Tokens` `RBAC` `OpenID Connect (OIDC)` `xUnit` `Moq` |

---

### 💼 Professional Experience

🏢 Full Stack .NET Developer Intern @ Digital Business Systems (DBS MENA) | Cairo, Egypt (Apr 2026 – Jun 2026) ├── Developed production-grade Product Management System using ASP.NET Core and Angular within an Agile setup. ├── Designed and secured RESTful APIs using Clean Architecture, CQRS (MediatR), EF Core, and SQL Server. └── Implemented JWT authentication, permission-based authorization, and dynamic frontend Angular features.

💻 Backend Developer Intern @ Code Way | Remote (Sep 2025 – Jan 2026) ├── Developed Distributed Notifications Microservice supporting 3 delivery channels (In-App, Email, Push). ├── Built event-driven communication using RabbitMQ & MassTransit with retry policies and dead-letter handling. └── Applied Transactional Outbox Pattern, Background Services, CQRS, and Stored Procedures for data integrity.

---

### 🚀 Featured Projects

#### 1. 🤖 [AI Product Intelligence Platform](https://github.com/Dev-Ahmed-Ashraf/ProductManagement)
> **Full Stack AI-Powered Product Management Platform built with ASP.NET Core 8 & Angular**

* **Autonomous Tool Calling**: Built an AI assistant using Groq LLaMA 3.3 that executes actions (creating products, filtering catalog, querying knowledge base) via structured tool-calling handlers.
* **Asynchronous RAG Pipeline**: Engineered a non-blocking PDF ingestion queue (`IBackgroundTaskQueue`) that extracts text via `PdfPig`, embeds via `Ollama`, and stores vectors in `Qdrant` for semantic similarity search.
* **Enterprise Security**: Secured with 9 claims-based permissions, JWT bearer auth with refresh tokens, and audit trail interceptors.
* 🛠️ `ASP.NET Core 8` `Angular 21` `Groq LLaMA 3.3` `Qdrant` `Ollama` `Clean Architecture` `CQRS` `SQL Server`

[📦 GitHub Repository](https://github.com/Dev-Ahmed-Ashraf/ProductManagement) • [🌐 Live Demo](https://dev-ahmed-ashraf.vercel.app/)

---

#### 2. 🏨 [Hotel Booking Platform API](https://github.com/Dev-Ahmed-Ashraf/Hotel-Booking-API)
> **Modular ASP.NET Core 8 API with 40+ RESTful Endpoints & Stripe Payments**

* **Domain Design**: Built 7 core domain modules (Hotels, Rooms, Availability, Bookings, Reviews, Payments, Offers) following Clean Architecture & CQRS.
* **Idempotent Payments**: Integrated Stripe payment workflows with idempotent `PaymentIntent` processing and webhook listeners for reliable booking synchronization.
* **Infrastructure & CI/CD**: Automated Azure infrastructure provisioning using Bicep (App Service, Azure SQL, ACR, Key Vault) and GitHub Actions CI/CD with Docker & OIDC.
* 🛠️ `.NET 8` `CQRS` `EF Core` `Stripe Webhooks` `Serilog` `Docker` `Azure Bicep` `GitHub Actions`

[📦 GitHub Repository](https://github.com/Dev-Ahmed-Ashraf/Hotel-Booking-API)

---

#### 3. 📨 [Distributed Notifications Microservice](https://github.com/Dev-Ahmed-Ashraf/Notifications-Microservice)
> **Event-Driven Messaging Service for Distributed Systems**

* **Multi-Channel Dispatch**: Consumes domain events from RabbitMQ / MassTransit to dispatch in-app, email, and push notifications.
* **Transactional Reliability**: Guarantees zero message loss using the Transactional Outbox Pattern, background workers, and dead-letter queues.
* 🛠️ `ASP.NET Core` `RabbitMQ` `MassTransit` `Outbox Pattern` `Background Services` `SQL Server`

[📦 GitHub Repository](https://github.com/Dev-Ahmed-Ashraf/Notifications-Microservice)

---

#### 4. 🛒 [Full-Stack E-Commerce Platform](https://github.com/Dev-Ahmed-Ashraf/ECommerce-Platform)
> **Scalable E-Commerce Backend & Interactive Web Application**

* **Full Lifecycle Support**: Product catalog management, shopping cart, order processing, wishlist, and 3-role administration (Admin, Manager, Customer).
* **Performance**: Enhanced user experience with AJAX partial page renders and LINQ query optimization.
* 🛠️ `ASP.NET Core MVC` `EF Core` `SQL Server` `ASP.NET Identity` `AJAX` `Bootstrap`

[📦 GitHub Repository](https://github.com/Dev-Ahmed-Ashraf/ECommerce-Platform)

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

I am actively open to discussing **full-stack & backend remote opportunities**, **AI systems architecture**, and **technical collaborations**.

* 📧 **Email**: [ahmedashraf01085@gmail.com](mailto:ahmedashraf01085@gmail.com)
* 💼 **LinkedIn**: [linkedin.com/in/dev-ahmed-ashraf](https://linkedin.com/in/dev-ahmed-ashraf)
* 🌐 **Portfolio**: [dev-ahmed-ashraf.vercel.app](https://dev-ahmed-ashraf.vercel.app/)
* 📍 **Location**: Cairo, Egypt (UTC+2 / UTC+3, flexible hours for global teams)

---

<div align="center">
  <p><i>"Building robust backends today; shaping intelligent distributed systems for tomorrow."</i></p>
</div>
