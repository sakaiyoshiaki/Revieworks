## アプリ名
### Revieworks

## 概要
社内の組織課題や現場の改善点を洗い出し、外部の社員や専門家の意見・評価を取り入れて議論できる意見投稿アプリです。

## 本番環境
http:/ <br>
ログイン情報(テスト用) <br>
・Eメール：test@test.com <br>
・パスワード 123app

## 制作背景
前職で経理の仕事をして感じたことの１つに、担当部署ごとに優れたノウハウを持っていながら担当部署で完結してしまい、それを他の部署に生かして業務改善につなげる仕組みが弱かったことがあります。
また、優秀な人材が半年もしない内に辞めてしまうなど、離職率の改善も課題としてありました。
会社の評判など社外口コミサイトは多く存在しますが、社内の本社と現場・外部をつなげたコミュニケーションの円滑化を図り、社内環境の改善につなげるアプリはまだ少ないと感じます。
そこで本アプリでは
①「現場担当者と管理部の認識のズレを解消し、部署間の連携を促す」
②「現場レベルの改善のフィードバックを早めて、優秀な人材の離職防止や会社の評判upにつなげる」
ことを目的として制作しました。

## ページ一覧
・ユーザー管理ページ <br>
・投稿意見一覧ページ(トップページ)  <br>
・意見投稿ページ  <br>
・意見詳細ページ  <br>
・プロフィールページ  <br>
・チャットページ  <br>
・Zoomページ  <br>

## 使用技術(開発環境)
### バックエンド
Ruby2.6.4, Ruby on Rails6.0
### フロントエンド
HTML, CSS, SCSS, Javascript, JQuery, Ajax
### データベース
MySQL, SequelPro
### インフラ
AWS(EC2,S3), Capistrano, Docker(開発環境)
### Webサーバー(本番環境)
nginx
### アプリケーションサーバ(本番環境)
unicorn
### ソース管理
Github, GitHubDesktop
### テスト
RSpec
### エディタ
VSCode

## 途中経過(投稿意見一覧ページ)
<img width="1678" alt="スクリーンショット 2021-01-26 21 37 44" src="https://user-images.githubusercontent.com/67823080/105845983-e27c1480-601e-11eb-91bf-b05a06f74a5a.png">
