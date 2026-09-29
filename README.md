# Adi Malka

I build and run software for small businesses: web apps and stores, automations
and AI agents, and the cloud infrastructure underneath them. One person, end to
end, from the first conversation to the thing running in production at 3am.

**[adimalka.com](https://adimalka.com)** · [Guides I write](https://adimalka.com/knowledge) · Israel

---

## In production

**[BuildForce Prime](https://buildforceprime.com)** — a marketplace for
construction labour. A contractor posts how many workers he needs and where,
vetted manpower corporations bid without seeing each other's prices, and he
compares and picks. Attendance, hours and payroll run on top of the match.
Multi-tenant, event-driven, mobile apps on the way.
<sub>React · TanStack Start · Fastify · Postgres · Prisma · Supabase · Docker</sub>

**PurserOps** — an inventory and purchasing agent for an Amazon Seller Central
operation. Reads supplier mail, consolidates stock across FBA, the manufacturer
and the 3PL, computes days of cover against seasonally matched prior-year
demand, and drafts the purchase order down to whole pallets and whole
truckloads. 123 tables, an LLM agent over the whole domain, and an MCP server so
it can be operated from a chat window.
<sub>TypeScript · Fastify · Postgres · Supabase · LangChain · MCP · Railway</sub>

**[Whole Naturals](https://wholenaturals.com)** — a Shopify store taken from an
empty theme to a live shop: content, catalogue, a price ladder and a cart
upsell. Bottles per order went from 1 to 1.8.
<sub>Shopify · Liquid · JavaScript</sub>

## Infrastructure

**[eks-production-stack](https://github.com/adimalka14/eks-production-stack)** —
a production-grade EKS cluster for a three-tier app: Karpenter for dynamic
nodes, HPA and VPA, full monitoring, S3 backups with lifecycle policies.

**[asterra-devops-assignment](https://github.com/adimalka14/asterra-devops-assignment)** —
GeoJSON lands in S3, moves through SQS, is processed and validated on
Kubernetes, stored in RDS and drawn on a map. All of it in Terraform, three
pipelines in GitHub Actions.

**[ha-cluster-docker](https://github.com/adimalka14/ha-cluster-docker)** — three
containerised Apache servers behind a floating IP, managed by Pacemaker and
Corosync, with Jenkins continuously proving failover still works.

---

## What I work in

**Languages** TypeScript · JavaScript · Python · SQL
**Backend** Node · Fastify · Express · Postgres · Prisma · Supabase · Redis
**Frontend** React · Next.js · TanStack Start · Tailwind
**Infrastructure** AWS · Kubernetes · EKS · Terraform · Docker · GitHub Actions · Karpenter
**AI** LangChain · MCP · agent loops and structured extraction over real business data

---

I write about the parts of this that cost people money: [cutting an AWS
bill](https://adimalka.com/aws-cost-optimization), [what actually breaks when
you build a site with AI](https://adimalka.com/build-website-with-ai), and [why
every site from the same builder looks the
same](https://adimalka.com/design-language-for-business-site).

Work with me: **[adimalka.com](https://adimalka.com)** ·
[LinkedIn](https://linkedin.com/in/Adimalka)
