# BUG HUNTER

基礎プログラミングII 前期理解度試験の対策サイト。
C言語のバグを撃ち抜くゲームで、構造体・動的メモリ・ファイル操作・GitHub を復習します。

**▶ [遊ぶ](https://goldfishstar0055.github.io/kisopuro-test/)**

---

## 2つのモード

| モード | 内容 |
|---|---|
| 🎯 バグハンター | コードの中から壊れている1行をクリックで撃ち抜く。全18問・残機3。試験の第3問（30点）と同じ作業 |
| ⏱ タイムアタック | 90秒で何問答えられるか。連続正解でスコア倍率アップ、誤答は3秒ペナルティ。全40問からシャッフル |

どちらもプレイ後に「取りこぼしたトピック」が集計され、どこを復習すればいいかが出ます。
ハイスコアはブラウザに保存されます。

## 出題範囲

第2〜13回（構造体・GitHub・malloc/free・ファイル操作）

- **構造体** … struct / typedef / `.` と `->` / strcpy / 初期化順 / ポインタ渡し
- **動的メモリ** … malloc / free / realloc / メモリリーク・二重free・ダングリング
- **ファイル操作** … fopen の3モード / NULLチェック / fprintf / fgets + sscanf / fclose
- **GitHub** … add / commit / push / Fork / clone / Pull Request

## 操作

| キー | 動作 |
|---|---|
| `1` 〜 `4` | 選択肢を選ぶ（タイムアタック） |
| `Enter` | 次へ進む（バグハンター） |

マウス操作だけでも遊べます。

## 技術メモ

- 単一の `index.html`（HTML + CSS + JavaScript）。ビルド不要
- 外部依存はフォント（Google Fonts の DotGothic16）のみ
- ハイスコアは `localStorage` に保存
- パレットは [Sweetie 16](https://lospec.com/palette-list/sweetie-16)

## ライセンス

学習用。自由に fork して使ってください。
