---
type: daily
date: <% tp.date.now("YYYY-MM-DD") %>
weekday: <% tp.date.now("dddd") %>
focus:
energy:
tags: [daily]
---

# <% tp.date.now("YYYY-MM-DD dddd") %>

> [!multi-column]
>
>> [!todo]- Top 3
>> - [ ] 
>> - [ ] 
>> - [ ] 
>
>> [!tip]- Personal
>> - [ ] Workout
>> - [ ] Read 20 min
>> - [ ] Journal

## Task Inbox (TaskNotes)
- [ ] Capture each new task as a dedicated note using `TaskNote.md`

## Today (Tasks Plugin)
```tasks
not done
(due on today) OR (happens on today)
sort by priority
```

## Open High Priority
```tasks
not done
priority is high
sort by due
```

## Dataview: recently touched project notes
```dataview
TABLE file.mtime as "Last Modified", status
FROM "Projects"
SORT file.mtime DESC
LIMIT 8
```

## Notes
- 

## End of day
- Wins:
- Lessons:
- Carry forward:

