# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](code-of-conduct.md). By participating in this
project you agree to abide by its terms.

## Adding a new tool

Please ensure your pull request adheres to the following guidelines:

### Entry format

```
- [icons] [Tool Name](URL) - Brief description ending with a period. `LICENSE` `Tech/Language`
```

**Examples:**

```
- 📖🔁 [Joplin](https://joplinapp.org/) - Open source note-taking with sync and E2EE support. `AGPL-3.0` `Electron/TypeScript`
- 📕🤖🔁 [Taskade](https://www.taskade.com) - Collaborative note-taking and task management with AI. (Proprietary)
```

### Icon reference

| Icon | Add when... |
|:----:|:------------|
| 📖 | Notes are stored in plain text (Markdown, org-mode, wiki, etc.) |
| 📕 | Notes are stored in a database or proprietary format |
| 🤖 | The tool has an Android app |
| 🍎 | The tool has an iOS app |
| 👍 | You have personally used it for years and recommend it |
| 🔁 | The tool provides built-in multi-device sync |
| 🔒 | The tool supports end-to-end encryption |
| ⚠️ | Project is archived or no longer actively maintained |

### Checklist for new entries

- [ ] The tool is primarily for note-taking or knowledge management
- [ ] The description is concise (1-2 sentences) and ends with a period
- [ ] The link goes to the official website or GitHub repo
- [ ] Icons are accurate (check platform support, sync, encryption)
- [ ] For open-source tools: license (SPDX) and tech stack are included
- [ ] The entry is added to the correct category
- [ ] The entry is not a duplicate of an existing entry
- [ ] The tool is actively maintained (last commit within 12 months)

### Categories

Pick the **single most appropriate** category:

- **Native GUI** — Desktop apps with native UI (Qt, GTK, SwiftUI, Flutter, etc.)
- **CLI** — Command-line tools
- **TUI** — Terminal user interfaces
- **Editor Plugin** — Plugins for text editors (VS Code, Emacs, Vim, etc.)
- **Electron** — Desktop apps built with Electron
- **Tauri** — Desktop apps built with Tauri
- **Web UI** — Web-based or self-hosted applications
- **Proprietary** — Closed-source commercial tools

## Updating your PR

If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md)
on the different ways you can update your PR so that we can merge it.
