# 概要

[【動画付き】Rails 5.1で作るVue.jsアプリケーション ～Herokuデプロイからシステムテストまで～](https://qiita.com/jnchito/items/30ab14ebf29b945559f6)
を参考にrailsでVue.jsを扱う。  

* rails導入
* Vue.js導入
* Vue.jsチュートリアルの適用
* heroku本番環境へのデプロイ
* vueファイル即時リロード適用
* システムテスト導入

（伊藤淳一さんの動画は、rubymineあるいはIntelliJ IDEA ultimateを使用している場合、ショートカット等の使用感を覗くことができます）

# 実行
#### 準備
```bash
$ bin/bundle install
```

#### vueファイル変更即時リロードでサーバ起動
```bash
$ bin/server
```

#### システムテスト実行
```bash
bin/rails test:system
```
* テスト失敗時にtmp/screenshotsにpng画像が残る