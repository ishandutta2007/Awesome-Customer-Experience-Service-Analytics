# Awesome-Customer-Experience-Service-Analytics

## Top Customer Experience & Service Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Support Ticket Analytics, CSAT Measurement & Customer Journey Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Experience & Service Analytics**. These tools help support and CX teams measure what matters—ticket resolution times, SLA compliance, CSAT/NPS trends, agent performance, and the behavioral signals that predict churn—turning raw service interactions into actionable intelligence.

**Examples** include Zendesk Explore, Freshworks Analytics, Salesforce CRM Analytics, ServiceNow Performance Analytics, and open-source alternatives like CustomerCore, erxes, and InsightPulse (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted CX analytics, open-source support intelligence, and community-driven CSAT measurement—ideal for organizations seeking data sovereignty and predictable costs over per-seat or per-ticket SaaS pricing. The open-source CX analytics space is fragmented but functional: erxes offers a complete experience management stack, CustomerCore provides real-time AI triage, and lightweight dashboards fill specific gaps.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global customer experience (CX) and service analytics market is estimated at approximately $14 billion to $20 billion, projected to surge beyond $70 billion by 2032 at a CAGR of 15%–18%. The sector is moderately fragmented with ongoing consolidation: mega-cloud and enterprise CRM titans (Salesforce, Microsoft, ServiceNow, Google Cloud) command substantial market share through native BI and workflow suites, while specialized CX platforms and point-solution AI vendors compete intensely in customer journey intelligence and voice-of-customer analytics.

## SaaS/Hosted Platforms

| Product | Company Size (Market Cap / Valuation / ARR) | Starting Price | Free Tier / Free Trial Limits | Description |
|---------|---------------------------------------------|----------------|-------------------------------|-------------|
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | ~$3.1T Market Cap (Microsoft) / $245B+ ARR | $14 / user / month (Power BI Pro) | Free forever: Power BI Desktop (local report authoring only); 60-day free trial for Power BI Pro cloud features | Microsoft's BI platform for building CX dashboards from service data. Integrates with Dynamics 365, Excel, and Azure. |
| **[Looker (Google Cloud)](https://looker.com/)** | ~$2.1T Market Cap (Alphabet) / $45B+ Cloud ARR | $5,000 / month ($60,000 / year base Standard tier) | Free forever for Looker Studio (basic dashboarding); core Looker BI requires sales-provisioned evaluation/PoC (no self-serve free trial) | Enterprise BI platform with semantic modeling (LookML) and governed CX metrics across Google Cloud data warehouses. |
| **[Salesforce CRM Analytics](https://www.salesforce.com/)** | ~$180B Market Cap / $41.5B ARR | $140 / user / month (Growth tier, annual billing) | 30-day free trial for Salesforce CRM / Analytics trial orgs; no free forever tier | Analytics platform within Salesforce ecosystem. Analyzes service cases, CSAT surveys, and customer interaction data alongside CRM records. |
| **[Tableau](https://www.tableau.com/)** | ~$180B Market Cap (Salesforce parent; $15.7B acquisition) | $15 / user / month (Viewer) / $75 / user / month (Creator, min 1 required) | Free forever: Tableau Public (all workbooks must be publicly shared); 14-day full platform free trial for Tableau Cloud | Visual analytics platform commonly used for CX dashboards. Connects to Zendesk, Salesforce, and service databases. |
| **[ServiceNow Performance Analytics](https://www.servicenow.com/)** | ~$104B Market Cap / $15.4B ARR | ~$100 / fulfiller / month (bundled starting in ITSM/CSM Professional tiers) | Free forever: Personal Developer Instance (PDI sandbox for developer testing only); no commercial production free trial | Enterprise analytics for ITSM and customer service workflows. Tracks KPIs, SLA attainment, and service performance trends. |
| **[Zendesk Explore](https://www.zendesk.com/)** | ~$10.2B Private Valuation / ~$2B ARR | $19 / agent / month (Support Team) / $55 / agent / month (Suite Team) | 14-day free trial (access to Zendesk Suite Professional features, extendable once by 14 days upon request); no free forever tier | Native analytics and reporting for Zendesk Support. Prebuilt dashboards for ticket volume, agent performance, CSAT, and SLA compliance. |
| **[Freshworks Analytics](https://www.freshworks.com/)** | ~$3.3B Market Cap / ~$1B ARR | $19 / agent / month (Growth plan, annual billing) | Free forever: Freshdesk Free Plan for up to 2 agents (basic ticketing & knowledge base, limited analytics); 14-day trial for paid tiers | Analytics module within Freshdesk and Freshservice. Reports on ticket trends, agent efficiency, SLA metrics, and customer satisfaction. |
| **[Sisense](https://www.sisense.com/)** | ~$1B+ Private Valuation / ~$140M ARR | ~$25,000 / year (Self-Serve / Essential starting tier) | 7-day free trial with full platform access (no credit card required); no free forever tier | Embedded analytics platform for product and CX teams wanting white-labeled, in-app customer experience dashboards. |
| **[Domo](https://www.domo.com/)** | ~$150M Market Cap / ~$318M ARR | ~$30,000 / year (pre-purchased consumption credit model) | 30-day free trial with unlimited user seats and full platform data connectors; no free forever tier | Cloud BI with drag-and-drop dashboard builder and pre-built CX and service operations templates. |
| **[Klipfolio](https://www.klipfolio.com/)** | ~$35M Private Valuation / ~$15M ARR | $120 / month (Base plan, annual billing) | 14-day free trial of Klips (full feature access, up to plan limits); PowerMetrics has a limited free forever tier (2 metrics) | Dashboard builder focused on real-time business monitoring with pre-built CX integrations and unlimited dashboard viewers. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[erxes](https://github.com/erxes/erxes)** | [![Stars](https://img.shields.io/github/stars/erxes/erxes?style=social&color=white)](https://github.com/erxes/erxes/stargazers) | **The most complete open-source experience management platform and direct alternative to HubSpot + Qualtrics.** ~3,527 GitHub stars. Source-available (fair-code). Self-hosted XOS (Experience Operating System) with plugins for Team Inbox, Messenger, Sales Management, Lead Generation, Engage, Contact Management, Knowledgebase, and Task Management. Designed for complete data control with no third-party monitoring. Composable architecture lets you build the exact CX stack you need [citation:5][citation:13]. |
| **[CustomerCore](https://github.com/saibalajinamburi/CustomerCore)** | [![Stars](https://img.shields.io/github/stars/saibalajinamburi/CustomerCore?style=social&color=white)](https://github.com/saibalajinamburi/CustomerCore/stargazers) | **Real-time AI-powered customer intelligence with multi-agent triage.** Enterprise-grade platform built on Redpanda (Kafka), Apache Iceberg, dbt, and LangGraph. Automates ticket classification, priority assignment, churn risk calculation, and SLA breach prediction. Six specialized sub-agents (Classify, Memory, RAG, Churn, Incident, HITL) produce a validated 14-field triage output in **under 2 seconds**. Includes full MLOps with MLflow and human-in-the-loop review queues [citation:2][citation:10]. |
| **[InsightPulse](https://github.com/iamjeshurun/InsightPulse)** | [![Stars](https://img.shields.io/github/stars/iamjeshurun/InsightPulse?style=social&color=white)](https://github.com/iamjeshurun/InsightPulse/stargazers) | **Voice-of-customer intelligence platform for feedback analysis.** Takes raw reviews, surveys, support tickets, and complaint narratives and turns them into structured signal. Analyzes sentiment, aspect (billing, access, fraud, fees), urgency, and confidence. FastAPI backend with React dashboard, drift monitoring, and human correction workflows. Sentiment model measured at 0.583 Macro-F1 on held-out test set [citation:6]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Open Customer Insights](https://github.com/Nutlope/open-customer-insights)** | [![Stars](https://img.shields.io/github/stars/Nutlope/open-customer-insights?style=social&color=white)](https://github.com/Nutlope/open-customer-insights/stargazers) | Open-source customer insights workspace for calls, support tickets, and Slack. Grounded chat across transcripts and tickets, semantic search, company timelines, competitor tracking, and an authenticated MCP server for coding agents. Integrates Gong, Pylon, and Slack optionally [citation:7]. |
| **[Smart Support Analytics Dashboard](https://github.com/aroojjaved93/Smart-support-analytics-dashboard)** | [![Stars](https://img.shields.io/github/stars/aroojjaved93/Smart-support-analytics-dashboard?style=social&color=white)](https://github.com/aroojjaved93/Smart-support-analytics-dashboard/stargazers) | Lightweight Python dashboard for JIRA-based support workflows. Visualizes SLA breaches (line/bar/pie charts), team performance comparisons, and real-time ticket status per agent. Plotly + Pandas; easy to plug in your own JIRA data or CSV exports [citation:3][citation:15]. |
| **[django-customersatisfactionmetrics](https://github.com/pescheckit/customersatisfactionmetrics)** | [![Stars](https://img.shields.io/github/stars/pescheckit/customersatisfactionmetrics?style=social&color=white)](https://github.com/pescheckit/customersatisfactionmetrics/stargazers) | Django package for creating and managing CSAT, NPS, CES, and generic surveys. Supports anonymous and logged-in responses with user metadata (IP, user agent). Includes impression tracking, touchpoint cooldowns, and subject links to tie feedback to application objects [citation:9]. |
| **[retentioneering-tools](https://github.com/retentioneering/retentioneering-tools)** | [![Stars](https://img.shields.io/github/stars/retentioneering/retentioneering-tools?style=social&color=white)](https://github.com/retentioneering/retentioneering-tools/stargazers) | Python toolkit for clickstream and event log analytics. Customer journey mapping, behavioral segmentation, A/B test analysis, Markov chain simulation, and graph-based user flow visualization. ~907 stars, actively maintained [citation:14]. |

**Frameworks for building custom systems**: Combine **erxes** for a full experience management stack with CRM and knowledge base, **CustomerCore** for real-time AI triage and churn risk scoring, and **InsightPulse** for voice-of-customer sentiment analysis—all deployable via Docker without per-agent SaaS fees. For lightweight SLA dashboards, **Smart Support Analytics** provides a quick JIRA-connected starting point.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CX and service analytics platforms handle sensitive customer interaction data and satisfaction scores; enforce role-based access, PII redaction, and compliance with applicable data protection regulations.
- **Open-source CX analytics is fragmented and requires assembly.** erxes offers the most complete platform but is source-available (fair-code) rather than fully OSI open-source [citation:5][citation:13]. CustomerCore is technically impressive but early-stage and complex to operate [citation:2][citation:10]. InsightPulse is explicitly a portfolio project with a sentiment model accuracy of 0.583 Macro-F1—not production-grade for automated decisions without human review [citation:6]. Commercial platforms (Zendesk Explore, Freshworks Analytics, ServiceNow) are bundled with their respective service subscriptions and not sold standalone.

---

**Made for CX analysts, support operations managers, customer success leaders, and developers building service intelligence infrastructure.**  
Let's make customer experience analytics more open, actionable, and human-centered.
