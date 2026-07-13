# prompt-to-pedagogy

**プロンプト設計と教育学をつなぐ** ためのオープンな執筆プロジェクト。
生成 AI へのプロンプト設計を、教育学（学習理論・授業設計・評価論）の
知見と接続することを目的とした記事群を公開しています。

## 🎯 このリポジトリの目的

- プロンプト設計を「思いつき」ではなく **教育学の理論に基づいた設計行為** として捉え直す
- 教育現場・研修設計・EdTech 開発に活かせる **実践可能な知見** を蓄積する
- 記事・プロンプトの両方をオープンに共有し、再利用と改善を促す

## 📚 記事一覧

> **推奨読み順**: **特別編 第 2 回 (俯瞰マップ) → 特別編 第 1 回 (校務への応用) → 本編 第 1〜17 回 (授業設計への応用)**
> の順で読むと、6 層モデルという同じ視点で連載全体を通貫できます。

| 読む順 | No. | タイトル | ステータス | ディレクトリ |
| :-: | :-: | :------ | :-------: | :---------- |
| 1  | S2  | **特別編 第2回:** プロンプトの書き方だけを教わっても、なぜ授業も校務も変わらないのか (**俯瞰マップ / 6 層モデル**) | 公開 | [`articles/special-02-beyond-prompts/`](articles/special-02-beyond-prompts/) |
| 2  | S1  | **特別編 第1回:** 学校の働き方改革を変える生成 AI の使い方 (**6 層を校務に応用**) | 公開 | [`articles/special-01-work-style-reform-ai/`](articles/special-01-work-style-reform-ai/) |
| 3  | 01  | 第1回: Instructional Design と生成 AI | 公開 | [`articles/01-instructional-design-and-generative-ai/`](articles/01-instructional-design-and-generative-ai/) |
| 4  | 02  | 第2回: Analysis — 佐藤先生が自分を分析した日 | 公開 | [`articles/02-addie-analysis-teacher-self-understanding/`](articles/02-addie-analysis-teacher-self-understanding/) |
| 5  | 03  | 第3回: Analysis — 学習者分析 | 公開 | [articles/03-addie-analysis-learner-analysis/](articles/03-addie-analysis-learner-analysis/) |
| 6  | 04  | 第4回: Analysis — タスク分析 | 公開 | [articles/04-addie-analysis-task-analysis/](articles/04-addie-analysis-task-analysis/) |
| 7  | 05  | 第5回: Analysis — 環境・制約分析 | 準備中 | [`articles/05-addie-analysis-context-analysis/`](articles/05-addie-analysis-context-analysis/) |
| 8  | 06  | 第6回: Design — 逆向き設計 | 準備中 | [`articles/06-addie-design-backward-design/`](articles/06-addie-design-backward-design/) |
| 9  | 07  | 第7回: Design — ルーブリックの共同設計 | 準備中 | [`articles/07-addie-design-rubric-codesign/`](articles/07-addie-design-rubric-codesign/) |
| 10 | 08  | 第8回: Design — 授業構造 (Gagné × Merrill) | 準備中 | [`articles/08-addie-design-lesson-structure/`](articles/08-addie-design-lesson-structure/) |
| 11 | 09  | 第9回: Development — 教材ドラフトと査読ループ | 準備中 | [`articles/09-addie-development-material-draft/`](articles/09-addie-development-material-draft/) |
| 12 | 10  | 第10回: Development — 差異化と多モダリティ | 準備中 | [`articles/10-addie-development-differentiation/`](articles/10-addie-development-differentiation/) |
| 13 | 11  | 第11回: Development — プロンプト・パターンカタログ | 準備中 | [`articles/11-addie-development-prompt-catalog/`](articles/11-addie-development-prompt-catalog/) |
| 14 | 12  | 第12回: Implementation — 授業前リハーサル | 準備中 | [`articles/12-addie-implementation-rehearsal/`](articles/12-addie-implementation-rehearsal/) |
| 15 | 13  | 第13回: Implementation — 授業中の AI ファシリテーション | 準備中 | [`articles/13-addie-implementation-in-class-ai/`](articles/13-addie-implementation-in-class-ai/) |
| 16 | 14  | 第14回: Evaluation — 形成的評価 | 準備中 | [`articles/14-addie-evaluation-formative/`](articles/14-addie-evaluation-formative/) |
| 17 | 15  | 第15回: Evaluation — 総括的評価とポートフォリオ | 準備中 | [`articles/15-addie-evaluation-summative/`](articles/15-addie-evaluation-summative/) |
| 18 | 16  | 第16回: Evaluation — プログラム評価と次サイクル | 準備中 | [`articles/16-addie-evaluation-program/`](articles/16-addie-evaluation-program/) |
| 19 | 17  | 第17回: 佐藤先生の 1 年後 (統合ふりかえり) | 準備中 | [`articles/17-reflection-one-year-later/`](articles/17-reflection-one-year-later/) |

> [!NOTE]
> 連載全体の設計・依存関係・各回の詳細は
> [`shared/series-plan.md`](shared/series-plan.md) を参照してください。

## 🗂 ディレクトリ構成

```
prompt-to-pedagogy/
├── README.md              # このファイル（プロジェクト概要・記事一覧）
├── LICENSE                # CC BY-NC 4.0
├── CONTRIBUTING.md        # 執筆ガイド
├── articles/              # 記事本体（テーマごとに 1 ディレクトリ）
│   └── NN-topic-slug/
│       ├── README.md      # 記事本文（GitHub Flavored Markdown）
│       ├── prompts/       # 記事に対応するプロンプト集
│       ├── examples/      # 実行例・出力サンプル
│       └── assets/        # 図表・画像
├── templates/             # 新規記事・プロンプトのテンプレート
│   ├── article-template.md
│   └── prompt-template.md
└── shared/                # 全記事共通のリソース
    ├── glossary.md        # 用語集（教育学 × プロンプト設計）
    └── references.md      # 参考文献リスト
```

## ✍️ 執筆ガイド

- 記法: **GitHub Flavored Markdown**
- アラートは `> [!NOTE]` / `> [!TIP]` / `> [!WARNING]` / `> [!IMPORTANT]` / `> [!CAUTION]` を使用
- 詳細は [`CONTRIBUTING.md`](CONTRIBUTING.md) を参照

## 📄 ライセンス

本リポジトリのすべてのコンテンツ（記事・プロンプト・図表）は
**[Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.ja)**
の下で提供されています。

- ✅ 共有・翻案は自由
- ✅ クレジット表示（著作者名・ライセンス・変更の明示）が必要
- ❌ **営利目的での利用は不可**

詳細は [`LICENSE`](LICENSE) を参照してください。
