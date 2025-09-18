# プロジェクト構造

<!-- プロジェクトのディレクトリやファイルの構造を記述します -->

## ディレクトリ構成

```
.spec/
├── scripts/
│   └── task-create.sh          # タスク作成スクリプト
├── template/
│   ├── kanban.md               # カンバンテンプレート
│   ├── requirements.md         # 要求定義書テンプレート
│   ├── spec.md                 # 機能仕様書テンプレート
│   └── task.md                 # タスクテンプレート
├── work/
│   ├── common/
│   │   ├── develop-policy.md   # 開発ポリシー
│   │   ├── project-structure.md # プロジェクト構造（このファイル）
│   │   ├── spec-policy.md      # 仕様ポリシー
│   │   ├── teckstack.md        # 技術スタック
│   │   └── testing.md          # テスト方針
│   └── phase-00001/
│       ├── requirements.md     # フェーズ1要求定義書
│       ├── spec.md            # フェーズ1機能仕様書
│       └── tasks/
│           ├── 001-addition-integer.md    # 整数の足し算機能実装タスク
│           ├── 002-addition-decimal.md    # 小数の足し算機能実装タスク
│           ├── 003-subtraction-integer.md # 整数の引き算機能実装タスク
│           ├── 004-subtraction-decimal.md # 小数の引き算機能実装タスク
│           └── 005-display-results.md    # 計算結果表示機能実装タスク
src/
├── math/
│   ├── addition.js            # 足し算機能実装
│   └── subtraction.js         # 引き算機能実装
└── display/
    └── results.js             # 結果表示機能実装
```

## タスクファイル一覧

### Phase-00001: 基本計算機能実装

| タスク番号 | ファイル名 | 説明 | 優先度 | ステータス |
|------------|------------|------|--------|-----------|
| 001 | 001-addition-integer.md | 整数の足し算機能実装 | P0 | Backlog |
| 002 | 002-addition-decimal.md | 小数の足し算機能実装 | P1 | Backlog |
| 003 | 003-subtraction-integer.md | 整数の引き算機能実装 | P0 | Backlog |
| 004 | 004-subtraction-decimal.md | 小数の引き算機能実装 | P1 | Backlog |
| 005 | 005-display-results.md | 計算結果表示機能実装 | P2 | Backlog |