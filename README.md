# 職務経歴書

## 基本情報
|key|value|
|---|---|
|Birth| 1993/06/29|
|Family| 未婚・子供なし|
|Location|東京都|
|Mail| ksg.kamina93@gmail.com|

## 趣味
- 映画鑑賞
  - オールジャンル好き中でも好きなのはアクション
  - 1番好きなのエクスペンダブルズシリーズ
  - 土日はよく動画配信サービスで映画を探している
- ゲーム
  - オールジャンルやります。（コンシューマーもPCもスマホも）
  - FPSが得意、大会出場経験有
  - なんだかんだ一番好きなのはシミュレーションゲーム
- アニメ
  - 1シーズンひととおりは見て、何個か見ます
  - 地方なので動画配信サービスだより
- 日本酒
  - たまに蔵見学とか行きます
  - 日本酒にあう料理を探すのが好き
  - 飲み比べで銘柄当てられます

### スキルマップ
理解度基準

|記号|基準|
|---|---|
|◎|一人でできる|
|◯|大体理解しているが、不安な部分がある|
|△|触ったことがある|
---
|言語|期間|理解度|
|---|---|---|
|PHP|2年|◯|
|Java|1年|◯|
|Ruby|1年|◯|
|COBOL|半年|△|
|Objective-C|1か月|△|
|Python||△|
|Golang||△|
|C||△|
|JavaScript|3年|◯|
|HTML5|3年|◎|
|CSS|3年|◎|
---
|フレームワーク|期間|理解度|
|---|---|---|
|CakePHP|半年|◯|
|Laravel|1年|◯|
|Ruby on Rails|1年|◯|
|Django|3か月|△|
|Spring Fremework|半年|△|
|JQuery|2年|◯|
|React||△|
|Bootstrap 3|2年|◎|
|Bootstrap 4|半年|◯|
|Pure|半年|◯|
---
|AWS Service|期間|理解度|
|---|---|---|
|VPC|2年|◯|
|Subnet|2年|◯|
|SecurityGroup|2年|◯|
|EC2|2年|◯|
|AutoScaling(EC2)|半年|◯|
|ALB ELB|2年|◯|
|RDS|2年|◯|
|RDS(Aurora)|1年|◯|
|DynamoDB|半年|◯|
|ElastiCache|1年|◯|
|S3 Bucket|2年|◯|
|CloudFront|2年|◯|
|WAF & Shield|3か月|◯|
|Certificate Manage|1年|◯|
|Route53|1年|◯|
|CloudWatch|1年|◯|
|ECS|3か月|△|
|ECR|3か月|△|
|CodeBuild|3か月|△|
|CodePipeline|3か月|△|
|Lambda|3か月|△|
|API Gateway|3か月|△|
|IAM|1年|◯|
|Role|1年|◯|
|Policy|1年|◯|
---
|その他スキル|期間|理解度|
|---|---|---|
|Linux|2年|◯|
|Windows|5年|◯|
|Mac|2年|◯|
|Mysql|1年半|◯|
|MariaDB|半年|◯|
|Postgresql|1年|◯|
|Redash|3か月|◯|
|Git|2年|◯|
|CVS|1年|◯|
|CircleCI|1年|◯|
|Ansible|1年|◯|
|CloudFormation|1年|◯|
|Terraform|1年|◯|
|ElasticSearch|1年半|◯|
|Kibana|1年半|◯|
|Elastic Cloud|1年|◯|
|Sentry|半年|◯|
|LogDNA|半年|◯|
|Mackerel|3か月|◯|
|New Relic|3か月|◯|
|Datadog|3か月|◯|
|Docker|1年|◯|

## やったことはないが興味があるもの
- GCP
- k8s
- 機械学習
- VR

## 登壇歴
- 社内
  - LT機械学習の初め方
  - LT CloudFrontでの推奨環境構築
- 社外
  - なし

## 受賞歴
- 社内
  - なし
- 社外
  - なし

## 職務経歴

### 2016/04 - 2019/07 : 合同会社DMM.com

職務: エンジニア

#### 献立提案アプリのフルリプレイス

- 元々、バックエンド側がPythonで動いていたものをRuby on Railsで一新
- サーバがさくらのクラウドを使っていたのでAWSで再構築（月額のサーバ費用が200万程から50万程まで削減）

#### アダルトイベント特設サイト改修

- CVSを使用してコード管理
- PHPを使用、社内のログインAPIを使用
- 前年までのと違いページの遷移方法が変わったので対応

#### 社内日報改修

- 手入力メインで画面をGoogleカレンダーのような見た目の画面に改修
- API側でPHP Laravelを使用、フロント側をJavaScript、JQueryで実装

#### 貸出自転車サーバの構築
 
 - AWSにて高負荷対策サーバの構築
 - EC2、AutoScalingを使用
 - DBはAuroraを使用
 - 静的ファイルはCloudFrontで配信する形に

#### 大型ブログのデプロイ環境改修

- Pythonでデプロイ用のバッチを作成
- 作成したバッチをJenkinsで起動させるジョブを作成

#### 運用チームが使用しているツールの修正対応

- 機能一覧には載っている作られていない機能の追加
- 機能自体はあるが動いていない機能のバグ修正
- 運用チームから出た要望による機能修正

#### イベント会場のログ監視環境、wifi環境の構築

- JANOGの会場のネットワーク環境を構築（回線を引っ張ったり、スイッチを設定し、配置したり）
- Nginx + flentd + Elasticsearch + kibanaでログを可視化
- 可視化を行いどこにアクセスが集中しているかを確認、Alertで感知

#### 社内運用チームの業務改善ヒアリング

- 運用チームのメンバーに一人一人ヒアリングを行い、業務内容をスプレッドシートにまとめ可視化

### 2016/07 - 現在 : 株式会社IGNIS（株式会社スタジオキング）