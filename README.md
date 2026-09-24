# XRift ハンズオン 2026年10月 資料

前回の [XRift ハンズオン資料](https://webxr-jp.github.io/xrift-handson-2026-04/) の配色とスライド形式を参考にした、XRift Studioでワールドを作るハンズオン資料です。開催日時など未確定の情報は入れていません。

## 参加者向け

[スライド](./slides.md)は、XRiftアカウントの作成、XRift Studioのインストールとログイン、最初のワールドを開いて動かすところまで案内します。参加者がVS CodeやNode.js、XRift CLIを個別に入れる手順はありません。制作に必要なツールはStudioの初回セットアップが用意します。

XRift Studioは有志製のアプリです。操作の詳細は[公式リポジトリのガイド](https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/index.md)も参照してください。

## 資料の編集・確認

資料の編集者はNode.jsを用意し、次を実行します。

```bash
npm install
npm run dev
```

資料は `slides.md`、共通の見た目は `style.css` にあります。公開用のビルドは `npm run build` で確認できます。

## 公開

`main` へのpushでGitHub Pagesにデプロイするワークフローを用意しています。GitHubの **Settings → Pages → Build and deployment → Source** を **GitHub Actions** に設定してください。リポジトリの公開設定やPagesの利用条件によっては追加の設定が必要です。公開先は `https://webxr-jp.github.io/xrift-handson-2026-10/` を想定しています。
