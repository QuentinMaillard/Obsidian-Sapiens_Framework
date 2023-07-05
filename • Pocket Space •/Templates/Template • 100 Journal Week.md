⬆️ up :: [[112. Weeks]]

🏷️ tags :: #index/embodiment

---

# This week notes
```dataviewjs
let currentWeekNumber = dv.current().date.weekNumber;
dv.list(dv
	.pages("#daily_note")
	.where(n => n.date.weekNumber == currentWeekNumber)
	.sort(n => n.date)
	.file.link)
```
