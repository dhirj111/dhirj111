<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=200&section=header&text=Dhiraj%20Patel&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20Backend%20Engineering%20%7C%20AI-Powered%20Products&descSize=18&descAlignY=60" alt="Dhiraj Patel banner" width="100%"/>

<a href="https://github.com/dhirj111">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2563EB&center=true&vCenter=true&width=720&lines=Building+scalable+APIs+and+data-heavy+backends;Shipping+AI-powered+developer+products;49.8M%2B+records+indexed+and+queryable+in+PostgreSQL;From+idea+%E2%86%92+deployed+on+Linux+%2B+Nginx" alt="Typing animation"/>
</a>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-dhirj111-181717?style=for-the-badge&logo=github)](https://github.com/dhirj111)
[![ModernLeet](https://img.shields.io/badge/Live-ModernLeet-2563EB?style=for-the-badge&logo=vite&logoColor=white)](https://modernleet.com)
[![CellDataEngine](https://img.shields.io/badge/Live-CellDataEngine-0891B2?style=for-the-badge&logo=postgresql&logoColor=white)](https://celldataengine.com)
![Profile views](https://komarev.com/ghpvc/?username=dhirj111&label=Profile%20views&color=2563eb&style=for-the-badge)

</div>

---

## 👨‍💻 About

I'm a **full-stack developer** who is happiest on the backend — designing REST APIs, modelling data, and making large datasets fast to query. I build and run products end to end: from the React interface to the database, and all the way to the Linux server and Nginx config that serves it.

```text
🔭 Focus        →  Backend engineering · system design · AI-powered products
⚙️  Day to day   →  Node.js / Express · TypeScript · React · MongoDB · PostgreSQL · MySQL
🤖 AI           →  LLM integration (LLaMA, Gemini, OpenAI) inside real product workflows
☁️  Ops          →  Oracle Cloud · Linux · Nginx · Docker
🚢 Shipping     →  Two live production sites (links below)
```

---

## 🚀 Live Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [ModernLeet](https://modernleet.com)
**AI-powered coding practice platform**

A LeetCode-style environment where you solve problems in an in-browser editor and get **AI-assisted code review** on your solution.

- CodeMirror-based interactive coding interface
- APIs for questions and test-case execution
- Code reviews from **LLaMA 3.1-8B** via Inference.net
- JWT auth, **email OTP verification**, password recovery
- Dedicated coding and challenge sections, fully responsive

`React` `Vite` `Node.js` `Express` `MongoDB` `JWT` `LLaMA`

[🌐 Visit site](https://modernleet.com)

</td>
<td width="50%" valign="top">

### 📡 [CellDataEngine](https://celldataengine.com)
**Global cell-tower intelligence platform**

A geospatial data platform for looking up cellular towers by network identifiers or by coordinates, built on a large, cleaned, deduplicated dataset.

- Normalized **~16 GB** of tower datasets from multiple sources
- Imported and deduplicated **49.8M+ records** in PostgreSQL
- Composite-key data organization with indexed lookups
- Query services for network identifiers and coordinate search
- Deployed on **Oracle Cloud** behind **Nginx**

`Node.js` `Express` `PostgreSQL` `SQL` `Oracle Cloud` `Nginx` `Linux`

[🌐 Visit site](https://celldataengine.com)

</td>
</tr>
</table>

### 🔎 How ModernLeet works

```mermaid
flowchart LR
    U([👤 Learner]) --> F[⚛️ React + Vite<br/>CodeMirror editor]
    F -->|REST + JWT| B[🟢 Express API]
    B --> D[(🍃 MongoDB<br/>users · problems)]
    B --> T[🧪 Test-case<br/>execution]
    B -->|solution + results| L[🤖 LLaMA 3.1-8B<br/>via Inference.net]
    L -->|AI code review| B
    B --> F
```

### 🗺️ How CellDataEngine works

```mermaid
flowchart LR
    S1[(Raw tower<br/>datasets ~16 GB)] --> N[🧹 Normalize<br/>and deduplicate]
    N --> P[(🐘 PostgreSQL<br/>49.8M+ records<br/>composite-key indexes)]
    C([Client]) --> X[🌐 Nginx]
    X --> A[🟢 Express query service]
    A -->|identifier lookup<br/>coordinate search| P
```

---

## 🧩 More Work

| Project | What it demonstrates | Stack |
|---|---|---|
| [**WowCalorie**](https://github.com/dhirj111/wowcalorie) | Relational modelling of users and dishes, secure auth, image upload pipeline | Express · Sequelize · MySQL · JWT · bcrypt · Multer · Cloudinary |
| [**GroupChat**](https://github.com/dhirj111/groupchat) | Real-time messaging with room-based groups and membership models | Express · Socket.IO · Sequelize · MySQL · JWT |

> 📦 Browse all public repositories on [**github.com/dhirj111**](https://github.com/dhirj111?tab=repositories).

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technologies |
|:---|:---|
| **Languages** | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **Databases** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white) |
| **AI / LLMs** | ![LLaMA](https://img.shields.io/badge/LLaMA_3.1-0467DF?style=flat-square&logo=meta&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |
| **DevOps & Tools** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

</div>

---

## 💡 What I Bring

- **Data at scale** — cleaning, deduplicating and indexing tens of millions of rows so lookups stay fast.
- **API craftsmanship** — clean REST design, JWT auth and authorization, OTP flows, and sensible error handling.
- **AI in production** — wiring LLMs into real user flows (code review), not just demos.
- **Real-time systems** — Socket.IO rooms, membership models and persistent message history.
- **Ownership of the full path** — schema → API → UI → server → domain → Nginx.

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=dhirj111&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhirj111&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=dhirj111&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dhirj111&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" width="100%"/>

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm open to backend and full-stack opportunities, and to interesting collaborations.
The best way to reach me is through GitHub — open an issue or follow along.

[![Follow on GitHub](https://img.shields.io/badge/Follow-@dhirj111-181717?style=for-the-badge&logo=github)](https://github.com/dhirj111)
[![See ModernLeet](https://img.shields.io/badge/See-ModernLeet-2563EB?style=for-the-badge)](https://modernleet.com)
[![See CellDataEngine](https://img.shields.io/badge/See-CellDataEngine-0891B2?style=for-the-badge)](https://celldataengine.com)

<br/>

*Building, learning, and solving real-world problems through code.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1d4ed8,100:0f172a&height=100&section=footer" alt="Footer" width="100%"/>

</div>
