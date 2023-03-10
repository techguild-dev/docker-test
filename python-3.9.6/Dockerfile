# ベースイメージ
FROM python:3.9-slim-buster

# アプリの依存パッケージをインストール
RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    default-libmysqlclient-dev \
    && rm -rf /var/lib/apt/lists/*

# 作業ディレクトリを設定
WORKDIR /app

# 依存Pythonライブラリをインストール
# COPY requirements.txt .
# RUN pip install -r requirements.txt

# アプリケーションコードをコピー
COPY . .