---
type: shell-commands
tags: [shell-commands, automation]
---

# Shell Commands plugin snippets

> Adapt paths for your machine and vault location.

## Open today's daily note (Linux/macOS)
```bash
obsidian "obsidian://open?vault=ObsidianFiles&file=Daily%2F$(date +%Y-%m-%d)"
```

## Quick git status in vault
```bash
cd /path/to/ObsidianFiles && git status --short --branch
```

## Commit note changes
```bash
cd /path/to/ObsidianFiles && git add . && git commit -m "vault: update notes" && git push
```

## Export markdown list of overdue tasks (ripgrep)
```bash
cd /path/to/ObsidianFiles && rg "- \[ \].*due::" -n
```

