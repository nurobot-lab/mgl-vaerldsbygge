---
tags:
  - wiki
links: halvädelsten
aliases:
---
# halvädelstenar

---
```dataview
TABLE WITHOUT ID
file.link AS "ID", file.etags AS "Type", join(file.outlinks, [delimiter]) AS "Mentions"
FROM [[]]
```