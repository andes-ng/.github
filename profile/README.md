<div align="center">

<img src="https://raw.githubusercontent.com/andes-ng/.github/main/profile/banner.png" alt="Andes NG" width="100%" />

**Andes NG is an open-source Angular design system for dense, enterprise applications: standalone, signal-based components with an API and a visual language we own.**

[![npm](https://img.shields.io/npm/v/@andes-ng/ui?logo=npm&logoColor=white&label=%40andes-ng%2Fui&color=2563eb&labelColor=0f172a)](https://www.npmjs.com/package/@andes-ng/ui)
[![Storybook](https://img.shields.io/badge/Storybook-live-ff4785?logo=storybook&logoColor=white&labelColor=0f172a)](https://andes-ng.github.io/andes/)
[![Angular](https://img.shields.io/badge/Angular-22-dd0031?logo=angular&logoColor=white&labelColor=0f172a)](https://angular.dev)
[![License](https://img.shields.io/badge/license-MIT-2563eb?labelColor=0f172a)](https://github.com/andes-ng/andes/blob/main/LICENSE)

</div>

---

## What we build

Andes NG gives Angular teams a component library they can theme without a build step and trust in production: WAI-ARIA keyboard behavior, right-to-left layouts, dark mode and reduced-motion support are part of every component, and every color, size and motion value is a CSS custom property.

**Try it:** [the Storybook](https://andes-ng.github.io/andes/) lists every component, state and variant.

## Packages

| Package                                                                      | Purpose                                                      |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------ |
| [`@andes-ng/ui`](https://www.npmjs.com/package/@andes-ng/ui)                 | Standalone Angular components, one public entry point        |
| [`@andes-ng/tokens`](https://www.npmjs.com/package/@andes-ng/tokens)         | Design tokens as CSS custom properties, framework-agnostic   |
| [`@andes-ng/primitives`](https://www.npmjs.com/package/@andes-ng/primitives) | Behavior directives and services the components are built on |
| [`@andes-ng/testing`](https://www.npmjs.com/package/@andes-ng/testing)       | Helpers for testing applications that use Andes NG           |

```bash
npm install @andes-ng/ui @andes-ng/tokens
```

## Repositories

| Repo                                           | What it is                                                                                |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------- |
| [**andes**](https://github.com/andes-ng/andes) | The monorepo: the four packages, the Storybook and a consumer-style playground (Nx, pnpm) |

## How we work

- **Gitflow:** `feature/*`, `bugfix/*` and `hotfix/*` branches go into `develop`; releases are cut from `develop` into `main`.
- **Releases:** the four packages share one version. A `release/X.Y.Z` branch publishes release candidates under the `rc` tag; merging to `main` promotes the exact same build to `latest`, with npm provenance.
- **Decisions are written down** as [architecture decision records](https://github.com/andes-ng/andes/tree/main/docs/adr).

## Get in touch

Questions, bug reports or ideas? Open an issue on [the repository](https://github.com/andes-ng/andes/issues/new/choose). Security reports go through the repository's **Security** tab, never a public issue.

---

<div align="center">

Andes NG · Angular components, built to last.

</div>
