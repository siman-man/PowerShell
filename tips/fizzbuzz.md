### PowerShellでFizzBuzz

---

書いてみた

```powershell
for($i = 1; $i -le 100; $i++){
  if( $i % 15 -eq 0 ){
    write("FizzBuzz")
  }elseif( $i % 5 -eq 0 ){
    write("Buzz")
  }elseif( $i % 3 -eq 0 ){
    write("Fizz")
  }else{
    write("$i")
  }
}
```
