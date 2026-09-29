# Dubai Global Trading Business

End-to-end research, business planning, regulatory analysis, financial modelling, provider due diligence, risk assessment, and business architecture for a Dubai/UAE-based broker-backed global trading platform.

## Locked Project Concept

We are building a **branded client-facing trading platform that connects users to existing licensed brokers through approved APIs / embedded trading infrastructure**.

Our company is **not** intended to become the executing broker, market maker, principal dealer, client-money custodian, or proprietary risk-taker.

### Target flow

User → Our Branded Platform → Approved Broker API / Broker-Controlled Trading Workflow → Licensed Broker → Market / Liquidity

The licensed broker remains responsible for the underlying trading account, execution, liquidity/market access, margin engine, source-of-truth positions/orders, and under the current mandate client-money custody and withdrawals.

## Non-Negotiable Foundation Constraints

- **No market risk** for our entity.
- **No exposure to customer profit or loss.**
- **No B-book / principal / matched-principal dealing by our entity.**
- **No execution of customer trades as broker/dealer.**
- **No custody or control of customer trading funds.**
- **No margin, settlement or liquidity inventory exposure.**
- Revenue should come from transparent commercial economics such as per-lot/per-trade commission, broker revenue share, platform/service fees, affiliate/introduction economics, or legally permitted transparent markup — **not from customer losses**.
- Technical API availability is not enough: the broker must explicitly permit the intended third-party client-facing workflow contractually.

## Current Legal-Structure Research

The **business model is now locked**, but the lightest legally robust UAE wrapper is still being researched. Current surviving routes are:

1. **Broker-backed technology / embedded-broker model** — primary capital-light challenger.
2. **DIFC / DFSA Arranging model + broker execution/custody** — primary regulated route under investigation.
3. **Mainland Category 5 Introduction / Promotion + broker-controlled trading** — fallback if order entry must remain fully broker-side.

**Own brokerage / dealer / matched-principal models are out of scope under the current mandate.** They are retained only as regulatory boundary/benchmark research.

## Current Phase

**Phase 1 — Foundation, legal perimeter, broker/provider feasibility and commercial economics.**

No broker, API provider, UAE legal wrapper, target-country set, or final commercial agreement is approved yet.

## Working Method

Research → Verify → Compare → Challenge → Stress-test → Decide → Document → Re-verify.

Every material conclusion is classified as one of: Verified Fact, Provisional Fact, Assumption, Open Question, Decision, Rejected Option, or Risk.

## Documentation Standard

Primary project artifacts are Microsoft Office-compatible:

- DOCX — research reports, business plans, regulatory and commercial analysis
- XLSX — comparison matrices, financial models, risk registers, decision logs
- PPTX — executive summaries, business architecture, diagrams and decision presentations

Diagrams, flowcharts, comparison tables and visual decision aids are included where they materially improve analysis.

## Repository Structure

- `00_Master/`
- `01_Foundation/`
- `02_Market_Research/`
- `03_Business_Models/`
- `04_UAE_Regulation/`
- `05_Global_Markets/`
- `06_Brokers_and_Providers/`
- `07_Commercial_Model/`
- `08_Financial_Model/`
- `09_Risk/`
- `10_Business_Architecture/`
- `11_Product_and_Operations/`
- `12_Marketing_and_Growth/`
- `13_Launch_and_Scale/`
- `14_Decisions/`
- `15_Research_Evidence/`

## Governance Rule

No licence, broker, API, provider, country, commercial structure, or revenue model is labelled “best” until primary evidence is documented, alternatives are compared, downside cases are challenged, and the result remains consistent with the no-market-risk / no-execution / no-custody mandate.

---

This repository is the controlled project record. Research and working analysis may be performed outside GitHub; only synchronized project artifacts and approved supporting files are committed here.
