<div align="center">

<img src="assets/gz-logo.png" alt="GZ" width="140" />

# Abd Alrahaman Mohamed

**Full-Stack Engineer  ·  AI Systems  ·  Applied Security Research**

Alexandria, Egypt  ·  Remote-first

</div>

---

![Impact](https://img.shields.io/badge/OCTOBER%202026%20HIGHLIGHTS-D4AF37?style=for-the-badge&labelColor=0d0d0d)

**10 OSS organisations with active public standing · 2 PRs merged · 2 security advisories accepted**

🏆 Formalized **APDS — Asymmetric Patch Detection for Symmetric APIs** (new vulnerability-discovery methodology). First application: an un-patched symmetric sibling of CVE-2024-40658, **byte-identical across 6 AOSP branches for 25 months**. Submitted to Google ASR (**CVSS 10.0 Critical** · in panel review). Reference implementation open-sourced at **[apds-hunt](https://github.com/61465/apds-hunt)** within 24 h of submission.

**Merged this cycle**
- ✅ **PostHog #5083** — opt-in WebView bot detection
- ✅ **Supabase storage #1500** — TUS `X-Supabase-Object-Id` response header (merged by @ferhatelmas)

**Open PRs across the stack**
- 🔧 **Drizzle ORM #6497** — `useLiveQuery` on `expo-sqlite` now subscribes to joined tables (new `SQLiteRelationalQuery.getReferencedTables()`, cycle-guarded)
- 🔧 **Sentry-JS #25348** — Nuxt pages-router client-plugin unit tests (5 code paths × 13 cases, pre-blessed by MEMBER @JPeer264)
- 🔧 **SvelteKit #17432** — `adapter-cloudflare` swaps the Cloudflare platform proxy in place when `wrangler.toml` changes (Vercel bot: *"the bug is fixed"*)
- 🔧 **Sentry Relay #6508** — derived trace context prefers the DSC `trace_id` (84/84 local tests)
- 🔧 **Inngest #5004** — single shared TracerProvider via `BatchSpanProcessor`, stops a per-run `OtelTracerProvider` leak
- 🔧 **Supabase storage #1488** — auto-select URL-signing JWK from `JWT_JWKS`
- 🔧 **Supabase storage #1499** — magic-byte MIME validator, 61 tests + 2 security-review iterations with `depthfirst-app`
- 🔧 **Supabase auth #2863** — preserve OAuth 2.1 client sessions during MFA step-up
- 🔧 **PostHog #5244** — rrweb `MutationBuffer.processBufferedMutations` O(n²) → O(n), 500-row shadow-DOM regression

**Design proposals accepted-for-review**
- 📝 **Prisma ORM #20678** (v7 maintenance line) — ALS-based transparent transaction propagation for `$extends`, 8-case failure matrix
- 📝 **Node.js core #55422** (v22.x / v24.x LTS) — LTS-only fix for `Buffer.copy` silent corruption past 4 GiB
- 📝 **Nitro #4471** (v3 line) — conditions-aware `externals.ts` resolve so `@sentry/tanstackstart-react` doesn't crash the Rollup graph

**Security advisories**
- 📝 **Trigger.dev GHSA-65rr-73jq-6qhf accepted** (CVSS 9.6)
- 📝 **Documenso GHSA-2rp7-mrh6-v9m2 in triage** (CVSS 7.6, first-ever GHSA on the repo)

---

![Impact](https://img.shields.io/badge/SELECTED%20IMPACT-D4AF37?style=for-the-badge&labelColor=0d0d0d)

- **Top 16% (325 / 2,076 teams)** on Kaggle *AI Agent Security: Multi-Step Tool Attacks* — verified score **83.745**
- Reduced WhatsApp ban rate from Meta's 0.5% baseline to **0.1%** (5× improvement) via a 13-layer defense stack in production SaaS
- **90.6% adversarial containment at 5.9% FPR** on 8,000 seeded sessions — [Ariadne](https://ssrn.com/abstract=6870178) framework (SSRN preprint)
- Hospital-ready radiology AI: **69 s per 24-slice CT at 92% confidence** — midcine v3
- Shipped **134-agent NEXUS catalog** with MCP orchestration + a five-verifier grounding gate that removed 724 unsupported cyber claims across 770 production invocations

---

![Research](https://img.shields.io/badge/PUBLISHED%20RESEARCH%20%26%20METHODOLOGY-D4AF37?style=for-the-badge&labelColor=0d0d0d)

- **[apds-hunt](https://github.com/61465/apds-hunt)** — reference tool for the APDS methodology (XOR Rule theorem + 6-step algorithm). MIT. Oct 2026.
- **[Ariadne: Adaptive, Human-in-the-Loop Defense for AI Agents](https://ssrn.com/abstract=6870178)**  ·  SSRN 6870178  ·  Jun 2026
- **[Oblivion Gate: Zero-Trace Fragmentation in Distributed Data Architectures](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6602478)**  ·  SSRN 6602478  ·  May 2026

---

![Stack](https://img.shields.io/badge/TECH%20STACK-D4AF37?style=for-the-badge&labelColor=0d0d0d)

**Languages** · Python · TypeScript · JavaScript · Rust · Dart · SQL · LaTeX
**AI / ML** · PyTorch · Transformers · LoRA · DPO · Ollama · Claude API · MCP · RAG · LangGraph · multi-agent orchestration
**Web / Backend** · Next.js 15 · React · NestJS · FastAPI · Node.js · Express · Prisma · PWA · Turborepo · pnpm workspaces
**Healthcare** · DICOM · pynetdicom · highdicom · OHIF v3 · Cornerstone3D · FHIR R4 · HL7
**Cybersecurity** · WebAuthn/Passkeys · OAuth2 · SIEM · SOAR · EDR · YARA · pen testing (TCM-certified) · adversarial-AI defense · responsible disclosure (CVSS 3.1)
**DevOps** · Docker · Kubernetes · Firecracker · gVisor · Tailscale mesh · Cloudflare Tunnel · self-hosted PaaS (Ollama + Vaultwarden + Gitea + Grafana)

---

![Elsewhere](https://img.shields.io/badge/ELSEWHERE-D4AF37?style=for-the-badge&labelColor=0d0d0d)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdalrahman--gz-D4AF37?style=for-the-badge&labelColor=0d0d0d&logo=linkedin&logoColor=D4AF37)](https://www.linkedin.com/in/abdalrahman-gz/)
[![Kaggle](https://img.shields.io/badge/Kaggle-abdalrahmanmohamed3-D4AF37?style=for-the-badge&labelColor=0d0d0d&logo=kaggle&logoColor=D4AF37)](https://www.kaggle.com/abdalrahmanmohamed3)
[![SSRN](https://img.shields.io/badge/SSRN-Author%2011211189-D4AF37?style=for-the-badge&labelColor=0d0d0d)](https://ssrn.com/author=11211189)
[![Email](https://img.shields.io/badge/Email-abdarahman10555%40gmail.com-D4AF37?style=for-the-badge&labelColor=0d0d0d&logo=gmail&logoColor=D4AF37)](mailto:abdarahman10555@gmail.com)

---

![LiveProducts](https://img.shields.io/badge/LIVE%20PRODUCTS-D4AF37?style=for-the-badge&labelColor=0d0d0d)

- **MEDNEXA** (Egyptian healthcare integration platform — HIS × LIS × PACS, HL7v2 + FHIR R4 + DICOM, PDPC-aligned audit) — [github.com/61465/MEDNEXA](https://github.com/61465/MEDNEXA)
- **Thawani** (WhatsApp Commerce SaaS, live paid tenants) — [thawani.cc](https://thawani.cc) · backup landing on GitHub Pages if the domain is down: [61465.github.io/thawanidemo](https://61465.github.io/thawanidemo/) · source: [github.com/61465/Thawani](https://github.com/61465/Thawani)
- **apds-hunt v0.1** (public reference tool for the APDS vulnerability-discovery methodology) — [github.com/61465/apds-hunt](https://github.com/61465/apds-hunt)
- **Nexus Zone portfolio companion** — [61465.github.io/Nexus_Zone_Portfolio_Companion](https://61465.github.io/Nexus_Zone_Portfolio_Companion/) · source: [github.com/61465/Nexus_Zone_Portfolio_Companion](https://github.com/61465/Nexus_Zone_Portfolio_Companion)

---

![Pinned](https://img.shields.io/badge/PINNED%20REPOSITORIES%20BELOW-D4AF37?style=for-the-badge&labelColor=0d0d0d)

*Selected showcases from the ecosystem. Full source code, datasets, and proprietary models remain private for commercial and research reasons.*
