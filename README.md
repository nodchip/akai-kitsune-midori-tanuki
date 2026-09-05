# 赤いきつねに転生したオレと、緑のたぬきに転生したボク

食品擬人化×異世界転生×宿命のライバル×B級グルメ勇者譚。カクヨムへの投稿を目指す執筆用フォルダです。

## フォルダ構成

```text
README.md                 この案内・執筆の進め方
AGENTS.md                 執筆後のレビュースキルへの案内
.agents/skills/
  episode-review-fix-loop/SKILL.md  Luna によるレビュー・修正ループ
planning/                 作者用の資料（ネタバレを含む）
  concept.md              作品の軸・テーマ・決め台詞
  characters.md           登場人物・能力・弱点
  world.md                国家・信仰・出汁術
  outline.md              三部構成と全10話の構成案
  open-questions.md       執筆前に決める事項
  continuity.md           伏線・時系列・状態の管理
  progress.md             各話の執筆・推敲・公開状況
  reviews/NN.md           各話のレビュー記録（実施時に作成）
manuscript/               カクヨムに貼り付ける本文の正本
  01.txt ～ 10.txt         1話1ファイル（現在は空）
publishing/               投稿欄に入れる情報と確認手順
  work.md                 作品タイトル・紹介文・タグの案
  format.md               本文の書式・カクヨム記法
  checklist.md            推敲・投稿前後の確認
templates/
  episode-plan.md         必要になった話に使う詳細プロット雛形
```

## 資料の扱い

- `concept.md`、`characters.md`、`world.md` は、提示された設定を整理したものです。
- `outline.md` の各話の出来事・視点・引き、紹介文、執筆書式は初期案です。確定設定とは区別して扱います。
- 未指定の仕組みは `open-questions.md` に残しています。本文を書く際に、未決事項を既定の設定として扱わないでください。
- 本文は未執筆です。空の `.txt` は原稿の置き場所であり、完成原稿ではありません。

## 執筆の進め方

1. 設定資料と `planning/open-questions.md` を読み、その話に必要な事項を決めます。
2. `planning/outline.md` を確認します。詳細化が必要なら雛形を `planning/episode-01.md` などへコピーします。
3. 対応する `manuscript/NN.txt` に本文だけを書きます。話数・タイトルは `planning/progress.md` で管理します。
4. [episode-review-fix-loop](.agents/skills/episode-review-fix-loop/SKILL.md) で Luna のレビューと本文修正を指摘ゼロまで繰り返します。設定変更や伏線を資料に反映し、実施記録を `planning/reviews/NN.md` に残して進捗を更新します。
5. `publishing/checklist.md` に沿って確認し、カクヨムのタイトル欄と本文欄へ別々に入力します。
6. 公開後、公開日時・URLを進捗表に記録します。投稿画面で本文を修正した場合も正本に反映します。

ファイルは UTF-8 で保存します。本文の別コピーは常設せず、改稿履歴は必要に応じて Git で管理します。公開日・総文字数・各話の長さは未定です。本構成の作成には、本文の執筆、コミット、サイトへの投稿は含みません。
