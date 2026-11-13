# 🌿 FARAHSAN ONLINE — Official Djibouti Store

<p align="center">
  <img src="images/farahsan-online-banner.png" alt="Farahsan Online — Natural Beauty & Wellness" width="100%">
</p>

<p align="center">
  <a href="https://github.com/edenunix/Farhasan-Online">
    <img src="https://img.shields.io/badge/GitHub-edenunix%2FFarhasan--Online-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <img src="https://img.shields.io/badge/Node.js-20%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/pnpm-11.24.0-F69220?style=for-the-badge&logo=pnpm&logoColor=white" alt="pnpm">
  <img src="https://img.shields.io/badge/TypeScript-5.5.4-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Prettier-3.3.3-F7B93E?style=for-the-badge&logo=prettier&logoColor=white" alt="Prettier">
  <img src="https://img.shields.io/badge/GitHub_Pages-Deployment-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages">
</p>

<p align="center">
  <strong>Natural Beauty · Wellness · Aloe Vera</strong>
</p>

<p align="center">
  A multilingual e-commerce platform dedicated to Forever Living Products and natural wellness in Djibouti.
</p>

<p align="center">
  <a href="https://edenunix.github.io/Farhasan-Online/">
    <strong>🌐 VISIT THE OFFICIAL STORE</strong>
  </a>
  &nbsp;·&nbsp;
  <a href="https://github.com/edenunix/Farhasan-Online">
    <strong>💻 SOURCE CODE</strong>
  </a>
</p>

---

## 📌 1. Project Overview

**FARAHSAN ONLINE** is an e-commerce platform specializing in natural Aloe Vera, beauty, personal care, and wellness products from **Forever Living Products**, serving customers in Djibouti.

The platform is designed to make product discovery and ordering easier through a multilingual interface, locally relevant payment information, WhatsApp assistance, and delivery information.

The project combines a customer-facing online store with a structured development workspace for its web, backend, and database components.

### Project Information

| Information | Details |
|---|---|
| Project | FARAHSAN ONLINE |
| Industry | E-commerce / Beauty / Wellness |
| Market | Djibouti |
| Product range | Forever Living Products |
| Languages | French, Somali, Afar, Arabic, English |
| Website | GitHub Pages |
| Repository | GitHub |
| Status | Online platform / ongoing development |

---

## ✨ 2. Core Features

### 🛍️ E-commerce & Product Catalog

- Product catalog dedicated to Forever Living Products.
- Organized product categories:
  - Drinks and Aloe Vera Gels
  - Nutrition and Supplements
  - Beauty and Skincare
  - Personal Care and Hygiene
  - Packs and Wellness Programs
- Product imagery and organized navigation.
- Interactive product discovery.
- Product filtering and shopping cart functionality as provided by the storefront.

### 🌍 Multilingual Experience — i18n

Five integrated languages:

| Language | Language |
|---|---|
| 🇫🇷 French | Français |
| 🇸🇴 Somali | Soomaali |
| 🇩🇯 Afar | Qafar |
| 🇸🇦 Arabic | العربية |
| 🇬🇧 English | English |

Internationalization features:

- Multilingual interface.
- Language preference persistence using `localStorage`.
- Right-to-left (RTL) layout support for Arabic.
- Cairo typography for Arabic content.
- Language-aware interface presentation.

### 💳 Local Payment Options

The platform presents payment options adapted to the Djiboutian market.

| Payment Method | Provider |
|---|---|
| Waafi | Salaam African Bank |
| D-Money | Djibouti Telecom |
| BCI Pay | BCI-MR |
| Cash | Cash on Delivery |

### 📲 WhatsApp Ordering & Customer Support

- Direct access to official WhatsApp assistance.
- Customer communication for product information and orders.
- WhatsApp contact: **+253 77 29 77 05**.

### 🚚 Local Delivery

- Delivery information for Djibouti.
- Service information covering Djibouti City and Balbala.

### 🔐 Security & Web Best Practices

The project includes security-related web configurations and practices:

- Content Security Policy (CSP).
- XSS mitigation practices.
- Clickjacking protection through `X-Frame-Options: DENY`.
- External link protection with `rel="noopener noreferrer"`.
- Controlled resource paths and image fallback handling.

---

## 🏗️ 3. Technical Architecture

The repository is organized as a **pnpm monorepo**, with separate workspace locations for applications and shared packages.

```text
Farhasan-Online/
│
├── apps/                     # Application workspaces
│
├── packages/                 # Shared packages
│
├── assets/                   # Storefront visual assets
│
├── Image forever/            # Forever Living product images
│
├── images/                   # Project presentation images
│
├── index.html                # Storefront entry page
├── produits.html             # Product catalog page
│
├── package.json              # Root workspace configuration
├── pnpm-workspace.yaml       # pnpm workspace definitions
├── tsconfig.base.json        # Shared TypeScript configuration
└── README.md
```

