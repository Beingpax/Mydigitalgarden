---
cssClasses: cards cards-1-1 table-wide
---
```dataview
TABLE WITHOUT ID
	(link(file.path, alias)) as title,
	bar
FROM #goal and -"📗Templates"
WHERE Progress != Target
SORT Type DESC
```

---

=== multi-column-start: ID_45p6
```column-settings
Number of Columns: 3
Largest Column: standard
Border: off
```

## To-Do
- [ ] Start using focusmate if i don't work on myself
- [ ] **How to create multiple columns on obsidian***
- [ ] Finish 50% of The Molecule of More

=== end-column ===
## Reading List

- [[& The Molecule of More]]
- [[& Can't Hurt Me]]
- [[& How to live]]

=== end-column ===
## Important Links
- [[🎯Goals]]
- [[🍕 Fleeting Notes]]
- [[💌Rules I LIve By]]

=== multi-column-end

---

=== multi-column-start: ID_02jn
```column-settings
Number of Columns: 2
Largest Column: standard
```
## Recent
`$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(5).file.link)`

=== end-column ===
## Navigation
- [[Writing Ideas]]
- [[Visual Illustrations Ideas]]
- [[Video Ideas]]

=== multi-column-end

---
## [[Notes to Process]]
```dataview 
TABLE file.ctime as "Created" 
FROM #todevelop and "🌻References" 
SORT file.ctime Asc
Limit 12
```
---