# 👋 Hello.

> [!NOTE]
> **A note on the journey:**
> It's normal to feel like a beginner—with occasional, impromptu flashes of self-actualization. You look back after 10 or 20 years, and you still feel like a beginner.
>
> From the master's perspective, potential is everywhere. Those looking at the master see only wisdom and experience.
>
> The master smiles and kindly acknowledges: *The road is vast beyond comprehension. I am merely a step ahead, yet we are closer than you realize.*

---

## 🏗️ Featured Architecture

### 🇬🇧 Serverless DevSecOps Job Radar
A stateful, fully automated CI/CD data pipeline that aggregates and serves live cybersecurity roles in London. Built entirely on serverless and edge compute technologies.

> [!IMPORTANT]  
> **🔗 [View the Live Dashboard Here](https://my-job-board.pages.dev)**

#### 🛠️ Core Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

#### ⚙️ The Data Pipeline
How the system processes data from end-to-end:

1. **📥 Scrape:** A daily GitHub Action runs a Python script to pull jobs from the Adzuna & Reed APIs.
2. **🧹 Filter:** Queries a Cloudflare D1 (SQLite) database to drop duplicates and save only fresh leads.
3. **🔔 Alert:** Pushes new job alerts instantly to a private Discord webhook.
4. **🚀 Serve:** A Cloudflare Worker API securely exposes the database to a fast, edge-hosted React (Vite) frontend.

---
