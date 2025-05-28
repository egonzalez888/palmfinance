# Palm Finance

**Instant, Sub-1% Global Money Rail** [cite: 50]

---

**Project Status:** Planning & Pre-Development (As of May 2025)

This repository is for the upcoming Palm Finance project. Currently, we are in the planning and architectural design phase. Code development has not yet commenced. This README outlines our vision, the problems we aim to solve, and our proposed solution.

---

## The Problem We're Solving

Palm Finance is being engineered to address the significant inefficiencies in today's global payment infrastructure[cite: 51]. Individuals, SMEs, and platforms currently face:
* **Slow settlement times:** Cross-border transfers often take 1–3 days[cite: 52].
* **High and opaque fees:** Average costs can range from 6-8%, with unclear FX spreads[cite: 52].
* **Barriers to adopting modern rails:** Smaller banks and fintechs often lack the cryptographic custody expertise, specialized talent, and audit resources needed to leverage stablecoin technology directly[cite: 53].
* **Manual and capital-intensive processes:** Operations like marketplace escrows and global payroll remain cumbersome and error-prone[cite: 54].

## Our Vision: The Palm Finance Solution

Our core mission is to build Palm Finance as a solution that will:
> Convert every inbound USD into USDC the millisecond it arrives, move it over the Circle Payments Network (CPN) in real time, then redeem it into local fiat—handing any sponsor-bank client a 60-second, sub-1% global payment rail via a single, elegant API. [cite: 55]

We aim to make international payments dramatically faster, cheaper, and more accessible, especially for institutions that currently find it difficult to innovate in this space.

## Core Principles & Planned Features

Palm Finance will be built upon the following guiding philosophies:

* **Abstraction over Reinvention:** Hide all cryptocurrency and blockchain complexity behind familiar, developer-friendly REST API and Webhook surfaces[cite: 67]. Partners will interact with simple payment primitives, not raw blockchain protocols[cite: 67].
* **Compliance-First Design:** Embed SOC-2 readiness, automated Travel Rule solutions, and robust on-chain AML capabilities at the architectural level[cite: 68].
* **Modular Corridor Expansion:** Perfect a single, high-impact corridor (e.g., U.S. → Mexico) as a template for rapid expansion[cite: 69].
* **Developer-Centric Go-To-Market (GTM):** Enable "deployment in <15 minutes" for sandbox testing via a white-label SDK, CLI tools, and comprehensive documentation[cite: 70].
* **Bank-Agnostic Core:** Architected to integrate with any willing and capable sponsor bank, ensuring resilience and choice[cite: 71].
* **Speed & Efficiency as a Product:** Leverage stablecoins (USDC) and real-time payment networks (CPN, RTP, FedNow, SPEI) to deliver near-instant settlement as a core feature[cite: 73].

## Target Audience (Planned)

We envision Palm Finance serving:

* **Primary:** U.S. Community Banks & Credit Unions[cite: 98].
* **Secondary:** LatAm-centric (and other emerging market) Neobanks & Payment Apps[cite: 99].
* **Tertiary (Phase 2+):** Freelance/Gig Platforms and Marketplace Operators[cite: 100].

## Anticipated Technology Stack

While subject to evolution, our initial technical considerations include:

* **Core Infrastructure:** Circle Payments Network (CPN)[cite: 56], Circle Programmable Wallets[cite: 57].
* **Backend:** Go / TypeScript (indicated in resource planning [cite: 121]).
* **Cloud Platform:** GCP Cloud Run, Pub/Sub (mentioned for MVP [cite: 76]).
* **Database:** Postgres (for double-entry ledger PoC [cite: 76]).
* **Compliance Integrations:** Sumsub (KYC), TRM Labs (AML)[cite: 76], Notabene (Travel Rule)[cite: 68].
* **FX Oracles:** Chainlink (for FX oracle [cite: 76]).
* **Infrastructure as Code:** Terraform[cite: 76].

## High-Level Roadmap Overview (See Master Blueprint for Details)

Our development will follow a phased approach[cite: 76]:

1.  **Phase 0 (Foundation):** Validate core tech stack & compliance integrations (Circle Wallet, Ledger PoC, KYC/AML APIs)[cite: 76].
2.  **Phase 1 (Corridor MVP):** Establish a live U.S. → Mexico rail in a sandbox environment (ACH/RTP on-ramp, SPEI off-ramp, Demo App)[cite: 76].
3.  **Phase 2 (Pilot & Grant Application):** Prove MVP with capped live volume; secure initial partnerships & funding[cite: 76].
4.  **Further Phases:** Partner On-Ramp & Initial Scale, Revenue Scale & Feature Expansion, Resilience & Long-Term Moat development[cite: 76].


## How to Get Involved (Future)

Once development is underway, we will provide guidelines here on how to contribute, report issues, or suggest features.
