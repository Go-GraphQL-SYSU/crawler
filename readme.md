# SWAPI-Crawler

只能将爬取的数据保存到 ./data/data.db中，所以使用前需要自行创建data目录

目录

```
E:.
|   go.mod
|   go.sum
|   main.go
|
\---data
        data.db //运行生成
```

Example

```go
package main

import "github.com/Go-GraphQL-SYSU/crawler"

func main(){
	crawler.ScrapAndSave()
}
```

go.mod

```go
module main

go 1.13

require github.com/Go-GraphQL-SYSU/crawler v0.0.0-20191212062240-3ca1023085eb // indirect
```