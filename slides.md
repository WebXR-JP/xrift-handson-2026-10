---
theme: default
title: XRift ハンズオン
author: WebXR-JP
info: |
  XRift Studioでワールドを作るハンズオン
colorSchema: dark
fonts:
  sans: Noto Sans JP
  mono: JetBrains Mono
---

<div class="flex flex-col items-center justify-center h-full text-center">

<div class="text-purple-300 text-xl tracking-widest mb-8">WebXR-JP / 2026.10</div>

# XRift ハンズオン

## 自分だけのワールドを作ろう

<div class="mt-10 text-lg opacity-75">
  XRift Studioを使って、作る・歩く・見せるを体験します
</div>

</div>

---

# 今日やること

<div class="grid grid-cols-2 gap-6 mt-8">

<div class="p-6 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">01　つなぐ</div>
  <p>XRiftのアカウントを作って、XRift Studioとつなぎます。</p>
</div>

<div class="p-6 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">02　作る</div>
  <p>エディターで物を置き、色を変えてワールドを作ります。</p>
</div>

<div class="p-6 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">03　歩く</div>
  <p>Playで中に入り、自分の作品を確かめます。</p>
</div>

<div class="p-6 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">04　見せる</div>
  <p>できあがった作品を、XRiftで公開する流れを知ります。</p>
</div>

</div>

---

# まず使うもの

<div class="mt-8 space-y-5">

<div class="p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">パソコン</div>
  <div>Windows または Mac。インターネットにつながる状態にしておきます。</div>
</div>

<div class="p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">XRiftのアカウント</div>
  <div>作品を自分のアカウントで公開するときに使います。</div>
</div>

<div class="p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <div class="text-purple-300 font-bold text-2xl">XRift Studio</div>
  <div>ワールドを作るアプリ。画面を見ながら操作できます。</div>
</div>

</div>

---

# 1. XRiftのアカウントを作る

<div class="mt-8 text-2xl">
  <a href="https://xrift.net/">XRiftを開く ↗</a>
</div>

<ol class="mt-7 space-y-4 text-xl">
  <li>画面の案内に沿ってアカウントを作る</li>
  <li>ブラウザでログインできることを確かめる</li>
  <li>使ったログイン方法を覚えておく</li>
</ol>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  すでにアカウントがあれば、そのアカウントを使えます。
</div>

---

# 2. XRift Studioを入れる

<div class="mt-6 text-xl">
  <a href="https://webxr-jp.github.io/xrift-studio/#download">XRift Studioのダウンロード案内を開く ↗</a>
</div>

<div class="mt-7 space-y-4 text-xl">
  <div>① 自分のパソコンに合うインストーラーを選ぶ</div>
  <div>② インストールしてXRift Studioを開く</div>
  <div>③ 最初の画面で <b class="text-purple-300">「セットアップを開始」</b> を押す</div>
</div>

<div class="mt-9 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  プロジェクト一覧が表示されたらOK。制作に必要なツールはアプリが用意します。
</div>

<div class="mt-5 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/installation.md">インストールガイド ↗</a>
</div>

---

# 3. XRift Studioをアカウントにつなぐ

<div class="mt-6 space-y-5 text-xl">
  <div>① XRift Studioの画面で <b class="text-purple-300">「XRift にログイン」</b> を押す</div>
  <div>② 開いたブラウザで、先ほど作ったアカウントでログインする</div>
  <div>③ Studioに戻り、自分の表示名が出たら連携完了</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  ここではまだ作品を公開しません。ログインと公開は別の操作です。
</div>

---

# 4. 最初のワールドを開く

<div class="mt-6 space-y-5 text-xl">
  <div>① プロジェクト一覧の <b class="text-purple-300">「新規プロジェクト」</b> を押す</div>
  <div>② <b class="text-purple-300">「ワールドをビジュアルで作る」</b> を選ぶ</div>
  <div>③ <b class="text-purple-300">「空のワールド」</b> から始める</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  最初から床・ライト・開始位置が入っています。ここに好きなものを置いていきます。
</div>

---

# まずは一つ、置いてみよう

<div class="mt-6 space-y-5 text-xl">
  <div>上部の <b class="text-purple-300">「素材を追加」</b> から球を置いてみます。</div>
  <div>球を選び、右側の <b class="text-purple-300">Inspector</b> で位置を変えます。</div>
  <div><b class="text-purple-300">Play</b> を押すと、作ったワールドの中を歩けます。</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  まずは置く・動かす・歩く。この3つができれば大成功！
</div>

<div class="mt-5 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/first-world.md">操作を詳しく見る ↗</a>
</div>

---

# 困ったときは

<div class="mt-6 space-y-5 text-xl">
  <div>アカウントに入れない → まず <a href="https://xrift.net/">XRiftのサイト</a>でログインを確認</div>
  <div>セットアップが止まった → 表示された内容を確認して「セットアップを再試行」</div>
  <div>Studioでログインできない → ブラウザで認証を終えたか確認</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  解決しないときは、止まった画面をスタッフに見せてください。
</div>

<div class="mt-5 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/index.md">XRift Studioの使い方 ↗</a>
</div>
