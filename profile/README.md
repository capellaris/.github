<div align="center">

<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:3b82f6,100:8b5cf6&height=220&section=header&text=Capellaris&fontSize=72&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=AI%20Agent%20Console%20%E2%80%94%20Your%20workforce,%20amplified.&descSize=18&descAlignY=55&descAlign=50" width="100%" />

<!-- Tagline badges -->
<p>
  <img src="https://img.shields.io/badge/multi--agent-HMAS-0f172a?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-gateway-3b82f6?style=for-the-badge&logo=lightning&logoColor=white" />
  <img src="https://img.shields.io/badge/multi--org-SaaS-8b5cf6?style=for-the-badge&logo=building&logoColor=white" />
  <img src="https://img.shields.io/badge/realtime-streaming-10b981?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

<br/>

**Capellaris** is an AI-native agent console that lets organizations deploy, orchestrate, and observe<br/>
autonomous AI agents — each with their own role, memory, knowledge base, and toolset.

<br/>

<a href="https://capellaris.dscamargo.com.br">🌐 Live Demo</a> &nbsp;·&nbsp;
<a href="https://www.instagram.com/capellaris.ai">📸 Instagram</a> &nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/daniel13">💼 LinkedIn</a>

<br/><br/>

</div>

---

## ⚡ How it works

```mermaid
graph LR
  subgraph You["👤 Your Team"]
    U[Users]
  end

  subgraph Console["🖥️ capellaris-ai"]
    FE[React App]
    API[Core API]
  end

  subgraph Brain["🧠 capellaris-nebula"]
    HMAS[Agent<br/>Orchestrator]
    A1[📊 Marketing]
    A2[💰 Finance]
    A3[⚖️ Legal]
    A4[💻 Dev]
    A5[📈 Data]
    A6[🔬 Research]
  end

  subgraph Tools["🔌 capellaris-photon"]
    MCP[MCP Gateway]
    T1[Google Drive]
    T2[GitHub]
    T3[Slack]
    T4[+ more]
  end

  subgraph DB["🗄️ Supabase"]
    PG[(PostgreSQL<br/>+ pgvector)]
  end

  U -->|chat, tasks| FE
  FE --> API
  API --> HMAS
  HMAS --> A1 & A2 & A3 & A4 & A5 & A6
  A1 & A2 & A3 & A4 & A5 & A6 -->|use tools| MCP
  MCP --> T1 & T2 & T3 & T4
  HMAS <-->|memory, knowledge, RAG| PG
  API <-->|auth, data| PG

  style You fill:#f8fafc,stroke:#3b82f6,stroke-width:2px
  style Console fill:#eff6ff,stroke:#3b82f6,stroke-width:2px
  style Brain fill:#f5f3ff,stroke:#8b5cf6,stroke-width:2px
  style Tools fill:#ecfdf5,stroke:#10b981,stroke-width:2px
  style DB fill:#fefce8,stroke:#f59e0b,stroke-width:2px
```

<br/>

## 🧠 What makes it different

<table>
<tr>
<td width="50%">

### 🤖 Hierarchical Multi-Agent System
Each org gets 9+ specialized agents (marketing, finance, legal, dev, HR, operations, data, research) orchestrated by a crew manager. Agents collaborate, delegate tasks, and use tools autonomously.

### 🔌 Model Context Protocol
First-class MCP gateway with per-org credential injection. Connect Google Drive, GitHub, Slack, Brave Search — agents use external tools without users ever seeing an API key.

</td>
<td width="50%">

### 📚 RAG Knowledge Base
Upload company docs, business plans, and product info. Vector search (pgvector + HNSW) injects relevant context into agent backstories automatically.

### 🏢 Multi-Org & Multi-Tenant
Full org lifecycle: create, invite (email/link), join, transfer ownership. RLS-enforced data isolation. Role-based access (owner/admin/member/viewer/guest).

</td>
</tr>
</table>

<br/>

## 🛠 Tech Stack

<div align="center">

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/i18n-4_locales-f59e0b?style=for-the-badge" />
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/CrewAI-FF6F00?style=for-the-badge&logo=openai&logoColor=white" />
</p>

### Infrastructure
<p>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

### AI & Models
<p>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Embeddings-text--embedding--3--small-10b981?style=for-the-badge" />
</p>

### Dev & Ops
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud_Build-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white" />
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" />
</p>

</div>

<br/>

## 📦 Repositories

<div align="center">

| Repo | Description | Stack |
|:-----|:------------|:------|
| **capellaris-ai** | Control Plane — console, API, auth, invites | React · Express · TypeScript |
| **capellaris-nebula** | Execution Plane — HMAS orchestration, RAG, learning | Python · FastAPI · CrewAI |
| **capellaris-photon** | MCP Gateway — tool proxy with per-org credentials | TypeScript · MCP Protocol |

</div>

<br/>

## 👤 About the Creator

<table>
<tr>
<td>

**Daniel Camargo** — Full-stack engineer, polyglot, automation enthusiast.

Building Capellaris to make AI agents accessible to every team — not just developers.

<p>
  <a href="https://www.dscamargo.com.br"><img src="https://img.shields.io/badge/Website-dscamargo.com.br-0f172a?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/daniel13"><img src="https://img.shields.io/badge/LinkedIn-daniel13-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:daniel.camargo@hotmail.com"><img src="https://img.shields.io/badge/Email-daniel.camargo-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.instagram.com/capellaris.ai"><img src="https://img.shields.io/badge/Instagram-capellaris.ai-E4405F?style=flat-square&logo=instagram&logoColor=white" /></a>
</p>

</td>
</tr>
</table>

<br/>

<!-- Footer -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:3b82f6,100:8b5cf6&height=100&section=footer" width="100%" />

</div>
