# Project Status

**Project:** Dubai Global Trading Business  
**Phase:** Foundation Alignment + Broker/API Feasibility  
**Date:** 29-Sep-2026

## Locked Business Concept

The project is a **broker-backed branded trading platform**. Users will interact through our brand/interface while an existing licensed broker provides the underlying trading account, execution, liquidity/market access, margin engine, source-of-truth positions/orders and, under the current mandate, client-money custody and withdrawals.

### Non-negotiable constraints

- No market/trading P&L exposure for our entity.
- No dependence on whether clients win or lose trades.
- No B-book / principal / matched-principal dealing by our entity.
- No execution as broker/dealer.
- No client-money custody/control.
- No margin, settlement or liquidity-inventory exposure.
- Revenue must be commercial (commission, broker revenue share, platform/service fees, introduction economics, or legally permitted transparent markup), not client-loss based.
- Broker API / embedded workflow permission must be explicit in the commercial/legal agreement.

## Previous-Work Audit

The prior research was directionally aligned on broker execution/custody, but the clarified mandate required a governance reset:

- **KEEP / PRIORITISE:** broker-backed technology / embedded-broker model.
- **KEEP:** DIFC/DFSA Arranging route as a possible legal wrapper around a stronger client-facing role.
- **KEEP AS FALLBACK:** Mainland Category 5 Introduction/Promotion with broker-controlled trading.
- **OUT OF SCOPE:** own brokerage, dealing as principal, matched-principal dealing, B-book economics, and holding/controlling client assets.

Own-broker/dealing research is retained only to define regulatory boundaries we must not cross.

## Completed / Created

- Project repository and governance standard.
- Foundation business-model landscape and comparison workbooks.
- UAE regulatory-route and legal-perimeter deep dives.
- Batch 1 regulatory/business decision model.
- Batch 2 provider/country/commercial feasibility analysis.
- Foundation Alignment Audit & Target Model Lock v1.0.
- Target Model Control & Decision Register v1.0.
- Batch 3 Broker/API Partner Shortlist & Target-Model Fit v1.0.
- Batch 3 Broker/API Partner RFI & Shortlist workbook v1.0.

## Current Evidence-Based Position

1. The **business concept is approved/locked**; the exact UAE legal wrapper remains open.
2. UAE Mainland Category 5 Introduction is not a client-order execution licence for OTC derivatives / Spot FX.
3. DIFC/DFSA Arranging permissions are a serious candidate because arranging and dealing/custody are separately permissioned in the public register.
4. A pure technology/embedded-broker structure remains the preferred capital-light challenger if the actual order-entry workflow can remain broker-controlled and legally outside our own regulated execution/dealing role.
5. The licensed broker must remain execution counterparty and client-money holder under the current mandate.
6. Own brokerage/dealing is no longer an active candidate.
7. **cTrader Open API is currently the strongest technical-fit candidate** because official Spotware documentation supports custom trading applications, live trading, OAuth customer authorisation and customer use of API integrations within third-party applications.
8. **Direct broker proprietary APIs remain a parallel priority** because they may provide stronger commercial/legal alignment and better control over data/partnership terms.
9. Initial broker RFI candidates include Pepperstone, FxPro, FP Markets and the broader cTrader-affiliated broker ecosystem; none is approved until explicit third-party client-facing permission and commercial terms are confirmed in writing.

## Immediate Research Gate

Before a provider/legal wrapper is selected, resolve:

- exactly where the customer Buy/Sell instruction is legally received in each candidate workflow;
- whether our branded front end may initiate/order-route without crossing into dealing/execution;
- which brokers explicitly permit third-party branded client-facing trading through API/embedded components;
- customer-contract and data-ownership structure;
- broker revenue-share/per-lot economics and provider fees;
- target-country restrictions and broker country acceptance;
- total Year-1 cash requirement for the surviving no-market-risk models;
- at least two written broker confirmations covering the intended branded third-party workflow.

## Documentation Rule

Primary project artifacts remain Microsoft Office compatible (DOCX/XLSX/PPTX). GitHub is used minimally as the controlled project record; research and artifact generation are performed outside GitHub and synchronized at meaningful milestones.
