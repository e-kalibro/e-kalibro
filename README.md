<a name="top"></a>
<div align="center">

<img src="https://raw.githubusercontent.com/e-kalibro/e-kalibro/main/Profile.png" width="150" alt="E-Kalibro logo" />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:013D26,100:04663D&height=220&section=header&text=E-KALIBRO&fontSize=72&fontColor=EAB625&fontAlignY=38&animation=fadeIn&desc=Digital%20Library%20Management%20System%20%E2%80%A2%20Metro%20Dagupan%20Colleges&descAlignY=58&descSize=17&descColor=FFFFFF" alt="E-Kalibro banner" />

<a href="https://github.com/e-kalibro/e-kalibro">
  <img src="https://readme-typing-svg.demolab.com/?font=Poppins&weight=600&size=24&duration=3000&pause=1200&color=EAB625&background=00000000&center=true&vCenter=true&width=700&lines=Welcome+to+E-Kalibro;A+Smarter+Library+for+MDC;Built+with+Svelte+4+%E2%9A%A1;Cataloging+%E2%80%A2+Circulation+%E2%80%A2+Insights" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/INSTITUTION-METRO%20DAGUPAN%20COLLEGES-04663D?style=for-the-badge&labelColor=013D26" />
<img src="https://img.shields.io/badge/TYPE-CASE%20STUDY-EAB625?style=for-the-badge&labelColor=013D26" />
<img src="https://img.shields.io/badge/STACK-SVELTE%204-04663D?style=for-the-badge&logo=svelte&logoColor=EAB625&labelColor=013D26" />

<br/>

<img src="https://img.shields.io/github/stars/e-kalibro/e-kalibro?style=for-the-badge&color=EAB625&labelColor=013D26&logo=github&logoColor=white" />
<img src="https://img.shields.io/github/forks/e-kalibro/e-kalibro?style=for-the-badge&color=04663D&labelColor=013D26&logo=github&logoColor=white" />
<img src="https://img.shields.io/github/issues/e-kalibro/e-kalibro?style=for-the-badge&color=EAB625&labelColor=013D26" />
<img src="https://img.shields.io/github/last-commit/e-kalibro/e-kalibro?style=for-the-badge&color=04663D&labelColor=013D26" />
<img src="https://img.shields.io/github/license/e-kalibro/e-kalibro?style=for-the-badge&color=EAB625&labelColor=013D26" />

<br/><br/>

<a href="https://github.com/e-kalibro/e-kalibro/issues/new?labels=bug&title=%5BBUG%5D">
<img src="https://img.shields.io/badge/🐞_Report_Bug-04663D?style=for-the-badge&labelColor=013D26" />
</a>
<a href="https://github.com/e-kalibro/e-kalibro/issues/new?labels=enhancement&title=%5BFEATURE%5D">
<img src="https://img.shields.io/badge/💡_Request_Feature-EAB625?style=for-the-badge&labelColor=013D26" />
</a>
<a href="https://github.com/e-kalibro/e-kalibro/wiki">
<img src="https://img.shields.io/badge/📘_Documentation-04663D?style=for-the-badge&labelColor=013D26" />
</a>

</div>

<br/>

## 📑 Table of Contents

