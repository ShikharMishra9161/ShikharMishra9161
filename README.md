<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:6366f1&height=200&section=header&text=Shikhar%20Mishra&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20%26%20Backend%20Engineer&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="header"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=6366F1&center=true&vCenter=true&width=640&lines=Node.js+%C2%B7+TypeScript+%C2%B7+Next.js+%C2%B7+Redis;Building+fault-tolerant+backends+%E2%9A%99%EF%B8%8F;Shipping+LLM-powered+products+%F0%9F%A4%96;~200+jobs%2Fsec+%40+p99+%3C+85ms+%F0%9F%9A%80;Open+to+SDE+internships+%26+new-grad+roles+(2027)" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://shikharmishra9161.github.io/"><img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/shikhar-mishra-480171294/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/shikharmishra7/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:shikharmishra9161@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://shikharmishra9161.github.io/assets/Shikhar_Mishra_Resume.pdf"><img src="https://img.shields.io/badge/Resume-111827?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ShikharMishra9161&color=6366f1&style=flat-square&label=Profile+Views" alt="profile views"/>
</p>

---

## 👨‍💻 About Me

```ts
const shikhar = {
  role:        "Full-Stack & Backend Engineer",
  education:   "B.Tech CSE @ AKGEC, Ghaziabad (2023 – 2027)",
  experience:  "SWE Intern @ Itrik Softech (Jan – Jun 2026)",
  focus:       ["job queues", "retry logic", "indexing", "performance under load", "LLM features"],
  dailyHabit:  "LeetCode in Java — 300+ problems solved",
  lookingFor:  "SDE internships (6-month · on-site / hybrid / remote) & new-grad roles 2027",
};
```

- ⚙️ I like the parts of a system that break under load: queues, retries, crash recovery, and slow queries
- 🤖 I build LLM features into real products: Gemini function calling, RAG pipelines, streaming voice
- 🧪 I write modular, tested code (Jest, Vitest, real-database integration tests) and ship with CI/CD
- 🏆 Cleared Rounds 1 & 2 of **HackWithInfy** (Infosys)

---

## 💼 Experience

**Software Engineering Intern** · Itrik Softech Private Limited · *Jan 2026 – Jun 2026*
- Built Node.js REST APIs and integrated JWT authentication to secure endpoints and web workflows
- Debugged existing systems to fix defects and improve performance; built React + Tailwind CSS frontends
- Worked in agile sprints with peer code reviews on Git/GitHub; tested and deployed releases on Vercel and Render

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📊 [Pulse](https://github.com/ShikharMishra9161/pulse-analytics)
**Multi-tenant product analytics platform** — a lightweight Mixpanel/PostHog alternative

- Public REST API for custom events → real-time & historical dashboards
- PostgreSQL schema with composite + **GIN JSONB indexes**, partition-ready event table
- API-key auth, per-key rate limits, Zod validation, **4-role RBAC**
- **64 tests** in Vitest against a real Postgres DB

<img src="https://skillicons.dev/icons?i=nextjs,ts,postgres,prisma,vercel" height="32"/>

[🔗 Live](https://pulse-analytics-self.vercel.app) · [💻 Code](https://github.com/ShikharMishra9161/pulse-analytics)

</td>
<td width="50%" valign="top">

### ⚙️ [TaskFlow](https://github.com/ShikharMishra9161/taskflow)
**Distributed job queue & background workers**

- Redis priority queue (atomic Lua pop) → N concurrent workers
- **~200 jobs/sec at p99 < 85 ms** in load tests
- Idempotency keys, exponential backoff, dead-letter queue
- Heartbeat recovery requeued **100%** of in-flight jobs from crashed workers
- 4 Dockerized services · CI on GitHub Actions → GHCR

<img src="https://skillicons.dev/icons?i=nodejs,ts,express,redis,mongodb,docker,githubactions" height="32"/>

[💻 Code](https://github.com/ShikharMishra9161/taskflow)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ [Saamne](https://github.com/ShikharMishra9161/saamne)
**AI voice mock-interview platform**

- Real-time voice interviewer across 3 rounds; generates questions from your resume PDF
- **2–3x lower voice latency (~1.2s)** by streaming Gemini output to speech sentence by sentence
- Sandboxed code runner for **4 languages** with hidden performance tests that reject brute force
- Zod-validated LLM feedback reports

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind" height="32"/>

[💻 Code](https://github.com/ShikharMishra9161/saamne)

</td>
<td width="50%" valign="top">

### 🧠 [AI Study Planner](https://github.com/ShikharMishra9161/ai-study-planner)
**Gamified MERN app with an AI agent**

- **44 REST endpoints** across 6 MongoDB models
- **91% faster queries** (167 ms → 15 ms), 99.9% fewer docs scanned with 9 compound indexes on 100K tasks
- Gemini agent with function calling for personalized study paths
- RAG pipeline with OCR over uploaded notes

<img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb" height="32"/>

[🔗 Live](https://ai-study-planner-omega-five.vercel.app/) · [💻 Code](https://github.com/ShikharMishra9161/ai-study-planner)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<p align="center">
  <b>Languages</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=ts,js,java,python,html,css&perline=10" alt="languages"/>
</p>

<p align="center">
  <b>Frontend & Backend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,nodejs,express&perline=10" alt="frameworks"/>
</p>

<p align="center">
  <b>Databases</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,prisma,mongodb,mysql,redis&perline=10" alt="databases"/>
</p>

<p align="center">
  <b>DevOps, Testing & Tools</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=docker,githubactions,jest,vitest,git,github,vercel,postman&perline=10" alt="tools"/>
</p>

<p align="center">
  <b>AI / LLM</b><br/><br/>
  <img src="https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/Function_Calling-111827?style=for-the-badge&logo=openai&logoColor=white" alt="Function calling"/>
  <img src="https://img.shields.io/badge/RAG-6366F1?style=for-the-badge&logo=databricks&logoColor=white" alt="RAG"/>
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white" alt="Zod"/>
</p>

---

## 📈 GitHub & LeetCode Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ShikharMishra9161&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="165" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShikharMishra9161&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="165" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ShikharMishra9161&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/shikharmishra7?theme=dark&font=JetBrains%20Mono&ext=heatmap" alt="LeetCode stats"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ShikharMishra9161&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Contribution graph"/>
</p>

---

## 🌱 Currently Exploring

- 🏗️ System design — scaling, caching, and event-driven architectures
- ☁️ AWS fundamentals for deploying containerized services
- 🤖 Deeper AI agent & RAG architectures

---

## 🤝 Let's Connect

<p align="center">
  I'm open to <b>SDE / Backend / Full-Stack internships</b> and <b>new-grad roles (2027)</b>.<br/>
  The fastest way to reach me is <a href="mailto:shikharmishra9161@gmail.com">shikharmishra9161@gmail.com</a>.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:1e3a8a,100:0f172a&height=110&section=footer" width="100%" alt="footer"/>
</p>
