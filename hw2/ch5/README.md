# File Manipulation #


    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ ls
    ch1/   ch11/  ch13/  ch3/  ch5/  ch7/  ch9/
    ch10/  ch12/  ch2/   ch4/  ch6/  ch8/

**Making a directory**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ mkdir linuxtutorialwork

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ ls
    ch1/   ch11/  ch13/  ch3/  ch5/  ch7/  ch9/
    ch10/  ch12/  ch2/   ch4/  ch6/  ch8/  linuxtutorialwork/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ mkdir -p linuxtutorialwork/foo/bar

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ cd linuxtutorialwork/foo/bar

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork/foo/bar (master)
    $ pwd
    /c/Users/Mari/csc221/hw2/linuxtutorialwork/foo/bar

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork/foo/bar (master)
    $

**Removing a Directory**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork/foo (master)
    $ cd ../../

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ rmdir linuxtutorialwork/foo/bar

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ ls linuxtutorialwork/foo

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)

**Creating a blank file**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ pwd
    /c/Users/Mari/csc221/hw2

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ cd linuxtutorialwork

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    foo/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ touch example1

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    example1  foo/

**Copying a file or directory**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls example1 foo
    example1

    foo:

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ cp example1 barney

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    barney  example1  foo/

**Moving a file or directory**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    barney  example1  foo/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ mkdir backups

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ mv foo backups/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    backups/  barney  example1

**Renaming files and directories**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ cd ..

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ mkdir linuxtutorialwork/testdir

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ mv linuxtutorialwork/testdir ~/csc221/hw2/linuxtutorialwork/fred

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ ls linuxtutorialwork
    backups/  barney  example1  fred/

**Removing a file**

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2 (master)
    $ cd linuxtutorialwork

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    backups/  barney  example1  fred/

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ rm example1

    Mari@DESKTOP-H60JHVG MINGW64 ~/csc221/hw2/linuxtutorialwork (master)
    $ ls
    backups/  barney  fred/