# learn_linux
Linuxの使い方をまとめながら再学習する

基本的に ssh などの CLI(TTY？noGUI？何て言ったらいんだ？) を前提に書く



# 基礎
- 困ったら
  + help
  + man コマンド
  + コマンド --help
  + ググる

- 作業ディレクトリ移動
  + cd パス
  + pushd パス
  + popd

- ファイル一覧表示
  + ls

- ファイルの内容を表示
  + cat ファイルパス
  + less ファイルパス
  + more ファイルパス

- 出力が長すぎて表示がはみ出る場合
  + コマンド | less

- 管理者権限
  + sudo

- ソフトのインストールなど
  + apt
    * debian系
  + apt-get
    * debian系
  + dpkg
    * debian系 / .deb パッケージのインストールなど
  + pacman
    * arch系 / msys2-mingwなど
  + yum
    * readhat系
  + など


[EOF]