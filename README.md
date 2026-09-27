<a href="https://xainner.com">
  <img src="assets/banner.svg" alt="Xainner — Founder Engineer · AI Architect" width="100%" />
</a>

<div align="center">

[![Website](https://img.shields.io/badge/xainner.com-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://xainner.com)
[![Rinari.ai](https://img.shields.io/badge/rinari.ai-1E1B2E?style=for-the-badge)](https://rinari.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NnYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNVY5aDMuNDF2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNyAyLjM3IDQuMjcgNS40NnY2LjI4ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMyAyLjA2IDIuMDYgMCAwIDEgMCA0LjEzek03LjEyIDIwLjQ1SDMuNTZWOWgzLjU2djExLjQ1ek0yMi4yMiAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjczdjIwLjU0QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NWMuOTggMCAxLjc4LS43NyAxLjc4LTEuNzNWMS43M0MyNCAuNzcgMjMuMiAwIDIyLjIyIDB6Ii8+PC9zdmc+)](https://www.linkedin.com/in/joserojas29/)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/339977677811482634)
[![Email](https://img.shields.io/badge/business@xainner.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:business@xainner.com)

</div>

<br />

I design and build **complete digital ecosystems** — from the runtime of an AI agent to the desktop app that drives it, the SaaS that monetizes it and the infrastructure it runs on. I work end to end — product, architecture, backend, frontend, mobile and infra — focused on systems that can be **inspected, verified and operated** in production.

```yaml
now:        Rinari — an AI agent with its own engine, terminal client and desktop workspace
focus:      agents · LLM tooling · native apps · SaaS · self-hosting
principles: the model proposes, the runtime authorizes · evidence over promises · local-first when it matters
```

<br />

## ✦ Flagship — Rinari

> **One engine, two ways to work.** Rinari Engine is an agent harness written in Python that owns execution, sessions, model routing, permissions and state. On top of it live a terminal client and a desktop workspace, connected through a versioned protocol.

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Xainner/Rinari-Agent">
  <img src="https://raw.githubusercontent.com/Xainner/Rinari-Agent/main/docs/assets/rinari-agent-hero-v2.png" alt="Rinari Agent" width="100%" />
</a>

### [Rinari Agent](https://github.com/Xainner/Rinari-Agent)
**Turn a conversation into work you can inspect.**

A desktop workspace for AI-assisted development, research and project work.

- **PLAN · BUILD · REVIEW** modes with per-mode permission rules
- Execution timeline: tool calls, commands, diffs, checkpoints and verification
- **Boards**: N parallel sessions, each with its own project and model; agents that message each other with explicit approval
- Embedded Chromium browser, background processes, OCR and vision
- OpenAI, Anthropic, Ollama, LM Studio or any compatible endpoint

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=flat-square&logo=electron&logoColor=9FEAF9)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
[![CI](https://github.com/Xainner/Rinari-Agent/actions/workflows/agent-ci.yml/badge.svg)](https://github.com/Xainner/Rinari-Agent/actions/workflows/agent-ci.yml)

</td>
<td width="50%" valign="top">

<a href="https://github.com/Xainner/Rinari-CLI">
  <img src="https://raw.githubusercontent.com/Xainner/Rinari-CLI/main/docs/img/rinari-cli-hero.png" alt="Rinari CLI" width="100%" />
</a>

### [Rinari CLI](https://github.com/Xainner/Rinari-CLI)
**Your terminal. An agent that can work with it.**

Rinari's engine and its terminal client: explore code, plan, execute and review with evidence.

- `ask` · `plan` · `agent` · `review` · `verify` · `resume` · `undo`
- Repository tools with **tree-sitter + LSP**, Git, shell, PTY, browser, HTTP
- Extensible: **MCP**, OpenAPI, skills, plugins and hooks in the same runtime
- Specialist sub-agents with budgets, workspace isolation and model routing
- Permission profiles, approvals, sandboxing, traces and diagnostics

![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)
![Typer](https://img.shields.io/badge/Typer_+_Rich-000000?style=flat-square&logo=gnubash&logoColor=white)
![MIT](https://img.shields.io/badge/License-MIT-8B5CF6?style=flat-square)
[![CI](https://github.com/Xainner/Rinari-CLI/actions/workflows/ci.yml/badge.svg)](https://github.com/Xainner/Rinari-CLI/actions/workflows/ci.yml)

</td>
</tr>
</table>

```mermaid
flowchart LR
    CLI["⌨️ Rinari CLI<br/>terminal"] --> Engine
    Desktop["🖥️ Rinari Agent<br/>Electron + React"] -- "NDJSON · stdio<br/>versioned protocol" --> Engine
    Engine["⚙️ Rinari Engine<br/>Python"] --> Models["🧠 Providers & models"]
    Engine --> Tools["🛠️ Tools · Policy · Approvals"]
    Engine --> State["💾 Sessions · Context · Artifacts"]
```

<br />

## ✦ Open source

<table>
<tr>
<td width="50%" valign="top">

#### 🎬 [Director — MiniMax H3 Prompt Director](https://github.com/Xainner/MiniMax-H3-Prompt-Director)
Desktop app for directing AI video like a real production. **The LLM only writes prose; structure is enforced by a deterministic renderer** and a 20+ rule validator with an automatic repair pass.

![Tauri](https://img.shields.io/badge/Tauri_2-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🧰 [Toolbox](https://github.com/Xainner/toolbox)
Self-hosted suite of **24 PDF and image tools**, iLovePDF + Photoroom style. Local AI (BiRefNet, Real-ESRGAN, OCRmyPDF) with optional GPU; adding a new tool is **a single file**.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧩 [MCP-Servers](https://github.com/Xainner/MCP-Servers)
Hand-crafted **Model Context Protocol** servers for Planka, n8n and PufferPanel: full CRUD, typed schemas and predictable outputs for Claude, Cursor, VS Code and more.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

</td>
<td width="50%" valign="top">

#### ✨ [Luma](https://github.com/Xainner/Luma)
A modern chat for any **OpenAI-compatible** server: token-by-token streaming, image and video attachments, per-model *thinking* levels and on-the-fly model discovery.

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Fastify](https://img.shields.io/badge/Fastify_5-000000?style=flat-square&logo=fastify&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/SQLite_/_Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧟 [Rinari — Zomboid Bot](https://github.com/Xainner/Rinari-Zomboid-Bot)
AI operator on Discord for Project Zomboid servers. **Closed endpoint allowlist, policy enforced in code** and fail-closed server identity checks before every mutation.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![discord.js](https://img.shields.io/badge/discord.js_v14-5865F2?style=flat-square&logo=discord&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🎙️ [Social Persona Studio](https://github.com/Xainner/Social-Personal-Studio)
A **local-first** content studio with a distinct editorial voice per brand: personas with style memory, image analysis and 5 ready-to-post concepts for X and Telegram per idea.

![Tauri](https://img.shields.io/badge/Tauri_2-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🗄️ [Kurisu Model Vault](https://github.com/Xainner/kurisu-model-vault)
Self-hosted AI model backup and management: Hugging Face Hub search, real-time download progress, SHA-256 integrity checks and disk monitoring.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🏥 [EDUS Appointment Automator](https://github.com/Xainner/Automatizador-Citas-Edus)
Automated medical appointment booking on Costa Rica's CCSS EDUS system with Playwright and AI vision, a Telegram bot and scheduled monitoring for slot releases.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)

</td>
</tr>
</table>

<br />

## ✦ Products in production

| | Product | What it is | Stack |
|:-:|---|---|---|
| 🏴 | **[Rinari.ai](https://rinari.ai)** | Multimodal AI platform: assistant, images, voice and automations | ![AI](https://img.shields.io/badge/AI-8B5CF6?style=flat-square) ![React](https://img.shields.io/badge/Web-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) |
| 💬 | **[Rinari.bot](https://discord.com/oauth2/authorize?client_id=1473471376131100683&permissions=8&scope=bot%20applications.commands)** | AI-powered Discord bot with moderation and smart tools | ![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white) ![AI](https://img.shields.io/badge/AI-8B5CF6?style=flat-square) |
| ⚽ | **[TeamMaker.club](https://teammaker.club)** | SaaS for teams, tournaments and real-time stats | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TS-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| 🏟️ | **[MiCanchaCR.com](https://micanchacr.com)** | Soccer field booking across Costa Rica | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Maps](https://img.shields.io/badge/Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white) |
| 🍳 | **[ReceTica.com](https://recetica.com)** | Recipe platform and community | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| 💻 | **[SerDigital](https://serdigitalcr.com)** | Professional web apps and digital solutions | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| 🎮 | **[ARK Servers](https://ark.renxaii.com)** | ARK: Survival Evolved servers on optimized infrastructure | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

<br />

## ✦ Stack

<table>
<tr><td><b>Languages</b></td><td>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

</td></tr>
<tr><td><b>AI & agents</b></td><td>

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)

</td></tr>
<tr><td><b>Frontend & desktop</b></td><td>

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=flat-square&logo=electron&logoColor=9FEAF9)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

</td></tr>
<tr><td><b>Backend & data</b></td><td>

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td></tr>
<tr><td><b>Infra</b></td><td>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td></tr>
</table>

<br />

<div align="center">

**Got a product to build?** → [xainner.com](https://xainner.com) · [business@xainner.com](mailto:business@xainner.com)

<sub>📍 San José, Costa Rica</sub>

</div>
