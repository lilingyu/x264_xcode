#This is a xcode project for debugging x264

## how to setup?

```shell
mkdir x264-xcode
cd x264-xcode
#git clone thisRepo
bash-3.2$ ls build/x264-xcode
README.md               x264-xcode              x264-xcode.xcodeproj
#git clone x264
bash-3.2$ ls x264/
AUTHORS         common          config.mak      encoder         input           x264.c          x264cli.h
COPYING         config.guess    config.sub      example.c       output          x264.h          x264dll.c
Makefile        config.h        configure       extras          tools           x264.pc         x264res.rc
autocomplete.c  config.log      doc             filters         version.sh      x264_config.h

cd x264
./configure
#in config.mak, replace -O3 width -g for debug
```
