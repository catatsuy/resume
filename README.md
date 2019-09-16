# 職務経歴書

## 個人データ

  * 氏名：金子 達哉
  * ID: `catatsuy`
  * URL: https://www.catatsuy.org/

## 職務経歴

### 株式会社メルカリ（2018/6〜）

  * メルカリSREチーム
  * Software Engineer, Infrastructure

### ピクシブ株式会社（2013/10〜2018/6）

  * 数ヶ月間pixivの開発を行った後、インフラ部に異動
  * 2016年4月に開発部に再び異動、様々な開発に関わる
    * pixivのPHP7化やHTTPS化、pixivFANBOXリリースなど多数
    * 広告サーバーの新機能リリースも担当
  * インフラ部でオンプレミスでのインフラ運用、PHPのアプリケーションサーバーやMySQLサーバーの構築・運用を担当
    * 新しい広告サーバーのリリースにインフラ担当として関わり、一部の配信サーバーの実装も担当
    * 採用の内容を充実させるためにインターン生用のpixivの開発環境を作成、インターンの内容を飛躍的に充実させた
      * インターンを支えるpixivの開発環境 - pixiv inside [archive] https://devpixiv.hatenablog.com/entry/2015/04/06/161536

### ソフトウェア開発

#### 社内広告サーバーのリリース・運用・開発

  * 管理サーバーをRuby on Rails、配信サーバーをGo言語で開発
  * リリース時はインフラ全般と配信サーバーを中心に担当、その後は運用・新機能仕様策定・配信サーバーの機能追加を担当
  * 公開資料多数
    * テクノロジー x ビジネスで広告を本気で変革する。pixiv流 広告プロダクトの作り方 - pixiv inside https://inside.pixiv.blog/yattyo/3587
    * logrotateの設定とファイルのアクセスモードについて – Tatsuya Kaneko – Medium https://medium.com/@catatsuy/logrotateの設定とファイルのアクセスモードについて-f9719352dada
    * ピクシブ社内広告サーバーに新機能を追加するためにボクがやったこと - pixiv inside [archive] https://devpixiv.hatenablog.com/entry/2015/12/15/180227
    * ピクシブ社内広告サーバーでのGoの開発・運用 #gocon /p_ads_server_gocon2015 // Speaker Deck https://speakerdeck.com/catatsuy/p-ads-server-gocon2015
    * ピクシブ新広告サーバー構築物語 // Speaker Deck https://speakerdeck.com/catatsuy/pikusibuxin-guang-gao-sabagou-zhu-wu-yu
    * Golang_ads_deliver // Speaker Deck https://speakerdeck.com/catatsuy/golang-ads-deliver

#### pixivのHTTPS化

  * PHPで構築された大規模サービスのHTTPS化
    * pixivを常時HTTPS化するまでの道のり（前編） - pixiv inside https://inside.pixiv.blog/catatsuy/1746
    * pixivを常時HTTPS化するまでの道のり（後編） - pixiv inside https://inside.pixiv.blog/catatsuy/1872


#### pixivのPHP7化

  * PHP7化の前にKyoto Tycoon廃止とpeclのmemcacheを廃止
    * 開発基盤チームが目指す事 #pixiv_night - Qiita https://qiita.com/catatsuy/items/f1338f6f3206b829120d
    * 私とHTTPS化とnginx-luaとPerl - Qiita https://qiita.com/catatsuy/items/33d2615ea03c484dbdad
  * Kyoto Tycoon廃止完了後にすべてのサーバーの移転計画を立てて実施


#### pixivのHTTP/2化

  * pixivでは障壁があったHTTP/2を有効にする
    * pixivのHTTP/2有効化の軌跡 - pixiv inside https://inside.pixiv.blog/catatsuy/4091
    * これからドンドン使われていくSNIについて – catatsuy – Medium https://medium.com/@catatsuy/これからドンドン使われていくsniについて-511e42254611


## 業務外活動

### ISUCON

