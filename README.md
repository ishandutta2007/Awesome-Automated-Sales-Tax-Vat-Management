# Awesome Automated Sales Tax & VAT Management

A curated list of automated sales tax and VAT compliance SaaS platforms, calculation engines, and developer tools.

---

## Sector Overview & Market Dynamics

The global tax automation and management software sector is estimated at approximately **$22 billion to $28 billion**, projected to exceed **$50 billion by the early 2030s** expanding at a compound annual growth rate (CAGR) of 10%–12%. The market is **moderately fragmented overall** due to diverse jurisdictional mandates and localized cross-border regulations, yet exhibits **high concentration at the top tier** where a handful of dominant enterprise and payment-native platforms command the majority of corporate tax compliance volume.

---

## SaaS Sales Tax & VAT Platforms

| Company / Product | Company Size (Valuation / Revenue) | Starting Pricing (Specific Tier) | Free Tier / Trial Limits | Details & Capabilities |
|---|---|---|---|---|
| **Stripe Tax** (includes **TaxJar**) | **$159B valuation** (~$6.8B net revenue; TaxJar acquired for ~$850M–$900M) | **$90/month** (Tax Complete starter plan for 200 transactions/mo & 2 registrations/yr) or **0.50% / $0.50 per transaction** (Tax Basic pay-as-you-go where registered) | **TaxJar:** 30-day free trial (no credit card required, unlimited sandbox calculation during trial); **Stripe Tax:** Free sales monitoring/threshold alerts across jurisdictions until registration is triggered | Automated calculation, nexus tracking, and filing support across 50+ countries and all US states. |
| **Thomson Reuters ONESOURCE** | **$53B market cap** (~$8B TTM revenue) | **$12,000/year** (custom entry tier for standard ERP determination modules via AWS Marketplace / direct licensing) | **No free tier**; 30-day sales-assisted POC/pilot sandbox for qualified enterprise accounts upon request | Enterprise multi-tier determination, global VAT/GST compliance, and deep ERP integrations (SAP, Oracle, Workday). |
| **Avalara (AvaTax)** | **$8.4B valuation** (Acquired by Vista Equity Partners in 2022) | **$69/state/month** (SST Services tier) or **$79/state/month** (Core Compliance tier, annual billing, 3-state minimum) | **90-day free trial** (AvaTax developer sandbox evaluation with up to 500 calculation calls) | 1,400+ pre-built integrations, real-time rates across 13,000+ US jurisdictions, international cross-border calculation and automated filing. |
| **Chargebee Tax** | **$3.5B valuation** (Series H funding) | **$0/month** (Starter tier up to $250k cumulative lifetime billing; then 0.75% overage) or **$599/month** (Performance tier billed annually for up to $100k/mo MRR) | **Free forever plan** up to $250,000 cumulative lifetime billing; paid tiers include a **14-day free trial** with full feature access | Subscription billing native tax engine with automated rules and direct Avalara/Vertex connector support. |
| **Sovos Compliance** | **$2.5B–$3.0B valuation** (~$400M+ revenue; backed by Hg & TA Associates) | **$10,000/year** (Small/Mid tier starting contract for basic single-module determination <50k transactions) | **No free tier** for enterprise tax engines; **7-day free trial** available specifically for *Sovos ReportMyUP* product (credit card required) | Specializes in global indirect tax determination, continuous transaction controls (CTC), e-invoicing mandates, and statutory reporting. |
| **Vertex, Inc.** (includes **Taxamo**) | **$2.5B market cap** (~$650M revenue; acquired Taxamo for $200M in 2021) | **$8,500/year** (~$708/month entry-level subscription for small-scale cloud connectors; standard median enterprise deployment at ~$33,000/year) | **No free tier**; guided sandbox testing and customized proof-of-concept environment available upon vendor sales demo approval | Enterprise indirect tax software for corporate buyers, cross-border e-commerce VAT/GST compliance (Taxamo Assure), and omnichannel commerce. |
| **Anrok** | **$525M valuation** (Series C funding) | **$100/market/month** (Starter tier; each US state, EU OSS, or country counted as an active market) | **No permanent free tier**; pre-sale custom sandbox environment provided during onboarding evaluation upon demo request | Built specifically for SaaS and digital subscription businesses; integrates directly with Stripe, Chargebee, and corporate ERPs. |
| **Quaderno** | Bootstrapped / Acquired by Visma (~$3M ARR) | **€29/month** (Hobby plan, includes up to 25 transactions/month; next tier is €49/month for up to 100 transactions) | **7-day free trial** (Includes full sandbox testing access to tax calculation, invoicing, and threshold notifications) | Automated tax receipts, instant threshold monitoring, and filing assistance for digital products, SaaS, and e-commerce. |

---

## Open-Source Tax Calculation Libraries

*Note: These libraries provide offline or API-assisted calculation logic and tax rate determination, but do not handle automated remittances or government filing.*

| Project | Stars | Language | Capabilities |
|---|---|---|---|
| **[mpociot/vat-calculator](https://github.com/mpociot/vat-calculator)** | ~1.2k | PHP | EU VAT calculation library with European VIES VAT number validation and reverse charge handling. |
| **[node-sales-tax](https://github.com/valeriansaliou/node-sales-tax)** | ~310+ | TypeScript / Node.js | International sales tax and VAT calculator for Node.js with offline tax rates and VAT fraud checks. |
| **[OpenSalesTax](https://github.com/opensalestax)** | Community | PHP / Python | Self-hosted US sales tax engine with integrations/connectors for Odoo, Saleor, and Drupal Commerce. |
| **[nexus-tax](https://github.com)** | Community | PHP | Multi-jurisdiction economic nexus determination, calculation engine, and reverse charge rule handler. |

---

## Contributing

Contributions and additions are welcome! Please ensure any submitted SaaS platform includes verified starting tier pricing, free tier/trial details, and company scale metrics.
