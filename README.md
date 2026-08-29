<div align="center">

<!-- ============ BANNER ============ -->
<img src="./banner.svg" width="100%" alt="Angel Zapata · Systems & Full Stack Developer"/>

<!-- ============ TYPING EFFECT ============ -->
<a href="https://github.com/angeldevmobile">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=22D3EE&center=true&vCenter=true&width=600&lines=Shipped+Flux%2C+an+API+client+for+devs;Building+Orion%2C+a+language+in+Rust;Rust+%C2%B7+TypeScript+%C2%B7+Java+%C2%B7+Python;Banking+%26+Fintech+background" alt="Typing SVG" />
</a>

<br/><br/>

<!-- ============ SOCIAL BADGES ============ -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabriel-zapata-239501287/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0b1220?style=for-the-badge&logo=vercel&logoColor=22d3ee)](https://portfolio-angel-dev.onrender.com/)
[![Email](https://img.shields.io/badge/Email-0b1220?style=for-the-badge&logo=gmail&logoColor=22d3ee)](mailto:zapata.axuariogabriel@gmail.com)

<img src="https://komarev.com/ghpvc/?username=angeldevmobile&color=22d3ee&style=flat-square&label=Profile+Views" alt="Profile views"/>

</div>

<br/>

## About me

```typescript
const angel = {
  role: "Systems & Full Stack Developer",
  location: "Perú",
  languages: ["Rust", "TypeScript", "Java", "Python", "Dart"],
  stack: {
    systems:  ["Rust", "Cranelift", "Tokio"],
    backend:  ["Node.js", "Spring Boot", "Flask"],
    frontend: ["React", "Next.js", "Flutter"],
    data:     ["PostgreSQL", "Prisma"],
  },
  shipped:  "Flux · API client, launched on Product Hunt & Hacker News",
  building: "Orion · a language written in Rust (VM, JIT, GC, 58+ stdlib modules)",
  background: "Banking & Fintech: secure payments, compliance, high-perf APIs",
  philosophy: "Build things that matter, ship things that work",
};
```

<br/>

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛰️ Flux &nbsp;![Shipped](https://img.shields.io/badge/Shipped-34d399?style=flat-square&labelColor=0b1220)

Desktop API client & Postman alternative. AI test generation, gRPC, GraphQL, WebSocket, SSE, and a free CLI runner for CI.

![Rust](https://img.shields.io/badge/Rust-0b1220?style=flat-square&logo=rust&logoColor=22d3ee)
![Tauri](https://img.shields.io/badge/Tauri-0b1220?style=flat-square&logo=tauri&logoColor=22d3ee)
![TypeScript](https://img.shields.io/badge/TypeScript-0b1220?style=flat-square&logo=typescript&logoColor=22d3ee)

[![Website](https://img.shields.io/badge/fluxapi.dev-0b1220?style=flat-square&logo=googlechrome&logoColor=22d3ee)](https://fluxapi.dev)
[![Repo](https://img.shields.io/badge/Repo-0b1220?style=flat-square&logo=github&logoColor=22d3ee)](https://github.com/angeldevmobile/Flux-Post)

</td>
<td width="50%" valign="top">

### ⚙️ Orion &nbsp;![Active](https://img.shields.io/badge/Active-fbbf24?style=flat-square&labelColor=0b1220)

A programming language written in Rust, in active development since early 2025. Bytecode VM, Cranelift JIT, custom GC, DAP debugger, 58+ stdlib modules, and 400+ automated tests.

![Rust](https://img.shields.io/badge/Rust-0b1220?style=flat-square&logo=rust&logoColor=22d3ee)
![Cranelift](https://img.shields.io/badge/Cranelift_JIT-0b1220?style=flat-square&logoColor=22d3ee)

[![Repo](https://img.shields.io/badge/Repo-0b1220?style=flat-square&logo=github&logoColor=22d3ee)](https://github.com/angeldevmobile/Orion)
[![VS Code ext](https://img.shields.io/badge/VS_Code_ext-0b1220?style=flat-square&logo=visualstudiocode&logoColor=22d3ee)](https://github.com/angeldevmobile/Extension-lenguaje-orion)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 Flux Learning &nbsp;![Live](https://img.shields.io/badge/Live_·_Beta-22d3ee?style=flat-square&labelColor=0b1220)

AI-powered flashcards with spaced repetition (SM-2), real-time duels, weekly leagues, and a deck marketplace. Import from PDF, YouTube or text.

![Next.js](https://img.shields.io/badge/Next.js-0b1220?style=flat-square&logo=nextdotjs&logoColor=22d3ee)
![TypeScript](https://img.shields.io/badge/TypeScript-0b1220?style=flat-square&logo=typescript&logoColor=22d3ee)
![Supabase](https://img.shields.io/badge/Supabase-0b1220?style=flat-square&logo=supabase&logoColor=22d3ee)

[![Live Demo](https://img.shields.io/badge/Live_Demo-0b1220?style=flat-square&logo=vercel&logoColor=22d3ee)](https://flux-learning-7g6f.vercel.app/)

</td>
<td width="50%" valign="top">

### 🤖 Orion AI Platform &nbsp;![Early](https://img.shields.io/badge/Early-f97316?style=flat-square&labelColor=0b1220)

Multi-LLM automation platform, built as an application layer on top of Orion. Early stage, no public release yet.

![React](https://img.shields.io/badge/React-0b1220?style=flat-square&logo=react&logoColor=22d3ee)
![Node.js](https://img.shields.io/badge/Node.js-0b1220?style=flat-square&logo=nodedotjs&logoColor=22d3ee)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0b1220?style=flat-square&logo=postgresql&logoColor=22d3ee)

</td>
</tr>
</table>

**Orion ecosystem:** [VS Code extension](https://github.com/angeldevmobile/Extension-lenguaje-orion) (IntelliSense, real compiler diagnostics, debugger) · [Playground API](https://github.com/angeldevmobile/PlayGround---API) (sandboxed execution, Rust + Axum)

<details>
<summary><b>A taste of Orion</b></summary>

```orion
use json
use fs

data = json.parse(fs.read("users.json"))
summary = json.extract(data, ["name", "age"])
show("Summary:", summary)
```

Clean syntax, gradual typing (type-checked by default), a concurrent HTTP server, and a columnar data engine (`.odf` format, ~8× faster than Python in benchmarks).
</details>

<br/>

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=rust,ts,js,py,dart&theme=dark" alt="Languages"/>

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,spring,fastapi,graphql&theme=dark" alt="Backend"/>

**Frontend & Mobile**

<img src="https://skillicons.dev/icons?i=react,nextjs,flutter,tailwind&theme=dark" alt="Frontend"/>

**Databases & Cloud**

<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,firebase,prisma,aws,docker,vercel,githubactions&theme=dark" alt="DB & Cloud"/>

**AI & Integrations**

![OpenAI](https://img.shields.io/badge/OpenAI_GPT-0b1220?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_Claude-0b1220?style=flat-square&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0b1220?style=flat-square&logo=langchain&logoColor=34d399)
![RAG](https://img.shields.io/badge/RAG_Systems-0b1220?style=flat-square&logoColor=22d3ee)

</div>

<br/>

## GitHub Stats

<div align="center">

<img width="49%" src="./profile-summary-card-output/github_dark/3-stats.svg" alt="GitHub Stats"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=angeldevmobile&hide_border=true&background=00000000&ring=22d3ee&fire=34d399&currStreakLabel=22d3ee&currStreakNum=ffffff&sideNums=22d3ee&sideLabels=8b949e&dates=8b949e" alt="Streak"/>

<img width="49%" src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repos per Language"/>
<img width="49%" src="./profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Most Commit Language"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=angeldevmobile&bg_color=00000000&color=22d3ee&line=34d399&point=ffffff&area=true&area_color=22d3ee&hide_border=true&custom_title=Contribution%20Graph" alt="Activity Graph"/>

</div>

<!-- ============ SNAKE ANIMATION ============ -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/angeldevmobile/angeldevmobile/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/angeldevmobile/angeldevmobile/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/angeldevmobile/angeldevmobile/output/github-contribution-grid-snake.svg">
</picture>

</div>

<br/>

## Certifications & Learning

<table>
<tr>
<td width="50%" valign="top">

**Certifications**

| Certification | Issuer | Year |
|:---|:---|:---|
| OCI 2023 Certified Foundations Associate | Oracle | 2023 |
| OCI 2023 AI Certified Foundations Associate | Oracle | 2023 |
| Python for Data Science and AI | Coursera | 2024 |
| IBM Mainframe Developer | IBM |  |
| Google Data Analytics | Google |  |

</td>
<td width="50%" valign="top">

**Currently learning**

| Topic | Focus |
|:---|:---|
| Compiler design | LLVM, ANTLR4, AST optimization |
| Rust | Systems programming |
| Advanced ML | RAG systems, LLM fine-tuning |
| Distributed systems | Architecture patterns |

</td>
</tr>
</table>

<br/>

## Let's connect

<div align="center">

Open to collaborating on ambitious projects, discussing architecture decisions, or just talking tech.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabriel-zapata-239501287/)
[![Gmail](https://img.shields.io/badge/Gmail-Write_me-0b1220?style=for-the-badge&logo=gmail&logoColor=22d3ee)](mailto:zapata.axuariogabriel@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-See_my_work-0b1220?style=for-the-badge&logo=vercel&logoColor=22d3ee)](https://portfolio-angel-dev.onrender.com/)

<br/>

<sub><i>"Build things that matter, ship things that work."</i></sub>

</div>
