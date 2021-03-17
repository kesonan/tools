# tools
Golang学习过程中编写的工具集

[![Go](https://github.com/anqiansong/tools/actions/workflows/go.yml/badge.svg)](https://github.com/anqiansong/tools/actions/workflows/go.yml)

# package目录
* sqlx
  * `orm`
    `sql.Rows` 映射操作，将 `sql.Rows` 通过反射映射到一个指针变量（接收体）中。
* syncx
    `singleflight` 并发访问共享结果，推荐使用 `golang.org/x/sync/singleflight`