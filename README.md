# testpages

GitHub Pages で公開する制作物置き場。

## フォルダ構成

```
/
├── index.html                         … トップ（プロジェクト一覧）
├── .nojekyll                          … Jekyll処理を無効化（静的HTMLをそのまま配信）
└── projects/
    └── 名古屋市学生社会課題解決プロジェクト/
        ├── index.html                 … プロジェクト内の制作物一覧
        └── koekake-memory-test/
            └── index.html             … 記憶と声かけのテスト
```

新しい制作物は `projects/<プロジェクト名>/<制作物名>/index.html` に置き、
一つ上の `index.html` の一覧にリンクを追加する。
