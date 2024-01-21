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

顧客管理システム

<!-- プロジェクトについて -->

## プロジェクトについて



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
サーバーが正常に起動すると、http://127.0.0.1:8000 でアプリケーションにアクセスできます。

### フロントエンドの依存関係をインストールおよび実行:

```bash
npm install
npm run dev
```
上記コマンドで、フロントエンドの依存関係をインストールし、開発用のビルドを行います。

### アプリケーションの起動:

ブラウザで http://127.0.0.1:8000 にアクセスして、アプリケーションが正常に表示されるか確認してください。


<p align="right">(<a href="#top">トップへ</a>)</p>
