# Awesome Eve Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of production-ready AI agents built with [Eve](https://vercel.com/docs/eve).

## Contents

- [Knowledge & RAG](#knowledge--rag)
- [Research & Search](#research--search)
- [Data & Databases](#data--databases)
- [Documents & Content](#documents--content)
- [Developer Tools](#developer-tools)
- [Browser & Automation](#browser--automation)
- [Integrations](#integrations)
- [Utilities](#utilities)
- [What is Eve?](#what-is-eve)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)

## Knowledge & RAG

- **[Chat with PDF Agent](https://agentcn.vercel.app/docs/agents/eve/chat-with-pdf)** — Agent that indexes a PDF into a vector store and answers questions over it with page-cited retrieval.
- **[Company Knowledge Agent](https://agentcn.vercel.app/docs/agents/eve/company-knowledge)** — Agent that indexes internal documents into a vector store and answers questions over them, with PII redaction.
- **[Docs Chatbot Agent](https://agentcn.vercel.app/docs/agents/eve/docs-chatbot)** — Agent that answers questions about a library's functions by looking up structured documentation.

## Research & Search

- **[Deep Search Agent](https://agentcn.vercel.app/docs/agents/eve/deep-search)** — Agent that researches a question, evaluates its own findings, and iterates until the answer is complete and cited.
- **[Docs Expert Agent](https://agentcn.vercel.app/docs/agents/eve/docs-expert)** — Agent that answers questions about libraries and APIs by searching the live web and citing sources.
- **[AI SEO Audit Agent](https://agentcn.vercel.app/docs/agents/eve/ai-seo-audit)** — Agent that fetches a page through context.dev and scores its readability to AI answer engines across six categories, returning failing checks and an agent-ready fix prompt.

## Data & Databases

- **[Chat with Database Agent](https://agentcn.vercel.app/docs/agents/eve/text-to-sql)** — Agent that introspects a database schema, converts questions to SQL, and runs read-only queries.
- **[CSV to Questions Agent](https://agentcn.vercel.app/docs/agents/eve/csv-to-questions)** — Agent that summarizes a CSV dataset to stay within token limits, then generates focused analytical questions.
- **[Google Sheets Analysis Agent](https://agentcn.vercel.app/docs/agents/eve/google-sheets)** — Agent that reads, analyzes, and edits Google Sheets via the Sheets API.

## Documents & Content

- **[Meeting Notes Agent](https://agentcn.vercel.app/docs/agents/eve/meeting-notes)** — Agent that turns a raw meeting transcript into a structured summary, decisions, and action items.
- **[Customer Feedback Summary Agent](https://agentcn.vercel.app/docs/agents/eve/feedback-summary)** — Agent that retrieves, categorizes, and summarizes customer feedback into an executive report with recommendations.
- **[Flash Cards from PDF Agent](https://agentcn.vercel.app/docs/agents/eve/flashcards-pdf)** — Agent that turns a PDF into study flash cards, with optional AI-generated images per concept.
- **[Chat with YouTube Agent](https://agentcn.vercel.app/docs/agents/eve/chat-with-youtube)** — Agent that fetches a video's metadata and transcript, then answers questions with clickable timestamp citations.
- **[Extract DESIGN.md Agent](https://agentcn.vercel.app/docs/agents/eve/extract-design-md)** — Agent that pulls a site's design tokens, brand assets, screenshot, and page Markdown through context.dev and composes a self-contained DESIGN.md design-system document.

## Developer Tools

- **[GitHub PR Code Review Agent](https://agentcn.vercel.app/docs/agents/eve/github-review)** — Agent that fetches a GitHub pull request and returns adaptive, file-by-file code review feedback.

## Browser & Automation

- **[Browser Agent](https://agentcn.vercel.app/docs/agents/eve/browser-agent)** — Agent that drives a real browser with Playwright using a snapshot-and-selector pattern to complete web tasks.
- **[Claw Autonomous Assistant](https://agentcn.vercel.app/docs/agents/eve/claw)** — Agent that operates a sandboxed workspace — read/write files and run shell commands — to finish multi-step tasks.

## Integrations

- **[Slack Agent](https://agentcn.vercel.app/docs/agents/eve/slack-agent)** — Agent that replies to Slack mentions and DMs, threaded, via the Slack Web API.

## Utilities

- **[Weather Agent](https://agentcn.vercel.app/docs/agents/eve/weather)** — Agent that looks up current weather for a location via the Open-Meteo API.

## What is Eve?

Eve is an agent framework where each recipe is a single agent — a model, a system prompt, and a set of tools — that you can drop into your app and deploy anywhere your JavaScript runs.

Learn more at [vercel.com/docs/eve](https://vercel.com/docs/eve).

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold it.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=shadcn-labs/awesome-eve-agents&type=Date)](https://star-history.com/#shadcn-labs/awesome-eve-agents&Date)
