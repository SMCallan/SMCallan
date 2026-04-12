It's normal to feel like a noob - with occasional and impromptu flashes of self-actualisation. Then you look back and you've been at it for 10 years, 20 years, and you still feel like a noob, - with occasional and impromptu flashes of self-actualisation.
---
From the master's perspective, potential is everywhere
---
Those that see the master see wisdom and experience
---
The master smiles, kindly acknowledges, the road is vast beyond comprehension, and I am merely a step ahead, yet we are closer than you realise.
---

## 🇬🇧 Serverless DevSecOps Job Radar

A stateful, fully automated CI/CD data pipeline that aggregates and serves live cybersecurity roles in London. 

**🔗 [Live Dashboard](https://my-job-board.pages.dev)**

**🛠️ Tech Stack:** Python, GitHub Actions, Cloudflare D1 (SQLite), Cloudflare Workers (API), React (Vite).

**⚙️ The Pipeline:**
1. **Scrape:** A daily GitHub Action runs a Python script to pull jobs from Adzuna & Reed APIs.
2. **Filter:** Checks a Cloudflare D1 database to drop duplicates and only save fresh leads.
3. **Alert:** Pushes new jobs instantly to a private Discord webhook.
4. **Serve:** A Cloudflare Worker API securely exposes the database to the React frontend.
