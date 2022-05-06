# cirkit-blog
株式会社CirKitのブログ

# 構成
* Next.js
* Prisma
* MariaDB
* Tailwind CSS

# 環境構築
* DockerエンジンとDocker Composeをインストールする
* Dockerのネットワークを作る
  * `docker network create cirkit-blog`
* このリポジトリをフォークしてフォーク先リポジトリをクローンする
* .envファイルを作る
* コンテナを起動する
  * `docker-compose up`
* http://localhost:3000 にアクセスする

# Tips
## Prisma Studioにアクセスする

* コンテナを起動する

```bash
docker-compose up
```

* Prisma Studioを起動する

```bash
docker-compose exec nextjs yarn prisma studio
```

* http://localhost:5555 にアクセスする
