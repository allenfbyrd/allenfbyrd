# Allen Byrd

**AI, cybersecurity & GRC.** Architecting people-first AI, cybersecurity, and governance — for Fortune 500s and federal agencies.

📍 McLean, VA · 🔗 [allenfbyrd.com](https://allenfbyrd.com) · 💼 [LinkedIn](https://linkedin.com/in/allenfbyrd) · 📧 [allen@allenfbyrd.com](mailto:allen@allenfbyrd.com) · 📞 +1 (571) 293-1320 (public cell)

Open to new collaborators, team members, work, and business opportunities.

---

## What I do

I build scalable solutions at the intersection of **artificial intelligence**, **cybersecurity**, and **governance, risk & compliance** — with an emphasis on clear ownership, operational pragmatism, and teams that take pride in doing the fundamentals well. Practicality is not the same as timidity: the AI products that hold up under audit, regulatory scrutiny, and adversarial use are the ones built with security and governance as operational practices, not mere policy exercises.

**TL;DR:** I like building cool things and tinkering with electronics. When I make money off of it, that's great, but I'll be doing it until I kick the bucket regardless. **Come do it with me!**

## Selected open-source work

### [`Polycentric-Labs/evidentia`](https://github.com/Polycentric-Labs/evidentia) — *Python · AI · GRC*

Open-source, AI-enabled GRC engine. Cross-framework control gap analysis, AI-drafted risk statements grounded in your actual environment, and evidence collection + validation — all from a single lightweight Python tool. Framework-agnostic. No vendor lock-in. No consultant required. Multi-package monorepo with PyPI Trusted Publisher (OIDC), CycloneDX SBOM, and PEP 740 attestations on every release.

### [`Polycentric-Labs/regrails`](https://github.com/Polycentric-Labs/regrails) — *Python · LLM guardrails · regulatory compliance*

Weekend POC that codifies federal regulation (FERPA — 34 CFR Part 99, Subpart D) into 23 machine-readable rules with verbatim-text faithfulness gates, and wires them into an LLM advisor as a **deny-by-default guardrail with a full audit trail**. The decision step is deterministic (no LLM in the loop) and every demo run is replayable without an API key. A small-scale instance of one of the most concrete asks in modern AI-in-the-loop compliance: codify institutional policy into machine-readable logic, ensure alignment with regulatory requirements, keep the audit honest.

### [`perplexityai/modelcontextprotocol#111`](https://github.com/perplexityai/modelcontextprotocol/pull/111) — *upstream PR (open) · 2026-05-24*

Authored an additive PR to the Perplexity MCP server adding `perplexity_research_start` / `_poll` / `_cancel` tools so the Sonar Deep Research model works against MCP clients with hardcoded `tools/call` timeouts (e.g., Claude Desktop). Diagnosis used wire-level capture (stdin-tee of the MCP transport) to demonstrate that progress-notification-based fixes can't apply when the client never sends `_meta.progressToken`. 600+ lines TypeScript with 7 new vitest tests; complementary to existing issue [#110](https://github.com/perplexityai/modelcontextprotocol/issues/110).

## Working together

The fastest way to reach me is by [email](mailto:allen@allenfbyrd.com) or my [public cell](tel:+15712931320) (it's best to text it first, please). First reply within 48 hours, usually faster. For introductions and quick questions, a paragraph is plenty. I'm friendly and love meeting new folks, so don't be shy. Looking forward to chatting with you!

For background, current status, and résumé: **[allenfbyrd.com](https://allenfbyrd.com)**.
