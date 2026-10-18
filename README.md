# Fathoni (Toni) Ali Mukti

**AI Engineer · Full-Stack Developer** — Java, Indonesia (UTC+7). Remote worldwide, overlapping US and EU hours.

Nearly three years building ERP systems for a pharmaceutical manufacturer — several production apps in daily use by around 200 staff across sales, factory and internal HR. Then two full ERP products built and deployed solo, with LLM features running in them today.

## Open the demos

| | |
|---|---|
| **[ERP Sales](https://erp-sales.aetherglo.com/)** | Field sales: regions → orders, 4-tier approval ladder, RAG business-rule validation returning structured risk scores, email-to-order pipeline, document-grounded assistant. One-click sign-in. |
| **[ERP Warehouse](https://erp-warehouse.aetherglo.com/)** | WMS with a live 3D floor view, real-time stock across 3 warehouses, RBAC across 19 modules, AI assistant grounded in live stock plus your own procedures. |

Every module works on seeded sample data — no setup, no invite, no sales call.

## How I work on LLM features

- **Guardrails before capability** — controlled CRUD instead of raw SQL, confirmation flows on every write, full audit log.
- **The model proposes, a person approves** — no agent action lands without a human confirming it.
- **Measured, not vibes** — an 8-case benchmark scoring 6 fields per case gates the test suite, and the suite asserts all six decision branches actually fire.
- **Provider-agnostic** — an OpenAI-compatible layer, so models swap without touching the app. Production runs **Upstage Solar-pro-4**.
- **Honest about limits** — the benchmark verifies the plumbing around the model, not the model's quality. That is graded separately, on an opt-in live path.

## Stack

`TypeScript` `Bun` `Turborepo` `React 19` `tRPC` `Prisma` `PostgreSQL` `Express` `Zod` `Tauri` `Tailwind CSS` `n8n` `Docker` `AWS`

## Availability

Open to **remote AI Engineer roles worldwide**, overlapping **US and EU hours**. Available immediately.

- 📄 [Résumé — 1 page PDF](https://toni.aetherglo.com/Fathoni_Ali_Mukti_Resume.pdf)
- 🌍 [toni.aetherglo.com](https://toni.aetherglo.com/) — case studies and build notes
- ✍️ [toni.aetherglo.com/blog](https://toni.aetherglo.com/blog/) — published build logs
- 🔗 [LinkedIn](https://www.linkedin.com/in/fathoni/)

---

Both projects live in this account: [`erp-sales`](https://github.com/fathonialimukti/erp-sales) · [`erp-warehouse`](https://github.com/fathonialimukti/erp-warehouse)
