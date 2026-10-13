<div align="center">

# Hi there, I'm Ryan Myat Thu 👋

### **ICE Student & Developer**
*Building resilient serverless architectures, real-time applications, and full-stack systems.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-RyanMyatThu--dev-181717?style=for-the-badge&logo=github)](https://github.com/RyanMyatThu-dev)
[![Email](https://img.shields.io/badge/Email-ryanmyatthu%40gmail.com-EA4335?style=for-the-badge&logo=gmail)](mailto:ryanmyatthu@gmail.com)

---

</div>

## 👨‍💻 About Me

I am an Information and Communication Engineering (ICE) student and software developer focused on building scalable cloud architectures, event-driven backends, and robust full-stack applications. My core technical domain centers on **.NET / C#**, **AWS Serverless infrastructure**, **TypeScript / React**, and **Python systems programming**.

- ☁️ **Cloud & Infrastructure**: Designing production-ready AWS architectures utilizing Lambda, HTTP API Gateway, EventBridge Scheduler, SQS Dead-Letter Queues, and CloudFormation Infrastructure-as-Code (IaC) with secure GitHub Actions OIDC pipelines.
- ⚡ **Backend Engineering**: Architecting high-throughput ASP.NET Core Web APIs, SignalR real-time websocket synchronization, and secure TLS socket networking protocols.
- 🎨 **Full-Stack & Mobile**: Delivering responsive, accessible user interfaces with Next.js, React, Tailwind CSS, and cross-platform mobile apps with Flutter.

---

## 🚀 Featured Engineering Projects

### 1. [Financial Management & Student Budget Tracker](https://github.com/RyanMyatThu-dev/FinancialManagement)
> **Full-Stack Serverless Cloud Platform with Event-Driven Automation**
> 
> [![Live Demo](https://img.shields.io/badge/Live%20App-st--finance.vercel.app-success?style=flat-square&logo=vercel)](https://st-finance.vercel.app/)
> [![GitHub Repo](https://img.shields.io/badge/Source-FinancialManagement-blue?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev/FinancialManagement)
> `ASP.NET Core 10` `AWS Lambda` `API Gateway v2` `Next.js` `Supabase PostgreSQL` `EventBridge` `SQS DLQ` `CloudFormation` `OIDC`

* **Serverless Cloud Architecture**: Deployed as an ASP.NET Core Web API on AWS Lambda behind HTTP API Gateway v2, paired with a Next.js frontend hosted on Vercel and Supabase PostgreSQL with pooled connection routing.
* **Autonomous Cron Scheduling**: Implemented EventBridge Scheduler to trigger a dedicated serverless Jobs Lambda executing hourly recurring expense calculations and midnight daily quota recalibrations (Asia/Bangkok timezone) without persistent background worker processes.
* **Resilience & Fault Tolerance**: Engineered an encrypted SQS Dead-Letter Queue (DLQ) with CloudWatch alarms capturing exhausted scheduler and Lambda delivery retries; strictly enforces database uniqueness constraints for idempotent execution.
* **Enterprise DevSecOps Pipeline**: Automated staging and production deployment via GitHub Actions utilizing short-lived AWS OpenID Connect (OIDC) federated tokens (eliminating permanent IAM credentials) and CloudFormation IaC with AWS SSM Parameter Store (`SecureString`).
* **Domain Innovation**: Designed a **Dynamic Safe-to-Spend Quota** and localized **Canteen Meal Index** converting abstract monetary allowances into tangible daily meal units.

---

### 2. [Smart Clinic Management System (SCMS / KuMel)](https://github.com/RyanMyatThu-dev/KuMel)
> **Enterprise-Grade Clinical Workflow & Healthcare Practice Platform**
> 
> [![GitHub Repo](https://img.shields.io/badge/Source-SCMS%20%2F%20KuMel-blue?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev/KuMel)
> `.NET 8` `ASP.NET Core Web API` `EF Core 8` `SignalR` `React 18` `Flutter` `PostgreSQL` `MCP (Model Context Protocol)`

* **Clean Feature-Driven Architecture**: Structured using Feature-based Organization with the `Result<T>` pattern, hosting cohesive business workflows, controllers, and validation layers across multi-tenant clinic roles (Doctors, Receptionists, Pharmacists, Admins).
* **Real-Time Queue Orchestration**: Implemented SignalR WebSockets for zero-latency queue status synchronization and state updates across practitioner dashboards and patient displays.
* **Pharmaceutical & Medical Records (EMR)**: Built automated FIFO pharmaceutical inventory tracking with expiration batch monitoring, disease diagnostic catalogs, and reusable electronic prescription templates.
* **Billing & Asset Automation**: Integrated automated billing pipelines with payment slip verification, Cloudinary asset storage, and programmatic medical invoice PDF generation via DinkToPdf.
* **Multi-Client & AI Integration**: Developed dual frontends—a responsive React 18 Web App (Vite, Tailwind CSS, DaisyUI, i18n localization) and a Flutter mobile client (Riverpod, Dio)—plus an AI clinic assistant integrated via Anthropic's Model Context Protocol (MCP).

---

### 3. [NEON / CHAT](https://github.com/RyanMyatThu-dev/TCP-Chat)
> **Encrypted TCP Terminal Chat Engine & Cloud-Hosted Socket Infrastructure**
> 
> [![Live Guide](https://img.shields.io/badge/Live%20Guide-Interactive%20Docs-cyan?style=flat-square&logo=githubpages)](https://ryanmyatthu-dev.github.io/TCP-Chat/)
> [![GitHub Repo](https://img.shields.io/badge/Source-TCP--Chat-blue?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev/TCP-Chat)
> `Python 3.12` `Raw Sockets` `TLS / SSL` `AWS EC2` `CloudFormation` `Astral uv` `React`

* **Network Protocols & Security**: Engineered a client-server socket protocol over verified TLS encryption featuring length-prefixed packet framing, room isolation, and shared-password authentication.
* **Cost-Aware Cloud Infrastructure**: Hosted on AWS EC2 (`ap-southeast-1` Singapore) with automated session management and CloudWatch-triggered auto-shutdown after three hours of runtime to minimize cloud expenditures.
* **Zero-Dependency Distribution**: Packaged for cross-platform distribution using Astral `uv` tool isolation, featuring customized ASCII installers executable directly via `curl | sh` (Unix) and PowerShell (Windows).
* **Interactive Web Companion**: Built an animated retro-cyberpunk installation and room invitation guide in React + Vite, deployed on GitHub Pages.

---

### 4. [Cloud Explained — Serverless Architecture Animations](https://github.com/RyanMyatThu-dev)
> **Programmatic Technical Explanations of Cloud Computing & Serverless Systems**
> 
> `Python` `Manim Community Edition` `AWS Architecture` `ASP.NET Core on Lambda`

* **Programmatic Visual Explanations**: Developed mathematical-quality educational vector animations in Python using Manim Community Edition detailing serverless mechanics.
* **Architectural Coverage**: Illustrated ASP.NET Core Lambda deployment lifecycles, S3 artifact staging, CloudFormation resource deployment, and HTTP API Gateway event conversion into the ASP.NET Core middleware pipeline.

---

## 🛠️ Technical Skills & Arsenal

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Backend & Systems** | C# (.NET 8 / .NET 10), ASP.NET Core Web API, Entity Framework Core, SignalR, Python 3.12 (AsyncIO, Sockets), Model Context Protocol (MCP), RESTful APIs |
| **Cloud & DevOps** | AWS (Lambda, API Gateway HTTP API v2, EventBridge, SQS DLQ, EC2, SSM, IAM, CloudFormation), Supabase, Vercel, Docker, GitHub Actions (OIDC CI/CD) |
| **Frontend & Mobile** | React, Next.js, TypeScript, Vite, Tailwind CSS, DaisyUI, Radix UI, Flutter (Dart, Riverpod) |
| **Databases & Storage** | PostgreSQL, SQLite, AWS S3, Cloudinary |
| **Tools & Practices** | Git, Astral `uv`, Neovim, Linux / Bash, Serilog, Swagger / Scalar, Clean Architecture, Result Pattern |

---

## 📈 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RyanMyatThu-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Ryan's GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RyanMyatThu-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />

</div>

---

<div align="center">
  <sub>Crafted with passion for clean code and cloud architecture. Let's connect!</sub>
</div>
