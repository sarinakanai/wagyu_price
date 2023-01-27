# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

- リモートリポジトリとは専用のサーバに配置して複数人で共有するためのリポジトリです。Githubなど
- ローカルリポジトリとはユーザ一人ひとりが利用するために、自分の手元のマシン上に配置するリポジトリです。
- リポジトリとは、ファイルやディレクトリの履歴を管理する場所のことです。

## プッシュとマージの違いは何でしょうか？

- プッシュは、追加・変更した情報をローカルリポジトリからリモートリポジトリに送る操作です。
- マージは、別のブランチの作業内容(変更履歴)をブランチに取り込むこと
- なので、違いとしては作業用のブランチを切り、編集しその変更内容をマージすることにより別のブランチに取り組むことが出来、その情報をローカルからリモートに送ることをプッシュと言います。

## コミットとプッシュの違い

- コミットとは編集したファイルを保存する時、新しくフォルダを作る時に名前を付けてローカルのリポジトリに履歴として記録されます。
- プッシュは、追加・変更した情報をローカルリポジトリからリモートリポジトリに送る操作です。
- なので、編集した時、新しくフォルダを作る時に名前をつけてローカルリポジトリに記録させ、それをローカルリポジトリからリモートリポジトリに送る操作をプッシュと言います。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- どういった変更をしたのかを具体的にわかりやすく書いてあげる。誰がみてもわかるようにする。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- ローカルでマージするフロー　ローカル上で別のブランチにマージし、リモートのブランチにプッシュし、リモートに更新させる。
- プルリクエストでマージするフロー　プルリクエストを作成し、リモート上でコードレビューをしてからマージするという手順を踏む。
- ローカルでマージするとコードレビューをする前にメインに反映されるため、コードにバグがあっても気づかない可能性がでてきますが、プルリクエストでマージすると事前にバグを発見する事ができます。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

- 先にマージされた変更内容を取り込む
- 後にマージしようとしている変更内容を取り込む
- どちらの変更内容も取り込む