### サイズの単位をサポート

---

**[DateTime]:Now**で本日の日付データを取得できる。

```powershell
PS C:\Users> $today = [DateTime]::Now
PS C:\Users> $today

2014年8月11日 13:56:43


PS C:\Users> $today.year
2014
PS C:\Users> $today.hour
13
```
