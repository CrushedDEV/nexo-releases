# Nexo

**One desktop app for all your AI subscriptions.** Nexo connects your **Claude** and **ChatGPT** accounts — through your existing Pro/Max/Plus plan or an API key — and lets them share memory, projects and conversations.

> This repository only hosts the Windows installers and the issue tracker. The source code is private.

## Download

1. Download `Nexo-Setup-x.y.z.exe` from the [latest release](https://github.com/CrushedDEV/nexo-releases/releases/latest).
2. Run it. The installer is not code-signed yet: if Windows SmartScreen shows a warning, click **More info → Run anyway**.

Once installed, **Nexo updates itself**: new versions download in the background and install with one click — a small window shows the progress and Nexo reopens on its own.

## What you can do

- **Chat and Code.** Chat with any model, or let an agent work in a folder: it reads, edits and runs commands, with permission modes like Claude Code.
- **All your accounts together.** Several Claude and ChatGPT accounts side by side. Compare answers, or let one account take over automatically when another hits its plan limit (*failover*).
- **Shared memory.** What one account learns about you, all of them know. Projects keep their own instructions and documents.
- **Skills and connectors.** Your Claude Code and Codex skills, plus MCP servers (GitHub, Notion, browser, Context7…).
- **Bring your history.** Import your chats from Claude and ChatGPT exports, and your local Claude Code sessions.
- **Chat themes.** Type `/theme` to give a conversation a living ASCII wallpaper — pick one or describe the mood you want.
- **Limits and stats.** Session and weekly plan usage, context size, response times, streaks and token usage per day.
- **And more:** remote control, a message queue, file attachments (zip, PDF, Office…), an in-app browser and terminal, English and Spanish interface.

Nexo never spends API credit on your behalf when you use a subscription: if a tool is signed in with an API key instead of your plan, Nexo refuses to send and tells you how to fix it.

## Requirements

- Windows 10 or 11 (64-bit).
- To use a **Claude Pro/Max** plan: [Claude Code](https://claude.com/download), signed in with your Claude account.
- To use a **ChatGPT Plus/Pro** plan: [Codex](https://github.com/openai/codex) (`npm i -g @openai/codex`), signed in with ChatGPT.
- Or an **API key** from Anthropic, OpenAI or any OpenAI-compatible service.

Nexo's first-run guide walks you through all of this. Each person uses their own accounts on their own computer.

## Feedback and support

- Found a bug? [Open a bug report](https://github.com/CrushedDEV/nexo-releases/issues/new?template=bug_report.yml).
- Have an idea? [Request a feature](https://github.com/CrushedDEV/nexo-releases/issues/new?template=feature_request.yml).
- Security issue? Please **don't** open a public issue — see [SECURITY.md](SECURITY.md).

See also [CONTRIBUTING.md](CONTRIBUTING.md), [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and [ACCESSIBILITY.md](ACCESSIBILITY.md).

---

Nexo is an independent project. It is not affiliated with or endorsed by Anthropic or OpenAI. Claude and ChatGPT are trademarks of their respective owners.
