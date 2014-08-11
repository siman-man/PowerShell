### 文字列操作まとめ

---

PowerShellの文字列操作まとめ。

### toUpper(), toLower()メソッド

```powershell
$message = "Hello World"

write $message
write $message.toUpper()
write $message.toLower()
```

実行結果
```
Hello World
HELLO WORLD
hello world
```
