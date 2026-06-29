# セレンディップ工場診断LP

セレンディップ・ロボクロス株式会社「工場診断サービス」への送客キャンペーンLP。
本体HPとは独立した単一ページの静的サイト（HTML/CSS/JS を `index.html` に内蔵）。

## 構成
- `index.html` … LP本体（9セクション。濃紺×ゴールドの硬派トーン）
- `images/` … 使用画像（工場写真・レポート画像など、Web用JPG）

## 公開（Vercel）
- このリポジトリを Vercel に Import すると、`index.html` がそのまま配信される（ビルド不要・Root Directory = リポジトリ直下）。
- `main` ブランチへの push で自動デプロイ。
- 本番ドメイン予定：`lp.serendip-rxm.com`（サブドメインのDNS設定が必要）。

## 申込み導線
- 各CTAは既存の問い合わせフォーム `https://www.serendip-rxm.com/inquiry/` にリンク（フォーム自体は本体HP側。HubSpot連携・GTM計測はそちらで稼働）。
