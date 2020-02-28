# NumberToWords
Convert number to thai language words with Golang

แปลงตัวเลขเป็นคำอ่านภาษาไทยด้วยภาษา Go
# Getting Started
Install : ติดตั้ง

```go get -u github.com/earthrockey/numbertowords```

Use : ใช้งาน

```
import (
  "github.com/earthrockey/numbertowords"
)

func main() {
  words := numbertowords.NumToWords(12345) //parameter type int output type string
  fmt.Println(words) 
}
```
```
Output
>>> หนึ่งหมื่นสองพันสามร้อยสี่สิบห้า
```
# License
earthrockey
