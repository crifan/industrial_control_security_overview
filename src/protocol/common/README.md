# 常见协议

## 常见协议总结

| 工控协议 | 传输协议 | 端口 | 说明 | zoomeye查询链接 |
| ------ | ---------- | ---- | ---- | ------------- |
| Modbus | TCP | 502 | 工控常用协议，Modbus协议是应用于电子控制器上的一种协议。通过此协议设备间可以通信。它已成为一通用工业标准。<br/>详见：[Modbus](https://book.crifan.com/books/industrial_control_security_overview/website/protocol/common/modbus.html) | [port:502](https://www.zoomeye.org/searchResult?q=port:502) |
| Siemens S7 | TCP | 102 | 西门子PLC支持的通讯协议。属于第7层的协议，用于西门子设备之间进行交换数据，通过TSAP，可加载MPI,DP,以太网等不同物理结构总线或网络上，PLC一般可以通过封装好的通讯功能块实现。<br/>s7协议是SIEMENS s7协议族的标准通信协议，使用s7-应用接口的通信不依赖特定的总线系统。<br/>详见：[Siemens S7](https://book.crifan.com/books/industrial_control_security_overview/website/protocol/common/siemens_s7.html)  | [port:102](https://www.zoomeye.org/searchResult?q=port:102) |
| BACnet | TCP/UDP ? | 47808 | 楼宇自动控制网络数据通讯协议。楼宇自动控制网络数据通讯协议（A Data Communication Protocol for Building Automation and Control Networks）。BACnet 协议是为计算机控制采暖、制冷、空调HVAC系统和其他建筑物设备系统定义服务和协议。<br/>楼宇自动控制网络数据通讯协议(BACnet)是针对采暖、通风、空调、制冷控制设备所设计，同时也为其他楼宇控制系统（例如照明、安保、消防等系统）的集成提供一个基本原则。 | [port:47808](https://www.zoomeye.org/searchResult?q=port:47808) |
| ATG | TCP | 10001 | ATG，油罐液位仪，一种储油罐的监测设备；ATG（Automated-Tank-Gauge）协议是液位仪器的私有通讯协议 | [port:10001](https://www.zoomeye.org/searchResult?q=port:10001) |
| `IEC 104`| TCP | 2404 | 输配电通讯协议。`IEC 104`=`IEC 60870-5-104`是国际电工委员会制定的一个规范，用于适应和引导电力系统调度自动化的发展，规范调度自动化及远动设备的技术性能。 | [port:2404](https://www.zoomeye.org/searchResult?q=port:2404) |
| `DNP3`=`DNP 3.0` | TCP/UDP | 20000 | `DNP`=`Distributed Network Protocol`=`分布式网络协议` 是一种应用于自动化组件之间的通讯协议，常见于电力、水处理等行业。分布式网络协议，主要用于电力行业。SCADA可以使用DNP协议与主站、RTU、及IED进行通讯。 <br/>简化OSI模型，只包含了物理层，数据层与应用层的体系结构（EPA）| [port:20000](https://www.zoomeye.org/searchResult?q=port:20000) |
| ICCP |  |  | 电力控制中心通讯协议 | |
| OPC | | | 过程控制的OLE （OLE for Process Control）。OPC包括一整套接口、属性和方法的标准集，用于过程控制和制造业自动化系统 | |
| &nbsp;&nbsp;OPC DA | TCP | 135 | OPC（OLE for Process Control, 用于过程控制的OLE）是一个工业标准。OPC包括一整套接口、属性和方法的标准集，用于过程控制和制造业自动化系统。OPC DA基于微软的OLE、COM和DCOM技术 | |
| &nbsp;&nbsp;OPC UA | TCP | 4840 | opc-ua<br/>tcp4840 port:4840<br/>OPC-UA（Unified Architecture）是下一代的OPC 标准，通过提供一个完整的、安全和可靠的跨平台的架构，以获取实时和历史数据和时间。OPC UA不再依靠DCOM，而是基于面向服务的架构 （SOA） | |
| CIP |  |  | 通用工业协议，被`DeviceNet`、`ControlNet`、`EtherNet/IP`三种网络所采用 | |
| Tridium Niagara Fox | TCP | 1911 | Fox协议是Tridium公司开发的Niagara框架的一部分，广泛应用于楼宇自动化控制系统 | [port:1911](https://www.zoomeye.org/searchResult?q=port:1911) |
| Crimson V3 | TCP | 789 | | [port:789](https://www.zoomeye.org/searchResult?q=port:789) |
| PCWorx | TCP | 1962 | PCWorx协议由菲尼克斯电气公司开发，目前广泛使用于工控系统。PCWORX3.11是菲尼克斯电气公司的专用协议 | [port:1962](https://www.zoomeye.org/searchResult?q=port:1962) |
| ProConOs | TCP | 20547 | ProConOS是德国科维公司(KW-Software GmbH)开发的用于PLC的实时操作系统，它是一个高性能的PLC运行时引擎，目前广泛使用于基于嵌入式和PC的工控系统 | [port:20547](https://www.zoomeye.org/searchResult?q=port:20547) |
| MELSEC-Q  | TCP/UDP | tcp 5007 / UDP 5006 | MELSEC-Q系列设备使用专用的网络协议进行通讯，该系列设备可以提供高速、大容量的数据处理和机器控制 | [port:5007](https://www.zoomeye.org/searchResult?q=port:5007)，[port:5006](https://www.zoomeye.org/searchResult?q=port:5006) |
| `IEC-61850` = MMS + goose + SV | TCP | 102 | 输配电通讯协议。IEC 61850标准是电力系统自动化领域唯一的全球通用标准。它通过标准的实现，实现了智能变电站的工程运作标准化。使得智能变电站的工程实施变得规范、统一和透明 | |
| GE SRTP | TCP | 18245 | GE-SRTP协议由美国通用电气公司开发，GE PLC可以通过GE-SRTP进行数据通信和数据传输 | |
| CANopen |  |  | 控制局域网通讯协定 | |
| `ONVIF` | UDP | 3702 | ONVIF协议的开发目的是通过全球性的开放接口标准来推进网络视频在安防市场的应用，这一接口标准将确保不同厂商生产的网络视频产品具有互通性 | |
|  |  |  |  | |
| **工业现场总线** |  |  |  | |
| PROFIBUS |  |  | 一种用于工厂自动化车间级监控和现场设备层数据通信与控制的现场总线技术，可实现现场设备层到车间级监控的分散式数字控制和现场通信网络 | |
| `EtherNet/IP` | TCP/UDP | 44818 | Ethernet/IP是一个面向工业自动化应用的工业应用层协议。它建立在标准UDP/IP与TCP/IP协议之上，利用固定的以太网硬件和软件，为配置、访问和控制工业自动化设备定义了一个应用层协议。<br/>是一种CIP的实现方式，由罗克韦尔自动化公司开发的工业以太网通讯协定。 | [port:44818](https://www.zoomeye.org/searchResult?q=port:44818) |
| Profinet |  |  | 开放式的工业以太网通讯协定 | |
| EtherCAT |  |  | 德国Beckhoff公司推动的开放式实时以太网通讯协定 | |
| HART-IP | TCP/UDP | 5094 | HART协议是美国Rosement公司于1985年推出的一种用于现场智能仪表和控制室设备之间的通信协议。现已成为全球智能仪表的工业标准 | |
|  |  |  |  | |
| **PLC通信协议** |  |  |  | |
| MELSEC | TCP/UDP | TCP 5007<br/>UDP 5006 | 三菱Q PLC支持的通讯协议 | |
| OMRON FINS | TCP/UDP | 9600 | 欧姆龙PLC支持的通讯协定。欧姆龙PLC使用网络协议FINS进行通信，可通过多种不同的物理网络，如以太网、控制器连接等。 | [port:9600](https://www.zoomeye.org/searchResult?q=port:9600) |
| EGD |  |  | GE Fanuc为PLC开发的通讯协定 | |
| Sinec H1 |  |  | 西门子PLC支持的通讯协议 | |
| **无线协议** |  |  |  | |
| mqtt |  |  |  | |
| zigbee | | | 开放式的无线通讯协定 | |
|  |  |  |  | |
| **主流网络协议** |  |  |  | |
| RTPS | TCP | 554 | RTSP协议是一种实时流传输协议，该协议定义了一对多应用程序如何有效地通过IP网络传送多媒体数据 | |
| SIP | TCP | 5060 | SIP协议是由IETF制定的多媒体通信协议，SIP的开发目的是用来帮助提供跨越因特网的高级电话业务 | |
|  |  |  |  | |
| **其他协议** |  |  |  | |
| IEC 103 |  |  |  | |
| Power Link |  |  | 开放式实时以太网通信 | |
| FF HSE |  |  | 基金会现场总线以太网通信协定 | |
| CoAP |  |  | 轻量应用层协议 | |
| openSAFETY |  |  | 开源安全应用协议 | |
| SERCOS III |  |  | 实时以太网通讯协定 | |
| TTEthernet |  |  | 实时以太网通讯协定 | |
| CDT |  |  | 远动规约 | |
| KNXnet/IP |  |  | 住宅和楼宇控制标准 | |
| Lontalk |  |  | 埃施朗公司的LonWorks技术所使用的通讯协议 | |
| SAE J1939 |  |  | 一种CAN的变种，适用在农业车辆及商用车辆 | |
| USITT DMX512-A  |  |  | 灯光控制数据传输协议 | |
| BSSAP/BSAP |  |  | 由Bristol Babcock Inc发展的通讯协定 | |
| Gryphon |  |  | 车用通讯协定 | |
| Doip |  |  | 汽车诊断协议 | |
| AUTOSAR |  |  | 汽车开放系统协议 | |
| redlion-crimson3 | TCP | 789 | 协议被Crimson桌面软件用于与Red Lion G306工控系统的HMI人机接口 | |
| Fox | TCP | 1911 | Fox协议是Tridium公司开发的Niagara框架的一部分，广泛应用于楼宇自动化控制系统 | |
| secure-fox | TCP | 4911 | Fox协议是Tridium公司开发的Niagara框架的一部分，广泛应用于楼宇自动化控制系统 | |
| moxa-nport | UDP | 4800 | Moxa串口服务器专为工业应用而设计。不通配置组合的串口服务器更能符合不同工业现场的需求。NPort系列串口服务器让传统 RS-232/422/485设备立即联网，提供您基于IP的串口联网解决方案 | |
| codesys | TCP | 2455 | CoDeSys编程接口在全球范围内使用广泛，全球上百个设备制造商的自动化设备中都是用了该编程接口 | |
| ddp | TCP/UDP | 5002 | DDP协议（DTU DSC Protocol）是DTU与DSC之间的通讯协议，DDP是一种厂商定义的私有公开性质的通信协议，用于数据的传输和DTU管理 | |
| lantronix-udp | TCP | 30718 | Lantronix串口服务器专为工业应用而设计。串口服务器是一种具有串口转以太网功能的设备，它能将RS-232/485/422串口转换成TCP/IP网络接口，串口服务器广泛的应用在SCADA数据采集环节上，用于解决串口和以太网的通信问题 | |
| wdbrpc | TCP | 17185 | VxWorks是世界上使用最广泛的一种在嵌入式系统中部署的实时操作系统，是由美国WindRiver公司于1983年设计开发的。VxWorks系统在工业控制领域应用较广泛。WDB RPC是VxWorks的远程调试协议 | |
| dahua-dvr | TCP | 37777 | DAHUA-DVR协议是浙江大华安防监控设备的私有通信协议，该协议用于实时视频流量的传输 | |
| vstarcam-udp | UDP | 8600 | VSTARCAM-UDP协议是威视达康安防监控设备的私有通信协议该协议用于获取安防监控设备的网络配置等信息 | |
| CSPV4 | TCP | 2222 | CSPV4是可以识别PLC5/SLC 500控制器的服务；罗克韦尔的SLC 500功能强大，拥有先进的指令集、丰富的输入输出模块，专门针对工业现场恶劣的工作环境而设计 | |
| general-electric-srtp | TCP | 18245 | GE-SRTP协议由美国通用电气公司开发，GE PLC可以通过GE-SRTP进行数据通信和数据传输 | |
|  |  |  |  | |
| **私有协议** |  |  |  | |
| bachmann-tcp | TCP | 3500 | Bachmann是一种私有协议，用于Bachmann PLC的通讯，常见于风力发电等行业 | |
| bachmann-udp | UDP | 3003 | Bachmann是一种私有协议，用于Bachmann PLC的通讯，常见于风力发电等行业 | |
| beckoff-ads | UDP | 48899 | Beckoff-ads是一种私有协议，用于Beckoff PLC的通讯，常见于风力发电等行业 | |
| hollysys-lk | UDP | 6000 | Hollysys-lk协议是一种私有协议，用于Hollysys PLC的通讯，常见于电力、石油、化工等行业 | |
| hollysys-macs | UDP | 8000 | Hollysys-macs协议是一种私有协议，用于Hollysys DCS的通讯，常见于电力、石油、化工等行业 | |
| siemens-license | TCP  | 4410  | Siemens License协议是一种私有协议，用于西门子上位机软件的License服务 | |
| igss | TCP | 12397 | IGSS协议是一种私有协议，用于IGSS（Interactive Graphical SCADA System）软件之间的通讯 | |
| foxboro | TCP | 20476 | Foxboro是一种私有协议，用于Foxboro PLC的通讯，常见于电力、石油、化工等行业 | |
| ilon-smartserver | TCP | 1628 | ILON-SMARTSERVER协议是ECHELON公司生产的iLon系列产品的私有通信协议，iLon系列产品可以广泛的应用于工业控制领域；iLon SmartServer类似于一台服务器，起着指令分发，数据存储等作用 | |
|  |  |  |  | |

