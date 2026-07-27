---
Lore Type: Lore
GVG Role: Lore
---
# Lore

- [[#Guild|Guild]]
- [[#Fanfiction|Fanfiction]]


---
## Guild
* ### Heka's Wedding Rehearsal
	* https://youtu.be/6HhB1TfMzAo

---
## Fanfiction

![[Lore.base]]

```dataview
TABLE lore-type, date, author, collaborators
FROM ![[Lore.base]]
where author != null
sort lore-type, date desc
```