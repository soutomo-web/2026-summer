# [機能名] 仕様書

## 1. 概要 (Why/What)
- **目的:** この機能が解決する課題や目的を簡潔に記述。
- **ターゲット:** 誰のための機能か。

## 2. 関連ドキュメント
- [ ] 関連するADR (技術的決定): `docs/ADR/xxxx.md`
- [ ] 関連するIssue/PR: (GitHubのリンク)

## 3. 画面イメージ
![ロゴ](https://smt.docomo.ne.jp/dmenu/img/top_logo_gray.png)

## 4. ロジックフロー (Mermaid)
※システムの処理フローや条件分岐をここに記述してください。AIはこの図を読み取って実装を行います。

```mermaid
graph TD
    User[ユーザー] -->|操作| Frontend[フロントエンド]
    Frontend -->|APIリクエスト| Backend[バックエンド]
    Backend -->|判定| Decision{条件分岐}
    Decision -->|Yes| Action1[処理A]
    Decision -->|No| Action2[処理B]


