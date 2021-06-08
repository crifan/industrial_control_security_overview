# embedded-toolkit

* `embedded-toolkit`：跨平台的嵌入式程序
  * 概述：严格意义上来说，这并不是一个工具，而是一个编译好的工具集
  * 包括工具
    * `tcpdump` (statically linked
    * `gawk` (statically linked)
    * `lsof` (statically linked)
    * `gdbserv` (statically linked)
    * `tshd` (statically linked)
    * `mawk` (statically linked)
    * `libpcap` (static library, used for linking into tcpdump so not present in this repo)
  * 说明
    * 这些已经编译好的二进制，包含了多个平台，如 x86、arm、mips，如果不想花时间在交叉编译上，可以使用它们，但不保证二进制有没有安全问题
  * GitHub
    * https://github.com/akpotter/embedded-toolkit
