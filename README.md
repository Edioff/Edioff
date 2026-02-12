<div align="center">

# Johan Cruz

### Data Engineer & Web Scraping Specialist

*Turning protected websites into structured data*

**Bogota, Colombia** | Building data pipelines that extract, transform, and deliver at scale

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johan-andres-cruz-forero/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Edioff)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:datahive.scraping@gmail.com)

</div>

---

## What I Build

I design and operate **large-scale web scraping systems** and **data pipelines** that run in production, not just demos. My work at Red Atlas processes **50M+ property records** across 4 countries (Spain, Argentina, Colombia, Puerto Rico) from **68+ real estate portals** — running 24/7 with automated monitoring, error recovery, and incremental updates.

When a website fights back with anti-bot protections, I fight smarter. I've deeply analyzed **Akamai Bot Manager v2** (reverse-engineering 512KB of obfuscated JavaScript), bypassed **Cloudflare** challenges, and cracked **Alibaba's MTOP SDK** cookie signing — all without headless browsers in the critical path.

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![curl_cffi](https://img.shields.io/badge/curl__cffi-00599C?style=flat-square&logo=curl&logoColor=white)

</div>

**Core:** Python, PostgreSQL, Docker, Linux, Git
**Scraping:** Playwright, Selenium, undetected-chromedriver, curl_cffi, BeautifulSoup, lxml
**Anti-Bot:** TLS fingerprint impersonation, cookie signing, sensor data generation, JavaScript deobfuscation
**Data:** PySpark, Pandas, FastAPI, SQLite, CSV/JSON pipelines
**Infrastructure:** Docker Compose, proxy rotation (NetNut, residential), headless browsers at scale

## Currently Exploring

Building at the intersection of **web scraping and AI**: using LLM APIs (Claude, OpenAI) for intelligent HTML analysis and adaptive extraction, experimenting with AI agent orchestration for self-healing crawlers, and integrating language models into data pipelines for automated cleaning and classification.

## Featured Projects

### [O'Reilly Auto Parts Scraper](https://github.com/Edioff/oreillyauto-scraper) — Akamai Bot Manager v2 Research
Deep reverse engineering of a site protected by **Akamai Bot Manager v2**. Deobfuscated 512KB of JavaScript to map sensor data generation, cookie signing, and device fingerprinting. Built a scraper using `curl_cffi` for TLS impersonation with partial bypass of Akamai's detection layers.

### [Akamai Bot Manager Analysis](https://github.com/Edioff/akamai-analysis) — Enterprise Anti-Bot Deep Dive
Technical analysis of how Akamai Bot Manager v2 works under the hood: 100+ browser signals collected, sensor data encoding, cookie validation lifecycle, and server-side checks. 11-page technical report documenting the full reverse engineering methodology and findings.

### [Goofish Scraper](https://github.com/Edioff/goofish-scrape) — Alibaba Anti-Bot Bypass
Scraped **18,000+ products** from Alibaba's Goofish platform by cracking the MTOP SDK cookie signing mechanism. Hybrid approach: Playwright for initial auth, then direct API calls via `curl_cffi` with Chrome TLS fingerprint. 5-10 products/second with multiprocessing.

### [TikTok Scraper](https://github.com/Edioff/tiktokscraper) — High-Performance Comment Extraction
Extracts TikTok comments at **667 comments/minute** using a hybrid API + scraping approach. Built for volume with rate limiting, session management, and structured JSON/CSV output.

### [Vrbo Scraper](https://github.com/Edioff/vrbo-scraper) — Vacation Rental Data Extraction
Full-featured vacation rental scraper for Vrbo: listing discovery, detail extraction, pricing, amenities, host info, and geolocation. Handles pagination, anti-bot detection, and cookie management with undetected-chromedriver.

### [Booking.com Scraper](https://github.com/Edioff/booking-scraper) — Async Multi-City Hotel Extraction
Async Booking.com scraper with **3 parallel workers** extracting hotel listings, room-level pricing, amenities, reviews, and geolocation. 2,400+ lines of Playwright async code handling complex modals, overlays, and dynamic loading.

### [CLI Web Scraper](https://github.com/Edioff/CLI-Web-Scraper) — Real Estate Puerto Rico
Command-line tool for extracting property listings from Puerto Rican real estate portals. Built with Playwright and BeautifulSoup for reliable data extraction with structured JSON output.

## Scale & Production Experience

| Metric | Value |
|--------|-------|
| Records in production | **50M+** property records |
| Countries covered | **4** (Spain, Argentina, Colombia, Puerto Rico) |
| Portals scraped | **68+** Spanish real estate sites |
| Anti-bot systems bypassed | Cloudflare, Alibaba MTOP SDK |
| Anti-bot systems deeply analyzed | Akamai Bot Manager v2 (512KB JS reverse-engineered) |
| Concurrent scraping speed | Up to **667 items/minute** |
| Infrastructure | Docker, PostgreSQL, automated monitoring |

## Services

I'm available for freelance projects in:

- **Protected Site Extraction** — Targets behind Cloudflare, DataDome, and custom anti-bot systems
- **Data Pipeline as a Service** — End-to-end: extraction, cleaning, and structured delivery
- **Real Estate Data (LATAM & Europe)** — 50M+ records across Spain, Argentina, Colombia, Puerto Rico
- **AI-Enhanced Scraping** — LLM-powered extraction that adapts when sites change
- **API Reverse Engineering** — Finding and consuming undocumented APIs for browserless extraction

**Interested in working together?** Reach out via [email](mailto:datahive.scraping@gmail.com) or [LinkedIn](https://www.linkedin.com/in/johan-andres-cruz-forero/).

---

<div align="center">

![Edioff's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Edioff&show_icons=true&theme=github_dark&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Edioff&layout=compact&theme=github_dark&hide_border=true)

</div>
