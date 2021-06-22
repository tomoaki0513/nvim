# nvimの設定
<<<<<<< HEAD
=======
## 前処理
  - nodeをインストール
    - brew install node
  - python3をインストール
    - brew install python
  - nodeのneovimパッケージ
    - npm install -g neovim
  - python3のneovimパッケージ
    - pip3 install pynvim
  - bash_profile,zshrcのどちらかに"export XDG_BASE_HOME='~/.config'"を記載
  - プラグイン管理をdeinで行うためにインストール
  ```bash
    curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
    sh ./installer.sh ~/.config/nvim/dein
  ```
  - vimと打ってもnvimが起動する
    - zshrc,bashrcのどちらかに"alias vim='nvim'"を記述
>>>>>>> develop

