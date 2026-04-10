# Pavlo Kuzina — Frontend Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pavlo--kuzina-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/pavlo-kuzina-549646197)
[![GitHub followers](https://img.shields.io/github/followers/PashaSchool?style=flat&logo=github)](https://github.com/PashaSchool)
![Location](https://img.shields.io/badge/Location-Ukraine-FFD700?style=flat)

---

Frontend developer specialising in **React** and **TypeScript**, with a focus on developer tooling and open-source utilities. I build things that help teams write cleaner code, catch technical debt early, and ship more consistent interfaces.

---

## Open Source Projects

### [design-auditor](https://github.com/PashaSchool/design-auditor)
> **Lighthouse for design consistency.**

A CLI tool that crawls websites using a real browser and audits them against design system best practices. Unlike static CSS analysers, it captures computed styles, JavaScript-injected values, and runtime-resolved CSS custom properties to reflect what users actually see.

**What it checks:**
- Typography — font families, sizes, and line-height consistency
- Color — unique palette size, shade clustering via delta-E, WCAG AA contrast validation
- Spacing — grid system adherence (4 px / 8 px), outlier detection
- Components — touch target sizes, button variants, border-radius systems, z-index organisation
- Outputs a structured JSON report ready for CI pipelines

```bash
npx design-auditor https://yoursite.com
```

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js_18+-339933?style=flat&logo=node.js&logoColor=white)

---

### [Faultlines](https://github.com/PashaSchool/faultlines) &nbsp; [![faultlines.dev](https://img.shields.io/badge/faultlines.dev-2563eb?style=flat)](https://faultlines.dev)
> **Know where technical debt lives — no Jira required.**

An automated code intelligence platform that analyses git history to detect features, map user-facing flows, and surface bug-fix hotspots across your codebase. Gives engineering teams an objective, data-driven view of what to refactor next.

- Sonnet-powered semantic feature detection with monorepo and workspace support
- Health scoring per feature based on bug-fix ratio, churn, and contributor patterns
- CLI for local analysis, SaaS dashboard for team-wide visibility

```bash
pip install faultlines
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_AI-191919?style=flat&logo=anthropic&logoColor=white)
[![Site](https://img.shields.io/badge/faultlines.dev-2563eb?style=flat)](https://faultlines.dev)

---

### [react-csv-autopilot](https://github.com/PashaSchool/utils-kit/tree/main/packages/react-csv-autopilot)
> **CSV exports that handle pagination automatically.**

A React hooks library that makes large CSV exports painless. Pass it a paginated data source and it handles the batching logic, so UI code stays clean.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

---

### [react-url-query-params](https://github.com/PashaSchool/utils-kit/tree/main/packages/react-url-query-params)
> **Lightweight URL state for react-router-dom.**

A minimal React hook that makes reading and writing URL query parameters as ergonomic as `useState`, with full compatibility with react-router-dom.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=react-router&logoColor=white)

---


*Open to collaboration on developer tooling, React libraries, and design-system automation.*
