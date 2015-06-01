### 概要
GitHubにプッシュすると、自動的にブラウザテストが実行されるように設定する。

1. GitHubにプッシュ
2. Travis CIでビルドが開始される
3. Travis CI上でKarmaが起動し、  
   Sauce Labsと連携したブラウザテストを実行
