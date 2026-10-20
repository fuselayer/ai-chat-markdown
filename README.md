# AI Chat Markdown

Tampermonkey userscript that exports Claude, Grok, and Arena.ai conversations to clean Markdown.

Fork of [ChatGPT/Claude/Grok/Arena | Conversation/Chat Markdown Export/Download](https://greasyfork.org/en/scripts/559376-chatgpt-claude-grok-arena-conversation-chat-markdown-export-download) by [Piknockyou](https://greasyfork.org/en/users/1462137-piknockyou), AGPL-3.0. The exporter is entirely their work; this repo only adds the change below.

## Install

Open the `.user.js` file in Tampermonkey → Install.

## Fork changes

- **Battle Pair Copy** (Arena.ai) — hover a battle / side-by-side turn: a thin outline wraps both responses and a copy button attaches to its right edge. Click copies both responses, formatted with the exporter's own Markdown renderer (thinking, code, citations, model names), straight to the clipboard. Toggle in settings, per provider.

`@updateURL` / `@downloadURL` are removed so Greasy Fork updates don't overwrite this fork.
