## 概要

JavaとVert.xを使用して以下のRESTful APIを実装します。

- POST /blogs: ブログの新規作成。
- GET /blogs: 全てのブログの一覧取得。
- GET /blogs/{id}: 特定のブログの詳細情報を取得。
- PUT /blogs/{id}: 特定のブログの更新。
- DELETE /blogs/{id}: 特定のブログの削除。
- POST /blogs/{id}/comments: 特定のブログに対する新規コメントの作成。

RxJavaを利用して非同期の操作を行います。

PostgreSQLを使ってブログとコメントのデータを管理します。ブログテーブルとコメントテーブルを作成します。