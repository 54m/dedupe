# これはなんぞ？
[]int{1, 2, 3, 3}や、[]string{"1", "2", "3", "3"}となっているスライスから、
重複しているものを取り除く時に型ごとに自前実装しないといけない
そんな時に一つにまとめられていて少しでも使えるものを作りました。

# 導入
```commandline
go get -u github.com/54mch4n/dedup
```
詳しくは `example/main.go`

# ライセンス
MIT
