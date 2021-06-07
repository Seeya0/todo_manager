# Todo Manager
### https://todo-management-tool.herokuapp.com/

ユーザーごとにtodo管理ができるアプリです。

プログラミングを学び始めて1ヶ月半までにで学んだことをツールに入れ込み、アウトプットをしました。
主にDjangoを使用し作成しました。

# 作成した理由
部署内のタスク管理ができていないこと課題としてありました。

どの人がどんなタスクを持っていて、それらが終わっているかどうかがわからず、現状を把握することが困難でした。

それを解決しようと思って作ったのがこのアプリです。

ユーザーごとにタスク管理ができ、マネージャー（権限者）はユーザーごとの状態が見れられます。

●意識した点(工夫)　３点

・マネージャーはグループに入っているユーザー全てのタスクを見れること
何日の何時に部下がタスクを終わらせたかを把握でき、マネジメントができる。

・ユーザーごとにタスクを管理できること
現在のタスクと完了したタスクが見られる。
マネージャーはタスクがいつ完了したかを把握することができ、仕事の指示がしやすくなる

・ユーザーが重複をしないようにした

# ログイン方法
https://todo-management-tool.herokuapp.com/

上記URLにアクセスをしてください。

画面中央下の「Start」を押し、新規登録をしてください。

また、テストアカウントを用意してありますので、新規登録をせずに始めることもできます。

下記のアドレスとパスワードをご使用ください。

ユーザーネーム：test

パスワード:test

ログイン後は「タスクの作成」をクリックすことでタスク管理をすることができます。


# 使用技術
・Python 3.8.5

・Django　3.1.4

・JavaScript ES2020

・HTML/CSS

・Bootstrap 4

・SQlite

・gunicorn 20.0.4

・Heroku


# 機能一覧
・ユーザー登録/ログイン・ログアウト機能

・ユーザーごとのデータ管理

・タスクの追加、タスク管理

・データの作成、削除、完了したタスクの管理　CRUDを実装

・エラーハンドリング
ユーザー重複しない仕様

・管理者権限　ユーザーごとのタスク状況を把握
チームマネジメントを円滑にする