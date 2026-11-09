# Awesome-Automated-Sales-Tax-Vat-Management

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **Chargebee Tax has no standalone price**, **Vertex has no public pricing page**, and the open-source side is a set of libraries, not platforms.

## The data problems

**Chargebee Tax is not a standalone product.** Chargebee's documentation describes tax profile configuration and integration with Avalara—**there is no separate "Chargebee Tax" SKU or pricing page** . It is a feature of the Chargebee billing platform.

**Vertex publishes no prices.** `vertexinc.com/pricing` returns a 404; O Series and Vertex Cloud are quoted after a demo based on tax types, jurisdictions, and systems . Do not fabricate a figure.

**Taxamo's pricing is "not recorded"** in the API directories surfaced—no free tier, no rate . Mark quote-only.

**Stripe Tax has a genuinely published, complex pricing model.** Two plans: **Tax Complete** (subscription, 1-year contract, registration + calculation + filing) and **Tax Basic** (pay-as-you-go, calculation only) . Tax Complete tiers: **$90/mo** (200 transactions), **$430/mo** (1,000), **$1,000/mo** (2,500), **$1,500/mo** (5,000), with per-transaction overages from $0.35–$0.50 and registration/filing fees that vary by jurisdiction .

## What the search results actually contain

| Platform | Pricing | Verified detail |
|---|---|---|
| **Avalara** | **$79/state/month annual** (Core Compliance, 3-state min); **$69/state/month** (SST Services, no minimum)  | No per-return fees; unlimited returns; 1,400+ integrations  |
| **Anrok** | **$100/market/month** (Starter); Custom quote; Pro **$500/mo**; Enterprise **$1,000/mo**  | Per-market pricing—each US state, each EU OSS, each country is a market  |
| **TaxJar** | **Starter from $39/mo**; **Professional from $99/mo**  | Order-volume tiers; flex fees for peak months  |
| **Quaderno** | **€29/mo** (Hobby, 25 transactions) to **€10,500/mo** (1M transactions)  | Transaction-based; unlimited users/jurisdictions on paid tiers; 7-day free trial  |
| **Sovos** | **Small-mid: from ~$1X,XXX/year** (single module, <50K transactions)  | E-invoicing jurisdictions add **$15K–$50K/year each**; implementation **30–100% of Year 1**  |
| **Stripe Tax** | **$90–$1,500/mo** (Tax Complete); Tax Basic pay-as-you-go  | Registration and filing fees vary by country  |
| **Vertex** | **No public pricing**  | Quote after demo; tax content licensed by type and region  |
| **Chargebee Tax** | **No standalone price**  | Feature of billing platform; Avalara integration available  |
| **Thomson Reuters ONESOURCE** | **Custom pricing**; must purchase ONESOURCE license  | Annual integration subscription fee  |
| **Taxamo** | **Pricing not recorded**  | Paid subscription/licence  |

**Open-source projects (usable):**

| Project | Stars | What it actually does |
|---|---|---|
| **node-sales-tax** | **311**  | International sales tax calculator for Node.js; offline with optional VAT fraud check; rates kept up-to-date  |
| **OpenSalesTax** | Not surfaced | Self-hosted US sales tax engine; PHP SDK and connectors for Odoo, Saleor, Drupal Commerce  |
| **mpociot/vat-calculator** | **1,189**  | EU VAT calculation for PHP; 2.99M downloads  |
| **nexus-tax** | Not surfaced | Framework-agnostic PHP tax engine with multi-jurisdiction support, reverse charge, nexus determination  |

**None of these are SaaS replacements.** They are calculation libraries/engines you embed in your own application. **OpenSalesTax** is the closest to a self-hosted platform, but it is calculation-only—the merchant remits .

## What I recommend

**Split into three honest categories:**

**1. SaaS Sales Tax & VAT Platforms** (proprietary):
- **Avalara** — $69–$79/state/month 
- **Anrok** — $100/market/month 
- **TaxJar** — from $39/month 
- **Quaderno** — €29–€10,500/month 
- **Stripe Tax** — $90–$1,500/month 
- **Sovos** — from ~$1X,XXX/year 
- **Vertex, Chargebee Tax, ONESOURCE, Taxamo** — **pricing not surfaced** 

**2. Open-Source Calculation Libraries** (not platforms):
- **node-sales-tax** (311 stars) 
- **mpociot/vat-calculator** (1,189 stars) 
- **OpenSalesTax** (self-hosted engine, connectors only) 
- **nexus-tax** (PHP engine) 

**Flag the pricing model differences explicitly:** per-state (Avalara), per-market (Anrok), per-order-volume (TaxJar), per-transaction (Quaderno), per-subscription-tier (Stripe), and enterprise-quote (Sovos, Vertex) produce incomparable costs at the same footprint.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate Vertex, Chargebee, ONESOURCE, or Taxamo pricing, or present calculation libraries as SaaS platform replacements.
