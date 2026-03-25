---
type: dashboard
tags: [home, dashboard]
---

# Home Dashboard

## Focus for today
- 

## Due soon
```tasks
not done
due before in 7 days
sort by due
```

## Active projects
```dataview
TABLE owner, target
FROM "Projects"
WHERE status = "active"
SORT target ASC
```

## Recently created task notes
```dataview
TABLE created, priority, due
FROM "Tasks"
WHERE type = "tasknote"
SORT created DESC
LIMIT 12
```