ISUCON公式Blog http://isucon.net/

  * ISUCON9 運営・予選出題
  * ISUCON8 3位
  * ISUCON7 予選敗退
  * ISUCON6 運営・本選出題
  * ISUCON5 本選出場
  * ISUCON4 準優勝

#### ISUCON9

運営として予選の問題を出題

https://github.com/isucon/isucon9-qualify

  * 参照実装の実装・ベンチマーカーの実装など多数
    * ISUCON9予選の出題と外部サービス・ベンチマーカーについて - catatsuy - Medium https://medium.com/@catatsuy/isucon9-qualify-969c3abdf011

#### ISUCON6

運営として本選の問題を出題

https://github.com/isucon/isucon6-final

  * ansibleやGoの参照実装作成など多数
    * ISUCON6が終わったので出題した感想ポエム #isucon - catatsuyとは https://catatsuy.hateblo.jp/entry/2016/10/23/223202
    * ISUCON6本選のベンチマークでconsulを使用してクラスタを構築した話 / isucon6-night // Speaker Deck https://speakerdeck.com/catatsuy/isucon6-night

#### 社内ISUCON

ISUCON運営準備として社内ISUCONを作成。社内ISUCONとして採用実績多数、GitHubのスターも100超え。

https://github.com/catatsuy/private-isu

  * 問題の発案、Rubyの初期実装作成
  * Goによるベンチマーカー作成
  * Goの参考実装作成

など多数のことを行った。

  * ISUCON6出題チームが社内ISUCONを開催！AMIも公開！！ - pixiv inside [archive] https://devpixiv.hatenablog.com/entry/2016/05/18/115206
  * 社内ISUCONを公開したら広く使われた話 - pixiv inside [archive] https://devpixiv.hatenablog.com/entry/2016/09/26/130112
    * このエントリー公開後にも増えている

### オープンソース貢献

日常的に行っている。いくつかリンクを紹介する。

  * net/http: fix the old url about deflate (Iaa146829) · Gerrit Code Review https://go-review.googlesource.com/c/go/+/155217
  * support to add relative path dynamic-module in configure by catatsuy · Pull Request #343 · openresty/openresty https://github.com/openresty/openresty/pull/343
  * Can not execute code written in README by catatsuy · Pull Request #187 · pelletier/go-toml https://github.com/pelletier/go-toml/pull/187
  * Support for LibreSSL by catatsuy · Pull Request #23 · cubicdaiya/nginx-build https://github.com/cubicdaiya/nginx-build/pull/23
  * replace wget with the implementation of go by catatsuy · Pull Request #25 · cubicdaiya/nginx-build https://github.com/cubicdaiya/nginx-build/pull/25
  * save it as a temporary file during downloading by catatsuy · Pull Request #40 · cubicdaiya/nginx-build https://github.com/cubicdaiya/nginx-build/pull/40
  * remove cgo by catatsuy · Pull Request #5 · cubicdaiya/cachectl https://github.com/cubicdaiya/cachectl/pull/5
  * add unixtimestamp_key_names by catatsuy · Pull Request #47 · tagomoris/fluent-plugin-mysql https://github.com/tagomoris/fluent-plugin-mysql/pull/47


### 趣味プロダクト

ISUCON関係のものが多い

  * catatsuy/notify_slack: post to Slack on the command line https://github.com/catatsuy/notify_slack
    * ISUCONの情報共有にはこれ！notify_slack！/isucon_notify_slack - Speaker Deck https://speakerdeck.com/catatsuy/isucon-notify-slack
    * 標準入力を適当にまとめてSlackに通知するnotify_slackを作りました – Tatsuya Kaneko – Medium https://medium.com/@catatsuy/標準入力を適当にまとめてslackに通知するnotify-slackを作りました-e2e725a91c64

### 登壇

