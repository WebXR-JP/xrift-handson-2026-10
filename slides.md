---
theme: default
title: XRift ハンズオン
author: WebXR-JP
info: |
  XRift Studioで3Dワールドを作るハンズオン
colorSchema: dark
fonts:
  sans: Noto Sans JP
  mono: JetBrains Mono
---

<div class="flex flex-col items-center justify-center h-full text-center">

<div class="text-purple-300 text-xl tracking-widest mb-8">WebXR-JP / 2026.10</div>

# XRift ハンズオン

## 3Dのワールドを作ってみよう

<div class="mt-10 text-lg opacity-75">
  XRift Studioで、作る → 歩く → 見せる
</div>

</div>

---

# 今日の完成形

<div class="mt-8 p-8 rounded-xl bg-purple-500/10 border border-purple-400/30">

## 小さな休憩広場

<div class="text-xl mt-4">
  床に小道を作り、ベンチと目印を置いた、歩いて回れる3Dワールド。
</div>

</div>

<div class="grid grid-cols-3 gap-5 mt-8 text-center">
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">入り口から広場へ歩ける</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">自分で選んだ色がある</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">Playで中を見て回れる</div>
</div>

<div class="mt-8 text-base opacity-70">
  形や名前は自由。まずはこの小さな作品を完成させましょう。
</div>

---

# 今日の流れ

<div class="mt-8 space-y-4 text-xl">
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">1　XRiftのアカウントを用意する</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">2　XRift Studioを開いてアカウントとつなぐ</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">3　広場を作り、色をつける</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">4　ワールドの中を歩き、完成を確認する</div>
</div>

---

# 1. XRiftのアカウントを用意する

<div class="mt-8 text-2xl">
  <a href="https://xrift.net/">XRiftを開く ↗</a>
</div>

<div class="mt-8 space-y-5 text-xl">
  <div>① 画面の案内に沿ってアカウントを作る</div>
  <div>② ブラウザでログインできることを確かめる</div>
  <div>③ 使ったログイン方法を覚えておく</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  すでにアカウントがあれば、そのまま使えます。
</div>

---

# 2. XRift Studioを開く

<div class="mt-5 text-xl">
  <a href="https://webxr-jp.github.io/xrift-studio/#download">XRift Studioをダウンロード ↗</a>
</div>

<div class="mt-7 space-y-4 text-xl">
  <div>① パソコンに合うインストーラーを選んで入れる</div>
  <div>② XRift Studioを起動する</div>
  <div>③ 最初の画面で <b class="text-purple-300">「セットアップを開始」</b> を押す</div>
</div>

<div class="mt-9 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  プロジェクト一覧が出たら準備完了。必要な制作ツールはStudioが用意します。
</div>

<div class="mt-4 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/installation.md">インストールガイド ↗</a>
</div>

---

# 3. XRiftとつなぐ

<div class="mt-8 space-y-5 text-xl">
  <div>① Studioの <b class="text-purple-300">「XRift にログイン」</b> を押す</div>
  <div>② ブラウザでXRiftのアカウントにログインする</div>
  <div>③ Studioに戻り、自分の表示名を確認する</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  作品を公開するときにも同じアカウントを使います。
</div>

---

# 4. 空のワールドを開く

<div class="mt-7 space-y-5 text-xl">
  <div>① <b class="text-purple-300">「新規プロジェクト」</b> を押す</div>
  <div>② <b class="text-purple-300">「ワールドをビジュアルで作る」</b> を選ぶ</div>
  <div>③ <b class="text-purple-300">「空のワールド」</b> を選び、名前をつけて開く</div>
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  床・ライト・開始位置は最初からあります。まずは床と開始位置を残して作ります。
</div>

---

# 画面の見方

<div class="grid grid-cols-2 gap-5 mt-7 text-lg">
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30"><b class="text-purple-300">Scene</b><br/>ワールドを眺めて、物を選ぶ場所</div>
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30"><b class="text-purple-300">Hierarchy</b><br/>置いた物の一覧</div>
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30"><b class="text-purple-300">Inspector</b><br/>選んだ物の位置・大きさ・見た目を変える場所</div>
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30"><b class="text-purple-300">Assets</b><br/>色や素材を作って置いておく場所</div>
</div>

<div class="mt-7 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/editor-basics.md">画面の使い方 ↗</a>
</div>

---

# 5. 小道を作る

<div class="mt-6 space-y-5 text-xl">
  <div>① 上部の <b class="text-purple-300">「素材を追加」</b> から <b>Entityを作成 → Primitive → Cube</b></div>
  <div>② Hierarchyで追加したCubeを選ぶ</div>
  <div>③ Inspectorの <b>Transform</b> で、薄く・長くする</div>
</div>

<div class="mt-8 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30 text-lg">
  目安：位置 X: 0 / Y: 0.1 / Z: 0、 大きさ X: 2 / Y: 0.2 / Z: 6
</div>

<div class="mt-5 text-base opacity-70">
  床に重なると見えなくなります。少し上に置いて、Sceneで形を確認しましょう。
</div>

---

# 6. ベンチを作る

