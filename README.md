# 職務経歴書

## 基本情報

| key     | value                                                                                      |
| ------- | ------------------------------------------------------------------------------------------ |
| Name    | toiki/追木智明（おいき ともあき）                                                          |
| Age     | 1994/11/28 生まれ [年齢](https://www.google.com/search?q=1994%E5%B9%B4+%E5%B9%B4%E9%BD%A2) |
| Twitter | [@kn_prg](https://twitter.com/kn_prg)                                                      |

## スキル

### 言語

- Javascript,Typescript
- Node.js
- Python
- PHP
- C++
  - 競技プログラミングで使用

### フレームワーク

- React.js
  - 簡単な SPA から認証が必要なサービスまで実装経験あり
  - デザインへの興味が薄く、素のCSSは基本的なものしか書けません
- Next.js
  - SSR,SSGでサービスを開発したことがあります
- Vue.js
  - 業務で作成したサービスで利用、あまり詳しくない
- flask
  - 大学での研究や簡単な API の実装に使用

### DevOps

- git
  - 主に github
  - ブランチ戦略としては github-flow,gitworkflows(7)などをベースにプロジェクトごとにカスタム
  - 作業ブランチでは rebase+force push をガンガン使う派
- github action
  - コードの lint,test、サービスの本番環境へのデプロイなど
- Docker
  - dockerfile,docker-compose.yml は細かい部分を調べながら書ける
  - 基本的にローカル開発環境のために利用（凝った使い方はしたことがない）
- アジャイル
  - スクラムらしきものの経験は複数あり
    - プランニングポーカー、スプリントレビュー、デイリースタンドアップなど
    - JIRA を使ってベロシティの管理など
- モブプログラミング
  - 5 人程度のチームで 1 年弱行った経験あり
  - 心理的安全性の向上や Tips の共有などかなり効果があった

### クラウド

#### AWS

- 利用経験ありサービス
  - EC2,ECS,S3,CF,Route53,SQS,SES,SNS,CloudWatch,Lambda,RDS,DynamoDB,API GW,VPC,Secret manager,IAM,cognito など
- クラウドネイティブなシステム構成を考えることができます
- terraform を用いた IaC 経験があります

## 言語

- 日本語
  - ネイティブ
- 英語
  - 簡単な日常会話が出来ます、Listening は比較的得意
  - TOEIC: 730 点
- 中国語
  - 日常会話レベル

## こだわり

- 世の中にインパクトがあるサービス
  - すでに定評があり、これからどんどん開発を進めていくフェーズにあるサービスが良いです
  - 逆にサービスの方向性が定まっておらず、すぐに状況が変わるサービスは好みません
- 心理的安全性の高いチーム
  - チームメンバーが指示なくとも自走し、お互いに高め合いながら開発できると良いです
- 技術的な挑戦がしやすい環境
  - 日々刻々と進んでいく技術に取り残されず、挑戦していける環境に身を置きたいです

## 強み

- 競技プログラミングを昔やっていたため、計算量を意識したプログラムが書けます
- かなり時間にシビア（遅刻、寝坊をしたことがありません）

## やったことはないが興味があるもの

- Rust
  - Wasm や低レイヤの実装につかいたい
- エンジニアが働きやすい環境をつくること
- 低レイヤの実装（エミュレーターとか書いてみたい）

## 職務経歴

### 2021/1 - 現在 : 株式会社 AVILEN

職務: Web エンジニア

#### 自社 AutoML サービス構築

- チームの規模: 5,6 人(主な役割: 開発メンバー＋サブリーダー的な立ち位置)
- オンプレに導入されているサービスの SaaS 化と同時にインフラ構成刷新
- サービスの技術的仕様決め、チームが円滑に回るようにサポートなどを行っていた
- 主要技術: Python(3.8), React+Typescript, AWS(ECS,APIGW,Lambda,SQS,DynamoDB,RDS,S3,CF など),Terraform

#### 講座受講者管理システム

- チームの規模: 5,6 名(主な役割:開発メンバー＋技術サポート)
- 会社が提供している講座の受講から受講者の管理までを行うサービスの機能開発、技術サポート、インフラ構成移行（概要:EC2+RDS 構成から CF+ECS,S3 構成に変更）
- 副業時代から合わせて、1 年半程度コミット
- 主要技術：PHP,AWS(ECS,S3,RDS,CF,Lambda,Elasticache),Docker,Vue.js+Typescript

#### web エンジニア採用業務

- 採用のフローやコーディングテスト作成、採用面談〜合否判定までを担当
- インターン生の募集リニューアルなどを行った

### 2019/4 - 2020/12: ヤフー株式会社

職務: エンジニア

#### レガシーサービスの保守

- チームの規模: 3 人程度(主な役割: 開発メンバー)
- バグ修正、機能開発など
- ユーザーから正常に利用できないという報告を受け、UA やアクセスログから原因を探ったりしていた
- 主な技術: PHP,Scala,Perl,RHEL7,Chef,Jenkins

#### レガシーサービスのリニューアル

- チームの規模: 12 人程度(主な役割: 開発メンバー)
- 旧システムからモダンな言語、フレームワークを用いて基本モブブログラミングで再実装
- 主にフロントエンドに従事し、Next.js+Typescript を用いて SSR なアプリケーションを実装
- リニューアル版にロガーを導入し、必要箇所へのログの実装を行った
  - A/B テストの定義,旧版とリニューアル版 PV,CVR,Click 数などの比較など
- リニューアル版の新規機能開発を 1 週間スプリントで行い、毎週のように行った施策の効果を検証
- 主な技術: Next.js,Typescript,Github Actions,社内の独自フレームワーク複数
