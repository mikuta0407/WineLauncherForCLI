phpを使ったwine用ランチャー(CLI)

とりあえず現状Mac(M1)用


User manual

Start mode:
    win [aliasname]
    
    example:
        To start Domino.exe:
        "win domino"

Show list:
    win list

Add mode: 
    win add [aliasname] [exe file path] [Display name]

    example:
        To add Domino.exe:
        "win add domino Domino.exe Domino"

    You don't need to worry about the path of the exe file 
    because the file path will be automatically converted 
    when additional processing is done.