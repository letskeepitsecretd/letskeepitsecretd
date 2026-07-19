<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5f,100:0ea5e9&height=200&section=header&text=Dev%20Kumar%20Raikwar&fontSize=42&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=CS%20(IoT)%20Student%20%7C%20Building%20with%20AI%20Coding%20Agents%20%7C%20Learning%20DSA&descAlignY=58&descSize=16" />

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=650&lines=3rd-Year+B.Tech+CS+(IoT)+Student;Building+full-stack+%2B+agentic+AI+projects;Learning+DSA;Still+figuring+a+lot+of+this+out" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/B.Tech-Computer%20Science%20(IoT)-1e3a5f?style=for-the-badge&logo=googlescholar&logoColor=white" />
<img src="https://img.shields.io/badge/Manipal%20University%20Jaipur-Class%20of%202028-0f4c75?style=for-the-badge&logo=graduation-cap&logoColor=white" />
<img src="https://img.shields.io/badge/CGPA-8.4-0ea5e9?style=for-the-badge&logo=googlescholar&logoColor=white" />

<br/><br/>

<a href="https://gitgravity.vercel.app"><img src="https://img.shields.io/badge/Project-gitgravity.vercel.app-0284c7?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://linkedin.com/in/dev-kumar-raikwar-x7"><img src="https://img.shields.io/badge/LinkedIn-Connect-0369a1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:dev.1806raikwar21@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-0891b2?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/raikwarxdev"><img src="https://img.shields.io/badge/GitHub-raikwarxdev-155e75?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=raikwarxdev&label=Profile%20Views&color=0ea5e9&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/raikwarxdev?label=Followers&style=for-the-badge&color=0284c7&logo=github" />

</div>

<br/>

---

## ⚙️ About Me

```yaml
student:
  name: "Dev Kumar Raikwar"
  year: "3rd Year, B.Tech CS (IoT)"
  university: "Manipal University Jaipur"
  cgpa: 8.4
  how_i_build:
    - Ship real, working projects and figure out the rest along the way
    - Comfortable gluing together frontend, backend, and deployment for a project to actually work
  focus_areas:
    - Sharpening DSA fundamentals
  self_description: "Still a student. Still learning. Building things anyway."
```

I'm a 3rd-year Computer Science (IoT) student. I like building things that actually run — not just code that compiles, but apps that are deployed, working, and have real users hitting them. I'm currently sharpening DSA. I'm a student who's figured out how to ship, and I'm working on closing the gap between "can build a working app" and "understands everything under the hood."

<table align="center">
<tr>
<td>

**🎯 Currently Looking For**
- Software Engineering Internships (2027)
- Opportunities to learn from people better than me at this
- Feedback on my projects — I'd rather know what's wrong now

</td>
</tr>
</table>

<br/>

---

## ⚙️ Tools I've Used

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=c,cpp,python,js,ts,mysql" />

<br/><br/>

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,html,css" />

<br/><br/>

**Backend & Databases**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,fastapi,express,sqlite,mongodb,mysql,firebase,redis" />

<br/><br/>

**Deployment & Tools**
<br/>
<img src="https://skillicons.dev/icons?i=vercel,git,github,linux,vscode,arduino,raspberrypi" />

</div>

<br/>

---

## ⚙️ What I've Worked With (AI/Agentic Stuff)

Built as part of one hackathon project (FinTwin), still developing depth here:

- **LLM tool-calling agents** — built an agent pipeline (Groq / Llama 3.3) that picks between a few tools before responding
- **Basic RAG** — used sentence-transformers + cosine similarity to retrieve relevant docs before an LLM call, no vector DB
- **Confidence-based routing** — set a threshold so low-confidence agent decisions get flagged for human review instead of auto-executing
- **Async API handling** — dealt with rate limits by rotating API keys across a few Groq keys

<br/>

---

## ⚙️ Projects

<details open>
<summary><b>🚀 GitGravity — GitHub Wrapped-style Experience</b></summary>
<br/>

A deployed web app (gitgravity.vercel.app) that pulls a user's real GitHub stats and turns them into a 5-slide animated story, ending with a shareable, procedurally generated card.

| | |
|---|---|
| **Stack** | Next.js 14, TypeScript, Framer Motion, Canvas API, Upstash Redis, Vercel |
| **Status** | Live, still actively being worked on |
| **What it does** | Canvas-based particle animation, deterministic card generation per user/month, an admin dashboard to see usage |

Ran into and fixed real deployment issues along the way — Vercel's ephemeral filesystem wiping saved data (moved to Redis), Next.js serving stale cached data, and CORS issues with GitHub's avatar CDN.

</details>

<br/>

<details>
<summary><b>🏦 FinTwin — Agentic AI Banking Project</b></summary>
<br/>

Built for the SBI Banking AI Hackathon 2026. A banking-outreach system where an LLM agent looks at a synthetic customer's data, decides if/how to reach out, and either auto-sends an email or flags it for human review.

