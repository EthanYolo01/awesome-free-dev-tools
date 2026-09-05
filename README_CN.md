<div align="center">

# 🛠️ Awesome Free Developer Tools

**开发者免费 / 开源工具精选 —— 编辑器、AI 编程 Agent、API、数据库、部署、效率工具**

*持续收录 · 人工核验 · 有观点的筛选*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/EthanYolo01/awesome-free-dev-tools/issues)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/last%20updated-September%202026-blue?style=flat-square)](https://github.com/EthanYolo01/awesome-free-dev-tools/commits/main)
[![Stars](https://img.shields.io/github/stars/EthanYolo01/awesome-free-dev-tools?style=flat-square)](https://github.com/EthanYolo01/awesome-free-dev-tools/stargazers)

> **宁缺毋滥，不堆链接。**
> 每一条都过目。我们会写清 *为什么值得用*、*什么时候用*，而不是再做一份「Top 100」书签。

**开发者工具格局（2026 年 9 月）：** 🔓 自托管重新成为主流 &nbsp;·&nbsp; 🤖 AI 编程从插件走进完整终端 Agent &nbsp;·&nbsp; 🔌 MCP 成为 Linux 基金会中立标准 &nbsp;·&nbsp; ☁️ Vercel / Cloudflare 开源了生产级 Agent 套件 &nbsp;·&nbsp; ⚖️ 许可证 fork（OpenTofu、Valkey、Forgejo）守住了公地

---

🌐 Language / 语言切换：[English](README.md) | **中文**

</div>

---

## 📋 目录

- [🧭 筛选原则](#-筛选原则)
- [🏁 怎么用这份清单](#-怎么用这份清单)
- [⏳ 时间线](#-时间线)
- [💻 代码编辑器](#-代码编辑器)
- [🤖 AI 编程 Agent / 助手](#-ai-编程-agent--助手)
- [🔌 MCP 生态](#-mcp-生态)
- [🧩 Agent Skills](#-agent-skills)
- [🕸️ Agent 框架 / 沙箱 / 记忆](#️-agent-框架--沙箱--记忆)
- [☁️ 云厂商开源 Agent 基建](#️-云厂商开源-agent-基建)
- [🌐 云浏览器 / Agent 专用浏览器](#-云浏览器--agent-专用浏览器)
- [💰 计费 / 支付 / 订阅](#-计费--支付--订阅)
- [🔀 Git 托管与版本控制](#-git-托管与版本控制)
- [🔌 API 开发与测试](#-api-开发与测试)
- [⌨️ 终端 / Shell / CLI](#️-终端--shell--cli)
- [🗄️ 数据库工具](#️-数据库工具)
- [🎨 设计、绘图与原型](#-设计绘图与原型)
- [📦 容器 / Kubernetes / IaC](#-容器--kubernetes--iac)
- [🚀 自托管部署 / PaaS](#-自托管部署--paas)
- [📈 监控 / 日志 / 错误追踪](#-监控--日志--错误追踪)
- [📚 文档与知识库](#-文档与知识库)
- [📋 项目管理 / 团队协作](#-项目管理--团队协作)
- [✅ 代码质量 / 测试](#-代码质量--测试)
- [🧱 前端组件与工程化](#-前端组件与工程化)
- [🖥️ 跨平台桌面框架](#️-跨平台桌面框架)
- [📊 产品分析](#-产品分析)
- [🎬 代码可视化 / 截图 / 录屏](#-代码可视化--截图--录屏)
- [📝 README / Changelog / Commit](#-readme--changelog--commit)
- [🔒 安全与隐私](#-安全与隐私)
- [⚡ 现代运行时 / 包管理](#-现代运行时--包管理)
- [🧰 小众效率工具箱](#-小众效率工具箱)
- [🧩 浏览器扩展](#-浏览器扩展)
- [📖 学习与参考](#-学习与参考)
- [🗺️ 相关 Awesome 列表](#️-相关-awesome-列表)
- [🤝 如何贡献](#-如何贡献)
- [🙏 致谢](#-致谢)

---

## 🧭 筛选原则

这份清单不追求「越多越好」。入选要过这几关：

1. **开源 / 可自托管 / 免费优先** —— 同类功能里有扎实开源、可自托管或长期免费可用的方案，就先推它们（宁可 Yaak 不推 Postman，宁可 Plane 不推 Linear）。
2. **拒绝大路货堆砌** —— 不把人人都有的书签再抄一遍（VS Code、Docker 这类基础设施除外）。更愿意收录小众但口碑扎实、或近一两年才起来的项目。
3. **能落地，不是 Demo** —— 能下载、能部署、能打开网页就用。不收停留在概念阶段的玩具。
4. **一个坑位一个默认解** —— 同一需求不堆五个功能重复的选项。要放两个，必须有清晰取向（「要速度选 A，要功能全选 B」）。
5. **说清楚为什么** —— 每一行都要回答：它解决什么痛点，和最常见的替代品差在哪。

---

## 🏁 怎么用这份清单

```
你需要……
├── 写代码，但不想锁死在某一家云 IDE？
│   └── Neovim / Helix / Zed / VSCodium
├── 让 AI 真正改仓库，而不只是聊天？
│   └── OpenCode、Aider、Cline、Continue、Tabby + Ollama
├── 给 Agent 工具、浏览器、Skills 或长期记忆？
│   └── MCP + Agent Skills（agentskills.io / skills.sh）+ LiteLLM + browser-use / Playwright / agent-browser + Mem0 / Letta
├── 做 SaaS，但不想每月烧掉 200 美金工具费？
│   └── Coolify 或 Dokploy · Polar 或 Lago · PostHog · Uptime Kuma
├── 停掉 Postman / Figma / Linear / Notion 订阅？
│   └── Yaak 或 Bruno · Penpot · Plane · AFFiNE 或 Outline
└── Git、基础设施、密码都放在自己机器上？
    └── Forgejo/Gitea · OpenTofu · Vaultwarden
```

**一句话：** 网上那种「免费工具 Gist」多半是随机书签。这份清单给的是 **能直接跑起来的默认解**，并附 GitHub 链接，方便你自己核对协议、活跃度和星星。

---

## ⏳ 时间线

```
2023    ──  许可证震动后，本地优先：用 fork / 自托管替换 SaaS
            Podman、Gitea、自托管 PaaS 走出「爱好者玩具」区间

2024    ──  OpenTofu fork Terraform（Linux 基金会）
            Redis 改协议后，Valkey 社区 fork
            Forgejo / Gitea 成为「家里的 GitHub」默认选项
            Coolify 爆火：自己 VPS 上的 Vercel
            shadcn/ui 成为 React 默认「复制进仓库」的 UI 方案
            Tauri 2、Bun 开始从 Electron / npm 抢心智

2025    ──  MCP 捐给 Linux 基金会（Agentic AI Foundation）
            AI 编程离开聊天框：Cline、Aider、Continue、OpenCode
            browser-use / Playwright MCP 让「Agent 点网页」变得日常
            新仓库开始用 Biome / Oxlint 替代 ESLint+Prettier
            Vercel AI SDK、Cloudflare Agents SDK 从示例变成生产套件

2026    ──  终端 Coding Agent（OpenCode、Pi harness）进入主流
            Agent 沙箱（E2B）和记忆层（Letta、Mem0）变成标配
            Polar / Lago 让 Token / GPU 用量计费可以自托管
            Agent Skills 成为可移植的「一条命令教会 Agent 一个工种」格式
            出现专为 Agent 设计的云浏览器（Steel、Lightpanda、Vercel agent-browser）
            DeepSeek Harness（dsh）开源插件优先的编码 Agent 框架
            独立 SaaS 默认用自托管分析（PostHog），而不是 GA
```

---

## 💻 代码编辑器

模态、够快，而且不绑死某一家的遥测。

| 编辑器 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| ⭐ **Neovim** | [neovim.io](https://neovim.io) · [neovim/neovim](https://github.com/neovim/neovim) | 现代化的 Vim。LazyVim / AstroNvim 把配置门槛打下来；终端里插件生态仍然最深 |
| ⭐ **Helix** | [helix-editor.com](https://helix-editor.com) · [helix-editor/helix](https://github.com/helix-editor/helix) | Rust 模态编辑器，**内置** LSP + Tree-sitter。零配置就能用 |
| **Zed** | [zed.dev](https://zed.dev) · [zed-industries/zed](https://github.com/zed-industries/zed) | 前 Atom 团队。这一档里多人实时协作目前最流畅 |
| **Lapce** | [lapce.dev](https://lapce.dev) · [lapce/lapce](https://github.com/lapce/lapce) | Rust，原生远程开发，扩展体验接近 VS Code，但没有 Electron 税 |
| **VSCodium** | [vscodium.com](https://vscodium.com) · [VSCodium/vscodium](https://github.com/VSCodium/vscodium) | 去掉微软遥测和市场锁定的 VS Code 社区构建 |
| **Eclipse Theia** | [theia-ide.org](https://theia-ide.org) · [eclipse-theia/theia](https://github.com/eclipse-theia/theia) | 云端 **和** 桌面都能发的 IDE 框架，适合自己做发行版 |

---

## 🤖 AI 编程 Agent / 助手

2026 年竞争最凶的一类。取向：**开源、不锁模型、对着仓库干活**。

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **OpenCode** | [opencode.ai](https://opencode.ai) | MIT 协议的终端编码 Agent。客户端/服务端、不锁模型商。2026 年涨得最猛的开源 Claude Code 平替 |
| ⭐ **Aider** | [aider.chat](https://aider.chat) · [paul-gauthier/aider](https://github.com/paul-gauthier/aider) | 命令行结对编程：直接改代码并写 Git 提交。Git 原生，任意 LLM |
| ⭐ **Cline** | [cline/cline](https://github.com/cline/cline) | 编辑器里的开源智能体：终端 + 浏览器，每步可审批，原生 MCP。自带模型 Key |
| **Continue.dev** | [continue.dev](https://continue.dev) · [continuedev/continue](https://github.com/continuedev/continue) | 开源 VS Code / JetBrains 助手。任意 API 或本地模型；聊天 + 改代码 + Tab 补全 |
| **Tabby** | [tabby.tabbyml.com](https://tabby.tabbyml.com) · [TabbyML/tabby](https://github.com/TabbyML/tabby) | 可自托管的代码补全。代码不出内网 |
| **Ollama** | [ollama.com](https://ollama.com) · [ollama/ollama](https://github.com/ollama/ollama) | 一键跑本地大模型（含代码模型）。免费、私有 AI 编程栈的电池包 |
| **Pi (Agent Harness)** | [earendil-works/pi](https://github.com/earendil-works/pi) | 极简可黑的终端 Coding 工具包：统一多家 LLM API + Agent Loop + TUI。内核保持小，靠 Skills/插件适配你的工作流 |
| ⭐ **DeepSeek Harness（dsh）** | [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | DeepSeek 出品的开源 Agent Harness。口号是 **Everything is a Plugin** —— 循环、工具、工作流都可插拔，而不是封闭成套的编码盒子 |

---

## 🔌 MCP 生态

> MCP 是最近一年涨得最快的开发者基础设施之一。2025 年底进入 Linux 基金会的 Agentic AI Foundation。这里列 **元工具**（调试、编写、分发），不堆上万个具体 MCP Server。

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **MCP Inspector** | [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) | 官方调试器。看你的 Server 到底暴露了哪些 tools/resources。自己写 MCP 几乎必备 |
| ⭐ **FastMCP** | [jlowin/fastmcp](https://github.com/jlowin/fastmcp) | Python 装饰器几行变成 MCP Server。目前写 Server 最快的方式之一 |
| **Context7** | [context7.com](https://context7.com) · [upstash/context7](https://github.com/upstash/context7) | 给编程助手注入「当前版」库文档。专门治训练数据过时带来的 API 幻觉。Server 源码 MIT |
| **Playwright MCP** | [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 微软官方：点击、截图、读 DOM。Agent 操控浏览器的默认工具 |
| **GitHub MCP Server** | [github/github-mcp-server](https://github.com/github/github-mcp-server) | 官方、免费、开源。让 Agent 读写 Issue / PR / 仓库内容 |
| **Smithery** | [smithery.ai](https://smithery.ai) | MCP Server 托管和一键安装。最接近「MCP 界的 npm」 |

---

## 🧩 Agent Skills

> MCP 给 Agent **工具**。Skills 给 Agent **工种说明书** —— 可复用的指令、脚本和参考资料，任务对上了再加载。OpenCode、Claude Code、Cursor、Gemini CLI 等都在跟这套格式。

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| ⭐ **Agent Skills** | [agentskills.io](https://agentskills.io) | 可移植 Agent Skill 的开放规范：`SKILL.md` + 可选脚本。写一次，在兼容的编码 Agent 里都能跑 |
| ⭐ **skills.sh** | [skills.sh](https://www.skills.sh) | 可复用 Agent Skill 的注册表 / CLI。一条命令安装技能，给 Agent 补上它出厂没有的程序知识 |

---

## 🕸️ Agent 框架 / 沙箱 / 记忆

> Agent 从「能聊天」进化到「能干活」。这一层是编排、安全执行代码/浏览器、以及跨会话记忆。

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **LangGraph** | [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | 图 / 状态机：分支、断点、续跑。ReAct 循环不够用时再上它 |
| ⭐ **LiteLLM** | [BerriAI/litellm](https://github.com/BerriAI/litellm) | 一个 Python 库 / 代理统一 **100+** 家大模型 API（OpenAI 兼容）。密钥、额度、负载均衡、失败切换，以及免费 / 本地路由（Ollama 等），Agent 不用绑死一家厂商 |
| ⭐ **CrewAI** | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 角色分工的多智能体。验证「一组 Agent」想法时上手成本最低 |
| **Pydantic AI** | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | 类型安全的 Python Agent。结构化输入输出在生产里更靠谱 |
| **smolagents** | [huggingface/smolagents](https://github.com/huggingface/smolagents) | Hugging Face。核心极小，Code Agent 范式。一个下午搞懂 Agent 怎么转 |
| ⭐ **browser-use** | [browser-use/browser-use](https://github.com/browser-use/browser-use) | Agent 像人一样操作真实浏览器（填表、抓取、多步流程）。MIT。WebVoyager 第一梯队 |
| ⭐ **E2B** | [e2b.dev](https://e2b.dev) · [e2b-dev/E2B](https://github.com/e2b-dev/E2B) | 给 AI 生成代码用的隔离沙箱。回答「这段代码到底在哪跑」 |
| **Letta**（原 MemGPT） | [letta-ai/letta](https://github.com/letta-ai/letta) | Agent 长期记忆。避免上下文窗口一满就失忆 |
| **Mem0** | [mem0ai/mem0](https://github.com/mem0ai/mem0) | 可插进任意框架的记忆层。个性化、会自我更新 |
| **OpenHands**（原 OpenDevin） | [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) | 自主软件工程 Agent：读代码、跑测试、提 PR。这个方向最早、社区最大的开源项目之一 |
| ⭐ **Langfuse** | [langfuse.com](https://langfuse.com) · [langfuse/langfuse](https://github.com/langfuse/langfuse) | 开源 LLM/Agent 可观测：链路、Token、延迟、评测。可自托管或用云端免费额度。上生产前几乎必装 |

---

## ☁️ 云厂商开源 Agent 基建

Vercel、Cloudflare 把生产形态的套件开源了 —— 拿来 fork，不是黑盒产品。

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Vercel AI SDK** | [vercel/ai](https://github.com/vercel/ai) | TypeScript 工具包：OpenAI / Anthropic / Google，流式、结构化输出、Tool Calling、人工审批。Next.js / 全栈接 AI 的默认库 |
| **Vercel Open Agents** | [Open Agents 模板](https://vercel.com/templates/template/open-agents) | 后台编码 Agent 参考实现：Web UI、运行时、沙箱、GitHub。明确让你 fork |
| ⭐ **agent-browser** | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | Vercel Labs 给 **AI Agent** 用的高性能浏览器自动化 CLI。无头、够快，不必为了让 Agent 点网页去背一整套测试框架 |
| ⭐ **Cloudflare Agents SDK** | [cloudflare/agents](https://github.com/cloudflare/agents) | Workers + Durable Objects 上的有状态 Agent（SQL、WebSocket、定时任务）。边缘原生，体量可以很大 |
| **Cloudflare Agents Starter** | [cloudflare/agents-starter](https://github.com/cloudflare/agents-starter) | 基于 Workers AI 的聊天 Agent 模板 —— 起步不必另申请 OpenAI/Anthropic Key |
| **Cloudflare OS** | [cloudflare/cloudflare-os](https://github.com/cloudflare/cloudflare-os) | 内部 Agent 工作台开源：Gatekeeper 权限，把对话变成文档/工作流/小应用。可跑在开源 `workerd` 上 |

---

## 🌐 云浏览器 / Agent 专用浏览器

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Steel** | [steel.dev](https://steel.dev) · [steel-dev/steel-browser](https://github.com/steel-dev/steel-browser) | 为 Agent 做的浏览器 API：会话、隐身、回放。Docker 自托管或云端。Puppeteer / Playwright / Selenium 都能连 |
| ⭐ **Playwright** | [playwright.dev](https://playwright.dev) · [microsoft/playwright](https://github.com/microsoft/playwright) | 微软开源的浏览器自动化库。E2E 测试 **和** 网页抓取 / Agent 操控（Chromium、Firefox、WebKit）。调用方是 LLM 时搭配 [Playwright MCP](https://github.com/microsoft/playwright-mcp) |
| ⭐ **agent-browser** | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | Vercel Labs 出品的高性能浏览器 CLI，面向 AI Agent，而不是传统 QA 套件 |
| **Lightpanda** | [lightpanda-io/browser](https://github.com/lightpanda-io/browser) | Zig 从零写的无头浏览器（不是 Chromium fork）。官方基准约 Chrome 1/9 内存、约 11 倍速度。兼容 CDP |
| **BrowserOS** | [browseros.com](https://www.browseros.com) | 开源 Chromium fork，Agent 做进浏览器本体。本地 Claude/Gemini/Ollama；Chrome 插件还能用 |

---

## 💰 计费 / 支付 / 订阅

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Polar** | [polar.sh](https://polar.sh) · [polarsource/polar](https://github.com/polarsource/polar) | Apache 2.0 计费。Agent 按步 / GPU 用量、订阅、一次性、License Key、GitHub/Discord 权益。认真替代「只会 Stripe」 |
| **Lago** | [getlago.com](https://www.getlago.com) · [getlago/lago](https://github.com/getlago/lago) | 开源用量计费（API 调用、Token）。可自托管 |

---

## 🔀 Git 托管与版本控制

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Gitea / Forgejo** | [gitea.com](https://about.gitea.com) · [forgejo.org](https://forgejo.org) | 轻量、可自托管、界面接近 GitHub。摆脱平台锁定 |
| ⭐ **Lazygit** | [jesseduffield/lazygit](https://github.com/jesseduffield/lazygit) | 终端 Git TUI。全键盘，效率极高 |
| **delta** | [dandavison/delta](https://github.com/dandavison/delta) | 语法高亮、并排的 `git diff` |
| **Git Graph** | [mhutchie/vscode-git-graph](https://github.com/mhutchie/vscode-git-graph) | 编辑器里的提交历史图 |

---

## 🔌 API 开发与测试

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| ⭐ **Yaak** | [yaak.app](https://yaak.app) | Rust + Tauri。本地文件存储。更干净的 Postman |
| ⭐ **Bruno** | [usebruno.com](https://www.usebruno.com) | 请求以文件进 Git。不强制登录云端 |
| **Hoppscotch** | [hoppscotch.io](https://hoppscotch.io) | 开源 Web 客户端；也可以自部署 |
| **Mockoon** | [mockoon.com](https://mockoon.com) | 几分钟搭本地 Mock API |
| **HTTPie** | [httpie.io](https://httpie.io) | 命令行里比 curl 更人类的 HTTP 客户端 |

---

## ⌨️ 终端 / Shell / CLI

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| **Alacritty** | [alacritty.org](https://alacritty.org) | GPU 加速终端，纯文本配置，不堆功能 |
| **WezTerm** | [wezfurlong.org/wezterm](https://wezfurlong.org/wezterm) | Rust，跨平台，自带多路复用 |
| ⭐ **Starship** | [starship.rs](https://starship.rs) | 跨 Shell 提示符。快、好看、可移植 |
| ⭐ **fzf** | [junegunn/fzf](https://github.com/junegunn/fzf) | 模糊查找：文件、历史、分支，到处都能用 |
| ⭐ **ripgrep** | [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) | 仓库里你真正想用的 grep |
| **fd** | [sharkdp/fd](https://github.com/sharkdp/fd) | 默认更合理的 `find` |
| **bat** | [sharkdp/bat](https://github.com/sharkdp/bat) | 带高亮和 Git 的 `cat` |
| **eza** | [eza.rocks](https://eza.rocks) | 现代化的 `ls` |
| **jq** | [jqlang.github.io/jq](https://jqlang.github.io/jq/) | 命令行处理 JSON。没有讨价还价 |

---

## 🗄️ 数据库工具

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| ⭐ **DBeaver CE** | [dbeaver.io](https://dbeaver.io) | 几乎通吃主流数据库的通用客户端 |
| **Beekeeper Studio** | [beekeeperstudio.io](https://www.beekeeperstudio.io) | 界面更现代的 SQL 客户端（核心开源） |
| **pgAdmin** | [pgadmin.org](https://www.pgadmin.org) | PostgreSQL 官方管理工具 |
| **Adminer** | [adminer.org](https://www.adminer.org) | 单文件 PHP。丢上去就能管库 |
| **RedisInsight** | [redis.io/insight](https://redis.io/insight) | Redis 官方可视化 |
| **SurrealDB** | [surrealdb.com](https://surrealdb.com) | 真正起来过一波热度的多模型库 |
| ⭐ **Valkey** | [valkey.io](https://valkey.io) | Redis 社区 fork，Linux 基金会托管，完全开源 |

---

## 🎨 设计、绘图与原型

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Penpot** | [penpot.app](https://penpot.app) | 开源、对标 Figma 的设计/原型。可自部署 |
| ⭐ **Excalidraw** | [excalidraw.com](https://excalidraw.com) | 手绘风白板。工程师画图最快的那一个 |
| **tldraw** | [tldraw.dev](https://tldraw.dev) | 可内嵌的画布 SDK |
| **D2** | [d2lang.com](https://d2lang.com) | 文本生成架构图。能进 Git 做 diff |
| **Mermaid** | [mermaid.js.org](https://mermaid.js.org) | Markdown 里写图。GitHub 原生渲染 |

---

## 📦 容器 / Kubernetes / IaC

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Podman** | [podman.io](https://podman.io) | 无守护进程、命令兼容 Docker |
| **Portainer CE** | [portainer.io](https://www.portainer.io) | 容器可视化面板 |
| **k3s / Kind / Minikube** | [k3s.io](https://k3s.io) · [kind](https://kind.sigs.k8s.io) · [minikube](https://minikube.sigs.k8s.io) | 笔记本或边缘上能跑的 Kubernetes |
| **Lens** | [k8slens.dev](https://k8slens.dev) | Kubernetes 桌面 IDE |
| ⭐ **OpenTofu** | [opentofu.org](https://opentofu.org) | Terraform 社区 fork。协议分裂后的开源 IaC |

---

## 🚀 自托管部署 / PaaS

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Coolify** | [coolify.io](https://coolify.io) | 自己 VPS 上接近 Vercel/Heroku 的体验。近两年最火的自托管 PaaS |
| **Dokploy** | [dokploy.com](https://dokploy.com) | 更新；原生 Docker Compose；长得很快 |
| **CapRover** | [caprover.com](https://caprover.com) | 老牌一键应用 + 数据库 |

---

## 📈 监控 / 日志 / 错误追踪

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Uptime Kuma** | [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | 好看的自托管可用性监控。开源版 UptimeRobot |
| **GlitchTip** | [glitchtip.com](https://glitchtip.com) | 轻量开源 Sentry 替代 |
| **Grafana + Prometheus** | [grafana.com](https://grafana.com) · [prometheus.io](https://prometheus.io) | 开源指标栈。到现在仍是默认组合 |

---

## 📚 文档与知识库

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **AFFiNE** | [affine.pro](https://affine.pro) | Notion + Miro：块编辑器加白板。增长很快 |
| **Outline** | [getoutline.com](https://www.getoutline.com) | 团队 Wiki，界面接近 Notion。可自托管 |
| **Docusaurus** | [docusaurus.io](https://docusaurus.io) | Meta 出品的文档站生成器 |
| **VitePress** | [vitepress.dev](https://vitepress.dev) | 基于 Vite 的轻量文档。适合库文档 |

---

## 📋 项目管理 / 团队协作

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Plane** | [plane.so](https://plane.so) | 开源 Linear/Jira。Issue + 项目。可自托管 |
| **Huly** | [huly.io](https://huly.io) | 项目 + 文档 + 聊天。野心对标 Notion + Linear + Slack |
| **Focalboard** | [focalboard.com](https://www.focalboard.com) | 开源 Trello 风格看板 |
| **Zulip** | [zulip.com](https://zulip.com) | 按主题线程。技术团队异步沟通最好用的开源聊天之一 |
| **Rocket.Chat** | [rocket.chat](https://www.rocket.chat) | 可自托管的 Slack 替代 |

---

## ✅ 代码质量 / 测试

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| **ESLint / Prettier** | [eslint.org](https://eslint.org) · [prettier.io](https://prettier.io) | JS/TS 老牌标准组合。现在还到处都是 |
| ⭐ **Biome** | [biomejs.dev](https://biomejs.dev) | Rust 写的 linter + formatter。一个二进制替代两个工具。2026 年周下载已破千万 |
| **Oxlint** | [oxc.rs](https://oxc.rs) | 同样 Rust，极致速度。适合当前置高速预检 |
| ⭐ **Playwright** | [playwright.dev](https://playwright.dev) · [microsoft/playwright](https://github.com/microsoft/playwright) | 微软开源 E2E + 网页抓取自动化。Chromium / Firefox / WebKit。Agent 侧同一套引擎走 MCP |
| **Vitest** | [vitest.dev](https://vitest.dev) | 和 Vite 一体的单测，跑得快 |
| **Agent QA** | [vostride/agent-qa](https://github.com/vostride/agent-qa) | 面向用自然语言编写 Web、Android 和 iOS 回归测试的团队，跨运行复用执行记忆。采用 FSL-1.1-ALv2 源码可用许可，许可范围内使用无需软件费用；配置的服务提供商可能另收费 |

---

## 🧱 前端组件与工程化

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **shadcn/ui** | [ui.shadcn.com](https://ui.shadcn.com) | MIT 组件，**复制进你的仓库**。代码归你。2025–2026 React 事实上的默认 UI |
| **Turborepo** | [turborepo.com](https://turborepo.com) | Vercel 的 Monorepo 构建：增量 + 远程缓存 |
| **Storybook** | [storybook.js.org](https://storybook.js.org) | 组件独立开发和文档。前端团队标配 |

---

## 🖥️ 跨平台桌面框架

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Tauri** | [tauri.app](https://tauri.app) | Rust + 系统 WebView。体积比 Electron 小一个数量级。MIT/Apache |
| **Wails** | [wails.io](https://wails.io) | Go + Web UI。已经写 Go 时最常见的桌面方案 |

---

## 📊 产品分析

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **PostHog** | [posthog.com](https://posthog.com) · [PostHog/posthog](https://github.com/PostHog/posthog) | 埋点、漏斗、Session 回放、Feature Flag、实验。核心可自托管。GA + Mixpanel + LaunchDarkly 的开源合集 |

---

## 🎬 代码可视化 / 截图 / 录屏

> 容易被忽略，但做分享、写 README、发社交媒体时特别好用。

| 项目 | GitHub / 网站 | 为什么在这里 |
|---|---|---|
| **ScriptSpool** | [scriptspool.pixzens.com](https://scriptspool.pixzens.com/en) | 粘贴代码生成 MP4 / GIF / PNG / SVG，带主题和动画 |
| ⭐ **VHS** | [charmbracelet/vhs](https://github.com/charmbracelet/vhs) | 用脚本描述终端操作，自动出 GIF。特别适合 README 演示 |
| **asciinema** | [asciinema.org](https://asciinema.org) | 终端会话录制回放。比 GIF 小，还能复制文字 |
| **terminalizer** | [faressoft/terminalizer](https://github.com/faressoft/terminalizer) | 终端转 GIF，可自定义主题 |
| **silicon** | [Aloxaf/silicon](https://github.com/Aloxaf/silicon) | 命令行代码截图。管道进，图出来 |
| **Carbon** | [carbon.now.sh](https://carbon.now.sh) | 经典漂亮代码截图。前端部分开源 |

---

## 📝 README / Changelog / Commit

| 项目 | GitHub | 为什么在这里 |
|---|---|---|
| **readme-md-generator** | [kefranabg/readme-md-generator](https://github.com/kefranabg/readme-md-generator) | 交互式生成 README 脚手架 |
| **Commitizen** | [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 引导式规范化 commit |
| **Conventional Changelog** | [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 从规范化 commit 生成 Changelog |
| **Husky** | [typicode/husky](https://github.com/typicode/husky) | 轻量 Git hooks。提交前跑 lint/测试 |

---

## 🔒 安全与隐私

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| ⭐ **Bitwarden** | [bitwarden.com](https://bitwarden.com) | 客户端 **和** 服务端都开源 |
| ⭐ **Vaultwarden** | [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) | Rust 写的 Bitwarden 兼容服务端。自建默认选项 |
| **OWASP ZAP** | [zaproxy.org](https://www.zaproxy.org) | 开源 Web 应用安全扫描 |

---

## ⚡ 现代运行时 / 包管理

| 项目 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **Bun** | [bun.sh](https://bun.sh) | 运行时 + 打包 + 包管理 + 测试。卖点是冷启动 |
| **Deno** | [deno.com](https://deno.com) | 默认更安全的 JS/TS 运行时。原生 TypeScript |
| ⭐ **pnpm** | [pnpm.io](https://pnpm.io) | 内容寻址存储。Monorepo 省磁盘的首选 |

---

## 🧰 小众效率工具箱

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| **DevToys** | [devtoys.app](https://devtoys.app) | 桌面瑞士军刀：JSON、编解码、正则等几十个小工具 |
| **PowerToys** | [microsoft/PowerToys](https://github.com/microsoft/PowerToys) | 微软官方 Windows 增强：分屏、批量重命名、取色、PowerToys Run |
| **it-tools** | [it-tools.tech](https://it-tools.tech) | 同一思路的网页版 |
| ⭐ **Firecrawl** | [firecrawl.dev](https://www.firecrawl.dev) | 网页转干净 Markdown，给 Agent 用。2026 年标配级工具 |

---

## 🧩 浏览器扩展

| 项目 | 网站 / GitHub | 为什么在这里 |
|---|---|---|
| ⭐ **uBlock Origin** | [ublockorigin.com](https://ublockorigin.com) | 轻量、干净的拦截。仍然是第一个该装的 |
| **Violentmonkey** | [violentmonkey.github.io](https://violentmonkey.github.io) | 完全开源的用户脚本管理器。Tampermonkey 的开源替代 |
| **SingleFile** | [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) | 整页存成一个 HTML。离线存档很好用 |
| **Dark Reader** | [darkreader.org](https://darkreader.org) | 给没做深色模式的网站强制出合理暗色 |
| **Vimium** | [vimium.github.io](https://vimium.github.io) | 键盘操作浏览器。Vim 肌肉记忆直接复用 |
| ⭐ **Refined GitHub** | [refined-github/refined-github](https://github.com/refined-github/refined-github) | GitHub 网页体验补丁，用了回不去 |
| **Octotree** | [ovity/octotree](https://github.com/ovity/octotree) | GitHub 侧边栏文件树（核心开源） |

---

## 📖 学习与参考

| 资源 | 网站 | 为什么在这里 |
|---|---|---|
| ⭐ **MDN Web Docs** | [developer.mozilla.org](https://developer.mozilla.org) | Web 平台权威文档。非营利维护 |
| **DevDocs.io** | [devdocs.io](https://devdocs.io) | 多语言文档聚合，可离线 |
| **roadmap.sh** | [roadmap.sh](https://roadmap.sh) | 社区学习路线图。开源 |
| **freeCodeCamp** | [freecodecamp.org](https://www.freecodecamp.org) | 免费系统课程。非营利 |
| **Exercism** | [exercism.org](https://exercism.org) | 免费练习 + 人工导师。非营利 |

---

## 🗺️ 相关 Awesome 列表

| 列表 | 范围 |
|---|---|
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | 元列表。Awesome 该长什么样 |
| [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | 想看「所有」自托管应用时去这里 |
| [EthanYolo01/Awesome-Agent](https://github.com/EthanYolo01/Awesome-Agent) | Agent 框架、记忆、评测（姊妹列表） |
| [EthanYolo01/Awesome-MCP](https://github.com/EthanYolo01/Awesome-MCP) | MCP 协议资源（姊妹列表） |
| [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) | 自主 Agent 与 SDK |

---

## 🤝 如何贡献

欢迎 PR。这份清单优先 **能打开的链接 + 一句真的「为什么」**，而不是再塞几个名字。

**提交前请确认：**

1. 自己点开链接。失效或只有付费墙的不收录。
2. 优先 **开源，或可自托管的真实免费档**。
3. 写清它做什么、给谁用、为什么不是已有条目的重复。
4. 表格格式和该节现有行一致（只有默认首选才加 `⭐`）。
5. 先搜有没有重复。
6. 新增条目请同时改 **[README.md](README.md)（英文）** 和 **[README_CN.md](README_CN.md)（中文）**。

**维护：** 在 [EthanYolo01/awesome-free-dev-tools](https://github.com/EthanYolo01/awesome-free-dev-tools) 开 Issue。

---

## 🙏 致谢

<div align="center">

感谢 **[LINUX DO](https://linux.do)** 社区的讨论与校对，这份清单能一直打磨，离不开那里多出来的几双眼睛。

<a href="https://linux.do">
  <img src="assets/linuxdo.png" alt="LINUX DO" height="48">
</a>

</div>

---

<div align="center">

**觉得有用？** 给一个 ⭐，转给同事。
**缺工具或死链？** [开 Issue](https://github.com/EthanYolo01/awesome-free-dev-tools/issues) 或直接提 PR。

*最后更新：2026 年 9 月 · 由社区用 ❤️ 维护*

🌐 Language / 语言切换：[English](README.md) | **中文**

</div>
