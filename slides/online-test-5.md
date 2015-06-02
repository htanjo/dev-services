KarmaにはSauce Labs連携用の[karma-sauce-launcher](https://github.com/karma-runner/karma-sauce-launcher)プラグインがあり、簡単にセットアップできる。

`karma.conf.js`の設定（一部を抜粋）
```js
customLaunchers: {
  'SL_IE_11': {
    base: 'SauceLabs',
    browserName: 'internet explorer',
    platform: 'Windows 8.1',
    version: '11'
  },
  // ...
}
```

<small>ローカルでのテストとは異なり、複数のOS・ブラウザのバージョンでテストが実行できる。</small>
