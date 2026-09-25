---
theme: default
title: XRift Studioで3Dワールドを作る
author: WebXR-JP
info: |
  XRift Studioで3Dワールドを作るまでの流れ
colorSchema: dark
drawings:
  enabled: false
fonts:
  sans: Noto Sans JP
  mono: JetBrains Mono
---

<div class="flex flex-col items-center justify-center h-full text-center">

<img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/xrift-logo.svg" alt="XRift" class="h-20 max-w-64 object-contain mb-7" />

<div class="text-purple-300 text-xl tracking-widest mb-7">WebXR-JP / 2026.10</div>

# XRift Studioで<br/>3Dワールドを作る

## はじめ方から公開まで

<div class="mt-8 text-xl opacity-80">
  ブラウザとアプリ、どちらからでも始められます
</div>

</div>

---

# この資料で分かること

<div class="grid grid-cols-3 gap-5 mt-10">
  <div class="flow-card">
    <div class="flow-number">01</div>
    <strong>何を使う？</strong>
    <span>XRiftとXRift Studioの関係</span>
  </div>
  <div class="flow-card">
    <div class="flow-number">02</div>
    <strong>どう始める？</strong>
    <span>ブラウザ版・アプリ版の入口</span>
  </div>
  <div class="flow-card">
    <div class="flow-number">03</div>
    <strong>どう見せる？</strong>
    <span>制作からPlay、公開まで</span>
  </div>
</div>

<div class="mt-9 text-xl opacity-80 text-center">
  まず全体像をつかんでから、ワールド作りへ進みます。
</div>

---

# XRiftとは？

<div class="grid grid-cols-2 gap-10 items-center mt-8">

<div>
  <div class="text-2xl leading-relaxed">
    ブラウザから入れる、3Dの交流空間です。
  </div>
  <div class="text-xl mt-8 opacity-80">
    作ったワールドを公開すると、ほかの人にも見てもらえます。
  </div>
  <div class="text-base mt-9 opacity-65">
    XRift Studioは、そのワールドを作るための有志製アプリです。
  </div>
</div>

<div class="visual-card h-64 flex justify-center items-center">
  <img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/xrift-logo.svg" alt="XRiftのロゴ" class="w-64 max-h-32 object-contain" />
</div>

</div>

---

# 案内する人

<div class="grid grid-cols-2 gap-10 items-center mt-10">

<div class="flex justify-center">
  <img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/staff-hagar.png" alt="はが" class="w-48 h-48 rounded-full object-cover border-4 border-purple-400/50" />
</div>

<div>
  <div class="flow-number">WebXR-JP</div>
  <div class="text-4xl font-bold text-purple-300 mt-4">はが</div>
  <div class="text-xl mt-6">XRift Studioを使う流れを案内します。</div>
  <div class="text-lg mt-7 opacity-75">分からないところは気軽に聞いてください。</div>
</div>

</div>

---

# まずは流れを見てみよう

<div class="grid grid-cols-3 gap-4 mt-9">
  <div class="flow-card">
    <svg class="flow-icon" viewBox="0 0 64 64" fill="none" aria-label="アカウント"><circle cx="32" cy="20" r="10" stroke="currentColor" stroke-width="3"/><path d="M12 54c0-12 8-20 20-20s20 8 20 20" stroke="currentColor" stroke-width="3" stroke-linecap="round"/></svg>
    <div class="flow-number">01</div><strong>準備する</strong><span>XRiftのアカウント</span>
  </div>
  <div class="flow-card">
    <svg class="flow-icon" viewBox="0 0 64 64" fill="none" aria-label="制作"><rect x="8" y="10" width="48" height="37" rx="3" stroke="currentColor" stroke-width="3"/><path d="M17 54h30M32 47v7" stroke="currentColor" stroke-width="3" stroke-linecap="round"/></svg>
    <div class="flow-number">02</div><strong>作る・試す</strong><span>ブラウザかアプリで制作</span>
  </div>
  <div class="flow-card">
    <svg class="flow-icon" viewBox="0 0 64 64" fill="none" aria-label="公開"><circle cx="32" cy="32" r="22" stroke="currentColor" stroke-width="3"/><path d="M10 32h44M32 10c7 6 11 13 11 22s-4 16-11 22c-7-6-11-13-11-22s4-16 11-22Z" stroke="currentColor" stroke-width="3"/></svg>
    <div class="flow-number">03</div><strong>見せる</strong><span>XRiftへ公開</span>
  </div>
</div>

<div class="mt-8 text-xl opacity-80">Studioはブラウザでも、パソコンのアプリでも使えます。</div>

