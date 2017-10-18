# Ruby on Rails チュートリアルのサンプルアプリケーション

# 使い方
まずGemをインストールしてください。
```
bundle install --without production
```
次にデータベースのマイグレーションを実行します。
```
rails db:migrate
```
最後に、テストを実行してうまく動いているか確認してください。
```
rails test
```
テストが無事に通ったらRailsサーバを立ち上げる準備が整っているはずです。
```
rails server
```

