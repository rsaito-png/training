# ストレスチェック実施者養成研修（受講者向けページ）

公開先: https://training.psr-seishinkai.org/ （GitHub Pages、CNAME）

- `index.html` と `sct.html` は同じ内容（Square決済後や旧リンクの `/sct.html` でも開けるように）。
- `sct_logic.js` / `sct_cert.js` / `pc-scale.js` は rsaito-png/portal からの写し。運営画面（portal の `#sct`）と同じ計算を使うため、portal 側を直したら `portal/tools/sync_training.sh` でこちらへ写す。
- 職員ポータル（https://rsaito-png.github.io/portal/）は別リポジトリのまま。旧URL `portal/sct.html` はこのページへ転送。
- 運用マニュアル（sct-ops.html）は職員向けなので portal に残す。
