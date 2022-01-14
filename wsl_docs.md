# getting started on WSL

Installed emsdk

Installed my raylibinfo repo

Installed raylib4 source from release page on github

Now get the template from my github
git clone git@github.com:tonetheman/raylibtemplatetest.git

Look in the makefiles in raylibinfo directory
```
CHANGE THE HOME DIRECTORY REFERENCE
```

This is what the dir looks like at the end of that
```
agcc@LAPTOP-TRQQOHPO:~$ ls -ltr
total 20
drwxr-xr-x  9 agcc agcc 4096 Nov  4 14:08 raylib-4.0.0
drwxr-xr-x  6 agcc agcc 4096 Jan 10 15:27 node-v16.13.2-linux-x64
drwxr-xr-x 12 agcc agcc 4096 Jan 13 13:39 emsdk
drwxr-xr-x  5 agcc agcc 4096 Jan 14 08:25 raylibtemplatetest
drwxr-xr-x  3 agcc agcc 4096 Jan 14 08:29 raylibinfo
agcc@LAPTOP-TRQQOHPO:~$ pwd
/home/agcc
agcc@LAPTOP-TRQQOHPO:~$
```


Make the library
```
cd raylib-4.0.0
cd src
make -f ~/raylibinfo/makefile.tony.raylib4
```

Make the game
```
cd raylibtemptest
cd src
make -f ~/raylibinfo/makefile.tony.game
```

