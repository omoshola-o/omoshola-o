# Hi, I'm Omoshola 👋

**Building domain-specific AI models and the agentic infrastructure they run on.**

I work at the intersection of agentic systems, financial AI, and regulatory governance — where the gap between what AI can do and what institutions can trust is still wide open. I build AI systems that are architecturally precise, auditable, and honest about uncertainty.

Right now I'm fine-tuning a family of specialist models — **Solen** (supply chain), **Verac** (finance / settlement), **Axiom** (financial markets) — on top of the open agentic infrastructure that runs them. Generalist models are wide, not deep. A fine-tuned specialist trained to *reason* like a domain expert beats a generalist on the work that actually matters in regulated industries.

Published research: 100+ citations across ethical AI in financial decisioning, credit risk modeling, supply chain finance, and systemic risk.

**→ [omoshola.me](https://omoshola.me)**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### High-Level System Design

- 🏗️ I design complex AI systems as composed layers: data contracts, model services, reasoning engines, policy controls, and observable execution paths.
- 🔁 I prioritize architecture-level guarantees: traceability, determinism where required, graceful degradation, and explicit failure boundaries.
- 🧭 I treat governance as a system primitive, not an afterthought: explainability, audit logs, access control, and policy enforcement are built into core workflows.
- ⚙️ I enjoy hard systems problems at scale: multi-agent orchestration, graph-native memory, temporal reasoning, and reliability under real-world constraints.

---

### Current Projects

- 🧬 **agentralabs-models** — Domain-specific model training pipeline. Fine-tuning Gemma 4 to think like world-class domain experts, not generalists. Reasoning-first training across six categories that teach *how* experts think, not just what they know. Quality-scored data (4+/5 on reasoning depth, domain accuracy, calibration, practical value) and failure-pattern training on expert mistakes and corrections.
  - **Solen** — Supply Chain Management *(training)*
  - **Verac** — Finance / Settlement *(pipeline ready)*
  - **Axiom** — Financial Markets *(pipeline ready)*
- 🦀 **Nexus** — Supply chain intelligence platform in Rust. Treats demand, lead times, and supplier reliability as probability distributions. Monte Carlo simulation, temporal graph kernel, agentic recommendations a procurement team can audit. *(Powered by Solen.)*
- 💳 **FyxCred** — Credit intelligence built on behavioral cashflow data, not bureau scores. Three scores — financial health, income stability, financial resilience — with a consent-first data layer and bias transparency framework.
- 🧱 **[ZEX](https://github.com/zexrail/workspace-main)** — Multi-product workspace and execution layer coordinating core platform workflows across the ZEX portfolio.
- ✅ **[Verity](https://github.com/zexrail/verity-main)** — Verity backend implementation for truth-state validation and system-of-record outcomes.
- 🚆 **[ZEXRail](https://github.com/zexrail/zexrail-main)** — ZexRail backend implementation for rail operations and domain workflow orchestration. *(Powered by Verac.)*
- 💸 **[ZEXPay](https://github.com/zexrail/zexpay-main)** — ZexPay backend product workflow, integrated to create Verity proposals and consume Verity outcomes.
- 🧠 **[AgenticMemory](https://github.com/agentralabs/agentic-memory)** — Persistent memory for AI agents. A binary graph format that stores facts, decisions, corrections, and reasoning chains with semantic edge types.
- 👁️ **[AgenticVision](https://github.com/agentralabs/agentic-vision)** — Persistent visual memory for AI agents with embeddings, similarity search, and visual diff.
- 🧩 **[AgenticCodebase](https://github.com/agentralabs/agentic-codebase)** — Semantic code intelligence for concept mapping, grounding, and impact analysis.
- 🪪 **[AgenticIdentity](https://github.com/agentralabs/agentic-identity)** — Cryptographic identity, trust delegation, and signed action receipts for agents.
- ⏱️ **[AgenticTime](https://github.com/agentralabs/agentic-time)** — Temporal reasoning for schedules, deadlines, decay models, and sequence-aware context.
- 📜 **[AgenticContract](https://github.com/agentralabs/agentic-contract)** — Policy contracts and governance controls for obligations, approvals, and violations.
- 📡 **[AgenticComm](https://github.com/agentralabs/agentic-comm)** — Structured communication layer for channels, pub/sub routing, and agent coordination.

### Applied AI Impact (Selected)

- 🏦 **Explainable credit risk intelligence** — Architected an explainable ML credit risk pipeline for 200,000+ applications using ensemble modeling + real-time macroeconomic feature integration, with transparent reasoning outputs for underwriting; reduced default rates by 15% while expanding access to underserved populations.
- 🔐 **Privacy-preserving synthetic data** — Built a synthetic data generation stack combining Gaussian Copula and GAN-based synthesis for secure AI model development, achieving full anonymization with regulatory alignment while preserving statistical utility for downstream risk prediction.
- 📦 **Supply chain resilience modeling** — Developed forecasting and risk pipelines using ARIMA, neural time-series models, and ML supplier-risk scoring to detect disruptions early; reduced stockouts by 22% and drove $2M in cost savings via model-informed operations.

### Research & Explainable AI

- 🔬 **[Explainable Credit Intelligence](https://github.com/omoshola-o/explainable-credit-intelligence)** — SHAP-based interpretable risk scoring (CrossSHAP methodology)
- 🌐 **[Network Analysis — Supply Chain](https://github.com/omoshola-o/network_analysis_supply_chain)** — Systemic risk assessment in supply chains
- 🏦 **[Credit Risk Creditum](https://github.com/omoshola-o/credit-risk-creditum)** — Credit risk modeling and analysis
- 📊 **[RiskX](https://github.com/omoshola-o/riskx)** — Risk analytics engine
- 📄 **[AgenticMemory Paper I](https://github.com/agentralabs/agentic-memory/blob/main/paper/paper-i-format/agenticmemory-paper.pdf)** — Binary format and memory substrate design
- 📄 **[AgenticMemory Paper II](https://github.com/agentralabs/agentic-memory/blob/main/paper/paper-ii-query-expansion/agenticmemory-query-expansion.pdf)** — Query expansion and retrieval strategy
- 📄 **[AgenticMemory Paper III](https://github.com/agentralabs/agentic-memory/blob/main/paper/paper-iii-mcp-server/agentic-memory-mcp-paper.pdf)** — MCP server architecture and tooling
- 📄 **[AgenticVision Paper I](https://github.com/agentralabs/agentic-vision/blob/main/paper/paper-i-cortex/cortex-paper.pdf)** — Visual/web graph representation and reasoning
- 📄 **[AgenticVision Paper II](https://github.com/agentralabs/agentic-vision/blob/main/paper/paper-ii-agentic-vision-mcp/agentic-vision-mcp-paper.pdf)** — Vision MCP server design
- 📄 **[AgenticCodebase Paper](https://github.com/agentralabs/agentic-codebase/blob/main/paper/paper-i-semantic-compiler/agenticcodebase-paper.pdf)** — Semantic compiler and code intelligence architecture
- 📄 **[AgenticIdentity Paper](https://github.com/agentralabs/agentic-identity/blob/main/paper/paper-i-trust-anchor/agenticidentity-paper.pdf)** — Trust anchors, identity proofs, and receipt model
- 📄 **[AgenticTime Paper](https://github.com/agentralabs/agentic-time/blob/main/paper/paper-i-temporal-format/agentictime-paper.pdf)** — Temporal format and reasoning model
- 📄 **[AgenticContract Paper](https://github.com/agentralabs/agentic-contract/blob/main/paper/paper-i-policy-engine/agenticcontract-paper.pdf)** — Policy engine and governance constraints
- 📄 **[AgenticComm Paper](https://github.com/agentralabs/agentic-comm/blob/main/paper/paper-i-agentic-communication/paper.pdf)** — Agent communication runtime and protocol design
- 📄 **IEEE Academic Reviewer** — Peer reviewer for ICAD 2025
- 📐 **IEEE Standards Development** — AI ethics, cybersecurity, financial LLM requirements, supply chain security

### Leadership in AI Governance & Ethics

- 🏅 **IEEE Senior Member, 2025** — Elevated in recognition of significant contributions to the profession; eligible for executive volunteer positions and review panel service. Active memberships: IEEE Computational Intelligence Society, IEEE Consumer Technology Society, IEEE Technology and Engineering Management Society, IEEE Young Professionals.
- 🎯 **Ethics and Conference Reviewing** — NeurIPS 2025 (Datasets & Benchmarks), DeepLearningIndaba 2025, IEEE ICMI 2026 (King Faisal University), IEOM 2025 World Congress (University of Windsor), IEEE IATMSI, and 2025 International Conference on Signal Processing, Computation, Electronics, Power and Telecommunication.
- ⚖️ **Judging and Evaluation** — TrackShift Innovation Challenge 2025 (Mphasis F1 Foundation x MoneyGram Haas F1 Team), HackNC 2025 (UNC Chapel Hill), ASA Statistics Project Competition (Grades 7-12; 30+ projects), and ASA USCLAP.
- 🧪 **Journal Peer Review** — Journal of Data Analysis and Information Processing (JDAIP), including LLM-powered enterprise intelligence, healthcare big data, and cloud optimization work.
- 🤝 **Mentorship** — SciPy Conference 2025 Mentorship Program and Nova Talent Elite Mentorship Program, supporting emerging and senior professionals in ethical AI, financial AI, and supply chain analytics.

### Policy Engagement & Government Initiatives

- 🏛️ **OSTP Federal AI Policy Contributor (2025)** — Submitted technical recommendations on AI regulatory reform to address SR 11-7/SR 23-4 barriers to explainable financial AI, including SHAP/LIME recognition, federal data API clarification, and interagency coordination; quantified a 10-15% potential credit-loss reduction impact across the $18.04T household debt market. ([Notice 90 FR 46422](https://www.federalregister.gov/documents/2025/09/26/2025-18737/notice-of-request-for-information-regulatory-reform-on-artificial-intelligence) • [Docket OSTP-TECH-2025-0067](https://www.regulations.gov/docket/OSTP-TECH-2025-0067) • [Submission](https://www.regulations.gov/document/ITA-2025-0070-0001))
- 🌐 **U.S. Commerce Federal AI Export Strategy Contributor (2025)** — Submitted strategy guidance for the American AI Exports Program focused on compliance-native, explainable, and secure AI exports (Basel III/IV, GDPR alignment, SHAP/LIME, IEEE harmonization), with emphasis on financial resilience and allied infrastructure development. ([Notice 90 FR 48726](https://www.federalregister.gov/documents/2025/10/28/2025-19674/american-ai-exports-program) • [Docket ITA-2025-0070](https://www.regulations.gov/docket/ITA-2025-0070) • [Submission](https://www.regulations.gov/document/ITA-2025-0070-0021))

---

### What I'm Doing

- 🧬 **Specialist model family (Solen / Verac / Axiom)** — Fine-tuning Gemma 4 into reasoning-first domain experts for supply chain, settlement, and financial markets. The thesis: in regulated industries, depth beats breadth, and a model trained to *reason* like a specialist outperforms a generalist on the work that actually matters.
- 🦀 **Nexus** — Shipping a supply chain OS in Rust with probabilistic planning, simulation-first decision support, and auditable agent recommendations.
- 💳 **FyxCred** — Building cashflow-native credit intelligence for credit-invisible populations with explainable scoring, policy-aware decisions, and governance-ready outputs.
- 🧠 **Agentra Sisters** — Advancing MCP-native, artifact-portable infrastructure across graph memory, multimodal vision, semantic code intelligence, identity, time, policy, and communication.
- 🧪 **Applied AI R&D** — Developing explainability, uncertainty-aware modeling, and privacy-preserving data methods for regulated production systems.
- 📝 **Research Service** — Reviewing AI and cybersecurity research through IEEE and related scholarly programs.

---

### What I'm Thinking About

- How to engineer **trustworthy agent systems over time**, not just at launch.
- How to operationalize SHAP/LIME-style explainability so adverse-action reasons satisfy **ECOA/FCRA** requirements in real workflows.
- How to build credit models that expand access for people historically excluded by formal scoring systems.
- How to combine uncertainty quantification, calibration, and drift monitoring into continuous model governance.
- What memory, identity, policy, and reasoning primitives are required before agents can safely operate in regulated domains.
- How to use privacy-preserving synthetic data to balance data utility, security, and compliance.
- How African knowledge systems can inform modern computation and AI system design.

---

### Technical Focus

- **Modeling:** explainable ML, ensemble risk models, time-series forecasting (ARIMA + neural), supplier-risk scoring.
- **AI Safety & Governance:** model transparency, adverse-action traceability, policy-aware decision systems, regulatory-compliant AI deployment.
- **Data & Privacy:** synthetic data generation (Gaussian Copula + GAN), anonymization, utility-preserving data pipelines.
- **Agent Infrastructure:** graph-native memory, multimodal retrieval, identity and trust primitives, temporal reasoning, contract-constrained actions.

---

### GitHub Activity

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=omoshola-o&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" />
</p>
<p>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=omoshola-o&hide_border=true" alt="GitHub Streak" />
</p>
<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=omoshola-o&layout=compact&hide_border=true" alt="Top Languages" />
</p>

### Commit Map

<p>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=omoshola-o&bg_color=ffffff&color=111111&line=0a66c2&point=111111&area=true&hide_border=true" alt="GitHub Commit Activity Graph" />
</p>

---

### Connect

[![Website](https://img.shields.io/badge/omoshola.me-000000?style=flat-square&logo=astro&logoColor=white)](https://omoshola.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/omosholaowolabi)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/HowolarbyM)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:owolabi.omoshola@outlook.com)
