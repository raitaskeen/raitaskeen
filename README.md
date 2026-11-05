<div align="center">

<img src="assets/banner.svg" alt="Taskeen Haider · Founder, LegacyExodus" width="100%"/>

<br/>

[![Website](https://img.shields.io/badge/legacyexodus.tech-B24418?style=for-the-badge&logoColor=white)](https://legacyexodus.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raitaskeen)
[![Email](https://img.shields.io/badge/Email-1E1E1E?style=for-the-badge&logo=gmail&logoColor=white)](mailto:founder@legacyexodus.tech)
[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://raitaskeen.me)

</div>

---

## ✦ About

I build software that makes legacy systems **understandable and safe to change**. I founded **LegacyExodus**, a migration platform that analyses existing codebases deterministically and produces source-traceable evidence before any change is made. My work spans static analysis, full-stack web applications, commerce platforms and the infrastructure that runs them on Cloudflare.

| Principle | What it means in practice |
|---|---|
| 🔬 **Deterministic first** | Correctness comes from analysis and tests. AI supports reasoning and summarisation, never the source of truth. |
| 🧭 **Explicit uncertainty** | Unsupported behaviour is reported, never silently dropped. |
| ✅ **Verified delivery** | Every change ships with tests, a reviewed pull request and passing CI. |

---

## ◆ The LegacyExodus pipeline

Discovery and understanding are built and tested. Transformation and validation are the next stages.

<div align="center">
<img src="assets/pipeline.svg" alt="LegacyExodus pipeline: discovery and understanding built, transformation and validation planned" width="100%"/>
</div>

---

## ◆ Roadmap

LegacyExodus is built in stages, starting with the languages most in demand for modernisation.

<div align="center">
<img src="assets/roadmap.svg" alt="Roadmap of LegacyExodus products with build times and first revenue" width="100%"/>
</div>

| Product | First version | First revenue |
|---|---|---|
| Safety net (JavaScript / TypeScript) | ~3 months | ~4–5 months |
| Quantum-safe discovery | ~3 months after LegacyExodus | ~4–5 months after that |
| Quantum-safe migration (complete) | ~6–9 months | 2027–2028 |

**Language order:** JavaScript → TypeScript → TSX / JSX → Node.js, then PHP → Ruby on Rails → Java.

---

## ◆ Projects

### 🧬 LegacyExodus
![Status](https://img.shields.io/badge/status-private%20platform-B24418?style=flat-square) [![Website](https://img.shields.io/badge/website-legacyexodus.tech-B24418?style=flat-square)](https://legacyexodus.tech)

A deterministic repository-intelligence and static-analysis engine for JavaScript and TypeScript. It inventories a repository, parses source with Babel, builds symbol, dependency, control-flow (CFG) and data-flow (DFG) artifacts, and publishes validated JSON with manifest hashes.

- **Reproducible:** the same input always produces the same output, independent of locale.
- **Evidence over guesses:** unresolved or unsupported constructs stay visible in the output.
- **Run isolation:** SQLite-backed storage, snapshot reuse and integrity-checked artifacts.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) ![Babel](https://img.shields.io/badge/Babel-F9DC3E?style=flat-square&logo=babel&logoColor=black) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

---

### 🔎 LegacyExodus Analysis Sample
![Status](https://img.shields.io/badge/status-public%20sample-2D5BA8?style=flat-square) [![Repo](https://img.shields.io/badge/github-analysis--sample-181717?style=flat-square&logo=github)](https://github.com/LegacyExodus/legacyexodus-analysis-sample)

A sanitised, public sample of the engine's core: AST-driven control-flow graphs, reachability analysis, structural invariant checks and explicit reporting of unsupported semantics. It includes unit tests and a visual CFG demo.

```bash
bun run analyze sample.ts     # analyse the sample
bun run demo                  # open the visual CFG at http://localhost:3000
```

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) ![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=white)

---

### 🛒 Raavi Volt · amirstore.tech
![Status](https://img.shields.io/badge/status-live-138F5E?style=flat-square) [![Website](https://img.shields.io/badge/website-amirstore.tech-138F5E?style=flat-square)](https://amirstore.tech) [![Repo](https://img.shields.io/badge/github-raavi--volt-181717?style=flat-square&logo=github)](https://github.com/raitaskeen/raavi-volt)

An online store for Geepas and other electrical appliances, serving Lahore and Pakistan. The name combines the Ravi river of Lahore with "volt".

- **Shopping:** search, filters, live deals, cart and checkout.
- **Payments:** manual bank and Raast QR payments, with payment-proof upload and order tracking.
- **Operations:** admin dashboard for products, orders, payment verification and low-stock alerts.
- **Customers:** optional WhatsApp order updates and an installable app (PWA); every order is re-priced from the database on the server.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

### 🏛️ Annemarie-Schimmel-Haus Website
![Status](https://img.shields.io/badge/status-live-138F5E?style=flat-square) [![Website](https://img.shields.io/badge/website-live%20demo-138F5E?style=flat-square)](https://annemarie-schimmel.raitaskeen.workers.dev/en) [![Repo](https://img.shields.io/badge/github-full%20app-181717?style=flat-square&logo=github)](https://github.com/raitaskeen/annemarie-schimmel-haus)

A bilingual (English and German) website and staff workspace for a German cultural centre in Lahore.

- **Learning:** courses and batches, placement tests, events with registration.
- **Applications:** online course applications in five steps, with documents and a reference number.
- **Guide:** Schimmel, an assistant that answers from the centre's own course information.
- **Staff:** roles, applications, payments, messages and an audit trail of every staff action.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

### 🧩 ASH Digital Platform
![Status](https://img.shields.io/badge/status-prototype-8A5300?style=flat-square) [![Repo](https://img.shields.io/badge/github-ash--digital--platform-181717?style=flat-square&logo=github)](https://github.com/raitaskeen/ash-digital-platform)

The next-generation digital platform concept for the same centre: public web, institutional operations, teacher and student experiences, and verifiable credentials. Built as one platform with role-based access for administrators, teachers and students, developed against documented acceptance gates. Hosted production is not yet approved.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

---

### 🎬 Cine Vault
![Status](https://img.shields.io/badge/status-portfolio-5F5F5B?style=flat-square) [![Client](https://img.shields.io/badge/github-client-181717?style=flat-square&logo=github)](https://github.com/raitaskeen/cine-vault-web) [![API](https://img.shields.io/badge/github-api-181717?style=flat-square&logo=github)](https://github.com/raitaskeen/cine-vault-api)

A movie discovery platform with real-time search, dynamic filters and a responsive interface. The client and the REST API live in separate repositories.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

### ⚙️ AxiomExodus
![Status](https://img.shields.io/badge/status-in%20development-5F5F5B?style=flat-square)

Rust-native, local-first infrastructure for deterministic data processing and verification, with language-model reasoning kept bounded and deterministic compute underneath.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

---

## ◆ Open source

| Project | Contribution |
|---|---|
| [freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | Open-source coding curriculum · [PR #69385](https://github.com/freeCodeCamp/freeCodeCamp/pull/69385) |
| [MDN Web Docs](https://github.com/mdn) | Web platform documentation · [PR #281](https://github.com/mdn/translated-content-de/pull/281) |
| [Kana Dojo](https://github.com/lingdojo/kana-dojo) | Japanese learning platform · [PR #27003](https://github.com/lingdojo/kana-dojo/pull/27003) |

---

## ◆ Toolkit

<div align="center">

[![Languages](https://skillicons.dev/icons?i=ts,js,rust,nodejs,bun,react,nextjs,express&theme=dark)](https://skillicons.dev)
[![Data and infrastructure](https://skillicons.dev/icons?i=postgres,mongodb,mysql,docker,linux,cloudflare&theme=dark)](https://skillicons.dev)
[![Tooling](https://skillicons.dev/icons?i=git,github,githubactions,vscode,postman&theme=dark)](https://skillicons.dev)

</div>

**Focus areas:** static analysis and program representation (AST · CFG · DFG · IR) · software modernisation and migration · full-stack web applications · commerce and payments · CI/CD and developer tooling · Cloudflare and serverless deployment.

---

<div align="center">

### Let's talk

[![Email](https://img.shields.io/badge/Email-1E1E1E?style=for-the-badge&logo=gmail&logoColor=white)](mailto:founder@legacyexodus.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raitaskeen)
[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://raitaskeen.me)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/raitaskeen786)

<sub>Built with care in Lahore · legacyexodus.tech</sub>

</div>
