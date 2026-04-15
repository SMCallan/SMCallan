# 👋 Callan Smith MacDonald
### Full-Stack Software Engineer & Security Researcher | MSc Computer Science

Specialising in building secure, scalable applications across the entire stack—from embedded systems and backend architecture to user-centric frontends. I bridge the gap between complex infrastructure (Python, Node.js, Docker, CI/CD) and systemic risk management, applying macro-level threat modelling, OSINT, and vulnerability research to highly regulated environments.

🔗 **[LinkedIn](https://www.linkedin.com/in/callan-smith-macdonald)** | 🎯 **[TryHackMe / pwn.college](https://pwn.college/hacker/)** | 💻 **[LeetCode](https://leetcode.com/u/JJkB1pNE/)**

---

## 🏗️ Featured Architecture

### 🇬🇧 DevSecOps Market Intelligence Engine
A high-performance, edge-computing application that transforms raw job board data into actionable market intel. This isn't just a list of jobs; it's a real-time statistical analysis of the London cybersecurity landscape.

> [!IMPORTANT]  
> **🔗 [Explore the Live Dashboard](https://my-job-board.pages.dev)**
> 
> *Note: The repository for this engine is currently private to protect API integrations and data models. I am more than happy to provide a technical walkthrough of the source code and CI/CD pipelines upon request during interviews.*

#### 🛠️ Core Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

#### ⚙️ The Data Engine & Deliverables
How the system delivers high-signal intelligence:

* **📥 Ingest:** Daily GitHub Actions trigger a Python pipeline to scrape 500+ roles from Adzuna & Reed APIs.
* **🧹 Process:** Regex-based cleaning handles complex data formats (like trailing decimals) and normalizes records for a Cloudflare D1 (SQLite) backend.
* **📊 Analyze:** A custom Cloudflare Worker API performs on-the-fly financial modeling—separating **Contract Day Rates** from **Permanent Salaries** to provide accurate market averages across the entire 14-day dataset.
* **🎨 Experience:** A Vite + React frontend designed with a **"Trust & Clarity"** palette, specifically optimized for neurodivergent accessibility (ADHD, ASD, and Dyslexia-friendly chunking).
* **⚡ Edge-Powered:** Real-time search and smart pagination handled at the edge for sub-100ms response times.

---

> [!NOTE]
> **A personal note on the journey:**
> It's normal to feel like a beginner—with occasional, impromptu flashes of self-actualization. You look back after 10 or 20 years, and you still feel like a beginner.
>
> From the master's perspective, potential is everywhere. Those looking at the master see only wisdom and experience.
>
> The master smiles and kindly acknowledges: *The road is vast beyond comprehension. I am merely a step ahead, yet we are closer than you realize.*
