# Chapter 4 : Manual Pages #

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ man ls
    bash: man: command not found


    PS C:\Users\Mari> man ls

    NAME
        Get-ChildItem

    SYNTAX
        Get-ChildItem [[-Path] <string[]>] [[-Filter] <string>] [-Include <string[]>] [-Exclude <string[]>]
        [-Recurse] [-Depth <uint32>] [-Force] [-Name] [-UseTransaction] [-Attributes {ReadOnly | Hidden | System
        | Directory | Archive | Device | Normal | Temporary | SparseFile | ReparsePoint | Compressed | Offline |
        NotContentIndexed | Encrypted | IntegrityStream | NoScrubData}] [-Directory] [-File] [-Hidden]
        [-ReadOnly] [-System]  [<CommonParameters>]

        Get-ChildItem [[-Filter] <string>] -LiteralPath <string[]> [-Include <string[]>] [-Exclude <string[]>]
        [-Recurse] [-Depth <uint32>] [-Force] [-Name] [-UseTransaction] [-Attributes {ReadOnly | Hidden | System
        | Directory | Archive | Device | Normal | Temporary | SparseFile | ReparsePoint | Compressed | Offline |
        NotContentIndexed | Encrypted | IntegrityStream | NoScrubData}] [-Directory] [-File] [-Hidden]
        [-ReadOnly] [-System]  [<CommonParameters>]


    ALIASES
        gci
        ls
        dir


    REMARKS
        Get-Help cannot find the Help files for this cmdlet on this computer. It is displaying only partial help.
            -- To download and install Help files for the module that includes this cmdlet, use Update-Help.
            -- To view the Help topic for this cmdlet online, type: "Get-Help Get-ChildItem -Online" or
            go to https://go.microsoft.com/fwlink/?LinkID=113308.


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ pwd
    /c/Users/Mari


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ ls -a
    ./
    ../
    .bash_history
    .gitconfig
    .ipython/
    .lesshst
    .pylint.d/
    .ssh/
    .viminfo
    .vscode/
    '3D Objects'/
    AppData/
    'Application Data'@
    Contacts/
    Cookies@
    courses/
    csc121/
    csc221/
    Desktop/
    Documents/
    Downloads/
    ex25.py
    ex26.py
    Favorites/
    Hw_2/
    IntelGraphicsProfiles/
    'lets do this'/
    'lets do this it will be fun'/
    Links/
    'Local Settings'@
    MicrosoftEdgeBackups/
    Music/
    'My Documents'@
    NetHood@
    NTUSER.DAT
    ntuser.dat.LOG1
    ntuser.dat.LOG2
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.0.regtrans-ms
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.1.regtrans-ms
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.2.regtrans-ms
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.blf
    NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TM.blf
    NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer00000000000000000001.regtrans-ms
    NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer00000000000000000002.regtrans-ms
    ntuser.ini
    OneDrive/
    Pictures/
    PrintHood@
    Recent@
    'Saved Games'/
    Searches/
    SendTo@
    'Start Menu'@
    temp/
    Templates@
    Videos/


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ ls --all
    ./
    ../
    .bash_history
    .gitconfig
    .ipython/
    .lesshst
    .pylint.d/
    .ssh/
    .viminfo
    .vscode/
    '3D Objects'/
    AppData/
    'Application Data'@
    Contacts/
    Cookies@
    courses/
    csc121/
    csc221/
    Desktop/
    Documents/
    Downloads/
    ex25.py
    ex26.py
    Favorites/
    Hw_2/
    IntelGraphicsProfiles/
    'lets do this'/
    'lets do this it will be fun'/
    Links/
    'Local Settings'@
    MicrosoftEdgeBackups/
    Music/
    'My Documents'@
    NetHood@
    NTUSER.DAT
    ntuser.dat.LOG1
    ntuser.dat.LOG2
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.0.regtrans-ms
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.1.regtrans-ms
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.2.regtrans-ms
    NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.blf
    NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TM.blf
    NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer00000000000000000001.regtrans-ms
    NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer00000000000000000002.regtrans-ms
    ntuser.ini
    OneDrive/
    Pictures/
    PrintHood@
    Recent@
    'Saved Games'/
    Searches/
    SendTo@
    'Start Menu'@
    temp/
    Templates@
    Videos/


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ ls -alh
    total 6.7M
    drwxr-xr-x 1 Mari 197121    0 Feb 21 01:11  ./
    drwxr-xr-x 1 Mari 197121    0 Aug 17  2019  ../
    -rw-r--r-- 1 Mari 197121 1.3K Feb 21 10:07  .bash_history
    -rw-r--r-- 1 Mari 197121   71 Feb 21 01:11  .gitconfig
    drwxr-xr-x 1 Mari 197121    0 Dec  6 14:04  .ipython/
    -rw-r--r-- 1 Mari 197121   34 Feb  5 10:40  .lesshst
    drwxr-xr-x 1 Mari 197121    0 Feb 19 11:59  .pylint.d/
    drwxr-xr-x 1 Mari 197121    0 Jan 13 14:05  .ssh/
    -rw-r--r-- 1 Mari 197121  558 Jan 27 13:20  .viminfo
    drwxr-xr-x 1 Mari 197121    0 Feb 21 10:20  .vscode/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54 '3D Objects'/
    drwxr-xr-x 1 Mari 197121    0 Aug 15  2019  AppData/
    lrwxrwxrwx 1 Mari 197121   29 Aug 15  2019 'Application Data' -> /c/Users/Mari/AppData/Roaming/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Contacts/
    lrwxrwxrwx 1 Mari 197121   57 Aug 15  2019  Cookies -> /c/Users/Mari/AppData/Local/Microsoft/Windows/INetCookies/
    drwxr-xr-x 1 Mari 197121    0 Jan 22 13:13  courses/
    drwxr-xr-x 1 Mari 197121    0 Feb 19 11:57  csc121/
    drwxr-xr-x 1 Mari 197121    0 Feb 21 00:07  csc221/
    drwxr-xr-x 1 Mari 197121    0 Feb 18 01:57  Desktop/
    drwxr-xr-x 1 Mari 197121    0 Feb 21 00:55  Documents/
    drwxr-xr-x 1 Mari 197121    0 Feb 17 10:17  Downloads/
    -rw-r--r-- 1 Mari 197121 1018 Nov  5 21:57  ex25.py
    -rw-r--r-- 1 Mari 197121 2.2K Dec  4 08:37  ex26.py
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Favorites/
    drwxr-xr-x 1 Mari 197121    0 Dec  6 14:41  Hw_2/
    drwxr-xr-x 1 Mari 197121    0 Feb 23 16:49  IntelGraphicsProfiles/
    drwxr-xr-x 1 Mari 197121    0 Aug 26 22:39 'lets do this'/
    drwxr-xr-x 1 Mari 197121    0 Aug 26 22:41 'lets do this it will be fun'/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Links/
    lrwxrwxrwx 1 Mari 197121   27 Aug 15  2019 'Local Settings' -> /c/Users/Mari/AppData/Local/
    drwxr-xr-x 1 Mari 197121    0 Aug 15  2019  MicrosoftEdgeBackups/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Music/
    lrwxrwxrwx 1 Mari 197121   23 Aug 15  2019 'My Documents' -> /c/Users/Mari/Documents/
    lrwxrwxrwx 1 Mari 197121   65 Aug 15  2019  NetHood -> '/c/Users/Mari/AppData/Roaming/Microsoft/Windows/Network Shortcuts'/
    -rw-r--r-- 1 Mari 197121 1.8M Nov 17 21:38  NTUSER.DAT
    -rw-r--r-- 1 Mari 197121 532K Aug 15  2019  ntuser.dat.LOG1
    -rw-r--r-- 1 Mari 197121 160K Aug 15  2019  ntuser.dat.LOG2
    -rw-r--r-- 1 Mari 197121 1.0M Feb 23 16:50  NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.0.regtrans-ms
    -rw-r--r-- 1 Mari 197121 1.0M Feb 18 01:37  NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.1.regtrans-ms
    -rw-r--r-- 1 Mari 197121 1.0M Feb 18 01:37  NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.2.regtrans-ms
    -rw-r--r-- 1 Mari 197121  64K Feb 23 16:50  NTUSER.DAT{1c3790b3-b8ad-11e8-aa21-e41d2d101530}.TxR.blf
    -rw-r--r-- 1 Mari 197121  64K Aug 15  2019  NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TM.blf
    -rw-r--r-- 1 Mari 197121 512K Aug 15  2019  NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer00000000000000000001.regtrans-ms
    -rw-r--r-- 1 Mari 197121 512K Aug 15  2019  NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer00000000000000000002.regtrans-ms
    -rw-r--r-- 1 Mari 197121   20 Aug 15  2019  ntuser.ini
    drwxr-xr-x 1 Mari 197121    0 Feb 23 22:59  OneDrive/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Pictures/
    lrwxrwxrwx 1 Mari 197121   65 Aug 15  2019  PrintHood -> '/c/Users/Mari/AppData/Roaming/Microsoft/Windows/Printer Shortcuts'/
    lrwxrwxrwx 1 Mari 197121   54 Aug 15  2019  Recent -> /c/Users/Mari/AppData/Roaming/Microsoft/Windows/Recent/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54 'Saved Games'/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Searches/
    lrwxrwxrwx 1 Mari 197121   54 Aug 15  2019  SendTo -> /c/Users/Mari/AppData/Roaming/Microsoft/Windows/SendTo/
    lrwxrwxrwx 1 Mari 197121   58 Aug 15  2019 'Start Menu' -> '/c/Users/Mari/AppData/Roaming/Microsoft/Windows/Start Menu'/
    drwxr-xr-x 1 Mari 197121    0 Aug 26 22:26  temp/
    lrwxrwxrwx 1 Mari 197121   57 Aug 15  2019  Templates -> /c/Users/Mari/AppData/Roaming/Microsoft/Windows/Templates/
    drwxr-xr-x 1 Mari 197121    0 Feb 14 01:54  Videos/


**Activity**


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ man ls
    bash: man: command not found