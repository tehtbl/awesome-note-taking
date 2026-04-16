# Awesome Note-Taking — Evaluation Parameters

These parameters are designed to highlight **clear, meaningful differences** between note-taking projects when displayed in a simple comparison table.

---

## Parameter Definitions

### 1. Project Health & Activity

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 1 | **GitHub Stars** | Stars | Number (e.g., `35.2k`) | GitHub repo page |
| 2 | **Last Commit** | Last Commit | Date (`YYYY-MM`) or `archived` / `abandoned` | GitHub repo or release page |
| 3 | **Release Cadence** | Releases | `active` (<=3mo), `slow` (3-12mo), `stale` (>12mo), `none`, `archived` | GitHub releases tab |
| 4 | **Contributors** | Contributors | Number | GitHub contributors page |
| 5 | **Open Issues** | Open Issues | Number | GitHub issues tab |

### 2. Licensing & Cost

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 6 | **License** | License | SPDX ID (e.g., `MIT`, `AGPL-3.0`, `GPL-3.0`, `Apache-2.0`) or `Proprietary` | GitHub repo or website |
| 7 | **Pricing Model** | Pricing | `free`, `freemium`, `paid`, `open-core`, `donation-based` | Website pricing page |
| 8 | **Free Tier Limits** | Free Limits | Brief description or `unlimited` or `N/A` | Website pricing page |

### 3. Platform Support

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 9 | **Desktop Platforms** | Desktop | Comma-separated: `Win`, `Mac`, `Linux` or `—` if none | Website/downloads page |
| 10 | **Mobile Platforms** | Mobile | `Android`, `iOS`, `both`, `—` | App stores or website |
| 11 | **Web Access** | Web | `yes`, `self-hosted`, `—` | Website |
| 12 | **Browser Extension** | Extension | `yes`, `—` | Chrome/Firefox store |

### 4. Data & Storage

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 13 | **Storage Format** | Storage | `plain-text/md`, `plain-text/org`, `plain-text/wiki`, `plain-text/other`, `sqlite`, `custom-db`, `proprietary`, `mixed` | Documentation |
| 14 | **Local-First** | Local-First | `yes` (data on device by default), `optional`, `no` (cloud-required) | Documentation |
| 15 | **Self-Hostable** | Self-Host | `yes`, `—` | Documentation |
| 16 | **Export Formats** | Export | Comma-separated: `md`, `pdf`, `html`, `json`, `txt`, `docx`, `enex`, `opml` or `—` | Documentation/features page |
| 17 | **Import From** | Import | Comma-separated known sources: `Evernote`, `Notion`, `Markdown`, `OPML`, etc. or `—` | Documentation |

### 5. Sync & Collaboration

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 18 | **Built-in Sync** | Sync | `yes (proprietary)`, `yes (E2EE)`, `yes (self-hosted)`, `3rd-party only`, `git`, `—` | Features page |
| 19 | **E2E Encryption** | E2EE | `yes`, `optional`, `—` | Security documentation |
| 20 | **Real-time Collaboration** | Collab | `yes`, `—` | Features page |

### 6. Core Features

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 21 | **Editor Type** | Editor | `WYSIWYG`, `markdown`, `block-based`, `outliner`, `rich-text`, `handwriting`, `hybrid` | Try the app or docs |
| 22 | **Markdown Support** | Markdown | `native`, `plugin`, `export-only`, `—` | Documentation |
| 23 | **Backlinks / Graph** | Backlinks | `yes`, `—` | Features page |
| 24 | **Tags / Folders** | Organization | `tags`, `folders`, `both`, `notebooks`, `outliner`, `other` | Features page |
| 25 | **Full-text Search** | Search | `yes`, `—` | Features page |
| 26 | **Plugin / Extension System** | Plugins | `yes (large ecosystem)`, `yes`, `limited`, `—` | Documentation |
| 27 | **API Available** | API | `yes`, `limited`, `—` | Developer documentation |
| 28 | **AI Features** | AI | `built-in`, `plugin`, `—` | Features/pricing page |
| 29 | **Offline Mode** | Offline | `full`, `partial`, `—` | Features page |

### 7. Technology

| # | Parameter | Column Header | Values | How to Check |
|---|-----------|---------------|--------|-------------|
| 30 | **Tech Stack / Framework** | Tech | e.g., `Electron/TypeScript`, `Tauri/Rust`, `Flutter/Dart`, `Native/C++`, `Web/React` | GitHub repo or docs |

---

## Recommended Table Layout (Simplified)

For the final awesome-list table, use this **condensed 15-column format** that maximizes differentiation:

| Tool | Stars | Activity | License | Price | Desktop | Mobile | Web | Storage | Local | E2EE | Sync | Editor | Backlinks | Plugins |
|------|-------|----------|---------|-------|---------|--------|-----|---------|-------|------|------|--------|-----------|---------|

### Column Definitions (Condensed)

- **Stars** = GitHub stars (number)
- **Activity** = `green` active (commit <=3mo), `yellow` slow (3-12mo), `red` stale/archived (>12mo)
- **License** = SPDX or `Proprietary`
- **Price** = `Free`, `Freemium`, `Paid`, `Open-core`
- **Desktop** = `W` Win, `M` Mac, `L` Linux (e.g., `WML`)
- **Mobile** = `A` Android, `i` iOS (e.g., `Ai`)
- **Web** = `yes` / `SH` (self-hosted) / `—`
- **Storage** = `MD` markdown, `DB` database, `Org` org-mode, `Mix`
- **Local** = `yes` local-first / `cloud` cloud-required / `opt` optional
- **E2EE** = `yes` / `—`
- **Sync** = `yes` built-in / `Git` / `3P` third-party / `—`
- **Editor** = `MD` markdown, `WY` WYSIWYG, `BL` block, `OL` outliner, `RT` rich-text
- **Backlinks** = `yes` / `—`
- **Plugins** = `yes` / `—`

---

## High-Differentiator Parameters

These parameters create the **most visible contrast** between tools:

1. **Local-First vs Cloud** — Biggest philosophical divide
2. **E2E Encryption** — Only ~20% of tools have it
3. **Backlinks / Graph View** — Separates PKM tools from simple notepads
4. **Plugin System** — Only ~30% have meaningful plugin ecosystems
5. **Self-Hostable** — Key for privacy-conscious users
6. **Activity Status** — Immediately flags abandoned projects
7. **Storage Format** — Plain-text vs proprietary is a major decision factor
8. **Pricing Model** — Free vs freemium vs paid
9. **Mobile Support** — Many desktop tools lack mobile apps
10. **Real-time Collaboration** — Separates team tools from personal tools
