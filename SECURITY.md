# Security Policy

## Supported versions

Only the **latest release** of Nexo receives security fixes. Nexo updates itself automatically; please keep it up to date (**Settings → Check for updates**).

| Version | Supported |
|---------|-----------|
| Latest release | ✅ |
| Older releases | ❌ |

## Reporting a vulnerability

**Please do not report security vulnerabilities in public issues.**

Use GitHub's private reporting instead: go to the [Security tab](https://github.com/CrushedDEV/nexo-releases/security) and click **Report a vulnerability**. Only the maintainer can see these reports.

Please include:

- the Nexo version and Windows version;
- a description of the issue and its impact;
- steps to reproduce, or a proof of concept;
- any suggestion you have for a fix.

Do not include real API keys, tokens or personal data — use placeholders.

## What to expect

- An acknowledgement within a few days.
- An assessment and, if confirmed, a fix in a new release as soon as possible. The release notes will mention security fixes.
- Credit for the discovery in the release notes, if you'd like.

## How Nexo handles your data

- Nexo runs locally on your computer. Conversations, memory and projects are stored in your user folder (`%APPDATA%\Nexo`).
- API keys and connector tokens are encrypted with Windows' secure storage (DPAPI).
- Subscription accounts use the official tools (Claude Code, Codex) and their own sign-in; Nexo never sees your password.
- Nexo only talks to the AI providers you configure, to GitHub (to check for updates) and to the services of the connectors you add.
