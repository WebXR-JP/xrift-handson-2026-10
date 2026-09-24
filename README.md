# XRift ハンズオン 2026年10月 資料

前回の [XRift ハンズオン資料](https://webxr-jp.github.io/xrift-handson-2026-04/) の配色とスライド形式を参考にした、XRift Studioで3Dワールドを作る資料です。

## 内容

[スライド](./slides.md)では、XRiftアカウントの作成とStudioへのログインから始め、空のワールドに小道・ベンチ・目印を置きます。色をつけ、Playで歩き、保存を確認したら完成です。最後にXRiftへ公開する手順も紹介します。

参加者の制作はXRift Studio内で進められます。操作で迷ったら[XRift Studioの使い方](https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/index.md)も参照してください。

## 資料の編集・確認

資料の編集にはNode.jsが必要です。

```bash
npm install
npm run dev
```

スライドは `slides.md`、共通の見た目は `style.css` にあります。公開用のビルドは `npm run build` で確認できます。

## 公開

`main` へのpushでGitHub Pagesにデプロイするワークフローを用意しています。GitHubの **Settings → Pages → Build and deployment → Source** を **GitHub Actions** に設定してください。公開先は `https://webxr-jp.github.io/xrift-handson-2026-10/` です。
