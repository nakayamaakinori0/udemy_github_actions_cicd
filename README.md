# udemy_github_actions_cicd

[![backend](https://github.com/nakayamaakinori0/udemy_github_actions_cicd/actions/workflows/backend.yml/badge.svg)](https://github.com/nakayamaakinori0/udemy_github_actions_cicd/actions/workflows/backend.yml)

udemy-github-actions-key.pemはaws ec2 にssh接続するための秘密鍵

backend.serviceはec2のsystemdの設定



# サンプルアプリケーション

静的なフロントエンドと Web API から成る、足し算アプリケーションです。

## 開発モードでの起動手順

サンプルアプリケーションは、以下の手順で開発モードで起動します。

```console
cd backend/
npm ci
npm run dev
```

起動したら、ブラウザで http://localhost:8080 にアクセスしてください。

Cloud9 の場合は、「Tools」>「Preview」>「Preview Running Application」でプレビューを起動して、「Pop Out Into New Window」でブラウザの別タブでアクセスしてください。

## バックエンドをビルドして実行する手順

バックエンドをビルドして実行する場合は、以下のコマンドを実行してください。

```console
cd backend/
npm ci
npm run build
node dist/index.js
```
