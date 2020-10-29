# NFC

* NFC=近场通信
  * 工作模式：被动式
  * 工作频率：13.56MHz
  * 应用举例
    * 文字
      * 地铁一卡通
      * 门禁卡
      * 护照
      * Tesla Model 3的钥匙系统：Pektorn PKE
    * 图
      * ![nfc_iclass_mifare](../assets/img/nfc_iclass_mifare.png)
  * NFC 攻击
    * Mifare Classic 的破解
      * 其他类型
        * iClass：某公司的门禁卡
        * Ultralight：某地铁的一次性车票
    * 破解工具=逆向工具
      * PM3=PROXMARK3
        * 号称：研究RFID的瑞士军刀
        * 用途：读取Tesla车卡或物理钥匙
      * NFCGate
        * https://github.com/nfcgate
      * Proxmark3