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

> **推奨読み順**: **S2 (俯瞰マップ) → S1 (校務への応用) → 00〜17 (授業設計への応用)**

| 読む順 | # | ファイル | フェーズ | 主題 |
|:-:|:-:|:--|:--|:--|
|  1 | S2 | [special-02-beyond-prompts/](special-02-beyond-prompts/) | **特別編 (俯瞰マップ)** | プロンプトの先へ — 6 層モデル |
|  2 | S1 | [special-01-work-style-reform-ai/](special-01-work-style-reform-ai/) | **特別編 (校務応用)** | 学校の働き方改革を変える生成 AI の使い方 |
|  3 | 00 | [00-evolution-of-generative-ai/](00-evolution-of-generative-ai/) | 序章 | 生成 AI の進化 (確率の子 → 推論する相棒) |
|  4 | 01 | [01-instructional-design-and-generative-ai/](01-instructional-design-and-generative-ai/) | 総論 | 授業設計 (ID) と生成 AI |
|  5 | 02 | [02-addie-analysis-teacher-self-understanding/](02-addie-analysis-teacher-self-understanding/) | Analysis | 教師の自己分析 |
|  6 | 03 | [03-addie-analysis-learner-analysis/](03-addie-analysis-learner-analysis/) | Analysis | 学習者分析 |
|  7 | 04 | [04-addie-analysis-task-analysis/](04-addie-analysis-task-analysis/) | Analysis | タスク分析 |
|  8 | 05 | [05-addie-analysis-context-analysis/](05-addie-analysis-context-analysis/) | Analysis | 環境・制約分析 |
|  9 | 06 | [06-addie-design-backward-design/](06-addie-design-backward-design/) | Design | 逆向き設計 |
| 10 | 07 | [07-addie-design-rubric-codesign/](07-addie-design-rubric-codesign/) | Design | ルーブリック共同設計 |
| 11 | 08 | [08-addie-design-lesson-structure/](08-addie-design-lesson-structure/) | Design | 授業構造 |
| 12 | 09 | [09-addie-development-material-draft/](09-addie-development-material-draft/) | Development | 教材ドラフト |
| 13 | 10 | [10-addie-development-differentiation/](10-addie-development-differentiation/) | Development | 差異化と多モダリティ |
| 14 | 11 | [11-addie-development-prompt-catalog/](11-addie-development-prompt-catalog/) | Development | プロンプトカタログ |
| 15 | 12 | [12-addie-implementation-rehearsal/](12-addie-implementation-rehearsal/) | Implementation | 授業前リハーサル |
| 16 | 13 | [13-addie-implementation-in-class-ai/](13-addie-implementation-in-class-ai/) | Implementation | 授業中の AI |
| 17 | 14 | [14-addie-evaluation-formative/](14-addie-evaluation-formative/) | Evaluation | 形成的評価 |
| 18 | 15 | [15-addie-evaluation-summative/](15-addie-evaluation-summative/) | Evaluation | 総括的評価 |
| 19 | 16 | [16-addie-evaluation-program/](16-addie-evaluation-program/) | Evaluation | プログラム評価 |
| 20 | 17 | [17-reflection-one-year-later/](17-reflection-one-year-later/) | Reflection | 1 年後のふりかえり |

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
