# CrossPieces Arena — 公式Webページ

CrossPieces Arena（クロスピースアリーナ）の公式ドキュメントサイトです。GitHub Pages（`main` ブランチのルート）から公開しています。

## 公開ページ

- **トップページ:** https://wttk05.github.io/CrossPiecesArena/
- **遊び方・ルール:** https://wttk05.github.io/CrossPiecesArena/rules/
- **パッチノート:** https://wttk05.github.io/CrossPiecesArena/rules/#patch-notes
- **プライバシーポリシー:** https://wttk05.github.io/CrossPiecesArena/privacy/
- **利用規約:** https://wttk05.github.io/CrossPiecesArena/terms/

## 構成

- `index.html` — 公式ポータル（ページ内言語切替・各ページおよびSteamストアへの案内）
- `rules/index.html` — 遊び方・ルール（画像・CSS・JavaScriptを含む単体HTML）とパッチノート表示
- `rules/patch-notes.md` — パッチノート本体（Markdown）
- `privacy/index.html` — プライバシーポリシー（ページ内言語切替・ゲーム内 `UI.csv` 2026-10-28版と同期）
- `terms/index.html` — 利用規約（ページ内言語切替・ゲーム内 `UI.csv` 2026-10-28版と同期）

## パッチノートの更新方法

パッチノートの中身は `rules/patch-notes.md` だけで管理します。`rules/index.html` を編集する必要はありません。

1. `rules/patch-notes.md` のいちばん上（書き方のコメントのすぐ下）に、新しい版を足します。
2. `main` へ push すると、数分で公開ページの「パッチノート」タブに反映されます。

```markdown
## 1.0.0 - 2026-12-11

正式リリース版です。

### ゲーム全般

- 遊んで分かる変更（画面・操作・演出・オンライン・不具合の修正）を書きます。

### 駒

- **駒や効果の名前**：駒の動き・効果・説明の変更を書きます。
```

- 見出しは「`## 版 - 日付 - ラベル`」です。日付は `YYYY-MM-DD`、ラベル（Playtest など）は省けます。
- 版は数字で始めます。各版には `#v1.0.0` のようなリンクが付きます。
- 分類は「ゲーム全般」と「駒」の 2 つです。細かい内部の処理は書きません。
- いちばん上の版に「最新」の印が付きます。新しい版を必ず上に書いてください。
