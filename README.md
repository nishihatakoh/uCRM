<div id="top"></div>

## 使用技術一覧

<!-- シールド一覧 -->
<!-- 該当するプロジェクトの中から任意のものを選ぶ-->
<p style="display: inline">
  <!-- フロントエンドのフレームワーク一覧 -->
    <img src="https://img.shields.io/badge/-Html5-ffffff.svg?logo=html5&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Css3-ffffff.svg?logo=css3&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Vue.js-ffffff.svg?logo=vue.js&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Javascript-ffffff.svg?logo=javascript&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Php-ffffff.svg?logo=php&style=for-the-badge">
<img src="https://img.shields.io/badge/-Laravel-ffffff.svg?logo=laravel&style=for-the-badge">
<img src="https://img.shields.io/badge/-Mysql-ffffff.svg?logo=mysql&style=for-the-badge">

</p>

# uCRM

**uCRM**（Unified Customer Relationship Management）は、顧客管理を中心に据えた総合的なビジネスソリューションです。システムは主に購入、購買履歴、商品管理、顧客管理、そして効果的なデータ分析の機能に焦点を当てています。

## 主な機能

1. **購入画面:**
   - 使いやすく直感的な購入プロセスを提供し、ユーザーが製品やサービスを簡単に購入できるようにします。

2. **購買履歴:**
   - ユーザーごとの購買履歴を管理し、過去の購入情報を参照できるようにします。これにより、個々の顧客の嗜好や行動パターンを把握しやすくなります。

3. **商品管理:**
   - 商品情報の一元管理を可能にし、在庫状況や商品詳細などの情報をリアルタイムで更新できます。

4. **顧客管理:**
   - 顧客情報を集約し、個別のプロファイルや連絡履歴を管理。これにより、よりパーソナライズされたサービス提供が可能となります。

5. **データ分析:**
   - **日別、月別、年別の売り上げ推移:**
     売り上げの時間的変化を把握するために、直感的な棒グラフで日別、月別、年別の売り上げ推移を視覚化。

   - **デシル分析:**
     顧客を収益に基づいて十分なグループに分類し、収益の上位グループや下位グループの特性を把握。これにより、戦略的なアプローチが可能になります。

   - **RFM分析:**
     顧客の購買履歴から、Recency（最終購買からの経過時間）、Frequency（購買頻度）、Monetary Value（購買金額）の観点でセグメント化。これにより、特定の顧客セグメントに対してターゲットを絞った施策を実施できます。

**uCRM**はこれらの機能を組み合わせ、企業が効果的な顧客関係戦略を策定し、ビジネスの成果を最大化するのに役立つ総合的なプラットフォームです。

<p align="right">(<a href="#top">トップへ</a>)</p>

## 環境

<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

| 言語・フレームワーク  | バージョン |
| --------------------- | ---------- |
| php                　　　　　　| 8.3.0      |
| Laravel Framework     |  9.52.16   |
| vue.js　　　　　　　　　　　　　　　　　　　　　　　　    | 3.3.13     |
| inertia-vue3          | 0.6.0      |
| tailwindcss           | 0.5.7      |
| mySQL                 | 14.14      |
| npm               　　   | 8.19.2     |


その他のパッケージのバージョンは pyproject.toml と package.json を参照してください

<p align="right">(<a href="#top">トップへ</a>)</p>

## 開発環境構築

### 前提条件

- MAMPがインストールされていること
- Node.jsおよびnpmがインストールされていること
- Composerがインストールされていること

### 手順

1. **MAMPを起動する:**

   MAMPを起動して、ApacheとMySQLのサーバーを起動してください。

2. **ターミナルでuCRMディレクトリに移動:**

   ターミナルを開き、uCRMプロジェクトが存在するディレクトリに移動します。

   ```bash
   cd /path/to/uCRM

### バックエンドサーバーを起動:

Laravelのバックエンドサーバーを起動します。

```bash
php artisan serve
```
サーバーが正常に起動すると、[http://127.0.0.1:8000](http://localhost:8000/) でアプリケーションにアクセスできます。

### フロントエンドの依存関係をインストールおよび実行:

```bash
npm install
npm run dev
```
上記コマンドで、フロントエンドの依存関係をインストールし、開発用のビルドを行います。

### アプリケーションの起動:

ブラウザで http://localhost:8000/ にアクセスして、アプリケーションが正常に表示されるか確認してください。


<p align="right">(<a href="#top">トップへ</a>)</p>
