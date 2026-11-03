<h1 align="center">Hi, I'm Bekzod 👋</h1>
<h3 align="center">Backend-focused Full-Stack Developer · TypeScript · NestJS · PostgreSQL</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Uzbekistan-0EA5E9?style=flat-square" alt="Location" />
  <img src="https://img.shields.io/badge/Company-ELMA-22C55E?style=flat-square" alt="Company" />
  <img src="https://komarev.com/ghpvc/?username=bekzodjs&style=flat-square&color=6366F1" alt="Profile views" />
</p>

---

### 🧑‍💻 About me

- 🏭 I build internal business systems at **ELMA**, a wet-wipes manufacturer in Uzbekistan
- ⚙️ I mostly work on the backend: REST APIs, data modelling, imports from ERP exports, business calculations and access control
- 🚀 I take projects from the database schema to production: Docker, CI/CD, reverse proxy, migrations
- 🌐 I write software for Uzbek- and Russian-speaking users (i18n UZ / RU)

### 🛠 Tech stack

**Backend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)

**DevOps & tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 📌 Featured projects

#### 📦 Packaging & finished-goods accounting system — ELMA *(private, in production)*

Internal system that tracks packaging film and finished-goods stock for logo-printed wet wipes, per customer logo.
It imports monthly ERP (Smartup) Excel reports, calculates average consumption, months of cover, reorder and
production needs, and tied-up money, and gives managers a decision screen and Excel exports.

`NestJS 11` `Prisma 7` `PostgreSQL 16` `React 19` `TanStack Query/Table` `Tailwind 4` `Zod` `Docker` `GitHub Actions`

- All-or-nothing Excel imports in one transaction, compared against the previous month with warnings
- Role-based access plus per-user permissions, with an audit log for sensitive changes
- Unit and PostgreSQL integration tests (Vitest), CI with typecheck, build, migration-drift check and smoke test
- Deployed with Docker behind Nginx and Traefik, migrations applied on container start
- UI in Uzbek and Russian

#### 🚕 [taxiOrder](https://github.com/bekzodjs/taxiOrder) — taxi & truck ordering API

REST API for ordering taxis and cargo trucks: users, drivers, cars, balances, regions and districts, OTP login,
admin panel endpoints and a translation module for multilingual content.

`NestJS` `Prisma` `PostgreSQL` `JWT / Passport` `Swagger` `Cloudinary`

#### 🧴 [elma_original_](https://github.com/bekzodjs/elma_original_) — ELMA product catalog · [live demo](https://elma-catalog.netlify.app)

Company website and product catalog with an admin panel (product CRUD, news, inquiries, dashboard),
UZ / RU language switch and light / dark mode.

`Vue 3` `Vite` `Pinia` `Vue Router`

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=bekzodjs&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=tokyonight" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bekzodjs&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=bekzodjs&hide_border=true&theme=tokyonight" alt="GitHub streak" />
</p>

### 📫 Contact

[![GitHub](https://img.shields.io/badge/GitHub-bekzodjs-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bekzodjs)
