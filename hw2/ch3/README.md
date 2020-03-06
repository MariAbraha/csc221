# Chapter 3 : More about Files #

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ ls Documents
    'auto biography.docx'       'Custom Office Templates'/  'My Pictures'@
    Brooks-NoSilverBullet.pdf   desktop.ini                'My Videos'@
    csc121/                     important.pdf
    csc221/                    'My Music'@

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ file Documents/MyVideos
    Documents/MyVideos: cannot open `Documents/MyVideos' (No such file or directory)

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ ls Documents
    'auto biography.docx'       'Custom Office Templates'/  'My Pictures'@
    Brooks-NoSilverBullet.pdf   desktop.ini                'My Videos'@
    csc121/                     important.pdf
    csc221/                    'My Music'@

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ cd Myvideos
    bash: cd: Myvideos: No such file or directory

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ cd Documents

    Mari@DESKTOP-H60JHVG MINGW64 ~/Documents
    $ cd 'My videos'

    Mari@DESKTOP-H60JHVG MINGW64 ~/Documents/My videos
    $ pwd
    /c/Users/Mari/Documents/My videos


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ ls -a Documents
    ./                          csc121/                     important.pdf
    ../                         csc221/                    'My Music'@
    'auto biography.docx'       'Custom Office Templates'/  'My Pictures'@
    Brooks-NoSilverBullet.pdf   desktop.ini                'My Videos'@


    **Activity**


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ pwd
    /c/Users/Mari

    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ file Desktop
    Desktop: directory


    Mari@DESKTOP-H60JHVG MINGW64 ~
    $ file Desktop/Courses
    Desktop/Courses: directory

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