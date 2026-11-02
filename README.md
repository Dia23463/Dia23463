# Hi, I'm Dia

CS and Economics at UMass Amherst (class of 2028). I started out on frontend teams, got curious about what happens after a request leaves the browser, and now spend most of my time on the backend: authentication, data pipelines, and making systems keep working when something fails.

Right now I'm taking computer systems, learning how processes and memory work underneath the code I write.

## What I've been up to

- **AI Engineering Intern, Commonwealth of Massachusetts (BRPC).** Built a serverless RAG assistant on AWS (Lambda, S3, Bedrock, OpenSearch, DynamoDB, Cognito) that lets regional planners search 150+ planning documents across 32 towns, with every answer cited to its source. I owned:
  - **Authentication and authorization:** Cognito sign-in, a server-side admin proxy, and a short-lived HMAC token so a public Lambda endpoint only serves verified users. Found and fixed two security vulnerabilities, including an admin role-spoofing bug.
  - **Ingestion:** a web crawler built to survive slow servers and Lambda time limits (per-file deadlines, self-resuming runs, skipping unchanged files), plus a metadata pipeline that tags documents for filtered search.
  - **Citation auditing:** a second-pass check that drops any citation that isn't actually the source of a claim.
  - **Admin dashboard, deployment, and tests** for the crawler and metadata pipeline.

  The code is private, so there's no repo to link.
- **Snowflake AI Studio Fellow.** Geospatial ML on Census and CMS data to find healthcare deserts in New York State.
- **Capital One 2026 Tech Summit, 3rd place.** Access Prep, a multilingual assistant that helps people new to the US credit system prepare for applications like credit cards. My team built it in a weekend, and I built the multi-language support.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [RecessionIQ](https://github.com/Dia23463/RecessionIQ) | Dashboard tracking recession signals (CPI, unemployment, the yield curve) from Fed data, plus cross-market correlations from Yahoo Finance. | Next.js, TypeScript, Vercel |
| [Access Prep](https://github.com/ryanvaby/Access-Prep) | Helps students, immigrants, and freelancers with little or no US credit history prepare for credit card applications: an intake form, a chatbot that explains the process in plain language, and OCR that checks uploaded documents are the right type. 3rd place at Capital One's 2026 Tech Summit. I built the multi-language support. | React, TypeScript, Flask, LangChain, Gemini |
| [Healthcare deserts](https://github.com/Dia23463/snowflake-healthcare-desert-prediction-btt-project) | Predicts which areas of New York State lack healthcare access, with GenAI summaries of the results. | Python, scikit-learn, Snowflake |
| [Mutual fund calculator](https://github.com/TheRealBKJ/ELS_Technical_Challenge) | Mutual fund calculator using CAPM, with interactive sliders and an AI assistant whose guardrails block financial advice. | React, shadcn/ui, FastAPI, OpenAI |
| [Kapok](https://github.com/ShreyanshMisra/Kapok) | Offline-first disaster-response app for volunteer teams. Tasks save locally first and sync to Firebase when the signal comes back. Contributed as part of BUILD UMass. | Flutter, Firebase, Hive, BLoC, Mapbox |

## Tech I use

**Languages:** Python, TypeScript, JavaScript
**Backend:** Flask, FastAPI, Next.js API routes, REST
**Cloud:** AWS (Lambda, S3, DynamoDB, OpenSearch, Bedrock, Cognito), Firebase, Vercel
**AI/ML:** RAG, LangChain, LLM APIs (Bedrock, OpenAI, Gemini), scikit-learn, pandas
**Frontend and mobile:** React, Next.js, Flutter

## Find me

- LinkedIn: [in/diasutaria](https://www.linkedin.com/in/diasutaria)
- To learn what I am curious about: [medium](https://medium.com/@athena.parthenos10621)
- Happy to talk about backend systems, RAG pipelines, or anything at the intersection of finance and data.
