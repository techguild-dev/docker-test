FROM golang:1.18.1-alpine
# アップデートとgitのインストール
RUN apk update && apk add git

# 作業ディレクトリを設定
WORKDIR /app

COPY . .