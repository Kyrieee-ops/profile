# Profile
- プロフィール
    - [基本情報](#基本情報)
    - [AWS認定資格](#aws認定資格)
    - [Linux認定資格](#linux認定資格)
    - [保有スキル](#保有スキル)
    - [職務経歴詳細](#職務経歴詳細)
    - [業務外活動](#業務外活動)
    - [技術スタック](#技術スタック)

## 基本情報
| key | value |
| --- | --- |
| 名前 | Yuki.Izumi |
| 生年月日 | 1986/06/16 |
| Twitter | [@kyrieee_a](https://twitter.com/kyrieee_a) |
| 個人ブログ | [kyrieee.com](kyrieee.com) |
| Qiita | [@triple321jhango](https://qiita.com/triple321jhango) |

## AWS認定資格
| 認定日 | 認定資格 |
| --- | --- |
| 2022.04.30 | AWS Certified Solutions Architect - Associate (SAA) |

## Linux認定資格
| 認定日 | 認定資格 |
| --- | --- |
| 2023.05.13 | LinuC-1 |

## 職務経歴詳細
### 株式会社エージェントグロー(2022/11~現在)
### 職務内容
金融系基盤更改案件にて運用設計エンジニアとして従事。
主にインシデント管理に関する設計担当として以下を担当

運用設計書 / 運用手順書作成
- オンプレ基盤上のインフラ監視(ログ監視/ジョブ監視/プロセス監視/死活監視/ウイルス監視/不正接続/セキュリティインシデント検知/ファイアウォールログ管理/初動対応 -> インシデント管理システムへ連携するまでの流れ)
- インシデント/障害対応(監視システムによるアラート検知、およびユーザー問い合わせからのインシデント/障害判定 -> その後の影響確認/調査/対応/復旧までの流れ)
- ウイルス対応(ユーザー端末/サーバ/メールなどによるアラート検知およびユーザー問い合わせからのインシデント/障害判定 -> その後の影響確認/調査/対応/復旧までの流れ)
- プロジェクトの途中からはサブリーダーとして従事しました。

### サブリーダーとしての実務
業務運用手順書(システム利用者管理運用、サポートデスク運用などを指す)作成における
- ドキュメント作成における運用ルール化 -> フォーマット作成、記述ルールの統一
- タスク管理ツール導入 -> Plannerにて進捗管理を提案
- メンバー教育 (設計メンバーおよびオペレータへのOJT)

上記を担当しました。

### 株式会社DONUTS(2020/12~2022/10)
クラウド型電子カルテの自社開発している企業
### 職務内容
クラウド型電子カルテのクライアントへの導入および社内SEとして従事。
主にクラウド型電子カルテのプラグインツールの導入、運用、障害対応、社内運用業務の自動化などを担当
- クライアント端末へのプラグインツールのセットアップ
- クライアント端末とネットワークセグメントの異なる他社端末へのネットワークルーティング設定(PowerShell, Terminalなど)設定
- ネットワーク疎通確立後のプラグインツールを使用したファイル連携テスト
- 社内運用業務効率化のため、GASを使用した運用自動化を実施
- Notionを導入し、顧客管理ツール化、社内Wiki化などを構築
    - スケジュール管理、進捗管理などの業務の見えるかを実現
- 仮想Linuxを用いたレセプトコンピュータのシステム構築
- 利用した技術スタック
    - 言語: GAS, VBA
    - OS: Ubuntu, Windows10, Mac
    - ミドルウェア: 
        - DB: PostgreSQL
    - 各種ツール: 
        - Notion



## 業務外活動
###  [AWS認定資格 ソリューションアーキテクトアソシエイトの教科書: 合格へ導く虎の巻 Kindle版](https://www.amazon.co.jp/dp/B0BCPNZ9GJ?&linkCode=sl1&tag=kyrieee-22&linkId=de21025e80e1f7bb93c947493f8b549d&language=ja_JP&ref_=as_li_ss_tl) 
上記の執筆に携わりました。
 - 累計ダウンロード数は15,000冊に到達

### 本業務を通して得られたこと: 
ELB, Auto Scaling, Amazon EventBride, AWS Systems Managerの執筆に携わりました。
見やすいドキュメント作成をすることが可能です。
インプットだけでなく、意識的にアウトプットを日常から実施することで、ドキュメント作成(設計書など)においては特に役立てるかと思います。

### AWSハンズオン本作成プロジェクト 執筆に携わっています。
使用ツール: 

- Notion, GitHub, Googleドキュメント, Googleスライド

詳細: 

- Notion: 
    - Wikiなどを作成しナレッジの共有
    - プロジェクト管理
- GitHub (コマンド): 
    - ブランチを切りMarkdown形式で作成
    - プルリクエストでレビュー依頼

具体的に何をやっているか:

- メイン執筆者から依頼のあった部分執筆, 図解作成、改善, 文章構成確認、校正

- 担当したドキュメント: 
    - DBeaverを使用したプライベートサブネットに配置したEC2を経由したRDS接続 (執筆)
    - CloudFormationの解説 (執筆)
    - パッチ適用で既知の脆弱性に対策できるが、未知の脆弱性に対策できない (図解)
    - Amazon Inspectorがどういう仕組みで脆弱性をチェックしているか (執筆)
    - Systems ManagerのRun Commandでできること ログをS3へ出力するためには (執筆)
    - Iacツールについて Terraformとは、Terraformの特徴、CloudFormationとの比較 (執筆)

### 本業務を通して得られたこと: 
- AWS公式ドキュメントの読み込み、そこから読者に対して解釈しやすい文章作成をしますが、まずAWS公式ドキュメントを熟読 -> 自分なりに解釈した文章にアウトプットをすることで、担当したAWSリソースの深堀りができたことで、知識の定着させることができました。
併せて、ハンズオンの手順を作成するドキュメントもありますので、構築する作業も併せて実現できました。



## 技術スタック
### 実務経験あり
- OS: 
    - Windows10
    - MacOS
    - Ubuntu

- データベース: 
    - Oracle

- 言語: 
    - VBA
    - GAS
    - SQL

- ツール
    - Git
    - GitHub
    - Notion

### 実務経験はないが独学している、または個人で使用経験あり

- OS: 
    - Red Had Linux

- データベース:
    - MySQL

- AWS: 
    - Amazon Elastic Compute Cloud (EC2)
    - Amazon Relational Database Service (RDS)
    - Amazon Virtual Private Cloud (VPC)
    - Amazon CloudFormation
    - Amazon VPC Endpoint
    - Amazon Simple Storage Service (S3)
    - Amazon Elastic Load Balancing (ELB)
    - Amazon Route 53
    - Amazon Inspector
    - Amazon Systems Manager
        - State Manager
        - Run Command

- コンテナ: 
    - Docker

- 言語: 
    - PHP
    - HTML
    - CSS

- その他: 
    - Nginx
    - Virtual Box
    - Terraform