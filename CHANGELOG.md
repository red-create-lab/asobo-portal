# Asobo AB ポータルサイト CHANGELOG

## v1.2 (2026-10-01)
- 請求書ジェネレーターをローカルファイル埋め込みから、公開URL（https://red-create-lab.github.io/invoice-generator/）へのリンク/iframeに変更
- リポジトリ内のローカル版`invoice-generator.html`を削除
- これで両ツールとも本家リポジトリ更新がそのままポータルに反映される構成に統一

## v1.1 (2026-10-01)
- トーナメントビルダーをローカルファイル埋め込みから、公開URL（https://red-create-lab.github.io/tournament-builder/）へのリンク/iframeに変更
- 本家側の更新がそのまま反映されるため、ポータル側へのファイル再コピーが不要に
- リポジトリ内の乖離していたローカル版`tournament-builder.html`を削除

## v1.0 (2026-10-01)
- 初回リリース
- サイドバーメニュー構成（ホーム／トーナメントビルダー／請求書ジェネレーター）
- 各ツールをiframeで読み込み、別タブで開くボタンも設置
- ロゴをAsobo ABのロゴ画像に設定（背景透過済み）
