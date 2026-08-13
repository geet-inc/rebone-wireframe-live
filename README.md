# Rebone 会員サイト ワイヤーフレーム（ライブ起点モデル）

毎週水曜のライブレッスンを起点に、翌週の1週間へ割り振る設計のワイヤーフレームです。
カレンダー機能（旧 `rebone-wireframe-calendar`）も、このリポジトリに合流させています。

https://geet-inc.github.io/rebone-wireframe-live/

| ファイル | 画面 | 一覧の番号 |
|---|---|---|
| `index.html` | 6画面の一覧 | ─ |
| `01-home.html` | ホーム（通常の日） | 01 |
| `02-home-live.html` | ホーム（ライブのある水曜） | 02 |
| `04-theme-detail.html` | テーマの中身 | 03 |
| `05-switchlab.html` | Switch Lab | 04 |
| `06-calendar.html` | きろく（カレンダー） | 05 |
| `07-share.html` | ダウンロード（SNS投稿用の画像） | 06 |

- `03-themes.html`（これまでのテーマ）は削除しました。ホームからの導線は `04-theme-detail.html` に付け替えています。
- ファイル名は要件定義ノートと合わせるため、削除・合流のあとも変えていません。一覧の表示番号だけを 01〜06 に振り直しています。
- ボトムナビの4つ目は、確定している5タブ構成に合わせて全画面「きろく」で統一しています（カレンダー側の「カレンダー」表記から変更）。タブ名の改称は未確定の論点です。

前回提案（Rebuild 方式）のワイヤーは別リポジトリです。
https://geet-inc.github.io/rebone-wireframe/

**このフォルダには、公開してよい HTML・CSS 以外を置かないこと。**

株式会社Geet