---

# XRiftのアカウントを用意

<div class="grid grid-cols-2 gap-10 items-center mt-8">

<div>
  <div class="flow-number">01 / 準備する</div>
  <div class="text-2xl leading-relaxed mt-4">
    <a href="https://xrift.net/">XRiftを開く ↗</a><br/>
    アカウントを作って、ブラウザでログインします。
  </div>
  <div class="text-base opacity-70 mt-8">
    すでに持っている場合は、そのアカウントを使えます。
  </div>
</div>

<div class="visual-card flex flex-col justify-center items-center h-64">
  <img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/xrift-logo.svg" alt="XRiftのロゴ" class="w-52 max-h-24 object-contain" />
  <div class="text-xl mt-4 opacity-75">自分のワールドを見せる場所</div>
</div>

</div>

---

# Studioの使い方を選ぶ

<div class="grid grid-cols-2 gap-8 mt-8">

<div class="visual-card flex flex-col items-center text-center min-h-72">
  <img src="https://www.google.com/chrome/static/images/chrome-logo-m100.svg" alt="Google Chrome" class="w-16 h-16 mt-1 mb-5" />
  <strong class="text-2xl text-purple-300">ブラウザで開く</strong>
  <div class="text-base mt-4 opacity-80">パソコンのChromeなどから、そのまま制作。</div>
  <a class="mt-auto text-lg" href="https://webxr-jp.github.io/xrift-studio/editor.html">ブラウザ版βを開く ↗</a>
</div>

<div class="visual-card flex flex-col items-center text-center min-h-72">
  <svg aria-label="パソコン" role="img" class="w-18 h-18 mb-4 text-purple-300" viewBox="0 0 80 80" fill="none"><rect x="10" y="13" width="60" height="43" rx="5" stroke="currentColor" stroke-width="4"/><path d="M6 65h68M30 56l-3 9m23-9 3 9" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>
  <strong class="text-2xl text-purple-300">アプリを入れる</strong>
  <div class="text-base mt-4 opacity-80">Windows・Macなどのパソコンにインストール。</div>
  <a class="mt-auto text-lg" href="https://webxr-jp.github.io/xrift-studio/#download">ダウンロード案内 ↗</a>
</div>

</div>

---

# 使う端末の目安

<div class="grid grid-cols-3 gap-5 mt-9 text-center">
  <div class="flow-card items-center">
    <svg class="flow-icon" viewBox="0 0 64 64" fill="none" aria-label="パソコン"><rect x="7" y="10" width="50" height="36" rx="3" stroke="currentColor" stroke-width="3"/><path d="M4 54h56M24 46l-3 8m19-8 3 8" stroke="currentColor" stroke-width="3" stroke-linecap="round"/></svg>
    <strong>パソコン</strong><span>ブラウザ版・インストール版の両方を選べます。</span>
  </div>
  <div class="flow-card items-center">
    <svg class="flow-icon" viewBox="0 0 64 64" fill="none" aria-label="iPad"><rect x="11" y="5" width="42" height="54" rx="5" stroke="currentColor" stroke-width="3"/><circle cx="32" cy="53" r="2" fill="currentColor"/></svg>
    <strong>iPad</strong><span>Safariでブラウザ版を開き、タッチ操作で制作できます。</span>
  </div>
  <div class="flow-card items-center">
    <svg class="flow-icon" viewBox="0 0 64 64" fill="none" aria-label="スマホ"><rect x="18" y="4" width="28" height="56" rx="5" stroke="currentColor" stroke-width="3"/><path d="M27 10h10" stroke="currentColor" stroke-width="3" stroke-linecap="round"/></svg>
    <strong>スマホ</strong><span>ブラウザ版を開けます。制作はパソコンやiPadが進めやすいです。</span>
  </div>
</div>

<div class="mt-8 text-base opacity-70">Chromeは入口の例です。画面や操作は端末によって異なります。</div>

---

# アプリで始める場合

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">02 / インストール版</div>
  <div class="text-xl mt-6 leading-relaxed">
    アプリを起動し、最初の画面で
    <strong class="text-purple-300">「セットアップを開始」</strong>を押します。
  </div>
  <div class="text-base opacity-70 mt-8">必要な制作ツールはStudioが準備します。</div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/installation.png" alt="XRift Studioの初回セットアップ画面" />
  <div class="caption">インストール版の初回画面</div>
</div>

</div>

---

