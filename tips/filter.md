### フィルターをかける

---

**Where-Object**を使用すると、与えた条件に合致したオブジェクトをフィルターしてくれる。

```
Get-Process | Where-Object { $_.Name -like "*Search*" }
```
