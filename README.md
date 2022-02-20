# WineLauncherForCLI

phpを使ったwine用ランチャー(CLI)

とりあえず現状Mac(M1)用


## User manual

- Start mode:
    - `win [aliasname]`
    
    - example:
        - To start Domino.exe: `win domino`

- Show list: `win list`

- Add mode: 
    - `win add [aliasname] [exe file path] [Display name]`

    - example:
        - To add Domino.exe:
        `win add domino Domino.exe Domino`

    - You don't need to worry about the path of the exe file because the file path will be automatically converted when additional processing is done.

## requirement
- phpが必要
- 現状のプログラムをそのまま使うにはMac (phpのパス的にM1)が必要
    - 冒頭の部分を変えればM1以外のMacでもOK(自動判別対応したい)
    - 冒頭の部分と、ユーザー名の置換処理時のパスを変えればLinuxでもOK(自動判別対応したい)
- `win`ファイルがあるディレクトリにパスを通せば動くように、拡張子を消して、冒頭にphpへのパスを記載しています。まぁ複雑な事書いてないので適当に書き換えて使ってもらって大丈夫です。

## License

特に制限をしません。ご自由にお使いください。犯罪にさえ使わなければ何をしてもいいです。

There are no particular restrictions. Feel free to use it. You can do anything as long as you don't even use it for crime.