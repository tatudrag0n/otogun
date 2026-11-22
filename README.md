# 音撃 OTOGUN — リズム×シューティング

7レーンのリズム×シューティングゲーム。タップでレーン移動＆射撃、流れてくる敵をビートに合わせて撃ち落とす。

- 収録曲（パブリックドメインのクラシックをWeb Audioで演奏、外部音源ファイルなし）
  - CANON（パッヘルベルのカノン、120 BPM）
  - ODE TO JOY（ベートーヴェン「歓喜の歌」、132 BPM）
  - FATE（ベートーヴェン交響曲第5番「運命」、165 BPM）
- PERFECT／GREAT／GOOD／MISS判定、コンボ、全8ウェーブ
- シューティング要素：HP制の敵（通常は1発、大型のみ5〜6発で撃破、リズムと関係なく連射で攻撃）が出現し、敵弾を撃ってくる。敵弾は避けるか撃ち落として迎撃でき、敵が判定ラインに到達すると大ダメージ

## プレイ

https://otogun.mct-official.com/

単一HTMLファイル（`index.html`）だけで動作します。

## 公開方法

Cloudflare Workers（static assets）で配信。`wrangler.jsonc` の routes で `otogun.mct-official.com` をカスタムドメインとして設定しています。
