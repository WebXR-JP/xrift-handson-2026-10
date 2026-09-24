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

<div class="text-purple-300 text-xl tracking-widest mb-7">WebXR-JP / 2026.10</div>

# XRift Studio

## 3Dワールドを作るまでの流れ

<div class="mt-8 text-xl opacity-80">
  作る → 中を歩く → XRiftで見せる
</div>

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

# 案内するメンバー

<div class="grid grid-cols-3 gap-6 mt-9 text-center">

<div class="flow-card items-center">
  <img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/staff-hagar.png" alt="はが" class="w-28 h-28 rounded-full object-cover border-2 border-purple-400/50" />
  <strong class="text-purple-300">はが</strong>
  <span>進行・制作案内</span>
</div>

<div class="flow-card items-center">
  <img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/staff-tomyu.png" alt="とみゅ〜" class="w-28 h-28 rounded-full object-cover border-2 border-purple-400/50" />
  <strong class="text-purple-300">とみゅ〜</strong>
  <span>サポート</span>
</div>

<div class="flow-card items-center">
  <img src="https://raw.githubusercontent.com/WebXR-JP/xrift-handson-2026-04/2cbef7ca8096a0636fb3625f54805c93364f062d/public/staff-sawa-zen.png" alt="sawa-zen" class="w-28 h-28 rounded-full object-cover border-2 border-purple-400/50" />
  <strong class="text-purple-300">sawa-zen</strong>
  <span>XRift開発者</span>
</div>

</div>

<div class="mt-8 text-center text-xl opacity-80">
  分からないところは、気軽に聞いてください。
</div>

---

# まずは流れを見てみよう

<div class="grid grid-cols-3 gap-4 mt-9">
  <div class="flow-card"><div class="flow-number">01</div><strong>準備する</strong><span>XRiftのアカウント</span></div>
  <div class="flow-card"><div class="flow-number">02</div><strong>作る・試す</strong><span>ブラウザかアプリで制作</span></div>
  <div class="flow-card"><div class="flow-number">03</div><strong>見せる</strong><span>XRiftへ公開</span></div>
</div>

<div class="mt-10 text-xl opacity-80">
  Studioはブラウザで開く方法と、パソコンに入れる方法があります。
</div>

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
  <div class="text-5xl font-bold text-purple-300">XRift</div>
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
    <div class="text-4xl">💻</div>
    <strong>パソコン</strong>
    <span>ブラウザ版・インストール版の両方を選べます。</span>
  </div>
  <div class="flow-card items-center">
    <div class="text-4xl">▣</div>
    <strong>iPad</strong>
    <span>Safariでブラウザ版を開き、タッチ操作で制作できます。</span>
  </div>
  <div class="flow-card items-center">
    <div class="text-4xl">▯</div>
    <strong>スマホ</strong>
    <span>ブラウザ版を開けます。画面が狭いため、制作はパソコンやiPadが進めやすいです。</span>
  </div>
</div>

<div class="mt-8 text-base opacity-70">
  Chromeは入口の例です。表示や操作はブラウザ・端末によって異なります。
</div>

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

<div class="grid grid-cols-2 gap-8 mt-9">
  <div class="visual-card">
    <div class="flow-number">インストール版</div>
    <div class="text-xl mt-5">Studioの<strong class="text-purple-300">「XRift にログイン」</strong>からブラウザでログインします。</div>
  </div>
  <div class="visual-card">
    <div class="flow-number">ブラウザ版β</div>
    <div class="text-xl mt-5">編集はブラウザで始められます。XRiftへ送るときは、XRiftの設定で作るAPIキーを使います。</div>
  </div>
</div>

<div class="mt-9 text-base opacity-70">
  公開の操作は利用する版によって異なります。制作の流れは次から共通です。
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
</div>

<div class="visual-card h-64 flex flex-col justify-center">
  <div class="text-2xl font-bold text-purple-300">制作 → 確認 → 公開</div>
  <div class="text-lg mt-6 opacity-75">公開URLが出たら、実際に開いてみましょう。</div>
  <a class="text-base mt-6" href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/publishing.md">公開の手順 ↗</a>
</div>

</div>

---

<div class="flex flex-col items-center justify-center h-full text-center">

# 3Dワールド制作へ

<div class="text-2xl mt-9">
  ブラウザかアプリを選び、作って、Playで確かめ、XRiftで見せる。
</div>

<div class="text-lg mt-10 opacity-75">
  制作の具体的な内容は、次の段階で決めていきます。
</div>

</div>
