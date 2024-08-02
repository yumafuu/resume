# 職務経歴書

石川湧馬（いしかわゆうま）

[GitHub](https://github.com/yumafuu) | [X(Twitter)](https://x.com/yuma_katameoome)

## 基本情報

主にバックエンドの機能開発とAWSとコンテナを活用したインフラの構築・運用、CI/CDの構築、モニタリング基盤の構築などを行ってきました。また、簡単なフロントエンドの実装経験もあります。

SREやPlatform Engineeringに関心があり、業務効率化や信頼性・DX向上に取り組んでいます。

また、上記のためのツールを作成してGitHubで公開したり、プラクティスをZennの記事として公開したりしています。

**Zenn**
- [mailpitでメール送信のテストをする with Go](https://zenn.dev/ispec_inc/articles/mailpit-introduction)
- [Postman代替のCLIツール「Ain」の紹介](https://zenn.dev/ispec_inc/articles/ain-introduction)
- [ecspressoで作るRDSの踏み台Fargate](https://zenn.dev/ispec_inc/articles/ecspresso-bastion)

**GitHub**
- [yumafuu/docker-build-ecr-push-action: Build and push a Docker image to Amazon ECR with Buildx cache.](https://github.com/yumafuu/docker-build-ecr-push-action)
- [yumafuu/s1m: TUI Application for AWS Systems Manager Parameter Store](https://github.com/YumaFuu/s1m)

## 職務経歴

| 在籍期間           | 企業名                                 | ポジション                                 |
| ------------------ | -------------------------------------- | ------------------------------------------ |
| 2019-9 / 現在      | [ispec inc](https://ispec.tech/)       | バックエンド・インフラエンジニア→VPoE →SRE |
| 2019-1 / 2019-07   | 株式会社ラビッツ                       | インターン                                 |

## 株式会社ラビッツ

Ruby on Railsを使ったエンジニア転職サイトの開発にインターンとして参画しました。
担当はバックエンドとフロントエンドで機能単位での開発を行いました。

**技術スタック**
- Ruby on Rails
    - ERB
    - [Bootstrap](https://getbootstrap.jp/)

- AWS
    - EC2
    - RDS


## ispec inc

受託開発で10を超える様々な領域でのアプリケーションのゼロイチ開発を経験しました。

Go、Ruby、TypeScriptを用いたバックエンドの機能開発、Terraformを使ったIaCの導入やセキュリティ担保、CI/CDの構築、Datadogを用いた監視基盤の構築などを行っています。

Vue、Reactを使ったフロントエンドの実装とTailwind CSSやVuetifyを使ったデザインの実装も経験があります。

また採用活動も携わって、カジュアル面談や技術面談を通じてエンジニアの採用を行いました。

担当したプロジェクトを一部抜粋して記載します。(順不同）


### JamRoll

[JamRoll (ジャムロール) | AIが自動で録画・文字起こし・解析](https://jamroll.poetics-ai.com/)

インフラエンジニアとして参画し、EKSを用いてk8sクラスターの構築・運用やCI/CDの整備などを担当しました。

ArgoCDを使ったGitOpsの導入や、社内での採用経験が豊富なSSM Parameter Storeと連携ができるexternal-secretsを使ったシークレット管理の導入を行いました。


**技術スタック**
- AWS
  - EKS
    - [Helm](https://helm.sh/)
    - [Argo CD | Argo](https://argoproj.github.io/cd/)
    - [external-secrets](https://github.com/external-secrets/external-secrets)
  - Aurora (MySQL)
- CircleCI


### Nursebe

[ナースビー｜看護師のための、ぴえん相談室](https://nursebe.jp/)

バックエンド・インフラエンジニアとして参画。TypeScriptを用いたAPIの設計・開発とAWSを用いたインフラ構築を行った。
開発リソースをできるだけ減らしながら、スケーラブルなアプリケーションを作ることを目指し、バックエンドとフロントエンドでTypeScriptを採用し、インフラにAWS App RunnerとAurora Serverlessを採用した。

**技術スタック**
- AWS
    - AWS App Runner
    - Amplify Hosting
- GitHub Actions
- [NestJS](https://nestjs.com/)
    - TypeScript
    - [Prisma](https://www.prisma.io/)

### コミュニティ向けQ&Aアプリ
ライブ配信コミュニティの向けQ&Aアプリのバックエンド・インフラ構築・監視基盤を担当しました。

Ruby on Railsを用いたAPIの設計・開発とAWSを用いたインフラ構築を行いました。

**技術スタック**
- AWS
    - ECS
        - [ecspresso](https://github.com/kayac/ecspresso)
    - Aurora Serverless V2
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

### 医療クリニック向け予約管理アプリ

医療クリニック向けの予約管理アプリの認証基盤の実装と・インフラ、監視基盤の構築を担当しています。

Datadogを導入してより詳細な監視を行い、信頼性の高いアプリケーションを目指しています。

**技術スタック**
- AWS
    - Terraform
    - ECS
    - Aurora Serverless V2
- Datadog
    - Datadog APM
    - Datadog Logs
- Go


### 不動産向け退去立ち会い管理アプリ

LINE Botを用いた不動産向け退去立ち会い管理アプリのバックエンド・インフラ・フロントエンドを担当しました。

**技術スタック**
- AWS
    - Terraform
    - ECS
    - Aurora
    - Amplify Hosting
- LINE Bot
    - Messaging API
- Go
    - [line-bot-sdk-go](https://github.com/line/line-bot-sdk-go)
- Vue
    - [Nuxt](https://nuxt.com/)
    - [Vuetify](https://vuetifyjs.com/ja/)

### PHPのレガシーシステムのUIリプレイス&デプロイ

PHPで書かれたレガシーシステムのコードを引き継ぎUIの改修とDockerfile作成とAWSへのデプロイを行いました。

**技術スタック**
- AWS
    - ECS
    - RDS
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

## 個人活動

### TerraformのモジュールやGitHub ACtionsのパッケージの公開

社内で頻繁に使われていて、汎用的なものはGitHubで公開するようにしています。

| 作成物                                                                                                  | 説明                                                                                         |
|---------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| [ispec-inc/aws-oidc-github-terraform](https://github.com/ispec-inc/aws-oidc-github-terraform)           | AWSのOIDC認証を使ったGitHub Actionsのワークフローでのデプロイを行うためのTerraformモジュール |
| [ispec-inc/aws-ecr-terraform](https://github.com/ispec-inc/aws-ecr-terraform)                           | AWS ECRのリポジトリを作成するためのTerraformモジュール                                       |
| [ispec-inc/terraform-backend-cfn-template](https://github.com/ispec-inc/terraform-backend-cfn-template) | Terraformのバックエンドを構築するためのCloudFormationテンプレート                            |
| [yumafuu/docker-build-ecr-push-action](https://github.com/yumafuu/docker-build-ecr-push-action)         | DockerイメージをビルドしてECRにプッシュするGitHub Actionsのアクション                        |

### 登壇経験

Amazon ECSのデプロイツールであるecspressoの活用事例についてecspresso MeetUpにて登壇しました。
- [JAWS-UG コンテナ支部 #24 ecspresso MeetUp - connpass](https://jawsug-container.connpass.com/event/285124/)
- [ecspresso MeetUpで登壇しました！ #jawsug\_ct](https://zenn.dev/ispec_inc/articles/ecspresso-lt)
