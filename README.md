<div align="center">

# 👋 Hi, I'm Muchammad Zalde Zahwa Putra
### **Frontend & Fullstack Software Engineer**
**Building high-performance, type-safe web applications with clean architecture and modern UX**

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1000&color=10B981&center=true&vCenter=true&width=580&lines=Frontend+Developer+(React+19+%2B+TypeScript);Fullstack+Developer+(Next.js+%2B+Go+%2B+Bun);Exploring+AI+%26+Vector+Search+(pgvector);Clean+Code+%2B+Modern+UI+%2B+Continuous+Learning)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/muchammad-zalde-zahwa-putra-20a83b2a7/">
    <img src="https://img.shields.io/badge/Status-Open_for_Opportunities-10B981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" />
  </a>
  <a href="mailto:zaldealberic@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/muchammad-zalde-zahwa-putra-20a83b2a7/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

</div>

---

### 🧑‍💻 About Me

I am a **Software Engineer** focused on developing responsive, modern user interfaces and reliable, well-structured backend systems. I prioritize **clean architecture**, **type safety**, and **defensive validation** to build software that is easy to maintain and scale:

- 🌐 **Frontend Engineering:** Building interactive, high-performance SPAs & SSR applications using React 19, Next.js (App Router), TypeScript, and Tailwind CSS.
- ⚙️ **Backend Engineering:** Developing low-latency RESTful APIs with Golang (Gin), Bun + Elysia.js, and structured MVC/Livewire architectures with Laravel.
- 🗄️ **Database, Cache & AI:** Designing relational schemas (PostgreSQL, MySQL), in-memory caching (Upstash Redis), and semantic vector search using `pgvector`.
- 🧪 **Quality Assurance (QA):** Enforcing strict runtime schema validation (Zod), static type-checking (`tsc`), automated integration tests, and Playwright E2E browser testing.

---

### 🛠️ Core Competencies

| Domain | Core Technologies & Specializations |
| :--- | :--- |
| **Frontend Engineering** | React 19, Next.js 16 (App Router), TypeScript, Tailwind CSS v4, Vanilla CSS Modules, React Hook Form, Recharts, Three.js fundamentals |
| **Backend & Microservices** | Golang (Gin), Bun, Elysia.js, Laravel 11, Node.js, RESTful API Design, JWT Authentication (Argon2id / Bcrypt), Zod Schema Validation |
| **Database, Cache & AI** | PostgreSQL, MySQL, MariaDB, Upstash Redis (Caching & Rate Limiting), Prisma ORM, Drizzle ORM, pgvector (Semantic Search) |
| **Testing, CI/CD & DevOps** | Playwright (E2E Browser Testing), Bun Test Suite, GitHub Actions CI/CD Pipelines, Oxlint / ESLint, Vercel Serverless |

---

### 🌟 Featured Projects

