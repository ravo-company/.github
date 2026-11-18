## RAVO Company

**Software house that builds the operations software behind law firms and real-estate businesses.** Products run in production, are multi-tenant, and use AI with a human approving every decision that matters.

#### Products

| | |
|---|---|
| **RAVO Suite** | Operations platform for fractional-ownership resorts: sales floor, quota inventory, WhatsApp customer care, billing, P&L |
| **Legal Ops Portal** | AI-assisted intake and approval of court notices for law firms, integrated with DJEN, DataJud and ADVBox |
| **RAVO OS** | Internal cockpit: CRM, recurring revenue, P&L, goals, customer success |

#### Engineering standards

- **Data:** PostgreSQL as the source of truth, tenant isolation with Row-Level Security, forward-only migrations
- **Delivery:** every change goes through a small PR with green CI (lint, types, tests, secret scan, E2E smoke); decisions are written down as ADRs
- **Security:** least-privilege database roles, an auth policy required on every API route, secrets kept out of git and out of client bundles
- **AI:** models propose, people approve, and every write to a system of record is audited

Repositories are private to protect customer data. Access for technical evaluation is available on request.

📫 tecnologia@ravocompany.com.br · 📍 Brazil (UTC−3)
