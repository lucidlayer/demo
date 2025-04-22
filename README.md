# Traceform Demo Projects

<p align="center">
  <a href="https://github.com/lucidlayer/traceform-demo/stargazers">
    <img src="https://img.shields.io/github/stars/lucidlayer/traceform-demo?style=social" alt="GitHub stars" />
  </a>
  <a href="https://github.com/lucidlayer/traceform-demo/network/members">
    <img src="https://img.shields.io/github/forks/lucidlayer/traceform-demo?style=social" alt="GitHub forks" />
  </a>
  <a href="https://github.com/lucidlayer/traceform-demo/issues">
    <img src="https://img.shields.io/github/issues/lucidlayer/traceform-demo.svg" alt="GitHub issues" />
  </a>
  <a href="https://github.com/lucidlayer/traceform-demo/commits/main">
    <img src="https://img.shields.io/github/last-commit/lucidlayer/traceform-demo.svg" alt="Last commit" />
  </a>
  <a href="https://github.com/lucidlayer/traceform-demo">
    <img src="https://visitor-badge.laobi.icu/badge?page_id=lucidlayer.traceform-demo" alt="Page views" />
  </a>
</p>

> Experience Traceform's powerful developer workflow in real React projects! These demos let you try the full Traceform toolchain—CLI, VS Code extension, and browser extension—on real codebases, with step-by-step onboarding.

![Traceform CLI onboarding demo](.github/demo.gif)
*See above for a visual walkthrough of the onboarding and validation process.*

---

<details>
<summary><strong>Table of Contents</strong></summary>

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Demo Project List](#demo-project-list)
- [Step-by-Step Setup](#step-by-step-setup)
- [Traceform Onboarding](#traceform-onboarding)
- [Validation & Troubleshooting](#validation--troubleshooting)
- [FAQ](#faq)
- [Links & Resources](#links--resources)

</details>

---

## Overview

This repository contains four demo projects designed to showcase Traceform's capabilities. Each project is pre-configured **without Traceform**, allowing you to go through the setup process yourself and experience the onboarding flow as a new user would.

---

## Prerequisites

- **Node.js** (>= 18.17.0): [Download Node.js](https://nodejs.org/)
- **npm** (>= 8.0.0), **yarn** (>= 1.22.0), or **pnpm** (>= 7.0.0)
- A Chromium-based browser (for the Traceform extension)
- Visual Studio Code (for the Traceform VS Code extension)

---

## Demo Project List

Pick any demo to try Traceform from scratch:

- **Demo-01:** Basic React app
- **Demo-02:** React + TypeScript
- **Demo-03:** Vite + React
- **Demo-04:** Advanced patterns

---

## Step-by-Step Setup

1. **Choose a Demo Project**
   ```bash
   cd Demo-01  # or Demo-02, Demo-03, Demo-04
   ```
2. **Install Dependencies**
   ```bash
   npm install
   ```
3. **Install Traceform Onboarding CLI and Types**
   ```bash
   npm install --save-dev @types/node
   npx @lucidlayer/traceform-onboard check
   ```
   _Follow the interactive wizard to set up the Babel plugin, VS Code extension, and browser extension._

4. **Start the Demo App**
   ```bash
   npm run dev
   ```
5. **Open in Your Browser**
   - Visit the local address shown in your terminal (e.g., `http://localhost:5173`).

6. **Validate Traceform**
   - Open VS Code and check for the Traceform sidebar.
   - Use "Traceform: Find Component in UI" to highlight components in your browser.

---

## Traceform Onboarding

The onboarding CLI will guide you through:
- Checking prerequisites (Node.js, package manager)
- Installing the Traceform Babel plugin
- Adding configuration snippets (manual copy/paste)
- Installing the [Traceform VS Code extension](https://marketplace.visualstudio.com/items?itemName=LucidLayer.traceform-vscode)
- Installing the [Traceform Chrome extension](https://chromewebstore.google.com/detail/giidcepndnnabhfkopmgcnpnnilkaefa)
- Final validation and troubleshooting tips

For a full walkthrough, see the GIF above or watch the [YouTube demo](https://www.youtube.com/watch?v=0ZnyWkS2g44).

---

## Validation & Troubleshooting

- If you see "client connected" in the VS Code Traceform sidebar, setup is complete!
- If components are not highlighted in the browser, double-check:
  - The browser extension is installed and enabled
  - The dev server is running
  - The correct project is open in VS Code
- For more help, see the [Traceform documentation](https://github.com/lucidlayer/traceform) or open an issue.

---

## FAQ

**Q: Can I use these demos in a monorepo?**  
A: Yes! The onboarding CLI detects monorepos and works with common setups.

**Q: Does the CLI modify my files?**  
A: No. All configuration changes are manual (copy/paste from the wizard).

**Q: What if something fails?**  
A: The wizard provides troubleshooting tips and links to documentation for each step.

---

## Links & Resources

- [Traceform Onboarding CLI (npm)](https://www.npmjs.com/package/@lucidlayer/traceform-onboard)
- [Traceform VS Code Extension](https://marketplace.visualstudio.com/items?itemName=LucidLayer.traceform-vscode)
- [Traceform Chrome Extension](https://chromewebstore.google.com/detail/giidcepndnnabhfkopmgcnpnnilkaefa)
- [Traceform Documentation](https://github.com/lucidlayer/traceform)

---

*This repository is part of the Traceform developer toolset. For more information, visit [github.com/lucidlayer/traceform](https://github.com/lucidlayer/traceform)*
