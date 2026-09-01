<div align="center">

# 🛠️ Awesome Free Developer Tools

**A carefully curated list of free and open-source tools for developers — editors, AI coding agents, APIs, databases, deploy, and daily workflow**

*Continuously collected · Manually verified · Opinionated curation*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/EthanYolo01/awesome-free-dev-tools/issues)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/last%20updated-September%202026-blue?style=flat-square)](https://github.com/EthanYolo01/awesome-free-dev-tools/commits/main)
[![Stars](https://img.shields.io/github/stars/EthanYolo01/awesome-free-dev-tools?style=flat-square)](https://github.com/EthanYolo01/awesome-free-dev-tools/stargazers)

> **Opinionated curation over exhaustive listing.**
> Every entry was reviewed. We tell you *why* each tool matters and *when* to use it — not just dump another “top 100” page.

**Developer tooling landscape (September 2026):** 🔓 self-hosting is back in the mainstream &nbsp;·&nbsp; 🤖 AI coding agents moved from plugins to full terminals &nbsp;·&nbsp; 🔌 MCP became a Linux Foundation standard &nbsp;·&nbsp; ☁️ Vercel / Cloudflare open-sourced production agent kits &nbsp;·&nbsp; ⚖️ license forks (OpenTofu, Valkey, Forgejo) keep the commons alive

---

🌐 Language / 语言切换：**English** | [中文](README_CN.md)

</div>

---

## 📋 Table of Contents

- [🧭 Curation principles](#-curation-principles)
- [🏁 How to use this list](#-how-to-use-this-list)
- [⏳ Timeline](#-timeline)
- [💻 Code Editors](#-code-editors)
- [🤖 AI Coding Agents & Assistants](#-ai-coding-agents--assistants)
- [🔌 MCP Ecosystem](#-mcp-ecosystem)
- [🧩 Agent Skills](#-agent-skills)
- [🕸️ Agent Frameworks, Sandboxes & Memory](#️-agent-frameworks-sandboxes--memory)
- [☁️ Cloud-Vendor Open Agent Infra](#️-cloud-vendor-open-agent-infra)
- [🌐 Cloud / Agent Browsers](#-cloud--agent-browsers)
- [💰 Billing / Payments / Subscriptions](#-billing--payments--subscriptions)
- [🔀 Git Hosting & Version Control](#-git-hosting--version-control)
- [🔌 API Development & Testing](#-api-development--testing)
- [⌨️ Terminal / Shell / CLI](#️-terminal--shell--cli)
- [🗄️ Database Tools](#️-database-tools)
- [🎨 Design, Diagrams & Prototyping](#-design-diagrams--prototyping)
- [📦 Containers / Kubernetes / IaC](#-containers--kubernetes--iac)
- [🚀 Self-hosted Deploy / PaaS](#-self-hosted-deploy--paas)
- [📈 Monitoring / Logs / Errors](#-monitoring--logs--errors)
- [📚 Docs & Knowledge Bases](#-docs--knowledge-bases)
- [📋 Project Management & Collaboration](#-project-management--collaboration)
- [✅ Code Quality & Testing](#-code-quality--testing)
- [🧱 Frontend UI & Tooling](#-frontend-ui--tooling)
- [🖥️ Cross-platform Desktop Frameworks](#️-cross-platform-desktop-frameworks)
- [📊 Product Analytics](#-product-analytics)
- [🎬 Code → Screenshot / GIF / Video](#-code--screenshot--gif--video)
- [📝 README / Changelog / Commits](#-readme--changelog--commits)
- [🔒 Security & Privacy](#-security--privacy)
- [⚡ Runtimes & Package Managers](#-runtimes--package-managers)
- [🧰 Swiss-army Toolboxes](#-swiss-army-toolboxes)
- [🧩 Browser Extensions](#-browser-extensions)
- [📖 Learning Resources](#-learning-resources)
- [🗺️ Related Awesome Lists](#️-related-awesome-lists)
- [🤝 Contributing](#-contributing)

---

## 🧭 Curation principles

This list is **not** “the more links the better.” Entries have to clear a bar:

1. **Open source / self-host / free first** — if a solid OSS, self-hosted, or genuinely free option exists, we lead with it (Yaak over Postman, Plane over Linear).
2. **No greatest-hits dump** — we skip the tools everyone already has bookmarked (VS Code and Docker stay as infrastructure exceptions). Prefer sharp niche tools or projects that broke out in the last 1–2 years.
3. **Shippable, not a demo** — you can download, deploy, or open a URL today. No vaporware.
4. **One slot, one default** — we don’t stack five clones of the same job. If two stay, they have a real split (“pick A for speed, B for features”).
5. **Say *why*** — every row should answer: what pain it kills, and how it differs from the obvious alternative.

---

## 🏁 How to use this list

```
You need to...
├── Write code without a cloud IDE lock-in?
│   └── Neovim / Helix / Zed / VSCodium
├── Pair with an AI that actually edits the repo?
│   └── OpenCode, Aider, Cline, Continue, Tabby + Ollama
├── Give an agent tools, a browser, Skills, or memory?
│   └── MCP + Agent Skills (agentskills.io / skills.sh) + LiteLLM + browser-use / Playwright / agent-browser + Mem0 / Letta
├── Ship a SaaS without a $200/mo stack?
│   └── Coolify or Dokploy · Polar or Lago · PostHog · Uptime Kuma
├── Stop paying Postman / Figma / Linear / Notion?
│   └── Yaak or Bruno · Penpot · Plane · AFFiNE or Outline
└── Keep Git, infra, and secrets on your own metal?
    └── Forgejo/Gitea · OpenTofu · Vaultwarden
```

**One-line summary:** A typical “free tools” gist = random bookmarks. This list = **defaults you can actually run**, with GitHub links so you can verify license, activity, and stars yourself.

---

## ⏳ Timeline

```
2023    ──  Local-first revolt: people fork or replace SaaS after license shocks
            Podman, Gitea, and self-hosted PaaS leave the “hobby” ghetto

2024    ──  OpenTofu forks Terraform (Linux Foundation)
            Valkey forks Redis after the license change
            Forgejo / Gitea stay the default “GitHub at home”
            Coolify explodes as “Vercel on my VPS”
            shadcn/ui becomes the default React UI copy-paste kit
            Tauri 2 and Bun eat mindshare from Electron / npm

2025    ──  MCP donated to the Linux Foundation (Agentic AI Foundation)
            AI coding leaves the chat pane: Cline, Aider, Continue, OpenCode
            browser-use / Playwright MCP make “agent clicks the web” boringly real
            Biome / Oxlint start replacing ESLint+Prettier in new repos
            Vercel AI SDK + Cloudflare Agents SDK go from samples to production kits

2026    ──  Terminal coding agents (OpenCode, Pi harness) go mainstream
            Agent sandboxes (E2B) and memory layers (Letta, Mem0) are table stakes
            Polar / Lago make usage billing for token/GPU products self-hostable
            Agent Skills become a portable “install one command, teach the agent a job” format
            Cloud browsers (Steel, Lightpanda, Vercel agent-browser) exist specifically for agents
            DeepSeek Harness (dsh) open-sources a plugin-first coding agent harness
            Self-hosted analytics (PostHog) is the indie-SaaS default, not GA
```

---

## 💻 Code Editors

Modal, fast, and not locked to a single vendor’s telemetry.

| Editor | Site / GitHub | Why it is here |
|---|---|---|
| ⭐ **Neovim** | [neovim.io](https://neovim.io) · [neovim/neovim](https://github.com/neovim/neovim) | Modern Vim. LazyVim / AstroNvim drop the config cliff; plugin ecosystem is still the deepest in terminals |
| ⭐ **Helix** | [helix-editor.com](https://helix-editor.com) · [helix-editor/helix](https://github.com/helix-editor/helix) | Rust modal editor with LSP + Tree-sitter **built in**. Zero-config “it just works” |
| **Zed** | [zed.dev](https://zed.dev) · [zed-industries/zed](https://github.com/zed-industries/zed) | From the Atom team. Fastest multiplayer editing in this class |
| **Lapce** | [lapce.dev](https://lapce.dev) · [lapce/lapce](https://github.com/lapce/lapce) | Rust, native remote-dev, VS Code–like extensions without the Electron tax |
| **VSCodium** | [vscodium.com](https://vscodium.com) · [VSCodium/vscodium](https://github.com/VSCodium/vscodium) | VS Code without Microsoft telemetry and marketplace lock-in |
| **Eclipse Theia** | [theia-ide.org](https://theia-ide.org) · [eclipse-theia/theia](https://github.com/eclipse-theia/theia) | Cloud **and** desktop IDE framework if you need to ship a custom product |

---

## 🤖 AI Coding Agents & Assistants

The most competitive category in 2026. Preference: **open, model-agnostic, repo-native**.

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **OpenCode** | [opencode.ai](https://opencode.ai) | MIT terminal coding agent. Client/server, no vendor lock-in. The open Claude Code alternative that grew hardest in 2026 |
| ⭐ **Aider** | [aider.chat](https://aider.chat) · [paul-gauthier/aider](https://github.com/paul-gauthier/aider) | CLI pair-programmer. Edits the tree and writes Git commits. Git-native, any LLM |
| ⭐ **Cline** | [cline/cline](https://github.com/cline/cline) | Open agent in the editor: terminal + browser, approve each step, native MCP. Bring your own key |
| **Continue.dev** | [continue.dev](https://continue.dev) · [continuedev/continue](https://github.com/continuedev/continue) | Open VS Code / JetBrains assistant. Any API or local model; chat + edit + tab |
| **Tabby** | [tabby.tabbyml.com](https://tabby.tabbyml.com) · [TabbyML/tabby](https://github.com/TabbyML/tabby) | Self-hosted code completion. Code never leaves the LAN |
| **Ollama** | [ollama.com](https://ollama.com) · [ollama/ollama](https://github.com/ollama/ollama) | One-command local LLMs (including code models). The battery pack for a free, private stack |
| **Pi (Agent Harness)** | [earendil-works/pi](https://github.com/earendil-works/pi) | Tiny, hackable terminal coding harness: unified LLM APIs + agent loop + TUI. Kernel stays small; Skills/plugins fit *your* workflow |
| ⭐ **DeepSeek Harness (dsh)** | [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | Open-source agent harness from DeepSeek. **Everything is a plugin** — loop, tools, and workflows stay swappable instead of a closed Claude-Code-shaped box |

---

## 🔌 MCP Ecosystem

> MCP is the fastest-growing developer infrastructure of the last year. End of 2025 it landed in the Linux Foundation’s Agentic AI Foundation. We list **meta-tools** (inspect, author, gateway) — not the 10,000+ individual servers.

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **MCP Inspector** | [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) | Official debugger. See tools/resources your server actually exposes. Required if you write MCP servers |
| ⭐ **FastMCP** | [jlowin/fastmcp](https://github.com/jlowin/fastmcp) | Decorate a Python function → MCP server. Fastest way to ship a server today |
| **Context7** | [context7.com](https://context7.com) · [upstash/context7](https://github.com/upstash/context7) | Injects *current* library docs into coding agents. Kills stale-training-data API hallucinations. MIT server |
| **Playwright MCP** | [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | Official Microsoft MCP: click, screenshot, read the DOM. The default browser tool for agents |
| **GitHub MCP Server** | [github/github-mcp-server](https://github.com/github/github-mcp-server) | Official, free, open. Issues / PRs / repo contents from the agent |
| **Smithery** | [smithery.ai](https://smithery.ai) | Host + one-click install for MCP servers. Closest thing to “npm for MCP” |

---

## 🧩 Agent Skills

> MCP gives agents **tools**. Skills give agents **playbooks** — reusable folders of instructions, scripts, and references they load when a task matches. The format is showing up in OpenCode, Claude Code, Cursor, Gemini CLI, and more.

| Project | Site / GitHub | Why it is here |
|---|---|---|
| ⭐ **Agent Skills** | [agentskills.io](https://agentskills.io) | The open spec for portable agent skills: `SKILL.md` + optional scripts. Write once, run in any compatible coding agent |
| ⭐ **skills.sh** | [skills.sh](https://www.skills.sh) | Registry / CLI for reusable agent skills. One command to install a skill and give the agent procedural knowledge it did not ship with |

---

## 🕸️ Agent Frameworks, Sandboxes & Memory

> Agents went from “chat” to “do the job.” This layer is orchestration, safe code/browser execution, and memory that survives a session.

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **LangGraph** | [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | Graph/state-machine control: branches, checkpoints, resume. When ReAct loops are not enough |
| ⭐ **LiteLLM** | [BerriAI/litellm](https://github.com/BerriAI/litellm) | One Python SDK / proxy for **100+** LLM APIs (OpenAI-compatible). Keys, spend limits, load balancing, and fallbacks — including free / local routes (Ollama, etc.) so agents are not glued to one vendor |
| ⭐ **CrewAI** | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | Role-playing multi-agent. Lowest onboarding cost to test a team of agents |
| **Pydantic AI** | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | Type-safe Python agents. Structured I/O you can actually trust in production |
| **smolagents** | [huggingface/smolagents](https://github.com/huggingface/smolagents) | Hugging Face. Tiny core, Code-Agent style. Best afternoon to learn how agents work |
| ⭐ **browser-use** | [browser-use/browser-use](https://github.com/browser-use/browser-use) | Agents drive a real browser (forms, scrape, multi-step). MIT. Top-tier WebVoyager scores |
| ⭐ **E2B** | [e2b.dev](https://e2b.dev) · [e2b-dev/E2B](https://github.com/e2b-dev/E2B) | Isolated sandbox for AI-generated code. Answers “where does this even run?” |
| **Letta** (ex-MemGPT) | [letta-ai/letta](https://github.com/letta-ai/letta) | Long-term agent memory. Stops “forgot everything after the context window” |
| **Mem0** | [mem0ai/mem0](https://github.com/mem0ai/mem0) | Drop-in memory layer for any framework. Personalized, self-improving |
| **OpenHands** (ex-OpenDevin) | [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) | Autonomous SWE agent: read, test, PR. Oldest large OSS project in this niche |
| ⭐ **Langfuse** | [langfuse.com](https://langfuse.com) · [langfuse/langfuse](https://github.com/langfuse/langfuse) | Open LLM/agent observability: traces, tokens, latency, evals. Self-host or cloud free tier. Install before production |

---

## ☁️ Cloud-Vendor Open Agent Infra

Vercel and Cloudflare open-sourced production-shaped kits — fork them; they are not black boxes.

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **Vercel AI SDK** | [vercel/ai](https://github.com/vercel/ai) | TypeScript kit: OpenAI / Anthropic / Google, streaming, structured output, tools, HITL. Default for Next.js / full-stack AI |
| **Vercel Open Agents** | [Open Agents template](https://vercel.com/templates/template/open-agents) | Reference background coding agent: Web UI, runtime, sandboxes, GitHub. Meant to be forked |
| ⭐ **agent-browser** | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | Vercel Labs CLI for **AI-agent** browser automation. Fast, headless, built so an agent can click the web without dragging in a full test framework |
| ⭐ **Cloudflare Agents SDK** | [cloudflare/agents](https://github.com/cloudflare/agents) | Stateful agents on Workers + Durable Objects (SQL, WebSocket, cron). Edge-native, huge scale |
| **Cloudflare Agents Starter** | [cloudflare/agents-starter](https://github.com/cloudflare/agents-starter) | Chat agent template on Workers AI — no extra OpenAI/Anthropic key to start |
| **Cloudflare OS** | [cloudflare/cloudflare-os](https://github.com/cloudflare/cloudflare-os) | Internal agent workbench, open-sourced: Gatekeeper permissions, turn chats into docs/workflows/apps. Runs on open `workerd` |

---

## 🌐 Cloud / Agent Browsers

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **Steel** | [steel.dev](https://steel.dev) · [steel-dev/steel-browser](https://github.com/steel-dev/steel-browser) | Browser API built for agents: sessions, stealth, replay. Docker self-host or cloud. Puppeteer / Playwright / Selenium |
| ⭐ **Playwright** | [playwright.dev](https://playwright.dev) · [microsoft/playwright](https://github.com/microsoft/playwright) | Open-source browser automation from Microsoft. E2E tests **and** scraping/agent control (Chromium, Firefox, WebKit). Pair with [Playwright MCP](https://github.com/microsoft/playwright-mcp) when the caller is an LLM |
| ⭐ **agent-browser** | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | High-performance browser CLI from Vercel Labs, designed for AI agents rather than QA suites |
| **Lightpanda** | [lightpanda-io/browser](https://github.com/lightpanda-io/browser) | Headless browser in Zig from scratch (not a Chromium fork). ~1/9 Chrome RAM, ~11× faster in their benches. CDP-compatible |
| **BrowserOS** | [browseros.com](https://www.browseros.com) | Open Chromium fork with the agent *in* the browser. Local Claude/Gemini/Ollama; Chrome extensions still work |

---

## 💰 Billing / Payments / Subscriptions

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **Polar** | [polar.sh](https://polar.sh) · [polarsource/polar](https://github.com/polarsource/polar) | Apache 2.0 billing. Agent-step / GPU usage, subs, one-off, license keys, GitHub/Discord entitlements. Serious OSS alternative to “just Stripe” |
| **Lago** | [getlago.com](https://www.getlago.com) · [getlago/lago](https://github.com/getlago/lago) | Open usage-based billing (API calls, tokens). Self-host |

---

## 🔀 Git Hosting & Version Control

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **Gitea / Forgejo** | [gitea.com](https://about.gitea.com) · [forgejo.org](https://forgejo.org) | Light, self-hosted GitHub-like UI. Escape the platform |
| ⭐ **Lazygit** | [jesseduffield/lazygit](https://github.com/jesseduffield/lazygit) | Terminal Git TUI. Keyboard-only, viciously fast |
| **delta** | [dandavison/delta](https://github.com/dandavison/delta) | Syntax-highlighted, side-by-side `git diff` |
| **Git Graph** | [mhutchie/vscode-git-graph](https://github.com/mhutchie/vscode-git-graph) | Commit graph inside the editor |

---

## 🔌 API Development & Testing

| Project | Site / GitHub | Why it is here |
|---|---|---|
| ⭐ **Yaak** | [yaak.app](https://yaak.app) | Rust + Tauri. Local files. “Postman, but clean” |
| ⭐ **Bruno** | [usebruno.com](https://www.usebruno.com) | Collections as files in Git. No forced cloud login |
| **Hoppscotch** | [hoppscotch.io](https://hoppscotch.io) | Open web client; self-host if you want |
| **Mockoon** | [mockoon.com](https://mockoon.com) | Local mock APIs in minutes |
| **HTTPie** | [httpie.io](https://httpie.io) | Human `curl` for the command line |

---

## ⌨️ Terminal / Shell / CLI

| Project | Site / GitHub | Why it is here |
|---|---|---|
| **Alacritty** | [alacritty.org](https://alacritty.org) | GPU terminal, plain-text config, no bloat |
| **WezTerm** | [wezfurlong.org/wezterm](https://wezfurlong.org/wezterm) | Rust, cross-platform, multiplexer included |
| ⭐ **Starship** | [starship.rs](https://starship.rs) | Prompt for every shell. Fast, pretty, portable |
| ⭐ **fzf** | [junegunn/fzf](https://github.com/junegunn/fzf) | Fuzzy find files, history, branches — everywhere |
| ⭐ **ripgrep** | [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) | The grep you actually want in a repo |
| **fd** | [sharkdp/fd](https://github.com/sharkdp/fd) | `find` with sane defaults |
| **bat** | [sharkdp/bat](https://github.com/sharkdp/bat) | `cat` with syntax highlight + Git |
| **eza** | [eza.rocks](https://eza.rocks) | Modern `ls` |
| **jq** | [jqlang.github.io/jq](https://jqlang.github.io/jq/) | JSON on the CLI. Non-negotiable |

---

## 🗄️ Database Tools

| Project | Site / GitHub | Why it is here |
|---|---|---|
| ⭐ **DBeaver CE** | [dbeaver.io](https://dbeaver.io) | One client for almost every database |
| **Beekeeper Studio** | [beekeeperstudio.io](https://www.beekeeperstudio.io) | Modern SQL UI (core is open) |
| **pgAdmin** | [pgadmin.org](https://www.pgadmin.org) | Official PostgreSQL admin |
| **Adminer** | [adminer.org](https://www.adminer.org) | Single-file PHP. Deploy in one drop |
| **RedisInsight** | [redis.io/insight](https://redis.io/insight) | Official Redis GUI |
| **SurrealDB** | [surrealdb.com](https://surrealdb.com) | Multi-model DB that actually got traction |
| ⭐ **Valkey** | [valkey.io](https://valkey.io) | Redis community fork under the Linux Foundation. Fully open |

---

## 🎨 Design, Diagrams & Prototyping

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **Penpot** | [penpot.app](https://penpot.app) | Open Figma-class design + prototype. Self-host |
| ⭐ **Excalidraw** | [excalidraw.com](https://excalidraw.com) | Hand-drawn whiteboard. Fastest diagram for engineers |
| **tldraw** | [tldraw.dev](https://tldraw.dev) | Embeddable canvas SDK |
| **D2** | [d2lang.com](https://d2lang.com) | Text → architecture diagrams. Diffable in Git |
| **Mermaid** | [mermaid.js.org](https://mermaid.js.org) | Diagrams in Markdown. GitHub renders them natively |

---

## 📦 Containers / Kubernetes / IaC

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **Podman** | [podman.io](https://podman.io) | Daemonless Docker-compatible engine |
| **Portainer CE** | [portainer.io](https://www.portainer.io) | Visual container ops |
| **k3s / Kind / Minikube** | [k3s.io](https://k3s.io) · [kind](https://kind.sigs.k8s.io) · [minikube](https://minikube.sigs.k8s.io) | Kubernetes that fits a laptop or the edge |
| **Lens** | [k8slens.dev](https://k8slens.dev) | Desktop Kubernetes IDE |
| ⭐ **OpenTofu** | [opentofu.org](https://opentofu.org) | Terraform community fork. Open IaC after the license split |

---

## 🚀 Self-hosted Deploy / PaaS

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **Coolify** | [coolify.io](https://coolify.io) | Vercel/Heroku feel on your VPS. The breakout self-hosted PaaS |
| **Dokploy** | [dokploy.com](https://dokploy.com) | Newer; native Docker Compose; growing fast |
| **CapRover** | [caprover.com](https://caprover.com) | Veteran one-click apps + databases |

---

## 📈 Monitoring / Logs / Errors

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **Uptime Kuma** | [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | Beautiful self-hosted uptime. Open UptimeRobot |
| **GlitchTip** | [glitchtip.com](https://glitchtip.com) | Light open Sentry alternative |
| **Grafana + Prometheus** | [grafana.com](https://grafana.com) · [prometheus.io](https://prometheus.io) | The open metrics stack. Still the default |

---

## 📚 Docs & Knowledge Bases

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **AFFiNE** | [affine.pro](https://affine.pro) | Notion + Miro: blocks and a whiteboard. Fast growth |
| **Outline** | [getoutline.com](https://www.getoutline.com) | Team wiki with a Notion-like UI. Self-host |
| **Docusaurus** | [docusaurus.io](https://docusaurus.io) | Meta’s docs site generator |
| **VitePress** | [vitepress.dev](https://vitepress.dev) | Fast Vite docs. Great for libraries |

---

## 📋 Project Management & Collaboration

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **Plane** | [plane.so](https://plane.so) | Open Linear/Jira. Issues + projects. Self-host |
| **Huly** | [huly.io](https://huly.io) | Projects + docs + chat. Notion + Linear + Slack ambition |
| **Focalboard** | [focalboard.com](https://www.focalboard.com) | Open Trello-style boards |
| **Zulip** | [zulip.com](https://zulip.com) | Topic threads. Best async chat for engineering teams |
| **Rocket.Chat** | [rocket.chat](https://www.rocket.chat) | Self-hosted Slack alternative |

---

## ✅ Code Quality & Testing

| Project | Site | Why it is here |
|---|---|---|
| **ESLint / Prettier** | [eslint.org](https://eslint.org) · [prettier.io](https://prettier.io) | The old JS/TS standard pair. Still everywhere |
| ⭐ **Biome** | [biomejs.dev](https://biomejs.dev) | Rust linter + formatter. One binary instead of two. 10M+ weekly downloads in 2026 |
| **Oxlint** | [oxc.rs](https://oxc.rs) | Rust, speed-first. Use as a fast pre-lint in front of ESLint |
| ⭐ **Playwright** | [playwright.dev](https://playwright.dev) · [microsoft/playwright](https://github.com/microsoft/playwright) | Microsoft E2E + web scraping automation. Chromium / Firefox / WebKit. Same engine agents use via MCP |
| **Vitest** | [vitest.dev](https://vitest.dev) | Unit tests that feel like Vite |

---

## 🧱 Frontend UI & Tooling

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **shadcn/ui** | [ui.shadcn.com](https://ui.shadcn.com) | MIT components you **copy into the repo**. You own the code. De facto React UI in 2025–2026 |
| **Turborepo** | [turborepo.com](https://turborepo.com) | Vercel monorepo builds: incremental + remote cache |
| **Storybook** | [storybook.js.org](https://storybook.js.org) | Isolated component workshop. Team default |

---

## 🖥️ Cross-platform Desktop Frameworks

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **Tauri** | [tauri.app](https://tauri.app) | Rust + OS WebView. Order-of-magnitude smaller than Electron. MIT/Apache |
| **Wails** | [wails.io](https://wails.io) | Go + web UI. The usual choice if you already write Go |

---

## 📊 Product Analytics

| Project | GitHub / Site | Why it is here |
|---|---|---|
| ⭐ **PostHog** | [posthog.com](https://posthog.com) · [PostHog/posthog](https://github.com/PostHog/posthog) | Events, funnels, session replay, flags, experiments. Self-host the core. GA + Mixpanel + LaunchDarkly in one open stack |

---

## 🎬 Code → Screenshot / GIF / Video

> Easy to skip. Unfairly useful for talks, READMEs, and social posts.

| Project | GitHub / Site | Why it is here |
|---|---|---|
| **ScriptSpool** | [scriptspool.pixzens.com](https://scriptspool.pixzens.com/en) | Paste code → MP4 / GIF / PNG / SVG with themes and motion |
| ⭐ **VHS** | [charmbracelet/vhs](https://github.com/charmbracelet/vhs) | Script a terminal session → GIF. Perfect README demos |
| **asciinema** | [asciinema.org](https://asciinema.org) | Record/replay the terminal. Smaller than GIF; copyable text |
| **terminalizer** | [faressoft/terminalizer](https://github.com/faressoft/terminalizer) | Terminal → GIF with themes |
| **silicon** | [Aloxaf/silicon](https://github.com/Aloxaf/silicon) | CLI code screenshots. Pipe in, image out |
| **Carbon** | [carbon.now.sh](https://carbon.now.sh) | Classic pretty code shots. Frontend is open |

---

## 📝 README / Changelog / Commits

| Project | GitHub | Why it is here |
|---|---|---|
| **readme-md-generator** | [kefranabg/readme-md-generator](https://github.com/kefranabg/readme-md-generator) | Interactive README scaffold |
| **Commitizen** | [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | Guided conventional commits |
| **Conventional Changelog** | [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | Changelog from those commits |
| **Husky** | [typicode/husky](https://github.com/typicode/husky) | Git hooks without the pain. Lint/test before commit |

---

## 🔒 Security & Privacy

| Project | Site / GitHub | Why it is here |
|---|---|---|
| ⭐ **Bitwarden** | [bitwarden.com](https://bitwarden.com) | Open client **and** server |
| ⭐ **Vaultwarden** | [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) | Rust Bitwarden-compatible server. The self-host default |
| **OWASP ZAP** | [zaproxy.org](https://www.zaproxy.org) | Open web app scanner |

---

## ⚡ Runtimes & Package Managers

| Project | Site | Why it is here |
|---|---|---|
| ⭐ **Bun** | [bun.sh](https://bun.sh) | Runtime + bundler + pm + tests. Cold start is the pitch |
| **Deno** | [deno.com](https://deno.com) | Secure-by-default JS/TS. Native TypeScript |
| ⭐ **pnpm** | [pnpm.io](https://pnpm.io) | Content-addressed store. Best disk story for monorepos |

---

## 🧰 Swiss-army Toolboxes

| Project | Site / GitHub | Why it is here |
|---|---|---|
| **DevToys** | [devtoys.app](https://devtoys.app) | Desktop: JSON, codecs, regex, dozens of utilities |
| **PowerToys** | [microsoft/PowerToys](https://github.com/microsoft/PowerToys) | Official Windows extras: FancyZones, rename, color picker, PowerToys Run |
| **it-tools** | [it-tools.tech](https://it-tools.tech) | Same idea in the browser |
| ⭐ **Firecrawl** | [firecrawl.dev](https://www.firecrawl.dev) | Web → clean Markdown for agents. 2026 staple |

---

## 🧩 Browser Extensions

| Project | Site / GitHub | Why it is here |
|---|---|---|
| ⭐ **uBlock Origin** | [ublockorigin.com](https://ublockorigin.com) | Light, honest blocker. Still the one to install first |
| **Violentmonkey** | [violentmonkey.github.io](https://violentmonkey.github.io) | Open userscript manager. Tampermonkey without the closed core |
| **SingleFile** | [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) | Whole page → one HTML. Offline archive |
| **Dark Reader** | [darkreader.org](https://darkreader.org) | Force a sane dark theme on sites that never shipped one |
| **Vimium** | [vimium.github.io](https://vimium.github.io) | Keyboard browser. Muscle memory from Vim |
| ⭐ **Refined GitHub** | [refined-github/refined-github](https://github.com/refined-github/refined-github) | GitHub UI, actually usable |
| **Octotree** | [ovity/octotree](https://github.com/ovity/octotree) | File tree in the GitHub sidebar (core is open) |

---

## 📖 Learning Resources

| Resource | Site | Why it is here |
|---|---|---|
| ⭐ **MDN Web Docs** | [developer.mozilla.org](https://developer.mozilla.org) | Canonical Web platform docs. Nonprofit |
| **DevDocs.io** | [devdocs.io](https://devdocs.io) | Many docs, one search, offline |
| **roadmap.sh** | [roadmap.sh](https://roadmap.sh) | Community roadmaps. Open |
| **freeCodeCamp** | [freecodecamp.org](https://www.freecodecamp.org) | Full free curriculum. Nonprofit |
| **Exercism** | [exercism.org](https://exercism.org) | Exercises + human mentors. Nonprofit |

---

## 🗺️ Related Awesome Lists

| List | Scope |
|---|---|
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | The meta-list. How awesome lists are supposed to look |
| [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | If you want *every* self-hosted app |
| [EthanYolo01/Awesome-Agent](https://github.com/EthanYolo01/Awesome-Agent) | Agent frameworks, memory, benchmarks (sister list) |
| [EthanYolo01/Awesome-MCP](https://github.com/EthanYolo01/Awesome-MCP) | MCP protocol resources (sister list) |
| [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) | Autonomous agents and SDKs |

---

## 🤝 Contributing

Contributions are welcome. This list prioritizes **working links + a real “why”** over stuffing more names.

**Before you open a PR:**

1. Visit the link. Dead or paywalled-only tools do not belong here.
2. Prefer **open source or a real free tier you can self-host**.
3. Write what it does, who it is for, and why it is not a duplicate of a row we already have.
4. Match the table format of that section (`⭐` only if it is a default pick).
5. Search for duplicates first.
6. If you add an entry, please update **both** [README.md](README.md) (English) and [README_CN.md](README_CN.md) (Chinese).

**Maintainer:** open an issue on [EthanYolo01/awesome-free-dev-tools](https://github.com/EthanYolo01/awesome-free-dev-tools).

---

<div align="center">

**Found this useful?** Give it a ⭐ and share it with your team.
**Something missing or a dead link?** [Open an issue](https://github.com/EthanYolo01/awesome-free-dev-tools/issues) or submit a PR.

*Last updated: September 2026 · Maintained with ❤️ by the community*

🌐 Language / 语言切换：**English** | [中文](README_CN.md)

</div>
