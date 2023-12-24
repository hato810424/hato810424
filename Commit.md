# Commit メッセージの書き方
メモ

## フォーマット

[Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)

```
<type>: [emoji] [Issue number] <title>
```

### Type
参考元 - [Gitのコミットメッセージの先頭につけた方が良い単語リスト(prefix集)](https://qiita.com/muranakar/items/20a7927ffa63a5ca226a)

| type | 内容 |
| --- | --- |
| `add` | ファイルなどを追加 |
| `feat` | 新機能を実装 |
| `fix` | 既存の機能などを修正した場合 |
| `hotfix` | 既存の機能の**緊急性の高い不具合**などを修正した場合 |
| `remove` | ファイルなどを削除 |
| `change` | 既存の機能に修正を加えた場合 |
| `perf` | パフォーマンスを向上させる変更 |
| `refactor` | 変数 / 関数 の名前を変更、使っていない物を削除 |
| `update` | ビルドプロセスや補助ツール、ライブラリなどの変更 |
| `style` | 見た目を 変更 / 修正 |
| `docs` | ドキュメント / 文面を更新 |
| `test` | テストコードを 追加 / 修正 |

* 絵文字は[gitmoji](https://gitmoji.dev/)を使うと便利