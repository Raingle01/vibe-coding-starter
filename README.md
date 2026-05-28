# 🚀 vibe-coding-starter

[English](README.md) | [中文](README.zh.md)

**Stop vibe coding blindly.**

Most people's first vibe coding session looks like this:

```
"Help me build a todo app"
→ AI writes 2000 lines of code
→ Doesn't work
→ "Fix it"
→ AI rewrites everything
→ Still doesn't work
→ Give up
```

This skill fixes that. It turns your AI into a **product manager first, coder second**.

```
"I want to build a ___"
→ AI asks plain-language questions (never technical)
→ AI creates a complete product plan + dev documents
→ You hand the documents to any AI coding tool
→ AI builds it step by step, no chaos
```

**Zero coding experience required. Works in Claude Code, Cursor, Windsurf, Codex.**

## Installation

### Claude Code plugin

```text
/plugin marketplace add Raingle01/vibe-coding-starter
/plugin install vibe-coding-product-launcher@raingle-skills
```

Or from the CLI:

```bash
claude plugin marketplace add Raingle01/vibe-coding-starter
claude plugin install vibe-coding-product-launcher@raingle-skills
```

### Skills CLI

```bash
npx skills add https://github.com/Raingle01/vibe-coding-starter --skill vibe-coding-product-launcher
```
