
ORDER BY Varchar  Desc
```sql
ORDER BY { fn LENGTH(SUBBARCODE) } DESC ,SUBBARCODE DESC

```


Clear Gap Enter Copy From Excel
```sql
UPDATE Table_name
SET Col = REPLACE(REPLACE(Colname, CHAR(13), ''), CHAR(10), '')
```


Where Condition Date +- 2 Year
```sql
 (RIGHT(LEFT(Colname, 4), 2) BETWEEN RIGHT(YEAR(GETDATE() - 365), 2) AND RIGHT(YEAR(GETDATE()), 2))
```