| | |
|---|---|
| **Stack** | FastAPI, SQLite, React/Vite/TypeScript, Groq LLM, n8n, WebSocket |
| **Status** | Submitted, backend live on Render, frontend live on Vercel |
| **What it does** | 4-step agent flow (Investigate → Decide → Draft → Validate), basic RAG for policy lookup, real email delivery tested end-to-end |

Spent a lot of this project debugging — WebSocket message issues, broken email payloads, an LLM model getting deprecated mid-project, and accidentally committing a 200MB virtual environment folder to git.

</details>

<br/>

<details>
<summary><b>🎓 SyncSphere — Campus Social Platform</b></summary>
<br/>

A 2nd-year college project — a campus-only social app combining a LinkedIn-style networking feed with peer-matching for hackathons/group work and a club discovery feature.

| | |
|---|---|
| **Stack** | React Native, Node.js, MongoDB, Firebase |
| **Status** | Built as a Project-Based Learning (PBL) submission |

</details>

<br/>

<details>
<summary><b>🗂️ EventVault — Event Management System</b></summary>
<br/>

A CRUD-based system for college admins to create and manage events — registration, prize pool tracking, and event metadata.

| | |
|---|---|
| **Stack** | Node.js, Express, MySQL, REST API |
| **Status** | College project, functional CRUD system |

</details>

<br/>

---

## ⚙️ Positions of Responsibility

*(Campus roles)*

**Senior Coordinator – Promotions** · IEEE Computer Society, MUJ
`2025 – 2026`
Handled promotional outreach for IEEE CS chapter events on campus.

**Joint Head – Curations** · E-Cell MUJ
`2025 – 2026`
Helped source and curate startup pitches and speaker sessions for E-Cell events.

**Core Member** · MUJ HackX & Genesis 4.0
`2025`
Coordinated day-of operations and helped curate judges for a campus hackathon.

**Campus Ambassador** · Techfest IIT Bombay | E-Summit IIT Delhi
`2025`
Represented these events on campus, helped drive student registrations.

<br/>

---

## ⚙️ Certifications

<div align="center">

**Red Hat**
<br/>
<img src="https://img.shields.io/badge/RHEL%20Automation%20with%20Ansible%209.0-EE0000?style=flat-square&logo=redhat&logoColor=white" />
<img src="https://img.shields.io/badge/Red%20Hat%20System%20Administration%20II%209.3-EE0000?style=flat-square&logo=redhat&logoColor=white" />

<br/><br/>

**Cisco**
<br/>
<img src="https://img.shields.io/badge/CCNA%3A%20Introduction%20to%20Networks-1BA0D7?style=flat-square&logo=cisco&logoColor=white" />
<img src="https://img.shields.io/badge/CCNA%3A%20Switching%2C%20Routing%20%26%20Wireless%20Essentials-1BA0D7?style=flat-square&logo=cisco&logoColor=white" />

<br/><br/>

**Coursera**
<br/>
<img src="https://img.shields.io/badge/Prompt%20Engineering-0056D2?style=flat-square&logo=coursera&logoColor=white" />

<br/><br/>

**Anthropic**
<br/>
<img src="https://img.shields.io/badge/Claude%20Code%20in%20Action-D97757?style=flat-square&logo=anthropic&logoColor=white" />

</div>

<br/>

---

## ⚙️ GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=raikwarxdev&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=0ea5e9&text_color=94a3b8" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=raikwarxdev&theme=github-dark-blue&hide_border=true&background=0d1117&ring=0ea5e9&fire=38bdf8&currStreakLabel=94a3b8" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=raikwarxdev&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8" />

</div>

<br/>

---

## ⚙️ Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=raikwarxdev&theme=github-dark&hide_border=true&bg_color=0d1117&color=38bdf8&line=0ea5e9&point=94a3b8" />

</div>

<br/>

---

## ⚙️ Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/raikwarxdev/raikwarxdev/output/github-contribution-grid-snake-dark.svg" />

</div>

> Generated via [Platane/snk](https://github.com/Platane/snk) GitHub Action.

<br/>

---

## ⚙️ Right Now

```yaml
right_now:
  learning:
    - DSA fundamentals
    - Understanding the systems I've been building well enough to explain them without help
  building:
    - GitGravity — still iterating (animations, SuperCard system, admin dashboard)
  focus:
    - Getting better at DSA before internship season
```

<br/>

---

## ⚙️ Connect

<div align="center">

<a href="mailto:dev.1806raikwar21@gmail.com"><img src="https://img.shields.io/badge/Gmail-dev.1806raikwar21%40gmail.com-0891b2?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/dev-kumar-raikwar-x7"><img src="https://img.shields.io/badge/LinkedIn-dev--kumar--raikwar--x7-0369a1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/raikwarxdev"><img src="https://img.shields.io/badge/GitHub-raikwarxdev-155e75?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://gitgravity.vercel.app"><img src="https://img.shields.io/badge/Project-gitgravity.vercel.app-0284c7?style=for-the-badge&logo=vercel&logoColor=white" /></a>

</div>

<br/>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:1e3a5f,100:0f172a&height=130&section=footer" />

</div>
