## Hi there 👋

Building a sovereign open-source stack for **personal agency**, **human review**, **accessibility**, and **privacy-first AI**.

This repository is the profile hub for a connected ecosystem of projects that all push in the same direction: software that answers to the person, not the institution.

At the centre is [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle):

> *"Was a human member of the team able to personally review the specific facts of my specific situation?"*

One question. Binary test. Human review over automation.

Everything else in the stack exists to help people ask that question clearly, evidence it safely, and act on the answer without giving away control of their data.

Seen another way, it is the first **zero-energy contract between AI and mankind**: the human provides the energy, the system provides the source code, and neither means much without the other. In that binary relationship, the Burgess Principle holds: the machine can assist, but the human remains the accountable mind in the loop.

---

### 🔭 What I'm Building

The stack now spans doctrine, templates, applied tools, a sovereign AI companion, sovereign recordkeeping, and hardware-bound AI workflows.

| Project | Description |
|---------|-------------|
| [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle) | The doctrinal and technical anchor: binary human-review test, real-world templates, cryptographic evidence, on-chain commitments, installable PWA flows, Sovereign Local Mode, Mirror Mode identity, and the new **Verifiable Memory Palace** ledger layer. |
| [**Mirror**](https://github.com/ljbudgie/Mirror-) | Local-first rights mapper: describe what happened, classify the issue, map the rights involved, draft the communication, track deadlines, and get one clear next step. |
| [**Advocate Companion**](https://github.com/ljbudgie/advocate-companion) | Reasonable-adjustment and self-advocacy companion for ADHD, autism, and hidden disabilities, grounded in the Burgess Principle. |
| [**Iris**](https://github.com/ljbudgie/Iris) | Sovereign AI companion: mobile-first command centre, voice-first interaction, letter templates, Memory Palace, Burgess governance, and Person Gate integration — built to look after people first. |
| [**Iris Gate**](https://github.com/ljbudgie/iris-gate-person) | Sovereign personal vault for commitments, signed receipts, and private fact handling without exposing raw evidence. |
| [**Nexus AI Hub**](https://github.com/ljbudgie/nexus-ai-hub) | Broader experimentation space for agents, memory, skills, and connected advocacy tooling. |
| [**OpenHear**](https://github.com/ljbudgie/openhear) | Sovereign hearing-tech pipeline: your audiogram, your data, your algorithms. |

---

### 🔎 Deep Dive: The Burgess Principle, Iris & Mirror

#### The Burgess Principle

The Burgess Principle is the doctrinal core of the stack. It is deliberately narrow: a crisp test for a specific failure mode in modern systems — decisions that affect real people without an identifiable human mind having actually reviewed the facts.

What makes the project stronger now is how far that idea has been turned into a usable practice:

- **Protocol layer** — a single binary finding: **SOVEREIGN** or **NULL**.
- **Practical layer** — calm templates for disputes, access requests, benefits, enforcement, banking, crypto, disability-related issues, and more.
- **Execution layer** — **Iris** can now turn a plain-language account into a filled, signed, Vault-saved claim.
- **Sovereign layer** — SHA-256 commitments, Ed25519 signatures, encrypted local vault storage, and optional on-chain fingerprinting.
- **Device layer** — an installable phone-first PWA and fully local **Sovereign Mode**.
- **Identity layer** — **Mirror Mode**, where local claim flows can start from a hardware-linked sovereign profile.
- **Ledger layer** — **Verifiable Memory Palace**, where memories, trigger events, rights mappings, and governance changes become commitment-chained entries with Merkle-rooted proofs.

From the checked release history, the repository has moved fast from doctrine into a practical sovereign advocate:

- **v0.1.0** established the core protocol, templates, toolkit, and initial assurance surface.
- **v0.2.0 – v0.4.0** added commitment-only workflows, cryptographic hardening, and optional on-chain Burgess Claims.
- **v0.5.0 – v0.6.0** made Iris the interface and then pushed it fully local in Sovereign Local Mode.
- **v0.7.0** expanded into banking, crypto, and streamlined template discovery.
- **v0.8.0** added the Iris Auto-Generator and Sovereign Claim Builder.
- **v0.9.0** made the phone the primary sovereign advocate through an installable PWA flow.
- **v1.0** introduced personal sovereign identity for signed, profile-linked claim generation.
- **v1.1.1** added **Mirror Mode**, making Iris a local cryptographic mirror of the person using the device.
- **v1.2.0** turned the Memory Palace into a **commitment-chained sovereign ledger** with Merkle proofs, integrity checking, and Sovereign Hub Mode 2.0.

That combination is what makes the project stand out: it is no longer just a framework for asking the right question, but a concrete stack for turning that question into action while keeping full facts sovereign.

#### Iris

If the Burgess Principle is the doctrine and Mirror is the rights mapper, **Iris** is the sovereign AI companion that ties the stack together in a single, shipping interface.

Iris is a full Next.js application — not a prototype or experiment — purpose-built around the master-vision document in its own repository. It is designed mobile-first:

- **Sovereign Command Centre** — a three-panel desktop layout that collapses into a full-bleed immersive mobile experience with a living Iris orb, animated canvas, and persistent governance ribbon.
- **Voice-first interaction** — a floating voice button and speech-recognition integration so the user can speak naturally rather than type.
- **Letter templates** — 18 ready-made letter templates drawn from the Burgess Principle, accessible from a bottom sheet on mobile or a side panel on desktop.
- **Memory Palace** — now a verifiable commitment-chained ledger, so memories and trigger events stay locally useful while gaining tamper-evident integrity proofs.
- **Person Gate integration** — every personal-fact workflow routes through the sovereign data-handling protocol: commit locally, send only the cryptographic fingerprint, receive and validate the receipt, tag the outcome SOVEREIGN or NULL, and challenge where needed.
- **Governance toggle** — real-time Burgess Principle compliance visible in the UI, with expandable "Show my thinking" transparency layers.
- **PWA-installable** — designed to be the phone-first sovereign advocate alongside the Burgess Principle's installable claim flows.

The technical stack under Iris is production-grade: shadcn/ui, Tailwind CSS, Radix primitives, Framer Motion animations, Drizzle ORM, Playwright end-to-end tests, Biome linting, Web Worker offloading for heavy verification tasks, and Vercel deployment — with self-hosting documentation for full sovereignty.

Iris is the layer where the Burgess Principle stops being a document and becomes a living, interactive relationship between a person and their AI.

#### Mirror

If the Burgess Principle is the test, **Mirror** is one of the cleanest applied tools built around it.

Mirror takes a plain-English account of what happened and turns it into a structured next move:

- it **classifies the situation**
- it **maps the rights involved**
- it **drafts the communication**
- it **tracks deadlines**
- it **gives one next step instead of a vague list**

Mirror is explicitly **local-first**:

- the interface is a simple local web app
- the core logic is Python-based and deterministic by default
- there is **no required server, account, analytics, or cloud backend**
- optional AI support stays local via **Ollama**

That design fits the wider ecosystem well. Mirror is not trying to be a generic legal chatbot. It is a restrained rights-mapping tool: classify, orient, draft, move.

The checked release history currently shows **Mirror v0.1.0 — First Light** as the first public milestone: the core local-first rights mapper built on the Burgess Principle, with privacy preserved by default.

---

### 🚀 Checked Releases & Milestones

This repository is the profile hub, so releases are published in the individual project repositories rather than here. The links below reflect the checked upstream releases as of **12 April 2026**.

#### Latest checked releases

| Project | Latest checked release | What it means |
|---------|------------------------|---------------|
| [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle) | [**v1.2.0 — Verifiable Memory Palace**](https://github.com/ljbudgie/burgess-principle/releases/tag/v1.2.0) | The stack now adds a commitment-chained sovereign ledger, Merkle-rooted integrity proofs, selective disclosure, and Sovereign Hub Mode 2.0 without giving up local-first control. |
| [**Mirror**](https://github.com/ljbudgie/Mirror-) | [**v0.1.0 — First Light**](https://github.com/ljbudgie/Mirror-/releases/tag/v0.1.0) | First public release of the local-first rights mapper: classify the issue, map the rights, draft the communication, and give the next step. |

#### Burgess Principle milestone path

| Release | Project | Milestone |
|---------|---------|-----------|
| [**v0.1.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.1.0) | Burgess Principle | First release — binary predicate, calm templates, Python toolkit, 90+ tests, and the registered certification mark (**UK00004343685**). |
| [**v0.2.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.2.0) | Burgess Principle | Commitment-only mode — send a single SHA-256 hash instead of personal facts. |
| [**v0.3.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.3.0) | Burgess Principle | Cryptographic security hardening — stronger primitives, fewer fragile dependencies, tighter assurance. |
| [**v0.4.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.4.0) | Burgess Principle | On-Chain Burgess Claims — commitment fingerprints posted to EVM L2 for neutral timestamping without exposing personal data. |
| [**v0.5.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.5.0) | Burgess Principle | Iris — conversational AI companion grounded in the protocol. |
| [**v0.6.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.6.0) | Burgess Principle | Sovereign Local Mode — Iris runs entirely on-device. |
| [**v0.7.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.7.0) | Burgess Principle | Financial and crypto expansion — new templates plus faster routing and discovery. |
| [**v0.8.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.8.0) | Burgess Principle | Iris Auto-Generator + Sovereign Claim Builder — generate, fill, sign, and save claims from natural language. |
| [**v0.9.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.9.0) | Burgess Principle | Phone as Sovereign Advocate — installable PWA, voice-first claim flow, and local mobile vault workflow. |
| [**v1.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v1.0) | Burgess Principle | First Contact — personal sovereign identity and signed profile-linked claim generation. |
| [**v1.1.1**](https://github.com/ljbudgie/burgess-principle/releases/tag/v1.1.1) | Burgess Principle | Mirror Mode — hardware identity reflection, mirrored contact reuse, and a more personal sovereign local workflow. |
| [**v1.2.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v1.2.0) | Burgess Principle | Verifiable Memory Palace — commitment-chained ledger blocks, Merkle proofs, full integrity verification, and Sovereign Hub Mode 2.0 for manual-first sync. |

#### Mirror milestone path

| Release | Project | Milestone |
|---------|---------|-----------|
| [**v0.1.0**](https://github.com/ljbudgie/Mirror-/releases/tag/v0.1.0) | Mirror | First Light — tell it what happened, it maps your rights, applies the Burgess Principle, drafts the communication, and gives you the next step. Local-first, no data leaves your device. |

---

### 📈 Current Stack Snapshot

Based on the checked upstream releases, repository positioning, and visible documentation as of **12 April 2026**:

| Project | Current role | Snapshot |
|---------|--------------|----------|
| [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle) | **Anchor** | The most mature public layer in the stack: doctrine, templates, cryptographic evidence, local AI, installable phone workflow, sovereign profile, Mirror Mode, and a verifiable commitment-chained memory ledger. |
| [**Mirror**](https://github.com/ljbudgie/Mirror-) | **Applied rights mapper** | Focused, local-first tool with a strong first release and a very clear product shape. |
| [**Advocate Companion**](https://github.com/ljbudgie/advocate-companion) | **Accessibility application** | Brings the same human-first logic into reasonable adjustments and disability self-advocacy. |
| [**Iris**](https://github.com/ljbudgie/Iris) | **Sovereign AI companion** | Complete, shipping mobile-first companion: voice interaction, letter templates, Memory Palace, Person Gate integration, governance ribbon, PWA-installable, production-grade Next.js stack with end-to-end tests and self-hosting docs. |
| [**Iris Gate**](https://github.com/ljbudgie/iris-gate-person) | **Sovereign records layer** | Keeps personal facts private while exposing only commitments, receipts, and proof surfaces when needed. |
| [**OpenHear**](https://github.com/ljbudgie/openhear) | **Hearing sovereignty** | Extends the same privacy-first philosophy into hearing data and accessibility. |

Taken together, the pattern is now clearer than before:

- **The Burgess Principle** is the doctrinal and shipping anchor.
- **Iris** is the sovereign AI companion that makes the doctrine interactive, mobile-first, and voice-accessible.
- **Mirror** and **Advocate Companion** are focused application layers for rights mapping and disability self-advocacy.
- **Iris Gate** and **Nexus AI Hub** expand the sovereign recordkeeping and tooling surface around that core.

---

### ✨ Why This Stack Stands Apart

- **It is a real stack, not just a model or a UI** — doctrine, templates, apps, cryptographic proof, and deployment paths from cloud to fully local sovereign use.
- **The projects reinforce each other** — the Principle defines the standard, the apps operationalise it, and the sovereign tooling protects the records they create.
- **Accessibility is part of the architecture** — not an afterthought, but a design centre across advocacy, disability tooling, and hearing-tech work.
- **AI is used under accountability constraints** — useful only insofar as it preserves human review, privacy, and personal control.
- **The work is concrete** — tagged releases, documented milestones, shipping tooling, and practical workflows rather than vision-only claims.

---

### 🛠️ Tech Stack

- **Core languages:** ![Python](https://img.shields.io/badge/-Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![HTML/CSS/JS](https://img.shields.io/badge/-HTML%2FCSS%2FJS-E34F26?style=flat-square&logo=html5&logoColor=white)
- **Frontend:** ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Radix UI](https://img.shields.io/badge/-Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white) ![Framer Motion](https://img.shields.io/badge/-Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
- **Local AI:** ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![llama.cpp](https://img.shields.io/badge/-llama--cpp--python-4B0082?style=flat-square)
- **Runtime & delivery:** ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![PWA](https://img.shields.io/badge/-Installable_PWA-5A0FC8?style=flat-square)
- **Security & assurance:** SHA-256 commitments, Ed25519 signatures, Merkle-rooted inclusion proofs, encrypted local vault workflows, optional on-chain fingerprinting, pytest, and accessibility audits

---

### 🌱 Focus Areas

- ⚖️ **Ethical AI & Human-First Protocols** — keeping humans meaningfully in the loop
- 🔐 **Privacy-First & Data Sovereignty** — local-first design, cryptographic commitments, zero external servers where possible
- ♿ **Accessibility & Neurodiversity** — tooling for ADHD, autism, hidden disabilities, and hearing accessibility
- 📜 **Legal Tech & Digital Rights** — accountability, institutional challenge, and structured self-advocacy
- 🤖 **Sovereign AI Workflows** — smart routing, consensus, claim generation, and local identity reflection

---

### 🧭 How It Fits Together

- **The Burgess Principle** sets the standard.
- **Mirror** and **Advocate Companion** help people apply it in real situations.
- **Iris** is the sovereign AI companion that brings the doctrine, the rights mapper, and the sovereign vault into a single interactive experience.
- **Iris Gate** keeps sensitive facts and commitments sovereign.
- **OpenHear** extends the same philosophy into hearing accessibility.
- **Nexus AI Hub** is the wider experimentation space for agents, memory, and skills.

---

### 💬 Ask Me About

The Burgess Principle · sovereign AI · personal data rights · accessibility in tech · local-first advocacy tools · human review over automated power

---

*All projects are open-source and **MIT licensed**. Contributions welcome!*
