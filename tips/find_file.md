### ファイル名の検索

---

Get-ChildItemでの一覧取得からWhere-Objectでのフィルターを行う

```powershell
Get-ChildItem | Where-Object {$_.Name -match ".*.ps1"}
```
