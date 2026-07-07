# Farhan Almutairi

**AI Engineer & Software Builder** — Self-Hosted AI & Automation Systems
Founder @ CarbonFlow · Security & Bug Bounty · Al Majma'ah, Saudi Arabia

I build **local-first (on-premise) AI infrastructure**, autonomous-agent governance, and
cybersecurity automation — production systems that run entirely on owned hardware.

🌐 [carbonflows.store](https://carbonflows.store) · 💼 [linkedin.com/in/carbonflows](https://linkedin.com/in/carbonflows) · ✉️ far7an.o88@gmail.com

---

## Local-First AI Security & Automation Suite

A suite of **22 enterprise microservices** (Python, standard-library only) — each ships a CLI,
a local HTTP service (health / metrics / version), signed audit trails, and real benchmarks.
**353 automated tests passing.**
*Source repositories are private — available for review on request.*

### 🛡️ AI Security & Agent Governance
- **almunaa** — Agent immune system: prompt-injection & tool-abuse defense across the full agent lifecycle. Hybrid detector **F1 98%** on a 15.9k-sample dataset.
- **aegis** — Verifiable agent action-gate: executes only allow-listed commands, logged to an **Ed25519-signed hash-chain ledger**. F1 92%, p99 13.8 ms over 47k decisions.
- **almeezan** — Independent verifier ("judge") for AI outputs (evidence / PII / policy) → PASS / REVIEW / BLOCK with a signed audit trail.
- **alwaseet** — Enterprise AI gateway (DLP): sanitizes PII, API and payment keys before requests reach cloud AI. **0 leaks over 47k checks**.
- **almuwajjih** — Sovereign local/cloud router: sensitivity-aware routing with **zero** sensitive-data leakage to the cloud.
- **alsiyada** — AI compliance auditor: evaluates a platform manifest (data classification, region, PII, audit log) → PASS / REVIEW / BLOCK.

### 🔎 Security Tooling
- **kashif** — Local SAST scanner for source & binaries: AST analysis + CWE mapping, validated against **12k NVD CVEs**.
- **alain_alsahira** — Lightweight runtime guard (EDR): Sigma / YARA-style rules → OK / INVESTIGATE / ISOLATE with remediation.
- **aldir_almozza** — Distributed threat-defense: signal fingerprinting + severity/consensus blocklist.
- **alqofl** — Serverless Ed25519 software licensing: offline verify + device fingerprint. 12k-license benchmark, **705/705 tamper attempts detected**.

### 🤖 AI Systems & Automation
- **alsirb** — Local multi-agent software factory: builds a tested Python project from a single brief. F1 96%.
- **aldhakira** — Local "second brain" RAG: secret-redacting ingest + dependency-free BM25 retrieval. **Recall@5 98.6%**.
- **alsada** — Generative Engine Optimization (GEO): measure and improve how AI engines (ChatGPT / Gemini / Perplexity) describe a brand.
- **alkhaliya** — Local n8n-style automation engine: auditable JSON workflow runs.
- **alnedd** — Business-OS control plane: service registry, health dashboard, work-order routing.
- **almuallim** — Local Arabic teaching engine: AST code analysis + NVD/CVE security lessons.
- **alnabd** — Content-reception predictor: local Naive Bayes scoring with rewrite suggestions.

### 🛒 Business Automation
- **almandoub** — Local WhatsApp / Telegram support agent: PII-safe intent routing (**99.8% accuracy**).
- **almatjar_althaki** — Store-in-a-box core: catalog, recommendations, draft orders (no real payments).
- **almasna_altaswiqi** — Marketing pilot: extracts SEO / content briefs from large corpora.
- **alharis_alsahabi** — SRE advisor: reads service metrics → OK / WARN / INCIDENT with remediation.
- **alshabah** — Safe web-action planner: policy-checked browser / CDP dry-run steps.

---

## Selected Platforms
- **CarbonFlow** — live AI-automation platform on a self-hosted edge server (Alpine Linux, 17 Docker containers) with a Cloudflare Workers site.
- **ZEED** — self-hosted RAG system: 781k-vector Qdrant knowledge base, three local LLMs served on a single consumer GPU.
- **GrowBox Pro** — desktop social-analytics application (Tauri 2 + Rust + SvelteKit 5) with offline Ed25519 licensing.

## Tech
`Python` · `Rust` · `Node.js / TypeScript` · `Kotlin` · `Docker` · `Linux` · `Qdrant` · `Ollama` · `Cloudflare Workers` · `FastAPI` · `Tauri` · `SvelteKit`
