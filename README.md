# nvimの設定
## 前処理
  - bash_profile,zshrcのどちらかに"export XDG_BASE_HOME='~/.config'"を記載
  ```bash
    curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
    sh ./installer.sh ~/.config/nvim/dein
  ```
  - vimと打ってもnvimが起動する
    - zshrc,bashrcのどちらかに"alias vim='nvim'"を記述

