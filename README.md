# AgentLEX – Multi-Agent Regulatory Intelligence for Product Compliance

AgentLEX is a multi-agent system that discovers, extracts, and tracks regulatory requirements for any product. Given a product description (features, markets, materials), it identifies relevant EU (and optionally global) regulations, extracts structured information (IDs, clauses, dates, jurisdictions), stores them in a persistent registry, detects new or updated regulations, generates compliance summaries with mitigation measures, and continuously evaluates its own performance through quality tests.

---

## Goal

AgentLEX aims to:

- Discover all relevant regulations for a given product in the EU (and optionally worldwide).
- Extract structured regulatory data: IDs, clauses, dates, jurisdictions, scope.
- Store results in a persistent, versioned regulatory registry.
- Detect new or updated regulations on subsequent runs.
- Generate a compliance summary and suggested mitigation measures.
- Perform continuous quality evaluation across agents and pipelines.

---

## Motivation

Regulations are numerous, evolving, and fragmented across multiple sources (EUR-Lex, ECHA, ESPR, AI Act, RoHS, etc.).

Engineers, compliance officers, and LCA practitioners increasingly need fast, explainable answers to:

- **“Which regulations apply to my product in market X?”**
- **“What changed since last time?”**

As virtual twins (e.g., 3DEXPERIENCE-based digital twins) become central to product development, their value increases when they become **compliance-aware**.

A multi-agent, ontology-driven system can transform raw legal text into structured, reusable, and version-controlled regulatory knowledge.

---
