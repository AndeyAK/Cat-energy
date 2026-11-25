# Cat Energy

**Responsive website for a functional cat food brand.**

Cat Energy is a multi-page website developed as part of the HTML Academy professional course. The project focuses on responsive layout, structured markup, modular stylesheets and interactive interface elements.

<p align="center">
  <a href="https://andeyak.github.io/Cat-energy/">
    **View Live Demo**
  </a>
</p>

<!-- Add a project screenshot here -->

## Project Overview

The website presents a fictional brand of functional cat food and provides visitors with information about its products and nutrition programs.

The project includes three main pages:

- **Home** — brand introduction, product advantages and featured nutrition programs.
- **Catalog** — product listing with descriptions and ordering interface.
- **Program Selection** — a form for selecting an appropriate nutrition program.

## Features

- Responsive layout for different screen sizes.
- BEM methodology for organizing CSS classes.
- Modular SCSS architecture.
- Nunjucks templates for reusable page structure.
- JavaScript ES modules.
- Interactive navigation menu.
- Before/after comparison slider.
- Automated build process with Gulp.
- Code quality checks using ESLint and Stylelint.
- Automated deployment to GitHub Pages through GitHub Actions.

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| SCSS | Styling and modular CSS |
| JavaScript (ES Modules) | Interface interactions |
| Nunjucks | HTML templating |
| Gulp | Build automation |
| PostCSS | CSS processing |
| ESLint | JavaScript linting |
| Stylelint | Stylesheet linting |
| pnpm | Package management |
| GitHub Actions | Automated deployment |

## Getting Started

### Requirements

- Node.js 22
- pnpm 9.12.3

### Installation

Clone the repository:

```bash
git clone https://github.com/AndeyAK/Cat-energy.git
```

Navigate to the project directory:

```bash
cd Cat-energy
```

Install dependencies:

```bash
pnpm install
```

### Development

Start the development server:

```bash
pnpm start
```

### Production Build

Create a production build:

```bash
pnpm build
```

## Project Structure

```text
Cat-energy/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── source/
│   ├── pages/
│   │   ├── index.njk
│   │   ├── catalog/
│   │   └── form/
│   ├── scripts/
│   ├── styles/
│   └── ...
├── gulpfile.js
├── package.json
├── pnpm-lock.yaml
└── README.md
```

The `source/` directory contains the project source files. Other files and directories in the project root contain configuration and build-related resources.

## Deployment

The project is deployed to **GitHub Pages**.

Deployment is automated using GitHub Actions. The workflow builds the project and publishes the generated files when changes are pushed to the `master` branch.

**Live Demo:** https://andeyak.github.io/Cat-energy/

## Original Course Information

- **Student:** [Андрей Катасонов](https://up.htmlacademy.ru/adaptive/31/user/2450769)
- **Mentor:** [Сергей Артёмов](https://htmlacademy.ru/profile/firefoxic)

## Important

- `source/` — directory containing source files for project development.
- All other files in the project root and other directories contain project configuration.

## Documentation

- [Contributing.md](./Contributing.md) — information about Git workflow in the project.
- [Workflow.md](./Workflow.md) — project setup, file structure and workflow documentation.

---

<p align="center">
  <a href="https://htmlacademy.ru/intensive/adaptive">
    <img src="https://camo.githubusercontent.com/31ab12bdb76ca0ff29aab83b4644a48c0b4e2a05bc96a28d28614d3b2b7e9eb2/68747470733a2f2f75702e68746d6c61636164656d792e72752f7374617469632f696d672f696e74656e736976652f61646170746976652f6c6f676f2d666f722d6769746875622d322e706e67" alt="HTML Academy" width="180">
  </a>
</p>

Repository created for learning in the professional online course **HTML and CSS: Responsive Layout and Automation** by [HTML Academy](https://htmlacademy.ru).
