# Léo FAUQUEMBERGUE - Développeur Full Stack ✨

**HEY !** 👾

Issu d'un cursus STAPS et d'un Master MEEF EPS, j'ai multiplié les expériences de terrain en encadrement et en pédagogie — dont un stage long et formateur — avant de me reconvertir dans le développement. J'en garde la rigueur, le goût du travail en équipe et l'habitude de **décomposer le complexe en étapes claires** : une logique qui sert autant à transmettre qu'à concevoir une architecture.

Aujourd'hui, je conçois des applications web pensées pour être **robustes, sécurisées et maintenables**.

---

### 🎯 Ce que je recherche : Alternance Bac+4/5 ou CDI

Titulaire des titres **DWWM** (Niveau 5) et **CDA** (Niveau 6) obtenus chez O'clock, et après un stage en développement mobile chez MIS Group, je recherche actuellement une **alternance en formation Bac+4/5** ou un **poste de Développeur Full Stack en CDI**.

---

### 📌 Projets Phares

#### 🐾 PetFosterConnect — Mise en relation refuges / familles d'accueil · CDA (Niveau 6)

💻 **[Code source](https://github.com/Leo-Fauquembergue/PetFosterConnect)**
**Stack :** TypeScript · React · NestJS · PostgreSQL · Prisma

![Aperçu de PetFosterConnect](https://github.com/user-attachments/assets/e30e3125-9aae-47e0-ba87-c75ae4413e55)

> Réalisé en équipe Agile (rôle Product Owner + dev full stack), puis perfectionné en totale autonomie.
> Authentification JWT double token, RBAC avec héritage des rôles, conformité RGPD et CI/CD complet de bout en bout.

<details>
<summary>🔧 <strong>Détails techniques</strong></summary>
<br>

- **🏗️ Architecture & Données :** BDD PostgreSQL modélisée via Prisma (Schema-First, migrations). RBAC avec héritage des rôles, protection IDOR via guards personnalisés (`@CheckOwner`) et Soft Delete pour la conformité RGPD (droit à l'oubli).
- **🛡️ Backend (NestJS) :** API RESTful modulaire documentée Swagger. Authentification JWT Double Token (Access/Refresh), hachage Argon2, middleware CSRF personnalisé, rate limiting et validation Zod bout-en-bout. Transactions ACID Serializable (`$transaction`) pour prévenir les race conditions. Notifications asynchrones Nodemailer + Handlebars (pattern Fire-and-Forget).
- **🎨 Frontend (TypeScript / React) :** SPA Mobile-First avec Vite. Formulaires React Hook Form + Zod, hook `useFetch` avec `AbortController` (annulation réseau, prévention des memory leaks). Algorithme de matching calculant la compatibilité adoptant/animal en temps réel. Export PDF des fiches avec QR Code. Accessibilité (WCAG / A11Y) native.
- **🚀 Qualité & DevOps :** Monorepo npm workspaces avec typage End-to-End (`@projet/shared-types`). Biome pour la qualité de code. Pipeline CI/CD GitHub Actions (Jest, Vitest, PostgreSQL éphémère, branch protection rules). Docker (conteneur CI + dev local). Déploiement continu sur architecture découplée : backend sur Render, frontend sur Vercel.

</details>

#### 🌳 GreenRoots — Plateforme e-commerce de reforestation · DWWM (Niveau 5)

💻 **[Code source](https://github.com/Leo-Fauquembergue/GreenRoots)**
**Stack :** TypeScript · React · Node.js · Express · PostgreSQL · Sequelize

![Aperçu de GreenRoots](https://github.com/user-attachments/assets/9fcf6772-f9ef-4452-8d3e-476ab54de9e9)

> Réalisé en équipe Agile (rôle lead back-end + dev full stack).
> Architecture MVC, sécurité guidée par l'OWASP Top 10, tunnel d'achat complet et panel d'administration.

<details>
<summary>🔧 <strong>Détails techniques</strong></summary>
<br>

- **🏗️ Architecture & Données :** BDD PostgreSQL modélisée via Sequelize (MLD, migrations, seeding automatisé). RBAC via middlewares dédiés (`isAuthenticated`, `isAdmin`) et conformité RGPD intégrée (pages légales et politique de confidentialité via les outils CNIL).
- **🛡️ Backend (Node / Express) :** API RESTful modulaire en architecture MVC. Authentification par sessions persistantes en BDD (`express-session`), hachage Argon2, validation Zod et protection XSS (`express-xss-sanitizer`). Sécurité guidée par l'OWASP Top 10 : CORS, scopes Sequelize pour l'exposition contrôlée des données sensibles. Logique métier de panier persistant (statut Order) avec tunnel d'achat complet.
- **🎨 Frontend (TypeScript / React) :** SPA Mobile-First avec Vite. Gestion d'état globale via React Context API (`AuthContext`, `CartContext`). Design system Tailwind CSS + SCSS. Panel d'administration complet (catalogue, commandes, suivi des arbres plantés).
- **🚀 Qualité & Déploiement :** Monorepo PNPM avec qualité de code unifiée via Biome. Revues de code systématiques (Pull Requests). BDD conteneurisée avec Docker Compose en développement. Déploiement continu sur architecture découplée : backend sur Render, frontend sur Vercel.

</details>

---

### 💻 Stack Technique

#### Langages & Fondamentaux
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)

#### Backend & API
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Zod](https://img.shields.io/badge/zod-3068b7?style=for-the-badge&logo=zod&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%231B5E20?style=for-the-badge&logo=swagger&logoColor=white)

#### Frontend & Mobile
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-%23000000.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

#### Tests
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/-Vitest-252529?style=for-the-badge&logo=vitest&logoColor=FCC72B)

#### Bases de données & DevOps
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=Prisma&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

#### Méthodologies & Outils
![Agile](https://img.shields.io/badge/Agile-FF6B35?style=for-the-badge&logo=atlassian&logoColor=white)
![Scrum](https://img.shields.io/badge/Scrum-009639?style=for-the-badge&logo=jira&logoColor=white)
![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Biome](https://img.shields.io/badge/biome-60A5FA?style=for-the-badge&logo=biome&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

---

### 💬 Parlons-en !

Je suis toujours ouvert à la discussion. N'hésitez pas à me contacter pour parler de :
- Conception d'API REST et modélisation de bases de données.
- Développement d'applications web ou mobiles avec TypeScript, React et Node.
- Opportunités d'alternance Bac+4/5 ou de poste en CDI.

<div align="center">
  <i>...et oui, je maîtrise aussi l'art du <code>div</code> centré. 😎</i>
</div>

---

### 🌐 Réseaux Sociaux & Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/leo-fauquembergue)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:leo.fau1708@gmail.com)

---

### 📊 Mes Statistiques GitHub

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Leo-Fauquembergue&theme=vision-friendly-dark&hide_border=true" alt="Statistiques de commits" />
</p>

---

### ✍️ Citation de Développeur Aléatoire

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Citation de développeur" />
</p>