# ログインと公開

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="visual-card">
    <div class="flow-number">インストール版</div>
    <div class="text-lg mt-4">Studioの「XRift にログイン」からブラウザでログインします。</div>
  </div>
  <div class="visual-card mt-5">
    <div class="flow-number">ブラウザ版β</div>
    <div class="text-lg mt-4">編集はすぐに始められます。XRiftへ送るときはAPIキーを使います。</div>
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/new-project.png" alt="インストール版の画面右上にXRiftにログインのボタンがある" />
  <div class="caption">画面例はインストール版</div>
</div>

</div>

---

# ワールドを開く

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">02 / 作る・試す</div>
  <div class="text-xl mt-6 leading-relaxed">
    プロジェクト一覧で<strong class="text-purple-300">ワールドを新しく作る</strong>。
    インストール版では「新規プロジェクト」から「ワールドをビジュアルで作る」を選びます。
  </div>
  <div class="text-base opacity-70 mt-8">
    ブラウザ版ではワールドを選んで「新規作成」に進みます。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/new-project.png" alt="インストール版の新規プロジェクト画面" />
  <div class="caption">画面例はインストール版</div>
</div>

</div>

---

# はじめる場所を選ぶ

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">02 / 作る・試す</div>
  <div class="text-xl mt-6 leading-relaxed">
    <strong class="text-purple-300">「空のワールド」</strong>から始められます。
    床・ライト・開始位置が用意されています。
  </div>
  <div class="text-base opacity-70 mt-8">
    ワールドの内容は、制作するときに決めましょう。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/blank-world.png" alt="空のワールドを選ぶ画面" />
  <div class="caption">「空のワールド」を選ぶ画面</div>
</div>

</div>

---

# 画面で作る

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">02 / 作る・試す</div>
  <div class="text-xl mt-6 leading-relaxed">
    物を置いて、位置や見た目を変えます。
    右側の<strong class="text-purple-300">Inspector</strong>で、選んだ物を調整できます。
  </div>
  <div class="text-base opacity-70 mt-8">
    変更は自動で保存されます。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/first-world.png" alt="XRift Studioの編集画面。中央にワールド、右に設定、下に素材がある" />
  <div class="caption">中央で見て、右側で調整</div>
</div>

</div>

---

# 中を歩いて確かめる

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">02 / 作る・試す</div>
  <div class="text-xl mt-6 leading-relaxed">
    <strong class="text-purple-300">Play</strong>でワールドの中に入ります。
    歩いて見た印象を確かめ、気になるところを調整します。
  </div>
  <div class="text-base opacity-70 mt-8">
    編集に戻るときはEscを押してからStop。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/play-mode.png" alt="Play中のワールド画面。上部にStopボタンがある" />
  <div class="caption">作りながら、実際の見え方を確認</div>
</div>

</div>

---

# XRiftで見せる

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">03 / 見せる</div>
  <div class="text-xl mt-6 leading-relaxed">
    ワールドができたらタイトル・説明・画像を整え、
    <strong class="text-purple-300">「XRiftへ公開」</strong>から送信します。
  </div>
  <div class="text-base opacity-70 mt-8">
    インストール版はログイン、ブラウザ版βはAPIキーが必要です。
    送信後は<ruby>審査<rt>しんさ</rt></ruby>の状況を確認します。
  </div>
  <a class="text-base mt-6 inline-block" href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/publishing.md">公開の手順 ↗</a>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/step-shots/myworld-list.png" alt="XRiftのマイワールド画面の例" />
  <div class="caption">XRiftの「マイワールド」画面の例</div>
</div>

</div>

---

# 持ち帰ること

<div class="mt-8 space-y-5 text-xl">
  <div class="visual-card"><strong class="text-purple-300">始める場所</strong>　ブラウザ版かアプリ版を選べる</div>
  <div class="visual-card"><strong class="text-purple-300">作る順番</strong>　ワールドを開く → 編集する → Playで確かめる</div>
  <div class="visual-card"><strong class="text-purple-300">見せる方法</strong>　作品を整えてXRiftへ公開する</div>
</div>

<div class="mt-9 text-lg opacity-70">
  作るワールドの内容は、これから自由に考えられます。
</div>

---

<div class="flex flex-col items-center justify-center h-full text-center">

<img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/xrift-logo.svg" alt="XRift" class="h-16 max-w-52 object-contain mb-6" />

# 3Dワールド制作へ

<div class="text-2xl mt-9">
  ブラウザかアプリを選び、作って、Playで確かめ、XRiftで見せる。
</div>

<div class="text-lg mt-10 opacity-75">
  制作の具体的な内容は、次の段階で決めていきます。
</div>

</div>
