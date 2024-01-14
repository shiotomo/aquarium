# aquarium

## このリポジトリについて

Dockerコンテナ上でデータベースを管理するためのツールです。

## 使用技術

- Docker
- DockerCompose

## 事前準備


```
cp .env.sample .env
```

.envに各DBで利用したいportやmysqlのroot passwordを設定してください。

## コマンド

実行
```
docker-compose up
```

停止
```
docker-compose down
```

