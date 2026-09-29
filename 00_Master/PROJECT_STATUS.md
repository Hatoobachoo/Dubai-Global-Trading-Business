# Project Status

**Project:** Dubai Global Trading Business  
**Phase:** Foundation Decision Draft v0.9 / Finalist Validation  
**Date:** 29-Sep-2026

## Locked Business Concept

The project is a **broker-backed branded trading platform**. Users interact through our brand/interface while an existing licensed broker provides the underlying trading account, execution, liquidity/market access, margin engine, source-of-truth positions/orders and client-money custody/withdrawals.

### Non-negotiable constraints

- No market/trading P&L exposure for our entity.
- No dependence on whether clients win or lose trades.
- No B-book / principal / matched-principal dealing by our entity.
- No execution as broker/dealer.
- No client-money custody/control.
- No margin, settlement or liquidity-inventory exposure.
- Revenue must be commercial (commission, broker revenue share, platform/service fees, introduction economics, or legally permitted transparent markup), not client-loss based.
- Broker API / embedded workflow permission must be explicit in the commercial/legal agreement.

## Current Finalist Structure

The broad provider scan is closed. Current finalist slots are:

1. Pepperstone
2. GO Markets
3. BlackBull Markets
4. FxPro
5. FP Markets
6. One direct regulated-broker proprietary-API candidate

cTrader Open API remains the leading technical route; direct broker proprietary APIs remain the main parallel route.

No finalist is approved until it passes the written RFI on branded third-party portal permission, broker-side execution/custody, country coverage, commercial economics, customer/data ownership, termination/suspension, migration rights and outage/SLA handling.

## Latest Foundation Pack

- `17_Foundation_Decision_Pack_v0.9.docx` — consolidated decision-ready research pack.
- `18_Foundation_Decision_Model_v0.9.xlsx` — consolidated regulatory, finalist, RFI, country, unit-economics, break-even, Year-1 cash, decision and evidence model.

These files are generated outside GitHub and retained as the current controlled working artifacts. GitHub remains a lightweight status/version-control record.

## Current Evidence-Based Position

1. The **business concept is approved/locked**; the exact UAE legal wrapper remains open.
2. Own brokerage/dealing, matched-principal dealing, client-money custody and B-book economics are out of scope.
3. **Tech-only / broker-controlled embedded workflow** is the preferred first legal hypothesis if specialist UAE advice confirms the actual UX/order flow stays outside regulated arranging.
4. **DIFC/DFSA Arranging** is the principal regulated fallback for a richer client-facing role without dealing/custody.
5. **Mainland Category 5 Introduction/Promotion** remains the lower-control fallback if order entry must remain broker-side.
6. **cTrader Open API** remains the strongest technical-fit candidate. Official Spotware material supports custom trading apps, live trading, OAuth 2.0 authorisation and allowing customers to use the API integration inside the developer's application.
7. Current Mainland SCA/CMA consolidated rules show Category 5 minimum paid-up capital of **AED 500,000** and separately list OTC/Spot-FX brokerage versus Introducing/Promotion.
8. DFSA currently lists Pepperstone Financial Services (DIFC) Limited with a Retail Clients endorsement and Arranging Deals in Investments permission.
9. DFSA states Authorised Firm application fees vary by Financial Services and range from **USD 15,000 to USD 70,000**.
10. Public commercial anchors include:
   - GO Markets Gold/XAU IB rebates of **US$1 / US$2 / US$3 per lot** by tier, custom rates, and up to US$5/lot for eligible high-volume partners.
   - BlackBull IB earnings advertised up to **US$10/lot**.
   - Pepperstone IB economics advertised up to **50% of spreads and commission**.
11. These public economics are planning anchors only; our branded portal model requires written negotiated terms.
12. Initial country screen keeps **UAE as core**, Kenya/Mauritius/South Africa as investigation markets, and UK/EU/Australia/US/India/Pakistan outside a generic Phase-1 offshore launch.
13. The current financial model intentionally shows that weak per-lot economics can require very large activity. At USD 50,000 monthly fixed OPEX: USD 1/lot requires ~50,000 lots/month; USD 2/lot ~25,000; USD 3/lot ~16,667.
14. Current Year-1 cash envelopes remain planning-only until quotes replace assumptions.

## Remaining Foundation Gates

Before Foundation Decision v1.0 can be approved:

- At least two brokers must explicitly approve the exact branded client-facing workflow in writing.
- UAE specialist advice must confirm the exact legal wrapper without execution, custody or principal risk for our entity.
- Quote-backed broker economics and provider fees must support sustainable unit economics.
- Initial allowed-country matrix must be confirmed by provider policy and legal review.
- Customer/data ownership, export and migration rights must be contractually acceptable.
- Termination/API-suspension terms must provide reasonable continuity protection.
- A credible fallback/second-broker path should exist.
- Year-1 cash requirement and break-even volume must be supportable by available capital.

## Current External Blockers

The remaining high-value evidence cannot be obtained from generic public research alone:

1. Written broker approval for our third-party branded portal/order-flow architecture.
2. Broker-specific fee/rebate schedules and minimum-volume commitments.
3. Broker-specific allowed/restricted-country lists and legal-entity routing.
4. Draft agreements covering customer/data ownership, export, termination and migration.
5. Specialist UAE legal/regulatory perimeter opinion on the exact user-interface and order-routing design.

## Next Phase

The next work is **finalist validation and Foundation Decision v1.0**, not broad provider discovery:

1. Send the standardised RFI to finalists.
2. Collect written commercial and architecture responses.
3. Obtain UAE specialist perimeter advice.
4. Replace public/assumed inputs with broker, legal, staffing and provider quotations.
5. Select primary launch route, primary broker and fallback broker.
6. Move into Business Architecture, Operating Plan and Launch Plan.

## Documentation Rule

Primary project artifacts remain Microsoft Office compatible (DOCX/XLSX/PPTX). GitHub is used minimally as the controlled project record; research and artifact generation are performed outside GitHub and synchronized at meaningful milestones.
