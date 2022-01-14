
# raylib info

I had a LOT of trouble getting the makefiles to work for raylib.

Something odd about linux and python3

I downloaded emsdk and installed and set latest

I downloaded a release zip of raylib

## to compile for web
```bash
cd emsdk
source ./emsdk_env.sh
cd ..
cd raylib-4.0.0
cd src
make -f makefile.tony
```