# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリはネット上にファイルをアップロードした状態でファイルを管理するものであり、
ローカルリポジトリは、自分のPC内でファイル等の状態を管理する。

## プッシュとマージの違いは何でしょうか？

プッシュは、自己のローカルリポジトリでの変更履歴をリモートリポジトリで共有すること。
マージは、別のブランチでの作業内容を他のブランチに変更履歴を取り込む点で異なる。

## コミットとプッシュの違い

コミットは作業内容を自己のリポジトリに記録するのであって、プッシュは、リモートリポジトリに作業内容を記録する。
記録する場所が異なる。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

1行目に変更内容の要約を記載し、
2行目に変更した理由を記載することで、変更した点を理解でき、
内容や詳細を確認するには、そのあとを読めばわかるため。

## プルリクエストとは何か

ローカルリポジトリでの変更内容をマージしてもらう依頼を行うこと

## コンフリクトとは何か

複数人が同じ場所を変更したことをマージしようとした際に生じる
エラー的なもの