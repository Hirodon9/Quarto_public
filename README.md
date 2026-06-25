# Quarto_public

このリポジトリは Quarto で作成した公開用コンテンツです。

## 公開ページ

- Git解説ページ: https://hirodon9.github.io/Quarto_public/git.html

## ファイル構成（抜粋）

- `git.qmd`
- `git2.qmd`
- `_quarto.yml`
- `_site/`（ビルド出力）

## ローカルでのビルド

```bash
quarto render
```

ビルド後、`_site/` に HTML が出力されます。

## GitHub Pages への公開

このリポジトリでは、以下のコマンドで GitHub Pages へ公開します。

```bash
quarto publish gh-pages
```

初回公開時は、GitHub 上のリポジトリ設定で Pages の公開元が `gh-pages` ブランチになっているか確認してください。
