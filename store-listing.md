# Chrome Web Store 掲載情報

## 基本情報

- 名前: FANZA Video Player Wide
- 概要（132字以内）: FANZA月額動画の作品詳細ページでサイドカラムを非表示にし、動画プレイヤーを大きく表示します。
- カテゴリ: エンターテイメント（仕事効率化でも可）
- 言語: 日本語
- 成人向けコンテンツ: 「アダルトコンテンツを含む / 対象とする」フラグを ON にする

## 詳細説明

FANZA月額動画（見放題ch など）の作品詳細ページで、右側のサイドカラム（ストリーミング/ダウンロード/レビュー/対応デバイスのタブ、作品情報）を非表示にします。これによりメインカラムが広がり、動画プレイヤーを大きく表示できます。

- 動作ページ: https://www.dmm.co.jp/monthly/*/-/detail/* （作品詳細ページのみ）
- CSS を1行注入するだけの軽量な拡張です
- データの収集・送信は一切行いません

## プライバシー

- 権限: なし（content_scripts の CSS 注入のみ、host は dmm.co.jp の作品詳細ページ限定）
- ユーザーデータの収集・利用・共有: なし
- プライバシーポリシー欄には本リポジトリ README の URL を記載可: https://github.com/noricha-vr/fanza-video

## 提出手順

1. https://chrome.google.com/webstore/devconsole で開発者登録（初回 $5）
2. GitHub Release の zip（fanza-video-player-wide-1.1.zip）をアップロード
3. スクリーンショット 1280x800 を最低1枚（適用前後の比較推奨）
4. 成人向けフラグ ON、データ収集なしを申告して審査へ
