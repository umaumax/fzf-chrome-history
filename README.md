# fzf-chrome-history

Chromeの履歴をfzfで選択して開くことができるスクリプト

![Demo](https://user-images.githubusercontent.com/17779386/56350061-dc7bc180-6204-11e9-84cc-11f0cf919426.gif)

# Requirement

- OS X
- fzf
- GNU Coreutils(gdate)

# Usage

```sh
# 直近1万件の履歴を出力
$ sh chromeHistory.sh

# 予めgrepしたものを出力(fzfでは日付・タイトルしか表示されないので、URLで抽出したい人用)
$ sh chromeHistory.sh PATTERN

# 日付指定
$ sh chromeHistory.sh -d
```

# Option

fzfで表示される「export」を選択すると画面に出力します。

![demo_export.gif](https://user-images.githubusercontent.com/17779386/56843356-6a793b80-68da-11e9-84fa-d0d24e63f92f.gif)
