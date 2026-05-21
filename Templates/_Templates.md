---
aliases:
  - Templates
tags:
  - type/resource
  - status/active
---

# Templates

Document templates for creating consistent, structured files in the vault.

## Available Templates

Each template includes YAML frontmatter with tags and metadata fields, making it easy to create new documents that fit seamlessly into the vault.

### Role Template
[[Role Template]] - Use for documenting volunteer positions

### Project Template
[Project Template](Templates/Project Template.md) - Use for creating new project pages with sponsor, status, repo-link tracking

### Venue Template
[Venue Template](Templates/Venue Template.md) - Use for documenting meeting venues with capacity, accessibility, contact info

### Meetup Template
[Meetup Template](Templates/Meetup Template.md) - Use for planning individual meetup events with agenda, roles, projects

### Meeting Notes Template
[Meeting Notes Template](Templates/Meeting Notes Template.md) - Use for documenting organizing team meetings with attendees, decisions, action items

### Announcement Template
[Announcement Template](Templates/Announcement Template.md) - Use for publishing organization news and milestone updates

## How to Use Templates

1. Go to the [Templates](Templates/_Templates.md) folder
2. Open the template that matches your document type
3. Copy the entire content (including YAML frontmatter)
4. Create a new file in the appropriate folder
5. Paste the template and fill in your information
6. Save and link from relevant index pages (like [Projects](Projects/_Projects.md) README or [Venues](Venues/_Venues.md) README)

## Template Benefits

- **Consistent YAML** — All documents have the same metadata fields for querying with Dataview
- **Wikilinks** — Frontmatter and structure make it easy to cross-link documents
- **Tags** — Predefined tag structure for filtering and discovery
- **Metadata** — Auto-updating dates, status tracking, and other fields

---

## Related
- [Resources](Resources/_Resources.md) - Other guides and documentation
- [Obsidian Plugin Setup](Resources/Obsidian Plugin Setup.md) - Setup Dataview and other plugins to work with templates
