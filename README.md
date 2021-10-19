# README

## アプリケーション名
『CONNECPETS』

## URL
https://connecpet2.herokuapp.com/  
＊お試しの方はゲストログインをご利用ください。

## アプリケーション概要
ユーザー様の愛犬、愛猫の情報を投稿していただき、検索することによって兄弟を探せるアプリケーションです。

## 目指した課題解決
感染症の大流行によりペットの需要が高まっている昨今。  
ペットを飼っている方なら一度は思ったことがあるであろう、私の愛犬,愛猫の親や兄弟がどんな子なんだろうと何気ない疑問。  
この何気ない疑問を解決し、親や兄弟を見つけた際には交流できるサービスでユーザーのニーズを満たすことを目指す。

## 各種ページ　機能説明
- ログイン、新規登録
  - お試しの方はゲストログインをご利用ください。
  - 新規登録時Eメールは任意の~~~@***の形でご入力ください。
- 兄弟を探す
  - フリーワードでは犬(猫)種や出身地、母犬(猫)、父犬(猫)の名前を入力して検索ができます。
  - 誕生日での絞り込み、犬猫の絞り込みもできます。
- ペット詳細画面
  - 星をクリックしてお気に入り登録できます。
    - デモ画像
      [![Image from Gyazo](https://i.gyazo.com/3cc86a28fd9558063507d84a07f42c1c.gif)](https://gyazo.com/3cc86a28fd9558063507d84a07f42c1c)
  - お気に入り登録するとマイページにてお気に入り一覧からすぐにその子のページへいけます。
  - 飼い主のところの詳細ボタンをクリックすると飼い主の詳細ページに遷移できます。
  - コメント欄ではコメントを残す事ができます。
  - 自分のペットの場合ペットプロフィールの編集,削除ができます。
- ユーザーページ（飼い主の詳細ページ）
  - フォローするボタンでフォローすることができ、マイページでフォロー一覧からすぐにこのページを開けます。
  - 相互フォローになるとチャットボタンが出現し、チャットができるようになります。
    - デモ画像
    [![Image from Gyazo](https://i.gyazo.com/cc3418aa018906ea71a6ca575c4fcf8d.gif)](https://gyazo.com/cc3418aa018906ea71a6ca575c4fcf8d)
  - そのユーザーのフォロー、フォロワー、お気に入りが確認できます。
  - フォロー、フォロワー、お気に入りをクリックすると一覧ページに遷移します。
  - ユーザーの飼っているペット一覧を確認することができます。
- マイページ
  - 自分のフォロー、フォロワー、お気に入りが確認できます。
  - フォロー数、フォロワー数、お気に入りをクリックすると一覧ページに遷移します。
  - プロフィール編集ボタンをクリックすると編集画面に遷移します。
  - プロフィール編集
    - プロフィール画像、ニックネーム、自己紹介文の編集ができます。
  - 基本情報変更
    - Eメール、パスワードを変更できます。
  - マイペット一覧
    - マイペットを確認できます。
    - マイペットをクリックするとペット詳細ページに遷移します。
    - マイペット登録ボタンをクリックすると編集画面に遷移します。
- フォローリスト,フォロワーリスト
  - フォローしてるユーザーの管理ができます。
  - 詳細ボタンをクリックするとユーザーページに遷移します。
- お気に入りリスト
  - お気に入りしたペットを確認できます。
  - 詳細ボタンをクリックするとペットページに遷移します。

## ER図
![CONNECPETのER図](https://i.gyazo.com/4a37a126cf370a6b129af75bb04b88d1.png)

## 環境
- ホストOS
  - MacOS
- 言語
  - HTML CSS JavaScript Ruby SQL
- フレームワーク
  - Ruby on Rails
- インフラ
  - heroku Docker AWS S3