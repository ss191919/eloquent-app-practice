# eloquent-app-practice

## 概要
COACHTECH 教材 Tutorial 9-4「Eloquent ORM ハンズオン演習」で作成した成果物です。
Eloquentモデルを使用してブログシステムを構築し、投稿の一覧表示・新規作成・編集・削除機能を実装しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Eloquent ORM
- MySQL


## 学んだこと
- Eloquentモデルを利用したデータベース操作の方法
- Controllerを使用したCRUD処理の実装方法
- Bladeを利用した一覧画面・登録画面・編集画面の作成方法

## 動作確認
- コンテナ起動　./vendor/bin/sail up -d
- ブラウザで http://localhost/posts にアクセスして以下動作を確認。
・投稿一覧が表示される
・投稿を新規作成できる
・投稿を編集できる
・投稿を削除できる
・公開日時が表示される