- [Who We Are](#-who-we-are)
- [About the Project](#-about-e-kalibro)
- [Core Features](#-core-features)
- [System Architecture](#-system-architecture)
- [Borrowing Workflow](#-borrowing-workflow)
- [Tech Stack](#-tech-stack)
- [Brand Palette](#-brand-palette)
- [Account Insights](#-account-insights)
- [Roadmap](#-roadmap)
- [Contributors](#-contributors)
- [License](#-license)

<br/>

## 👋 Who We Are

This account is the **official home of E-Kalibro** — it doesn't host a portfolio of unrelated projects, it exists for one purpose: to build, document, and showcase our capstone case study for **Metro Dagupan Colleges**. Everything below — the code, the diagrams, the stats — belongs to this one project.

<br/>

## 📖 About E-Kalibro

**E-Kalibro** is a web-based **Library Management System** developed as an academic case study for **Metro Dagupan Colleges (MDC)**. It reimagines the day-to-day work of running a campus library — cataloging titles, tracking who borrowed what and when it's due, and giving staff the visibility they need — as a fast, focused web app instead of a stack of logbooks and spreadsheets.

Built with **Svelte 4**, E-Kalibro is designed around three people: the **student** who just wants to find a book, the **librarian** who needs the circulation desk to move quickly, and the **administrator** who needs to see the collection from above.

<div align="center">

| | |
|---|---|
| 🏫 **Institution** | Metro Dagupan Colleges |
| 🧩 **Domain** | Library Management System |
| 📁 **Project Type** | Capstone / Case Study |
| ⚙️ **Frontend** | Svelte 4 |
| 📌 **Status** | 🟢 Active Development |

</div>

<br/>

## ✨ Core Features

<table>
<tr>
<td width="50%" valign="top">

### 📖 Catalog Management
Add, edit, and organize MDC's entire collection with rich, searchable metadata.

</td>
<td width="50%" valign="top">

### 🔄 Circulation Desk
Streamlined borrowing, returns, and renewals with real-time copy tracking.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 OPAC Search
A fast, student-facing catalog so anyone can find a title in seconds.

</td>
<td width="50%" valign="top">

### 🔔 Smart Notifications
Automated due-date reminders and overdue alerts for borrowers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛂 Role-Based Access
Tailored views and permissions for students, faculty, librarians, and admins.

</td>
<td width="50%" valign="top">

### 📊 Analytics Dashboard
Borrowing trends and collection insights to support library decisions.

</td>
</tr>
</table>

<br/>

## 🏛️ System Architecture

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#04663D','primaryTextColor':'#ffffff','primaryBorderColor':'#EAB625','lineColor':'#EAB625','secondaryColor':'#013D26','tertiaryColor':'#F7D560','fontSize':'14px'}}}%%
flowchart TD
    S[🎓 Students] --> APP
    F[👨‍🏫 Faculty] --> APP
    L[📚 Librarians] --> APP
    A[🛠️ Admin] --> APP

    APP[E-Kalibro Web App<br/>Svelte 4]

    APP --> M1[📖 Catalog Module]
    APP --> M2[🔄 Circulation Module]
    APP --> M3[🔔 Notification Module]
    APP --> M4[📊 Reports & Analytics]

    M1 --> DB[(MDC Library Database)]
    M2 --> DB
    M3 --> DB
    M4 --> DB
```

<br/>

## 🔄 Borrowing Workflow

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#04663D','primaryTextColor':'#ffffff','primaryBorderColor':'#EAB625','lineColor':'#EAB625','actorBorder':'#04663D','actorBkg':'#EAB625','actorTextColor':'#013D26'}}}%%
sequenceDiagram
    actor Student
    participant App as E-Kalibro
    participant Catalog
    participant Circulation
    participant DB as Database

    Student->>App: Search for a title
    App->>Catalog: Query catalog
    Catalog->>DB: Check availability
    DB-->>Catalog: Status: Available
    Catalog-->>App: Show result
    Student->>App: Request to borrow
    App->>Circulation: Create borrow record
    Circulation->>DB: Update copy status
    DB-->>Circulation: Confirmed
    Circulation-->>Student: Due date issued
```

<br/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=svelte,vite,javascript,html,css,figma,git,github&theme=dark" />

</div>

| Layer | Tools |
|---|---|
| **Frontend** | Svelte 4 · Vite · JavaScript (ES6+) · HTML5 · CSS3 |
| **Design** | Figma (UI/UX prototyping) |
| **Backend & Database** | _add your stack here — e.g. Node.js, Firebase, Supabase, or a REST API_ |
| **Tooling** | Git & GitHub · npm |

<br/>

## 🎨 Brand Palette

Colors lifted directly from the E-Kalibro mark — MDC green and gold.

<div align="center">

| Swatch | Name | Hex |
|---|---|---|
| ![](https://img.shields.io/badge/-04663D?style=flat-square) | MDC Green | `#04663D` |
| ![](https://img.shields.io/badge/-013D26?style=flat-square) | Deep Forest | `#013D26` |
| ![](https://img.shields.io/badge/-EAB625?style=flat-square) | MDC Gold | `#EAB625` |
| ![](https://img.shields.io/badge/-F7D560?style=flat-square) | Light Gold | `#F7D560` |
| ![](https://img.shields.io/badge/-FFFFFF?style=flat-square&logoColor=black) | Pure White | `#FFFFFF` |

</div>

<br/>

## 📊 Account Insights

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=e-kalibro&show_icons=true&bg_color=00000000&title_color=EAB625&icon_color=EAB625&text_color=ffffff&border_color=04663D&hide_border=false" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=e-kalibro&layout=compact&bg_color=00000000&title_color=EAB625&text_color=ffffff&border_color=04663D&hide_border=false" alt="Top Languages" />

<br/><br/>

**Contribution activity**

<img src="https://api.star-history.com/svg?repos=e-kalibro/e-kalibro&type=Date" alt="Star History" width="600"/>

<sub>Some org-level metrics may render sparsely until the account has more public activity — that's expected for a new case study repo.</sub>

</div>

<br/>

## 🗺️ Roadmap

- [x] Requirements gathering & case study analysis
- [x] System design & ERD
- [x] UI/UX prototyping (Figma)
- [ ] Core catalog module
- [ ] Circulation (borrow / return) module
- [ ] Fines & notifications
- [ ] Admin analytics dashboard
- [ ] User acceptance testing with MDC Library staff
- [ ] Deployment

<sub>Update this checklist as the project moves forward — it reflects on the README the moment you edit it.</sub>

<br/>

## 🤝 Contributors

<div align="center">

<a href="https://github.com/e-kalibro/e-kalibro/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=e-kalibro/e-kalibro&columns=8" alt="Contributors" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=e-kalibro&style=for-the-badge&color=04663D&label=PROFILE+VIEWS" alt="Profile views" />

</div>

This avatar grid pulls live from the repo's actual contributors — no manual upkeep needed as the team grows.

<br/>

## 📄 License

<div align="center">

<img src="https://img.shields.io/github/license/e-kalibro/e-kalibro?style=for-the-badge&color=EAB625&labelColor=013D26" />

<sub>Add a LICENSE file to the repo to have this badge reflect it automatically.</sub>

</div>

<br/>

<div align="center">

Made with 💚💛 for **Metro Dagupan Colleges**

[⬆ Back to top](#top)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:04663D,100:013D26&height=120&section=footer&animation=fadeIn" />

</div>
