##ffmpeg静态库编译脚本

---------

#编译步骤

1.安装mac编译器

> cp ./gas-preprocessor.pl /usr/local/bin/gas-preprocessor.pl

> chmod 777 /usr/local/bin/gas-preprocessor.pl

2.编译配置

> 编辑build-ffmpeg.sh

> 修改ffmpeg版本环境变量 VERSION，截至 2014-12-18 最新版本2.5.1，由于缺少汇编脚本，使用2.1.1

> 修改iOS编译器版本环境变量 SDKVERSION

3.运行编译

> sh ./build-ffmpeg.sh

4.编译好的静态库保存在以下目录

> ./build/built