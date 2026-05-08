# noeva-site

noeva のサポートサイト。GitHub Pages で配信。

## 構成

- `index.html` — サポートトップ
- `terms.html` — 利用規約
- `privacy.html` — プライバシーポリシー
- `tokushoho.html` — 特定商取引法に基づく表記
- `contact.html` — お問い合わせ
- `app_icon.png` / `favicon.png` — noeva アプリアイコン

## デプロイ

GitHub の `Settings > Pages` で `main` ブランチをソースに選択するだけで配信されます。
クリーン URL (`/terms` で `terms.html` を返す) は GitHub Pages の既定挙動で動作します。

## 編集時の注意

- すべてのページに `<meta name="robots" content="noindex">` を入れているため、検索エンジンには載りません。公開を始める段階で削除してください。
- `contact.html` の Instagram / X のアカウント名はプレースホルダ (`@noeva_app`)。実際のアカウント取得後に差し替えてください。
- 各ページの「制定」日付や `&copy; 2026 noeva` の表記は、変更時に更新してください。
