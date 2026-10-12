<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=3b82f6&center=true&vCenter=true&width=650&lines=Backend+Engineer;Cloud+%26+Infrastructure;Event-Driven+Systems;Node.js+%C2%B7+PostgreSQL+%C2%B7+AWS" alt="Typing SVG" />
  </a>
</h1>

---

### About

Backend-focused Computer Engineering student ('27), building systems that ship. I work primarily in **Node.js**, **PostgreSQL**, and **AWS** — from event-driven architectures to infrastructure analyzers. I care about clean interfaces, real test coverage, and doing the small things right.

- 🔭 Deepening my work in **distributed systems** and **cloud infrastructure**
- 🌱 Exploring **AI integration** and **system design patterns**
- 📫 Reach me at **aniruddhanalawade1234@gmail.com**

---

### Tech Stack

**Languages**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />

**Backend & APIs**
<br/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />

**Databases**
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />

**Cloud & Infrastructure**
<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" />
<img src="https://img.shields.io/badge/CloudFormation-FF4F00?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" />

**Frontend**
<br/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />

**Tools**
<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />

---

### 🚧 Currently Working On

#### 🦈 SmartShark
*Virtual Shark Tank platform — businesses pitch for investment, investors match and make offers.*

**Stack:** Node.js · Express · PostgreSQL · MongoDB · Redis · React · Drizzle ORM

**Highlights:**
- 60+ REST endpoints · 570+ tests running in CI
- Event-driven architecture with a self-maintaining registry (unknown event types are recorded, not dropped)
- OCR verification pipeline for Udyam, GST, and Shop Act documents
- Redis-cached investor feed populated with 788 real businesses
- Deployed on Render with health checks, structured logging, and graceful shutdown

[API Docs](https://smartshark.onrender.com/docs) · [Repository](https://github.com/aniruddha9674/smartshark)

---

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### ☁️ IaC Visualizer
*CloudFormation blast radius analyzer — traces downstream impact of template changes.*

**Stack:** Node.js · React · AWS Lambda · API Gateway · Bedrock · SAM

**Highlights:**
- Reverse-BFS blast radius computation beyond single-resource linters
- Intrinsic-tag walker (Ref, GetAtt, Sub, DependsOn) with 8 deterministic rules
- Cross-resource IAM check for unreachable S3 references
- Bedrock Nova Micro narration downstream of the rule engine
- 16 tests in CI · Deployed on Vercel

[Live](https://iac-visualizer.vercel.app/) · [Repository](https://github.com/aniruddha9674/iac-visualizer)

</td>
<td width="50%" valign="top">

#### 📦 Invennzy
*Inventory & business management platform used daily by a pilot lab.*

**Stack:** Node.js · Express · MySQL · React · Cloudinary

**Highlights:**
- Three-tier RBAC (Admin, Manager, Staff) via JWT middleware
- Billing query optimized from full scan → index range scan (EXPLAIN verified)
- Cloudinary-backed PDF generation for invoices
- Modular backend routers for billing, inventory, and orders

[Live](https://invennzy.com) · [Repository](https://github.com/aniruddha9674/Invennzy)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎓 Gradyze
*Academic management platform with role-based dashboards for admins, teachers, and students.*

**Stack:** React · Node.js · Express · MongoDB · JWT

**Highlights:**
- Three separate login flows (Admin, Teacher, Student) with JWT auth
- Protected admin workspace guarded by `PrivateRoute`
- Modular academic tools served from a dashboard menu
- Public marketing site with feature, pricing, and testimonial sections

[Live](https://gradyze.com) · [Repository](https://github.com/aniruddha9674/gradyze)

</td>
<td width="50%" valign="top">

#### 🎨 Pixel
*Modern pixel-art editor with a cinematic intro.*

**Stack:** React · TypeScript · Vite

**Highlights:**
- Custom canvas rendering pipeline
- Cinematic intro animations
- Componentized tool palette

[Live](https://www.pixelcraftpccoer.in/) · [Repository](https://github.com/aniruddha9674/Pixel)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ♟️ BlunderZero
*Chess engine with adaptive difficulty.*

**Stack:** Python · FastAPI

**Highlights:**
- Depth-limited minimax with alpha-beta pruning
- Three difficulty levels mapped to search depths
- Tactical pattern detection: fork, pin, skewer, discovered attack
- Tested against human play at all three levels

[Repository](https://github.com/aniruddha9674/blunderzero)

</td>
<td width="50%" valign="top">

#### 🌐 Personal Site
*Portfolio and project showcase.*

**Stack:** HTML · CSS

[Live](https://aniruddha9674.github.io) · [Repository](https://github.com/aniruddha9674/aniruddha9674.github.io)

</td>
</tr>
</table>

---

### Experience

**Software Developer Intern** · Prudent Agency · 2025
*Node.js · PostgreSQL · Instagram Graph API · YouTube Data API*

- Built a **Campaign Report Analyzer** replacing a manual CSV workflow — pulls ad performance data daily into PostgreSQL
- Wrote the API integration layer handling auth, pagination, and retries without duplicate ingestion
- Implemented ad metrics (CTR, CPR, ROAS, net revenue) for the daily profitability report

---

### Certifications

| Certification | Issuer | Year |
|---|---|---|
| Oracle Database Programming with SQL | Oracle Academy | 2025 |
| MongoDB Data Modeling | MongoDB University | 2025 |
| AWS Academy Graduate — Cloud Foundations | AWS | 2026 |

---

### GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=aniruddha9674&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=3b82f6&icon_color=3b82f6&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniruddha9674&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=3b82f6&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aniruddha9674&theme=dark&hide_border=true&background=0d1117&ring=3b82f6&fire=3b82f6&currStreakLabel=3b82f6" alt="GitHub Streak" />
</p>
