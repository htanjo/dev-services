### テストコード
BDDスタイルはJavaScriptというより、ほとんど英文に近い。
"test"よりも"spec"と呼ばれることもある。

<small>BDD : Behavior Driven Development（振る舞い駆動開発）</small>

```js
describe('.destroy()', function () {
  it('cleans up the target element', function () {
    dyframe.destroy();
    expect(element.innerHTML).to.be.empty;
  });
});
```
