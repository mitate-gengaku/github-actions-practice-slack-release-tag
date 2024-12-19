# Github Actionsの練習用リポジトリ
Github Actionsを使用してコードのチェック、テストを行い、その結果をSlackに通知する

```shell ディレクトリ構造
.
├─ .github
│  ├─ actions
│  │  └─ setup
│  │     └─ action.yml
│  ├─ ISSUE_TEMPLATE
│  ├─ workflows
│  │  ├─ code-check.yml
│  │  └─ release-note.yml
│  └─ release-drafter.yml
├─ app
├─ api
└─ infra
```

## branchルール
1. main
リリース用

2. dev
開発環境

3. feat
新規機能開発用

4. fix
タイポの修正・コードのリファクタリングをひとまとめに行う

5. docs
ドキュメント関連用

## commitルール
1. chore
ライブラリのインストール

2. feat
新しい機能の追加

3. fix
タイポやコードの修正

4. add
新しいコードの追加

5. remove
既存のコード等の削除
