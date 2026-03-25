# Obsidian Template Starter Pack

This repo now contains a practical set of Obsidian templates designed for:

- **TaskNotes-style task capture**
- **PARA project management (Projects / Areas / Resources / Archive)**
- **Daily and meeting workflows**
- **Plugin-aware templates** for:
  - Advanced Canvas
  - Copilot
  - Dataview
  - Excalidraw
  - Multi-Column Markdown
  - Shell Commands
  - Simple CanvaSearch
  - Style Settings
  - Tasks
  - Templater
  - Tray

## Folder layout

- `Templates/Daily` — daily notes and standups
- `Templates/Meetings` — meeting and 1:1 templates
- `Templates/Notes` — evergreen/permanent/reference notes
- `Templates/Projects` — project and weekly review templates
- `Templates/Tasks` — TaskNote/task templates
- `Templates/Canvas` — `.canvas` starter file and canvas workflow notes
- `Templates/Excalidraw` — Excalidraw markdown starter
- `Templates/Shell` — shell-command snippets for plugin integration

## Recommended Obsidian setup

1. Install and enable your community plugins.
2. Set template folder to `Templates` (Core Templates plugin) **or** use Templater with this path.
3. (Optional) Configure hotkeys:
   - Daily note template
   - New task note template
   - New meeting note template
4. In **Templater**, enable:
   - Trigger Templater on new file creation
   - Folder templates mapped to your preferred destinations

## Quick start workflow

1. Create daily note from `Templates/Daily/Daily Note.md`.
2. Capture actionable items with `Templates/Tasks/TaskNote.md`.
3. Run weekly review from `Templates/Projects/Weekly Review.md`.
4. Use `Templates/Canvas/Project Discovery.canvas` when planning visually.

## Notes on plugin usage

- **Tasks** queries are included using fenced ```tasks``` blocks.
- **Dataview** snippets assume files include frontmatter fields like `status`, `due`, `area`, `project`.
- **Multi-Column Markdown** uses callout containers that can be styled per your theme.
- **Excalidraw** template includes frontmatter and placeholders commonly recognized by Excalidraw plugin.
- **Shell Commands** examples are in markdown; map them to your local environment.

