# スポセン管理画面 デモ（sposen-demo）

スポーツセンター スタッフ管理画面のUIデモサイトです。
Claude Designで制作したプロトタイプをGitHub Pagesで公開しています。

- **公開URL**: https://undotsushin.github.io/sposen-demo/
- **関連リポジトリ**: [bukatsu-one-demo](https://github.com/undotsushin/bukatsu-one-demo)

## 構成

```
sposen-demo/
├── index.html      # デモ本体（Claude Design HTMLエクスポート・自己完結型）
├── .nojekyll       # GitHub PagesのJekyll処理を無効化
└── README.md
```

index.html はClaude Designのバンドル形式（アセット埋め込み・JS展開型）のため、
1ファイルで完結しています。表示にはJavaScriptが必要です。

## 更新手順

1. Claude Designで修正 → HTMLエクスポート
2. エクスポートしたファイルを `index.html` にリネームしてリポジトリ直下に上書き
3. commit & push（数分でPagesに反映）

```bash
git add -A
git commit -m "update: 画面修正"
git push origin main
```

## 注意事項

- 本デモはUIプロトタイプであり、データはすべてダミーです
- 課題リスト（44件）の対応状況は別途管理
