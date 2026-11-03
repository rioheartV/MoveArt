# 🎭 MoveArt

**日本語** | [English](#english)

自分の絵を、顔トラッキングと口パクで動かせる無料のアバターアプリです（Windows 10 / 11・試作版）。

- 配布ページ: https://rioheartv.github.io/apps/moveart/
- ダウンロード: [Releases](../../releases/latest) から `MoveArt_<版>.zip`（Python などを入れる必要はありません）

> 🧪 これは試作版です。思わぬ不具合があったり、使い方や機能・利用時間の決まりが、これからの版で変わることがあります。大事なモデルはこまめに保存し、別の場所にも控えを取ってください。

## できること

- 自分の PSD（レイヤー分けした絵）を取り込んで動かせる（レイヤーがそのままパーツになります）
- カメラの顔トラッキングで頭・目・口が動く・マイクの声で口パク
- 仮想カメラで OBS・配信・ほかのアプリにそのまま映せる（背景の色も選べます）
- パラメータを振った状態でパーツを動かすと、その形がそのパラメータに保存される・揺れ物理
- 録画・スクショ・PSD の書き出し・SmartPaint と連携して塗り直し

この版の顔トラッキングは 1 日 1 時間までです。読み込めるのは PSD と MoveArt のモデルだけです。

## はじめかた

1. zip を右クリック →「すべて展開」で、デスクトップやドキュメントなど書き込める場所に展開します（zip の中から直接起動しない・Program Files の中には置かないでください）。
2. 展開したフォルダの `MoveArt.exe` をダブルクリックします。
3. 最初に利用規約が出ます。読んで同意すると始まります。
4. キャラ選択の画面で「＋ キャラを追加…」を押し、自分の PSD を選びます。

「Windows によって PC が保護されました」と出た時は「詳細情報」→「実行」を押してください（作者の電子署名が無いため、初回だけ出ます）。
ファイルが本物か確かめる時は、Releases に書いた SHA256 と `Get-FileHash .\MoveArt_<版>.zip -Algorithm SHA256` の結果を比べてください。

## 利用規約

ダウンロード・使用の前に、[配布ページの利用規約](https://rioheartv.github.io/apps/moveart/#terms)を読んでください。自己責任で使ってください。
アプリ（exe・zip・中のファイル）をほかの場所で配布することは禁止です。紹介する時は配布ページかこのリポジトリのリンクを案内してください。
このリポジトリは配布用です。ソースコードは置いていません。

---

<a id="english"></a>

## English

A free avatar app that animates your own artwork with face tracking and lip sync (Windows 10 / 11, preview version).

- Download page: https://rioheartv.github.io/apps/moveart/ (Japanese)
- Download: `MoveArt_<version>.zip` from [Releases](../../releases/latest) (no Python or other setup required)

> 🧪 This is a preview version. It may have unexpected bugs, and usage, features and time limits may change in future versions. Save important models often and keep backups elsewhere.

### Features

- Import your own layered PSD and animate it (each layer becomes a part)
- Head, eyes and mouth follow your camera via face tracking; lip sync from your microphone
- Virtual camera output for OBS, streaming and other apps (selectable background color)
- Move parts while a parameter is set and the shape is saved to that parameter; sway physics
- Recording, screenshots, PSD export, repainting via SmartPaint integration

Face tracking in this version is limited to 1 hour per day. Only PSD files and MoveArt models can be loaded.

### Getting started

1. Right-click the zip → "Extract All" to a writable folder such as Desktop or Documents (do not run it from inside the zip or place it under Program Files).
2. Double-click `MoveArt.exe` in the extracted folder.
3. The terms of use appear first; read and accept them to start.
4. On the character select screen, press "＋ キャラを追加…" (Add character) and choose your PSD.

If "Windows protected your PC" appears, click "More info" → "Run anyway" (shown only on first launch because the app is not code-signed).
To verify the download, compare the SHA256 in the release notes with `Get-FileHash .\MoveArt_<version>.zip -Algorithm SHA256`.

### Terms of use

Please read the [terms of use](https://rioheartv.github.io/apps/moveart/#terms) (Japanese) before downloading or using. Use at your own risk.
Redistributing the app (exe, zip or its files) elsewhere is prohibited; please link to the download page or this repository instead.
The app UI is in Japanese. This repository is for distribution only; the source code is not included.
