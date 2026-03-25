---
type: review
cadence: weekly
date: <% tp.date.now("YYYY-[W]WW") %>
tags: [review, weekly]
---

# Weekly Review — <% tp.date.now("YYYY-[W]WW") %>

## 1) Close loops
```tasks
not done
due before tomorrow
sort by due
```

## 2) Review active projects
```dataview
TABLE status, owner, target
FROM "Projects"
WHERE status = "active"
SORT target ASC
```

## 3) Choose next week focus (max 3)
- [ ] 
- [ ] 
- [ ] 

## 4) Cleanup
- [ ] Archive completed notes
- [ ] Clear inboxes
- [ ] Re-prioritize high-impact tasks

