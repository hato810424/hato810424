# Commit メッセージの書き方
メモ

## フォーマット

[Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)

```
<type>: [emoji] [Issue number] [title]
```

例
```
fix: 〇〇が動かないバグを修正
```

## Type
参考元 / [Gitのコミットメッセージの先頭につけた方が良い単語リスト(prefix集) - qiita.com](https://qiita.com/muranakar/items/20a7927ffa63a5ca226a)

| Type       | 説明 |
| ---------- | --- |
| `add`      | ファイルを作成、 機能の追加 |
| `feat`     | 新機能を実装 |
| `fix`      | 既存の機能を修正 |
| `hotfix`   | 既存の機能の**緊急性の高い不具合**を修正 |
| `remove`   | ファイルを消去、 機能を削除 |
| `change`   | ファイル名を変更、 既存の機能を変更 |
| `perf`     | パフォーマンスを向上させる変更 |
| `refactor` | 変数 / 関数 の名前を変更、 使っていない物を削除、 コードを修正して改善 |
| `update`   | 補助ツール、ライブラリなどのバージョンを上げた |
| `style`    | 見た目を変更 |
| `docs`     | ドキュメント / 文面を変更 |
| `test`     | テストコードを変更 |
| `chore`    | 自動生成されたものや、上記どれにも当てはまらないもの |

* 絵文字は[gitmoji](https://gitmoji.dev/)を使うと便利