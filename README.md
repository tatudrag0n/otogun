# 音撃 OTOGUN — リズム×シューティング

7レーンのリズム×シューティングゲーム。タップでレーン移動＆射撃、流れてくる敵をビートに合わせて撃ち落とす。

- 収録曲（Web Audio生成、外部音源ファイルなし）
  - NEON RUNNER（128 BPM）
  - SAKURA CIRCUIT（142 BPM）
  - HYPER CORE（165 BPM）
- PERFECT／GREAT／GOOD／MISS判定、コンボ、全8ウェーブ

## プレイ

https://otogun.mct-official.com/

単一HTMLファイル（`index.html`）だけで動作します。

## 公開方法

Cloudflare Workers（static assets）で配信。`wrangler.jsonc` の routes で `otogun.mct-official.com` をカスタムドメインとして設定しています。
