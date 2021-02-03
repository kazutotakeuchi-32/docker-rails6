## Usage

``` zsh
# プロジェクト作成
  docker-compose run app rails new app  --force  --database=mysql  --webpacker
# ビルド
  docker-compose build
# webpacker insatall
  docker-compose run app rails webpacker:install
# DB作成
  docker-compose run app rails db:create
#  起動
  docker-compose run app bin/webpack-dev-server
  docker-compose　up
```
