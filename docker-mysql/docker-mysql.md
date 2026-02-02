Docker + MySQL 8.3 接続確認手順書

実行環境
・OS：Windows
・Docker Desktop 使用

データベース構成
・DB：MySQL 8.3
・コンテナ名：mysql83
・ポート番号：3306

起動手順

PowerShell を起動する

docker-mysql フォルダへ移動する

docker compose up -d を実行する

コンテナが起動していることを確認する

接続確認手順

docker exec -it mysql83 bash を実行

mysql -u root -p を実行

パスワードに rootpass を入力

MySQL にログインできることを確認

停止手順
・docker compose down を実行する