\# Docker + WordPress 環境構築手順



\## 1. 作業環境

\- OS：Windows 11

\- Docker Desktop 使用



\## 2. 使用技術

\- WordPress 6.4

\- MySQL 8.3

\- Docker Compose



\## 3. 構築手順



\### ① フォルダ作成

mkdir docker-wordpress



\### ② Dockerfile 作成

内容：

FROM wordpress:6.4



\### ③ docker-compose.yml 作成

WordPress と MySQL を同一 compose 内で定義



\### ④ 起動

docker compose up -d



\### ⑤ 確認

http://localhost:8080 にアクセス



\## 4. 動作確認結果

WordPress のインストール画面および

ログイン画面が表示されることを確認した。



