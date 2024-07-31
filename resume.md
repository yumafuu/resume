---
stylesheet: https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/2.10.0/github-markdown.min.css
body_class: markdown-body
css: |-
  .markdown-body { font-size: 10px; }
---

# 職務経歴書

## SNS

[GitHub](https://github.com/yumafuu) | [X(Twitter)](https://x.com/yuma_katameoome)

## 基本情報

バックエンドの機能開発に加えて、インフラの構築・運用、CI/CDの構築、モニタリングの構築などを行ってきました。
バックエンド、インフラをメインの技術スタックですが、フロントエンドの実装経験もあります。


Platform Engineeringに関心があり、業務効率化や信頼性・DX向上のためのツールを作成してGitHubで公開したり、プラクティスをZennの記事として公開したりしています。

**Zenn**
- [mailpitでメール送信のテストをする with Go](https://zenn.dev/ispec_inc/articles/mailpit-introduction)
- [Postman代替のCLIツール「Ain」の紹介](https://zenn.dev/ispec_inc/articles/ain-introduction)
- [ecspressoで作るRDSの踏み台Fargate](https://zenn.dev/ispec_inc/articles/ecspresso-bastion)

**GitHub**
- [yumafuu/docker-build-ecr-push-action: Build and push a Docker image to Amazon ECR with Buildx cache.](https://github.com/yumafuu/docker-build-ecr-push-action)
- [yumafuu/s1m: TUI Application for AWS Systems Manager Parameter Store](https://github.com/YumaFuu/s1m)

## 職務経歴

| 在籍期間         | 企業名                               | ポジション                            |
|------------------|--------------------------------------|---------------------------------------|
| 2019-9 / 現在    | [ispec inc](https://ispec.tech/)     | バックエンド・インフラエンジニア→VPoE |
| 2019-1 / 2019-07 | 株式会社ラビッツ                     | インターン                            |

## 株式会社ラビッツ

開発者3名程度のチームでRuby on Railsを使ったエンジニア転職サイトの開発に従事。
担当はバックエンドとフロントエンドで機能単位での開発を行った。

**技術スタック**
- Ruby on Rails
    - ERB
    - [Bootstrap](https://getbootstrap.jp/)

- AWS
    - EC2
        - Capistrano
    - RDS


## ispec inc

バックエンド・インフラをメインに担当。その他、簡単なフロントエンドの実装や業務効率化のための社内ツールの開発も行っている。

受託開発で10を超える様々な領域でのアプリケーションのゼロイチ開発を経験。

一部抜粋して記載する。(順不同)

### JamRoll

インフラエンジニアとして参画。

EKSを用いてk8sクラスターの構築・運用やCI/CDの整備などを担当。

**技術スタック**
- AWS
  - EKS
    - helm
    - ArgoCD
    - [external-secrets](https://github.com/external-secrets/external-secrets)
  - Aurora (MySQL)
  - ALB
- CircleCI


### Nursebe

バックエンド・インフラエンジニアとして参画。TypeScriptを用いたAPIの設計・開発とAWSを用いたインフラ構築を行った。
開発リソースをできるだけ減らしながら、スケーラブルなアプリケーションを作ることを目指し、バックエンドとフロントエンドでTypeScriptを採用し、インフラにAWS App RunnerとAurora Serverlessを採用した。

**技術スタック**
- AWS
    - AWS App Runner
    - Amplify Hosting
- GitHub Actions
- NestJS
    - TypeScript
    - [Prisma](https://www.prisma.io/)

### コミュニティ向けQ&Aアプリ
ライブ配信コミュニティの向けQ&Aアプリのバックエンド・インフラ構築・監視基盤を担当しました。

Ruby on Railsを用いたAPIの設計・開発とAWSを用いたインフラ構築を行いました。

**技術スタック**
- AWS
    - ECS
        - [ecspresso](https://github.com/kayac/ecspresso)
        - Fargate
    - Aurora Serverless V2
        - MySQL
    - Lambda
        - [lambroll](https://github.com/fujiwara/lambroll)
    - Amplify Hosting
    - OpenSearch
        - クラスタの構築と全文検索の実装
- Ruby on Rails
    - RSpec
    - [dry-rb](https://dry-rb.org/)
- GitHub Actions
- Datadog
    - Datadog Logs

### 不動産向け退去立ち会い管理アプリ

LINE Botを用いた不動産向け退去立ち会い管理アプリのバックエンド・インフラ・フロントエンドを担当しました。

**技術スタック**
- AWS
    - Terraform
    - ECS
        - Fargate
    - Aurora
        - MySQL
    - Amplify Hosting
- LINE Bot
    - Messaging API
- Go
    - Gin
    - [line-bot-sdk-go](https://github.com/line/line-bot-sdk-go)
- Vue
    - [Nuxt](https://nuxt.com/)
    - [Vuetify](https://vuetifyjs.com/ja/)

### PHPのレガシーシステムのUIリプレイス&デプロイ

PHPで書かれたレガシーシステムのコードを引き継ぎUIの改修とDockerfile作成とAWSへのデプロイを行いました。

**技術スタック**
- AWS
    - ECS
        - Fargate
    - RDS
        - MySQL
- UI
    - PHP
    - [Tailwind CSS](https://tailwindcss.com/)

### 業務効率化ツール

社内のトイル削減のために以下のようなツールを開発しています。
- 勤怠情報を取得しダッシュボードに表示するアプリ
- 採用媒体からのメールを受信・パースしてSlackに通知するツール

**技術スタック**
- [Deno Deploy ](https://deno.com/deploy)
- [Hono - Ultrafast web framework for the Edges](https://hono.dev/)
- Slack Api
- [Puppeteer](https://pptr.dev/)
- [Pipedream](https://pipedream.com/)


### その他プロジェクト

GoのAPI開発、インフラ構築、CI/CDの構築、モニタリングの構築など、様々なプロジェクトにスポットで参画しました。

## OSS活動

OSSに貢献したいと思いがあり、わずかですが以下のような活動を行っています。


### TerraformのモジュールやGithub ACtionsのパッケージの公開

社内で頻繁に使われていて、汎用的なものはGitHubで公開するようにしています。

| 作成物                                                                                                  | 説明                                                                                         |
|---------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| [ispec-inc/aws-oidc-github-terraform](https://github.com/ispec-inc/aws-oidc-github-terraform)           | AWSのOIDC認証を使ったGitHub Actionsのワークフローでのデプロイを行うためのTerraformモジュール |
| [ispec-inc/aws-ecr-terraform](https://github.com/ispec-inc/aws-ecr-terraform)                           | AWS ECRのリポジトリを作成するためのTerraformモジュール                                       |
| [ispec-inc/terraform-backend-cfn-template](https://github.com/ispec-inc/terraform-backend-cfn-template) | Terraformのバックエンドを構築するためのCloudFormationテンプレート                            |
| [yumafuu/docker-build-ecr-push-action](https://github.com/yumafuu/docker-build-ecr-push-action)         | DockerイメージをビルドしてECRにプッシュするGitHub Actionsのアクション                        |

### aquaへのパッケージ追加

CLIツールのパッケージマネージャーである[aqua](https://aquaproj.github.io/)にパッケージを追加するようにしています。
- [Commits · aquaproj/aqua-registry](https://github.com/aquaproj/aqua-registry/commits?author=yumafuu)

