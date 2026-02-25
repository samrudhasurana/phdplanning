# PhD Hub

> "The curious task of economics is to demonstrate to men how little they really know about what they imagine they can design." — Hayek

---

## Quick Links

- [Google Scholar Profile](#)
- [SSRN](#)
- [Student Portal](#)
- [ORCID-ID](#)

---

## Sections

| Section | Description |
|---------|-------------|
| [Tasks](./tasks/_index.md) | Track all research tasks by priority and status |
| [Research](./research/projects-overview.md) | Projects, meeting notes, literature, collaborators |
| [Papers](./papers/papers-overview.md) | Individual paper drafts and status |
| [Dissertation](./dissertation/overview.md) | Dissertation chapters overview |
| [Career](./career/publication-record.md) | Publications, opportunities, contacts |

---

## Quick Actions (CLI)

```bash
# Add a new task
phd task add "Task Title" --priority high --due 2026-03-01 --chapter "Chapter 4"

# Add a meeting or seminar note
phd note add "Advisor Meeting" --date 2026-02-25 --type meeting

# Add a paper to your reading list
phd lit add "Paper Title" --authors "Author Name" --year 2024 --journal "Journal Name"

# View all tasks
phd task list

# View upcoming deadlines
phd calendar

# Commit and push changes to GitHub
phd push "update: added new task"
```

See `phd help` for the full command reference.
