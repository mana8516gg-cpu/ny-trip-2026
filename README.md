# NY旅行アプリ — GitHub Pages 公開手順

## 必要なもの
- 無料のGitHubアカウント(https://github.com/join)
- このフォルダの4ファイル: index.html, manifest.json, service-worker.js, icon-192.png, icon-512.png, README.md(任意)

## 手順

### 1. リポジトリを作る
1. GitHubにログイン → 右上「+」→「New repository」
2. リポジトリ名を決める(例: `ny-trip-2026`)
3. Public / Private どちらでもOK(Privateでも無料でPages公開可能)
4. 「Create repository」をクリック

### 2. ファイルをアップロード
1. 作成したリポジトリのページで「uploading an existing file」(または「Add file」→「Upload files」)をクリック
2. このフォルダの中身(index.html, manifest.json, service-worker.js, icon-192.png, icon-512.png)をまとめてドラッグ&ドロップ
3. 下部の「Commit changes」をクリック

### 3. GitHub Pagesを有効化
1. リポジトリの「Settings」タブ → 左メニュー「Pages」
2. 「Build and deployment」の「Source」を「Deploy from a branch」に設定
3. 「Branch」を `main`(または `master`)、フォルダを `/ (root)` に設定して「Save」
4. 数十秒〜数分待つと、ページ上部に公開URLが表示されます
   例: `https://(あなたのユーザー名).github.io/ny-trip-2026/`

### 4. 家族・友人に共有
- 表示されたURLをLINEやメールでそのまま送るだけ
- 相手がURLを開き、スマホなら「ホーム画面に追加」(iPhone: 共有ボタン→ホーム画面に追加 / Android: メニュー→アプリをインストール)すると、アイコン付きのアプリのように使えます
- App Storeへの申請は不要です

### 5. 内容を更新したいとき
- リポジトリの index.html をブラウザ上で直接編集(鉛筆アイコン)するか、ファイルを再アップロードして Commit すれば、数分後に公開ページへ自動反映されます

## 注意点
- 完全に無料です(GitHub Pagesの利用に課金は発生しません)
- リポジトリをPublicにすると、リポジトリの中身(=旅程の内容)は誰でも見られる状態になります。家族・友人以外に見られたくない場合はPrivateリポジトリにしてください(Private + Pagesの無料公開も可能です)
- タスクのチェック状態はブラウザのlocalStorageに保存されるため、**開いた端末ごとに別々**に保存されます(全員で同期はされません)
