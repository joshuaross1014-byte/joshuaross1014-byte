# Hi, I'm Joshua 👋

I'm a techno-functional **ERP & WMS systems analyst** — hands-on across SAP Business One
and Körber/Infios HighJump & KCloud WMS in a high-volume, multi-site distribution
operation (~515K picks/month). I build the **integration, automation, and AI tooling**
around those systems: turning brittle GUI-automation into API integrations, manual
processes into audited production code, and giving teams safe, governed AI access to
live operational data.

🌱 Always building — recently: applied AI for operations (MCP), discrete-event
simulation, and cross-platform ERP/WMS depth.

### What I work with
`SAP Business One (Service Layer/OData, HANA)` · `Körber/Infios HighJump & KCloud WMS` ·
`T-SQL / SQL Server` · `SAP HANA SQL` · `Python` · `REST APIs` · `AI / Model Context Protocol (MCP)` ·
`Automation Anywhere (RPA)` · `SSRS`

### Selected work

My projects live in two monorepos — each subproject keeps its own README and full commit history.

**[warehouse-ai-lab](https://github.com/joshuaross1014-byte/warehouse-ai-lab)** — *the AI-ops suite: detect, simulate, act, understand*
- **[warehouse-twin](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/warehouse-twin)** — a digital twin of a grocery DC: zero-dependency discrete-event simulation grounded in real WMS operating statistics, with an AI copilot that designs and runs the experiments (staffing sweeps, growth stress-tests, automation payback, wave vs waveless release). **[Live interactive dashboard →](https://joshuaross1014-byte.github.io/warehouse-ai-lab/)**
- **[warehouse-aiops](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/warehouse-aiops)** — self-healing warehouse operations with a human in the loop: detect → diagnose → propose → **approve** → execute → verify → runbook. Proposals are data, execution only on explicit approval, every outcome audited.
- **[sql-codebase-mcp](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/sql-codebase-mcp)** — turn any SQL Server codebase into an AI-queryable dependency graph: "what breaks if I change this table?" answered in milliseconds. Field-tested on a production WMS codebase (515 procedures).
- **[claude-ops-toolkit](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/claude-ops-toolkit)** — AI diagnostic playbooks + always-on monitors (silent-when-clean) with Slack alerting over SAP B1 (HANA) and a SQL Server WMS.

**[wms-engineering](https://github.com/joshuaross1014-byte/wms-engineering)** — *production engineering*
- **[python-automation](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/python-automation)** — replaced legacy Automation Anywhere bots with direct SAP B1 Service Layer REST integrations (resilient clients, idempotent posting, dry-run).
- **[wmspython](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/wmspython)** — Python tooling over a SQL Server WMS: connection helpers, a live-query MCP server, environment diff reports, and a codebase-audit suite (with tests).
- **[WMS-Stored-Procedures](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/WMS-Stored-Procedures)** — production T-SQL I authored: idempotent wave planning, automated wave release with audit logging, and FEFO picking logic.

### Reach me
📫 joshua.ross1014@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/joshua-ross-084264203/)
