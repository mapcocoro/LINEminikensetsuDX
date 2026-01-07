# CLAUDE.md

このファイルはClaude Codeがこのリポジトリで作業する際のガイダンスを提供します。

## プロジェクト概要

建設・設備業向けのLINE LIFFデモアプリ。1/15の展示会でのチラシ配布用に作成。

## 技術構成

- **フレームワーク**: なし（Vanilla JS）
- **CSS**: Tailwind CSS (CDN)
- **LIFF SDK**: LINE Front-end Framework
- **ホスティング**: GitHub Pages

## ファイル構成

単一ファイル構成:
- `index.html` - 全画面・スタイル・ロジックを含む

## 画面構成

1. `screen-top` - トップ画面
2. `screen-input` - 入力フォーム画面
3. `screen-complete` - 完了画面
4. `screen-works` - 施工事例画面
5. `screen-about` - 会社情報画面

URLパラメータ `?page=works` または `?page=about` で初期画面を切り替え可能。

## LIFF設定

```javascript
const LIFF_ID = '2008841488-GtLX9MDH';
```

## デザインカラー

- Primary: `#1e3a8a` (紺色)
- Accent: `#f97316` (オレンジ)

## デプロイ

GitHub Pagesで自動デプロイ。mainブランチへのpushで更新される。

公開URL: https://mapcocoro.github.io/LINEminikensetsuDX/

## 注意点

- デモ用のため実際のデータ送信は行わない
- 施工事例の写真はUnsplashから取得
- 会社情報はダミーデータ
