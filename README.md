# Cesar Matias

### Python Backend Engineering · Web Data · Applied AI

I build backend systems that turn fragmented web data into useful products. My focus is Python, asynchronous services, web scraping, and the reliability of the systems around them: message contracts, retries, tests, and observability.

Based in São Paulo, Brazil. Software Engineer at **CarBigData**, with software engineering experience since 2021.

[LinkedIn](https://www.linkedin.com/in/cesarhmmatias/) · [Public repositories](https://github.com/cesarhmatias?tab=repositories)

## What I work on

- **Backend & distributed systems:** Python, asyncio, FastAPI, Django, RabbitMQ, PostgreSQL, Redis, Docker, AWS, and CI/CD.
- **Web data:** Scrapy, Playwright, Selenium, curl_cffi, API discovery, browser and HTTP fingerprint analysis, ETL, and data normalization.
- **Reliability:** pytest, integration tests with real infrastructure, message schemas, retry policies, Prometheus metrics, and incident diagnosis.
- **AI & product engineering:** LLM workflows, agent orchestration, and multi-tenant applications with Python and TypeScript/Next.js.

At CarBigData, my work includes strengthening a distributed data acquisition platform through test suites, contract validation, bug fixes, and application metrics. I also directed the development of a shared spider framework to replace duplicated infrastructure and make new integrations easier to maintain.

## Selected projects

### [Bot Detection Lab](https://github.com/cesarhmatias/akamai-style-bot-lab)

A local educational environment for studying bot detection and testing automation against a server you control. A **Go edge proxy** captures TLS and HTTP/2 fingerprints, while **FastAPI and Redis** handle detection signals, scoring, and challenges. CI checks a documented client comparison matrix. An independent simulation based on public research.

### [DaikinAC-menubar](https://github.com/cesarhmatias/DaikinAC-menubar)

A native **Swift macOS app** for controlling Daikin Smart AC units from the menu bar. Supports local network control with cloud fallback, energy readings, and diagnostics. The project combines protocol reverse engineering, Cognito authentication, AWS IoT device shadows, and credentials stored in the macOS Keychain. Unofficial; independently developed.

### Sua socIA — AI social media SaaS

My own product for managing multiple brands and their social content, with AI-assisted planning, writing, artwork, and human approval. I designed the architecture and directed development through deployment using coding agents.

Built with **FastAPI, PostgreSQL/pgvector, and Next.js**, with database-enforced tenant isolation through Row-Level Security, background jobs, and budget controls for AI usage. Source code is private.

### ScrapeLens — local HTTP inspection tool · in development

A macOS developer tool for answering: “The browser can make this request; what is my scraper doing differently?” Built with **Rust, Tauri, React, and TypeScript**, it combines Chrome CDP and NetLog capture, HAR import, request comparison, sanitized exports, and a local MCP interface. Not yet published on GitHub.

### Radar Automotivo — vehicle listing monitor · in development

A **Python/FastAPI** project that turns newly identified vehicle listings into spreadsheet exports and optional alerts for vehicle resellers. Current work covers collection integration, data contracts, and local validation; it remains a local MVP.

## How I build

I use Claude Code and Codex as part of my engineering workflow. I define the architecture, interfaces, task boundaries, and acceptance criteria; agents implement scoped changes, with separate review and executable checks. My responsibility is the design, the decisions, and validating the result.

I care about explicit failure states, tests that catch contract drift, and metrics that help explain what a system is doing.

## Earlier work

Engineering graduate from **Centro Universitário FEI**, with a background spanning healthcare, industrial digitalization, and embedded systems.

Earlier studies include [ESP32/MicroPython sensors](https://github.com/cesarhmatias/esp32_temperature_sensor_micropython), [Google Play data analysis](https://github.com/cesarhmatias/The-Android-App-Market-on-Google-Play), and [Kaggle notebooks](https://github.com/cesarhmatias/titanic_spaceship_kaggle_competition_2).

For professional opportunities or collaboration, connect with me on [LinkedIn](https://www.linkedin.com/in/cesarhmmatias/).
