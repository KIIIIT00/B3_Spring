# Git
## リポジトリのクローン
``` $git clone git@github.com:KIIIIT00/B3_Spring.git ```

## ファイルのステージング，コミット，プッシュ
```
$ git add example_file //example_fileをステージする場合
$ git add . //全ての変更をステージする場合
$ git commit -m "コミットメッセージ"
$ git push origin ブランチ名 //ローカルの変更をリモートリポジトリに反映
```

## リモートから変更を取得
```
$ git pull
```

## Tips
### ローカルの変更を確認
```
$ git status
```

### ログの確認
```
$ git log
$ git log --oneline //より詳細なログを確認するとき
```

### 差分の確認
```
$ git diff //変更点を確認
$ git diff diff_file //diff_fileの変更点を確認
```

### addの取り消し
```
$ git reset HEAD //全てのファイルを取り消し
$ git reset HEAD file_name //特定のファイルのみ取り消し
```

### commitの取り消し
```
$ git reset --hard HEAD^
```

### コミットメッセージの修正
```
$ git commit --amend "新たなコミットメッセージ"
```

### 退避
```
$ git stash //作業途中の変更を一時的に退避させる
$ git stash pop //再び作業を再開する
```

### ブランチ名の変更
```
$ git branch -m <古いブランチ名> <新しいブランチ名>

```


