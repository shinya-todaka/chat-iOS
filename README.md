# chat-iOS
## setup
以下のコマンドを実行した後、デバッグ環境の場合chat-iOS/Resources/GoogleInfoにGoogle-Info-dev.plistを入れる
※ Google-Info.plistからGoogle-Info-dev.plistに改名する
```
homebrewをインストールしていない場合
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
carthageをインストールしていない場合
$ brew install carthage
mintをインストールしていない場合
$ brew install mint
$ make all
```
