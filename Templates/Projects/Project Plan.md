---
type: project
status: active
owner:
area:
start: <% tp.date.now("YYYY-MM-DD") %>
target:
review: weekly
tags: [project]
---

# Project: <% tp.file.title %>

## Why

## Success Criteria
- [ ] 
- [ ] 

## Scope
### In
- 

### Out
- 

## Milestones
- [ ] M1 — date
- [ ] M2 — date
- [ ] M3 — date

## TaskNotes Index
```dataview
TABLE status, priority, due
FROM "Tasks"
WHERE project = this.file.name
SORT due ASC
```

## Risks
- 

## Resources
- 