### Workspace Organization

The root workspace defines two main groups:

- `apps/*` — application workspaces.
- `packages/*` — shared packages.

The root scripts expose separate development commands for:

- Backend application: `@farhasan/backend`
- Web application: `@farhasan/web`
- Database package: `@farhasan/database`

---

## 🧰 4. Technologies & Development Tools

### Core Development Stack

| Technology / Tool | Purpose |
|---|---|
| Node.js | JavaScript runtime |
| TypeScript | Typed JavaScript development |
| HTML5 | Web page structure |
| CSS3 | Styling and responsive presentation |
| JavaScript | Interactive functionality |
| pnpm | Package management and monorepo workspaces |
| pnpm Workspaces | Application and package organization |
| Prettier | Code formatting |
| TypeScript Compiler | Type checking and compilation |
| Git | Version control |
| GitHub | Source code hosting and collaboration |
| GitHub Pages | Public website hosting |

### Frontend & User Experience

| Technology | Purpose |
|---|---|
| HTML / CSS / JavaScript | Storefront interface |
| i18n | Multilingual interface |
| localStorage | Language preference persistence |
| Cairo Font | Arabic typography |
| RTL | Right-to-left Arabic layout |

### Backend & Data Workspace

The repository exposes dedicated backend and database workspace commands:

- Backend development through the `@farhasan/backend` workspace.
- Database operations through the `@farhasan/database` workspace.
- Database generation and schema synchronization commands.
- Shared TypeScript configuration.

*Specific backend frameworks, database engines, and ORM packages should be documented from their individual workspace dependencies.*

### Development Environment

| Component | Version / Configuration |
|---|---|
| Node.js | `>=20.0.0` |
| pnpm | `11.24.0` |
| TypeScript | `^5.5.4` |
| Prettier | `^3.3.3` |
| rimraf | `^6.0.1` |
| Project version | `1.2.0` |

---

## 🛠️ 5. Development Commands

The root `package.json` provides the following scripts:

| Command | Description |
|---|---|
| `pnpm dev` | Start application workspaces in parallel |
| `pnpm dev:backend` | Start backend development |
| `pnpm dev:web` | Start web development |
| `pnpm build` | Build all workspace packages |
| `pnpm lint` | Run workspace lint scripts |
| `pnpm typecheck` | Run TypeScript checks |
| `pnpm db:generate` | Generate database resources |
| `pnpm db:push` | Synchronize database schema |
| `pnpm clean` | Clean generated build and dependency directories |

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/edenunix/Farhasan-Online.git
```

**2. Enter the project directory**

```bash
cd Farhasan-Online
```

**3. Enable Corepack**

```bash
corepack enable
```

**4. Install dependencies**

```bash
pnpm install
```

**5. Start development**

```bash
pnpm dev
```

### Run Individual Workspaces

Backend:

```bash
pnpm dev:backend
```

Web:

```bash
pnpm dev:web
```

### Build & Quality Checks

```bash
pnpm build
pnpm lint
pnpm typecheck
```

### Database Commands

```bash
pnpm db:generate
pnpm db:push
```

*Note: Database commands require the corresponding workspace and database configuration to be available.*

---

## 🚀 6. Deployment & Hosting

### Public Storefront

The public storefront is hosted using GitHub Pages.

**Live Website:**

https://edenunix.github.io/Farhasan-Online/

### Repository

https://github.com/edenunix/Farhasan-Online

### Deployment Considerations

- GitHub Pages hosting for the public storefront.
- Relative asset paths for deployment compatibility.
- Product image organization.
- Automatic image fallback handling.
- Workspace build and validation scripts for development.

---

## 🖥️ 7. Project Preview

<p align="center">
  <img src="images/Project Preview.png" alt="Farahsan Online Platform Preview" width="100%">
</p>

### Official Resources

- 🌐 [Visit the online store](https://edenunix.github.io/Farhasan-Online/)
- 💻 [Explore the GitHub repository](https://github.com/edenunix/Farhasan-Online)

---

## 🎯 8. Project Objectives

- Build a digital commerce experience adapted to Djibouti.
- Improve access to natural beauty and wellness products.
- Provide a multilingual customer experience.
- Present locally relevant payment options.
- Simplify customer communication and ordering.
- Organize web, backend, and database development.
- Maintain a maintainable and scalable project structure.

---

## 👨‍💻 9. Developer & Ownership

**Developer:** ADEN AHMED ADEN

**Development Brand:** Aden.Code

**Official Contact:**

- Email: contact@farahsan.com
- WhatsApp: +253 77 29 77 05

**Project Status:** Public storefront online — development workspace maintained.

---

<p align="center">
  <strong>🌿 FARAHSAN ONLINE — Naturally Better.</strong>
</p>

<p align="center">
  © 2026 FARAHSAN ONLINE. All rights reserved.
</p>
