# sibyl

* `sibyl`：还原标准库中的符号表
  * 是什么：an enhanced API bruteforcing tool
  * 概述：sibyl 可以将一些原始的二进制文件中的标准库函数还原，识别库函数的符号表
  * Github
    * GitHub - cea-sec/Sibyl: A Miasm2 based function divination.
      * https://github.com/cea-sec/Sibyl
  * 其他类似/竞品工具
    * Bindiff
      * 基于`CFG`签名
        * `CFG`=`Control Flow Graph`
    * FindCrypt
      * 基于魔术常量`magic constants`
    * FLIRT
      * 基于增强的模式匹配enhanced pattern matching
  * 语法
    ```bash
    lys@ubuntu:~/Tools/miasm-0.1.1$ sibyl
    Usage: /usr/local/bin/sibyl [action]

    Actions:
      config   Configuration management  
      find     Function guesser          
      func     Function discovering      
      learn    Learn a new function 
    ```
  * 举例
    * 打印函数
      ```bash
      sibyl func -a arml u-boot.bin.elf > funcs.txt
      ```
    * 转换函数
      ```bash
      sibyl find -a arml -b ABI_ARM u-boot.bin.elf funcs.txt
      ```
    * 效果
      ```bash
        Python>
        Launch identification on 3085 function(s)
        Found memcpy at 0x8057120
        Found memmove at 0x805714c
        Found memset at 0x8057174
        Found strcat at 0x80571a8
        Found strchr at 0x80571cc
        Found strcmp at 0x8057208
        Found strcpy at 0x8057228
        Found strlen at 0x8057244
        Found strncmp at 0x8057258
        Found strncpy at 0x8057280
        Found strnlen at 0x80572a8
        Found strrchr at 0x80572c0
        Found memcmp at 0x80572ff
        Found strsep at 0x80576ac
        Found strspn at 0x8057704
        Found stricmp at 0x805799c
        Found strpbrk at 0x8057ab8
        Found strtok at 0x8057b30
        Found strcmp at 0x8057b48
        Found atoi at 0x805df1c
        Current: 64.83% (sub_0x80b4ab3)| Estimated time remaining: 14.45s
        Found atoi at 0x80f1cf3
        Current: 100.00% (sub_0x80f7a93)| Estimated time remaining: 0.00s
        Finished ! Found 21 candidates in 42.70s
        Results are also available in 'sibyl_res'
      ```
