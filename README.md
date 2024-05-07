# 職務経歴書

- [基本情報](#基本情報)
- [学歴・職歴](#学歴職歴)
- [経験領域](#経験領域)
  - [エンジニアリング](#エンジニアリング)
  - [その他](#その他)
- [スキル](#スキル)
- [職務経歴](#職務経歴)
- [自己 PR](#自己pr)
- [受賞](#受賞)

## 基本情報

**木村 優斗 | Kimura Yuto**

| 媒体 | リンク                                                         |
| ---- | -------------------------------------------------------------- |
| blog | [biosugar0.com](http://biosugar0.com)                          |
| zenn | [biosugar0.com](https://zenn.dev/biosugar0)                    |
| x    | [https://twitter.com/biosugar0](https://twitter.com/biosugar0) |
| mail | [Gmail](biosugar0@gmail.com)                                   |

## 学歴・職歴

| 年月    | 職歴                                                          |
| ------- | ------------------------------------------------------------- |
| 2019.03 | 東京電機大学大学院 理工学研究科 生命理工学専攻 修士課程 修了  |
| 2019.04 | 都内スタートアップ企業 バックエンドエンジニアとして入社       |
| 2019.06 | 都内スタートアップ企業 退社                                   |
| 2019.07 | 株式会社スマートショッピング バックエンドエンジニアとして入社 |
| 2021.11 | 株式会社スマートショッピング SRE 部に異動                     |

### 学位

修士(工学) &#124; 情報分子生物学専攻

## 経験領域

### エンジニアリング

- バックエンド開発
- マイクロサービス開発
- ドメイン駆動開発
- Infrastructure as Code(Terraform)
- クラウドインフラ構築(AWS)
- Kubernetes(EKS)構築、運用
- Site Relicability Engineering(SRE)
- LLM を活用したアプリケーション開発

### その他

- SRE チーム立ち上げ
- 開発組織の DevOps 推進

## スキル

<summary><strong>プログラム言語</strong></summary>

| 言語       | 経験年数 |
| ---------- | -------- |
| Go         | 4 年〜   |
| Bash       | 5 年〜   |
| Python     | 2 年〜   |
| TypeScript | 1 年〜   |

<summary><strong>その他利用経験</strong></summary>

| 名前           | 経験年数 |
| -------------- | -------- |
| Kubernetes     | 4 年〜   |
| Docker         | 4 年〜   |
| terraform      | 3 年〜   |
| GitHub Actions | 2 年〜   |
| Datadog        | 3 年〜   |
| Vim            | 7 年〜   |

等

## 職務経歴

### 都内スタートアップ企業 （2018.08 - 2018.10, 2019.04 - 2019.06）

#### バックエンドエンジニア

- パブリッククラウド環境構築・運用自動化プラットフォームのバックエンド開発
  - GCP のインフラ環境構築を支援する機能の開発
  - マイクロサービス群が使用する RBAC サービスの開発
  - ブラウザベースの SSH セッションマネージャの開発

### 株式会社スマートショッピング （2019.07 〜 現在）

#### バックエンドエンジニア（2019.07 〜 2021.11）

- 自社在庫管理 SaaS のフルリプレイス
  - EC2 から EKS への移行
  - マイクロサービス開発
  - コンテナ化
  - Github Actions を用いた GitOps 構築
  - terraform 化
- 在庫管理 SaaS の発注機能拡張
- 社内向けのサービスヘルススコア基盤の構築
- 在庫管理 SaaS への医療機関向け発注方法追加
- 在庫管理 SaaS の発注条件の追加
- Go 製アプリケーションの自動テスト整備(moq の導入、テスト実装、GitHub Actions 設定など)
- 在庫管理 SaaS のパラメーターの一括変更機能開発

#### SRE(2021.11 ~ 現在)

- [SRE チームの再立ち上げ](https://tech.smartshopping.co.jp/ss-new-sre)
  - SRE の役割、ミッションの明文化
  - SRE のプロダクト開発チームとの連携方法の策定
  - SRE ロードマップの作成
- [トイルの計測と可視化](https://tech.smartshopping.co.jp/measure-toil)
- CI/CD 整備
- トイルの削減
- 詳細設計ドキュメントの標準化
- SRE チームの MVV 策定
- インフラ変更のセルフサービス化
- AWS コスト最適化
- 開発生産性の向上を主導し、開発生産性が優れたエンジニア組織を表彰する Findy Team+ Award 2023 を受賞
  - [IoT 在庫管理・工程 DX SaaS の【スマートショッピング】、Findy Team+ Award 2023 を受賞](https://prtimes.jp/main/html/rd/p/000000075.000026042.html)
  - プルリクエストの細分化のため、変更行数が多い場合警告を行う仕組みを作成
  - デプロイ頻度の改善のため、ブランチ戦略の見直しとデプロイフローの簡略化、自動化
  - 課題発見と改善のための定例会のファシリテーション
- 可観測性の強化を目的として構造化ログを導入。共通パッケージの開発を行った
- GitHub Copilot for Business 導入
- OpenAI の組織アカウント整備
- k8s ミドルウェアの GitOps 管理
- 社内 LLM Slack Bot の開発
- Node Local DNS Cache の導入
- サーバーリソースの最適化。Pod のリソース設定を Datadog のメトリクスを元に再設定
- LLM を用いたミーティング議事録の自動生成
- 新規マイクロサービスデプロイ設定のコード化
- Datadog monitor, metrics の terraform 化
- 時系列データベースを利用したインフラ設計・検証
- Google Drive と連携する LLM による議事録生成システムの開発

## 自己 PR

バックエンドエンジニアの経験をベースに、SRE としての運用面まで考えたインフラから CI/CD の整備、バックエンドまでの設計、開発スキルを持っています。
また、運用の自動化など開発者体験の向上への取り組みも得意です。

私はエンジニアとして新しく何かを作ることも好きですが、その本質は運用にあると思っています。
そして SRE やプラットフォームエンジニアリングのような運用にフォーカスしたエンジニアリングが、 Google やメルカリのような大きな企業だけのものではなくスタートアップでこそ威力を発揮するということを示したいため、よりビジネスに効果的なスマートな構成、アプローチはどういうものなのかを探求していきたいです。
スタートアップにおいて、信頼性は高頻度な価値提供とシステムの安定性によって構成されるというポリシーを持っており、現職ではバックエンド実装も把握している SRE としてインフラからサーバーのチューニング、開発体験の向上、組織の生産性向上まで幅広く活動しています。

## 得意なこと

- バックエンド・インフラに関わる開発業務
- Infrastructure as Code
- 運用の自動化

## 得意でないこと

- フロントエンド
- ネイティブアプリケーションの実装・開発

## 副業する場合の希望契約形態

- 準委任契約

## 受賞

### 2021 年 MVP 受賞, 2021-12 &#124; [スマートマットショッピング](https://smartshopping.co.jp/AboutUs)

2021 年一番輝いた従業員に送られる MVP を受賞。

以下のような事項を総合的に評価していただきました。

- 開発環境の改善に対するモチベーション高く、オーナーシップもって検証、共有する姿勢。有用な情報はドキュメントとして横展開され再現性も意識されている
- エンジニア外からの問い合わせを介してお客様の課題や運用上の課題に対し積極的に対応した(エンジニアへの問い合わせのほぼ半分)
- 理想的な SRE チームを構築していくために、現状の課題感と共に、解決のための提案と実行を周囲を巻き込みながら推進した
  など

## 執筆

- [Kubernetes クラスターと同期する、マイクロサービスのためのローカル開発環境](https://tech.smartshopping.co.jp/k8s_microservice)
- [AWS Lambda with Container Image で Playwright を動かす](https://tech.smartshopping.co.jp/lambda-container-playwright)
- [Salesforce の Bulk API を Go から叩く](https://tech.smartshopping.co.jp/salesforce_bulk_go)
- [バックエンドエンジニアから SRE に転向しました](https://www.biosugar0.com/posts/2021/12/to-sre/)
- [トイルの計測とトラッキングを始めました](https://tech.smartshopping.co.jp/measure-toil)
- [Telepresence2 へ移行するためにやったこと](https://tech.smartshopping.co.jp/to-telepresence2)
- [SRE チームの再立ち上げとミッション、ビジョン、バリューを作った話](https://tech.smartshopping.co.jp/ss-new-sre)
- [SRE チームは DevOps に向き合い、開発を加速させる](https://zenn.dev/biosugar0/articles/sre-implements-devops)

## その他

- [初期からプロダクト開発を支えたエンジニアに聞く！スマートショッピングで SRE をする魅力](https://www.wantedly.com/companies/smartshopping/post_articles/513695)
