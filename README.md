## [kotori]


## ■サービス概要
家族や友人の記念日に
一言添えてお祝いを伝えられるサービスです。


## ■ユーザーが抱える問題
毎日忙しくて記念日を忘れてしまう。
お祝いしたい気持ちはあるけれど、直接面と向かってはなんとなく伝えにくい。


## ■課題に対する仮説
記念日が近づいた時、お知らせがあると忘れない。
オンライン上でのメッセージカードであれば、気軽に送ることができる。


## ■解決方法
登録した記念日の数日前と、当日に通知を送る。
メッセージや日付を入力してメッセージカードを作成する。


##　■メインのターゲットユーザー
家族や友人に、感謝の気持ちを伝えたい方。
家族や友人の記念日を大切にしたい方。


## ■サービスコンセプト
以下のようなポイントでサービスを作ろうと思った背景やその後の展開など自由に記載してください。
* ユーザーが抱えている課題感と提供するサービスでどのように解決するのか
* なぜそのサービスを作ろうと思ったのか
* どのようなサービスにしていきたいか
* どこが売りになるか、差別化ポイントになるか

私は、日々順調に過ごせるのは、家族や友人との温かい関係があってこそだと思っています。
身近な人に感謝やお祝いの気持ちを伝えることで良い関係性を築き、日々をより良く過ごせるようにと思い、
記念日をお祝いするサービスを作成しようと考えました。

毎日忙しく、記念日を見落としてしまったり、感謝の気持ちをなかなか伝えることができない方でも、
通知を受け取ることで記念日を忘れることを防ぎ、メッセージカードに一言添えることで、気持ちを伝えやすくなるのではと考えました。

また、記念日までの1日1日をより大切に過ごしていきたいという思いで、残日数を可視化できるように
当日までのカウントダウンが表示される機能を設けます。
忙しい中でも、記念日をどのように過ごしたいか考えたり、身近な人に対して思いやりの気持ちを持つことで、
自分自身も穏やかに過ごすことができ、家族との良い関係を築くきっかけになるのではと思います。

人生の土台である家族との絆を深めて、自分自身も大切な家族もより良く過ごしていける、
そういったきっかけになるサービスにしていきたいと考えます。


## ■実装を予定している機能
### MVP
- 会員登録
- ログイン機能
- 記念日の登録、一覧表示
- メッセージカードの作成
- メッセージカードのダウンロード機能

### ■本リリース迄に追加する機能
- LINE通知機能（記念日3日前、当日にお知らせ）
- 記念日までのカウントダウン表示機能
- 贈り物やお祝いの方法を検索できるページをヘッダーに設置
- 問い合わせフォームをヘッダーに設置


### ■スケジュール
1. 企画（アイデア企画・技術調査）：6/30〆切
2. 設計（README作成・画面遷移図作成・ER図作成）：7/12〆切
3. 機能実装：7/13 - 8/6
4. MVPリリース：8/7〆切
5. 本リリース：8/21


### ■技術選定
■バックエンド
- Rails
- Ruby

■フロントエンド
- Javascript

■外部API
- LINE Messaging API

■インフラ
- Fly.io

■その他
- CarrierWave


---

画面遷移図(Figma)

https://www.figma.com/file/Ux1dI4u754JU94VobcWQ1a/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?type=design&node-id=0%3A1&mode=design&t=4TShkf9KYGVF3evf-1

ER図

[![Image from Gyazo](https://i.gyazo.com/572a2ff9970225b8367dc5b48224564a.png)](https://gyazo.com/572a2ff9970225b8367dc5b48224564a)
