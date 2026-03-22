<div align="center">

<img src="https://img.shields.io/badge/-%F0%9F%8D3%20MiseOS-1A1F36?style=for-the-badge&logoColor=4CAF50" alt="MiseOS" height="40"/>

# Kitchen Intelligence, Engineered.

**The operating system for professional kitchens — powered by machine learning.**

[![Status](https://img.shields.io/badge/Status-Building%20MVP-4CAF50?style=flat-square)](https://miseos.io)
[![Stack](https://img.shields.io/badge/Stack-NestJS%20%7C%20NextJS%20%7C%20PostgreSQL-1A1F36?style=flat-square)](https://miseos.io)
[![Market](https://img.shields.io/badge/Market-US%20%7C%20AU%20%7C%20UK%20%7C%20EU-FF6F00?style=flat-square)](https://miseos.io)

</div>

---

## What is MiseOS?

Like *mise en place* transformed kitchen efficiency, **MiseOS transforms kitchen intelligence.**

MiseOS is a B2B SaaS platform that automates the complexity of modern food operations — combining culinary domain expertise with machine learning to give professional kitchens a true operating system.

> *Stop guessing. Start knowing.*

---

## Core Capabilities

| Capability | Description |
|---|---|
| 🤖 **AI Ingredient Categorization** | 95%+ accuracy across 60K+ ingredients — seconds, not hours |
| 🧬 **Nutrition Analysis** | Automatic per-recipe and per-menu nutrition calculated in real-time |
| 💰 **Recipe Costing** | Live food cost tracking with yield & shrinkage calculations |
| 🛡️ **Compliance Labels** | FDA, CFIA, and EU 1169/2011 label generation — automated |
| 📦 **Inventory Forecasting** | ML-powered demand planning and ordering optimization |
| 🏭 **Supplier Management** | Full procurement lifecycle — from vendor to plate |

---

## Who We Build For

- **Kitchen Managers** — operational control and cost visibility
- **Executive Chefs** — recipe intelligence and menu planning
- **Food Operations Directors** — multi-location oversight
- **Compliance Managers** — regulatory label generation at scale
- **Multi-location Restaurant Groups** — unified kitchen data platform

---

## Technical Foundation

```
Backend      NestJS · PostgreSQL (RLS) · Knex Migrations
Frontend     NextJS · React · Tailwind v4 · Mantine v7
Infra        k3s (Kubernetes) · HashiCorp Vault · CloudNativePG · MinIO
Data         USDA FoodData Central · 263 ingredient categories · 4-level hierarchy
Auth         Multi-tenant · Row-level security · PayPal billing
Email        Brevo transactional
```

### Architecture at a Glance

```
Supplier → Product → [Ingredient Template] → Recipe → Menu → Sales
                              ↓
                         Inventory ← ML Forecasting ← Orders
```

---

## Entity Model

```
📦 Product      Real purchasable items (SKU, supplier, price, unit)
🍎 Ingredient   Nutritional templates — system defaults + user custom
🍳 Recipe       Prepared dishes (nutrition labels + allergens REQUIRED)
📅 Menu         Service collections (breakfast / lunch / dinner / catering)
🏪 Inventory    Physical stock tracking per product per location
📈 Sales        Volume logging for forecasting and profitability
🚚 Supplier     Vendor management, lead times, performance scoring
```

---

## Roadmap

**Phase 1 — Foundation (MVP)** `Current`
- Recipe CRUD + multi-step instructions
- Ingredient library (2,847 system defaults + custom)
- Nutrition analysis engine (per 100g, per serving, per menu)
- Compliance label generator (FDA · CFIA · EU)
- Basic inventory tracking

**Phase 2 — Intelligence** `Q2 2026`
- Menu planning calendar (drag-drop)
- Sales volume tracking + revenue reporting
- Supplier management + purchase orders
- Advanced inventory (par levels, waste tracking, FIFO/LIFO)

**Phase 3 — AI/ML** `Q3–Q4 2026`
- Natural language search ("vegetarian recipes under $5")
- ML demand forecasting with seasonal adjustment
- Automated ordering optimization
- Cost reduction + ingredient substitution recommendations

**Phase 4 — Analytics** `2027`
- Recipe profitability dashboard
- Nutritional compliance analytics
- Operational velocity metrics
- Virtual kitchen assistant

---

## Repositories

| Repo | Description |
|---|---|
| `miseos-infra` | k3s infrastructure, Helm charts, bootstrap wizard, Vault config |
| `miseos-backend` | NestJS monorepo — core API, domain services, DB ownership |
| `miseos-migrations` | Knex migration scripts (decoupled from app) |
| `miseos-frontend` | NextJS + React — kitchen management dashboard |
| `.github` | Org profile and shared workflows |

---

## Target Markets

**English-speaking B2B** — United States · Australia · United Kingdom · European Union

---

<div align="center">

**Built with culinary expertise and engineering precision.**

[![Website](https://img.shields.io/badge/miseos.io-1A1F36?style=flat-square&logo=globe&logoColor=4CAF50)](https://miseos.io)
&nbsp;
[![Brand](https://img.shields.io/badge/Brand%20Guide-FF6F00?style=flat-square)](https://brand.miseos.io)
&nbsp;
[![Wiki](https://img.shields.io/badge/Engineering%20Wiki-4CAF50?style=flat-square)](https://dashi.miseos.io)

*© 2025–2026 MiseOS · Kitchen intelligence, engineered.*

</div>
