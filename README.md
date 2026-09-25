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

My projects live in two monorepos (plus a standalone SSRS reporting portal) — each subproject keeps its own README and full commit history.

**[warehouse-ai-lab](https://github.com/joshuaross1014-byte/warehouse-ai-lab)** — *the AI-ops suite: detect, simulate, act, understand*
- **[ai-ops-playbook](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/ai-ops-playbook)** — *start here:* how I give an AI assistant real access to production ERP/WMS systems and keep it safe — the MCP server pattern, a layered safety model, the automation pipeline, and the memory architecture behind it.
- **[warehouse-twin](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/warehouse-twin)** — a digital twin of a grocery DC: zero-dependency discrete-event simulation grounded in real WMS operating statistics, with an AI copilot that designs and runs the experiments (staffing sweeps, growth stress-tests, automation payback, wave vs waveless release). **[Live interactive dashboard →](https://joshuaross1014-byte.github.io/warehouse-ai-lab/)**
- **[warehouse-aiops](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/warehouse-aiops)** — self-healing warehouse operations with a human in the loop: detect → diagnose → propose → **approve** → execute → verify → runbook. Proposals are data, execution only on explicit approval, every outcome audited.
- **[sql-codebase-mcp](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/sql-codebase-mcp)** — turn any SQL Server codebase into an AI-queryable dependency graph: "what breaks if I change this table?" answered in milliseconds. Field-tested on a production WMS codebase (515 procedures).
- **[claude-ops-toolkit](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/claude-ops-toolkit)** — AI diagnostic playbooks + always-on monitors (silent-when-clean) with Slack alerting over SAP B1 (HANA) and a SQL Server WMS.
- **[advantage-architect-mcp](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/advantage-architect-mcp)** · **[kore-ui-mcp](https://github.com/joshuaross1014-byte/warehouse-ai-lab/tree/main/kore-ui-mcp)** — build a Körber WMS's RF-gun screens and web UI directly over MCP, from a reverse-engineered model of the vendor's design database.

**[wms-engineering](https://github.com/joshuaross1014-byte/wms-engineering)** — *production engineering*
- **[transfer-lefo-picking](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/transfer-lefo-picking)** *(new)* — transfers allocate latest-expiry-first while store orders keep FEFO: overrides in both allocation engines behind a per-warehouse switch, plus a guard for a latent mixed-wave defect I found through adversarial testing before go-live.
- **[b1_udf_bulk_update](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/python-automation/bots/b1_udf_bulk_update)** *(new)* — replaced a multi-file DTW job with a parallel, resumable Service Layer run: ~27k invoices updated (98.85%) in ~80 minutes, plus the SL failure modes it had to engineer around.
- **[supervisor-terminal-reset](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/supervisor-terminal-reset)** — self-service RF terminal reset that drops stranded inventory, clears the login lock, and *(new)* releases batches a crashed session left invisible to every scanner.
- **[rf-foreign-character-fix](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/rf-foreign-character-fix)** · **[market-receiving-pages](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/market-receiving-pages)** — vendor-platform ("Architect") customizations: RF guns crashing on multi-byte (CJK) item descriptions, and net-new web pages for batch market receiving. [Overview →](https://github.com/joshuaross1014-byte/wms-engineering/blob/main/docs/advantage-architect.md)
- **[pnl-automation](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/pnl-automation)** — inter-company billing on SAP B1 via the Service Layer: paired SO/AR per company, P&L workbook updates, and a finance-notification draft.
- **[python-automation](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/python-automation)** — replaced legacy Automation Anywhere bots with direct SAP B1 Service Layer REST integrations (resilient clients, idempotent posting, dry-run).
- **[wmspython](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/wmspython)** — Python tooling over a SQL Server WMS: connection helpers, a live-query MCP server, environment diff reports, and a codebase-audit suite (with tests).
- **[WMS-Stored-Procedures](https://github.com/joshuaross1014-byte/wms-engineering/tree/main/WMS-Stored-Procedures)** — production T-SQL I authored: idempotent wave planning, automated wave release with audit logging, and FEFO picking logic.

**[ssrs-reporting-portal](https://github.com/joshuaross1014-byte/ssrs-reporting-portal)** — *enterprise reporting, built from scratch*
- A SQL Server Reporting Services portal I designed and stood up on a dedicated report server: **136 reports + 299 shared datasets across 14 projects**, spanning SAP Business One (HANA) and a SQL Server WMS — receiving/shipping reconciliation, inventory & expiry, unallocated-order, and stock-comparison reporting. Sanitized work sample.

### Reach me
📫 joshua.ross1014@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/joshua-ross-084264203/)
