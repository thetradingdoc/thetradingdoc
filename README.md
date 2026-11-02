<p align="center"><img src="assets/profile-banner.svg" alt="AI Engineer — Solution Design" width="100%"/></p>

<p align="center">
<a href="#01--moneyfinder">🏆 MoneyFinder</a> &nbsp;·&nbsp;
<a href="#02--somo">🏆 Somo</a> &nbsp;·&nbsp;
<a href="#03--rehabninja">🎮 RehabNinja</a> &nbsp;·&nbsp;
<a href="#04--comfy-race">🏎️ Comfy Race</a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white" alt="React"/>
<img src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
<img src="https://img.shields.io/badge/Computer_Vision-7C3AED?style=flat-square" alt="Computer Vision"/>
<img src="https://img.shields.io/badge/AI_Agents-0F766E?style=flat-square" alt="AI Agents"/>
<img src="https://img.shields.io/badge/LLM_Tools-2563EB?style=flat-square" alt="LLM Tool Use"/>
<img src="https://img.shields.io/badge/ComfyUI-E11D48?style=flat-square" alt="ComfyUI"/>
<img src="https://img.shields.io/badge/Cloud-475569?style=flat-square" alt="Cloud Infrastructure"/>
</p>

**AI Engineer · Solution Design**

I design and build AI systems from problem definition through working product—connecting models, agents, computer vision, interfaces, and infrastructure into useful experiences. My work spans healthcare, financial technology, and interactive creative tools.

**4× hackathon winner** &nbsp;·&nbsp; **4 featured builds** &nbsp;·&nbsp; **Open-source builder**

