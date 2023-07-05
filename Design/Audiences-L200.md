# 想定オーディエンス (L200)

- [1. OneLake](#1-onelake)
  - [1.1. 必須 (Required)](#11-必須-required)
  - [1.2. あることが望ましい (Preferred)](#12-あることが望ましい-preferred)
- [2. Power BI](#2-power-bi)
  - [2.1. 必須 (Required)](#21-必須-required)
  - [2.2. あることが望ましい (Preferred)](#22-あることが望ましい-preferred)
- [3. Synapse Data Engineering](#3-synapse-data-engineering)
  - [3.1. 必須 (Required)](#31-必須-required)
  - [3.2. あることが望ましい (Preferred)](#32-あることが望ましい-preferred)
- [4. Data Factory](#4-data-factory)
  - [4.1. 必須 (Required)](#41-必須-required)
  - [4.2. あることが望ましい (Preferred)](#42-あることが望ましい-preferred)
- [5. Synapse Data Warehouse](#5-synapse-data-warehouse)
  - [5.1. 必須 (Required)](#51-必須-required)
  - [5.2. あることが望ましい (Preferred)](#52-あることが望ましい-preferred)
- [6. Synapse Real-Time Analytics](#6-synapse-real-time-analytics)
  - [6.1. 必須 (Required)](#61-必須-required)
  - [6.2. あることが望ましい (Preferred)](#62-あることが望ましい-preferred)
- [7. Synapse Data Science](#7-synapse-data-science)
  - [7.1. 必須 (Required)](#71-必須-required)
  - [7.2. あることが望ましい (Preferred)](#72-あることが望ましい-preferred)

---

## 1. OneLake

### 1.1. 必須 (Required)

* 無し

### 1.2. あることが望ましい (Preferred)

* 無し

---

## 2. Power BI

### 2.1. 必須 (Required)

* OneLake の知識 (ワークショップ冒頭で学びます)

### 2.2. あることが望ましい (Preferred)

* Power BI の経験 (レポート作成)
  * 座学およびハンズオンで使用します。詳細なナビゲーションがあるため必須ではありませんが、経験がある方がスムーズかと思われます。

---

## 3. Synapse Data Engineering

### 3.1. 必須 (Required)

* OneLake の知識 (ワークショップ冒頭で学びます)
* Power BI の経験 (レポート作成)
  * ハンズオンで使用します。

### 3.2. あることが望ましい (Preferred)

* 以下への興味関心
  * コード・ファーストでの ETL/ELT
  * レイクハウス / デルタレイク
  * Apache Spark
  * ノートブック

---

## 4. Data Factory

### 4.1. 必須 (Required)

* OneLake の知識 (ワークショップ冒頭で学びます)
* Azure Blob Storage のストレージアカウント
  * 座学およびハンズオンで使用します。御社の Azure サブスクリプションでご用意ください。用意できない場合はご相談ください。

### 4.2. あることが望ましい (Preferred)

* 以下への興味関心
  * ノーコード・ローコードでの ETL/ELT
  * Azure Data Factory / Azure Synapse Analytics の パイプライン / データフロー
  * Power BI データフロー (Microsoft Fabric データフロー Gen1)

---

## 5. Synapse Data Warehouse

### 5.1. 必須 (Required)

* OneLake の知識 (ワークショップ冒頭で学びます)
* Power BI の経験 (データセット, データモデリング, レポート作成)
  * ハンズオンで使用します。

### 5.2. あることが望ましい (Preferred)

* Azure Blob Storage または Azure Data Lake Storage Gen2 の知識
  * COOPY ステートメントがサポートするデータソースの一つとして紹介があります。知識があった方が理解しやすいかと思われます。
* データウェアハウスの概要に関する知識
  * データウェアハウスそのものに関する説明は行いません。データウェアハウスの知識が無くても Synapse Data Warehouse の機能を学んでいただくことはできますが、知識があった方が理解しやすいかと思われます。必要に応じて以下のドキュメントをご参照ください。
    * [Microsoft Azure のデータ ウェアハウス](https://learn.microsoft.com/ja-jp/azure/architecture/data-guide/relational-data/data-warehousing)
    * [データ ウェアハウスと分析](https://learn.microsoft.com/ja-jp/azure/architecture/example-scenario/data/data-warehouse)
* SQL Server ファミリー / T-SQL の経験
  * SQL Server, Azure SQL Database, Azure SQL Managed Instance, Azure Synapse Analytics 専用SQLプール
  * ハンズオンにおいても SQL を書き起こす内容はなく、コピー＆ペーストする内容となっています。ただし、T-SQL の知見があった方が、内容をより理解しやすいかと思われます。

---

## 6. Synapse Real-Time Analytics

### 6.1. 必須 (Required)

* OneLake の知識 (ワークショップ冒頭で学びます)
* Azure Blob Storage のストレージアカウント
  * ハンズオンで使用します。御社の Azure サブスクリプションでご用意ください。用意できない場合はご相談ください。
* Azure Event Hubs のアカウント
  * ハンズオンで使用します。御社の Azure サブスクリプションでご用意ください。用意できない場合はご相談ください。
* Power BI の経験 (レポート作成, Power BI Desktop を使用したデータソースへの接続)
  * ハンズオンで使用します。

### 6.2. あることが望ましい (Preferred)

* Azure Data Explorer / Azure Synapse Analytics Data Explorer の知識
  * 類似のサービスであるため、知識があると内容をより理解しやすいかと思われます。
* Apache Spark の知識
  * ハンズオンで概念のみ登場します。知識があると内容をより理解しやすいかと思われます。
* ノートブックの経験
  * ハンズオンで使用します。ナビゲートをするため経験が無くても問題ありませんが、経験があるとよりスムーズかと思われます。
* 以下への興味関心
  * イベントのリアルタイム / ストリーム処理
  * KQL

---

## 7. Synapse Data Science

### 7.1. 必須 (Required)

* OneLake の知識 (ワークショップ冒頭で学びます)
* Power BI の経験 (レポート作成)
  * ハンズオンで使用します。
* Python の経験
  * 全体的に Python を使用します。
* データサイエンスの知識・経験 (用語, 概念, プロセス)
  * 背景知識を持っていないと、理解が難しいと思われます。

### 7.2. あることが望ましい (Preferred)

* Azure Machine Learning の経験
  * モデル, 実験, 実行といった概念が共通するため、経験があると内容の理解がスムーズかと思われます。
* MLflow による MLOps の経験
  * ハンズオンで使用しますが、コピー＆ペーストする内容となっています。知識があると内容をより理解しやすいかと思われます。
* Apache Spark の知識
  * ハンズオンで使用しますが、コピー＆ペーストする内容となっています。知識があると内容をより理解しやすいかと思われます。
