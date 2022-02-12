# display_git_repo_user
リポジトリ内にいるとき`git config user.name`の内容を表示します。

~~リポジトリルートじゃないと表示できないから要改善~~
-> 済み

## how to use
1. `.dysplay_git_user_name`にメアド、ユーザー名を置き換え
2. `.dysplay_git_user_name`を`$HOME`に置く
3. `~/.bashrc`に`source ~/.dysplay_git_user_name`を追記する
4. `.bashrc`をリロード

リポジトリ作成時は`git-set ユーザー名`


## Exit Code
- 0: 正常終了
- 1: ユーザー名未設定
- 2: `git init`がエラー
- 3: 引数エラー
- 128: リポジトリが見つからない
