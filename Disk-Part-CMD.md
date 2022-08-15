## cmd as local admin

...

`diskpart` 

`list disk`

`select disk X`

`attribute disk clear readonly`

`clean`

---

#### If Multi Volumes Exist 


`clean all`

---

`create partition primary`

`format quick fs=ntfs`

`assign letter=X`

`exit`

...
---
