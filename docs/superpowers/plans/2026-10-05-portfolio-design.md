# Portfolio Design Implementation Plan

**Goal:** 承認済みの生成り・墨色・青緑のデザインに整える。
**Architecture:** index.html のCSSとセマンティックHTMLを更新する。既存の静的配信方式を維持する。
**Tech Stack:** HTML / CSS

## Constraints
文章・リンク先・画像素材を保持する。外部依存を追加しない。

## Task 1: Visual polish
- [x] CSSを更新：最大幅1080px、本文16px、青緑アクセント、見出しの強弱、タイムライン、カード。
- [x] ヒーロー、英語ラベル、実績グリッド、フッターを追加する。
- [x] 720px以下で一列、480px以下で文字と余白を縮小する。

## Task 2: Verification
- [x] ローカルサーバーでPCと390px・320px幅を確認する。
- [x] 横はみ出し、画像読み込み、フォーカス表示を確認する。
- [x] 元のリンク先の保持と git diff --check を確認する。
- [x] design-qa.md を実際の確認結果で更新する。
