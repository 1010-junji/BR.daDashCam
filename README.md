# 📸 daDashCam

<img width="320" height="320" alt="dashcam" src="https://github.com/user-attachments/assets/6ec1239e-e490-478f-ab1d-e2bfee3fa75e" />

`daDashCam の配布用リポジトリです`

## 概要 / Overview

daDashCamは、バックグラウンドで静かに動作する常駐型のアプリケーションです。ユーザーの作業を邪魔することなく、タスクトレイのアイコンから数クリックするだけで、デスクトップ全体の録画や、ヘッドレスブラウザ操作のモニタリングを開始・停止できます。
再現が難しいバグの記録、ソフトウェアの操作デモ、あるいは個人的な作業手順の備忘録として、さまざまなシーンであなたの「目」となります。

このリポジトリでは、画面をモニタリング・録画する `daDashCam` のソフトウェアを配布します。


![Animation3](https://github.com/user-attachments/assets/8152bfdd-3562-4e3b-882c-06fe29cbace1)

## 主な特徴 / Features

-   **🕊️ 軽量＆シンプル (Lightweight & Simple)**
    -   タスクトレイに常駐し、複雑なUIは一切なし。誰でも直感的に操作できます。
    -   低解像度・低フレームレートでの録画に最適化されており、古いPCや高負荷な作業中でも快適に動作します。

-   **🤖 高度なChromiumモニタリング (Advanced Chromium Monitoring)**
    -   [Chrome DevTools Protocol (CDP)](https://chromedevtools.github.io/devtools-protocol/) を活用し、通常の画面録画では捉えきれないブラウザ（Chrome, Edgeなど）内のマウスカーソルの動きやクリック操作を詳細に記録する、ユニークな機能を搭載しています。

-   **⚙️ 外部連携＆自動化 (External Integration & Automation)**
    -   Web API (`/startRecording`, `/stopRecording`) やコマンドライン引数 (`--start-recording`) をサポート。
    -   外部のテストスクリプトとの連携や、PC起動時の自動録画開始など、柔軟で高度な運用が可能です。

-   **📊 リソース監視 (Resource Monitoring)**
    -   録画と同時にCPUやメモリの使用率をCSVファイルに記録。アプリケーションのパフォーマンステストや、システムトラブルの解析にも活用できます。

## こんな方におすすめ / Ideal for...

-   **ソフトウェアテスター / QAエンジニア**
    -   再現性の低いバグが発生した際の、正確な操作手順の記録に。
-   **開発者**
    -   ソフトウェアのデモンストレーション動画の作成や、ユーザー操作の再現に。
-   **カスタマーサポート / ヘルプデスク**
    -   ユーザーからの問い合わせ内容を動画で正確に把握するために。
-   **すべてのPCユーザー**
    -   定型的な作業手順の記録や、後で見返したい操作の備忘録として。

## インストール / Installation

最新バージョンは、[リリースページ](https://github.com/1010-junji/BR.daDashCam/releases))からダウンロードできます。
インストーラー版 (`dadashcam.Setup.0.9.0.exe`)と、解凍するだけですぐに使えるポータブル版 (`dadashcam.0.9.0.exe`)を用意しています。

## クイックスタート / Quick Start

1.  アプリケーションを起動します。
2.  タスクトレイに表示された`daDashCam`のアイコンを右クリックします。
3.  `[デスクトップ録画の開始]` をクリックすると、録画が始まります。
4.  もう一度アイコンを右クリックし、`[デスクトップ録画の停止]` をクリックすると録画が終了し、動画ファイルが保存されます。
  
詳細な使い方はリリースページ内に同梱された **ユーザーマニュアル** をご覧ください。

## daDashCam

daDashCam 入手はこちらから。👉 https://github.com/1010-junji/BR.daDashCam.Player

<img width="120" height="120" alt="dadashcam-player" src="https://github.com/user-attachments/assets/ff7dec7c-682c-4196-9fec-1d217cdc765a" />

## コントリビュート / Contributing

バグ報告、機能提案、プルリクエストを歓迎します！
何かお気づきの点があれば、お気軽に[Issue](https://github.com/1010-junji/BR.daDashCam/issues)を立ててください。
