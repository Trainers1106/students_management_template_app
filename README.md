# students_management_template_app

このアプリケーションは、学習塾・スクール向けに 生徒の出欠管理・授業スケジュール管理・成績メモ などを一元化する Web アプリケーションです。

フロントエンドは React 18 + TypeScript + chakra ui、バックエンドは Flask (Python) で構築しています。

# Installation

本リポジトリからのインストールではなく，WEBアプリケーション化されているため，以下のurlからアクセスしてください． 
<https://develop.trainers1106.com/build/>

機能体験用ユーザー情報
- ユーザーID：admin
- パスワード：12345

# Features

- 振替ロジックに対応（生徒の振替授業の計算に用いられている複雑なロジックに対応）

- ワンタップ出席登録 ― 生徒の入退室を秒で記録

- 生徒カルテ ― 出欠・学習履歴を1画面に集約

- 役割ベース権限 ― 管理者 / 講師 / 事務スタッフで UI を自動切替
 
# Requirement

| レイヤ           | 必須バージョン例                     | 主なライブラリ                                                  |
| ------------- | ---------------------------- | -------------------------------------------------------- |
| **Frontend**  | Node 20 / npm 10             | React 18, TypeScript, chakra ui, React Router |
| **Backend**   | Python 3.11                  | mysql-connector-python, requests, Flask, python-dotenv, flask-cors         |


# students_management_template_app　フロント部分

1. docker-compose build #最初だけ
2. docker-compose up -d
3. docker-compose ps　＃起動確認
4. docker exec -it students_management_template_app sh
5. npx create-react-app . --template @chakra-ui/typescript --use-npm #プロジェクト作成時に最初だけ
6. docker-compose down #停止
 
# Author
 
* 作成者：五十嵐弘樹，並木海大
* 所属：早稲田大学　創造理工学部　経営システム工学科
* E-mail：五十嵐弘樹→h.igarashi@fuji.waseda.jp
* E-mail：並木海大→miharunamiki@gmail.com
 