<div class="mt-6 space-y-5 text-xl">
  <div>① Cubeを追加して横長にする → <b>座る部分</b></div>
  <div>② Cubeをもう2つ追加して細長くする → <b>左右の脚</b></div>
  <div>③ 小道をふさがないよう、横に並べる</div>
</div>

<div class="mt-8 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30 text-lg">
  座面の目安：大きさ X: 2 / Y: 0.2 / Z: 0.7。脚は座面の左右の下に置きます。
</div>

<div class="mt-5 text-base opacity-70">
  ぴったり揃わなくても大丈夫。Sceneを回して、横からも見てみましょう。
</div>

---

# 7. 広場の目印を作る

<div class="mt-7 space-y-5 text-xl">
  <div>① <b>素材を追加 → Entityを作成 → Primitive → Sphere</b></div>
  <div>② 小道の先に置き、Inspectorで位置と大きさを調整する</div>
  <div>③ 目印を見つけやすい高さにする</div>
</div>

<div class="mt-9 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  球のほかにも、好きな形を置いてみましょう。「自分の広場らしさ」が一つあればOK。
</div>

---

# 8. 色をつける

<div class="mt-6 space-y-5 text-xl">
  <div>① 下の <b class="text-purple-300">Assets</b> から <b>新規マテリアル</b> を作る</div>
  <div>② Inspectorの <b>Base Color</b> で好きな色を選ぶ</div>
  <div>③ 色を変えたい物を選び、<b>Mesh Renderer → マテリアル</b> に設定する</div>
</div>

<div class="mt-9 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  小道・ベンチ・目印のうち、まず一つだけ色を変えましょう。
</div>

<div class="mt-4 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/first-world.md">色の付け方 ↗</a>
</div>

---

# 9. 中に入ってみる

<div class="mt-7 space-y-5 text-xl">
  <div>① 上部に <b class="text-purple-300">「保存済み」</b> と出ていることを確認</div>
  <div>② <b class="text-purple-300">Play</b> を押し、画面をクリックする</div>
  <div>③ <b>WASD</b> または矢印キーで小道を歩く</div>
  <div>④ 編集に戻るときは <b>Esc</b>、続けて <b>Stop</b></div>
</div>

<div class="mt-8 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  ベンチや目印は見える？　通り道はふさがっていない？　歩いて確かめて、気になるところを直しましょう。
</div>

---

# できたか確認しよう

<div class="mt-8 space-y-4 text-xl">
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">□　小道・ベンチ・目印を置いた</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">□　少なくとも一つ、色を変えた</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">□　「保存済み」を確認した</div>
  <div class="p-4 rounded-lg bg-purple-500/10 border border-purple-400/30">□　Playで広場を歩いて確認した</div>
</div>

<div class="mt-9 text-xl text-purple-300 font-bold">
  これで、歩いて回れる3Dワールドの完成です！
</div>

---

# もっと作りたい人へ

<div class="grid grid-cols-2 gap-5 mt-8 text-lg">
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30">ベンチを増やして、並べ方を変える</div>
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30">目印の形や色を変えてみる</div>
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30">広場にもう一つ、好きな物を置く</div>
  <div class="p-5 rounded-lg bg-purple-500/10 border border-purple-400/30">Playで歩きながら、見え方を調整する</div>
</div>

<div class="mt-9 text-base opacity-70">
  小道が歩けることを先に確かめてから、少しずつ足しましょう。
</div>

---

# ワールドを見せるには

<div class="mt-7 space-y-5 text-xl">
  <div>① <b>Play</b> で見た目を確認し、<b>保存済み</b> を待つ</div>
  <div>② <b class="text-purple-300">「XRiftへ公開」</b> で、タイトル・説明・サムネイルを整える</div>
  <div>③ 公開先と内容を確認して送信する</div>
  <div>④ 審査の状態を確認し、公開URLが表示されたら開く</div>
</div>

<div class="mt-8 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  作るところまででも完成です。公開する場合は、スタッフと一緒に確認して進めましょう。
</div>

<div class="mt-4 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/publishing.md">公開の手順 ↗</a>
</div>

---

# 困ったときは

<div class="mt-6 space-y-5 text-xl">
  <div>セットアップが止まった → 内容を確認して <b>「セットアップを再試行」</b></div>
  <div>物が見つからない → Hierarchyで選び、<b>F</b> で視点を合わせる</div>
  <div>色が変わらない → マテリアルを作った後、物に割り当てたか確認</div>
  <div>歩けない → Playの画面をクリックしてから移動する</div>
</div>

<div class="mt-8 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  解決しないときは、止まった画面をスタッフに見せてください。
</div>

<div class="mt-4 text-base opacity-70">
  <a href="https://github.com/WebXR-JP/xrift-studio/blob/main/docs/guide/index.md">XRift Studioの使い方 ↗</a>
</div>

---

<div class="flex flex-col items-center justify-center h-full text-center">

# 3Dワールド、完成！

<div class="text-2xl mt-8">自分で作った広場を歩いてみよう。</div>

<div class="text-xl mt-10 opacity-75">
  形も色も、ここから自由に広げられます。
</div>

</div>
