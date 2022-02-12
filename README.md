# display_git_repo_user
リポジトリ内にいるとき`git config user.name`の内容を表示します。

リポジトリルートじゃないと表示できないから要改善

## how to use
`.dysplay_git_user_name`を`$HOME`に置いて`~/.bashrc`に`source ~/.dysplay_git_user_name`を追記するだけ

## Exit Code
- 0: 正常終了
- 1: ユーザー名未設定
- 2: `git init`がエラー
- 3: 引数エラー
- 128: 
