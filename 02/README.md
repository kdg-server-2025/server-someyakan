# server-someyakan
## 2回目の授業
# main.goファイルを作る
# main.goを実行する
go run main.go

# Dockerfileを作成
# go-helloという名前のdockerイメージを作成
docker build -t go-hello .

# コンテナを実行
docker run go-hello