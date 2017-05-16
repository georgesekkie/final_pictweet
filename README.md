## クローン方法

```
$ git clone https://github.com/georgesekkie/final_pictweet.git
$ bundle
#  データベース関連作成(errorpictweet_developmentという名前で生成)
$ bundle exec rake db:create
$ bundle exec rake db:migrate
# サーバー起動
$ rails s
```

## 問題

```
①rootのページでエラーがでる(2箇所問題があります)
②tweetがちゃんとDB に保存されない(2箇所修正点があります)
```
