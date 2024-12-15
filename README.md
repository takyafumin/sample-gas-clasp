# sample-gas-clasp

GAS を ローカルで開発してみる

## 環境

- node v20
- clasp

## プロジェクト作成

```bash
# clasp でログインする
clasp login

# プロジェクト作成
# Script ID には既に作成済みのScript IDを指定すると、Google Drive からソースコードをダウンロードしてくる
npx aside init
✔ Project Title: … GAS Sample by aside
✔ Create an Angular UI? … No / Yes
✔ Generate package.json? … No / Yes
✔ Adding scripts...
✔ Saving package.json...
✔ Installing dependencies...
✔ Installing src template...
✔ Installing test template...
✔ Script ID (optional): …
✔ Script ID for production environment (optional): …
```

## 使い方

### ビルド

```bash
# プロジェクトをビルドする
npm run build
```

### デプロイ

```bash
# lint, test も実行される
npm run deploy
```


### GASデプロイの手順

#### 初回

- コマンドラインでGASファイルを開く
  ```bash
  clasp open
  ```
- デプロイ＞新しいデプロイ
- 「ウェブアプリ」を選択してデプロイ

#### 2回目以降

- コマンドラインでGASファイルを開く
  ```bash
  clasp open
  ```
- デプロイ＞デプロイを管理
- デプロイ済みの定義を編集
  - バージョンは「新バージョン」を選択
  - 説明は任意
