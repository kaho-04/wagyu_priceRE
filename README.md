# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれなんでしょうか？
* リモートリポジトリ
    * githubにあるデータの保存場所
* ローカルリポジトリ
    * PCにあるデータの保存場所


## プッシュとマージの違いは何でしょうか？
* プッシュ
  * リモートリポジトリにデータをアップすること
* マージ
  * 別のブランチに変更された箇所のあるブランチを取り込むこと


## コミットとプッシュの違い
* コミット
  * 作業などで変更した履歴を保存すること
* プッシュ
  * コミットしたデータをリモートリポジトリにアップすること

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
* 誰が見てもわかりやすく変更内容を正確に書く

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
* ローカルでマージするフローは、PC上でmainブランチ等に作業用ブランチ等を取り込む手順。
* プルリクエストでマージするフローは、リモートリポジトリ上のmainブランチなどに取り込んでほしい作業用ブランチ等を、レビュー担当者等に誤りが無いか確認してもらうことで取り込む手順。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
* コンフリクトを起こしてしまった場合は、３つの対処方法があり、状況に応じて選択する。
  * 先にマージされた変更内容を反映する
  * 後にマージされた変更内容を反映する
  * どちらの変更内容も反映する
