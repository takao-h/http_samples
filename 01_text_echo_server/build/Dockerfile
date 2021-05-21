# go version
FROM golang:1.16.3-alpine

# update & git install
RUN apk add --update &&  apk add git

# make app dir
RUN mkdir /go/src/app
# ワーキングディレクトリの設定
WORKDIR /go/src/app
# ホストのファイルをコンテナの作業ディレクトリに移行
ADD . /go/src/app
