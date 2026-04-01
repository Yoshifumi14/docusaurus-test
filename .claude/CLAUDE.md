# CLAUDE.md

## プロジェクト概要

[会社名・チーム名] のデザインプリンシプルを言語化・公開するための Docusaurus 製ドキュメントサイト。

## 技術スタック

- **フレームワーク**: Docusaurus v3.8.1
- **言語**: TypeScript / MDX
- **ホスティング**: GitHub Pages
- **デプロイ**: GitHub Actions（main ブランチへの push で自動）

## ディレクトリ構成

```txt
docs/          # コンテンツ（Markdown / MDX）
src/           # カスタムコンポーネント（React / TypeScript）
static/        # 静的アセット（画像など）
.github/       # GitHub Actions ワークフロー
.claude/       # Claude Code 設定
  plans/       # 実装プラン（ローカルのみ・Git 管理外）
```
