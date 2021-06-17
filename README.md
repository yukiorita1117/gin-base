# About gin
This is a very light framework, unlike the full stack framework.

## Install

```
go version go1.11
```
であることを確認する。

- ファイルの作成

```
mkdir sample && cd sample
```

- go modを初期化

```
go mod init sample
```

- 初期化完了したら、ginのパッケージを取得する

```
go get -u github.com/gin-gonic/gin
```

- サーバーを立ち上げる

```
go run main.go
```

main.go で指定しているポート番号を叩く
```
engine.Run(":3000")
```

なので localhost:3000 でアクセスする。