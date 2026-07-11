# 執筆ガイド (CONTRIBUTING)

このリポジトリに記事・プロンプトを追加・編集するときの規約をまとめています。

## 1. 新規記事の追加手順

1. `articles/` 配下に `NN-topic-slug/` ディレクトリを作成
   - `NN`: 2 桁の連番（例: `01`, `02`, …）
   - `topic-slug`: 英小文字とハイフンによる短い識別子（例: `bloom-taxonomy-prompts`）
2. `templates/article-template.md` をコピーして `README.md` として配置
3. 必要に応じて以下のサブディレクトリを作成
   - `prompts/` — 記事で紹介するプロンプト（1 プロンプト = 1 ファイル）
   - `examples/` — プロンプトの実行例・出力サンプル
   - `assets/` — 図表・画像
4. ルートの [`README.md`](README.md) の「記事一覧」に行を追加

## 2. 記法ルール

- **GitHub Flavored Markdown** を使用する
- Qiita 記法（`:::note` 等）は **使わない**
- アラートは GitHub の記法を使う:
  ```markdown
  > [!NOTE]     参考情報
  > [!TIP]      便利なヒント
  > [!IMPORTANT] 重要事項
  > [!WARNING]  注意
  > [!CAUTION]  危険・非推奨
  ```
- 見出しレベルは `#`（記事タイトル）から始め、階層を飛ばさない
- コードブロックには言語識別子を付ける（例: ` ```python `, ` ```markdown `）

## 3. プロンプトファイルの規約

- ファイル名: `NN-purpose.md`（例: `01-lesson-plan-generator.md`）
- テンプレートは [`templates/prompt-template.md`](templates/prompt-template.md) を利用
- 冒頭に **目的 / 想定モデル / 教育学的根拠 / 使い方** を必ず記載

## 4. コミット・PR

- コミットメッセージは日本語または英語どちらでも可
- 1 コミット = 1 論理変更を推奨

## 5. ライセンス

投稿されたすべての内容は
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.ja) の下で公開されます。
コントリビュートすることで、この条件に同意したものとみなします。
