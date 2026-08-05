# 🍹 FreshJuice DEV – Developer Edition of the FreshJuice HubSpot Theme

[![GitHub Release](https://img.shields.io/github/v/release/freshjuice-dev/freshjuice-dev-hubspot-theme)](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/freshjuice-dev/freshjuice-dev-hubspot-theme)](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/commits/main)
[![GitHub License](https://img.shields.io/github/license/freshjuice-dev/freshjuice-dev-hubspot-theme)](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/blob/main/LICENSE)
[![GitHub watchers](https://img.shields.io/github/watchers/freshjuice-dev/freshjuice-dev-hubspot-theme)](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/watchers)
[![GitHub forks](https://img.shields.io/github/forks/freshjuice-dev/freshjuice-dev-hubspot-theme)](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/network/members)
[![GitHub Repo stars](https://img.shields.io/github/stars/freshjuice-dev/freshjuice-dev-hubspot-theme)](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/stargazers)

FreshJuice DEV is a modern, clean, and minimalistic HubSpot CMS theme designed specifically for developers.
Built with **Tailwind CSS** and **Alpine.js**, it offers full flexibility and a clean architecture, making it easy to customize and extend for real-world production use.

[**Demo website →**](https://freshjuice.dev/developer-edition/demo/)

---

## Purpose

This theme helps developers get a head start on HubSpot CMS theme development.
While most HubSpot themes are heavy and bloated, FreshJuice DEV is intentionally minimal — it loads only the components you actually need, resulting in a pixel-perfect design and a fast-loading website.

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v24.0.0 or newer)
- [HubSpot CMS CLI](https://developers.hubspot.com/docs/cms/developer-reference/local-development-cli)

### Installation

1. Clone the repo and `cd` into it.
2. Run `npm install` (requires Node v24.0.0+).
3. Run `npm run prepare` to install [Husky](https://typicode.github.io/husky/) hooks.
4. For local development:
   `npm run start` — runs Tailwind CSS, esbuild, and HubSpot CLI with file watching, rebuild, and live upload to HubSpot.
5. For production build:
   `npm run build` — builds Tailwind CSS and JavaScript.
6. For uploading to HubSpot:
   `npm run upload:hubspot` — uploads the theme via HubSpot CLI.

---

## Tech Stack

- **[Tailwind CSS](https://tailwindcss.com/)** – Utility-first CSS framework.
- **[Alpine.js](https://alpinejs.dev/)** – Minimal JavaScript framework for declarative interactivity.
- **[HubSpot CMS CLI](https://developers.hubspot.com/docs/cms/developer-reference/local-development-cli)** – Local development toolkit for HubSpot.

---

## Project Structure

```plaintext
source/                   # Theme source files
├── css/                  # Source CSS files (Tailwind CSS)
├── images/               # Source images and assets
└── js/                   # Source JavaScript files

theme/                    # Compiled theme files for HubSpot
├── css/                  # Compiled CSS files
├── images/               # Images and icons
├── js/                   # Compiled JS and vendor scripts
├── macros/               # HubL macros
├── modules/              # HubL modules
├── sections/             # HubL sections
└── templates/            # HubL templates
    ├── layouts/          # Layout templates
    ├── partials/         # Partial templates
    └── system/           # System templates
```

---

## Contributing

If you find an issue, [open an issue](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/issues).
Contributions are welcome — fork the repo and submit a pull request.

---

## Versioning

We use [SemVer](http://semver.org/) for versioning.
See the [releases page](https://github.com/freshjuice-dev/freshjuice-dev-hubspot-theme/releases) for available versions.

---

## License

Distributed under the MIT License. See the [LICENSE](./LICENSE) file for the full text.

**Key points of the MIT License**:
- You can use, copy, and modify the software.
- You can distribute original or modified versions of the software.
- You can include the software in commercial products or services.
- You must include the same license text in all copies or substantial portions of the software.
- No warranty is provided and no patent rights are granted.
