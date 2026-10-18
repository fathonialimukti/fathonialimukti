# Fathoni (Toni) Ali Mukti

**AI Engineer · Full-Stack Developer** — Java, Indonesia (UTC+7). Remote worldwide, overlapping US/EU hours.

I build AI features end to end — data model, API, LLM layer, UI — and ship them into production. Nearly three years building ERP systems for a pharmaceutical manufacturer, plus two fully deployed ERP products with LLM features running on live data.

## Open the demos

| | |
|---|---|
| **[ERP Sales](https://erp-sales.aetherglo.com/)** | Field sales: regions → orders, 4-tier approval ladder, RAG order validation, email-to-order pipeline, document-grounded assistant. One-click sign-in, seeded sample data. |
| **[ERP Warehouse](https://erp-warehouse.aetherglo.com/)** | WMS with a live 3D floor view, real-time stock across 3 warehouses, RBAC across 19 modules, AI assistant grounded in live stock plus company procedures. |

Both are live and clickable. Every module works on sample data — no setup, no invite.

## How I work on LLM features

- **Guardrails before capability** — controlled CRUD instead of raw SQL, confirmation flows on every write, full audit log.
- **The model proposes, a person approves** — agent actions require explicit confirmation.
- **Measured, not vibes** — an 8-case benchmark scoring 6 fields per case gates the test suite, and the suite asserts all six decision branches actually fire.
- **Provider-agnostic** — an OpenAI-compatible layer, so models swap without touching the app. Production runs **Upstage Solar-pro-4**.
- **Honest about limits** — the benchmark verifies the plumbing around the model, not the model's quality. That is graded separately on an opt-in live path.

## Stack

`TypeScript` `React` `tRPC` `Prisma` `PostgreSQL` `Node.js` `Docker` `CI/CD` `n8n` `Tauri` `RAG` `LLM integrations`

## Availability

Open to **remote AI Engineer roles worldwide**, overlapping **US and EU hours**. Available immediately.

## Elsewhere

- [aetherglo.com](https://aetherglo.com) — case studies and build notes
- [aetherglo.com/blog](https://aetherglo.com/blog/) — published build logs
- [Résumé](https://aetherglo.com/resume) — 1 page, PDF
- [LinkedIn](https://www.linkedin.com/in/fathoni/)

---

Both projects live in this account: [`erp-sales`](https://github.com/fathonialimukti/erp-sales) · [`erp-warehouse`](https://github.com/fathonialimukti/erp-warehouse)
