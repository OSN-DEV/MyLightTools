# pre-commit
ローカルレポジトリにローカルのユーザー・メールアドレスの設定を強要させるためのhookスクリプト。
既に作成済みのレポジトリの場合は`.git/hooks`に配置する。

`git init`でこのファイルをデフォルトで配置させるには`C:\Program Files\Git\mingw64\share\git-core\templates\hooks`にスクリプトを配置しておく。

ちなみにローカルのユーザー・メールアドレスはの設定は以下のコマンドで設定する。
```
// 設定
git config --local user.name "tk at office"
git config --local user.email "mail@office"

// 確認
git config --local --list
```

# windows
## reboot.bat / shutdown.bat
コールドブートできるようにするための再起動・シャットダウンのスクリプト。

# apple
#### ResetAlbumRate selection.scpt
選択したアルバムのレーティングをリセット

#### SetPlayCount.scpt
再生回数を設定

#### SetPlayCount1.scpt
再生回数を１、レーティングを１、選択を解除

#### SetPlayCount2.scpt
再生回数を１、レーティングを２、選択を解除

#### SetPlayCount3.scpt
再生回数を１、レーティングを１、選択を解除

