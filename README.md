# walkingwifi ポートフォリオ

添付デザインを再現した静的サイトです。ビルドやnpmのインストールは不要です。

## ローカル表示

```sh
python3 -m http.server 4173
```

http://localhost:4173/ を開いてください。

## Cloudflare Pages

Git連携の場合、このリポジトリを選び、以下を指定します。

- フレームワーク: None
- ビルドコマンド: `exit 0`
- ビルド出力ディレクトリ: `.`（リポジトリのルート）

Direct Uploadの場合は、`index.html`、`styles.css`、`assets/` を同じフォルダに入れて、そのフォルダをアップロードしてください。公開に必要なのはこの3つのみです。

## 編集

文章・リンクは `index.html`、スタイルは `styles.css` にあります。プロジェクトと外部リンクにはユーザー指定のURLを設定しています。

## 素材

技術ロゴ: [Devicon](https://github.com/devicons/devicon)（MIT、各ロゴは各社の商標）
外部リンクアイコン: [Tabler Icons](https://github.com/tabler/tabler-icons)（MIT）

ライセンス原文は `assets/devicon-LICENSE.txt` と `assets/tabler-LICENSE.txt` に保存しています。
