# Raptor

**Market intelligence for ecommerce: explore products, investigate competitors and model cash-on-delivery economics.**

[Live landing](https://radar-q3oz.onrender.com/) · [Feature tour](FEATURES.md) · [System map](SYSTEM.md) · [Engineering](ENGINEERING.md)

Raptor, previously Radar, connects a supplier catalog, timestamped inventory observations, advertising references and product investigations in one application. Collection, matching and assistant access are components of the same product.

![Raptor product catalog in native light mode](assets/raptor-catalog-reviewed-2026-11-07.png)

*Current application, November 7, 2026; native Spanish/light interface. Counts and stock describe observations, not confirmed sales. [Capture details](SCREENSHOTS.md).*

## From the landing to the workspace

The public landing introduces the product; the authenticated application contains the catalog, research and calculation tools.

![Raptor public landing](assets/raptor-landing-2026-11-07.png)

## What I built

| Area | Work |
| --- | --- |
| Explore | Product catalog, category navigation, filters and supplier information |
| Investigate | Saved product investigations, advertising references and supplier-match review |
| Calculate | Cash-on-delivery assumptions, delivery/return costs and advertising break-even calculations |
| Connect | Catalog collection, persistent observations and authenticated read-only access for AI assistants |

[See the current screens and implementation boundaries](FEATURES.md).

## Engineering approach

A similar title does not prove two listings are the same product. Supplier matches remain proposals until reviewed; stock changes remain observations. Missing costs stay unknown. [Read the technical decisions](ENGINEERING.md).

**JavaScript / TypeScript · React · Node.js · Express · SQLite · Python · MCP · S3-compatible storage**

**All my development work presented here was done with AI assistance.** I use programming and software engineering fundamentals to define requirements, review code, debug failures, test behavior and take responsibility for technical decisions.

Application source, databases and private research remain private. This repository contains the public case study and original interface captures. It claims no matching-accuracy, revenue or profitability results.

[Juan Diego Rios](https://github.com/excelenciaempire)
