<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="100%" height="50" style="object-fit: cover;" />

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2E86C1&center=true&vCenter=true&width=700&lines=Computer+Science+%40+UFMG;Building+Scalable+SaaS+Architectures;Full+Stack+Engineer+(Django+%2F+Angular);AI+%26+Cloud+Enthusiast" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://www.linkedin.com/in/thiago-arthur1">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:thiagodevprof@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://excaliweb.com">
      <img src="https://img.shields.io/badge/Portfolio-Excaliweb-000000?style=for-the-badge&logo=google-chrome&logoColor=white" />
    </a>
  </p>
</div>

---

## 👨‍💻 Engineering First

I am a **Software Engineer in the making** at **UFMG (Federal University of Minas Gerais)** with strong **production experience**.

Unlike many students, I have architected and maintained **real-world systems**, including **Multi-tenant SaaS platforms**, **Cloud Infrastructure (Azure / AWS)**, and **containerized deployments**. I focus on building software that is **scalable, secure, and maintainable**, always thinking in terms of architecture, not just code.

While my core strength lies in **Full Stack Engineering**, I am actively integrating **Artificial Intelligence** and **automation workflows** to create intelligent, data-driven systems.

- 🔭 **Expertise:** SaaS Architecture, REST APIs, CI/CD Pipelines
- 💼 **Experience:** Full Stack Developer working with Embedded Analytics
- 🏆 **Achievement:** 1st Place — *Unimed Innovation Challenge*

---

## 🧩 System Architecture Showcase

**Project:** *Intelligent Triage System (Unimed)*  
This architecture diagram is rendered natively by GitHub using **Mermaid.js** and represents the **real orchestration flow** of an award-winning healthcare project.
```mermaid
graph LR
    User["Patient"] -- "1. Sends Symptoms" --> WA["Evolution API<br/>(WhatsApp)"]
    WA -- "2. Webhook" --> N8N["n8n Orchestrator"]

    subgraph "Secure Cloud — VPS / Docker"
        DB["PostgreSQL"]
        AI["AI Engine<br/>(LLM Logic)"]

        N8N -- "3. Check History" --> DB
        N8N -- "4. Classify Risk" --> AI
        AI -- "5. Return Score" --> N8N
    end

    N8N -- "6. Priority Code" --> WA
    N8N -- "7. Notify Hospital" --> Dash["Hospital Dashboard<br/>(Angular)"]

    style N8N fill:#ff6600,stroke:#333,stroke-width:2px,color:#fff
    style AI fill:#2E86C1,stroke:#333,stroke-width:2px,color:#fff
    style DB fill:#333,stroke:#fff,stroke-width:2px,color:#fff
```

---

## 🛠️ Interactive Tech Stack

*Click to expand each category.*

<details open>
<summary><b>☁️ Cloud & DevOps</b></summary>
<br>
<div align="center">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</div>
<p align="center">
Experience managing VPS, Serverless Functions, CI/CD pipelines, and containerized environments.
</p>
</details>

<details>
<summary><b>💻 Backend & Architecture</b></summary>
<br>
<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
</div>
<p align="center">
Designing robust REST APIs, optimized SQL schemas, and high-performance caching layers.
</p>
</details>

<details>
<summary><b>🎨 Frontend</b></summary>
<br>
<div align="center">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
</div>
<p align="center">
Building responsive, component-based user interfaces with strong UX focus.
</p>
</details>

<details>
<summary><b>🤖 Data & AI</b></summary>
<br>
<div align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
</div>
<p align="center">
Applying engineering discipline to Machine Learning and intelligent workflow orchestration.
</p>
</details>

---

## 🚀 Highlighted Projects

<table width="100%">
<tr>
<td width="50%">

### 🏥 Intelligent Triage System

*Winner — Unimed Innovation Challenge*

AI-powered hospital triage system that automates patient prioritization via WhatsApp.

**Tech Stack**

* n8n (Workflow Orchestration)
* LLM-based Risk Classification
* Evolution API (WhatsApp)
* Angular Dashboard
* Docker + Redis

</td>

<td width="50%">

### 📊 SaaS Analytics Platform

*Professional Project — PRS Tecnologia*

Multi-tenant SaaS platform for embedded analytics and corporate reporting.

**Tech Stack**

* Django REST Framework
* Microsoft Azure (Serverless)
* PostgreSQL (Multi-tenant)
* Automated CI/CD Pipelines

</td>
</tr>
</table>

---

## 📈 Engineering Metrics

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Guinhoal&theme=dracula" />
</div>

<br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Guinhoal&show_icons=true&theme=dracula&hide_border=true&count_private=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Guinhoal&layout=compact&langs_count=6&theme=dracula&hide_border=true" height="160" />
</div>

<br>

<picture align="center">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Guinhoal/Guinhoal/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Guinhoal/Guinhoal/output/github-contribution-grid-snake.svg">
  <img align="center" width="100%" src="https://raw.githubusercontent.com/Guinhoal/Guinhoal/output/github-contribution-grid-snake.svg">
</picture>
