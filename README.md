# 日本史対策EX — サイト試作版

641問の既存データ（v7.1）を利用した、GitHub Pages対応の静的サイトです。

## 公開方法
1. ZIPを展開して、index.html / style.css / app.js / questions.json をGitHubリポジトリのルートにアップロードします。
2. GitHubの Settings → Pages → Build and deployment で Deploy from a branch を選択します。
3. main / (root) を指定して保存します。

## 機能
- 時代・難易度・問題形式・出題数の設定
- ランダム10問クイックスタート
- 解答後の解説、正誤表示
- 間違えた問題の復習と学習履歴（ブラウザのlocalStorage）
- キーボードで1〜4の選択、Enterで次へ
- モバイル対応

## 注意
全641問の個別史実照合は完了していません。正確性が保証された問題集としての公開は避けてください。

## GitHub Pagesでの公開
1. ZIPを展開し、5ファイルをリポジトリの直下にアップロード。
2. Settings → Pages → Deploy from a branch → main → /(root) → Save。
3. PagesのVisit siteから開く。

注: 全641問の史実照合は完了していません。

## 操作画面
初回は「まず10問やってみる」、範囲指定は「問題を選ぶ」から開始できます。回答後に正解と解説が表示され、間違えた問題は復習できます。
