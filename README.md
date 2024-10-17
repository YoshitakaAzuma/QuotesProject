QuotesOfForest(名言の森)
 
 このWebアプリはSpringを利用したWebアプリを作る練習をするのを主な目的として開発しています。

 アプリの概要はユーザが名言の登録とユーザが登録した名言を閲覧できることが基本機能となっています。基本機能の他にいいね機能、お気に入り機能、AIによるカテゴリの判別機能、プロフィール編集機能、フォロー機能などもあります。

 いいね機能、お気に入り機能、フォロー機能　この三つの機能はユーザのクリックをイベントのトリガーとしてRestAPIによってデータベースの情報を書き換えています。JavaScriptのfetchなどを利用してバックグラウンドであるJavaのメソッドを動かし、画面遷移をすることなくデータベースの書き換えと画面に表示されている情報の変更を行い、ユーザの体験をより良いものにしています。

 AIによるカテゴリの判別機能　この機能はユーザが名言の登録をする際にカテゴリの判別に悩んだ時AIが代わりにカテゴリを選択してくれる機能です。OpenAIを使用しておりtemparaturパラメータを0に設定することで返答の振れ幅を最小限に抑えて安定したカテゴリ判別機能を提供することに成功しました。
# DEMO
 画面草案<br>
 タイトル
<img src="https://github.com/user-attachments/assets/13f22254-fb06-4ccb-af94-5f4bbcd1d1af" width="600">
 
# Requirement
 
* Spring Boot
* Spring Security
* Gradle
* Lombok
* My Batis
* Thymeleaf
* PostgreSQL

# Usage
 
現在はサーバに接続していないため使用できない。
 
 
# Author
 
作成情報を列挙する
 
* 東 佳隆
* yoshitakapa913@gmail.com
