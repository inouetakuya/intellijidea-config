intellijidea-config
===================

JetBrains 製の Java IDE「IntelliJ IDEA」の設定ファイル

* http://www.jetbrains.com/idea/

## Getting started

```
cd ~/Library/Preferences/IntelliJIdea13
git init
git remote add origin git@github.com:inouetakuya/intellijidea-config.git
git pull origin master
```

下記のエラーとなる場合がある

```
error: Untracked working tree file 'foo/bar' would be overwritten by merge.
```

下記で対応する

```
git reset
git checkout .
```

それでもダメなら Git を駆使してがんばる

