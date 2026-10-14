# 📚 開発ルール (Development Rules)

開発に関する規約をまとめたリポジトリ。まずは下記の一覧から該当する規約を確認する。

## 規約一覧

| ファイル                                 | 概要                                                   |
| :--------------------------------------- | :----------------------------------------------------- |
| [ISSUE.md](./ISSUE.md)                   | Issueの作成ルール、テンプレート、ラベル運用            |
| [BRANCHING.md](./BRANCHING.md)           | ブランチ戦略、命名規則、接頭辞の種類                   |
| [COMMIT-MESSAGE.md](./COMMIT-MESSAGE.md) | コミットメッセージの書式、Gitコマンドのルール          |
| [PR.md](./PR.md)                         | プルリクエストの作成ルール、テンプレート、マージ方式   |
| [CODING-STYLE.md](./CODING-STYLE.md)     | 命名、実装、エラーハンドリング、型安全性、セキュリティ |
| [AI-GUIDELINES.md](./AI-GUIDELINES.md)   | AIアシスタント利用時の権限・安全ルール                 |

## 基本フロー

1. **Issue を作成する** → [ISSUE.md](./ISSUE.md)
2. **作業ブランチを切る** → [BRANCHING.md](./BRANCHING.md)
3. **コーディングする** → [CODING-STYLE.md](./CODING-STYLE.md)
   - AIアシスタントを使う場合は [AI-GUIDELINES.md](./AI-GUIDELINES.md) に従う
4. **コミットする** → [COMMIT-MESSAGE.md](./COMMIT-MESSAGE.md)
5. **PR を作成してレビュー・マージする** → [PR.md](./PR.md)
   - PR本文に `Closes #Issue番号` を記載し、マージ時にIssueを自動クローズする
6. **作業ブランチを削除する** → [BRANCHING.md](./BRANCHING.md)
