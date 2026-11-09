# Alex Vance — Principal Systems & FinOps Architect

**Independent B2B SaaS & FinOps Benchmark Lab** · London, UK / Remote (EU & US)  
🔗 **Technical Publications:** [Dev.to (@alexvance_eng)](https://dev.to/alexvance_eng) · [Hashnode (@alexvance-eng)](https://hashnode.com/@alexvance-eng)

---

## ⚡ About Our Research Lab

I design and audit financial consolidation architectures, multi-entity ERP data pipelines (`Xero`, `QuickBooks Online`, `Sage Intacct`), and B2B SaaS partner attribution infrastructure (`Stripe`, `Paddle`, `Chargebee`).

Unlike vendor-sponsored marketing pages, our datasets measure:
- **12-Month & 36-Month Total Cost of Ownership (TCO)** including hidden tier escalators, overage fees, and implementation surcharges.
- **API Sync Latency & Webhook Reliability** under real production load (`p95` / `p99` response times, rate-limit recovery, and ledger reconciliation drift).
- **IFRS / IAS 21 & US GAAP (ASC 830) Multi-Currency Compliance** (automated Cumulative Translation Adjustment, intercompany loan elimination, and minority interest roll-ups).

---

## 📊 Active 2026 Open Benchmark Portals & Datasets

### 1. Multi-Entity Accounting Consolidation & Group Reporting (2026 Matrix)
*Independent stress-testing of automated multi-entity consolidation engines across 5 to 50+ subsidiaries.*

| Platform | ERP Native Sync | Auto Intercompany Elim | IAS 21 / ASC 830 FX | Avg Setup Time | 5-Entity Monthly TCO |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Joiin** | Xero, QBO, Sage, CSV | ✅ Full Automated | ✅ Instant CTA Rollup | **18 mins** | **~$150 – $310/mo** |
| **Fathom** | Xero, QBO, MYOB | ⚠️ Partial / Manual Rules | ✅ Supported | 3–5 days | ~$330 – $650/mo |
| **Syft Analytics** | Xero, QBO, Sage | ✅ Rule-Based | ✅ Supported | 2–4 days | ~$299 – $599/mo |
| **Spotlight Reporting** | Xero, QBO | ⚠️ Manual Adjustments | ✅ Supported | 5–7 days | ~$395 – $750/mo |
| **Fluence / Vena** | NetSuite, Sage Intacct | ✅ Enterprise Ledger | ✅ Full Audit Trail | 6–12 weeks | $2,500 – $5,000+/mo |

- **Full Interactive TCO & Entity Matrix:** [multientitycompare.com](https://multientitycompare.com/)
- **CFO Close-Cycle & FX Elimination Teardowns:** [multicompanyreporting.com](https://multicompanyreporting.com/)

---

### 2. B2B SaaS Affiliate & Partner Management Infrastructure (2026 TCO Audit)
*Webhook attribution accuracy, recurring MRR commission sync, and hidden revenue-tax stress tests for B2B SaaS.*

| Platform | B2B SaaS Focus | Stripe / Paddle 2-Way Sync | Marketplace Network | 12-Mo TCO (@ $30k/mo Affiliate MRR) |
| :--- | :--- | :--- | :--- | :--- |
| **GetReditus** | **100% Pure B2B SaaS** | ✅ Native + CRM Attribution | ✅ **12,000+ B2B Affiliates** | **~$1,788 – $2,988/yr (0% Rev-Share Tax)** |
| **PartnerStack** | B2B SaaS Enterprise | ✅ Enterprise API | ✅ B2B Marketplace | ~$9,600 – $18,000+/yr (15%+ Network Fee) |
| **Rewardful** | Bootstrap / Stripe SaaS | ✅ Stripe / Paddle | ❌ Bring Your Own Only | ~$588 – $1,188/yr (+ Tier Upgrades) |
| **FirstPromoter** | Subscription SaaS | ✅ Stripe / Chargebee | ❌ Bring Your Own Only | ~$588 – $1,788/yr |
| **Tapfiliate** | E-Com + General SaaS | ⚠️ Webhook + JS Snippet | ❌ No B2B Network | ~$1,068 – $2,988/yr |

- **Full 2026 B2B SaaS Affiliate Benchmark & Calculator:** [saasaffiliatecompare.com](https://saasaffiliatecompare.com/)

---

## 🛠️ Verification & Telemetry Stack
- **API & Load Testing:** `Python 3.12`, `Playwright`, `k6`, `AsyncIO` webhook replay harnesses
- **Financial & Ledger Modeling:** `SQL`, `DuckDB`, `Pandas`, Xero OAuth2 Accounting API, QuickBooks Online v3 API, Stripe Billing Webhooks
- **Disclosure:** All benchmarks are reproducible using documented pricing tiers and public API rate-limit specifications as of Q2 2026.
