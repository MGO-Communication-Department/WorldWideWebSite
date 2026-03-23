# WorldWideWebSite

みりおが逓信部サイトを、Wayback上の情報を基に GitHub Pages + Pages CMS で再現した構成です。

## 構成

- `index.md`: トップページ
- `blog/index.html`: ブログ一覧
- `_posts/`: 記事データ
- `_data/home.yml`: トップページ文言・セクション文言
- `_layouts/`: レイアウト
- `assets/css/site.css`: スタイル
- `.pages.yml`: Pages CMS の編集定義

## Pages CMS で編集する項目

- Home (`_data/home.yml`)
	- ヒーロータイトル
	- ヒーロー本文
	- 各紹介カード
	- メイン画像URL
- Blog Posts (`_posts/*.md`)
	- タイトル、日付、著者、カテゴリ、抜粋、本文

## 備考

現行の `https://mgoteishin.org/` は差し替わっており、再現は主に Wayback の取得結果を基準にしています。
本文の一部は取得可能な抜粋を元に補完しています。