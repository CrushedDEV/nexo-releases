<div align="center">

<img src="docs/img/nexi.png" width="112" alt="Nexi, Nexo's mascot">

# Nexo

**Claude and ChatGPT in one desktop app.**<br>
Your subscriptions and API accounts share memory, projects and conversations:<br>
switch AI mid-conversation and the next answer keeps all the context.

[![Latest release](https://img.shields.io/github/v/release/CrushedDEV/nexo-releases?label=version&color=c4552d&style=for-the-badge)](https://github.com/CrushedDEV/nexo-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/CrushedDEV/nexo-releases/total?label=downloads&color=12805b&style=for-the-badge)](https://github.com/CrushedDEV/nexo-releases/releases)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-2f6fe0?style=for-the-badge&logo=windows11&logoColor=white)
![Languages](https://img.shields.io/badge/UI-English%20%7C%20Espa%C3%B1ol-7c4ddb?style=for-the-badge)

[**⬇ Download for Windows**](https://github.com/CrushedDEV/nexo-releases/releases/latest) · [What's new](#-whats-new-in-011) · [Features](#-features) · [Requirements](#-requirements) · [Support](#-feedback-and-support)

<br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="docs/img/chat-light.png">
  <img src="docs/img/chat.png" alt="A conversation in Nexo" width="900">
</picture>

</div>

> [!NOTE]
> This repository hosts the Windows installers and the issue tracker. The source code is private.

<br>

## ✨ Why Nexo

<table>
<tr>
<td width="33%" valign="top">

### 🤝 Two AIs, one chat
Claude and ChatGPT read the same conversation, memory and projects. Ask the other AI for a
**second opinion** in one click, or **compare** their answers side by side.

</td>
<td width="33%" valign="top">

### 💳 Your plans, not credit
Use your **Pro / Max** and **Plus / Pro** subscriptions through Claude Code and Codex. Nexo only
spends your plan's limits and **never** paid extra usage.

</td>
<td width="33%" valign="top">

### 🤖 Agents that work on their own
**Loop mode**, a parallel **task board** with isolated branches, project rules and GitHub built
in. You review and merge.

</td>
</tr>
</table>

```mermaid
flowchart LR
    You([🧑 You]) --> Nexo
    subgraph Nexo [" 🟧 Nexo "]
        M[(Memory · Projects<br>Conversations)]
    end
    Nexo -->|Claude Code| C[Claude Pro / Max]
    Nexo -->|Codex| G[ChatGPT Plus / Pro]
    Nexo -->|API key| A[Anthropic · OpenAI<br>OpenRouter · Ollama…]
    style Nexo fill:#2a1a14,stroke:#c4552d,color:#fff
    style C fill:#c4552d,stroke:#c4552d,color:#fff
    style G fill:#12805b,stroke:#12805b,color:#fff
    style A fill:#333,stroke:#555,color:#fff
```

<br>

## 📥 Download

1. Download `Nexo-Setup-x.y.z.exe` from the [latest release](https://github.com/CrushedDEV/nexo-releases/releases/latest).
2. Run it. The installer is not code-signed yet: if Windows SmartScreen shows a warning, click
   **More info → Run anyway**.

> [!TIP]
> Once installed, **Nexo updates itself**: new versions download in the background and install with
> one click. Afterwards, a "What's new" window shows what changed.

<br>

## 🎉 What's new in 0.11

<div align="center">
<img src="docs/img/changelog.png" alt="What's new window" width="820">
</div>

**17 new features**: loop mode, a parallel task board, project rules, GitHub, one-click diagnostics,
PIN lock, private chats, a knowledge base, a side document, voice mode and more.

<br>

## 🧭 Features

<table>
<tr>
<td width="50%" valign="top">

### ⚖️ Compare Claude and ChatGPT
<img src="docs/img/compare.png" alt="Comparing answers">

Ask up to **4 accounts at once** and pick the answer the conversation continues with. Shown here
with the animated *Night* theme.

</td>
<td width="50%" valign="top">

### 💻 Code: an agent in your folder
<img src="docs/img/code.png" alt="Code mode with changes and terminal">

It edits files and runs commands, with **Changes**, a real Windows **Terminal**, and your
**check** (say `npm test`) under every reply.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔁 Loop mode
<img src="docs/img/loop.png" alt="Loop mode">

A goal plus a command that checks it's done. The agent keeps going **until it passes**; if it gets
stuck, it stops or hands over to the other AI.

</td>
<td width="50%" valign="top">

### 📋 Parallel task board
<img src="docs/img/board.png" alt="Task board">

Several tasks at once, **each on its own isolated branch**. When they finish: merge, open a PR or
discard in one click.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🪟 Split view
<img src="docs/img/split.png" alt="Two chats side by side">

Drag chats from the sidebar and drop them anywhere: columns, rows or a grid, each one answering on
its own.

</td>
<td width="50%" valign="top">

### 🌅 Animated chat themes
<img src="docs/img/themes.png" alt="Chat themes">

Type `/theme` and pick a living ASCII wallpaper (sunset, night, rain, aurora…) or **describe the
mood** and the AI designs it.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏠 Home and templates
<img src="docs/img/home.png" alt="Nexo home screen">

"Pick up where you left off", templates with blanks (`{{text}}`) and your 5-hour and weekly
limits always in sight.

</td>
<td width="50%" valign="top">

### ⚙️ Full settings
<img src="docs/img/settings.png" alt="Settings">

English or Spanish, appearance, code themes, notifications, PIN, Windows context menu, a floating
mini window on Alt + Space…

</td>
</tr>
</table>

### And also

| | | |
|:---|:---|:---|
| 🔒 **PIN lock** and private chats | 🗝️ **Secret warning** before you send a key | 🩺 **One-click diagnostics** and error report |
| 📄 **Side document** the AI edits piece by piece | 📚 **Knowledge base** per project | 📓 **Work journal** for your day or week |
| 🐙 **GitHub**: issues, PRs and "Fix on a branch" | 🖱️ **Windows context menu** | 🎙️ **Voice mode** and read aloud |
| ⏰ **Scheduled prompts** that send themselves | 💾 **Automatic backups** to OneDrive or Drive | 🧾 **Export** to Markdown, web page or PDF |
| ↩️ **Undo** what the agent did | 🌿 **Isolated branches** (git worktree) | 🔔 **Windows notifications** when a reply finishes |
| 📥 **Import** your Claude and ChatGPT chats | 🧩 **MCP connectors** and **skills**, shared | 📊 **Stats**, streaks and "You've saved" |

<br>

## 🔁 How loop mode works

```mermaid
flowchart LR
    O[🎯 Goal] --> A[🤖 Agent works]
    A --> C{✅ Does the<br>check pass?}
    C -- Yes --> H([🎉 Done])
    C -- No --> E[📋 Nexo hands it<br>the errors]
    E --> S{Did the<br>error change?}
    S -- Yes --> A
    S -- No --> R[🔄 Stop or try<br>the other AI]
    R --> A
```

<br>

## 🧾 Requirements

| | To use… | You need |
|---|---|---|
| <img src="https://img.shields.io/badge/-Claude-c4552d?style=flat-square" alt=""> | a **Pro / Max** plan | [Claude Code](https://claude.com/download), signed in with your Claude account |
| <img src="https://img.shields.io/badge/-ChatGPT-12805b?style=flat-square" alt=""> | a **Plus / Pro** plan | [Codex](https://github.com/openai/codex) (`npm i -g @openai/codex`), signed in with ChatGPT |
| 🔑 | an **API key** | A key from Anthropic, OpenAI or any OpenAI-compatible service |

Plus **Windows 10 or 11 (64-bit)**. Nexo's first-run guide walks you through all of this.

> [!IMPORTANT]
> Nexo never spends API credit on your behalf when you use a subscription: if a tool is signed in
> with an API key instead of your plan, Nexo refuses to send and tells you how to fix it. Each person
> uses their own accounts on their own computer — subscriptions can't be shared or resold.

<br>

## 💬 Feedback and support

<table>
<tr>
<td align="center" width="33%">

🐞<br>
**Found a bug?**<br>
[Open a bug report](https://github.com/CrushedDEV/nexo-releases/issues/new?template=bug_report.yml)

</td>
<td align="center" width="33%">

💡<br>
**Have an idea?**<br>
[Request a feature](https://github.com/CrushedDEV/nexo-releases/issues/new?template=feature_request.yml)

</td>
<td align="center" width="33%">

🛡️<br>
**Security issue?**<br>
Please don't open a public issue —<br>see [SECURITY.md](SECURITY.md)

</td>
</tr>
</table>

> [!TIP]
> In Nexo, **Settings → About Nexo → Diagnostics** checks everything and can create an error report
> without keys or conversations — attach it to your bug report.

See also [CONTRIBUTING.md](CONTRIBUTING.md), [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and
[ACCESSIBILITY.md](ACCESSIBILITY.md).

---

<div align="center">
<img src="docs/img/nexi.png" width="48" alt=""><br>
<sub>Nexo is an independent project. It is not affiliated with or endorsed by Anthropic or OpenAI.<br>Claude and ChatGPT are trademarks of their respective owners.</sub>
</div>
