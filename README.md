# Pavlo Kuzina — Frontend Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pavlo--kuzina-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/pavlo-kuzina-549646197)
[![GitHub followers](https://img.shields.io/github/followers/PashaSchool?style=flat&logo=github)](https://github.com/PashaSchool)
![Location](https://img.shields.io/badge/Location-Ukraine-FFD700?style=flat)

---

Frontend developer specialising in **React** and **TypeScript**, with a focus on developer tooling and open-source utilities. I build things that help teams write cleaner code, catch technical debt early, and ship more consistent interfaces - and I'm currently building **[Faultlines](https://faultlines.dev)** end to end, from the analysis engine to the product.

---

## Featured · [Faultlines](https://github.com/PashaSchool/faultlines) &nbsp; [![faultlines.dev](https://img.shields.io/badge/faultlines.dev-39E6FF?style=flat&logoColor=white)](https://faultlines.dev)

> **A live, feature-level map of your codebase — built for engineering teams and the AI agents working alongside them.**

Faultlines turns months of git history into a structured map of your product. It detects the **features** in your code and the **user flows** that run through them, scores each one for health, and pins down exactly where technical debt and regression risk actually live - no Jira archaeology, no manual tagging, no annotations to maintain. One cold scan, two audiences:

**For engineers** - a "Signal Room" dashboard with per-feature health, coverage gaps, hotspots, change-impact (blast radius), and bus-factor risk. PR comments that show what a diff actually touches *before* you merge, plus weekly Slack digests of where the codebase is drifting.

**For AI agents** — an **MCP server** exposing 13 read-only tools that hand Cursor, Claude Code, and Cline a structured map of your product *plus* live production signal — so your agent edits with real context instead of grepping blind.

**Runtime, on the map** - Sentry errors and PostHog usage are attributed back onto the exact feature and flow they belong to. Activity and risk land where the work happens, not in a separate dashboard.

- Code-grounded, LLM-assisted feature & user-flow detection - monorepo / workspace aware
- Per-feature health: bug-fix ratio, churn, coverage, ownership & bus factor, change impact
- Native MCP for AI agents — your product map becomes first-class agent context
- Privacy by design — Standard, Private (customer-managed keys), and self-hosted Sovereign modes; **source code is never stored at rest**, on any tier
- Open-source CLI (MIT) + hosted platform — unlimited developers on every tier, pay for repos not seats

```bash
# 1 · Scan a repo locally with the open-source engine
pip install faultlines
faultlines analyze ~/my-project --llm --flows --symbols

# 2 · Give your AI agent the map (Cursor / Claude Code / Cline)
npx -y mcp-remote https://app.faultlines.dev/api/mcp
```

![Python](https://img.shields.io/badge/engine-Python-3776AB?style=flat&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/LLM-Claude-191919?style=flat&logo=anthropic&logoColor=white)
[![Live](https://img.shields.io/badge/Try_it-faultlines.dev-39E6FF?style=flat)](https://faultlines.dev)

**Tech behind it** &nbsp;
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-Neon-336791?style=flat&logo=postgresql&logoColor=white)
![AWS KMS](https://img.shields.io/badge/AWS-KMS-FF9900?style=flat&logo=amazonwebservices&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-workers-8B5CF6?style=flat&logo=fly.io&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-6E56CF?style=flat)

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
