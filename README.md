# Awesome Eve Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of production-ready AI agents built with [Eve](https://vercel.com/docs/eve).

Every agent below is a complete, copy-paste recipe from [agentcn](https://agentcn.vercel.app) — a shadcn-style registry of agents. Add one to your project with a single command:

```bash
npx shadcn@latest add @agentcn/eve/<agent>
```

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

## Knowledge & RAG

- **[Chat with PDF Agent](https://agentcn.vercel.app/docs/agents/eve/chat-with-pdf)** — Agent that indexes a PDF into a vector store and answers questions over it with page-cited retrieval.
  <br>`npx shadcn@latest add @agentcn/eve/chat-with-pdf`
- **[Company Knowledge Agent](https://agentcn.vercel.app/docs/agents/eve/company-knowledge)** — Agent that indexes internal documents into a vector store and answers questions over them, with PII redaction.
  <br>`npx shadcn@latest add @agentcn/eve/company-knowledge`
- **[Docs Chatbot Agent](https://agentcn.vercel.app/docs/agents/eve/docs-chatbot)** — Agent that answers questions about a library's functions by looking up structured documentation.
  <br>`npx shadcn@latest add @agentcn/eve/docs-chatbot`

## Research & Search

- **[Deep Search Agent](https://agentcn.vercel.app/docs/agents/eve/deep-search)** — Agent that researches a question, evaluates its own findings, and iterates until the answer is complete and cited.
  <br>`npx shadcn@latest add @agentcn/eve/deep-search`
- **[Docs Expert Agent](https://agentcn.vercel.app/docs/agents/eve/docs-expert)** — Agent that answers questions about libraries and APIs by searching the live web and citing sources.
  <br>`npx shadcn@latest add @agentcn/eve/docs-expert`
- **[AI SEO Audit Agent](https://agentcn.vercel.app/docs/agents/eve/ai-seo-audit)** — Agent that fetches a page through context.dev and scores its readability to AI answer engines across six categories, returning failing checks and an agent-ready fix prompt.
  <br>`npx shadcn@latest add @agentcn/eve/ai-seo-audit`

## Data & Databases

- **[Chat with Database Agent](https://agentcn.vercel.app/docs/agents/eve/text-to-sql)** — Agent that introspects a database schema, converts questions to SQL, and runs read-only queries.
  <br>`npx shadcn@latest add @agentcn/eve/text-to-sql`
- **[CSV to Questions Agent](https://agentcn.vercel.app/docs/agents/eve/csv-to-questions)** — Agent that summarizes a CSV dataset to stay within token limits, then generates focused analytical questions.
  <br>`npx shadcn@latest add @agentcn/eve/csv-to-questions`
- **[Google Sheets Analysis Agent](https://agentcn.vercel.app/docs/agents/eve/google-sheets)** — Agent that reads, analyzes, and edits Google Sheets via the Sheets API.
  <br>`npx shadcn@latest add @agentcn/eve/google-sheets`

## Documents & Content

- **[Meeting Notes Agent](https://agentcn.vercel.app/docs/agents/eve/meeting-notes)** — Agent that turns a raw meeting transcript into a structured summary, decisions, and action items.
  <br>`npx shadcn@latest add @agentcn/eve/meeting-notes`
- **[Customer Feedback Summary Agent](https://agentcn.vercel.app/docs/agents/eve/feedback-summary)** — Agent that retrieves, categorizes, and summarizes customer feedback into an executive report with recommendations.
  <br>`npx shadcn@latest add @agentcn/eve/feedback-summary`
- **[Flash Cards from PDF Agent](https://agentcn.vercel.app/docs/agents/eve/flashcards-pdf)** — Agent that turns a PDF into study flash cards, with optional AI-generated images per concept.
  <br>`npx shadcn@latest add @agentcn/eve/flashcards-pdf`
- **[Chat with YouTube Agent](https://agentcn.vercel.app/docs/agents/eve/chat-with-youtube)** — Agent that fetches a video's metadata and transcript, then answers questions with clickable timestamp citations.
  <br>`npx shadcn@latest add @agentcn/eve/chat-with-youtube`
- **[Extract DESIGN.md Agent](https://agentcn.vercel.app/docs/agents/eve/extract-design-md)** — Agent that pulls a site's design tokens, brand assets, screenshot, and page Markdown through context.dev and composes a self-contained DESIGN.md design-system document.
  <br>`npx shadcn@latest add @agentcn/eve/extract-design-md`

## Developer Tools

- **[GitHub PR Code Review Agent](https://agentcn.vercel.app/docs/agents/eve/github-review)** — Agent that fetches a GitHub pull request and returns adaptive, file-by-file code review feedback.
  <br>`npx shadcn@latest add @agentcn/eve/github-review`

## Browser & Automation

- **[Browser Agent](https://agentcn.vercel.app/docs/agents/eve/browser-agent)** — Agent that drives a real browser with Playwright using a snapshot-and-selector pattern to complete web tasks.
  <br>`npx shadcn@latest add @agentcn/eve/browser-agent`
- **[Claw Autonomous Assistant](https://agentcn.vercel.app/docs/agents/eve/claw)** — Agent that operates a sandboxed workspace — read/write files and run shell commands — to finish multi-step tasks.
  <br>`npx shadcn@latest add @agentcn/eve/claw`

## Integrations

- **[Slack Agent](https://agentcn.vercel.app/docs/agents/eve/slack-agent)** — Agent that replies to Slack mentions and DMs, threaded, via the Slack Web API.
  <br>`npx shadcn@latest add @agentcn/eve/slack-agent`

## Utilities

- **[Weather Agent](https://agentcn.vercel.app/docs/agents/eve/weather)** — Agent that looks up current weather for a location via the Open-Meteo API.
  <br>`npx shadcn@latest add @agentcn/eve/weather`

## What is Eve?

Eve is an agent framework where each recipe is a single agent — a model, a system prompt, and a set of tools — that you can drop into your app and deploy anywhere your JavaScript runs.

agentcn ships every recipe for both [Eve](https://vercel.com/docs/eve) and [Flue](https://flueframework.com), so you can pick the framework that fits your stack. See the [Flue companion list](https://github.com/shadcn-labs/awesome-flue-agents).

## Contributing

Contributions are welcome! New agent recipes are added to the [agentcn registry](https://agentcn.vercel.app) first — open a pull request there, and the agent will show up here. To add or fix an entry in this list, open a PR against this repo.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.
