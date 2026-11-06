# List of Free Google AI Tools

> 15 free Google AI tools nobody talks about — the stack worth $300+/mo that google quietly ships for free.
>
> no hype. honest writeups including what's free, what isn't, and the catch.

curated by [@exploraX_](https://x.com/exploraX_).

---

## the rules

- must be a Google AI product or open-source release
- must have a meaningful free tier (not just a trial)
- must be actively maintained as of 2026
- if there's a catch (regional waitlist, paid features mixed in, daily limits), it gets named in the writeup

**important:** "free" doesn't mean "unlimited." every tool below has caps. the writeups state them honestly so you know what you're getting.

---

## the list

| # | tool | category | what it replaces | catch? |
|---|------|----------|------------------|--------|
| 1 | [Pomelli](#1-pomelli) | AI marketing | jasper + copy.ai + a junior brand marketer | beta — paid tiers coming |
| 2 | [Stitch](#2-stitch) | AI UI designer | galileo AI + early-stage figma | regional beta |
| 3 | [Opal](#3-opal) | no-code workflow builder | n8n + zapier | US-first, experimental |
| 4 | [Antigravity](#4-antigravity) | agentic IDE | cursor ($20/mo) | free requests slashed to ~20/day |
| 5 | [Mixboard](#5-mixboard) | AI moodboard | canva + pinterest + milanote | US-only + waitlist |
| 6 | [Disco](#6-disco) | web discovery | manual tab wrangling | macOS-only + waitlist |
| 7 | [NotebookLM](#7-notebooklm) | research assistant | notion AI + perplexity + readwise | daily caps |
| 8 | [Learn Your Way](#8-learn-your-way) | AI learning | paid tutoring | waitlist for your own PDFs |
| 9 | [Flow Music](#9-flow-music) | AI music studio | suno + udio ($10/mo) | age-gated, daily caps |
| 10 | [Google AI Studio](#10-google-ai-studio) | vibe coder | openai playground + paid API credits | none |
| 11 | [Jules](#11-jules) | autonomous coding agent | devin + cursor agent | 15 tasks/day |
| 12 | [Gemini CLI](#12-gemini-cli) | terminal/CLI | claude code ($20/mo by default) | none |
| 13 | [Code Wiki](#13-code-wiki) | github visualiser | mintlify + devin deepwiki | public repos only |
| 14 | [Firebase Studio](#14-firebase-studio) | backend mgmt | replit + backend dashboards | ⚠️ sunsetting, signups closed |
| 15 | [Gemini Code Assist](#15-gemini-code-assist) | coding extension | github copilot ($10/mo) | none |

---

## 1. Pomelli

**replaces:** jasper + copy.ai + a junior brand marketer
**url:** [labs.google/pomelli](https://labs.google/pomelli)

point it at your website and it reverse-engineers your "Business DNA" — voice, colors, audience — then generates on-brand social posts, campaigns, and marketing images you can edit and export. built by Google Labs + DeepMind.

**free tier:** completely free in beta. no credit card, no generation limit, no watermark on exports. expanded from a 4-country beta to 170+ countries in march 2026.

**the catch:** still an experimental beta — Google has signaled paid tiers are coming once it exits beta. 18+, Google account required. and it's only as good as your website: thin site in, generic brand out.

---

## 2. Stitch

**replaces:** galileo AI + early-stage figma work
**url:** [stitch.withgoogle.com](https://stitch.withgoogle.com)

google's free figma killer. describe an interface, get production-ready HTML/CSS/Tailwind + figma export. the 2026 update added voice canvas, infinite canvas, and MCP integration with cursor.

**free tier:** 350 standard + 200 experimental generations per month.

**the catch:** still in Google Labs beta. unavailable in some countries. output quality is solid but generic — it generates from its own models, not your team's design system.

---

## 3. Opal

**replaces:** n8n + zapier (for AI mini-apps)
**url:** [opal.withgoogle.com](https://opal.withgoogle.com)

build no-code AI mini-apps and multi-step workflows by describing them in plain language. chain prompts, models, and an agent step into a visual pipeline, then share it on a Google-hosted link. basically a free n8n with Gemini baked in.

**free tier:** free with no published usage caps. app creation, the visual editor, the agent step, Gemini access, and hosted sharing are all included on a standard Google account.

**the catch:** rolled out US-first and still expanding. as a Labs experiment it can be reprioritized or shut down, and heavy workflows can still bump into underlying Gemini quotas even though Opal itself doesn't charge.

---

## 4. Antigravity

**replaces:** cursor ($20/mo) + windsurf
**url:** [antigravity.google](https://antigravity.google)

google's agentic IDE — the self-styled "cursor-killer." describe a feature and agents plan, edit across files, run tests, and build full apps from text prompts. free-tier users get Gemini 3 Pro, Claude Sonnet 4.5, and GPT-OSS models inside the editor.

**free tier:** $0, no card. unlimited tab completions and editor basics, plus a daily allowance of agent requests.

**the catch:** the agent allowance is the pressure point. the free daily request cap was cut hard after launch (from ~250 to ~20/day by late 2025) and Google has signaled the free offering may keep shifting. great to try, risky to build a daily workflow around until the limits settle.

---

## 5. Mixboard

**replaces:** canva + pinterest + milanote (moodboards)
**url:** [labs.google/mixboard](https://labs.google/mixboard)

a mix of canva and pinterest where you generate and combine AI images into moodboards. start from a text prompt or a pre-filled board, drop in your own images, and edit right on the canvas with natural language, powered by the Nano Banana image model.

**free tier:** free while in beta.

**the catch:** US-only during beta with a Google Labs waitlist for wider access. the high-end models (Nano Banana Pro / Gemini 3) have daily usage limits, and premium pricing hasn't been announced yet.

---

## 6. Disco

**replaces:** manual tab wrangling + custom dashboards
**url:** [labs.google/disco](https://labs.google/disco)

turns your open browser tabs into interactive AI apps ("GenTabs") built with Gemini 3. competitor tabs become a comparison matrix, travel tabs become an itinerary, recipe blogs become a meal planner with a shopping list — no code, just describe what you want.

**free tier:** free Google Labs experiment.

**the catch:** macOS-only and behind a waitlist right now. squarely experimental — the kind of Labs project that can change shape or get folded into something else without notice.

---

## 7. NotebookLM

**replaces:** notion AI + perplexity + readwise
**url:** [notebooklm.google](https://notebooklm.google)

upload sources (PDFs, websites, audio, YouTube). it summarizes, builds mind maps, generates quizzes, drafts slide decks, even turns your notes into a podcast you can listen to on a walk. genuinely changes how you research dense material.

**free tier:** 100 notebooks total. 50 sources per notebook. 50 chat queries/day. 3 audio overviews/day. 3 video overviews/day. 10 reports/day.

**the catch:** the 50-source-per-notebook cap is real. for big research projects you'll split material across notebooks. Plus tier ($7.99/mo via Google AI Plus) raises it to 300 sources if you outgrow free.

---

## 8. Learn Your Way

**replaces:** paid tutoring + generic online courses
**url:** [learnyourway.withgoogle.com](https://learnyourway.withgoogle.com)

turns any topic into a personalized, AI-built course. it takes educational content and regenerates it into multiple formats — immersive text with embedded questions, audio lessons, narrated slides, mind maps, and quizzes — adapted to how you learn.

**free tier:** free to use, with plenty of ready-made sources to explore.

**the catch:** uploading your *own* PDFs is behind a waitlist. it's a Google Labs experiment aimed at students, so expect the usual experimental-tool uncertainty around longevity.

---

## 9. Flow Music

**replaces:** suno + udio ($10/mo)
**url:** [flowmusic.app](https://flowmusic.app)

chat with an AI producer to generate full, produced songs — vocals, melody, arrangement — from a plain text prompt. runs on Google's Lyria model inside the broader Flow creative suite, with a stem splitter and an AI music-video generator (Veo) attached.

**free tier:** free on web and iOS. every generated track ships with full commercial rights for YouTube, podcasts, ads, and film — no extra fees.

**the catch:** Google sign-in + age verification to start, and generation is capped daily like the rest of the Flow suite. the heavy Veo music-video features lean on the same paid Flow / Google AI Pro allowances as regular video generation.

---

## 10. Google AI Studio

**replaces:** openai playground + paid API credits
**url:** [aistudio.google.com](https://aistudio.google.com)

web playground for gemini 3 pro and flash, and a fast "vibe coder" for prototyping MVPs and spinning up AI apps in seconds. comes with a free API key, generous rate limits, and a 1M-token context window that it actually uses.

**free tier:** generous daily quotas across all gemini models including pro. free API key for personal use.

**the catch:** the free API key has rate limits — fine for prototyping and personal projects, not for production. terms of service forbid using free-tier output to train competing models.

---

## 11. Jules

**replaces:** devin ($20/mo) + cursor agent ($20/mo)
**url:** [jules.google](https://jules.google)

assign jules a github issue. it spins up a secure cloud VM, clones your repo, writes a plan, makes the changes, opens a PR. you review the diff and merge.

**free tier:** 15 tasks/day, 3 concurrent tasks, runs on gemini flash.

**the catch:** flash isn't as strong as the pro model for complex changes. and 15 tasks/day fills up fast if you're using it seriously. pro tier ($19.99/mo) gives you 5x the limits and gemini 3.1 pro.

---

## 12. Gemini CLI

**replaces:** claude code ($20/mo by default)
**repo:** [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)
**license:** Apache 2.0

google's official open-source terminal agent. one command (`npx @google/gemini-cli`) and you've got an agent in your terminal that reads your codebase, runs shell commands, edits files, and ships PRs.

**free tier:** entire CLI is free. uses your free AI Studio API key.

**the catch:** subject to the same free API rate limits as AI Studio. for heavy daily use you may hit caps. easy fix: also wire it to a paid OpenRouter or Anthropic key as a fallback.

---

## 13. Code Wiki

**replaces:** mintlify + manual docs + devin's deepwiki
**url:** [codewiki.google](https://codewiki.google)

a self-updating wiki that explains an entire codebase using Gemini. point it at any public GitHub repo and it generates structured docs, architecture/class/sequence diagrams, and a Gemini-powered chat — every section hyperlinked straight to the relevant code, and it re-generates after each commit.

**free tier:** free for any public GitHub repository.

**the catch:** public repos only. private-repo support is a separate, waitlisted Gemini CLI extension you run on your own infra. launched as a public preview in late 2025, so features are still moving.

> note: some lists point "Codewiki" at `github.com/deepwiki` — that's Cognition's DeepWiki, a different product. Google's tool lives at [codewiki.google](https://codewiki.google).

---

## 14. Firebase Studio

**replaces:** replit + backend dashboards
**url:** [firebase.studio](https://firebase.studio)

a visual, AI-boosted cockpit for building apps and managing backend data and cloud logic, with Gemini wired in across the workspace.

**free tier:** the no-cost plan allowed 3 workspaces per user (up to 10 via the Google Developer Program, 30 via Premium).

**the catch:** ⚠️ **this one's on the way out.** Google disabled new workspace creation and new-user signup on **June 22, 2026**, and Firebase Studio is scheduled to sunset on **March 22, 2027**. if you're not already in, you can't get in — kept on the list for completeness, but treat it as deprecated, not something to start a new project on.

---

## 15. Gemini Code Assist

**replaces:** github copilot ($10/mo)
**url:** [codeassist.google](https://codeassist.google)

a professional AI pair programmer that drops into VS Code, JetBrains, Cursor, and GitHub. code completion, chat, and AI-powered code reviews on your PRs — with a genuinely free individual tier, not just a trial.

**free tier:** free for individuals since march 2026 — 180,000 code completions/month, 240 chat requests/day, plus AI code reviews in GitHub.

**the catch:** the free tier is the individual plan — no team admin, policy, or enterprise controls (those are the paid Standard / Enterprise tiers). check the free-tier data-usage terms before pointing it at proprietary code.

---

## disclaimers

**on "free."** every tool above has limits. "free" means "you can get real value without paying," not "unlimited." the writeups state the actual caps.

**on availability.** several Labs tools (Stitch, Opal, Mixboard, Disco, Learn Your Way) have regional waitlists or country restrictions. if a link doesn't work for you, that's why.

**on stability.** Google Labs experiments can get shuttered, migrated, or paywalled with little notice — Firebase Studio is the cautionary tale here. this list is accurate as of mid-2026 — check each tool's current status before building a workflow around it.

**on the replacements.** these don't always match the polish of their paid counterparts. NotebookLM's free tier won't replace a paid Notion AI workspace for a team. Jules' free tier won't replace Devin for a production codebase. these are starting points, not endpoints.

---

## related

see also [`open-source-vs-saas`](https://github.com/Moh4696/open-source-vs-saas) — 10 open-source github repos that replace major paid SaaS tools.

---

## contributing

found a free Google AI tool that belongs here? open a PR with:
- official google URL
- what's actually free vs paid
- the honest catch

no submissions accepted without an honest "catch" section. that's the whole point.

---

## license

this list and writeups are CC0 — public domain. fork, remix, repost, no attribution needed.

the individual tools listed are owned by Google. see each tool's terms of service for usage details.

## Companion Open Knowledge Format (OKF) Voice Hardware

- **[OneMira C1](https://onemira.com/products/c1)** — Standalone local AI voice recorder (`Works Standalone` · `✨ Local AI` · `🗣️ Speaker ID` · `Zero Cloud`, `$0/month`) built on Google's Open Knowledge Format (OKF) standard for local Markdown and Wiki context.
