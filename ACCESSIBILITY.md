# Accessibility

Nexo should be comfortable to use for everyone. This document describes what we support today, the known limitations, and how to tell us about barriers.

## Supported environments

- Windows 10 and 11 (64-bit), at any display scaling.
- Keyboard and mouse; touch and pen through Windows.

## What Nexo offers

- **Keyboard first.** Every main action has a shortcut: `Ctrl+K` search and commands, `Ctrl+N` new conversation, `Ctrl+B` toggle the sidebar, `Ctrl+,` settings, `/` templates and skills, `Esc` to stop a reply or close dialogs, `↑` to edit your last message. Menus can be navigated with the keyboard and some offer number shortcuts.
- **Readable text.** Three text sizes and two reading widths in **Settings**.
- **Themes.** Dark, light, or follow Windows. Text and controls are designed for strong contrast in both.
- **Reduced motion.** If Windows is set to reduce animations, Nexo's animated backgrounds and transitions stay still.
- **Not color alone.** Account types, statuses and charts always carry a label or icon next to their color, and chart colors are validated for color-vision deficiencies.
- **Language.** The interface is available in English and Spanish, and the AI answers in your language.

## Known limitations

- Screen reader support is partial: some custom controls (charts, the reasoning-effort slider, animated backgrounds) don't yet expose complete descriptions.
- Windows High Contrast themes are not fully adapted yet.
- Some third-party content shown inside Nexo (the in-app browser, connector results) depends on those services' accessibility.

## Reporting a barrier

If something in Nexo is hard or impossible for you to use, please [open an issue](https://github.com/CrushedDEV/nexo-releases/issues/new?template=bug_report.yml) and mention **accessibility** in the title. Tell us what you were trying to do, the assistive technology you use (if any), and what got in the way. Accessibility issues are treated as bugs and prioritized.
