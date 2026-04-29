<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Myxelium-Corp&fontSize=70&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Weaver%20of%20Digital%20Ecosystems%20%F0%9F%8D%84&descAlignY=55&descSize=22" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1200&color=00FF9C&center=true&vCenter=true&width=700&lines=Multi-Agent+AI+Orchestration+Platform+%F0%9F%8D%84;Inspired+by+fungal+mycelium+networks;LangGraph+%7C+Fastify+%7C+Vue3+%7C+Firebase+%7C+GCP;Zero+Trust+%7C+Human-In-The-Loop+%E2%9C%85;Production+on+Google+Cloud+Run+%F0%9F%9A%80" />

[![CI - Mycelium-Dev](https://github.com/Myxelium-Corp/Mycelium-Dev/actions/workflows/ci.yml/badge.svg)](https://github.com/Myxelium-Corp/Mycelium-Dev/actions/workflows/ci.yml)
[![Org](https://img.shields.io/badge/GitHub-Myxelium--Corp-00FF9C?style=flat-square&logo=github&labelColor=1a1a2e)](https://github.com/Myxelium-Corp)
[![Cloud Run](https://img.shields.io/badge/Cloud_Run-Live_🟢-4285F4?style=flat-square&logo=google-cloud&labelColor=1a1a2e)](https://antigravity-os-95047737843.us-west1.run.app)
[![License](https://img.shields.io/badge/License-Unlicensed-red?style=flat-square&labelColor=1a1a2e)](https://github.com/Myxelium-Corp)

</div>

---

## 🍄 Vision

> *"Mycelium is not a product. It's a living architecture — a swarm of AI agents coordinating like fungal networks underground, invisible yet omnipresent."*
>
> — Jordan Zerathe, Founder

Myxelium-Corp construit une **plateforme d'orchestration multi-agents IA** biomimétique.  
Chaque agent est une **cellule** dans un réseau vivant, capable de mémoire, d'apprentissage et de coordination autonome — sous supervision humaine stricte (HITL).

---

## 🧬 Architecture Mycelium OS

```mermaid
graph TB
    subgraph HUMAN["👤 Human Layer — Jordan Gate"]
        HMN[Jordan Zerathe\nRoot Admin]
        COCKPIT[🎛️ Cockpit-v2\nDashboard Vue3]
    end

    subgraph CLOUD["☁️ Cloud — Google Cloud Run"]
        AG[🌌 Antigravity OS\nOrchestrator]
        NX[🧠 Nexus Gateway\nFastify Router]
        BRAIN[🔮 Brain Dashboard]
    end

    subgraph AGENTS["🐝 Agent Swarm"]
        HIVE[HIVE\nLangGraph]
        SWARM[SWARM\nRedis pub/sub]
        CELLS[CELLS\nAutonomous Agents]
    end

    subgraph MEMORY["💾 Memory Layers"]
        FB[(Firebase\nFirestore)]
        VEC[(Vector Store\nEmbeddings)]
        CTX[Context\nCheckpointer]
    end

    HMN --> COCKPIT
    COCKPIT --> AG
    AG --> NX
    NX --> HIVE
    HIVE --> SWARM
    SWARM --> CELLS
    CELLS --> FB
    CELLS --> VEC
    FB --> CTX
    CTX --> HIVE
```

---

## 🗂️ Repositories

| Repo | Description | Status | Stack |
|------|-------------|--------|-------|
| [🧠 Mycelium-AI-core](https://github.com/Myxelium-Corp/Mycelium-AI-core) | Core IA : agents, OMEGA mission, Firebase checkpointer | 🟢 Actif | TS · LangGraph · Firebase |
| [⚙️ Mycelium-Dev](https://github.com/Myxelium-Corp/Mycelium-Dev) | Monorepo : cockpit-v2, core-api, Docker infra | 🟡 CI fix PR#11 | Vue3 · Express · Docker |
| [🌐 Open-Mycelium](https://github.com/Myxelium-Corp/Open-Mycelium) | Documentation publique & specs | 🟢 Actif | Markdown |
| [📚 Myxelium-Doc](https://github.com/Myxelium-Corp/Myxelium-Doc) | Wiki technique | 🟡 En construction | Markdown |

---

## 🛠️ Stack Technologique

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-00FF9C?style=for-the-badge&logo=langchain&logoColor=black" />
  <img src="https://img.shields.io/badge/Mermaid-FF3670?style=for-the-badge&logo=mermaid&logoColor=white" />
</p>

---

## 🔒 Gouvernance & Principes

| Principe | Implémentation |
|----------|---------------|
| **Zero Trust** | Chaque agent a des droits minimaux, auditables |
| **Human-In-The-Loop** | Jordan = seul décisionnaire final (Jordan Gate) |
| **Source of Truth** | `Mycelium-AI-core/OMEGA_MISSION_CONTROL.md` |
| **Branch Policy** | PRs obligatoires, CI vert requis avant merge |
| **Audit Trail** | Chaque action loguée dans Firestore |

---

## 🌟 Contribuer

> ⚠️ **Repos privés actuellement.** Ouverture progressive planifiée.

Pour collaborer :
1. Contacter **[@Drag0n69](https://github.com/Drag0n69)**
2. Review de code par des personnes de confiance via GitHub PRs
3. Zero Trust appliqué à chaque nouveau collaborateur

---

## 📫 Contact

<p align="left">
  <a href="https://github.com/Drag0n69"><img src="https://img.shields.io/badge/GitHub-Drag0n69-00FF9C?style=flat-square&logo=github&labelColor=1a1a2e" /></a>
  <a href="https://www.youtube.com/@Drag0n69_RSA"><img src="https://img.shields.io/badge/YouTube-Drag0n69_RSA-FF0000?style=flat-square&logo=youtube&labelColor=1a1a2e" /></a>
  <a href="https://x.com/JordanZera76441"><img src="https://img.shields.io/badge/Twitter-JordanZera76441-1DA1F2?style=flat-square&logo=twitter&labelColor=1a1a2e" /></a>
</p>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />

<div align="center">
<sub>🍄 Mycelium OMEGA — <em>Sovereignty & Intelligence</em> — Built with ❤️ by <a href="https://github.com/Drag0n69">Jordan Zerathe</a></sub>
</div>
