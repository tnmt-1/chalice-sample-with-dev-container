# ベースイメージの指定
FROM postgres

# 環境変数の設定
ENV POSTGRES_USER=myuser
ENV POSTGRES_PASSWORD=mypassword
ENV POSTGRES_DB=mydatabase

# データベースの初期化スクリプトをコンテナにコピー
COPY init.sql /docker-entrypoint-initdb.d/