[Selected work](#selected-work) · [Currently building](#04--comfy-race) · [How I build](#how-i-build)

---

## Selected work

### 01 / MoneyFinder &nbsp; 🏆 Hackathon winner

**AI-powered opportunity discovery for small businesses.**

MoneyFinder researches a business, identifies relevant **tax credits and unclaimed-funds opportunities**, creates an evidence-backed dossier, and prepares claim forms. The goal is to replace hours of disconnected research and repetitive paperwork with an explainable, approval-first workflow.

[**Explore the repository ↗**](https://github.com/thetradingdoc/moneyfinder) &nbsp;·&nbsp; [**Watch the demo ↗**](https://youtu.be/ltOwx898b8c)

<a href="https://youtu.be/ltOwx898b8c"><img src="https://raw.githubusercontent.com/thetradingdoc/moneyfinder/main/docs/assets/moneyfinder-intro.jpg" alt="MoneyFinder project demo — click to watch" width="720"/></a>

<details>
<summary><b>How it works — open the build notes</b></summary>
<br/>

- **Research:** builds a sourced business profile using company information and public records.
- **Reasoning:** matches company characteristics to specific incentives and explains why each program might apply.
- **Agent action:** creates a form-ready dossier, fills forms using a browser agent, reads values back, and stops for human approval.
- **Evidence:** preserves provenance and separates agency claim status from actual payment confirmation.

**Stack:** Python · AI agents · AWS Bedrock / Claude · SurrealDB · Anchor Browser · Daytona · Arize.

*The demo uses synthetic business data; recommendations are not tax or legal advice.*

</details>

---

### 02 / Somo &nbsp; 🏆 Hackathon winner

**An AI-native front desk for healthcare practices.**

Somo combines a conversational **AI receptionist** with operational tools for appointment booking, insurance eligibility, patient administration, and billing. It is designed to reduce repetitive front-desk work while keeping clinical and financial workflows auditable.

[**Explore the repository ↗**](https://github.com/thetradingdoc/somo-platform) &nbsp;·&nbsp; [**Somo website ↗**](https://callsomo.com)

<a href="https://github.com/thetradingdoc/somo-platform"><img src="https://raw.githubusercontent.com/thetradingdoc/somo-platform/main/middleware-platform/e2e-artifacts/provider-portal/today-desktop.png" alt="Somo healthcare provider portal — Today dashboard screenshot" width="720"/></a>

<details>
<summary><b>Explore the platform — product and architecture</b></summary>
<br/>

- **Voice front desk:** the Kelly AI agent handles inbound conversations and appointment scheduling.
- **Practice operations:** provider workflows cover patient context, schedules, confirmations, and front-desk visibility.
- **Revenue cycle:** insurance eligibility, claim workflows, payment tools, and medical coding integrations.
- **Two product lines:** a B2B front-desk pilot and a separate consumer health-session experience.

**Stack:** JavaScript / Node.js · Retell AI · FHIR · Stedi · Stripe · Google Cloud.

*Prototype and pilot functionality should not be confused with independently validated clinical or production outcomes.*

<details>
<summary>See another Somo screen</summary>
<br/>
<img src="https://raw.githubusercontent.com/thetradingdoc/somo-platform/main/middleware-platform/e2e-artifacts/provider-portal/agent-desktop.png" alt="Somo AI agent interface screenshot" width="720"/>
</details>

</details>

---

### 03 / RehabNinja &nbsp; Completed interactive prototype

**Physical rehabilitation turned into a camera-powered game.**

RehabNinja makes home exercises feel like play. A person follows a prescribed movement in front of their phone: **good reps slice fruit; form mistakes turn into bombs**. Behind the game, pose tracking records movement quality and gives simple feedback after the session.

[**Explore the repository ↗**](https://github.com/thetradingdoc/rehabninja) &nbsp;·&nbsp; [**Demo walkthrough ↗**](https://github.com/thetradingdoc/rehabninja/blob/main/docs/PLAY-DEMO.md)

<p>
<a href="https://github.com/thetradingdoc/rehabninja"><img src="https://raw.githubusercontent.com/thetradingdoc/rehabninja/main/docs/images/04-live-fruit.jpg" alt="RehabNinja live pose-tracked exercise with fruit game targets" width="250"/></a>
<a href="https://github.com/thetradingdoc/rehabninja"><img src="https://raw.githubusercontent.com/thetradingdoc/rehabninja/main/docs/images/05-live-bombs.jpg" alt="RehabNinja game feedback when exercise form breaks" width="250"/></a>
<a href="https://github.com/thetradingdoc/rehabninja"><img src="https://raw.githubusercontent.com/thetradingdoc/rehabninja/main/docs/images/06-session-report.jpg" alt="RehabNinja exercise session report" width="250"/></a>
</p>

<details>
<summary><b>What is inside the prototype?</b></summary>
<br/>

- **On-device computer vision:** YOLO11 pose inference with a MediaPipe fallback.
- **Real interaction:** tracks chair stands, squats, and balance exercises; game reactions correspond to movement/form events.
- **Patient experience:** short voice prompts, accessible feedback, and end-of-session summaries.
- **Safety design:** explicit symptom questions and rule-based triage, rather than AI inventing medical decisions.

**Stack:** Next.js · TypeScript · WebGPU / WASM · YOLO / MediaPipe · PixiJS · ElevenLabs.

*Built as a demo using synthetic patient data; not a clinically validated rehabilitation device.*

</details>

---

### 04 / Comfy Race &nbsp; In development

**What if ComfyUI could render the visuals of a game while you're playing it?**

Comfy Race explores a live racing experience where a native physics engine handles steering and collisions, and **ComfyStream + ComfyUI** restyle the actual game footage as it arrives. The essential proof is simple: **can you finish a race while watching only the AI-generated view?**

[**Explore the repository ↗**](https://github.com/thetradingdoc/comfy-race) &nbsp;·&nbsp; [**Read the build epic ↗**](https://github.com/thetradingdoc/comfy-race/blob/main/docs/BUILD_PLAN.md)

<details>
<summary><b>Live system architecture — see the planned pipeline</b></summary>
<br/>

```mermaid
flowchart LR
    A[Player input] --> B[Native racing physics]
    B --> C[Low-poly game frames]
    C --> D[ComfyStream]
    D --> E[ComfyUI image generation]
    E --> F[Live player display]
```

**Status:** design and source review completed; playable latency and the end-to-end integration have **not** been validated. No rendered demo is presented here as a finished feature.

</details>

---

## How I build

I work across the product stack, from an idea and user journey to APIs, model orchestration, real-time interaction, deployment, and testing.

<details>
<summary><b>More open-source work</b></summary>
<br/>

- [Clinical Data Science Portfolio](https://github.com/thetradingdoc/ClinicalDataSciencePortfolio) — applied machine learning in healthcare.
- [ComfyUI Templates](https://github.com/thetradingdoc/awesome-comfyui-templates) — reproducible creative AI workflows.
- [Medical RAG API](https://github.com/thetradingdoc/medical-rag-api) — medical code retrieval through vector search.
- [BillOps Agent](https://github.com/thetradingdoc/billops-agent) — invoice intake, policy review, and human-approved processing.

</details>

---

<sub>**Build real things. Show the work. Keep the evidence.** &nbsp;·&nbsp; [All repositories](https://github.com/thetradingdoc?tab=repositories)</sub>
