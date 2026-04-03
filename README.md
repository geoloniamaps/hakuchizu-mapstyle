# hakuchizu-mapstyle

子供向け白地図マップスタイル。

## スタイル一覧

| スタイル | 説明 | ファイル |
|---------|------|---------|
| ラベルあり | 国名・都道府県名・市区町村名あり | `style.json` |
| 国名のみ | 都道府県名・市区町村名なし | `style-nolabel.json` |
| テキストなし | すべてのラベルなし | `style-notext.json` |

## 開発

```bash
npm install
npm start        # 開発サーバー起動
npm run build    # docs/ にビルド
```

## ソース構成

- `style.yml` / `style-nolabel.yml` / `style-notext.yml` — スタイル定義（YAML）
- `layers/` — レイヤー定義ファイル
- `docs/` — ビルド出力・プレビューページ
