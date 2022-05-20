---
tags:
  - personal-knowledge-management
  - data
  - code
  - organization
---
I am trying to find all the [[orphan-notes]] in my [[zettlekasten]]. Ideally, this will include empty notes, so I can track the work left to do on the PKM. Ultimately, this is a [[Workbench]] note, in that I am *keeping track of things* that have not been assigned to a [[kanban]] board. 

What we want here is a [[dataview]] table of orphan notes, and empty notes. So I need to embed a list search in two cells of a table.


Okay, this here is going to break, but basically `-/\[\[` is a [[regular-expressions|regex]] for filtering all notes with internal links -- basically, what we're looking for: orphans. However, not sure if this also filters out empty (but linked) notes. Are internal links the same thing as backlinks?

```dataview
list
where (-/\[\[)
```