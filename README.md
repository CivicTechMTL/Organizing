# Civic Tech Montreal — Organizing 

Welcome to the Civic Tech Montreal organizing repo! This is a central knowledge hub for volunteer roles, meetup planning, projects, venues, and organizational information.

## 📖 What's in Here

- **[Roles](Roles/_Roles.md)** — Volunteer positions and detailed runsheets
- **[Meetups](Meetups/_Meetups.md)** — Meetup schedules, event details, and archives
- **[Projects](Projects/_Projects.md)** — Civic tech projects we're working on
- **[Venues](Venues/_Venues.md)** — Meeting spaces and event locations
- **[Minutes](Minutes/_Minutes.md)** — Organizing team meeting notes and decisions
- **[Announcements](Announcements/_Announcements.md)** — Organization news and updates
- **[Resources](Resources/_Resources.md)** — Guides, glossaries, and useful links
- **[Templates](Templates/_Templates.md)** — Document templates for creating new pages

## 🚀 Quick Start

### Option 1: Use in Obsidian (Recommended)

**Obsidian** is a free note-taking app that lets you explore connected documents with wikilinks, just like a personal Wikipedia.

#### Step 1: Download Obsidian
1. Visit [obsidian.md](https://obsidian.md/)
2. Download the free version for your operating system (Mac, Windows, Linux)
3. Install and open Obsidian

#### Step 2: Open This Vault
1. **Clone this repository:**
   ```bash
   git clone https://github.com/CivicTechMTL/Organizing.git
   cd Organizing
   ```

2. **Open in Obsidian:**
   - In Obsidian, click "Open Folder as Vault"
   - Navigate to the `Organizing` folder you just cloned
   - Click "Open" — Obsidian will recognize this as a vault!

3. **Start Exploring:**
   - Click any blue wikilink (like [Roles](Roles/_Roles.md) or [Projects](Projects/_Projects.md)) to navigate
   - Use Obsidian's **Graph View** (Ctrl/Cmd + Shift + G) to see connections between documents
   - Click the file browser on the left to browse by folder

#### Step 3: Install Recommended Plugins

Obsidian has optional community plugins. These are free and enhance the vault:

1. Open Obsidian Settings → Community Plugins → Browse
2. Search for and install:
   - **Front Matter Title** ⭐ *Recommended* — Auto-updates `created` and `updated` dates in YAML frontmatter
   - **Calendar** — See meeting dates in a calendar view
   - **Dataview** — Create dynamic lists and tables from your documents (optional)

**Setting Up Auto-Updated Dates:**
1. Install "Front Matter Title" plugin
2. Go to plugin settings and enable:
   - `Auto update modified date` ✓
   - Set modified date format to `YYYY-MM-DD`
3. Dates will now automatically update when you save files

**Plugin Configuration for Dates:**
```
Modified date field name: updated
Creation date field name: created
Date format: YYYY-MM-DD
```

This ensures every time you edit a document, the `updated` field updates automatically, and `created` stays fixed on the original date.

### Option 2: View on GitHub

If you prefer not to install Obsidian, you can browse the repository directly on GitHub. Wikilinks won't be clickable, but you can still read all the documents. 

---

## 📝 Using This Repo

### Tag Structure

Documents are organized with **hierarchical tags** for easy filtering and discovery:

**Type Tags:**
- `type/role` — Volunteer positions and responsibilities
- `type/project` — Civic tech projects
- `type/venue` — Meeting locations
- `type/meetup` — Meetup events
- `type/minutes` — Meeting notes and decisions
- `type/announcement` — Organization news and updates

**Status Tags:**
- `status/active` — Currently in use or happening
- `status/draft` — Work in progress, not finalized
- `status/archived` — Historical, no longer active

**In Obsidian:**
- Click any tag to see all documents with that tag
- Use the **Tags Pane** (Ctrl/Cmd + Shift + #) to explore all tags
- Filter documents by clicking a tag in a document's frontmatter

### Creating New Documents

Use **Templates** to create new documents with consistent structure:

1. Go to the [Templates](Templates/_Templates.md) folder
2. Copy a template (e.g., [Project Template](Templates/Project Template.md))
3. Paste it and rename it with your content
4. Fill in the details
5. Link it from relevant index pages (like [Projects](Projects/_Projects.md) [[Venues/README|README]])

### Search & Explore

**Find information fast:**
- **Obsidian Search**: Ctrl/Cmd + F searches across all documents
- **Graph View**: Ctrl/Cmd + Shift + G visualizes document connections
- **Backlinks**: At the bottom of any document, see what other pages link to it

### Dynamic Tables with Dataview

Several pages use **Dataview** to automatically compile and display lists:

- **[Venues](Venues/_Venues.md)** — Table of all venues with capacity, accessibility, owner
- **[Projects](Projects/_Projects.md)** — Table of all projects with status, sponsor, repo link

These tables **auto-update** when you create or modify venue/project documents. The YAML frontmatter fields (`capacity`, `status`, `owner`, etc.) populate the tables automatically.

**Install Dataview:**
1. Obsidian Settings → Community Plugins → Browse
2. Search for "Dataview"
3. Install and Enable
4. Tables on [Venues](Venues/_Venues.md) and [Projects](Projects/_Projects.md) will now display live data

See [Obsidian Plugin Setup](Resources/Obsidian Plugin Setup.md) for full plugin configuration details.

---

## 🤝 How to Contribute

We welcome contributions! Here's how:

1. **Clone the repo**: `git clone https://github.com/CivicTechMTL/Organizing.git`
2. **Make changes** in your favorite editor or Obsidian
3. **Commit**: `git commit -m "Add/update [description]"`
4. **Push**: `git push origin main`
5. **Create a Pull Request** on GitHub if you want a review before merging

### Guidelines
- Use [[wikilinks]] to connect related documents
- Update index READMEs when adding new documents
- Keep document titles and links consistent
- Use appropriate [Templates](Templates/_Templates.md) for new content

---

## 📂 Vault Contents

### Core Sections

| Section | Purpose | Key Files |
|---------|---------|-----------|
| [Roles](Roles/_Roles.md) | Volunteer positions and responsibilities | [Host](Roles/Host.md), [Greeter](Roles/Greeter.md), [Project Lead](Roles/Project Lead.md), etc. |
| [Meetups](Meetups/_Meetups.md) | Event schedules and details | [Meetup Schedule](Meetups/Meetup Schedule.md), Individual meetup pages |
| [Projects](Projects/_Projects.md) | Civic tech projects | Project profiles with GitHub links, status |
| [Venues](Venues/_Venues.md) | Meeting locations | Venue contacts, accessibility, capacity |
| [Minutes](Minutes/_Minutes.md) | Organizing decisions | Meeting notes and action items |
| [Announcements](Announcements/_Announcements.md) | News and milestones | Organization updates and achievements |
| [Resources](Resources/_Resources.md) | Guides and references | [How to Contribute](Resources/How to Contribute.md), [Civic Tech Glossary](Resources/Civic Tech Glossary.md), [Useful Links](Resources/Useful Links.md) |

### Meta

- **[Templates](Templates/_Templates.md)** — Document templates for consistency
- **.obsidian/** — Obsidian vault configuration
- **README.md** — This file

---

## 🔗 Important Links

- **GitHub**: [CivicTechMTL/Organizing](https://github.com/CivicTechMTL/Organizing)
- **Website**: [civictechmtl.ca](http://civictechmtl.ca (TBD)
- **Slack**: [#civic-tech-mtl ](https://join.slack.com/t/civictechmontreal/shared_invite/zt-3sx2os89v-6rIwr2sNmhl6r2FZvyPoCQ)
- **Luma**: [luma.com](https://luma.com/civictechmontreal) 

---

## ❓ Questions?

- **Attending a meetup?** Introduce yourself and ask! See [Meetup Schedule](Meetups/Meetup Schedule.md)
- **Want to volunteer?** Check out [How to Contribute](Resources/How to Contribute.md) and [Roles](Roles/_Roles.md)
- **Learning civic tech?** See [Civic Tech Glossary](Resources/Civic Tech Glossary.md) and [Useful Links](Resources/Useful Links.md)
- **Want to start a project?** See [Projects](Projects/_Projects.md)

---

## 🎯 Next Steps

- **New to civic tech?** Start with [How to Contribute](Resources/How to Contribute.md)
- **Looking for a role?** Browse [Roles](Roles/_Roles.md)
- **Interested in a project?** Check [Projects](Projects/_Projects.md)
- **Want to attend?** See [Meetup Schedule](Meetups/Meetup Schedule.md)

Welcome to Civic Tech Montreal! 🚀