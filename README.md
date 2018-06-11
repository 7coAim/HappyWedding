### HappyWedding
Tatsuyaさん ＆ Chikakoさん向けの
ご結婚のお祝いメッセージを投稿できるWebサイトです。

# README
デプロイ先：
https://agile-peak-41390.herokuapp.com/
- スリープ状態の場合があります。その場合は起動まで10秒程度お待ちください。

## 概要
- Ruby on Railsにて開発。
- メッセージの投稿・投稿確認・編集・一覧表示・削除機能を実装。
- バリデーションエラーは日本語化を実施。

## 環境、フレームワーク
- Bootstrap v3
- Ruby 2.3
- Ruby on Rails 5.1
- PostgreSQL
- heroku
- heroku add-ons Heroku Postgres

## 使い方（ローカル環境）
- git clone XXXXXX.git
- cd HappyWedding/
- rails db:migrate
- rails s

## 工夫、こだわり、サービス志向
- 遠方の方など、当日、結婚式に参加できない人からもお祝いメッセージを気軽に寄せてもらい、より一層お二人を祝福したい想いで、当時、それまでに勉強したRailsを活かす形で思いつきから半日で作成。
- 気軽にメッセージを入力してもらうため、ログイン不要の形とした。
- 本サイトをLINEなどSNSで共有してもらい、メッセージを次々に入力してもらうことを想定。
  - 分かり易さを重視し、シンプルなページ構成とし、２タップでメッセージ入力に到達できる遷移とした。
- また、Bootstrapによるレスポンシブデザインを適用し、スマートフォンからの利用を意識したUIにした。



以上です！
