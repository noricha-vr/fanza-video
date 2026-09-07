# FANZA Video Player Wide

FANZA月額動画の作品詳細ページでサイドカラム（タブ・レビュー・作品情報）を非表示にし、動画プレイヤーを大きく表示する Chrome 拡張。

## インストール

1. chrome://extensions を開く
2. デベロッパーモードを ON
3. 「パッケージ化されていない拡張機能を読み込む」で `hide-side-column-extension` ディレクトリを選択

## 対象URL

作品詳細ページのみ: `https://www.dmm.co.jp/monthly/*/-/detail/*`

## 構成

- `hide-side-column-extension/manifest.json` — Manifest V3
- `hide-side-column-extension/hide.css` — `.side-column` を非表示にするCSS
