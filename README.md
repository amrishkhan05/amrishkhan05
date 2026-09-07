<h1 align="center">Amrishkhan Sheik Abdullah</h1>

<p align="center">
  <strong>Technical Lead & Full Stack Engineer</strong><br />
  Dubai, UAE · Product-minded engineering lead · Creator of Aruvix
</p>

<p align="center">
  <a href="https://amrishkhan.dev">
    <img src="https://img.shields.io/badge/Portfolio-amrishkhan.dev-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/amrishkhan">
    <img src="https://img.shields.io/badge/LinkedIn-amrishkhan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://dev.to/amrishkhan05">
    <img src="https://img.shields.io/badge/DEV-amrishkhan05-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="DEV Community" />
  </a>
  <a href="https://www.aruvix.com/">
    <img src="https://img.shields.io/badge/Creator_of-Aruvix-16A34A?style=for-the-badge&logo=rocket&logoColor=white" alt="Creator of Aruvix" />
  </a>
</p>

<div align="center">
  <sub>Engineering systems for product teams, developer workflows, APIs, and reliable releases.</sub>
</div>

<br />

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>10+ years</strong></td>
      <td align="center"><strong>95%+ coverage</strong></td>
      <td align="center"><strong>Aviation + enterprise</strong></td>
      <td align="center"><a href="https://www.aruvix.com/"><strong>Aruvix</strong></a></td>
    </tr>
    <tr>
      <td align="center"><sub>Engineering delivery</sub></td>
      <td align="center"><sub>Release quality gates</sub></td>
      <td align="center"><sub>Production systems</sub></td>
      <td align="center"><sub>Developer tool creator</sub></td>
    </tr>
  </table>
</div>

## About

I build dependable web platforms, backend systems, and developer tools. My work is shaped by release quality, maintainability, and measurable product value.

I specialize in frontend and backend architecture, API design, microservices, payment integrations, database engineering, and delivery leadership. I enjoy building reliable systems with strong developer standards, high test coverage, and practical business impact.

Alongside enterprise engineering, I build open-source tools around a recurring problem I see in modern development: developers — and increasingly AI coding agents — need better tools for understanding context, respecting constraints, and making smaller, safer changes.

## What I Build

| Product engineering                                                          | Backend systems                                                       | Developer tooling                                                                 |
| ---------------------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Customer journeys, admin operations, frontend architecture, reusable modules | Secure APIs, microservices, payment workflows, webhook reconciliation | Aruvix, Frankly, Hallpass, SQL generation utilities, JSON/API/debugging workflows |

## Selected Wins

| Area              | Impact                                                                                                                 |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Airline systems   | Built and maintained passenger check-in modules, seat mapping, and ancillaries with Angular and NestJS.                |
| Payments          | Integrated Magnati and Network International with robust webhook-based reconciliation flows.                           |
| Architecture      | Designed scalable microservice boundaries and reduced frontend orchestration complexity through middleware.            |
| Quality           | Established a 95%+ test coverage quality gate with CI automation to prevent regressions.                               |
| Operations        | Managed Linux server deployments, monitoring, and production issue resolution.                                         |
| Developer tooling | Built Aruvix and open-source tools focused on developer productivity, AI-assisted engineering, and safer code changes. |
| Open source       | Published multiple npm packages and developer tools including Frankly, Hallpass, and `sql-select-query-generator`.     |

## Aruvix

Aruvix is a private developer workspace for formatting JSON, visualizing structures, sending API requests, comparing payloads, running quick dev utilities, and converting data without leaving the browser.

I built Aruvix because I kept switching between tabs just to format JSON, inspect a request, or diff two payloads. The product brings those everyday tools into one private, no-sign-up browser workspace built by a developer, for developers.

<table>
  <tr>
    <td><strong>Format</strong><br />JSON formatting, validation, and visual inspection.</td>
    <td><strong>Inspect</strong><br />API request checks and response review.</td>
    <td><strong>Compare</strong><br />Diff payloads, configs, code snippets, and snapshots.</td>
  </tr>
  <tr>
    <td><strong>Convert</strong><br />Prepare data for APIs, docs, tickets, and tests.</td>
    <td><strong>Refine</strong><br />Frontend helpers for CSS, SVG, and code translation.</td>
    <td><strong>Test</strong><br />QA helpers for sample data, assertions, and bug reports.</td>
  </tr>
</table>

> Private by design. No sign-up required. One unified workspace for the daily tools developers reach for while debugging APIs and structured data.

