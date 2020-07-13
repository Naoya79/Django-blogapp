# Django-blogapp

管理者の投稿した記事を閲覧できるブログアプリ

## 概要

Web開発の練習として、ブログアプリを作成しました。  
トップページは記事の一覧が表示されます。各記事は、画像・タイトル・投稿日時・内容が表示され、画像かタイトルをクリックすると詳細ページに移動できるようになっています。  
詳細ページはタイトル・投稿日時・画像・内容全文が表示されます。  


## 使用技術

使用した技術は以下の通りです。
- Django(Webアプリケーションフレームワーク)
- Bootstrap(UIフレームワーク)
- AWS(クラウドサーバ)
  - Nginx(Webサーバ)
  - gunicorn(アプリケーションサーバ)
  - PostgreSQL(データベース)

## 外観

投稿一覧
![スクリーンショット 2020-07-13 12 45 40](https://user-images.githubusercontent.com/67271461/87268986-e9ba5580-c506-11ea-83cb-0bcb1e1c3fc9.png)

投稿詳細
![スクリーンショット 2020-07-13 12 46 23](https://user-images.githubusercontent.com/67271461/87269002-f3dc5400-c506-11ea-807d-83f1f991394b.png)

投稿記事管理(管理者画面)
![screencapture-18-217-61-213-admin-posts-post-2020-07-13-12_32_42](https://user-images.githubusercontent.com/67271461/87269083-179f9a00-c507-11ea-93f6-6a343d74fa8e.png)

投稿内容記載(管理者画面)
![screencapture-18-217-61-213-admin-posts-post-add-2020-07-13-12_30_58](https://user-images.githubusercontent.com/67271461/87269093-1ec6a800-c507-11ea-91c2-4595b331435b.png)
