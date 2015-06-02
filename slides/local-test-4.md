### Karma Launcherの設定
テストをどの環境で実行するか設定する。  
`$ karma start`でKarmaが起動する。

```sh
# launcherプラグインのインストール
$ npm install --save-dev karma-chrome-launcher karma-phantomjs-launcher
```

```js
module.exports = function (config) {
  config.set({
    // ...
    browsers: ['Chrome', 'PhantomJS'],
    // ...
  })
};
```

<small>対象ブラウザはローカルにインストールされているものに限られる。  
また、このプロジェクトでは管理を一元化するため、gulpでKarmaを実行するように設定した。</small>