A curated selection of production-deployed applications demonstrating real-world architecture, business workflow handling, and technical depth:

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 01. [Todo List + AI RAG Suite](https://todo-list-zalde.vercel.app/)
**React 19 · TypeScript · Bun · Elysia.js · Upstash Redis · pgvector · Playwright**

A fullstack productivity suite featuring Kanban workflows, semantic AI search (RAG), and real-time calendar synchronization.
- **Modular Monorepo Architecture:** Clean decoupling between frontend (`Vite + React 19`) and backend (`Bun + Elysia.js`), with centralized authentication middleware (`requireAuth`) securing 15+ endpoints.
- **Semantic Vector Search (RAG):** Integrates `pgvector` and Google Gemini embeddings (768-dim) for contextual natural-language task retrieval and automated task breakdown.
- **In-Memory Caching & Rate Limiting:** Utilizes **Upstash Redis** REST integration for low-latency query caching and API abuse prevention on AI endpoints.
- **Live Webcal Subscription (RFC 5545):** Two-way automated schedule synchronization with Google Calendar, Apple Calendar, and Outlook, featuring secure URL/token regeneration.
- **Automated Cron & Email Dispatch:** Scheduled Vercel Cron jobs protected by `CRON_SECRET` dispatching H-3 deadline reminders and overdue notices via responsive dark-mode HTML emails.
- **Collaboration & Test Coverage:** Real-time multi-user task sharing via invite codes, 100% type safety (`tsc`), `bun test` integration suites (10/10), and Playwright E2E browser automation in GitHub Actions CI.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://todo-list-zalde.vercel.app/) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/todo-list-zalde)

</td>
<td width="50%" valign="top">

#### 💳 02. [POS Web Zalde](https://pos-web-zalde.vercel.app)
**React 18 · TypeScript · Tailwind CSS · Prisma ORM · Elysia API · PostgreSQL**

A production-ready Point of Sale (POS) and multi-warehouse inventory management system tailored for retail operations.
- **Multi-Warehouse Dual-Stock Engine:** Explicit relational tracking between front-store display inventory and warehouse backup reserves, with real-time transaction recalculations and low-stock alerts (≤ 5 units).
- **Automated Supplier Purchase Orders (PO):** Smart replenishment module generating structured purchase orders dispatched directly to vendor WhatsApp in one click.
- **Client-Side WebP Compression:** Custom browser-side image processing utility (`imageCompressor.ts`) resizing and converting product images to lightweight WebP (15–30 KB) prior to network upload.
- **In-Store Team Communication:** Event-driven floating chat drawer enabling instant cashier-to-warehouse restocking requests with quick-action templates.
- **Cloud Data Pipeline & Testing:** Bi-directional database synchronization scripts (`syncFromCloud`/`syncToCloud`) bridging local PostgreSQL and Neon Cloud, validated with 7 Bun integration test suites.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://pos-web-zalde.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/pos-web-zalde)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏢 03. [CRM Web Platform](https://crm-web-zalde.vercel.app)
**Next.js 16 · React 19 · TypeScript · Zod · Prisma ORM · Neon PostgreSQL**

An enterprise-grade CRM web platform for sales opportunity pipeline automation, B2B account directories, and customer service ticketing.
- **Defensive API Validation:** Enforces strict runtime payload validation and form sanitization via **Zod** across all API route handlers, preventing SQL injection alongside Prisma ORM parameterization.
- **Sales Opportunity Pipeline:** Multi-stage deal tracking (*Pending, Won, In Progress, Lost*) with expected close revenue aggregation and timestamped team activity feeds.
- **Service Desk & SLA Countdown:** Comprehensive ticketing engine with severity levels (*Critical, Major, Minor*), live countdown timers for remaining SLA resolution windows, and CSAT customer review feeds (96.5% satisfaction).
- **Integrated Knowledge Base:** Internal solutions repository with Markdown rendering, category tagging, and view-count analytics to deflect recurring inquiries.
- **Zero-Debt Type-Safe Architecture:** Next.js App Router with Server Components, scoped Vanilla CSS Modules, and 100% clean TypeScript verification (`tsc --noEmit`).

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://crm-web-zalde.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/CRM-web)

</td>
<td width="50%" valign="top">

#### 🏘️ 04. [System RT (Community & Dues)](https://system-rt-zalde.vercel.app/)
**React 19 · Vite 8 · React Router v7 · Tailwind v4 · Recharts 3 · Oxlint**

A Single Page Application (SPA) for neighborhood residency administration and financial ledger transparency.
- **Residency Lifecycle & Audit Trail:** Relational record management for 20 residential housing units (Blocks A & B), KTP identity verification, occupancy state (Permanent vs. Tenant), and automated move-in/move-out historical logs (`RiwayatPenghuni`).
- **Conditional Billing Rules:** Automated fee collection for Security (Rp 100k) and Sanitation (Rp 15k) with conditional waiver logic for vacant rental units, supporting monthly or 1-year lump-sum payments.
- **Financial Ledger & Cashflow Analytics:** Visual cashflow analytics via Recharts tracking routine overhead (security salaries, utilities) and maintenance costs, with printable financial report exports.
- **Modern Tooling & Code Health:** Powered by Vite 8, React 19, React Router v7, and Tailwind CSS v4, strictly audited by the high-performance Rust linter **Oxlint** (0 errors, 92 rules) in CI/CD.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://system-rt-zalde.vercel.app/) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/system-rt)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧠 05. [Personality & Career Assessment](https://personality-test-omega-three.vercel.app)
**Next.js 16 · React 19 · NextAuth v5 · React Hook Form · Zod · Dynamic SVG**

A multi-dimensional psychometric assessment platform for evaluating cognitive potential, career interests, and learning styles.
- **Three Standardized Psychometric Frameworks:** Implements Howard Gardner’s Multiple Intelligences (80 questions, 8 domains), John Holland’s RIASEC Career Codes (42 questions, 6 archetypes), and VAK Learning Modalities (27 questions).
- **Dynamic Polar SVG Radar Charts:** Math-driven custom SVG radar rendering (triangles for VAK, hexagons for RIASEC, octagons for Gardner) without heavy third-party chart dependencies.
- **High-Volume Form State Management:** Powered by `react-hook-form` to eliminate lag and redundant re-renders across 80+ questions, validated with strict `Zod` schemas.
- **Cloud Integration & NextAuth v5:** Automated test result persistence to Google Sheets API webhooks, backed by modern NextAuth v5 (Auth.js) session authentication.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://personality-test-omega-three.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/personality-test)

</td>
<td width="50%" valign="top">

#### 🏫 06. [School Financial System (SPP)](https://github.com/alberic13/keuangan-app)
**Laravel 11 · Livewire 4 · MariaDB · Spatie Permission · DomPDF · Excel**

An institutional financial administration and tuition management system built for educational institutions.
- **5-Tier RBAC Security:** Role-Based Access Control implemented via `spatie/laravel-permission` across five roles: `admin_keuangan`, `bendahara`, `kepala_madrasah`, `waka`, and `admin_tu`.
- **Institutional Tuition & Arrears Engine:** Handles standard tuition (SPP), Full-Day activity fees, and Boarding meal plans, tracking historical arrears as persistent open invoices across academic years.
- **Accounting & Official Document Generation:** Automated General Cash Book (*Buku Kas Umum* - BKU), printable payment receipts via `laravel-dompdf`, and bulk Excel data exports via `laravel-excel`.
- **Database Migration & Cloud Backup:** Custom console command (`php artisan legacy:import-transaksi`) migrating legacy schema transactions without downtime, paired with Google Drive cloud backup storage.
- **Reactive Livewire UI:** Instantaneous interface interactions without full page reloads via Livewire 4, supported by database queue workers.

[![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/keuangan-app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ✨ 07. [LKP Exotic](https://belajar-nextjs-taupe.vercel.app)
**Next.js 16 · React 19 · Three.js · GSAP · Drizzle ORM · MySQL2 · Zod**

A commercial web portal and LMS foundation for a vocational beauty academy.
- **Interactive 3D WebGL (Three.js):** Custom Three.js 3D viewport (`ThreeDSlider.js`) and cursor interactions optimized for consistent 60 FPS performance and zero Cumulative Layout Shift (CLS: 0).
- **Custom Stateless JWT Auth:** Handcrafted token-based authentication using `jose` and `bcryptjs` running securely through Next.js Server Actions and HTTP-only cookies.
- **Type-Safe ORM Layer:** Structured course enrollment database layer built on `Drizzle ORM` + `mysql2`, with defensive `Zod` validation.
- **Choreographed Micro-Interactions:** Smooth scroll-linked animations powered by `@gsap/react` and Framer Motion for a polished commercial brand feel.

[![Live Demo](https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white)](https://belajar-nextjs-taupe.vercel.app) [![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/LKP-EXOTIC)

</td>
<td width="50%" valign="top">

#### ⚡ 08. [WhatsApp Auto-Reply Bot](https://github.com/alberic13/whatsap-auto-reply-Golang)
**Golang 1.26 · Gin · Whatsmeow · Telegram API · Gemini AI SDK · GORM**

A high-concurrency automated messaging backend service with multi-channel routing and AI integration.
- **High Concurrency & Low Footprint:** Leverages Golang Goroutines and Channels to handle concurrent inbound message streams with ultra-low latency and minimal memory overhead.
- **Native WebSocket Protocol:** Direct binary WebSocket communication via `whatsmeow` with terminal QR pairing, completely bypassing resource-heavy headless browsers.
- **Unified Multi-Channel Router:** Centralized controller architecture routing incoming events from both WhatsApp socket streams and Telegram Bot API polling.
- **LLM Integration & Catalog Orders:** Connected to the official `google-generative-ai-go` SDK for conversational query answering, database keyword routing for product orders (`controllers/pesanan.go`), and Google Drive file archiving.
- **IoT Telemetry & Alerting:** Dedicated temperature sensor controller (`controllers/suhu.go`) capable of receiving environmental triggers and dispatching real-time threshold alerts to chat.

[![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/alberic13/whatsap-auto-reply-Golang)

</td>
</tr>
</table>

---

### 🎯 Engineering Values & Work Ethic

- **Pragmatic & Solution-Oriented:** Choosing the right tool for the job based on real engineering constraints (e.g., Go for concurrent socket listeners, Next.js/React 19 for SEO & interactive UI, Laravel for institutional RBAC financial systems).
- **Code Discipline & Type Safety:** Enforcing defensive validation boundaries (Zod), static typing (TypeScript/Go), and automated testing (Playwright, Bun Test, Oxlint) to prevent regressions in production.
- **Collaborative & Production-Ready:** Experienced with clean Git workflows (branching, structured semantic commits, pull requests), modular architecture separation, and comprehensive technical documentation.

---

### 🛠️ Tech Stack & Tools

<div align="center">

| Category | Technologies |
| :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Backend** | ![Golang](https://img.shields.io/badge/Golang-00ADD8?style=flat-square&logo=go&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) ![Elysia](https://img.shields.io/badge/ElysiaJS-8B5CF6?style=flat-square&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Database & Cache** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logoColor=black) |
| **Testing & Tools** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

</div>

---

### 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=alberic13&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alberic13&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=alberic13&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

### 📬 Get In Touch

I am open to software engineering opportunities as a **Frontend Developer**, **Backend Engineer**, or **Fullstack Software Engineer** (Full-time / Remote / Hybrid).

<div align="center">

<a href="https://www.linkedin.com/in/muchammad-zalde-zahwa-putra-20a83b2a7/">
  <img src="https://img.shields.io/badge/LinkedIn-Muchammad_Zalde-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="38" alt="LinkedIn" />
</a>
&nbsp;&nbsp;
<a href="mailto:zaldealberic@gmail.com?subject=Job%20Opportunity%20-%20Software%20Engineer">
  <img src="https://img.shields.io/badge/Email-zaldealberic@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="38" alt="Email" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/alberic13">
  <img src="https://img.shields.io/badge/GitHub-alberic13-181717?style=for-the-badge&logo=github&logoColor=white" height="38" alt="GitHub" />
</a>

</div>