社内外の勉強会、カンファレンスで発表を行っている。

  * mercari.go #4を開催しました - Mercari Engineering Blog https://tech.mercari.com/entry/2018/11/16/120000
    * 発表資料 https://gist.github.com/catatsuy/e627aaf118fbe001f2e7c665fda48146
  * HTTPS化についてヤフー・クックパッド・ピクシブが語る！ - 大規模HTTPS導入Night - connpass https://pixiv.connpass.com/event/57970/
    * 完全HTTPS化のメリットと極意を大規模Webサービス――ピクシブ、クックパッド、ヤフーの事例から探る：大規模HTTPS導入Night - ＠IT http://www.atmarkit.co.jp/ait/articles/1707/13/news010.html
    * ヤフー・クックパッド・ピクシブの現場エンジニアが語った、HTTPS化の裏側と対応のコツとは？｜CodeIQ MAGAZINE（CodeIQ MAGAZINE提供終了のためアーカイブ） https://getnews.jp/archives/1882952
  * GitLab Meetup Tokyo #1 - connpass https://gitlab-jp.connpass.com/event/49755/
    * ちゃんと復旧できる、GitLabのバックアップ運用方法 ─ GitLab meetup #01レポート - pixiv inside https://inside.pixiv.blog/catatsuy/805
    * GitLabの実践的な運用 #gitlabjp - Qiita https://qiita.com/catatsuy/items/b7fda84ca9cb3dbcdc79
    * GitLabの運用方法をドーンと公開！！ - pixiv inside [archive] https://devpixiv.hatenablog.com/entry/2016/12/17/100000

他多数


## 著作

  * pixivエンジニアが教えるプログラミング入門 (星海社新書) | 金子 達哉 |本 | 通販 | Amazon https://www.amazon.co.jp/dp/4061385682
    * 単著
    * 自分が発案した社内のプログラミング研修の内容の書籍化

以下はレビューを行ったもの

  * nginx実践入門 (WEB+DB PRESS plus) 技術評論社 久保達彦 道井俊介
  * WEB+DB PRESS Vol.100 特集2 対応必須！ 完全HTTPS化 移行手順からつまずくポイントまで
    * コラムでpixivの事例紹介あり
  * Software Design 2017年10月号 第1特集 個人でも会社でも使える！ これだけは知っておきたいGitのキホン 第6章：Git活用の実例［1］ クラウド=GitHubとオンプレ=GitLabを使い分けるピクシブ
    * 元々は自分に執筆依頼が来たが、社内の後輩に譲り、レビューを行った


## プログラミングスキル

  * Go
    * HTTPプロクシサーバー開発
      * Goでproxy serverを作るときにハマるポイント - Mercari Engineering Blog https://tech.mercari.com/entry/2018/12/05/105737
    * 広告配信サーバー開発
    * ISUCONのベンチマーカー
    * ISUCON参考実装作成
  * PHP
    * pixivの開発で主に利用
    * PHP7化も担当
    * pixivFANBOXのリリース、内部実装の見直しなど、アプリケーションの実装を多数担当
  * Ruby
    * Ruby on Railsのアプリケーションサーバーの運用を担当
    * 社内ISUCONの初期実装に利用
    * 社内プログラミング研修に利用（その後書籍化）
    * Ruby on Rails製のGitLabへのContribute経験あり
      * GitLabのスロークエリを駆逐するマージリクエストを送りました - catatsuyとは https://catatsuy.hateblo.jp/entry/2015/06/16/234243
    * fluentdのpluginへのContribute経験あり
      * fluent-plugin-mysqlへの変更が全部取り込まれました – Tatsuya Kaneko – Medium https://medium.com/@catatsuy/fluent-plugin-mysqlへの変更が全部取り込まれました-cfde4526d28b
  * JavaScript
    * ログイン基盤作成に使用
      * ポップアップウィンドウを使用してログイン基盤を作るときにハマるJavaScriptのポイント - Qiita https://qiita.com/catatsuy/items/babce8726ea78f5d25b1
    * 配信広告の挙動調査などで利用
