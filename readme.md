
# raylib info

## to compile for web (in raylib4 directory)

I had a LOT of trouble getting the makefiles to work for raylib.

Official words here: https://github.com/raysan5/raylib/wiki/Working-for-Web-(HTML5)

Something odd about linux and python3

I downloaded emsdk and installed and set latest

I downloaded a release zip of raylib

```bash
cd emsdk
source ./emsdk_env.sh
cd ..
cd raylib-4.0.0
cd src
make -f makefile.tony
```

## to compile for the web an actual game

See the makefile.tony.game file to see what I did. It is messy