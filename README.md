# appsync-serverless-poc

[Apollo Odyssey](https://www.apollographql.com/tutorials/)のLift-offで作るサンプルアプリケーション（Catstronaut）のバックエンドの一部をServerless Frameworkを使ってAppSyncにデプロイするサンプル実装

## Prerequisite

- Node.js >= 16
- pnpm

## Installation

```sh
git clone https://github.com/qmotas/appsync-serverless-poc.git
```

```sh
cd appsync-serverless-poc
pnpm install
```

## Deployment

認証情報を設定（AWS CLIで`aws configure`してある場合は不要）

```sh
pnpm serverless config credentials --provider aws --key xxx --secret yyy
```

```sh
pnpm serverless deploy
```
