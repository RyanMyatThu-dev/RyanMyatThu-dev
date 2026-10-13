<div align="center">

# Hi there, I'm Ye Myat Thu (Ryan) 👋

### **First-Year ICE Student @ Chulalongkorn University**
**Software Engineer | Cloud Backend & Full-Stack Developer**

*Building resilient serverless cloud architectures, real-time web applications, and networked systems.*

[![Status](https://img.shields.io/badge/Status-Seeking%20Internship%20%2F%20Part--Time%20Roles-brightgreen?style=for-the-badge)](mailto:ryanmyatthu@gmail.com)
<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ye%20Myat%20Thu-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ye-myat-thu-51733b419/)
[![GitHub](https://img.shields.io/badge/GitHub-RyanMyatThu--dev-181717?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev)
[![Email](https://img.shields.io/badge/Email-ryanmyatthu%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:ryanmyatthu@gmail.com)
[![University](https://img.shields.io/badge/Chulalongkorn%20University-B.Eng%20in%20ICE-pink?style=flat-square)](https://www.chula.ac.th/)

---

</div>

## 🎯 Profile & Career Objective

I am a first-year undergraduate studying **Information and Communication Engineering (ICE) at Chulalongkorn University**, combining solid computer engineering foundations with hands-on experience in production cloud systems. 

Beyond foundational coursework, I have engineered and deployed **event-driven serverless architectures on AWS**, **real-time healthcare clinic management backends in .NET 8**, and **secure networked tools in Python**. 

> **Actively seeking Software Engineering Internships or Part-Time Developer roles** (Bangkok, Hybrid, or Remote) where I can contribute to production backends (.NET / Python / Node.js), cloud infrastructure (AWS), or modern web applications (React / Next.js / TypeScript).

---

## 🛠️ Technical Skills

- **Languages:** C# (.NET 8 / .NET 10), TypeScript, JavaScript, Python 3.12, Dart, SQL, Bash
- **Backend & APIs:** ASP.NET Core Web API, Entity Framework Core, SignalR (WebSockets), RESTful APIs, Clean / Feature-Based Architecture, Result Pattern, Model Context Protocol (MCP)
- **Cloud & DevOps:** AWS (Lambda, API Gateway HTTP API v2, EventBridge Scheduler, SQS DLQ, EC2, SSM Parameter Store, IAM / OIDC, CloudFormation IaC), Supabase, Vercel, Docker, GitHub Actions (OIDC CI/CD), Astral `uv`
- **Frontend & Mobile:** React 18/19, Next.js, Vite, Tailwind CSS, DaisyUI, Radix UI, Flutter (Riverpod)
- **Databases & Storage:** PostgreSQL, SQLite, AWS S3, Cloudinary
- **Tools & Environments:** Git, Linux / Bash, Neovim, Serilog, Scalar / Swagger UI

---

## 📂 Featured Portfolio Case Studies

### 1. Financial Management & Student Budget Tracker (`st-finance`)
*Full-Stack Serverless Cloud Architecture & Autonomous Cron Workflows*

[![Live Demo](https://img.shields.io/badge/Live%20Application-st--finance.vercel.app-success?style=flat-square&logo=vercel)](https://st-finance.vercel.app/)
[![GitHub Repo](https://img.shields.io/badge/Repository-FinancialManagement-blue?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev/FinancialManagement)

- **The Challenge:** Traditional personal finance applications either rely on expensive, always-on servers or fail to solve the real spending habits of students on fixed monthly budgets.
- **The Solution:** Engineered a containerless, auto-scaling serverless web app powered by an ASP.NET Core 10 Web API on AWS Lambda behind HTTP API Gateway v2, paired with Next.js on Vercel and Supabase PostgreSQL.
- **Cloud Engineering & Resilience:**
  - Designed cron automation using **Amazon EventBridge Scheduler** invoking a dedicated jobs Lambda to execute hourly recurring schedules and midnight daily quota recalibrations (Asia/Bangkok timezone) without persistent background processes.
  - Implemented an encrypted **SQS Dead-Letter Queue (DLQ)** and CloudWatch alarms to catch retry exhausts, backed by database idempotency keys.
  - Hardened deployment security using **GitHub Actions with AWS OpenID Connect (OIDC)** federated authentication, eliminating static IAM credentials, and provisioned via CloudFormation IaC and SSM Parameter Store.
- **Domain Innovation:** Integrated a **Dynamic Safe-to-Spend Quota** and **50-Baht Canteen Meal Index**, translating complex student budgets into concrete meal allowances.

---

### 2. Smart Clinic Management System (`SCMS / KuMel`)
*Enterprise Healthcare Workflow Platform & Real-Time Queue Orchestration*

[![GitHub Repo](https://img.shields.io/badge/Repository-SCMS%20%2F%20KuMel-blue?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev/KuMel)

- **The Challenge:** Small-to-medium clinical practices face operational delays caused by desynchronized patient queues, paper records, and inventory waste due to expired pharmaceuticals.
- **The Solution:** Architected an end-to-end clinical management hub following Feature-Based Organization and the `Result<T>` pattern in ASP.NET Core Web API (.NET 8) with dual frontends (React 18 Web App and Flutter Mobile Client).
- **Key Engineering Achievements:**
  - **Real-Time Queue Orchestration:** Implemented SignalR WebSockets for zero-latency queue dispatch and real-time waiting list updates across doctor, receptionist, and patient screens.
  - **Smart Inventory & EMR:** Automated FIFO pharmaceutical stock tracking with batch expiration warnings, diagnostic catalogs, and reusable digital prescription templates.
  - **Financial & Document Pipelines:** Built automated billing with payment slip verification, Cloudinary asset storage, and programmatic medical invoice PDF generation via DinkToPdf.
  - **AI Integration:** Embedded an intelligent clinic assistant connected via Anthropic’s **Model Context Protocol (MCP)**.

---

### 3. NEON / CHAT (`TCP-Chat`)
*Encrypted TCP Terminal Socket Engine & Cost-Optimized Cloud Infrastructure*

[![Live Guide](https://img.shields.io/badge/Live%20Guide-ryanmyatthu--dev.github.io%2FTCP--Chat-cyan?style=flat-square&logo=githubpages)](https://ryanmyatthu-dev.github.io/TCP-Chat/)
[![GitHub Repo](https://img.shields.io/badge/Repository-TCP--Chat-blue?style=flat-square&logo=github)](https://github.com/RyanMyatThu-dev/TCP-Chat)

- **The Challenge:** Modern communication software often carries heavyweight web dependencies, high idle infrastructure costs, and unnecessary telemetry.
- **The Solution:** Built a terminal-native, neo-cyberpunk socket chat application in Python 3.12 utilizing custom length-prefixed packet framing and verified TLS encryption.
- **Key Engineering Achievements:**
  - **Protocols & Security:** Developed low-level socket communication with room isolation and shared password authentication over TLS certificates.
  - **Cost-Optimized Cloud Hosting:** Hosted the server on AWS EC2 (`ap-southeast-1` Singapore) with automated session monitoring and CloudFormation-managed auto-shutdown after 3 hours to eliminate idle costs.
  - **Frictionless Packaging:** Created zero-dependency cross-platform installers for Linux/macOS (`curl | sh`) and Windows (`irm | iex`) leveraging Astral `uv` tool isolation.
  - **Web Companion:** Deployed an animated React + Vite connection guide to GitHub Pages.

---

### 4. Cloud Architecture Visualizer (`Lambda_Deployment`)
*Programmatic Technical Explanations of Serverless Execution Lifecycles*

- **Technical Direction:** Developed mathematical vector animations in Python using **Manim Community Edition** to visually dissect serverless cloud mechanics.
- **Topics Illustrated:** Local ASP.NET Core packaging -> S3 deployment artifact staging -> CloudFormation control-plane deployment -> HTTP API Gateway request transformation into the .NET hosting pipeline.

---

## 🎓 Education

**Chulalongkorn University** | Bangkok, Thailand  
*Bachelor of Engineering (B.Eng.) in Information and Communication Engineering (ICE)*  
*Expected Graduation: 2029 (Currently First Year)*  
- Relevant Studies: Computer Programming, Object-Oriented Programming, Data Structures & Algorithms, Digital Systems.

---

## 📬 Let's Connect

- **LinkedIn:** [linkedin.com/in/ye-myat-thu-51733b419](https://www.linkedin.com/in/ye-myat-thu-51733b419/)
- **Email:** [ryanmyatthu@gmail.com](mailto:ryanmyatthu@gmail.com)
- **GitHub:** [@RyanMyatThu-dev](https://github.com/RyanMyatThu-dev)
- **Location:** Bangkok, Thailand (Available for On-site, Hybrid, or Remote roles)

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RyanMyatThu-dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Ryan's GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RyanMyatThu-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />

<br/>
<sub>Crafted with precision for scalable systems. Open to new challenges!</sub>

</div>
