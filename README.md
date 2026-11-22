# AI BLOG STUDIO LP

AI記事生成ツールの紹介用ランディングページです。GitHub Pagesにそのまま公開できる静的サイトです。

## ファイル
- `index.html`: LPの本文と各セクション
- `style.css`: PC/スマホのレイアウト、アニメーション
- `script.js`: メニュー、スクロール表示、生成手順のデモ
- `assets/`: LP内のデモブログ紹介用画像

## 公開方法
リポジトリのルートに `index.html` が来るよう全ファイル・フォルダをアップロードし、GitHubの Settings > Pages から main / (root) を選択します。

## デモブログのURL
`index.html` 内の `https://syucoltd202603-arch.github.io/syudemosite/` を変更すれば各社向けLPとして再利用できます。

## アニメーション
背景の光る波はCSSでアニメーションするSVGです。記事生成中の星、プログレスバー、カードのホバー、スクロール表示にも動きがあります。`prefers-reduced-motion` を尊重します。

## 注意
記事生成の3ステップ部分は説明用の演出で、AI APIには接続していません。デモサイトは別のGitHub Pagesサイトへのリンクです。外部ページのiframe表示は相手側のセキュリティ設定によって制限される場合があります。画像はLP用の生成風景素材です。
