<h1 align="center">Ujjawal Bansal</h1>

<p align="center">
  Full-stack developer · Final-year CS student at ABES Engineering College, Ghaziabad
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ujjawalbansal">LinkedIn</a> ·
  <a href="https://x.com/Ujjawal__Bansal">X</a> ·
  <a href="mailto:ujjawalbansal63@gmail.com">Email</a> ·
  <a href="https://github.com/ujjawal-bansal">GitHub</a>
</p>

---

## About

I build software that ends up in front of real users. Right now that means **QueueLite**, an OPD queue management system running in production at a clinic in Moradabad and handling 30–40 patients a day, and **Lexora AI**, a multi-stage LLM pipeline for essay grading and feedback.

- Final-year Computer Science student, graduating 2026
- Core Organizer of **Stellaris 2026**, a pan-India hackathon with 1,600+ registrations, a $19,000 prize pool, and GitHub as gold sponsor
- Content Lead at the GeeksforGeeks ABES Student Chapter
- AWS Academy Cloud Foundations certified
- Java for data structures and algorithms, TypeScript for everything else
- Interested in real-time systems, Postgres internals, and taking side projects all the way to production

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend and Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Tools and Cloud**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## Selected Work

### QueueLite — in production
Real-time OPD queue management for small Indian clinics. Live at Dev Eye Care, Moradabad, serving 30–40 patients daily.

- Live queue updates over Socket.IO with a polling fallback for dropped connections
- Daily-resetting token numbers made race-safe using PostgreSQL advisory locks
- Role-based staff dashboard with JWT authentication and clinic-scoped access control for multi-clinic data isolation

`Node.js` · `React` · `PostgreSQL` · `Supabase` · `Socket.IO`

### Lexora AI
An essay feedback pipeline that grades submissions, flags mistakes with exact quotes, and generates personalized practice questions.

- Three-stage architecture with isolated model calls per stage
- Zod validation with `z.infer<>`-derived types across every AI boundary, so unvalidated or hallucinated output never reaches the database
- Fixed eight-category mistake taxonomy enforced in both Postgres constraints and TypeScript unions, with deterministic routing in app logic (grammar to MCQ, structure to short response)

`SvelteKit` · `TypeScript` · `PostgreSQL` · `Groq`

### Savoney
A personal finance tracker covering transactions, budgets, and spending analytics.

- Five REST resource groups (auth, transactions, categories, budgets, analytics) built with Express and Mongoose
- JWT authentication with protected routes and persistent session restore
- Analytics dashboards built with Recharts for spending trends and budget progress

`MongoDB` · `Express` · `React` · `Node.js`

---

## GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ujjawal-bansal&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ujjawal-bansal&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top languages" />
</p>

---

<p align="center">
  Open to full-time software engineering roles and interesting collaborations.
</p>
