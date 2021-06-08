# 工控安全概览

如[信息安全概览](https://book.crifan.com/books/information_security_overview/website/)所总结，从技术领域分，信息安全大体可以分为：

* Web安全
  * =网络安全
* 移动端安全
* 工控安全

此处主要介绍工控领域内的安全：

* 工控安全，即在工控领域的安全相关技术的统称
  * 工控，全称**工业控制**
    * 工业，包含很多行业
      * 按照工业4.0
        * 抽象概念
          * ![concept_industrial_4](../assets/img/concept_industrial_4.jpg)
      * 工业控制的细分领域众多
        * 据调查近年来工控安全事件涉及超过 15 个行业
          * ![industrial_security_many_field](../assets/img/industrial_security_many_field.jpg)
        * 但目前工控市场安全只覆盖到了其中部分行业，要实现全面防护还有许多路要走
          * ![industrial_security_invest_low](../assets/img/industrial_security_invest_low.jpg)
  * 工控安全和传统互联网安全关系
    * ![net_security_industrial_control_security](../assets/img/net_security_industrial_control_security.png)
  * 工控安全概况
    * ![industrial_ctrl_security_overview](../assets/img/industrial_ctrl_security_overview.png)
    * ![industrial_ctrl_security_overall_trend](../assets/img/industrial_ctrl_security_overall_trend.png)

## 工控安全子方向

* 工控安全，其实也算是一个大的方向，其常见的具体的子方向包括
  * 工控固件逆向
    * 常涉及
      * Flash
        * 拆焊PCB版上的flash
        * 用编程器读取固件二进制
      * 架构
        * ARM
      * 系统
        * Linux
          * Linux kernel
          * Linux文件系统加密
          * uboot/grub
        * Vxworks
      * 固件
        * （固件）启动/加载地址
          * 魔数定位
          * 指令定位
        * 内存布局
        * 中断表地址
      * 分析工具
        * 反汇编
          * IDA PRO
            * switch 跳转表
          * Capstone
        * binwalk
        * rbasefind
  * 工业网络数据分析
  * 工控安全分析
  * 工业信息安全检测评估

## 工控威胁和情报

### 相关机构及关系

* 基础威胁情报(数据情报)
  * 流量/文件
  * BGP/AS/路由/Whois/指纹
  * Passive DNS/信誉数据
* 战术威胁情报(数据关联&分析)
  * 机读文件(IoC/TTP)
  * 情报落地、协作联动
* 战略威胁情报(价值&决策)
  * 可读报告
  * 意图分析、感知预测、决策支撑

![thread_company_relation](../assets/img/thread_company_relation.png)

### 工控系统威胁情报

![industrial_control_thread_intelligence](../assets/img/industrial_control_thread_intelligence.png)
