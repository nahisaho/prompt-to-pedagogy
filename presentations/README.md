# Presentations — プレゼンテーションコンテキスト

各回の記事内容を、講演・研修・オンラインセミナーで使えるプレゼンテーションに
翻訳したコンテキスト集。**スライドは含まず**、各スライドを作るための
「設計図 (context)」を Markdown で保存する。

- **著者:** nahisaho
- **ライセンス:** [CC BY-NC 4.0](../LICENSE)

## 各ファイルの構造

1 ファイル = 1 回分のプレゼン (10〜25 スライド)。各スライドに次の 4 要素を持つ。

| 要素 | 説明 |
|:--|:--|
| **Slide N — タイトル** | 見出し。パワーフレーズを入れて、1 スライド 1 メッセージを守る |
| **Subtitle** (任意) | 補助タイトル。必要な場合のみ |
| **Visual (画像生成用)** | AI 画像生成に渡すための **詳細な視覚描写**。構図・配色・登場要素・図表・ノイズにしたい印象語を含む |
| **Talk Script** | 発表者が話す文章 (1〜2 分 = 300〜500 字を目安) |

## 一覧

| # | ファイル | フェーズ | 主題 |
|:-:|:--|:--|:--|
| 00 | [00-evolution-of-generative-ai.md](00-evolution-of-generative-ai.md) | 序章 | 生成 AI の進化 (確率の子 → 推論する相棒) |
| 01 | [01-instructional-design-and-generative-ai.md](01-instructional-design-and-generative-ai.md) | 総論 | 授業設計 (ID) と生成 AI |
| 02 | [02-addie-analysis-teacher-self-understanding.md](02-addie-analysis-teacher-self-understanding.md) | Analysis | 教師の自己分析 |
| 03 | [03-addie-analysis-learner-analysis.md](03-addie-analysis-learner-analysis.md) | Analysis | 学習者分析 |
| 04 | [04-addie-analysis-task-analysis.md](04-addie-analysis-task-analysis.md) | Analysis | タスク分析 |
| 05 | [05-addie-analysis-context-analysis.md](05-addie-analysis-context-analysis.md) | Analysis | 環境・制約分析 |
| 06 | [06-addie-design-backward-design.md](06-addie-design-backward-design.md) | Design | 逆向き設計 |
| 07 | [07-addie-design-rubric-codesign.md](07-addie-design-rubric-codesign.md) | Design | ルーブリック共同設計 |
| 08 | [08-addie-design-lesson-structure.md](08-addie-design-lesson-structure.md) | Design | 授業構造 |
| 09 | [09-addie-development-material-draft.md](09-addie-development-material-draft.md) | Development | 教材ドラフト |
| 10 | [10-addie-development-differentiation.md](10-addie-development-differentiation.md) | Development | 差異化と多モダリティ |
| 11 | [11-addie-development-prompt-catalog.md](11-addie-development-prompt-catalog.md) | Development | プロンプトカタログ |
| 12 | [12-addie-implementation-rehearsal.md](12-addie-implementation-rehearsal.md) | Implementation | 授業前リハーサル |
| 13 | [13-addie-implementation-in-class-ai.md](13-addie-implementation-in-class-ai.md) | Implementation | 授業中の AI |
| 14 | [14-addie-evaluation-formative.md](14-addie-evaluation-formative.md) | Evaluation | 形成的評価 |
| 15 | [15-addie-evaluation-summative.md](15-addie-evaluation-summative.md) | Evaluation | 総括的評価 |
| 16 | [16-addie-evaluation-program.md](16-addie-evaluation-program.md) | Evaluation | プログラム評価 |
| 17 | [17-reflection-one-year-later.md](17-reflection-one-year-later.md) | Reflection | 1 年後のふりかえり |
| S1 | [special-01-work-style-reform-ai.md](special-01-work-style-reform-ai.md) | 特別編 | 学校の働き方改革を変える生成 AI の使い方 |
| S2 | [special-02-beyond-prompts.md](special-02-beyond-prompts.md) | 特別編 | プロンプトの書き方だけを教わっても、なぜ授業も校務も変わらないのか |

## 使い方

1. 画像生成 AI (DALL·E / Imagen / Firefly など) に `Visual` セクションを渡し、
   1 スライド 1 画像を生成
2. スライドツール (Google Slides / PowerPoint / Keynote / Marp) に貼り付け
3. `Talk Script` を発表原稿として使用 (1 スライド 1〜2 分)

## 共通ビジュアルガイド

全 17 プレゼンで統一する視覚言語:

- **配色:** 落ち着いた紺 (#1F3A5F) / 温かい橙 (#E68A2E) / 象牙色の背景 (#F7F3EA) を基調
- **人物:** 佐藤美咲先生 (30 代女性、黒髪ボブ、控えめな笑顔、
  カーディガンにブラウスが多い) を主人公として一貫して描く
- **AI の擬人化を避ける:** AI は光の粒・ホログラム・ノートブックの脇に浮かぶ図
  として抽象的に表現。ロボットや人型では描かない
- **教室:** 日本の高校教室 (ホワイトボード、生徒机 40 席想定)
- **タイポ:** 日本語 (源ノ角ゴシック / Noto Sans JP) を想定
- **画面比:** 16:9
