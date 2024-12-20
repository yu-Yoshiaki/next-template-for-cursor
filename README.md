# Cursor Driven Project Manager, Next.js.

Cursor エディタを活用した統合開発管理プロジェクトです。要件定義から実装まで、開発のライフサイクル全体を一元的に管理します。

## 主な機能

- 📝 要件管理

  - `/docs`ディレクトリで要件定義や設計ドキュメントを一元管理
  - 要件とコードの整合性を自動チェック

- 🧪 テスト駆動開発

  - テストファーストな開発アプローチ
  - `/tests`ディレクトリでテストケースを体系的に管理
  - ユニットテスト、統合テスト、E2E テストの実装

- 📋 タスク管理

  - `/tasks/todo`ディレクトリでタスクを管理
  - 進捗状況の可視化と追跡

- 🛠 開発ルール
  - `.cursorrules`でプロジェクト固有の開発ルールを定義
  - コーディング規約の自動適用

## プロジェクト構成

├── docs/ # プロジェクトドキュメント
│ ├── API.md # API 仕様
│ ├── ARCHITECTURE.md # アーキテクチャ設計
│ ├── DATABASE.md # データベース設計
│ └── ...
├── tasks/ # タスク管理
│ └── todo/ # 未完了タスク
├── tests/ # テストコード
├── .cursorrules # Cursor エディタ設定
└── README.md # プロジェクト概要

## 始め方

1. このリポジトリをクローン
2. Cursor エディタでプロジェクトを開く
3. `/docs`内のドキュメントをプロジェクトに合うように編集
4. `.cursorrules`の設定を確認

## 開発フロー

1. 要件定義 (`/docs`に記載)
2. テストケース作成 (`/tests`に配置)
3. 実装
4. タスク管理 (`/tasks/todo`で管理)

## 貢献について

プロジェクトへの貢献方法については[CONTRIBUTING.md](docs/CONTRIBUTING.md)を参照してください。

## ライセンス

[MIT ライセンス](LICENSE)の下で公開されています。
