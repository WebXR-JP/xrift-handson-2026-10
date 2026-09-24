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

# まずは流れを見てみよう

<div class="mt-6 text-2xl leading-relaxed">
  この資料では、XRift Studioを使った制作の流れを紹介します。
</div>

<div class="grid grid-cols-3 gap-4 mt-10">
  <div class="flow-card"><div class="flow-number">01</div><strong>準備する</strong><span>アカウントとStudio</span></div>
  <div class="flow-card"><div class="flow-number">02</div><strong>作る・試す</strong><span>編集してPlay</span></div>
  <div class="flow-card"><div class="flow-number">03</div><strong>見せる</strong><span>XRiftへ公開</span></div>
</div>

<div class="mt-8 text-base opacity-70">
  ワールドに何を作るかは、これから決めていきます。
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

# XRift Studioを入れる

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">01 / 準備する</div>
  <div class="text-2xl leading-relaxed mt-4">
    <a href="https://webxr-jp.github.io/xrift-studio/#download">Studioをダウンロード ↗</a>
  </div>
  <div class="text-xl mt-7">
    初めて起動したら<br/><strong class="text-purple-300">「セットアップを開始」</strong>を押します。
  </div>
  <div class="text-base opacity-70 mt-7">
    必要な制作ツールはStudioが準備します。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/installation.png" alt="XRift Studioの初回セットアップ画面" />
  <div class="caption">XRift Studioの初回画面</div>
</div>

</div>

---

# アカウントをつなぐ

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">01 / 準備する</div>
  <div class="text-xl mt-6 leading-relaxed">
    Studioの<strong class="text-purple-300">「XRift にログイン」</strong>を押します。
    ブラウザでXRiftにログインし、Studioに戻ります。
  </div>
  <div class="visual-card mt-8 text-lg">
    Studioに自分の表示名が出たら完了です。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/new-project.png" alt="XRift Studioのプロジェクト作成画面。右上にXRiftにログインのボタンがある" />
  <div class="caption">画面右上に「XRift にログイン」</div>
</div>

</div>

---

# ワールドを開く

<div class="grid grid-cols-2 gap-8 items-center mt-5">

<div>
  <div class="flow-number">02 / 作る・試す</div>
  <div class="text-xl mt-6 leading-relaxed">
    <strong class="text-purple-300">「新規プロジェクト」</strong>から
    <strong>「ワールドをビジュアルで作る」</strong>を選びます。
  </div>
  <div class="text-base opacity-70 mt-8">
    ここから画面を見ながら制作を始められます。
  </div>
</div>

<div>
  <img class="screenshot" src="https://raw.githubusercontent.com/WebXR-JP/xrift-studio/4337228c3049fabafe9c707ee0b1ef1bb635e03e/docs/guide/media/new-project.png" alt="新しいプロジェクトの作り方を選ぶ画面" />
  <div class="caption">左下の「ワールドをビジュアルで作る」</div>
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
    ワールドができたら<strong class="text-purple-300">「XRiftへ公開」</strong>から
    タイトル・説明・画像を整えて送信します。
  </div>
  <div class="text-base opacity-70 mt-8">
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
  XRift Studioで作り、Playで確かめ、XRiftで見せる。
</div>

<div class="text-lg mt-10 opacity-75">
  制作の具体的な内容は、次の段階で決めていきます。
</div>

</div>
