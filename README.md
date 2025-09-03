<div align="center">

# Anshuman Arora
### Systems-First Builder | Power Platform + Cloud + Full-Stack

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=shhumaan&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
</a>
<br/>
<p>I ship low-code and high-code systems that behave like products: governed, observable, and CI/CD-ready.  
Focused on business outcomes, not buzzwords—optimizing for reliability, security, and speed to value.</p>

</div>

---

### 🔗 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/anshuman-28507817a/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://anshumandev.cloud/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-black?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:anshuman.arora.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

### 🛠️ My Core Toolbox

<p align="center">
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/next-js.svg" alt="nextjs" width="40" height="40"/></a>
  <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/></a>
  <a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
  <a href="https://redis.io" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/></a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
  <a href="https://kubernetes.io" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/></a>
  <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/github_actions/github_actions-icon.svg" alt="githubactions" width="40" height="40"/></a>
</p>

---

## 🚀 Flagship Projects

### 1) TixGenius — Full-Stack Ticketing (Monorepo)
> Event ticketing platform designed for scale and developer velocity using a modern monorepo.

<details>
<summary><b>Why it matters & Key Features</b></summary>

**Why it matters:** Clean separation of concerns + shared packages enables fast feature delivery with consistent standards.

- **Next.js 14 + Express** across a **Turborepo** monorepo with shared types, ESLint, TS configs, and a shared UI lib
- **Quality gates**: ESLint, Prettier, Husky + lint-staged, typecheck, tests
- **CI/CD**: GitHub Actions for build/test; Dockerized services for reproducible deploys
- **DX**: One-command dev (`npm run dev`) spins up frontend and backend

**Stack:** `Next.js` `React` `TypeScript` `Tailwind` `Express` `Node` `Turborepo` `Docker` `GitHub Actions`
</details>

### 2) Cloud Portal CLI Assistant — Multi-Cloud Command Intelligence
> A companion that translates cloud console intent into secure, copy-ready CLI across AWS/Azure/GCP.

<details>
<summary><b>Why it matters & Key Features</b></summary>

**Why it matters:** Reduces toil and context-switching for cloud engineers; codifies institutional knowledge.

- **Browser Extension** reads console context → suggests precise CLI
- **Web App** knowledge base to save/share commands and runbooks
- **Backend API (Node)** with auth and structured storage (PostgreSQL)
- **AI Microservice (Python)** for command generation; optional **local-only AI** mode for privacy
- **Security stance:** minimal data retention, end-to-end encryption paths

**Stack:** `Next.js` `Node.js` `PostgreSQL` `Python (FastAPI/UVicorn)` `Docker` `(optional) Docker Compose`
</details>

### 3) AzureShield IAM — Enterprise-Grade Identity & Access
> Opinionated IAM platform with MFA, RBAC/ABAC, auditability, and Azure-ready deployment.

<details>
<summary><b>Why it matters & Key Features</b></summary>

**Why it matters:** Enforces least privilege with clear policy surfaces and auditable decision trails.

- **Auth**: JWT + refresh, **MFA/TOTP**, backup codes
- **Authorization**: **RBAC + ABAC** with hierarchical roles and dynamic policies
- **Observability**: full audit logs, health metrics, alerting hooks
- **Scale-ready**: Docker + Kubernetes; Azure Bicep/Terraform scaffolding
- **DX**: strong docs, OpenAPI, migrations via Alembic

**Stack:** `FastAPI (Python 3.11+)` `PostgreSQL` `SQLAlchemy` `Redis` `Next.js 14` `Material-UI` `K8s` `Azure` `GitHub Actions`
</details>

### 4) Ollama Chat Demo — Local LLM Chat UX (Next.js + NestJS)
> A modern chat interface for **local** LLM workflows on Ollama—privacy-first, fast, and skinnable.

<details>
<summary><b>Why it matters & Key Features</b></summary>

**Why it matters:** Teams can prototype LLM UX without shipping data off-prem.

- **Model discovery** + selection UI; **dark mode** and responsive layout
- **NestJS backend** orchestrates Ollama calls and model metadata
- **Persistence**: client-side session save/restore
- **Ops**: simple env config; split frontend/backend for clear boundaries

**Stack:** `Next.js` `Tailwind` `shadcn/ui` `NestJS` `TypeScript` `Axios` `Ollama`
</details>

### 5) Portfolio v2 — Productized Personal Site
> A next-gen portfolio showcasing projects and narrative with performance, theming, and animations.

<details>
<summary><b>Why it matters & Key Features</b></summary>

**Why it matters:** Signals polish and design empathy while staying maintainable and data-driven.

- **Next.js App Router**, **Framer Motion** animations, theme switching, Three.js particles
- **Data-driven** sections from JSON; code-split for fast loads
- **Project filters**, interactive sections, and contact form with validation

**Stack:** `Next.js` `TypeScript` `Tailwind` `Framer Motion` `Three.js` `Zod` `React Hook Form`
</details>

---

## 📈 What I Optimize For
> - **Reliability:** predictable rollouts, rollback plans, and runbooks
> - **Speed to Value:** monorepo ergonomics, shared types, one-shot dev scripts
> - **Governance:** audit trails, policy-as-data, environment strategy
> - **DX:** frictionless local dev, clear conventions, low cognitive load

---

## 🤝 How to Contribute

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/shhumaan/shhumaan/issues).

1.  **Fork** the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'feat: Add some AmazingFeature'')
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a **Pull Request**

---

*This README was enhanced with the help of an AI assistant.*
