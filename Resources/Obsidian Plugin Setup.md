---
tags:
  - type/resource
  - status/active
created: 
updated: 
---

# Obsidian Plugin Setup Guide

This guide walks you through setting up recommended plugins for the Civic Tech Montreal organizing vault.

## Required Plugin: Front Matter Title

This plugin automatically updates the `updated` field in YAML frontmatter whenever you save a file.

### Installation

1. Open Obsidian and go to **Settings**
2. Select **Community Plugins** in the left sidebar
3. Click **Browse**
4. Search for **"Front Matter Title"**
5. Click **Install**
6. Click **Enable** to activate the plugin

### Configuration

1. Go back to **Settings** → **Community Plugins**
2. Find **Front Matter Title** and click the ⚙️ gear icon
3. Configure these settings:

| Setting | Value |
|---------|-------|
| Modified date field name | `updated` |
| Creation date field name | `created` |
| Date format | `YYYY-MM-DD` |
| Automatically update modified date | ✓ Enabled |

4. Close settings

### How It Works

- **`created`** — Set automatically when you first create a file, never changes
- **`updated`** — Updates automatically every time you save the file
- **Date format** — All dates display as `YYYY-MM-DD` (e.g., `2026-05-20`)

### Verifying It Works

1. Create a new document from a template
2. Check the YAML frontmatter at the top
3. Edit the document
4. Save (Ctrl/Cmd + S)
5. The `updated` field should now show today's date

## Optional Plugins

### Dataview
Create dynamic lists and queries across your vault.

**Example:** List all active projects
```dataview
task where contains(tags, "status/active") and contains(tags, "type/project")
```

### Calendar
See your meetup dates in a calendar view.

### Graph Analysis
Visualize connections between documents.

---

## Troubleshooting

**Dates not updating?**
- Make sure Front Matter Title is enabled in Community Plugins
- Check that the field names match exactly: `created` and `updated`
- Save the file after editing (Ctrl/Cmd + S)

**Dates in wrong format?**
- Go to Front Matter Title settings
- Verify date format is set to `YYYY-MM-DD`
- Re-save the file

**Questions?**
- Check Obsidian's help: [obsidian.md/help](https://obsidian.md/help)
- Front Matter Title docs: See plugin description in Community Plugins
