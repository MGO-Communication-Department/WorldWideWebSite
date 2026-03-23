# WorldWideWebSite

みりおが逓信部サイトを Hugo + Docsy で構築するリポジトリです。
トップページは Wayback で確認できる過去サイトの文言を参考に再構成し、
各詳細ページは「工事中」プレースホルダーを配置しています。

## 使用技術

- Hugo
- Docsy theme

## 構成

- `hugo.toml`: Hugo 設定（Docsy テーマ、メニュー、言語設定）
- `content/_index.md`: TOPページ
- `content/about.md`: 逓信部とは（工事中）
- `content/join.md`: 入部方法（工事中）
- `content/activities.md`: 活動紹介（工事中）
- `content/blog/_index.md`: ブログ一覧ページ
- `content/blog/*.md`: ブログ記事
- `CNAME`: カスタムドメイン設定

## セットアップ

1. Hugo Extended をインストール
2. Go をインストール（Hugo Modules で Docsy を取得するため）
3. 依存モジュールを取得

```bash
hugo mod get github.com/google/docsy
hugo mod get github.com/FortAwesome/Font-Awesome
```

4. ローカル起動

```bash
hugo server
```

## 備考

- 旧 Jekyll / Pages CMS 用ファイルは削除済みです。
- Wayback 参照内容をもとに、TOP の文言とお知らせ導線を再構成しています。