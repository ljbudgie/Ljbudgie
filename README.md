## Hi there 👋

Building a sovereign open-source stack for **personal agency**, **human rights**, **accessibility**, and **ethical AI**.

This is a profile hub for a connected ecosystem: a human-first protocol, real-world rights tooling, local-first AI, and cryptographic recordkeeping that all push in the same direction — software that answers to the person, not the institution.

At the centre is [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle), a human-first protocol and registered UK certification mark (**UK00004343685**) built around one diagnostic question:

> *"Was a human member of the team able to personally review the specific facts of my specific situation?"*

Everything else in the stack is there to help people ask that question clearly, evidence it safely, and act on the answer.

---

### 🔭 What I'm Building

An ecosystem of projects designed to reinforce each other: **The Burgess Principle** provides the standard, **Mirror** and **Advocate Companion** turn that standard into guided action, **Iris / Iris Gate** handle sovereign AI and private records, and **OpenHear** applies the same philosophy to bodily data and hearing accessibility.

| Project | Description |
|---------|-------------|
| [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle) | Human-first protocol for challenging automated decisions: one binary test, calm templates, case studies, a Python toolkit, Iris as a cloud/local AI companion, and optional sovereign cryptographic + on-chain enforcement. |
| [**Iris**](https://github.com/ljbudgie/Iris) | AI companion built to look after people first. Multi-model orchestration, routing, and consensus with sovereign handling for personal facts. |
| [**Mirror**](https://github.com/ljbudgie/Mirror-) | Local-first rights mapping toolkit: tell it what happened and it classifies the issue, maps the rights involved, tracks deadlines, drafts the communication, hashes outgoing messages, and gives one clear next step. |
| [**Nexus AI Hub**](https://github.com/ljbudgie/nexus-ai-hub) | Experimental AI hub that brings together agent tooling, memory, skills, and advocacy projects into one cohesive stack. |
| [**Iris Gate**](https://github.com/ljbudgie/iris-gate-person) | Sovereign personal vault for commitments, signed receipts, and private record handling without exposing raw facts. |
| [**Advocate Companion**](https://github.com/ljbudgie/advocate-companion) | Reasonable Adjustment Companion for ADHD, autism, and hidden disabilities under the Equality Act 2010 / ADA. |
| [**OpenHear**](https://github.com/ljbudgie/openhear) | Sovereign hearing-tech pipeline: your audiogram, your data, your algorithms. |

---

### 🔎 Deep Dive: The Burgess Principle & Mirror

#### The Burgess Principle

The Burgess Principle is the doctrinal core of the stack. It is deliberately narrow: not a sprawling theory of everything, but a crisp test for a very specific failure mode in modern systems — decisions that affect real people without an identifiable human mind having actually reviewed the facts.

What makes it interesting is not just the question itself, but the way the repository turns that question into a usable practice:

- **Protocol layer** — a single binary predicate (**SOVEREIGN / NULL**) that can be applied consistently.
- **Practical layer** — calm, ready-to-send templates for disputes, access requests, benefits, enforcement, council tax, disability-related issues, and more.
- **Evidence layer** — case studies, audit trails, institutional registers, and documentation aimed at making the question operational rather than abstract.
- **Sovereign technical layer** — optional local cryptographic tooling, Ed25519-signed receipts, SHA-256 commitments, and on-chain timestamping that avoid exposing personal facts.
- **AI layer** — **Iris**, which now runs either in hosted cloud mode or fully offline in **Sovereign Local Mode**.

From the checked release history, the project has moved quickly from doctrine into tooling:

- **v0.1.0** established the core protocol, templates, verification toolkit, and initial test suite.
- **v0.2.0** introduced commitment-only workflows so users can send a hash instead of raw personal facts.
- **v0.3.0** hardened the cryptographic layer after review, replacing weak primitives and removing fragile dependencies.
- **v0.4.0** added **On-Chain Burgess Claims** for neutral timestamping and verifiable commitments on EVM L2.
- **v0.5.0** made **Iris** the practical conversational interface.
- **v0.6.0** pushed the stack fully local with **Sovereign Local Mode**, installation scripts, a modernised UI, and expanded automated test coverage.

That combination — protocol, templates, cryptographic recordkeeping, and local-first AI — is what makes the project stand out. It is not just arguing that human review matters; it is trying to make that demand legible, repeatable, and technically enforceable.

#### Mirror

If the Burgess Principle is the test, **Mirror** is one of the most direct ways to apply it in practice.

Mirror takes a plain-English account of what happened and turns it into a structured next move:

- it **classifies the situation** into one of nine domains
- it **maps the rights involved**
- it **drafts the communication**
- it **tracks deadlines**
- it **gives one next step instead of a vague list**

The architecture matters as much as the feature set. Mirror is explicitly **local-first**:

- the interface is a simple local web app
- the core logic is Python-based and deterministic by default
- there is **no required server, account, cookie banner, analytics, or cloud backend**
- optional AI support stays local via **Ollama**

That design choice fits the wider ecosystem well. Mirror is not trying to be a generic legal chatbot. It is a restrained rights-mapping tool: classify, orient, draft, move. The inclusion of 27 templates, statutory timelines, and commitment hashing shows a bias toward helping people do something concrete with a difficult situation, not just understand it conceptually.

The checked release history currently shows **Mirror v0.1.0 — First Light** as the first public milestone: the core local-first rights mapper built on the Burgess Principle, with privacy preserved by default.

---

### 🚀 Checked Releases & Milestones

This repository is the profile hub, so releases are published in the individual project repositories rather than here. The links below reflect the checked upstream releases as of **11 April 2026**.

#### Latest checked releases

| Project | Latest checked release | What it means |
|---------|------------------------|---------------|
| [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle) | [**v0.6.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.6.0) | Iris now runs entirely on local hardware in Sovereign Local Mode, with install scripts, updated UI, and expanded test coverage. |
| [**Mirror**](https://github.com/ljbudgie/Mirror-) | [**v0.1.0 — First Light**](https://github.com/ljbudgie/Mirror-/releases/tag/v0.1.0) | First public release of the local-first rights mapper: classify the issue, map rights, generate the question, and give the next step. |

#### Burgess Principle milestone path

| Release | Project | Milestone |
|---------|---------|-----------|
| [**v0.1.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.1.0) | Burgess Principle | First release — binary predicate, calm templates, Python toolkit, 90+ tests, and the registered certification mark (UK00004343685) as an open-source protocol. |
| [**v0.2.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.2.0) | Burgess Principle | Commitment-only mode — send a single SHA-256 hash instead of personal facts. Fresh commitments by default for unlinkability. |
| [**v0.3.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.3.0) | Burgess Principle | Cryptographic security hardening — eight vulnerabilities fixed, AES-256-GCM, PBKDF2, zero third-party crypto beyond audited `@noble/*`. |
| [**v0.4.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.4.0) | Burgess Principle | On-chain Burgess Claims — SHA-256 + Ed25519 commitment fingerprints posted to EVM L2 for neutral timestamping. No personal data touches the chain. |
| [**v0.5.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.5.0) | Burgess Principle | Iris — conversational AI companion grounded in the protocol. Streaming chat UI, system prompt, and serverless deployment. |
| [**v0.6.0**](https://github.com/ljbudgie/burgess-principle/releases/tag/v0.6.0) | Burgess Principle | Sovereign Local Mode — Iris runs entirely on-device via GGUF models. No cloud, no API keys, no data leaving your machine. 264 tests passing. |

#### Mirror milestone path

| Release | Project | Milestone |
|---------|---------|-----------|
| [**v0.1.0**](https://github.com/ljbudgie/Mirror-/releases/tag/v0.1.0) | Mirror | First Light — tell it what happened, it maps your rights, applies the Burgess Principle, drafts the communication, and gives you the next step. Local-first, no data leaves your device. |

---

### 📈 Current Strength Snapshot

Based on the checked upstream releases, repository structure, test surfaces, and workflow evidence as of **11 April 2026**:

| Project | Current strength | Why |
|---------|------------------|-----|
| [**The Burgess Principle**](https://github.com/ljbudgie/burgess-principle) | **Strong / more mature** | Six tagged releases through **v0.6.0**, visible CI on push + pull request, explicit multi-version Python test matrix (**3.11 / 3.12 / 3.13**), published security hardening history, broad documentation, and a larger verified surface spanning protocol, templates, API, on-chain claims, and local AI. |
| [**Mirror**](https://github.com/ljbudgie/Mirror-) | **Promising / early-stage but well-shaped** | A clean **v0.1.0** foundation with strong product clarity, modular Python core, and a meaningful pytest surface across classification, rights mapping, commitments, templates, deadlines, and AI adapter logic — but fewer releases and less visible operational maturity than Burgess Principle at this stage. |

#### Projected relative position

- **The Burgess Principle** currently looks like the stronger repository in terms of maturity, release depth, operational proof, and visible assurance practices.
- **Mirror** looks strong in concept and architecture, with a good early test surface and a very coherent first release, but it still reads like a first-generation product rather than a battle-hardened platform.
- Taken together, that is actually a healthy pattern: **The Burgess Principle** is the established doctrinal and technical anchor, while **Mirror** is a focused application layer with clear room to grow.

---

### ✨ Why This Stack Stands Apart

- **It is a full stack in the real sense** — not just models or UI, but doctrine, templates, software products, cryptographic recordkeeping, and deployment paths from cloud to fully sovereign local use.
- **The projects compound rather than compete** — the protocol informs the apps, the apps generate structured records, and the sovereign tooling protects those records without exposing raw personal facts.
- **Accessibility is treated as core infrastructure** — not an afterthought, but a design centre across rights advocacy, disability tooling, and hearing-tech sovereignty.
- **AI is used with accountability constraints** — routing, consensus, and assistance are useful only insofar as they preserve human review, privacy, and personal control.
- **The work is unusually concrete** — tagged releases, documented milestones, legal framing, case studies, and shipping tools rather than a vision-only repo.

---

### 🛠️ Tech Stack

- **Core languages:** ![Python](https://img.shields.io/badge/-Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![HTML/CSS/JS](https://img.shields.io/badge/-HTML%2FCSS%2FJS-E34F26?style=flat-square&logo=html5&logoColor=white)
- **Frontend:** ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
- **Local AI:** ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![llama.cpp](https://img.shields.io/badge/-llama--cpp--python-4B0082?style=flat-square)
- **Runtime & delivery:** ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
- **Security & assurance:** SHA-256 commitments, Ed25519 signatures, AES-256-GCM / PBKDF2 hardening, pytest, and accessibility audits

---

### 🌱 Focus Areas

- ⚖️ **Ethical AI & Human-First Protocols** — keeping humans meaningfully in the loop
- 🔐 **Privacy-First & Data Sovereignty** — local-first design, cryptographic commitments, zero external servers where possible
- ♿ **Accessibility & Neurodiversity** — tooling for ADHD, autism & hidden disabilities
- 📜 **Legal Tech & Digital Rights** — Equality Act, GDPR, institutional accountability
- 🤖 **Multi-Model AI Orchestration** — smart routing and consensus with local options

---

### 🧭 How It Fits Together

- **The Burgess Principle** sets the human-first standard.
- **Mirror** and **Advocate Companion** help people apply it in real situations.
- **Iris** provides the AI layer, while **Iris Gate** keeps sensitive facts sovereign.
- **OpenHear** extends the same privacy-first philosophy into hearing accessibility.
- **Nexus AI Hub** is the broader experimentation space for agent tooling, memory, and skills.

---

### 💬 Ask Me About

The Burgess Principle · sovereign AI · personal data rights · accessibility in tech · local-first advocacy tools · human review over automated power

---

*All projects are open-source and **MIT licensed**. Contributions welcome!*
