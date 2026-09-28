<p align="center">
  <a href="https://omar-argenes.netlify.app/">
    <img src="assets/banner.svg" alt="Omar Argenes Quispe — Web Systems Engineer · Angular · PHP · WordPress · Linux in production · AI-assisted debugging" width="100%" />
  </a>
</p>

<p align="center"><b>I build web systems, ship them to production and keep them running.</b></p>

<p align="center">
  <a href="https://omar-argenes.netlify.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-omar--argenes.netlify.app-5ee7ff?style=flat-square&logo=netlify&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/omar-argenes-quispe"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-omar--argenes--quispe-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://orcid.org/0009-0009-7371-1384"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0009--0009--7371--1384-A6CE39?style=flat-square&logo=orcid&logoColor=white" /></a>
  <a href="mailto:argenes77@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-argenes77%40gmail.com-8b7bff?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

### 👋 About

Systems Engineer (UMSS, Bolivia) working remotely for clients in Germany. My work sits where development meets operations: I build **Angular** applications, customize **WordPress** platforms with **PHP and JavaScript**, and take care of **deployments, SSL, caching and incident response** on Linux servers. I use **AI coding agents** as part of a controlled, evidence-based workflow.

- 🏢 **Currently:** Web Systems Engineer at **pirAMide Informatik GmbH** (Hamburg · remote, 2024 – present)
- 🧪 **Research:** author of [Debugging for Instances (DFI)](https://github.com/OmarArgenes/debugging-for-instances), an evidence-based method for AI-assisted debugging ([DOI](https://doi.org/10.5281/zenodo.22986103))
- 🌎 Cochabamba, Bolivia · UTC-4 · Spanish (native), English (B1)

---

### 🅰️ Angular

I have worked with Angular 17, 19 and 22 across company and personal projects.

| | |
|---|---|
| **Architecture** | Standalone components · zoneless change detection · domain-oriented folder structure · route-level lazy loading · route guards |
| **Rendering** | Server-side rendering and prerendering with `@angular/ssr` |
| **Design systems** | Shared UI libraries built with `ng-packagr` · SCSS design tokens · responsive layouts |
| **Quality** | TypeScript strict mode · Vitest · Prettier · accessibility targets (WCAG 2.2 AA) · Core Web Vitals targets |
| **Data** | RxJS services · REST APIs · Supabase (PostgreSQL + Auth) |
| **UI libraries** | PrimeNG · PrimeFlex · Bootstrap |
| **i18n** | ngx-translate — multilingual interfaces and language selectors |

---

### 🤖 AI-assisted engineering

> *AI proposes. Evidence decides. The engineer controls.* — core principle of DFI

- **AI coding agents in real repositories**, guided by repository-level instructions (`AGENTS.md`, `CLAUDE.md`) and written AI guidelines that define what an agent may and may not change.
- **Angular CLI MCP server** connected to the agent, so it works with the project's real tooling instead of guessing.
- **Evidence-based debugging with AI** — hypotheses are tested against what the system actually does before any fix is applied. I formalized this approach as [DFI](https://github.com/OmarArgenes/debugging-for-instances).
- **Human review stays in charge:** small changes, feature branches and verification after every change.

---

### 🏢 Current work at pirAMide Informatik

> Source code for this work is private because it belongs to my employer and its clients.
> Each project below links to a showcase repository with scope, architecture and my role — no source code. More write-ups: **[engineering-case-studies](https://github.com/OmarArgenes/engineering-case-studies)**.

| Area | What I do | Stack |
|---|---|---|
| **[Angular migration](https://github.com/OmarArgenes/piramide-angular-migration-showcase)** | Migrating a corporate website to a modern Angular application, preserving public URLs and visual baseline while improving maintainability, performance, accessibility and SEO | Angular 22 · SSR · TypeScript · SCSS · Vitest |
| **[Modern website redesign](https://github.com/OmarArgenes/piramide-modern-website-showcase)** | Redesign work: design system with tokens, responsive layouts, documented quality standards | Angular · TypeScript · SCSS |
| **[Business Manager platform](https://github.com/OmarArgenes/bm-platform-showcase)** | Product website, shared UI library and CRM interface concept for the company's business-management platform | Angular · SSR · ng-packagr |
| **WordPress development & operations** | Development, maintenance and support of **15+ client websites and web apps** across staging and production | WordPress · WooCommerce · BuddyBoss · LearnDash · PHP · JS |
| **Web operations** | Staging → production deployments, backups, SSL, caching, permissions and production incident resolution | Debian · Plesk · Nginx · PHP-FPM |

---

### 🤝 Verified contributions to team repositories

> Source code remains in the official repositories. Everything below links to public, merged pull requests — no code is redistributed here.

#### pirAMide Informatik GmbH — IWS Manager
[`Piramide-Informatik/iws-manager-webapp`](https://github.com/Piramide-Informatik/iws-manager-webapp) · **22 merged pull requests** · March – June 2025

Enterprise management web application. I built CRUD screens, data tables and navigation for the frontend.

**Stack:** Angular 19 · TypeScript · PrimeNG · Reactive Forms · ngx-translate · PrimeFlex

**What I worked on:** 10 master-data screens (users, roles, absence types, holidays, funding programs, IWS staff, commissions, teams, countries, costs) · work contracts, invoices and subcontracts modules · data tables with sorting, pagination, column filters and multiselect filters · form validation · multilingual UI and language selector · grouped master-data navigation menu

| PR | Contribution |
|---|---|
| [#16](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/16) | Work contracts table — PrimeNG table with sorting, global filter and dialogs |
| [#26](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/26) | Translation support and language selector (ngx-translate) |
| [#47](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/47) | Invoices table and improved language selection panel |
| [#55](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/55) | Subcontracting details — Reactive Forms with validation and related tables |
| [#95](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/95) | Grouped master-data navigation menu |
| [#101](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/101) | User management UI |
| [#139](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/139) | Funding programs UI |
| [#155](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/155) | IWS staff UI |
| [#179](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/179) | Countries, costs, teams and commissions screens |
| [#396](https://github.com/Piramide-Informatik/iws-manager-webapp/pull/396) | Scrolling fix applied across all data tables |

#### LabDev INFSIS (UMSS) — Social platform
Team project of the Department of Informatics and Systems, Universidad Mayor de San Simón · November 2024 – May 2025

**Frontend** · [`pagina-web-social-frontend`](https://github.com/labdev-infsis/pagina-web-social-frontend) · **8 merged PRs** · Angular 17 · TypeScript · Bootstrap

| PR | Contribution |
|---|---|
| [#21](https://github.com/labdev-infsis/pagina-web-social-frontend/pull/21) | Commenting on posts |
| [#33](https://github.com/labdev-infsis/pagina-web-social-frontend/pull/33) | Emoji reactions on comments |
| [#50](https://github.com/labdev-infsis/pagina-web-social-frontend/pull/50) | Replies UX — descending order, auto-focus on reply, show more / show less, consistent date format |
| [#53](https://github.com/labdev-infsis/pagina-web-social-frontend/pull/53) | Replying to comments, including nested replies |
| [#55](https://github.com/labdev-infsis/pagina-web-social-frontend/pull/55) | Reactions component and refactor of comments and replies |

**Backend** · [`pagina-web-social-backend`](https://github.com/labdev-infsis/pagina-web-social-backend) · **6 merged PRs** · Java 17 · Spring Boot 3 · Spring Data JPA

| PR | Contribution |
|---|---|
| [#23](https://github.com/labdev-infsis/pagina-web-social-backend/pull/23) | Search posts by text — controller, service, repository query, DTO and mapper |
| [#60](https://github.com/labdev-infsis/pagina-web-social-backend/pull/60) | Paginated post listing in batches of 10 (`Pageable`) |
| [#62](https://github.com/labdev-infsis/pagina-web-social-backend/pull/62) | Posts ordered by date with pagination |
| [#66](https://github.com/labdev-infsis/pagina-web-social-backend/pull/66) | Nested replies — self-referencing JPA relationship, JPQL query for top-level replies and reply-tree building |
| [#68](https://github.com/labdev-infsis/pagina-web-social-backend/pull/68) | Emoji reactions on replies — controller, service, repository, DTOs and mappers |

---

### ⭐ Featured projects

| Project | Description | Stack | Links |
|---|---|---|---|
| **[Debugging for Instances (DFI)](https://github.com/OmarArgenes/debugging-for-instances)** | Methodological framework for AI-assisted, evidence-based software diagnosis — falsifiable hypotheses, controlled instrumentation and verified fixes | Methodology · JSON Schema · JS | [Paper (Zenodo)](https://zenodo.org/records/22986103) |
| **[Engineering Case Studies](https://github.com/OmarArgenes/engineering-case-studies)** | Public-safe write-ups of professional work: Angular migration, design systems, B2B product frontend and a production incident | Angular · SSR · PHP-FPM | — |
| **[Personal Portfolio](https://github.com/OmarArgenes/portfolio-showcase)** | Bilingual portfolio hand-built with a WebGL aurora background, a 3D globe on canvas and animated SVG diagrams | HTML · CSS · Vanilla JS · WebGL | [Live](https://omar-argenes.netlify.app/) |
| **[Automotive Workshop System](https://github.com/OmarArgenes/mecanica-automotriz-web)** | Management system for an automotive repair shop: customers, vehicles, intake inspection, work orders, parts requests and printable documents | Angular 19 · TypeScript · Supabase · PostgreSQL · Netlify | [Live](https://zcanedo.netlify.app/) |

---

### 🧰 Skills

**Frontend** &nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![PrimeNG](https://img.shields.io/badge/PrimeNG-DD0031?style=flat-square)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

**Backend & data** &nbsp;
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-555?style=flat-square)
![JSON](https://img.shields.io/badge/JSON-000?style=flat-square&logo=json&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)

**WordPress ecosystem** &nbsp;
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-92003B?style=flat-square&logo=elementor&logoColor=white)
![Divi](https://img.shields.io/badge/Divi-7A3EE8?style=flat-square)
![WPBakery](https://img.shields.io/badge/WPBakery-0473AA?style=flat-square)
<br />WooCommerce Memberships & Subscriptions · BuddyBoss · LearnDash · Modern Events Calendar · WP Job Manager · custom themes, plugins, shortcodes, forms, roles & permissions

**Operations** &nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Plesk](https://img.shields.io/badge/Plesk-52BBE6?style=flat-square&logo=plesk&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
<br />Staging → production · DNS · SSL · backups · caching · PHP-FPM / OPcache · file permissions · post-deployment QA

**AI & methods** &nbsp;
![AI coding agents](https://img.shields.io/badge/AI_coding_agents-8b7bff?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-555?style=flat-square)
![DFI](https://img.shields.io/badge/DFI-evidence--based_debugging-5ee7ff?style=flat-square)
<br />Prompt engineering · root cause analysis · Scrum · OKR · Design Thinking

**IT foundations:** 10+ years of hardware, software and network support — Windows/Linux, LAN/Wi-Fi, routers, peripherals, data recovery, malware removal and end-user support.

**Working knowledge:** React · Node.js · Laravel · Docker · Python · Power BI

---

### 🔎 How I work

- **Evidence before fixes.** I debug by forming hypotheses and testing them against what the system actually does.
- **Production is part of the job.** Backups before changes, staging before production, verification after every deployment.
- **Small, reviewable changes.** Feature branches, pull requests and descriptive commits.
- **Documentation first.** Architecture, standards and decisions are written down before implementation starts.

---

<p align="center">
  <sub>Open to remote roles · <a href="https://omar-argenes.netlify.app/">omar-argenes.netlify.app</a></sub>
</p>