[Explore Aruvix](https://amrishkhan.dev/aruvix)

## AI Developer Tooling

I'm experimenting with a simple idea: AI coding agents are becoming very good at writing code. The interesting engineering problem is increasingly about teaching them **when not to write more code** and **which rules they are not allowed to ignore**.

That led to Frankly and Hallpass.

### Frankly

**Frankly reviews AI-generated changes and asks the awkward senior-engineer question: *did this really need to change this much?***

It is an open-source coding-agent plugin focused on reducing unnecessary code changes and keeping patches intentional, reviewable, and maintainable.

Frankly is designed around engineering restraint rather than raw code generation. It can inspect proposed changes, identify unnecessarily large diffs, challenge avoidable complexity, and encourage the agent toward a smaller implementation where appropriate.

**Core ideas**

* Diff minimization and change-scope analysis.
* Detect unnecessarily broad AI-generated patches.
* Encourage simpler implementations before changes reach review.
* Conservative, senior-engineer-style review behaviour.
* Automatic review with manual escape hatches.
* Designed for AI-assisted development workflows.

[View Frankly on GitHub](https://github.com/amrishkhan05/frankly) · [View on npm](https://www.npmjs.com/package/@amrishkhan05/frankly)

### Hallpass

**Hallpass is the mildly suspicious hall monitor for AI coding agents.**

Modern repositories increasingly contain instructions such as `AGENTS.md`, `CLAUDE.md`, architectural constraints, coding conventions, and repository-specific rules. The problem is that an instruction file is only useful if the agent actually follows it.

Hallpass checks agent behaviour against repository rules and flags violations, contradictions, and stale or missing guidance.

**Core ideas**

* Enforce repository-level AI coding rules.
* Understand `AGENTS.md`, `CLAUDE.md`, and related instructions.
* Detect rule violations and conflicting guidance.
* Identify stale repository instructions.
* Help bootstrap repository guidance when rules are missing.
* Provide concise, intentionally witty review feedback.

Its personality is deliberate: less corporate policy engine, more hall monitor standing beside your pull request asking for a pass.

[View Hallpass on GitHub](https://github.com/amrishkhan05/hallpass) · [View on npm](https://www.npmjs.com/package/@amrishkhan05/hallpass)

## Tech Writing

I write practical engineering guides that simplify complex concepts and improve developer workflows.

* JavaScript and browser fundamentals.
* API design, API clients, and developer tooling.
* AI-assisted software engineering and coding-agent workflows.
* Software architecture and production engineering.
* GitHub workflows, SSH setup, and productivity.
* SOLID principles, maintainability, and engineering practices.
* Lessons borrowed from industries outside software and applied to engineering systems.

[Read my articles on DEV](https://dev.to/amrishkhan05)

## Open Source

### Frankly

A coding-agent plugin focused on engineering restraint: smaller diffs, intentional changes, and less unnecessary complexity.

[GitHub](https://github.com/amrishkhan05/frankly) · [npm](https://www.npmjs.com/package/@amrishkhan05/frankly)

### Hallpass

A rules-enforcement plugin for AI coding agents that checks repository instructions and catches violations, contradictions, and stale guidance.

[GitHub](https://github.com/amrishkhan05/hallpass) · [npm](https://www.npmjs.com/package/@amrishkhan05/hallpass)

### sql-select-query-generator

Generates dynamic SQL SELECT queries from JSON configuration to speed up backend development and reporting use cases.

[sql-select-query-generator](https://www.npmjs.com/package/sql-select-query-generator)

## Core Stack

<div align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original.svg" title="Bootstrap" alt="Bootstrap" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg" title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="Node.js" alt="Node.js" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-plain.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jquery/jquery-original-wordmark.svg" title="jQuery" alt="jQuery" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nginx/nginx-original.svg" title="Nginx" alt="Nginx" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="GitHub" alt="GitHub" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original-wordmark.svg" title="Express" alt="Express" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="VS Code" alt="VS Code" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="npm" alt="npm" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original-wordmark.svg" title="MongoDB" alt="MongoDB" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" title="Microsoft SQL Server" alt="Microsoft SQL Server" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/angularjs/angularjs-plain.svg" title="Angular" alt="Angular" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
</div>

<details>
  <summary><strong>Engineering style</strong></summary>
  <br />
  I prefer clear contracts, maintainable boundaries, measurable release quality, practical automation, and simple tools that reduce repeated developer effort.
</details>

## Git Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=amrishkhan05&theme=highcontrast&hide_border=true&date_format=j%20M%5B%20Y%5D&fire=DD2727" alt="GitHub Streak" />
</p>

## Connect

* Portfolio: [amrishkhan.dev](https://amrishkhan.dev)
* LinkedIn: [linkedin.com/in/amrishkhan](https://www.linkedin.com/in/amrishkhan)
* DEV: [dev.to/amrishkhan05](https://dev.to/amrishkhan05)
* GitHub: [github.com/amrishkhan05](https://github.com/amrishkhan05)
* Email: [amrishkhansheikabdullah@gmail.com](mailto:amrishkhansheikabdullah@gmail.com)
