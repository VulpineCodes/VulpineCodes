# Hi, I'm Franklin

Computer Science & Cognitive Studies at **Vanderbilt University, class of 2027**. I grew up in Lagos, Nigeria, and I'm interested in building systems that are reliable under real-world messiness — fraud graphs, pharmacy inventory, donated books getting to the right kids.

Previously a Software Engineering intern at **Microsoft** (Xbox Commerce Feeds & Risk), where I built a fraud investigation tool with Node.js, KQL / Azure Data Explorer, and Cytoscape.js — including graph expansion for flagged accounts, an AI fraud-signal integration via MCP, and security hardening work. I've also done VR research at Vanderbilt's Wallace Multisensory Lab and built an early travel assistant during a FactSet externship.

**Looking for:** 2027 new-grad roles in full-stack / backend engineering, data & infrastructure engineering, and AI application engineering.

## Flagship projects

### [Chapters of Change](https://github.com/VulpineCodes/chapters-of-change)
A full-stack platform connecting donors of used comics & manga with schools, libraries, and community organizations.
**TypeScript · Next.js · NestJS · PostgreSQL / Prisma · Redis / BullMQ**
The interesting engineering: a strict donation-lifecycle state machine, server-enforced RBAC, a transactional outbox so status changes and notifications can't diverge, and idempotent request handling — all covered by tests for concurrent/duplicate submissions and authorization failures.

### [Myles — Travel Intelligence Assistant](https://github.com/VulpineCodes/myles)
A tool-using AI travel planner that compares options against your budget and constraints — and refuses to invent prices when providers fail.
**Python · FastAPI · LangGraph · Next.js · PostgreSQL · Redis**
Deterministic planning logic is separated from model reasoning, every recommendation cites a provider record, and a reproducible evaluation harness scores constraint satisfaction, grounding, and graceful failure handling.

### [PharmaFlow](https://github.com/VulpineCodes/pharmaflow)
A data platform helping small independent pharmacies — the kind my father ran in Lagos — move from paper ledgers to reliable inventory operations.
**Python · FastAPI · PostgreSQL · DuckDB · dbt · Airflow · Kafka/Redpanda · Terraform · Prometheus/Grafana**
Idempotent ingestion, validation with a quarantine you can actually inspect, reconciliation and discrepancy detection, and pipeline observability. Inventory/operations only — no patient data, ever.

## What I care about in code
- Correctness you can test: state machines, idempotency, data-quality checks
- Honest systems: no fabricated metrics, failures that are visible instead of silent
- Clear architecture write-ups — each repo's `ARCHITECTURE.md` explains the trade-offs, not just the stack

---

Demo links and screenshots will be added as deployments land. Pin order: Chapters of Change, Myles, PharmaFlow.
