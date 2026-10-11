# billiards-ar

WebXR で机や床にビリヤード台を置いて遊べる、2人対戦のビリヤードゲームです。エイトボールとナインボールに対応しています。

## 遊び方

- `index.html` … AR版。Android の Chrome で開き、「ARで遊ぶ」から平らな面をタップして台を置きます。AR 非対応の端末では「3D表示で遊ぶ」が使えます。
- `2d.html` … 上から見下ろす2D版。どのブラウザでも遊べます。

**操作**：台をタップ／ドラッグして狙い、下のバーを横に引いて離すとショット。PC では矢印キーで微調整、スペース長押しでも打てます。

## 公開

WebXR は HTTPS が必要です。GitHub Pages（Settings → Pages → Branch: `main` / `root`）で公開すると、`https://<ユーザー名>.github.io/billiards-ar/` で遊べます。

ライブラリは three.js 0.160.0（unpkg から読み込み）を使っています。ビルド不要の単体 HTML です。
