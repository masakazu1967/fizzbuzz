# TDD勉強会

価値のある「動作するきれいなコード」を書くためにテスト駆動開発を行う。
2020/02/15にサイボウズ松山オフィスでAgile459により行われた「[TDD Boot Camp in 愛媛 #1](https://agile459.connpass.com/event/161044/)」でt_wadaさんがデモした問題。
[見てわかるテスト駆動開発 / TDD Live and Workshop 2019 Spring](https://speakerdeck.com/twada/tdd-live-and-workshop-2019-spring)

## TDDのサイクル

1. 次の目標を考える
2. その目標を示すテストを書く
3. そのテストを実行して失敗させる(Red)
4. 目的のコードを書く
5. 2で書いたテストを成功させる(Green)
6. テストが通るままでリファクタリングを行う(Refactor)
7. 1から6を繰り返す

## デモ: FizzBuzz問題

1から100までの数をプリントするプログラムを書け。ただし3の倍数の時は数の変わりに「Fizz」と、5の倍数のときは「Buzz」とプリントし、3と5両方の倍数の場合には「FizzBuzz」とプリントすること。

## まとめ

- 問題を小さく分割する
- 歩幅を調整する
  - テスト → 仮実装 → 三角測量 → 実装
  - テスト → 仮実装 → 実装
  - テスト → 明確な実装
- テストの構造化とリファクタリング

## 参考文献

- [TDD Boot Camp in 愛媛 に参加しました！](https://one-person.hatenablog.jp/entry/2020/02/27/192617)
- [TDD Boot Camp in 愛媛 ふりかえり ~やはり俺のTDD Boot Camp参加は間違っていなかった~](https://qiita.com/k2works/items/623fb84001d8c67120a6)
- [動作するきれいなコード: SeleniumConf Tokyo 2019 基調講演文字起こし+α](https://t-wada.hatenablog.jp/entry/clean-code-that-works)