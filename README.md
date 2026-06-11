# Portfolio Website Docs

Public documentation shell for Michael Panico's live portfolio website:

https://www.michaelspanico.com/

The private implementation repository remains private. This docs shell explains the public portfolio strategy, validation approach, assistant behavior, and privacy boundaries without exposing source history, resume archives, environment variables, generated logs, or private career-planning material.

## Recruiter Snapshot

The portfolio supports roles in:

- Business Analytics
- Business Intelligence
- Data Analysis
- Financial Data Analysis
- Market Data Analysis
- Analytics Automation
- Quant-adjacent analytics and research-support roles where requirements match the current proof base

The site is intentionally framed around current evidence: Power BI, SQL, Python, dashboarding, reporting automation, applied analytics projects, and careful financial-data / market-data positioning.

It does not position Michael as a current professional quant trader, quant developer, professional quant researcher, or enterprise AI platform owner.

## What The Website Demonstrates

- A clear public candidate identity for BI, data analytics, financial-data, market-data, and automation roles.
- A recruiter-readable project library with short project summaries and proof surfaces.
- Downloadable public resume assets.
- A guided assistant that answers role-fit and project questions from bounded portfolio context.
- Conservative language around AI-assisted workflows, market-data projects, and quant-adjacent interests.
- Validation gates before public profile updates.

## Public Routes

- Home: https://www.michaelspanico.com/
- CV: https://www.michaelspanico.com/cv
- Projects: https://www.michaelspanico.com/projects

## Assistant Boundary

The portfolio assistant should:

- emphasize Power BI, SQL, Python, Avnet business-analytics experience, KPI reporting, and workflow automation;
- connect experience to BI, data analytics, financial-data, market-data, fintech, and analytics-automation roles;
- frame AI-assisted workflow work as durable context, handoff rules, validation gates, and documentation discipline;
- avoid claiming enterprise AI ownership or production agent-platform experience;
- describe quant-related interest as future, stretch, or quant-adjacent unless future verified projects change the evidence base.

## Public vs. Private Boundary

This docs shell may include:

- live site links;
- public-safe architecture summaries;
- validation notes;
- recruiter-facing explanation;
- screenshots only after privacy review.

This docs shell must not include:

- private source code from the portfolio monorepo;
- resume DOCX archives or private resume variants;
- `.env` files, API keys, tokens, provider logs, or deployment internals;
- Avnet proprietary information;
- private financial, Schwab, Plaid, or banking data;
- raw transcripts, job-search records, or private career-planning notes;
- local machine paths or nested private repo contents.

## Validation Checklist

Before using the portfolio as a public profile proof surface:

- run lint and production build;
- check live routes render meaningful content;
- verify resume downloads;
- run assistant smoke and golden evals;
- check console warnings/errors;
- scan public copy for stale location/date wording, coming-soon language, unsupported quant claims, and hype-heavy agent/AI wording;
- confirm public GitHub links point only to `mp2123` or `*-Docs` repos.

## Resume Relevance

The website reinforces this public positioning:

```text
Business Analytics / BI / Data Analyst candidate with Power BI, SQL, Python, workflow automation, applied ML projects, and growing focus on financial data, market data, fintech, and quant-adjacent analytics.
```

It is meant to support current BI/data/analytics applications while documenting a careful path toward financial-data, market-data, fintech, data-science, and quant-adjacent opportunities.
