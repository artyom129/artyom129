<div align="center">

# Artyom Koncha

### Python backend and automation developer

Webhooks, queues, integrations and data pipelines that keep working when something upstream breaks, and say so clearly when they can't.

[Get an estimate](mailto:artyom129.x@gmail.com?subject=Project%20estimate) · [Telegram](https://t.me/arttyism) · [LinkedIn](https://www.linkedin.com/in/artyom-python-automation/) · [Portfolio site](https://artyom129.github.io/)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

I'm Artyom, based in Kazakhstan. I take on project-based Python backend and automation work. Below is what I build, with screenshots and numbers from projects you can open and run.

## What I build

| If you have this problem | I deliver | Open an example |
|---|---|---|
| Webhooks and integrations fail without anyone noticing | Intake with signature checks, retries, replay and a dead-letter queue. Nothing is lost and every failure is visible | [Backplane](https://github.com/artyom129/backplane), [api-webhook-reliability-monitor](https://github.com/artyom129/api-webhook-reliability-monitor) |
| Background jobs get stuck or run twice | A job system with retries, idempotency keys, schedules and recovery after a crash | [QueueForge](https://github.com/artyom129/queueforge), [OpsWeave](https://github.com/artyom129/opsweave) |
| Your SaaS needs accounts, plans and limits | A multi-tenant backend with login, roles, API keys, quotas, billing webhooks and an audit log | [TenantForge](https://github.com/artyom129/tenantforge), [CohortSwitch](https://github.com/artyom129/CohortSwitch) |
| A data migration or import has to be right | A check that compares both sides record by record and returns a verdict, a report and a patch plan | [SyncProof](https://github.com/artyom129/syncproof), [DataDrop-Guardian](https://github.com/artyom129/DataDrop-Guardian) |
| Your team does the same work by hand in spreadsheets, PDFs and a CRM | Automation that cleans, validates and routes the data, with a dashboard your team can use | [Invoice dashboard](https://github.com/artyom129/invoice-document-automation-dashboard), [LeadSignal HQ](https://github.com/artyom129/leadsignal-hq), [RelayDesk](https://github.com/artyom129/RelayDesk-AI-Business-Automation-AI-Integration-Platform) |
| You run a booking or scheduling product | A backend with conflict detection and a mobile client, deployed and running | [SlotBridge](https://github.com/artyom129/SlotBridge) |

## Work you can open

<table>
  <tr>
    <td width="33%" valign="top"><a href="https://github.com/artyom129/syncproof"><img src="https://raw.githubusercontent.com/artyom129/syncproof/main/docs/screenshots/run.png" alt="SyncProof run page"></a><br><sub><a href="https://github.com/artyom129/syncproof">SyncProof</a> compares a migration record by record. On a 1,200-customer test it found 65 changed records, 40 renamed IDs, 25 missing, 3 repeated and 12 extra.</sub></td>
    <td width="33%" valign="top"><a href="https://github.com/artyom129/opsweave"><img src="https://raw.githubusercontent.com/artyom129/opsweave/main/docs/screenshots/workflow.png" alt="OpsWeave workflow graph"></a><br><sub><a href="https://github.com/artyom129/opsweave">OpsWeave</a> draws the path the last run took through the workflow. Skipped branches are dashed, failed payloads wait for a one-time replay.</sub></td>
    <td width="33%" valign="top"><a href="https://github.com/artyom129/invoice-document-automation-dashboard"><img src="https://raw.githubusercontent.com/artyom129/invoice-document-automation-dashboard/main/docs/screenshots/review.jpg" alt="Invoice review queue"></a><br><sub><a href="https://github.com/artyom129/invoice-document-automation-dashboard">Invoice dashboard</a> reads invoice data from PDFs and queues the uncertain ones for review. 110 tests.</sub></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><a href="https://github.com/artyom129/leadsignal-hq"><img src="https://raw.githubusercontent.com/artyom129/leadsignal-hq/main/docs/screenshots/board.png" alt="LeadSignal HQ lead board"></a><br><sub><a href="https://github.com/artyom129/leadsignal-hq">LeadSignal HQ</a> scores leads, routes them by keywords and tracks SLA deadlines. 63 tests.</sub></td>
    <td width="33%" valign="top"><a href="https://github.com/artyom129/logpulse-sentinel"><img src="https://raw.githubusercontent.com/artyom129/logpulse-sentinel/main/docs/screenshots/incidents.png" alt="LogPulse incident list"></a><br><sub><a href="https://github.com/artyom129/logpulse-sentinel">LogPulse Sentinel</a> groups noisy log lines into incidents. On the demo logs, 68 events become 6 incidents.</sub></td>
    <td width="33%" valign="top"><a href="https://github.com/artyom129/fullstack-poker"><img src="https://raw.githubusercontent.com/artyom129/fullstack-poker/main/docs/screenshots/table.png" alt="Poker table"></a><br><sub><a href="https://github.com/artyom129/fullstack-poker">Fullstack Poker</a> is a Hold'em table with side pots and a showdown breakdown. 34 backend, 29 frontend and 3 end-to-end tests.</sub></td>
  </tr>
</table>

Test counts for the other main projects: TenantForge 128, SlotBridge 121, QueueForge 40, CohortSwitch 56, SyncProof 27. Each of them runs in CI on every push.

## How a project goes

1. You describe the task. A few lines are enough.
2. I reply with a price and a timeline for that task.
3. If there is existing code, I read it first and write tests around the parts I will touch.
4. I build the work with tests and CI, and show you a version you can run.
5. You get the code in your repository, a README, and notes on how the system behaves when things fail. A Docker setup comes with it where the project needs one.

Security checks are part of the build: outbound request limits, signed callbacks, encrypted secrets, hashed API keys and CSV exports that are safe to open in Excel.

The READMEs of the main projects are in English, Russian and Kazakh.

---

<div align="center">

### Have a task like one of these?

Describe it and I will send a price and a timeline.

[artyom129.x@gmail.com](mailto:artyom129.x@gmail.com?subject=Project%20estimate) · [Telegram @arttyism](https://t.me/arttyism)

</div>
