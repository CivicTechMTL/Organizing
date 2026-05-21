---
aliases:
  - Venues
---

# Venues

Directory of venues where Civic Tech Montreal holds meetups and events. Each venue has important information about capacity, accessibility, amenities, and booking details.

## Using Venue Pages
- See [Venue Template](Templates/Venue Template.md) for formatting new venue pages
- Include contact info, capacity, amenities, accessibility, and booking requirements
- Note wheelchair accessibility, parking, WiFi, and refreshment options
- Link from [Meetups](Meetups/_Meetups.md) pages and [Venue Finder](Roles/Venue Finder.md) role

## All Venues

```dataview
table capacity, accessible, last-reviewed
from "Venues"
where !contains(file.name, "README")
sort file.name
```

*Table auto-updates as you add venue pages. Requires Dataview plugin.*

## Venue Selection Criteria
- ✓ Capacity of 30-100+ people
- ✓ Wheelchair accessible
- ✓ Free rental
- ✓ Good public transit access
- ✓ WiFi available
- ✓ Projector/screen for presentations

## Booking Process
1. Contact [Venue Finder](Roles/Venue Finder.md) role holder
2. Confirm availability and pricing
3. Submit booking form
4. Create venue page documenting details
5. Link to [Meetups](Meetups/_Meetups.md) that use this venue

---

## Related Documentation
- [[Venue Finder Role|Venue Finder]] - Person responsible for securing venues
- [Meetups](Meetups/_Meetups.md) - Scheduled events and their locations
- [Minutes](Minutes/_Minutes.md) - Venue-related decisions and discussions
