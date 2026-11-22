# P5X攻略手帖

ペルソナ5: The Phantom X（日本版）の自分用攻略メモ。静的サイト（ビルドなし）で GitHub Pages に公開。

- 公開: https://ykdtmnhnddsbba-jj.github.io/p5x-techo/
- `index.html` … 画面（タブ: いまの結論 / シナジー / 今後のキャラ / Tier・ガチャ / 資料）
- `data/p5x.json` … 中身のデータ。更新はこのファイルだけ直せばよい
- チェック・石メモ・表示テーマはブラウザの localStorage（キー `p5x.v1`）に保存

## データの足し方
- シナジーを追加: `synergies` に1件足す（`ranks` は [ランク, 正解, ほかの選択肢]、`dates` は [場所, 正解, もう一方]）
- ガチャ更新: `current`（開催中）・`upcoming`（予想）・`verdict`（結論）・`updated`（日付）を直す
- 予想・未確認の情報は必ずそう書く
