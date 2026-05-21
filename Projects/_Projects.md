---
aliases:
  - Projects
---
# Civic Tech Projects

Overview of active and past civic tech projects developed at Civic Tech Montreal. Each project has a dedicated page with details about the sponsor, status, and GitHub repository.

## Using Project Pages
- See [Project Template](Templates/Project Template.md) for formatting new project pages
- Include sponsor, start date, description, current status, and GitHub repo link
- Link to [Roles](Roles/_Roles.md) of team members and [Venues](Venues/_Venues.md) for project work sessions
- Update status regularly and include latest updates

## All Projects

```dataview
table status, sponsor, repo-link, start-date
from "Projects"
where !contains(file.name, "README") and contains(tags, "type/project")
sort status
```

**Filter by Status:**
```dataview
table status, sponsor, updated
from "Projects"
where !contains(file.name, "README") and status = "In Progress"
sort file.name
```

*Tables auto-update as you add/modify project pages. Requires Dataview plugin.*

## Project Status Types
- **In Planning**: Concept phase, gathering requirements
- **In Progress**: Active development or implementation
- **On Hold**: Paused temporarily
- **Completed**: Project delivered or concluded

## How to Add a Project
1. Create a new file using the [Project Template](Templates/Project Template.md)
2. Fill in sponsor, date, description, status, and repo link
3. Link it from this README
4. Link from related [Roles](Roles/_Roles.md) and [Meetups](Meetups/_Meetups.md)

---

## Related Documentation
- [Roles](Roles/_Roles.md) - Team members and project leadership
- [Meetups](Meetups/_Meetups.md) - Where projects are discussed and demoed
- [Resources](Resources/_Resources.md) - Shared tools, guides, and documentation
- [Minutes](Minutes/_Minutes.md) - Project decisions and updates
