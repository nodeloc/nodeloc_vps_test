# NodeLoc聚合测评脚本 [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Feverett7623%2Fnodeloc_vps_test%2Fblob%2Fmain%2FNlbench.sh&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

这是NodeLoc提供给各位用户的主机聚合测评脚本，可一键自动对主机进行Yabs、融合怪、IP质量、流媒体解锁，三网测速，回程路由等测评，测评结束后会生成一个txt文件，可在线自行复制内容 发到NodeLoc论坛。

**版本：** 2024-09-08 v1.2.4

**Github地址：** https://github.com/everett7623/nodeloc_vps_test

**VPS 选购:** [NodeLoc VPS](https://www.nodeloc.com/vps)

### 使用方法
确保用户为ROOT，主机网络通畅，复制下面任意命令运行

**支持CentOS/Debian/Ubuntu/Deepin**

CentOS
```bash
yum install wget&&wget -O Nlbench.sh https://raw.githubusercontent.com/everett7623/nodeloc_vps_test/main/Nlbench.sh && chmod +x Nlbench.sh && ./Nlbench.sh
```
Debian/Ubuntu/Deepin
```bash
wget -O Nlbench.sh https://raw.githubusercontent.com/everett7623/nodeloc_vps_test/main/Nlbench.sh && chmod +x Nlbench.sh && ./Nlbench.sh
```

### 效果图
#### 运行截图
![image](https://s.rmimg.com/2024/09/21/56db40f55c1d901066fe15973b70af06.png)

![image](https://s.rmimg.com/2024/09/21/b6a48d97e8124f452ef069901fe727d6.png)

![image](https://s.rmimg.com/2024/09/21/d697aac320074e6a0316aea2ae953efd.png)
#### 生成内容
以NiiHost商家提供的香港国际线路机器测试，此机器以免费虚拟主机的形式将上架Free NodeLoc
```
[tabs]
[tab="YABS"]
```
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
#              Yet-Another-Bench-Script              #
#                     v2024-06-09                    #
# https://github.com/masonr/yet-another-bench-script #
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
Sat Sep 21 08:13:15 PM CST 2024
Basic System Information:
---------------------------------
Uptime     : 14 days, 22 hours, 15 minutes
Processor  : Intel Core Processor (Broadwell, IBRS)
CPU cores  : 4 @ 2399.996 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ✔ Enabled
RAM        : 7.7 GiB
Swap       : 0.0 KiB
Disk       : 127.9 GiB
Distro     : Debian GNU/Linux 12 (bookworm)
Kernel     : 6.1.0-9-amd64
VM Type    : KVM
IPv4/IPv6  : ✔ Online / ✔ Online
IPv6 Network Information:
---------------------------------
ISP        : Skywolf Technology LLC
ASN        : AS7720 Skywolf Technology LLC
Location   : Hong Kong, Kowloon ()
Country    : Hong Kong

fio Disk Speed Tests (Mixed R/W 50/50) (Partition /dev/vda3):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 124.43 MB/s  (31.1k) | 148.72 MB/s   (2.3k)
Write      | 124.76 MB/s  (31.1k) | 149.50 MB/s   (2.3k)
Total      | 249.20 MB/s  (62.3k) | 298.22 MB/s   (4.6k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 205.87 MB/s    (402) | 221.90 MB/s    (216)
Write      | 216.81 MB/s    (423) | 236.68 MB/s    (231)
Total      | 422.68 MB/s    (825) | 458.59 MB/s    (447)
 *cue elevator music*
Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value                         
                |                               
Single Core     | 551                           
Multi Core      | 1947                          
Full Test       | https://browser.geekbench.com/v5/cpu/22889112
YABS completed in 4 min 26 sec
```
[/tab]
[tab="融合怪"]
```
--------------------- A Bench Script By spiritlhl ----------------------
                   测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.08.29
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Intel Core Processor (Broadwell, IBRS)
 CPU 核心数        : 4
 CPU 频率          : 2399.996 MHz
 CPU 缓存          : L1: 128.00 KB / L2: 16.00 MB / L3: 64.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 273.88 MiB / 7.72 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 3.05 GiB / 127.82 GiB
 启动盘路径        : /dev/vda3
 系统在线时间      : 14 days, 22 hour 20 min
 负载              : 1.26, 0.92, 0.41
 系统              : Debian GNU/Linux 12 (bookworm) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 6.1.0-9-amd64
 TCP加速方式       : bbr
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS7720 Skywolf Technology LLC
 IPV4 位置         : Hong Kong / Hong Kong / HK
 IPV6 ASN          : AS7720 Skywolf Technology
 IPV6 位置         : Hong Kong
 IPV6 子网掩码     : 128
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)

 1 线程测试(单核)得分: 		1/1 
 1 线程测试(单核)得分: 		740 Scores

 4 线程测试(多核)得分: 		1/1 
 4 线程测试(多核)得分: 		3027 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)

 单线程读测试:		1/1 
 单线程读测试:		14150.18 MB/s

 单线程写测试:		1/1 
 单线程写测试:		12365.23 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		->
 100MB-4K Block		15.3 MB/s (3735 IOPS, 6.85s)		->
 100MB-4K Block		15.3 MB/s (3735 IOPS, 6.85s)		18.5 MB/s (4521 IOPS, 5.66s)
 1GB-1M Block		->
 1GB-1M Block		320 MB/s (305 IOPS, 3.28s)		->
 1GB-1M Block		320 MB/s (305 IOPS, 3.28s)		385 MB/s (366 IOPS, 2.73s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------

Running fio test...
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 121.92 MB/s  (30.4k) | 151.66 MB/s   (2.3k)
Write      | 122.25 MB/s  (30.5k) | 152.46 MB/s   (2.3k)
Total      | 244.18 MB/s  (61.0k) | 304.13 MB/s   (4.7k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 203.21 MB/s    (396) | 211.96 MB/s    (206)
Write      | 214.00 MB/s    (417) | 226.08 MB/s    (220)
Total      | 417.21 MB/s    (813) | 438.04 MB/s    (426)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：美国
[IPV6]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：中国香港
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG07S42)
Youtube识别地域: 中国香港(HK)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG33S01)
Youtube识别地域: 中国香港(HK)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：HK 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：HK 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============

 Dazn:					Yes (Region: HK)

 Disney+:				No

 Netflix:				Yes (Region: US)

 YouTube Premium:			Yes (Region: HK)

 Amazon Prime Video:			Yes (Region: HK)

 TVBAnywhere+:				No

 Spotify Registration:			Yes (Region: HK)

 Instagram Licensed Audio:		Failed (Error: PAGE ERROR)

 OneTrust Region:			HK [Unknown]

 iQyi Oversea Region:			HK

 Bing Region:				US

 YouTube CDN:				Hong Kong

 Netflix Preferred CDN:			Hong Kong

 ChatGPT:				No (Only Available with Mobile APP)

 Google Gemini:				No

 Wikipedia Editability:			Yes

 Google Search CAPTCHA Free:		Yes

 Steam Currency:			HKD
 ---Forum---

 Reddit:				Yes
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
============[ Multination ]============

 Dazn:					IPv6 Is Not Currently Supported

 Disney+:				IPv6 Is Not Currently Supported

 Netflix:				Yes (Region: HK)

 YouTube Premium:			Yes (Region: HK)

 Amazon Prime Video:			IPv6 Is Not Currently Supported

 TVBAnywhere+:				IPv6 Is Not Currently Supported

 Spotify Registration:			Yes (Region: HK)

 Instagram Licensed Audio:		Failed (Error: PAGE ERROR)

 OneTrust Region:			HK [Unknown]

 iQyi Oversea Region:			IPv6 Is Not Currently Supported

 Bing Region:				HK

 YouTube CDN:				Hong Kong

 Netflix Preferred CDN:			Hong Kong

 ChatGPT:				Failed (Network Connection)

 Google Gemini:				No

 Wikipedia Editability:			Yes

 Google Search CAPTCHA Free:		Yes

 Steam Currency:			IPv6 Is Not Currently Supported
 ---Forum---

 Reddit:				IPv6 Is Not Currently Supported
=======================================
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------

 Tiktok Region:		Failed
-------------IP质量检测--基于oneclickvirt/securityCheck使用-------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  [0] | scamalytics数据库 [1] | virustotal数据库   [2] | abuseipdb数据库   [3] | ip2location数据库    [4]
ip-api数据库  [5] | ipwhois数据库     [6] | ipregistry数据库   [7] | ipdata数据库      [8] | db-ip数据库          [9]
ipapiis数据库 [A] | ipapicom数据库    [B] | bigdatacloud数据库 [C] | cheervision数据库 [D] | ipqualityscore数据库 [E]
IPV4:
安全得分:
声誉(越高越好): 0 [2] 
信任得分(越高越好): 42 [8] 
VPN得分(越低越好): 31 [8] 
代理得分(越低越好): 44 [8] 
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 98 [8]
欺诈得分(越低越好): 0 [1 E] 
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0012 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: DataCenter/WebHosting/Transit [3] corporate [9] hosting ASN [C] hosting [0 7] business [8 A]
公司类型: hosting [0 7] business [A]
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 1 C] No [5 6 8 A]
是否移动设备: Yes [E] No [5 A C]
是否代理: No [0 1 4 5 6 7 8 9 A B C D E] 
是否VPN: No [0 1 6 7 A C D E] 
是否Tor: No [0 1 3 6 7 8 A B C D E] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B E] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D E]
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
是否机器人: No [E] 
DNS-黑名单: 313(Total_Check) 0(Clean) 8(Blacklisted) 24(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0012 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [B]
安全信息:
使用类型: DataCenter/WebHosting/Transit [3] business [A]
公司类型: business [A] 
是否云提供商: Yes [D] 
是否数据中心: Yes [1 A] 
是否移动设备: No [A] 
是否代理: No [1 A B D] 
是否VPN: No [1 A D] 
是否Tor: No [1 3 A B D] 
是否Tor出口: No [1 D] 
是否网络爬虫: No [A B] 
是否匿名: No [1 D] 
是否攻击者: No [D] 
是否滥用者: No [A D] 
是否威胁: No [D] 
是否中继: No [D] 
是否Bogon: No [A D] 
DNS-黑名单: 313(Total_Check) 0(Clean) 0(Blacklisted) 313(Other) 
Google搜索可行性：YES
-------------邮件端口检测--基于oneclickvirt/portchecker开源-------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✔     ✔     ✔     ✔     ✔     ✔    
QQ        ✔     ✔     ✔     ✘     ✔     ✘    
163       ✔     ✔     ✔     ✘     ✔     ✘    
Sohu      ✔     ✔     ✔     ✘     ✔     ✘    
Yandex    ✔     ✔     ✔     ✘     ✔     ✘    
Gmail     ✔     ✔     ✘     ✘     ✘     ✘    
Outlook   ✔     ✘     ✔     ✘     ✔     ✘    
Office365 ✔     ✘     ✔     ✘     ✔     ✘    
Yahoo     ✔     ✔     ✘     ✘     ✘     ✘    
MailCOM   ✔     ✔     ✔     ✘     ✔     ✘    
MailRU    ✔     ✔     ✘     ✘     ✔     ✘    
AOL       ✔     ✔     ✘     ✘     ✘     ✘    
GMX       ✔     ✘     ✔     ✘     ✔     ✘    
Sina      ✔     ✘     ✔     ✘     ✔     ✘    
----------------三网回程--基于oneclickvirt/backtrace开源----------------
北京电信 219.141.140.10  检测不到回程路由节点的IP地址
北京联通 202.106.195.68  联通4837   [普通线路] 
北京移动 221.179.155.161 移动CMI    [普通线路] 
上海电信 202.96.209.133  电信163    [普通线路] 
上海联通 210.22.97.1     联通4837   [普通线路] 
上海移动 211.136.112.200 检测不到回程路由节点的IP地址
广州电信 58.60.188.222   电信163    [普通线路] 
广州联通 210.21.196.6    联通4837   [普通线路] 
广州移动 120.196.165.24  移动CMI    [普通线路] 
成都电信 61.139.2.69     电信163    [普通线路] 
成都联通 119.6.6.6       联通4837   [普通线路] 
成都移动 211.137.96.205  移动CMI    [普通线路] 
准确线路自行查看详细路由，本测试结果仅作参考
同一目标地址多个线路时，可能检测已越过汇聚层，除了第一个线路外，后续信息可能无效
---------------------回程路由--感谢fscarmen开源及PR---------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自ipip.net或nexttrace，请知悉!
广州电信 58.60.188.222
0.52 ms 	AS7720 中国 香港 skywolf.cloud
0.48 ms 	* RFC1918
0.62 ms 	* RFC1918
1.57 ms 	AS1299 [ARELION-NET] 中国 香港 arelion.com
1.84 ms 	AS1299 [ARELION-NET] 中国 香港 arelion.com
1.50 ms 	AS1299 [ARELION-NET] 中国 香港 arelion.com
50.14 ms 	AS1299 [ARELION-NET] 日本 东京都 东京 arelion.com
149.12 ms 	AS1299 [ARELION-NET] 美国 加利福尼亚 圣何塞 arelion.com
158.49 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
* ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
162.65 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.50 ms 	AS7720 中国 香港 skywolf.cloud
0.76 ms 	* RFC1918
3.98 ms 	AS3356 中国 香港 lumen.com
156.11 ms 	AS3356 美国 加利福尼亚 洛杉矶 lumen.com
* ms 	AS3356 美国 加利福尼亚 洛杉矶 lumen.com
* ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
337.53 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
396.30 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
343.93 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
337.83 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.55 ms 	AS7720 中国 香港 skywolf.cloud
0.60 ms 	* RFC1918
0.75 ms 	* RFC1918
8.82 ms 	AS3356 中国 香港 lumen.com
2.89 ms 	AS58453 [CMI-INT] 中国 香港 cmi.chinamobile.com 移动
8.68 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
54.17 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
9.91 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
59.81 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
10.25 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
13.82 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
11.07 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 503.52 Mbps	 930.48 Mbps	 0.64	  0.0%
日本东京	 1027.70 Mbps	 889.43 Mbps	 43.11	  0.0%
联通成都	 46.69 Mbps	 4.86 Mbps	 154.10	  NULL
电信Suzhou5G	 635.65 Mbps	 813.20 Mbps	 167.89	  NULL
电信浙江	 525.11 Mbps	 754.60 Mbps	 177.97	  NULL
该运营商.net的节点列表为空，正在替换为.cn的节点列表。。。
------------------------------------------------------------------------
 总共花费      : 6 分 43 秒
 时间          : Sat Sep 21 20:24:39 CST 2024

------------------------------------------------------------------------
  短链:
    http://hpaste.spiritlhl.net/u/lOYRj7.txt
```
[/tab]
[tab="IP质量"]
```
########################################################################

                      IP质量体检报告：103.213.*.*

                    bash <(curl -sL IP.Check.Place)

                   https://github.com/xykt/IPQuality

        报告时间：2024-09-21 20:24:42 CST  脚本版本：v2024-07-29
########################################################################

一、基础信息（Maxmind 数据库）

自治系统号：            AS7720

组织：                  Skywolf Technology LLC

坐标：                  114°9′57″E, 22°15′28″N

地图：                  https://check.place/22.2578,114.1657,15,cn

城市：                  N/A

使用地：                [HK]香港, [AS]亚洲

注册地：                [US]美国

时区：                  Asia/Hong_Kong

IP类型：                 广播IP 

二、IP类型属性

数据库：      IPinfo    ipregistry    ipapi     AbuseIPDB  IP2LOCATION 

使用类型：     机房        机房        商业        机房        机房    

公司类型：     机房        机房        商业    

三、风险评分

风险等级：      极低         低       中等       高         极高

SCAMALYTICS：  0|低风险

ipapi：    0.00%|极低风险

AbuseIPDB：    0|低风险

IPQS：                38|低风险

DB-IP：         |低风险

四、风险因子

库： IP2LOCATION ipapi ipregistry IPQS SCAMALYTICS ipdata IPinfo IPWHOIS

地区：    [HK]    [HK]    [US]    [HK]    [US]    [HK]    [HK]    [HK]

代理：     否      否      否      否      否      否      否      否 

Tor：      否      否      否      否      否      否      否      否 

VPN：      否      否      否      否      否      无      否      否 

服务器：   是      否      是      无      否      否      是      否 

滥用：     否      否      否      否      无      否      无      无 

机器人：   否      否      无      否      否      无      无      无 

五、流媒体及AI服务解锁检测

服务商：  TikTok   Disney+  Netflix Youtube  AmazonPV  Spotify  ChatGPT 

状态：     失败     解锁     解锁     解锁     解锁     解锁     仅APP  

地区：              [US]     [US]     [HK]     [HK]     [HK]     [HK]   

方式：              原生     原生     原生     原生     原生     原生   

六、邮局连通性及黑名单检测

本地25端口：阻断

IP地址黑名单数据库：  有效 439   正常 428   已标记 8   黑名单 3

========================================================================

今日IP检测量：460；总检测量：111564。感谢使用xy系列脚本！ 

报告链接：https://Report.Check.Place/IP/SD4ATJ2Q8.svg

########################################################################

                IP质量体检报告：2401:5a0:1000:*:*:*:*:*

                    bash <(curl -sL IP.Check.Place)

                   https://github.com/xykt/IPQuality

        报告时间：2024-09-21 20:24:42 CST  脚本版本：v2024-07-29
########################################################################

一、基础信息（Maxmind 数据库）

自治系统号：            AS7720

组织：                  Skywolf Technology LLC

坐标：                  114°9′57″E, 22°15′28″N

地图：                  https://check.place/22.2578,114.1657,15,cn

城市：                  N/A

使用地：                [HK]香港, [AS]亚洲

注册地：                [US]美国

时区：                  Asia/Hong_Kong

IP类型：                 广播IP 

二、IP类型属性

数据库：      IPinfo    ipregistry    ipapi     AbuseIPDB  IP2LOCATION 

使用类型：     机房        机房        商业        机房        机房    

公司类型：     机房        机房        商业    

三、风险评分

风险等级：      极低         低       中等       高         极高

SCAMALYTICS：  0|低风险

ipapi：    0.00%|极低风险

AbuseIPDB：    0|低风险

IPQS：                38|低风险

DB-IP：         |低风险

四、风险因子

库： IP2LOCATION ipapi ipregistry IPQS SCAMALYTICS ipdata IPinfo IPWHOIS

地区：    [HK]    [HK]    [HK]    [HK]    [HK]    [HK]    [HK]    [HK]

代理：     否      否      否      否      否      否      否      否 

Tor：      否      否      否      否      否      否      否      否 

VPN：      否      否      否      否      否      无      否      否 

服务器：   是      是      是      无      否      否      是      否 

滥用：     否      否      否      否      无      否      无      无 

机器人：   否      否      无      否      否      无      无      无 

五、流媒体及AI服务解锁检测

服务商：  TikTok   Disney+  Netflix Youtube  AmazonPV  Spotify  ChatGPT 

状态：     失败     解锁     解锁     解锁     屏蔽     解锁     失败   

地区：              [HK]     [HK]     [HK]              [HK]            

方式：              原生     原生     原生              原生            

六、邮局连通性及黑名单检测

本地25端口：阻断

========================================================================

今日IP检测量：461；总检测量：111565。感谢使用xy系列脚本！ 

报告链接：https://Report.Check.Place/IP/20NO52WN0.svg

```
[/tab]
[tab="流媒体"]
```
项目地址 https://github.com/lmc999/RegionRestrictionCheck 
改版地址 https://github.com/xykt/RegionRestrictionCheck 
脚本适配OS: CentOS 6+, Ubuntu 14.04+, Debian 8+, MacOS, Android (Termux), iOS (iSH)
 ** 测试时间: Sat Sep 21 08:26:04 PM CST 2024
 ** 正在测试IPv4解锁情况 
--------------------------------
 ** 您的网络为: Skywolf Technology (103.213.*.*) 
============[ Multination ]============

 Dazn:			原生解锁	Yes (Region: HK)

 TikTok:				Failed

 Disney+:		原生解锁	Yes (Region: US)

 Netflix:		原生解锁	Yes (Region: US)

 YouTube Premium:	原生解锁	Yes (Region: HK)

 Amazon Prime Video:	原生解锁	Yes (Region: HK)

 TVBAnywhere+:				No

 iQyi Oversea Region:	原生解锁	HK

 YouTube CDN:				Hong Kong 

 Netflix Preferred CDN:			Hong Kong  

 Spotify Registration:	原生解锁	Yes (Region: HK)

 Steam Currency:			HKD

 ChatGPT:		原生解锁	APP Only (Region: HK)

 Google Gemini:				No

 Bing Region:				US

 Wikipedia Editability:			Yes
 Instagram Licensed Audio:		->
 Instagram Licensed Audio:		Failed
 ---Forum---

 Reddit:				Yes
=======================================
=============[ Hong Kong ]=============

 Now E:					Yes

 Viu.com:		原生解锁	Yes (Region: HK)

 Viu.TV:				Yes

 MyTVSuper:				No

 HBO GO Asia:				Yes (Region: HK)

 SonyLiv:				Failed (Network Connection)

 BiliBili Hongkong/Macau/Taiwan:	Yes

 Bahamut Anime:				No
=======================================
 ** 正在测试IPv6解锁情况 
--------------------------------
 ** 您的网络为: Skywolf Technology (2401:5a0:1000:*:*) 
============[ Multination ]============

 Dazn:					Failed (Network Connection)

 TikTok:				Failed

 Disney+:		原生解锁	Yes (Region: HK)

 Netflix:		原生解锁	Yes (Region: HK)

 YouTube Premium:	原生解锁	Yes (Region: HK)

 Amazon Prime Video:			Unsupported

 TVBAnywhere+:				Failed (Network Connection)

 iQyi Oversea Region:			Failed

 YouTube CDN:				Hong Kong 

 Netflix Preferred CDN:			Hong Kong  

 Spotify Registration:	原生解锁	Yes (Region: HK)

 Steam Currency:			Failed (Network Connection)

 ChatGPT:				Failed

 Google Gemini:				No

 Bing Region:				

 Wikipedia Editability:			Yes
 Instagram Licensed Audio:		->
 Instagram Licensed Audio:		Failed
 ---Forum---

 Reddit:				Failed (Network Connection)
=======================================
=============[ Hong Kong ]=============

 Now E:					Failed (Network Connection)

 Viu.com:				Failed

 Viu.TV:				Failed (Network Connection)

 MyTVSuper:				No

 HBO GO Asia:				Failed (Network Connection)

 SonyLiv:				Failed (Network Connection)

 BiliBili Hongkong/Macau/Taiwan:	Failed (Network Connection)

 Bahamut Anime:				Failed (Network Connection 1)
=======================================
本次测试已结束，感谢使用此脚本 
检测脚本当天运行次数: 15; 共计运行次数: 130345 
```
[/tab]
[tab="响应"]
```
正在测试 https://www.google.com
尝试 1: 141.816000 ms
尝试 2: 139.710000 ms
尝试 3: 145.609000 ms
尝试 4: 127.850000 ms
尝试 5: 133.706000 ms
平均时间: 137.73 ms for https://www.google.com
----------------------------------
正在测试 https://www.facebook.com
尝试 1: 279.553000 ms
尝试 2: 276.562000 ms
尝试 3: 270.553000 ms
尝试 4: 254.919000 ms
尝试 5: 259.105000 ms
平均时间: 268.13 ms for https://www.facebook.com
----------------------------------
正在测试 https://www.twitter.com
尝试 1: 336.111000 ms
尝试 2: 335.082000 ms
尝试 3: 341.563000 ms
尝试 4: 348.053000 ms
尝试 5: 337.916000 ms
平均时间: 339.74 ms for https://www.twitter.com
----------------------------------
正在测试 https://www.youtube.com
尝试 1: 185.676000 ms
尝试 2: 218.367000 ms
尝试 3: 229.474000 ms
尝试 4: 242.499000 ms
尝试 5: 201.249000 ms
平均时间: 215.45 ms for https://www.youtube.com
----------------------------------
正在测试 https://www.netflix.com
尝试 1: 747.800000 ms
尝试 2: 891.505000 ms
尝试 3: 740.914000 ms
尝试 4: 577.570000 ms
尝试 5: 576.444000 ms
平均时间: 706.84 ms for https://www.netflix.com
----------------------------------
正在测试 https://chat.openai.com
尝试 1: 102.288000 ms
尝试 2: 91.900000 ms
尝试 3: 87.534000 ms
尝试 4: 90.253000 ms
尝试 5: 76.423000 ms
平均时间: 89.67 ms for https://chat.openai.com
----------------------------------
正在测试 https://www.github.com
尝试 1: 151.443000 ms
尝试 2: 148.913000 ms
尝试 3: 156.583000 ms
尝试 4: 149.070000 ms
尝试 5: 132.996000 ms
平均时间: 147.80 ms for https://www.github.com
----------------------------------
网站                          平均时间(ms)
--------------------------------------------------
https://www.google.com               137.73 ms
https://www.facebook.com             268.13 ms
https://www.twitter.com              339.74 ms
https://www.youtube.com              215.45 ms
https://www.netflix.com              706.84 ms
https://chat.openai.com               89.67 ms
https://www.github.com               147.80 ms
--------------------------------------------------
Total Avg                            272.19 ms
```
[/tab]
[tab="多线程测速"]
```
 Version               : v2024-04-25
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
大陆三网+教育网 IPv4 多线程测速，v2024-03-15
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
 
最近的测速点        926.58 Mbps    1006.95 Mbps   0.64 ms      0.07 ms      
 
电信 江苏苏州       771.95 Mbps    477.19 Mbps    167.57 ms    0.06 ms      
 
电信 浙江杭州       869.27 Mbps    220.41 Mbps    184.97 ms    132.76 ms    
 
电信 浙江宁波 5G    698.34 Mbps    0.67 Mbps      562.57 ms    941.00 ms    
 
电信 江苏镇江 5G    795.93 Mbps    246.76 Mbps    169.45 ms    1.20 ms      
 
电信 江苏南京 5G    647.26 Mbps    266.73 Mbps    172.83 ms    1.71 ms      
 
联通 江苏无锡       531.04 Mbps    69.99 Mbps     157.90 ms    113.78 ms    
 

测速次数过多，暂时被限制，请过一段时间后再进行测试
 

------------------------------------------------------------------------
系统时间：2024-09-21 21:56:29 CST
北京时间: 2024-09-21 21:56:29 CST
------------------------------------------------------------------------
```
[/tab]
[tab="单线程测速"]
```
```
[/tab]
[tab="回程路由"]
```
No:1/9 Traceroute to 中国 深圳 电信 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - 172.67.155.192 - 118.16ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 59.36.216.1, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.90 ms
2   10.0.0.6        *                         RFC1918          
                                              0.65 ms
3   10.98.4.1       *                         RFC1918          
                                              4.57 ms
4   62.115.44.124   AS1299   [ARELION-NET]    中国 香港   arelion.com 
                                              1.73 ms
5   *
6   *
7   *
8   *
9   *
10  *
11  218.30.54.181   AS4134   [CHINANET-US]    美国 加利福尼亚 圣何塞 Cogent/Telia-CT-PoP www.chinatelecom.com.cn  电信
                                              165.18 ms
12  *
13  202.97.66.226   AS4134   [CHINANET-BB]    中国 广东 广州  www.chinatelecom.com.cn  电信
                                              158.75 ms
14  119.147.61.138  AS4134   [CHINANET-GD]    中国 广东 深圳 福田 www.chinatelecom.com.cn  电信
                                              162.74 ms
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:2/9 Traceroute to 中国 上海 电信 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - [2606:4700:3037::ac43:9bc0] - 90.04ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 101.226.41.65, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.59 ms
2   10.0.0.6        *                         RFC1918          
                                              0.77 ms
3   10.98.4.1       *                         RFC1918          
                                              0.82 ms
4   62.115.44.124   AS1299   [ARELION-NET]    中国 香港   arelion.com 
                                              1.63 ms
5   *
6   *
7   *
8   62.115.116.198  AS1299   [ARELION-NET]    美国 加利福尼亚 洛杉矶  arelion.com 
                                              151.61 ms
9   218.30.54.181   AS4134   [CHINANET-US]    美国 加利福尼亚 圣何塞 Cogent/Telia-CT-PoP www.chinatelecom.com.cn  电信
                                              158.13 ms
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:3/9 Traceroute to 中国 北京 电信 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - 104.21.40.176 - 86.01ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 220.181.53.1, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.49 ms
2   10.0.0.6        *                         RFC1918          
                                              0.60 ms
3   10.98.4.1       *                         RFC1918          
                                              0.55 ms
4   62.115.44.124   AS1299   [ARELION-NET]    中国 香港   arelion.com 
                                              1.69 ms
5   *
6   *
7   *
8   62.115.123.140  AS1299   [ARELION-NET]    美国 加利福尼亚 圣何塞  arelion.com 
                                              150.66 ms
9   218.30.54.181   AS4134   [CHINANET-US]    美国 加利福尼亚 圣何塞 Cogent/Telia-CT-PoP www.chinatelecom.com.cn  电信
                                              158.90 ms
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:4/9 Traceroute to 中国 广州 联通 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - 104.21.40.176 - 76.73ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 210.21.4.130, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.57 ms
2   10.0.0.6        *                         RFC1918          
                                              0.51 ms
3   10.98.4.1       *                         RFC1918          
                                              0.91 ms
4   62.115.44.124   AS1299   [ARELION-NET]    中国 香港   arelion.com 
                                              1.85 ms
5   *
6   *
7   62.115.137.210  AS1299   [ARELION-NET]    日本 东京都 东京  arelion.com 
                                              49.07 ms
8   62.115.116.198  AS1299   [ARELION-NET]    美国 加利福尼亚 洛杉矶  arelion.com 
                                              150.47 ms
9   80.239.134.247  AS1299                    美国 加利福尼亚 洛杉矶  arelion.com 
                                              226.99 ms
10  *
11  219.158.9.214   AS4837   [CU169-BACKBONE] 中国 北京   chinaunicom.cn  联通
                                              233.30 ms
12  *
13  219.158.8.93    AS4837   [CU169-BACKBONE] 中国 北京   chinaunicom.cn 
                                              213.88 ms
14  120.86.0.182    AS17816  [APNIC-AP]       中国 广东 广州  chinaunicom.cn  联通
                                              245.00 ms
15  120.86.0.182    AS17816  [APNIC-AP]       中国 广东 广州  chinaunicom.cn  联通
                                              262.52 ms
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:5/9 Traceroute to 中国 上海 联通 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - [2606:4700:3037::ac43:9bc0] - 74.51ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 112.65.95.129, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.46 ms
2   10.0.0.6        *                         RFC1918          
                                              0.61 ms
3   10.10.53.0      *                         RFC1918          
                                              0.55 ms
4   203.131.254.209 AS2914   [NTT-GLOBAL]     中国 香港   gin.ntt.net 
                                              0.78 ms
5   *
6   *
7   129.250.4.232   AS2914   [NTT-BACKBONE]   日本 大阪府 大阪  gin.ntt.net 
                                              55.67 ms
8   129.250.66.138  AS2914   [NTT-BACKBONE]   日本 大阪府 大阪  gin.ntt.net 
                                              105.92 ms
9   219.158.6.157   AS4837   [CU169-BACKBONE] 中国 上海   chinaunicom.cn  联通
                                              103.49 ms
10  *
11  *
12  210.22.66.178   AS17621  [APNIC-AP]       中国 上海   chinaunicom.cn  联通
                                              105.26 ms
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:6/9 Traceroute to 中国 北京 联通 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - 172.67.155.192 - 95.56ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 61.49.140.217, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.67 ms
2   10.0.0.6        *                         RFC1918          
                                              0.66 ms
3   10.10.53.0      *                         RFC1918          
                                              0.91 ms
4   203.131.254.209 AS2914   [NTT-GLOBAL]     中国 香港   gin.ntt.net 
                                              3.05 ms
5   *
6   *
7   129.250.5.199   AS2914   [NTT-BACKBONE]   日本 东京都 东京  gin.ntt.net 
                                              52.04 ms
8   219.158.35.157  AS4837   [CU169-BACKBONE] 中国 北京 北京  chinaunicom.cn 
                                              122.36 ms
9   219.158.9.221   AS4837   [CU169-BACKBONE] 中国 北京   chinaunicom.cn 
                                              115.93 ms
10  *
11  219.158.9.221   AS4837   [CU169-BACKBONE] 中国 北京   chinaunicom.cn 
                                              113.86 ms
12  61.49.140.217   AS4808                    中国 北京   中国联通  联通
                                              109.82 ms
No:7/9 Traceroute to 中国 深圳 移动 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - 104.21.40.176 - 64.15ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 120.233.53.1, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.46 ms
2   10.0.0.6        *                         RFC1918          
                                              0.49 ms
3   10.10.50.0      *                         RFC1918          
                                              0.64 ms
4   *
5   4.69.208.58     AS3356                    中国 香港   lumen.com 
                                              2.56 ms
6   223.121.3.9     AS58453  [CMI-INT]        中国 香港   cmi.chinamobile.com  移动
                                              2.60 ms
7   223.120.22.69   AS58453  [CMI-INT]        中国 香港   cmi.chinamobile.com  移动
                                              2.97 ms
8   223.120.22.186  AS58453  [CMI-INT]        中国 广东 广州  cmi.chinamobile.com 
                                              49.99 ms
9   221.183.92.197  AS9808   [CMNET]          中国 广东 广州  chinamobileltd.com  移动
                                              54.32 ms
10  221.183.92.205  AS9808   [CMNET]          中国 广东 广州  chinamobileltd.com  移动
                                              53.50 ms
11  221.183.167.25  AS9808   [CMNET]          中国 广东 广州  chinamobileltd.com 
                                              63.41 ms
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:8/9 Traceroute to 中国 上海 移动 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - 172.67.155.192 - 92.72ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 183.194.216.129, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.66 ms
2   10.0.0.6        *                         RFC1918          
                                              0.65 ms
3   10.10.50.0      *                         RFC1918          
                                              0.64 ms
4   *
5   4.69.208.58     AS3356                    中国 香港   lumen.com 
                                              2.05 ms
6   223.121.3.9     AS58453  [CMI-INT]        中国 香港   cmi.chinamobile.com  移动
                                              3.05 ms
7   223.120.22.65   AS58453  [CMI-INT]        中国 香港   cmi.chinamobile.com  移动
                                              3.19 ms
8   *
9   221.183.89.182  AS9808   [CMNET]          中国 上海   chinamobileltd.com  移动
                                              30.30 ms
10  221.183.89.33   AS9808   [CMNET]          中国 上海   chinamobileltd.com  移动
                                              52.57 ms
11  221.183.89.50   AS9808   [CMNET]          中国 上海   chinamobileltd.com  移动
                                              32.44 ms
12  221.183.51.206  AS9808   [CMNET]          中国 上海   chinamobileltd.com 
                                              55.10 ms
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
No:9/9 Traceroute to 中国 北京 移动 (TCP Mode, Max 30 Hop, IPv4)
===================================================================
NextTrace v1.3.4 2024-09-10T13:25:26Z 6a3ea6a
[NextTrace API] preferred API IP - [2606:4700:3037::ac43:9bc0] - 96.63ms - Misaka.HKG
IP Geo Data Provider: LeoMoeAPI
traceroute to 211.136.25.153, 30 hops max, 52 bytes payload
1   103.213.4.1     AS7720                    中国 香港   skywolf.cloud 
                                              0.59 ms
2   10.0.0.6        *                         RFC1918          
                                              0.67 ms
3   10.10.50.0      *                         RFC1918          
                                              1.01 ms
4   *
5   4.69.218.150    AS3356                    中国 香港   lumen.com 
                                              1.46 ms
6   *
7   223.120.22.69   AS58453  [CMI-INT]        中国 香港   cmi.chinamobile.com  移动
                                              3.28 ms
8   223.120.22.138  AS58453  [CMI-INT]        中国 北京   cmi.chinamobile.com  移动
                                              65.11 ms
9   221.183.55.106  AS9808   [CMNET]          中国 北京  回国到达层 chinamobileltd.com  移动
                                              66.68 ms
10  221.183.25.201  AS9808   [CMNET]          中国 北京   chinamobileltd.com  移动
                                              65.60 ms
11  *
12  *
13  *
14  *
15  211.136.67.166  AS56048  [CMNET]          中国 北京   bj.10086.cn  移动
                                              69.99 ms
16  211.136.95.226  AS56048  [CMNET]          中国 北京   bj.10086.cn  移动
                                              70.25 ms
17  *
18  *
19  211.136.25.153  AS56048  [CMNET]          中国 北京   bj.10086.cn  移动
                                              68.92 ms
```
[/tab]
[tab="去程路由"]
[/tab]
[tab="Ping.pe"]
[/tab]
[tab="哪吒 ICMP"]
[/tab]
[tab="其他"]
[/tab]
[/tabs]
```

**测试结束后将生成一个txt文件，点击或者复制到浏览器后，可直接点击复制到[NodeLoc论坛](https://www.nodeloc.com/)，无需进行更多操作**
![image](https://github.com/user-attachments/assets/543a7741-943d-412c-9db7-58e5c66754c2)

## 免责声明
* NodeLoc聚合测评脚本属于自用分享工具，本脚本仅为各类脚本聚合。
* 工具中所有脚本均来自互联网，未对官方脚本文件进行任何更改，不对脚本安全性负责。如果你比较在意安全，请勿使用各类一键脚本。

## 问题反馈

如果您在使用过程中遇到问题，或者有功能建议，欢迎通过 [GitHub Issues](https://github.com/everett7623/nodeloc_vps_test/issues) 提交反馈。

## 许可协议

本项目采用 [AGPL-3.0 license](LICENSE) 许可。

### 鸣谢
1. [Yabs脚本](https://yabs.sh)——[masonr](https://github.com/masonr)
2. [融合怪脚本](https://gitlab.com/spiritysdx/za/-/raw/main/ecs.sh)——[spirit lhl](https://gitlab.com/spiritysdx)
3. [IP质量测试脚本](https://IP.Check.Place)——[xykt](https://github.com/xykt/)
4. [流媒体测试脚本](https://media.ispvps.com)——[xykt](https://github.com/xykt/)
5. [响应测试脚本](https://nodebench.mereith.com/scripts/curltime.sh)——[nodebench](https://nodebench.mereith.com)
6. [测速脚本](https://bash.icu/speedtest)——[i-abc](https://github.com/i-abc)
7. [回程测试脚本](https://raw.githubusercontent.com/Chennhaoo/Shell_Bash/master/AutoTrace.sh)——[陈豪](https://github.com/Chennhaoo/)

特别感谢以上作者提供的脚本
