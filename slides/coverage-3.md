### ![Logo](img/logo-coveralls.png) Coveralls
<https://coveralls.io/>

カバレッジの情報を元に、解析結果を表示・通知してくれる  
オンラインサービス。
無料で利用できる。

- Travis CIと連携し、ビルドごとに結果を集計できる
- 対象コードが行単位で色分け表示され、見やすい
- GitHubのプルリクエストとも連動する

<small>事前にCoverallsの管理画面で対象リポジトリを設定しておく。  
[karma-coveralls](https://github.com/caitp/karma-coveralls)プラグインを使うと、Karmaの実行で自動送信できるようになる。</small>
