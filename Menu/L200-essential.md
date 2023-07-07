###### tags: `Microsoft Fabric` `Workshop`

# Microsoft Fabric Workshop (L200-essential, 629min)

Index

- [1. イントロダクション (31min)](#1-イントロダクション-31min)
  - [1.1. L100](#11-l100)
  - [1.2. L200 (31min)](#12-l200-31min)
    - [1.2.1. はじめに (23min)](#121-はじめに-23min)
    - [1.2.2. 基本操作 (6min)](#122-基本操作-6min)
    - [1.2.3. ワークスペース (7min)](#123-ワークスペース-7min)
  - [1.3. L300](#13-l300)
- [2. OneLake (38min)](#2-onelake-38min)
  - [2.1. L100](#21-l100)
  - [2.2. L200 (38min)](#22-l200-38min)
    - [2.2.1. 概要 (17min)](#221-概要-17min)
    - [2.2.2. 機能 (21min)](#222-機能-21min)
  - [2.3. L300](#23-l300)
- [3. Power BI (13min)](#3-power-bi-13min)
  - [3.1. L100](#31-l100)
  - [3.2. L200 (13min)](#32-l200-13min)
    - [3.2.1. 概要 (6min)](#321-概要-6min)
    - [3.2.2. Direct Lake (Preview) (7min)](#322-direct-lake-preview-7min)
  - [3.3. L300](#33-l300)
- [4. Synapse Data Engineering (65min)](#4-synapse-data-engineering-65min)
  - [4.1. L100](#41-l100)
  - [4.2. L200 (65min)](#42-l200-65min)
    - [4.2.1. 概要 (2min)](#421-概要-2min)
    - [4.2.2. レイクハウス (16min)](#422-レイクハウス-16min)
    - [4.2.3. Delta Lake (6min)](#423-delta-lake-6min)
    - [4.2.4. Apache Spark (17min)](#424-apache-spark-17min)
    - [4.2.5. ノートブック (4min)](#425-ノートブック-4min)
    - [4.2.6. チュートリアル (20min)](#426-チュートリアル-20min)
  - [4.3. L300](#43-l300)
- [5. Data Factory (108min)](#5-data-factory-108min)
  - [5.1. L100](#51-l100)
  - [5.2. L200 (108min)](#52-l200-108min)
    - [5.2.1. 概要 (6min)](#521-概要-6min)
    - [5.2.2. コネクタ (8min)](#522-コネクタ-8min)
    - [5.2.3. パイプライン (45min)](#523-パイプライン-45min)
    - [5.2.4. データフロー (28min)](#524-データフロー-28min)
    - [5.2.5. その他/共通 (21min)](#525-その他共通-21min)
  - [5.3. L300](#53-l300)
- [6. Synapse Data Warehouse (88min)](#6-synapse-data-warehouse-88min)
  - [6.1. L100](#61-l100)
  - [6.2. L200 (88min)](#62-l200-88min)
    - [6.2.1. 概要 (37min)](#621-概要-37min)
    - [6.2.2. データの取り込み (7min)](#622-データの取り込み-7min)
    - [6.2.3. 接続とセキュリティ (6min)](#623-接続とセキュリティ-6min)
    - [6.2.4. データの表示 (13min)](#624-データの表示-13min)
    - [6.2.5. データのモデリング (15min)](#625-データのモデリング-15min)
    - [6.2.6. チュートリアル1 (10min)](#626-チュートリアル1-10min)
  - [6.3. L300](#63-l300)
- [7. Synapse Real-Time Analytics (88min)](#7-synapse-real-time-analytics-88min)
  - [7.1. L100](#71-l100)
  - [7.2. L200 (88min)](#72-l200-88min)
    - [7.2.1. 概要 (14min)](#721-概要-14min)
    - [7.2.2. イベントストリーム (20min)](#722-イベントストリーム-20min)
    - [7.2.3. KQL データベース (19min)](#723-kql-データベース-19min)
      - [7.2.3.1. 概要](#7231-概要)
      - [7.2.3.2. データベースとテーブルの作成](#7232-データベースとテーブルの作成)
      - [7.2.3.3. データの取得](#7233-データの取得)
      - [7.2.3.4. Data Factory との接続](#7234-data-factory-との接続)
    - [7.2.4. KQL (25min)](#724-kql-25min)
      - [7.2.4.1. 概要](#7241-概要)
    - [7.2.5. KQL クエリセット (2min)](#725-kql-クエリセット-2min)
    - [7.2.6. OneLake との統合 (3min)](#726-onelake-との統合-3min)
    - [7.2.7. Microsoft Fabric ノートブック からの利用 (2min)](#727-microsoft-fabric-ノートブック-からの利用-2min)
    - [7.2.8. Power BI からの接続 (3min)](#728-power-bi-からの接続-3min)
  - [7.3. L300](#73-l300)
- [8. Synapse Data Science (267min)](#8-synapse-data-science-267min)
  - [8.1. L100](#81-l100)
  - [8.2. L200 (267min)](#82-l200-267min)
    - [8.2.1. 概要 (11min)](#821-概要-11min)
    - [8.2.2. データの準備 (6min)](#822-データの準備-6min)
    - [8.2.3. 実験とモデル (23min)](#823-実験とモデル-23min)
    - [8.2.4. Python (12min) ※Optional](#824-python-12min-optional)
    - [8.2.5. R (46min) ※Optional](#825-r-46min-optional)
    - [8.2.6. Apache Spark (65min)](#826-apache-spark-65min)
      - [8.2.6.1. 概要](#8261-概要)
      - [8.2.6.2. ワークスペース](#8262-ワークスペース)
      - [8.2.6.3. 開発](#8263-開発)
    - [8.2.7. チュートリアル (E2E) (32min)](#827-チュートリアル-e2e-32min)
  - [8.3. L300](#83-l300)
- [9. Data Activator](#9-data-activator)
- [10. 管理者およびガバナンス](#10-管理者およびガバナンス)


---


## 1. イントロダクション (31min)

### 1.1. L100

N/A

### 1.2. L200 (31min)

#### 1.2.1. はじめに (23min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric とは](https://learn.microsoft.com/ja-jp/fabric/get-started/microsoft-fabric-overview) | 4 |
| 2 | [Microsoft Fabric プレビュー情報](https://learn.microsoft.com/ja-jp/fabric/get-started/preview) | 1 |
| 3 | [Microsoft Fabric の用語 - 一般的な用語](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#general-terms) | 1 |
| 4 | [はじめに \| Microsoft Fabric を使用したエンドツーエンドの分析の概要](https://learn.microsoft.com/ja-jp/training/modules/introduction-end-analytics-use-microsoft-fabric/1-introduction) | 1 | Training |
| 5 | [Microsoft Fabric を使用してエンドツーエンドの分析を調べる \| Microsoft Fabric を使用したエンドツーエンドの分析の概要](https://learn.microsoft.com/ja-jp/training/modules/introduction-end-analytics-use-microsoft-fabric/2-explore-analytics-fabric) | 5 | Training || 6 | [データ チームと Microsoft Fabric \| Microsoft Fabric を使用したエンドツーエンドの分析の概要](https://learn.microsoft.com/ja-jp/training/modules/introduction-end-analytics-use-microsoft-fabric/3-data-team) | 3 | Training |
| 7 | [Microsoft Fabric を有効にして使用する \| Microsoft Fabric を使用したエンドツーエンドの分析の概要](https://learn.microsoft.com/ja-jp/training/modules/introduction-end-analytics-use-microsoft-fabric/4-use-fabric) | 6 | Training |


**Supplements**

* [知識チェック \| Microsoft Fabric を使用したエンドツーエンドの分析の概要](https://learn.microsoft.com/ja-jp/training/modules/introduction-end-analytics-use-microsoft-fabric/5-knowledge-check)

#### 1.2.2. 基本操作 (6min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric Home からアイテムとアクションに移動する方法の概要](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-home) | 3 |
| 2 | [Fabric ヘルプ ウィンドウの使用方法](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-help-pane) | 1 |
| 3 | [コンテンツの検索・並べ替え・フィルター処理](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-search) | 1 |
| 4 | [Fabric 設定 ウィンドウ](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-settings) | 1 |

#### 1.2.3. ワークスペース (7min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [ワークスペース](https://learn.microsoft.com/ja-jp/fabric/get-started/workspaces) | 3 |
| 2 | [ワークスペースの作成](https://learn.microsoft.com/ja-jp/fabric/get-started/create-workspaces) | 2 |
| 3 | [Microsoft Fabric のワークスペースのロール](https://learn.microsoft.com/ja-jp/fabric/get-started/roles-workspaces) | 1 |
| 4 | [ワークスペースへのアクセス権をユーザーに付与する](https://learn.microsoft.com/ja-jp/fabric/get-started/give-access-workspaces) | 1 |

### 1.3. L300

N/A


---


## 2. OneLake (38min)

### 2.1. L100

N/A

### 2.2. L200 (38min)

#### 2.2.1. 概要 (17min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [OneLake](https://learn.microsoft.com/ja-jp/fabric/onelake/onelake-overview) | 3 |
| 2 | [Microsoft Fabric の用語 - OneLake](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#onelake) | 1 |
| 3 | [はじめに \| Microsoft Fabric でのレイクハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-lakehouses/1-introduction) | 1 | Training |
| 4 | [Microsoft Fabric Lakehouse を探索する \| Microsoft Fabric でのレイクハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-lakehouses/2-fabric-lakehouse) | 5 | Training |
| 5 | [Microsoft Fabric Lakehouses を使用する \| Microsoft Fabric でのレイクハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-lakehouses/3-work-lakehouse) | 6 | Training |
| 6 | [OneLake を使用してレイクハウスを作成する](https://learn.microsoft.com/ja-jp/fabric/onelake/create-lakehouse-onelake) | 1 | Tutorial |

**Supplements**

* [演習 - Microsoft Fabric Lakehouse でデータを作成して取り込む \| Microsoft Fabric でのレイクハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-lakehouses/4-exercise-lakehouse)
* [知識チェック \| Microsoft Fabric でのレイクハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-lakehouses/5-knowledge-check)

#### 2.2.2. 機能 (21min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [ショートカット](https://learn.microsoft.com/ja-jp/fabric/onelake/onelake-shortcuts) | 6 |
| 2 | [ショートカットの作成](https://learn.microsoft.com/ja-jp/fabric/onelake/create-onelake-shortcut) | 3 |
| 3 | [ADLS Gen2 のショートカットの作成](https://learn.microsoft.com/ja-jp/fabric/onelake/create-adls-shortcut) | 1 |
| 4 | [OneLake エクスプローラー](https://learn.microsoft.com/ja-jp/fabric/onelake/onelake-file-explorer) | 3 |
| 5 | [OneLake データ ハブ](https://learn.microsoft.com/ja-jp/fabric/get-started/onelake-data-hub?toc=%2Ffabric%2Fonelake%2FTOC.json&bc=%2Ffabric%2Fonelake%2Fbreadcrumb%2Ftoc.json) | 1 |
| 6 | [OneLake でのデータのセキュリティ保護の概要](https://learn.microsoft.com/ja-jp/fabric/onelake/get-started-security) | 2 |
| 7 | [OneLake のセキュリティ](https://learn.microsoft.com/ja-jp/fabric/onelake/onelake-security) | 2 |
| 8 | [Microsoft Fabric 決定ガイド: データ ウェアハウスまたはレイクハウス](https://learn.microsoft.com/ja-jp/fabric/get-started/decision-guide-warehouse-lakehouse) | 3 |

### 2.3. L300

N/A


---


## 3. Power BI (13min)

### 3.1. L100

N/A

### 3.2. L200 (13min)

#### 3.2.1. 概要 (6min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [チュートリアル: Power BI ユーザー向け Fabric](https://learn.microsoft.com/ja-jp/power-bi/fundamentals/fabric-get-started) | 6 |

#### 3.2.2. Direct Lake (Preview) (7min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Direct Lake (プレビュー)](https://learn.microsoft.com/ja-jp/power-bi/enterprise/directlake-overview) | 6 |
| 2 | [PBI レポートでのダイレクト レイク モードのしくみ](https://learn.microsoft.com/ja-jp/fabric/data-engineering/lakehouse-pbi-reporting) | 1 |

### 3.3. L300

N/A


---


## 4. Synapse Data Engineering (65min)

### 4.1. L100

N/A

### 4.2. L200 (65min)

#### 4.2.1. 概要 (2min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric のデータ エンジニアリングとは](https://learn.microsoft.com/ja-jp/fabric/data-engineering/data-engineering-overview) | 1 |
| 2 | [Microsoft Fabric の用語 - Synapse Data Engineering](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#synapse-data-engineering) | 1 |

#### 4.2.2. レイクハウス (16min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric のレイクハウスとは](https://learn.microsoft.com/ja-jp/fabric/data-engineering/lakehouse-overview) | 2 |
| 2 | [Lakehouse のワークスペース ロール](https://learn.microsoft.com/ja-jp/fabric/data-engineering/workspace-roles-lakehouse) | 1 |
| 3 | [Microsoft Fabric でレイクハウスを作成する](https://learn.microsoft.com/ja-jp/fabric/data-engineering/create-lakehouse) | 1 | Tutorial |
| 4 | [Fabric Lakehouse エクスプローラーを移動する](https://learn.microsoft.com/ja-jp/fabric/data-engineering/navigate-lakehouse-explorer) | 1 |
| 5 | [レイクハウスのショートカットとは](https://learn.microsoft.com/ja-jp/fabric/data-engineering/lakehouse-shortcuts) | 1 |
| 6 | [Fabric Lakehouse にデータを取得するためのオプション](https://learn.microsoft.com/ja-jp/fabric/data-engineering/load-data-lakehouse) | 1 |
| 7 | [コピー アクティビティを使用してデータをコピーする方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/copy-data-activity) | 4 |
| 8 | [Microsoft Fabric でデータ パイプラインの実行を監視する方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/monitor-pipeline-runs) | 1 |
| 9 | [クイック スタート: データをコピーする最初のパイプラインを作成する](https://learn.microsoft.com/ja-jp/fabric/data-factory/create-first-pipeline-with-sample-data) | 2 | Quick start|
| 10 | [コピー アシスタントを使用してAzure SQL DB から Lakehouse にデータを移動する](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-move-data-lakehouse-copy-assistant) | 2 | Tutorial |

#### 4.2.3. Delta Lake (6min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Lakehouse テーブルと Delta Lake テーブル](https://learn.microsoft.com/ja-jp/fabric/data-engineering/lakehouse-and-delta-tables) | 3 |
| 2 | [Delta Lake とは](https://learn.microsoft.com/ja-jp/azure/synapse-analytics/spark/apache-spark-what-is-delta-lake) | 2 |
| 3 | [Delta Lake テーブルへの読み込み](https://learn.microsoft.com/ja-jp/fabric/data-engineering/load-to-tables) | 1 |

#### 4.2.4. Apache Spark (17min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric の Spark コンピューティングとは](https://learn.microsoft.com/ja-jp/fabric/data-engineering/spark-compute) | 4 |
| 2 | [はじめに \| Microsoft Fabric で Apache Spark を使用する](https://learn.microsoft.com/ja-jp/training/modules/use-apache-spark-work-files-lakehouse/1-introduction) | 1 | Training |
| 3 | [Apache Spark の使用に向けて準備を行う \| Microsoft Fabric で Apache Spark を使用する](https://learn.microsoft.com/ja-jp/training/modules/use-apache-spark-work-files-lakehouse/2-spark) | 3 | Training |
| 4 | [Spark コードを実行する \| Microsoft Fabric で Apache Spark を使用する](https://learn.microsoft.com/ja-jp/training/modules/use-apache-spark-work-files-lakehouse/3-spark-code) | 3 | Training |
| 5 | [Microsoft Fabric の Spark ワークスペース管理設定](https://learn.microsoft.com/ja-jp/fabric/data-engineering/workspace-admin-settings) | 2 |
| 6 | [Apache Spark ワークスペースの管理設定に関する FAQ](https://learn.microsoft.com/ja-jp/fabric/data-engineering/spark-admin-settings-faq) | 4 |

#### 4.2.5. ノートブック (4min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric ノートブックの使用方法](https://learn.microsoft.com/ja-jp/fabric/data-engineering/how-to-use-notebook) | 4 |

#### 4.2.6. チュートリアル (20min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Lakehouse のエンドツーエンドのシナリオ: 概要とアーキテクチャ](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-lakehouse-introduction) | 4 | Tutorial |
| 2 | [Lakehouse チュートリアル: Fabric ワークスペースを作成する](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-lakehouse-get-started) | 1 | Tutorial |
| 3 | [Lakehouse チュートリアル: レイクハウスの作成、サンプル データの取り込み、レポートの作成](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-build-lakehouse) | 3 | Tutorial |
| 4 | [Lakehouse チュートリアル: レイクハウスにデータを取り込む](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-lakehouse-data-ingestion) | 2 | Tutorial |
| 5 | [Lakehouse チュートリアル: Lakehouse でデータを準備して変換する](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-lakehouse-data-preparation) | 6 | Tutorial |
| 6 | [Lakehouse チュートリアル: Microsoft Fabric でレポートを作成する](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-lakehouse-build-report) | 3 | Tutorial |
| 7 | [Lakehouse チュートリアル: Fabric リソースをクリーンアップする](https://learn.microsoft.com/ja-jp/fabric/data-engineering/tutorial-lakehouse-clean-up) | 1 | Tutorial |

### 4.3. L300

N/A


---


## 5. Data Factory (108min)

### 5.1. L100

N/A

### 5.2. L200 (108min)

#### 5.2.1. 概要 (6min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric の Data Factory とは](https://learn.microsoft.com/ja-jp/fabric/data-factory/data-factory-overview) | 2 |
| 2 | [Microsoft Fabric の用語 - Data Factory](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#data-factory) | 1 |
| 3 | [Azure Data Factoryから Microsoft Fabric の Data Factory へのアクセス](https://learn.microsoft.com/ja-jp/fabric/data-factory/compare-fabric-data-factory-and-azure-data-factory) | 3 |

#### 5.2.2. コネクタ (8min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [コネクタの概要](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-overview) | 2 |
| 2 | [Lakehouse コネクタの概要](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-lakehouse-overview) | 1 |
| 3 | [Azure Blob Storage コネクタの概要](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-azure-blob-storage-overview) | 1 |
| 4 | [Azure Blob Storage接続を作成する方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-azure-blob-storage) | 4 |

#### 5.2.3. パイプライン (45min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [はじめに \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/1-introduction) | 1 | Training |
| 2 | [パイプラインについて \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/2-understand-fabric-pipeline) | 6 | Training |
| 3 | [アクティビティの概要](https://learn.microsoft.com/ja-jp/fabric/data-factory/activity-overview) | 3 |
| 4 | [データのコピー アクティビティを使用する \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/3-copy-data) | 3 | Training |
| 5 | [コピー アクティビティを使用してデータをコピーする方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/copy-data-activity) | 4 | How-to |
| 6 | [コピー アクティビティで Lakehouse を構成する方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-lakehouse-copy-activity) | 7 | How-to |
| 7 | [コピー アクティビティでAzure Blob Storageを構成する方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-azure-blob-storage-copy-activity) | 5 | How-to |
| 8 | [クイック スタート: データをコピーする最初のパイプラインを作成する](https://learn.microsoft.com/ja-jp/fabric/data-factory/create-first-pipeline-with-sample-data) | 2 | Quick start guide |
| 9 | [パイプライン テンプレートを使用する \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/4-pipeline-templates) | 3 | Training |
| 10 | [Microsoft Fabric の Data Factory 用テンプレート](https://learn.microsoft.com/ja-jp/fabric/data-factory/templates) | 1 | How-to |
| 11 | [概念: データ パイプラインの実行](https://learn.microsoft.com/ja-jp/fabric/data-factory/pipeline-runs) | 1 |
| 12 | [パイプラインを実行して監視する \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/5-run-monitor-pipelines) | 5 | Training |
| 13 | [Microsoft Fabric でデータ パイプラインの実行を監視する方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/monitor-pipeline-runs) | 1 | How-to |
| 14 | [監視ハブでデータ パイプラインの実行を参照する](https://learn.microsoft.com/ja-jp/fabric/data-factory/monitoring-hub-pipeline-runs) | 1 |
| 15 | [Azure Blob Storageから Lakehouse へのコピー](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-pipeline-copy-from-azure-blob-storage-to-lakehouse) | 2 | Tutorial |

**Supplements**

* [演習 - パイプラインを使用してデータを取り込む \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/6-exercise-pipelines)
* [知識チェック \| Microsoft Fabric で Data Factory パイプラインを使用する](https://learn.microsoft.com/ja-jp/training/modules/use-data-factory-pipelines-fabric/7-knowledge-check)

#### 5.2.4. データフロー (28min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [はじめに \| Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/1-introduction) | 2 | Training |
| 2 | [Microsoft Fabric のデータフロー (Gen2) について \| Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/2-dataflows-gen-2) | 6 | Training |
| 3 | [Microsoft Fabric のデータフロー (Gen2) について詳しく確認する \| Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/3-explore-dataflows-gen-2) | 4 | Training |
| 4 | [データフロー第 1 世代からデータフロー第 2 世代への取得](https://learn.microsoft.com/ja-jp/fabric/data-factory/dataflows-gen2-overview) | 3 |
| 5 | [クイック スタート: データを取得および変換するための最初のデータフローを作成する](https://learn.microsoft.com/ja-jp/fabric/data-factory/create-first-dataflow-gen2) | 3 | Quick start guide |
| 6 | [データフローの下書きを保存する](https://learn.microsoft.com/ja-jp/fabric/data-factory/dataflows-gen2-save-draft) | 1 | How-to |
| 7 | [データフローで Lakehouse データ レイクに接続する](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-lakehouse-dataflows) | 1 | How-to |
| 8 | [データフロー内のAzure Blob Storageに接続する](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-azure-blob-storage-dataflows) | 1 | How-to |
| 9 | [サンプル データを Lakehouse にコピーし、Microsoft Fabric の Data Factory を使用してデータフローを使用して変換する](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-load-data-lakehouse-transform) | 3 | Tutorial |
| 10 | [Microsoft Fabric でデータフロー (Gen2) とパイプラインを統合する \| Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/4-dataflow-pipeline) | 2 | Training |
| 11 | [パイプラインでデータフローを使用する](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-dataflows-gen2-pipeline-activity) | 2 | Tutorial |

**Supplements**

* [演習 - Microsoft Fabric でデータフロー (Gen2) を作成して使用する \| Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/5-exercise)
* [知識チェック \| Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/6-knowledge-check)

#### 5.2.5. その他/共通 (21min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [クイック スタート: データフローとデータ パイプラインを使用してデータを移動および変換する](https://learn.microsoft.com/ja-jp/fabric/data-factory/transform-data) | 4 | Quick start guide |
| 2 | [Data Factory のエンド ツー エンドのシナリオ: 概要とアーキテクチャ](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-end-to-end-introduction) | 3 | Quick start guide |
| 3 | [モジュール 1: Data Factory を使用してパイプラインを作成する](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-end-to-end-pipeline) | 3 | Quick start guide |
| 4 | [モジュール 2: Data Factory でデータフローを使用してデータを変換する](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-end-to-end-dataflow) | 6 | Quick start guide |
| 5 | [モジュール 3: Data Factory を使用して通知を自動化して送信する](https://learn.microsoft.com/ja-jp/fabric/data-factory/tutorial-end-to-end-integration) | 3 | Quick start guide |
| 6 | [Microsoft Fabric の意思決定ガイド: コピー アクティビティ、データフロー、または Spark](https://learn.microsoft.com/ja-jp/fabric/get-started/decision-guide-pipeline-dataflow-spark) | 2 |

### 5.3. L300

N/A


---


## 6. Synapse Data Warehouse (88min)

### 6.1. L100

N/A

### 6.2. L200 (88min)

#### 6.2.1. 概要 (37min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [はじめに \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/1-introduction) | 3 | Training |
| 2 | [データ ウェアハウスの基礎を理解する \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/2-understand-data-warehouse) | 7 | Training |
| 3 | [Microsoft Fabric のデータ ウェアハウスとは](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/data-warehousing) | 7 |
| 4 | [Microsoft Fabric の用語 - Synapse データ ウェアハウス](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#synapse-data-warehousing) | 1 |
| 5 | [Fabric のデータ ウェアハウスを理解する \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/3-understand-data-warehouse-fabric) | 6 | Training |
| 6 | [より良い一緒に:湖畔と倉庫](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/get-started-lakehouse-sql-endpoint) | 7 |
| 7 | [Microsoft Fabric 決定ガイド: データ ウェアハウスまたはレイクハウス](https://learn.microsoft.com/ja-jp/fabric/get-started/decision-guide-warehouse-lakehouse?toc=%2Ffabric%2Fdata-warehouse%2Ftoc.json&bc=%2Ffabric%2Fdata-warehouse%2Ftoc.json) | 3 |
| 8 | [Microsoft Fabric でサンプル ウェアハウスを作成する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/create-warehouse-sample) | 2 | How-to |
| 9 | [倉庫の設定とコンテキスト メニュー](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/settings-context-menus) | 1 |

#### 6.2.2. データの取り込み (7min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [ウェアハウスにデータを取り込む](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/ingest-data) | 4 |
| 2 | [COPY ステートメントを使用してウェアハウスにデータを取り込む](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/ingest-data-copy) | 3 | Tutorial |

#### 6.2.3. 接続とセキュリティ (6min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric でのデータ ウェアハウスへの接続](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/connectivity) | 5 |
| 2 | [Microsoft Fabric でのデータ ウェアハウスのセキュリティ](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/security) | 1 |

#### 6.2.4. データの表示 (13min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric のデータ プレビューでデータを表示する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/data-preview) | 1 | How-to |
| 2 | [データのクエリと変換 \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/4-query-transform-data) | 6 | Training |
| 3 | [ビジュアル クエリ エディターを使用したクエリ](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/visual-query-editor) | 2 | How-to |
| 4 | [SQL クエリ エディターを使用したクエリ](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/sql-query-editor) | 4 | How-to |

#### 6.2.5. データのモデリング (15min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [分析とレポート用にデータを準備する \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/5-model-data) | 6 | Training |
| 2 | [Microsoft Fabric の既定の Power BI データセット](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/datasets) | 3 |
| 3 | [Microsoft Fabric の既定の Power BI データセットでのデータ モデリング](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/model-default-power-bi-dataset) | 2 |
| 4 | [Microsoft Fabric のデータ ウェアハウスのデータ モデルでリレーションシップを定義する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/data-modeling-defining-relationships) | 2 |
| 5 | [Microsoft Fabric と Power BI Desktop のPower BI サービスでレポートを作成する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/reports-power-bi-service) | 2 | How-to |

#### 6.2.6. チュートリアル1 (10min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric でウェアハウスを作成する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/create-warehouse) | 3 | Tutorial |
| 2 | [Microsoft Fabric のウェアハウスにテーブルを作成する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/create-table) | 1 | Tutorial |
| 3 | [データ パイプラインを使用してウェアハウスにデータを取り込む](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/ingest-data-pipelines) | 2 | Tutorial |
| 4 | [Microsoft Fabric の SQL エンドポイントまたはウェアハウスに対してクエリを実行する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/query-warehouse) | 2 | Tutorial |
| 5 | [Microsoft Fabric でデータ ウェアハウスに関するレポートを作成する](https://learn.microsoft.com/ja-jp/fabric/data-warehouse/create-reports) | 2 | Tutorial |

**Supplements**

* [演習 - データ ウェアハウスでデータを分析する \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/7-exercise)
* [知識チェック \| Microsoft Fabric でのデータ ウェアハウスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-warehouse/8-knowledge-check)

### 6.3. L300

N/A


---


## 7. Synapse Real-Time Analytics (88min)

### 7.1. L100

N/A

### 7.2. L200 (88min)

#### 7.2.1. 概要 (14min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [はじめに \| Microsoft Fabric での Real-Time Analytics の概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-kusto-fabric/1-introduction) | 3 | Training |
| 2 | [Synapse Real-Time Analytics とは? \| Microsoft Fabric での Real-Time Analytics の概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-kusto-fabric/2-define-real-time-analytics) | 5 | Training |
| 3 | [Fabric のReal-Time Analytics とは](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/overview) | 2 |
| 4 | [Real-Time Analytics と Azure Data Explorerの違いは何ですか?](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/realtime-analytics-compare) | 3 |
| 5 | [Microsoft Fabric の用語 - Synapse Real-Time Analytics](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#synapse-real-time-analytics) | 1 |

#### 7.2.2. イベントストリーム (20min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric イベント ストリーム - 概要](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/overview) | 1 |
| 2 | [Microsoft Fabric でイベントストリームを作成および管理する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/create-manage-an-eventstream) | 2 | How-to |
| 3 | [イベント ストリームでイベント ソースを追加および管理する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/add-manage-eventstream-sources) | 4 | How-to |
| 4 | [イベントストリーム内の宛先を追加および管理する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/add-manage-eventstream-destinations) | 4 | How-to |
| 5 | [イベント プロセッサ エディターを使用してイベント データを処理する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/process-events-using-event-processor-editor) | 3 | How-to |
| 6 | [Eventstream アイテム内のデータをプレビューする](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/preview-data) | 1 | How-to |
| 7 | [リアルタイム イベントの取り込み、フィルター処理、変換を行い、Delta Lake 形式で Microsoft Fabric Lakehouse に送信する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/event-streams/transform-and-stream-real-time-events-to-lakehouse) | 5 | Tutorial |

#### 7.2.3. KQL データベース (19min)

##### 7.2.3.1. 概要

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [KQL データベースとテーブルを理解する \| Microsoft Fabric での Real-Time Analytics の概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-kusto-fabric/3-describe-kusto-databases-tables) | 5 | Training |

##### 7.2.3.2. データベースとテーブルの作成

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [KQL データベースを作成する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/create-database) | 1 | How-to |
| 2 | [空のテーブルを作成する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/create-empty-table) | 1 | How-to |

##### 7.2.3.3. データの取得

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [OneLake からデータを取得する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/get-data-onelake) | 2 | How-to |
| 2 | [BLOB コンテナーからデータを取得する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/get-data-blob-container) | 2 | How-to |
| 3 | [BLOB からデータを取得する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/get-data-blob) | 3 | How-to |

##### 7.2.3.4. Data Factory との接続

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [コピー アクティビティで KQL データベースを構成する方法](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-kql-database-copy-activity) | 3 | How-to |
| 2 | [データフローで Azure Data Explorer (Kusto) に接続する](https://learn.microsoft.com/ja-jp/fabric/data-factory/connector-kusto-dataflows) | 2 | How-to |

#### 7.2.4. KQL (25min)

##### 7.2.4.1. 概要

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Kusto 照会言語 (KQL) の概要](https://learn.microsoft.com/ja-jp/azure/data-explorer/kusto/query/?context=%2Ffabric%2Fcontext%2Fcontext) | 2 |
| 2 | [KQL クイック リファレンス](https://learn.microsoft.com/ja-jp/azure/data-explorer/kusto/query/kql-quick-reference) | 4 |
| 3 | [サンプル クエリを使用する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/query-table) | 1 | How-to |
| 4 | [KQL を使用してクエリを記述する \| Microsoft Fabric での Real-Time Analytics の概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-kusto-fabric/4-write-queries-kusto-query-language) | 6 | Training |
| 5 | [チュートリアル: 一般的な演算子について学習する](https://learn.microsoft.com/ja-jp/azure/data-explorer/kusto/query/tutorials/learn-common-operators) | 3 | Tutorial |
| 6 | [チュートリアル: 集計関数を使用する](https://learn.microsoft.com/ja-jp/azure/data-explorer/kusto/query/tutorials/use-aggregation-functions) | 7 | Tutorial |
| 7 | [チュートリアル: 複数のテーブルのデータを結合する](https://learn.microsoft.com/ja-jp/azure/data-explorer/kusto/query/tutorials/join-data-from-multiple-tables) | 2 | Tutorial |

**Supplements**

* [演習: Fabric で Synapse Real-Time Analytics を探索する \| Microsoft Fabric での Real-Time Analytics の概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-kusto-fabric/5-exercise-use-kusto-query-data-onelake)
* [知識チェック \| Microsoft Fabric での Real-Time Analytics の概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-kusto-fabric/6-knowledge-check)

#### 7.2.5. KQL クエリセット (2min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [KQL クエリセット内のデータのクエリを実行する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/kusto-query-set) | 2 | How-to |

#### 7.2.6. OneLake との統合 (3min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [1 つの論理コピー](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/onelake-mirroring) | 2 | How-to |
| 2 | [OneLake でデータにアクセスするためのショートカットを作成する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/onelake-shortcut) | 1 | How-to |

#### 7.2.7. Microsoft Fabric ノートブック からの利用 (2min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [チュートリアル: Apache Spark でノートブックを使用して KQL データベースに対してクエリを実行する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/spark-connector) | 2 | Tutorial |

#### 7.2.8. Power BI からの接続 (3min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Power BI レポートでデータを視覚化する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/create-powerbi-report) | 1 | How-to |
| 2 | [Power BI Desktopで KQL データベースのデータを使用する](https://learn.microsoft.com/ja-jp/fabric/real-time-analytics/power-bi-data-connector) | 2 | How-to |

### 7.3. L300

N/A


---


## 8. Synapse Data Science (267min)

### 8.1. L100

N/A

### 8.2. L200 (267min)

#### 8.2.1. 概要 (11min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [はじめに \| Microsoft Fabric でのデータ サイエンスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-science-fabric/1-introduction) | 1 | Training |
| 2 | [データ サイエンスを理解する \| Microsoft Fabric でのデータ サイエンスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-science-fabric/2-data-science) | 6 | Training |
| 3 | [Microsoft Fabric のData Scienceとは](https://learn.microsoft.com/ja-jp/fabric/data-science/data-science-overview) | 3 |
| 4 | [Microsoft Fabric の用語 - Synapse Data Science](https://learn.microsoft.com/ja-jp/fabric/get-started/fabric-terminology#synapse-data-science) | 1 |

#### 8.2.2. データの準備 (6min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric で Data Wrangler を使用してデータ準備を高速化する方法](https://learn.microsoft.com/ja-jp/fabric/data-science/data-wrangler) | 2| How-to |
| 2 | [Microsoft Fabric で Pandas を使用してデータを読み書きする方法](https://learn.microsoft.com/ja-jp/fabric/data-science/read-write-pandas) | 4 | How-to |

**Supplements**

* [Data Wrangler (Preview)](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.datawrangler)

#### 8.2.3. 実験とモデル (23min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric でデータ サイエンスを探索する \| Microsoft Fabric でのデータ サイエンスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-science-fabric/3-fabric-concepts) | 8 | Training |
| 2 | [Microsoft Fabric での機械学習の実験](https://learn.microsoft.com/ja-jp/fabric/data-science/machine-learning-experiment) | 3 | How-to |
| 3 | [Microsoft Fabric の機械学習モデル](https://learn.microsoft.com/ja-jp/fabric/data-science/machine-learning-model) | 2 | How-to |
| 4 | [機械学習モデルをトレーニングする](https://learn.microsoft.com/ja-jp/fabric/data-science/model-training/model-training-overview) | 2 |
| 5 | [MLflow を使用して実験を追跡する \| Microsoft Fabric でのデータ サイエンスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-science-fabric/4-mlflow) | 8 | Training |

**Supplements**

* [演習 - Microsoft Fabric でモデルをトレーニングして追跡する \| Microsoft Fabric でのデータ サイエンスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-science-fabric/5-exercise-use-notebook)
* [知識チェック \| Microsoft Fabric でのデータ サイエンスの概要](https://learn.microsoft.com/ja-jp/training/modules/get-started-data-science-fabric/6-knowledge-check)

#### 8.2.4. Python (12min) ※Optional

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Python for Apache Spark を使用する](https://learn.microsoft.com/ja-jp/fabric/data-science/python-guide/python-overview) | 2 |
| 2 | [Microsoft Fabric で scikit-learn を使用してモデルをトレーニングする方法](https://learn.microsoft.com/ja-jp/fabric/data-science/train-models-scikit-learn) | 2 | How-to |
| 3 | [Microsoft Fabric で Python ライブラリを管理する](https://learn.microsoft.com/ja-jp/fabric/data-science/python-guide/python-library-management) | 3 | How-to |
| 4 | [Apache Spark と Python を使用してデータを分析する](https://learn.microsoft.com/ja-jp/fabric/data-science/python-guide/python-visualizations) | 5 | Tutorial |

**Supplements**

* [Quickstart: Pandas API on Spark](https://spark.apache.org/docs/3.3.0/api/python/getting_started/quickstart_ps.html)

#### 8.2.5. R (46min) ※Optional

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [R for Apache Spark を使用する](https://learn.microsoft.com/ja-jp/fabric/data-science/r-overview) | 3 |
| 2 | [SparkR を使用する](https://learn.microsoft.com/ja-jp/fabric/data-science/r-use-sparkr) | 12 | How-to |
| 3 | [sparklyr を使用する](https://learn.microsoft.com/ja-jp/fabric/data-science/r-use-sparklyr) | 5 | How-to |
| 4 | [Tidyverse を使用する](https://learn.microsoft.com/ja-jp/fabric/data-science/r-use-tidyverse) | 6 | How-to |
| 5 | [R ライブラリの管理](https://learn.microsoft.com/ja-jp/fabric/data-science/r-library-management) | 5 | How-to |
| 6 | [R でデータを視覚化する](https://learn.microsoft.com/ja-jp/fabric/data-science/r-visualization) | 2 | How-to |
| 7 | [チュートリアル: R を使用したアボカドの価格予測](https://learn.microsoft.com/ja-jp/fabric/data-science/r-avocado) | 6 | Tutorial |
| 8 | [フライト遅延予測](https://learn.microsoft.com/ja-jp/fabric/data-science/r-flight-delay) | 7 | Tutorial |

#### 8.2.6. Apache Spark (65min)

##### 8.2.6.1. 概要

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric の Spark コンピューティングとは](https://learn.microsoft.com/ja-jp/fabric/data-engineering/spark-compute?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 4 |
| 2 | [Fabric の Apache Spark ランタイム](https://learn.microsoft.com/ja-jp/fabric/data-engineering/runtime?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 7 |

##### 8.2.6.2. ワークスペース

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Microsoft Fabric の Spark ワークスペース管理設定](https://learn.microsoft.com/ja-jp/fabric/data-engineering/workspace-admin-settings?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 2 |
| 2 | [Microsoft Fabric でカスタム Spark プールを作成する方法](https://learn.microsoft.com/ja-jp/fabric/data-engineering/create-custom-spark-pools?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 2 |
| 3 | [ワークスペース アイテムの最近の実行](https://learn.microsoft.com/ja-jp/fabric/data-engineering/spark-item-recent-runs?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 1 |
| 4 | [Apache Spark ワークスペースの管理設定に関する FAQ](https://learn.microsoft.com/ja-jp/fabric/data-engineering/spark-admin-settings-faq?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 4 |

##### 8.2.6.3. 開発

###### 10.1.6.3.1. 概要

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Fabric MSSparkUtils の概要](https://learn.microsoft.com/ja-jp/fabric/data-engineering/microsoft-spark-utilities?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 12 |
| 2 | [Microsoft Fabric で Apache Spark ライブラリを管理する](https://learn.microsoft.com/ja-jp/fabric/data-engineering/library-management?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 5 |
| 3 | [ノートブックに関するリアルタイムのアドバイスのための Apache Spark Advisor](https://learn.microsoft.com/ja-jp/fabric/data-engineering/spark-advisor-introduction?toc=%2Ffabric%2Fdata-science%2Ftoc.json&bc=%2Ffabric%2Fdata-science%2Fbreadcrumb%2Ftoc.json) | 2 |

###### 10.1.6.3.2. Spark MLlib

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [Apache Spark MLlib を使用して機械学習モデルを構築する](https://learn.microsoft.com/ja-jp/fabric/data-science/model-training/fabric-sparkml-tutorial) | 7 | How-to |

###### 10.1.6.3.3. SynapseML

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [最初の SynapseML モデル](https://learn.microsoft.com/ja-jp/fabric/data-science/synapseml-first-model) | 2 | How-to |
| 2 | [LightGBM](https://learn.microsoft.com/ja-jp/fabric/data-science/lightgbm-overview) | 1 |
| 3 | [分類 - SynapseML の前後](https://learn.microsoft.com/ja-jp/fabric/data-science/classification-before-and-after-synapseml) | 5 | How-to |
| 4 | [高速、条件付き、k-ニアレスト ネイバーを使用したカルチャとメディア全体のアートの探索](https://learn.microsoft.com/ja-jp/fabric/data-science/conditional-k-nearest-neighbors-exploring-art) | 7 | How-to |
| 5 | [レシピ: 分離フォレストを使用した多変量異常検出](https://learn.microsoft.com/ja-jp/fabric/data-science/isolation-forest-multivariate-anomaly-detection) | 4 | How-to |

#### 8.2.7. チュートリアル (E2E) (32min)

| # | タイトル | Time (min) | 備考 |
| ---:|:--- | ---:| --- |
| 1 | [データ サイエンスのエンドツーエンドのシナリオ: 概要とアーキテクチャ](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-introduction) | 2 |
| 2 | [データ サイエンスチュートリアル シリーズ用にシステムを準備する](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-prepare-system) | 2 | How-to |
| 3 | [パート 1: Apache Spark を使用して Microsoft Fabric Lakehouse にデータを取り込む](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-ingest-data) | 4 | Tutorial |
| 4 | [パート 2: Microsoft Fabric ノートブックを使用してデータを探索して視覚化する](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-explore-notebook) | 6 | Tutorial |
| 5 | [パート 3: Apache Spark を使用してデータクレンジングと準備を実行する](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-data-cleanse) | 4 | Tutorial |
| 6 | [パート 4: Microsoft Fabric で機械学習モデルをトレーニングして登録する](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-train-models) | 8 | Tutorial |
| 7 | [パート 5: バッチ スコアリングを実行し、予測をレイクハウスに保存する](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-batch-scoring) | 3 | Tutorial |
| 8 | [パート 6: 予測を視覚化する Power BI レポートを作成する](https://learn.microsoft.com/ja-jp/fabric/data-science/tutorial-data-science-create-report) | 3 | Tutorial |

### 8.3. L300

N/A


---


## 9. Data Activator

TBA


---


## 10. 管理者およびガバナンス

TBA
