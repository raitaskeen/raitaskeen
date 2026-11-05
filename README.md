<div align="center">

# Taskeen Haider

**Founder, LegacyExodus · Full-Stack and Systems Engineer**

Lahore, Pakistan · Software modernisation · Developer tooling · Deterministic analysis

[![Website](https://img.shields.io/badge/legacyexodus.tech-B24418?style=for-the-badge&logoColor=white)](https://legacyexodus.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raitaskeen)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:founder@legacyexodus.tech)

</div>

---

## About

I build software that makes legacy systems understandable and safe to change. I founded **LegacyExodus**, a migration platform that analyses existing codebases deterministically and produces source-traceable evidence before any change is made. My work also covers full-stack web applications, commerce platforms, and the infrastructure that runs them on Cloudflare.

**How I work**
- **Deterministic first.** Correctness comes from analysis and tests. AI supports reasoning, orchestration and summarisation, but it is never the source of truth.
- **Explicit uncertainty.** Unsupported behaviour is reported, never silently dropped.
- **Verified delivery.** Every change ships with tests, a reviewed pull request, and passing CI.

---

## LegacyExodus: roadmap

LegacyExodus is built in stages, starting with the languages most in demand for modernisation.

| Product | First version | First revenue |
|---|---|---|
| Safety net (JavaScript / TypeScript) | ~3 months | ~4–5 months |
| Quantum-safe discovery | ~3 months after LegacyExodus | ~4–5 months after that |
| Quantum-safe migration (complete) | ~6–9 months | 2027–2028 |

**Language order:** JavaScript, TypeScript, TSX, JSX and Node.js first; then PHP, Ruby on Rails and Java.

---

## Projects

### LegacyExodus
**Status:** Private platform in active development · [legacyexodus.tech](https://legacyexodus.tech)

A deterministic repository-intelligence and static-analysis engine for JavaScript and TypeScript. It inventories a repository, parses source with Babel, and builds symbol, dependency, control-flow (CFG) and data-flow (DFG) artifacts, then publishes validated JSON projections with manifest hashes.

- Same input, same output: results are reproducible and locale-independent.
- Evidence over guesses: unresolved or unsupported constructs stay visible in the output.
- Run isolation and snapshot reuse, backed by SQLite with integrity-checked artifacts.
- The planned pipeline has four stages: discovery, understanding, transformation and validation. Discovery and understanding are implemented; transformation and migration planning are not yet built.

**Stack:** TypeScript · Bun · Babel · SQLite

### LegacyExodus Analysis Sample
**Status:** Public sample · [GitHub](https://github.com/LegacyExodus/legacyexodus-analysis-sample)

A sanitised, public sample of the engine's core. It builds control-flow graphs from the AST, runs reachability analysis, validates structural invariants, and reports unsupported semantics explicitly. It includes unit tests and a visual CFG demo.

```bash
bun run analyze sample.ts     # analyse the sample
bun run demo                  # open the visual CFG at http://localhost:3000
```

**Stack:** TypeScript · Bun · Biome

### Raavi Volt (amirstore.tech)
**Status:** Live · [amirstore.tech](https://amirstore.tech) · [Source](https://github.com/raitaskeen/raavi-volt)

An online store for Geepas and other electrical appliances, serving Lahore and Pakistan. The name combines the Ravi river of Lahore with "volt".

- Storefront with search, filters, live deals, and cart and checkout.
- Manual bank and Raast QR payments, with a payment-proof upload and order tracking.
- Admin dashboard for products, orders, payment verification and low-stock alerts.
- Optional WhatsApp order updates at each stage, and a two-way assistant for order questions.
- Installable as an app (PWA), with edge caching on Cloudflare. Every order is re-priced from the database on the server.

**Stack:** Next.js 16 · React 19 · TypeScript · Tailwind CSS v4 · shadcn/ui · Cloudflare Workers · D1

### Annemarie-Schimmel-Haus Website
**Status:** Live · [Public site](https://annemarie-schimmel.raitaskeen.workers.dev/en) · [Full application](https://github.com/raitaskeen/annemarie-schimmel-haus)

A bilingual (English and German) website and staff workspace for a German cultural centre in Lahore.

- Courses and batches, placement tests, and events with registration.
- Online course applications in five steps, with documents and a reference number.
- Schimmel, a guide assistant that answers from the centre's own course information.
- Staff workspace with roles, applications, payments, messages and an audit trail of every staff action.
- A static public copy is also published, which runs without a server.

**Stack:** Next.js 16 · React 19 · TypeScript · PostgreSQL 17 · Drizzle ORM · Cloudflare Workers (OpenNext) · Hyperdrive

### ASH Digital Platform
**Status:** Governed prototype with synthetic data · [Source](https://github.com/raitaskeen/ash-digital-platform)

The next-generation digital platform concept for the same centre: public web, institutional operations, teacher and student experiences, and verifiable credentials. It is built as one platform with role-based access for administrators, teachers and students, and it is developed against documented milestones and acceptance gates. Hosted production deployment is not yet approved.

**Stack:** Next.js · React · TypeScript · Tailwind CSS · Bun · Hono · PostgreSQL · Supabase Auth

### Cine Vault
**Status:** Full-stack portfolio project · [Client](https://github.com/raitaskeen/cine-vault-web) · [API](https://github.com/raitaskeen/cine-vault-api)

A movie discovery platform with real-time search, dynamic filters and a responsive interface. The client and the REST API live in separate repositories.

**Stack:** React 19 · Vite · Tailwind CSS · Node.js · Express · MongoDB

### AxiomExodus
**Status:** In development

Rust-native, local-first infrastructure for deterministic data processing and verification. It keeps language-model reasoning bounded, with deterministic compute underneath.

**Stack:** Rust

---

## Open source contributions

- [**freeCodeCamp**](https://github.com/freeCodeCamp/freeCodeCamp): open-source coding curriculum ([PR #69385](https://github.com/freeCodeCamp/freeCodeCamp/pull/69385)).
- [**MDN Web Docs**](https://github.com/mdn): web platform documentation ([PR #281](https://github.com/mdn/translated-content-de/pull/281)).
- [**Kana Dojo**](https://github.com/lingdojo/kana-dojo): Japanese learning platform ([PR #27003](https://github.com/lingdojo/kana-dojo/pull/27003)).

---

## Skills

**Languages and frameworks**

[![Languages](https://skillicons.dev/icons?i=ts,js,rust,nodejs,bun,react,nextjs,express&theme=dark)](https://skillicons.dev)

**Data and infrastructure**

[![Data and infrastructure](https://skillicons.dev/icons?i=postgres,mongodb,mysql,docker,linux,cloudflare&theme=dark)](https://skillicons.dev)

**Tooling**

[![Tooling](https://skillicons.dev/icons?i=git,github,githubactions,vscode,postman&theme=dark)](https://skillicons.dev)

**Areas:** static analysis and program representation (AST, CFG, DFG, IR) · software modernisation and migration · full-stack web applications · commerce and payments · CI/CD and developer tooling · Cloudflare and serverless deployment.

---

## Contact

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:founder@legacyexodus.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raitaskeen)
[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://raitaskeen.me)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/raitaskeen786)
