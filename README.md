# dokoiko-legal

iOS アプリ「Whimo」のプライバシーポリシーと利用規約を GitHub Pages で公開するための公開リポジトリ。

公開ページ: https://tomokazukozuma.github.io/dokoiko-legal/

## 含まれるもの

- `privacy.md` — プライバシーポリシー（日本語・正文）
- `terms.md` — 利用規約（日本語・正文）
- `index.md` — ランディング
- `en/privacy.md` — Privacy Policy（英語・参考訳、`/en/privacy`）
- `en/terms.md` — Terms of Service（英語・参考訳、`/en/terms`）
- `en/index.md` — 英語ランディング（`/en/`）
- `_config.yml` — Jekyll 設定 (`jekyll-theme-cayman` + 拡張子なし permalink)

英語版は front matter の `permalink` で URL を明示している（`_config.yml` の `permalink: /:basename` はディレクトリを無視してファイル名だけで URL を作るため、指定しないと日本語版と衝突する）。

内容を変更する場合は日英両方を更新すること。相違がある場合は日本語版が優先する旨を各文書に明記している。

## 編集

各 Markdown を直接編集して push すると数十秒〜数分で公開ページに反映される。
