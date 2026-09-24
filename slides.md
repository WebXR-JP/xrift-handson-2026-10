---
theme: default
title: XRift ハンズオン｜事前準備
author: WebXR-JP
info: |
  XRift ハンズオン 2026年10月開催に向けた事前準備
colorSchema: dark
fonts:
  sans: Noto Sans JP
  mono: JetBrains Mono
---

<div class="flex flex-col items-center justify-center h-full text-center">

<div class="text-purple-300 text-xl tracking-widest mb-8">WebXR-JP / 2026.10</div>

# XRift ハンズオン

## 事前準備から始めよう

<div class="mt-10 text-lg opacity-75">
  当日までに使うものをそろえ、ログインまで確認します
</div>

</div>

---

# 事前準備のゴール

この4つができれば準備完了です。

1. パソコンに **VS Code** と **Node.js** を入れる
2. **XRift アカウント**を作る
3. **XRift CLI** を入れる
4. `xrift whoami` で自分の名前を確認する

<div class="mt-10 text-base opacity-70">
  初めてでも大丈夫です。次のページから順番に進めてください。
</div>

---

# 1. 作業に使うソフトを入れる

<div class="grid grid-cols-2 gap-8 mt-8">

<div class="p-6 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <h2>VS Code</h2>
  <p>コードを書いたり、コマンドを入力したりするために使います。</p>
  <a href="https://code.visualstudio.com/">公式サイトからダウンロード ↗</a>
</div>

<div class="p-6 rounded-xl bg-purple-500/10 border border-purple-400/30">
  <h2>Node.js</h2>
  <p>JavaScript をパソコンで動かすために使います。公式サイトの LTS（推奨版）を選んでください。</p>
  <a href="https://nodejs.org/">公式サイトからダウンロード ↗</a>
</div>

</div>

<div class="mt-8 text-base">
  インストール後、VS Code の「ターミナル」→「新しいターミナル」で確認します。
</div>

```bash
node --version
npm --version
```

---

# 2. XRift のアカウントを作る

<a href="https://xrift.net/">xrift.net を開く ↗</a>

<div class="mt-6 text-xl">
  アカウントを作成し、ブラウザからログインできることを確認してください。
</div>

<div class="mt-10 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  すでにアカウントがあれば、新しく作る必要はありません。
</div>

---

# 3. XRift CLI を入れる

VS Code のターミナルで、次のコマンドを実行します。

```bash
npm install -g @xrift/cli
```

インストールできたか確認します。

```bash
xrift --version
```

<div class="mt-6 text-base opacity-75">
  数字が表示されれば準備できています。コマンドが見つからない場合は、ターミナルを開き直してから再度確認してください。
</div>

---

# 4. ログインする

ターミナルで実行します。

```bash
xrift login
```

ブラウザが開いたら、XRift のアカウントでログインしてください。

```bash
xrift whoami
```

<div class="mt-6 p-5 rounded-xl bg-purple-500/10 border border-purple-400/30">
  自分のユーザー名が表示されたら、事前準備は完了です！
</div>

---

# 困ったときは

- `node` や `npm` が見つからない → Node.js を入れ直し、ターミナルを開き直す
- `xrift` が見つからない → CLI のインストールを確認し、ターミナルを開き直す
- ログインできない → <a href="https://xrift.net/">XRift のサイト</a>でログインできるか確認する

<div class="mt-10">
  詳しい使い方：<a href="https://docs.xrift.net/">XRift 公式ドキュメント ↗</a>
</div>

<div class="mt-8 text-base opacity-70">
  解決しない場合は、表示されたエラーメッセージを控えて当日スタッフに聞いてください。
</div>
