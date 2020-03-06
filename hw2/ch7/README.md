# Chapter 7: Wildcards #

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221 (master)
    $ cd hw2/linuxtutorialwork

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ pwd
    /c/Users/Mari/csc221/hw2/linuxtutorialwork

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    backups/  barney  fred/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls b*
    barney

    backups:
    foo/

**Some more example**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    backups/  barney  barry.txt  blah.txt  fred/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls ~/csc221/hw2/linuxtutorialwork/*.txt
    /c/Users/Mari/csc221/hw2/linuxtutorialwork/barry.txt
    /c/Users/Mari/csc221/hw2/linuxtutorialwork/blah.txt

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls ?a*
    barney  barry.txt

    backups:
    foo/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls *.???
    barry.txt  blah.txt