# Pavlo Kuzina - Frontend Engineer

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

**Stack:** TypeScript · Playwright · Node.js 18+

---

### [featuremap](https://github.com/PashaSchool/featuremap)
> **Surface technical debt without opening Jira.**

A CLI tool that analyses git history to identify which areas of a codebase carry the most accumulated complexity and change pressure — giving teams an objective view of where technical debt lives.

**Stack:** Python

---

### [react-csv-autopilot](https://github.com/PashaSchool/react-csv-autopilot)
> **CSV exports that handle pagination automatically.**

A React hooks library that makes large CSV exports painless. Pass it a paginated data source and it handles the batching logic, so UI code stays clean.

**Stack:** TypeScript · React

---

### [react-url-query-params](https://github.com/PashaSchool/react-url-query-params)
> **Lightweight URL state for react-router-dom.**

A minimal React hook that makes reading and writing URL query parameters as ergonomic as `useState`, with full compatibility with react-router-dom.

**Stack:** TypeScript · React · react-router-dom

---


*Open to collaboration on developer tooling, React libraries, and design-system automation.*
