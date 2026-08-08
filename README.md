# syam-develop.github.io

個人開発アプリ(100apps)のサポートページ・プライバシーポリシー置き場。
GitHub Pages で https://syam-develop.github.io/ から配信される。

## 構成

アプリごとに小文字のフォルダを切り、その中に `privacy.html` を置く。

```
index.html                  … アプリ一覧(新アプリ追加時にリンクを足す)
<app-id>/privacy.html       … 各アプリのプライバシーポリシー
```

| アプリ | ポリシー URL |
|---|---|
| 卒煙記録 | https://syam-develop.github.io/quitsmoke/privacy.html |

## 新しいアプリを追加するとき

1. `cp -r quitsmoke <new-app-id>` して `privacy.html` の内容を書き換える
   (デザインは全アプリ共通。アクセントカラーだけアプリに合わせて変えてよい)
2. `index.html` の一覧にカードを1枚追加する
3. main に push すれば数十秒〜数分で公開される
