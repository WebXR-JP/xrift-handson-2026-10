# XRift ハンズオン 2026年10月 資料

前回の [XRift ハンズオン資料](https://webxr-jp.github.io/xrift-handson-2026-04/) を参考にした Slidev 資料です。まずは事前準備のスライドを公開できる状態にしています。開催日時や当日の制作内容は確定後に追加します。

## 事前準備

[slides.md](./slides.md) を参照してください。VS Code、Node.js、XRift CLI、XRift アカウントの準備からログイン確認まで説明しています。

## 編集・確認

Node.js をインストールした後、次を実行します。

```bash
npm install
npm run dev
```

資料は `slides.md`、共通の見た目は `style.css` を編集します。公開用のビルドは `npm run build` で確認できます。

## 公開

`main` への push で GitHub Pages にデプロイするワークフローを用意しています。GitHub の **Settings → Pages → Build and deployment → Source** を **GitHub Actions** に設定してください。リポジトリの公開設定や Pages の利用条件によっては、追加の設定が必要です。公開先は `https://webxr-jp.github.io/xrift-handson-2026-10/` を想定しています。
