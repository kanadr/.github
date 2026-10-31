## Kanadr: white-label hosted PBX for telecom operators

Kanadr is a multi-tenant IP PBX (centrex) that telecom operators, integrators and resellers sell under their own brand. Each operator runs it on its own Debian VM, or we host it for them in France. Their business customers only see the operator's brand.

- **Built for operators**: account hierarchy (operator, reseller, customer, user), one SIP trunk per customer, per-call rating on three price lists with CSV export.
- **API first**: everything the portal does goes through a public REST API, documented in OpenAPI in English and French. It also has signed webhooks and Prometheus metrics.
- **AI-ready**: a built-in [MCP server](https://docs.kanadr.com/guide/operateur/en/operateur/mcp.html) lets Claude, ChatGPT, Le Chat or any MCP client use the API with the user's own rights.
- **Measured capacity**: 200 concurrent calls on 2 vCPU and 4 GB. Active/passive high availability with failover in under two minutes.
- **Core written in Rust**, running on Debian 13, PostgreSQL and nginx.

**Links**: [website](https://www.kanadr.com/en) · [documentation](https://docs.kanadr.com/) · [API reference](https://docs.kanadr.com/api/en/) · [pricing](https://www.kanadr.com/en/tarifs) · [book a demo](https://www.kanadr.com/en/contact)

---

**En français** : Kanadr est un centrex IP en marque blanche pour opérateurs télécom, intégrateurs et revendeurs, installé chez l'opérateur ou hébergé en France. Voir le [site](https://www.kanadr.com/) et la [documentation](https://docs.kanadr.com/).
