# rbasefind

* `rbasefind`：查找固件基地址
  * 概述：暴力查找固件在内存中的基地址的工具
  * 背景：在拿到固件的第一步，最重要的就是确定基地址，这样才能让`IDA`识别更多的函数和字符串
  * Github
    * https://github.com/sgayou/rbasefind
  * 用法举例
    ```bash
    lys@ubuntu:~/Documents/test$ rbasefind u-boot.bin
    Located 10 strings
    Located 72155 pointers
    Scanning with 8 threads...
    0x80700000: 8
    0xff22d000: 1
    0xfe3a6000: 1
    0xfdb83000: 1
    0xfca84000: 1
    0xfbf1d000: 1
    0xfb632000: 1
    0xf965e000: 1
    0xf7bae000: 1
    0xf777a000: 1
    ```
