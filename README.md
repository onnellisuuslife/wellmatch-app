# WellMatch PWA

専門家マッチング × ウェルネス アプリのデモ版です。

## GitHub Pages への公開手順

### 1. リポジトリを作成する
1. GitHub にログイン
2. 右上の「+」→「New repository」
3. Repository name: `wellmatch-app`
4. Public を選択
5. 「Create repository」

### 2. ファイルをアップロードする
1. 「uploading an existing file」をクリック
2. このフォルダの中身を全部ドラッグ＆ドロップ
   - index.html
   - manifest.json
   - sw.js
   - icons/ フォルダごと
3. 「Commit changes」

### 3. GitHub Pages を有効にする
1. リポジトリの「Settings」タブ
2. 左メニュー「Pages」
3. Branch: `main` / folder: `/ (root)` を選択
4. 「Save」

### 4. URLが発行される（数分後）
```
https://（あなたのGitHubユーザー名）.github.io/wellmatch-app/
```

### 5. スマホでアクセスしてホーム画面に追加
- iPhone: Safari で開く → 共有ボタン → 「ホーム画面に追加」
- Android: Chrome で開く → メニュー → 「ホーム画面に追加」

これでアプリアイコンがホーム画面に表示されます。

## ファイル構成
```
wellmatch-pwa/
├── index.html      ← メインアプリ
├── manifest.json   ← PWA設定
├── sw.js           ← Service Worker
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## 機能
- ユーザー登録・ログイン（匿名OK）
- ウェルネスマップ（12分野）
- 専門家一覧（12名）
- AIカウンセリング（APIキー入力でリアルAI動作）
- 専門家マッチング体験
- XP・レベルシステム
- デイリークエスト
- 実績バッジ

## お問い合わせ
onnellisuus.life@gmail.com
https://www.onnellisuus.net
