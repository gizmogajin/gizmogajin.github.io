#db

```ataview
TABLE
	file.mtime AS "Last Modified",
	At_Chapter AS "At Chapter"
FROM "~~~GIZMOGAJIN/Databases/Entries" AND !#db
WHERE Type != "Anime" AND My_Status = "Ongoing"
SORT file.mtime DESC
```

```query
path: "~~~GIZMOGAJIN/Databases/Entries"
```

