> 以下内容多半都已过时（至2022.1已有一年半没有更新），会造成网站或软件可能已经挂掉或相关信息失真的情况。但白嫖翻墙大致上就这些手段，本文具有参考意义。



# 白嫖目录：

[0.5 解决方案](#0)

1. 网站实现  
[1.1 在线代理](#1)  
2. 扩展实现  
[2.1 browser extension](#2)  
3. 软件实现  
[3.1 proxy browser](#3)  
[3.2 VPN](#4)  
[3.3 SS/SSR/V2ray/Clash/Clashr/winXray](#5)  
&emsp;[3.3.1 软件下载](#6)  
&emsp;[3.3.2 免费节点分享](#7)  
&emsp;[3.3.3 机场导航](#8)  
&emsp;[3.3.4 其他相关网站](#9)  
4. 系统自有设置实现  
[4.1 在系统设置里设置VPN或代理](#10)  
5. 自建软/硬件实现  
[5.1 搭建服务器](#11)  
[5.2 搭建路由](#12)  
6. 附录  
[6.1 其他](#13)  
[6.2 翻墙信息](#14)  
[6.3 有试用期的VPN](#15)  
[6.4 两个软件](#16)  


### <h1 id="0">0.5 解决方案<h1>
> 2022.10.17

> 这部分是本人正在使用的方案，仅作为参考

#### 应用场景

PC端为主力，移动端偶尔使用；使用时间分散，非整天；流量要多；稳定性要求不高

#### 方案

- 手机上安装蓝灯和银河VPN，应急使用；
- 浏览器安装 Astar VPN 扩展，应急使用；
- PC上使用代理软件，机场选择试用流量多的，反复注册使用。若机场注册时需使用代理，则通过应急手段注册或先注册一个墙内可用的机场。
> 至于机场哪里找，YouTube 或者本页面都有参考答案

### <h1 id="1">1.1 在线代理<h1>

这种方式将代理的载体设为网站，不像大部分都是一个软件一样，比较小众
> 2022.10.17
 
### <h1 id="2">2.1 browser entension<h1>
extension    |备注  |安装
---|:---:|:----:
Astar VPN     |chrome extesion    |[1](https://chrome.google.com/webstore/detail/astar-vpn-free-and-fast-v/jajilbjjinjmgcibalaakngmkilboobh?utm_source=chrome-ntp-icon) 
> 如果没有大流量需求，只是查查资料，只使用这个就够了，因为据说这个扩展还可以。——2022.10.17


### <h1 id="3">3.1 proxy browser<h1>

Proxy Browser |Android|IOS|Windows|Mac|Linux|Note
--------------|:-----:|:-:|:-----:|:-:|:---:|:--:
灵狐浏览器    |√      |√  |√       |   |     |需手机号登录；[官网](https://ie.linkfoxvpn.com/#/)
Tuber浏览器   |√      |敬请期待|   |   |    |[官网](http://pc.txappnet.com/)
龙卷风浏览器  |       |   |√      |   |     |
绿光浏览器    |√      |√  |√      |√  |     |需手机号登录；[官网](https://www.sgreennet.com/)  
Opera         |√      |   |√      |√  |√    |Opera 40以上；[官网](https://www.opera.com/zh-tw)    

> 这种方式不太靠谱，一是因为很容易失效，二是因为内容有过滤。——2022.10.17

### <h1 id="4">3.2 VPN<h1>  

**我用过，能用的**

VPN           |Android|IOS|Windows|Mac|Linux|Browser Entensions|Others|Note
--------------|:-----:|:-:|:-----:|:-:|:---:|:----------------:|:----:|:--:
老王VPN       |√      |√  |√      |√  |     |                  |      |[官网1](https://www.laowang.cn.com/), [官网2]()
VPN Gate      |√      |√  |√      |√  |     |                  |      |[官网](https://www.vpngate.net/cn/)
蓝灯          |√      |√  |√      |√  |√    |                  |      |500M/月；[官网](https://getlantern.org/zh_CN/)；[中国官网](https://www.getlandeng129.org/)；[GitHub](https://github.com/getlantern/download)；安卓端可看看这个：[安卓端：多开分身与蓝灯](https://github.com/TiantianPython/fan_qiang/blob/master/%E5%AE%89%E5%8D%93%E7%AB%AF%EF%BC%9A%E5%A4%9A%E5%BC%80%E5%88%86%E8%BA%AB%E4%B8%8E%E8%93%9D%E7%81%AF.md)
小明VPN       |√      |√  |       |   |     |                  |      |不稳定；[官网](https://gitithub.com/xm19/blob/master/)
猴王VPN       |√      |   |       |   |     |                  |      |谷歌商店下载
ProtonVPN     |√      |√  |√      |√  |√    |                  |Router|[官网](https://protonvpn.com/)  


**还没来得及用的**

VPN           |Android|IOS|Windows|Mac|Linux|Browser Entensions|Others|Note
--------------|:-----:|:-:|:-----:|:-:|:---:|:----------------:|:----:|:--:
Windscribe    |√      |√  |√      |√  |√    |Chrome, Fireox, Opera|TV, Router|10G/月（无email注册2G/月）[官网](https://chn.windscribe.com/)
Hide.me       |√      |√  |√      |√  |√    |                  |      |2G/月；[官网](https://hide.me/en/)
Tunnelbear    |√      |√  |√      |√  |     |Chrome            |      |500M/月；安卓端需Google Play服务；[官网](https://www.tunnelbear.com/)
Psiphon       |√      |√  |√      |   |     |                  |      |[官网](https://psiphon.ca/zh/)
黑洞加速器    |√      |√  |       |   |     |                  |      |[官网](https://www.hd86048.com/)
SetupVPN      |√ |COMING SOON|√   |√  |√    |Chrome, Firefox, Edge|Chrome OS|[官网](https://setupvpn.com/)
TomVPN        |√      |   |       |   |     |                  |      |20G/月，可看广告得流量；[开源网址](https://gitlab.com/tomxiaoha/tom)
Free OpenVPN  |√      |√  |√      |√  |√    |                  |      |[官网](https://www.freeopenvpn.org/en/)
DotVPN        |√      |√  |       |   |     |Chrome, Firefox, Opera|  |[官网](https://dotvpn.com/en)
OPENVPN       |√      |√  |√      |√  |√    |                  |      |[官网](https://openvpn.net/)
SPEEDTEST     |√      |√  |√      |√  |√    |Chrome            |Apple TV|[官网](https://www.speedtest.net/)
Mast VPN      |√      |   |       |   |     |                  |       |[官网](https://www.mast-studio.net/)
Savage VPN    |√      |   |       |   |     |                  |       |[官网](https://www.savagevpn.com/)
VPN4Test      |√      |   |√      |√  |√    |                  |       |[官网](https://vpn4test.com/)    
Rava VPN      |√      |√  |√      |√  |     |                  |       |[官网](https://anyuezhixin.cn/)  
Free VPN      |√      |√  |       |   |     |                  |       |[官网](https://freevpn.org/)    
Tenon VPN     |√      |√  |√      |√  |√    |                  |       |[官网](https://www.tenonvpn.net/)
杰克VPN       |√      |   |       |   |     |                  |       |[官网](https://gitithub.com/jack/blob/master/)
JustVPN       |√      |√  |Coming soon…||   |                  |       |[官网](https://justvpn.net/)
逗鲨/蓝鲸VPN  |√      |   |       |   |     |                  |       |[官网](https://www.whalerun.net/)
TunSafe       |       |   |√      |   |     |                  |       |[官网](https://tunsafe.com/)
一键连加速器  |√      |√  |敬请期待|敬请期待||                  |       |[官网](https://firstadmedia.cn/)
蜜蜂加速器    |√      |√  |       |   |     |                  |       |[官网](http://www.mifengf.com/)
佛跳墙加速器  |√      |√  |√      |√  |     |                  |       |[官网](https://fotiaoqiang.io/)
蚂蚁加速器    |√      |√  |√      |   |     |                  |       |[官网](https://b.antss.me/)
 
[如何在 Windows 上安装 设置 OpenVPN，附免费VPN节点和使用教程 | 零度解说](https://www.youtube.com/watch?v=rwi0tPd-owU)

[还在用付费VPN?2022年神奇实测TOP8史诗级VPN ！免费更比付费强,最高能跑100M ！8款即装即用，无需注册，安全纯净无广告，稳定高效，8K高速，不限流量，不限设备，一键连接，全球网络！ - YouTube](https://www.youtube.com/watch?v=4ZqddPgn9B4)

**VPN导航网站**
网站               |备注             |点击访问
--|:--:|:--:
国外VPN大全        |  |[1](https://www.vpnwebsite.net/)
国外VPN网址导航    |  |[2](https://www.bestvpp.com/)
the best VPN deals|  |[3](https://thebestvpndeals.com/)
翻墙者             |  |[4](https://www.fanqiangzhe.com/)  


### <h1 id="5">3.3 SS/SSR/V2ray/Clash/Clashr/winXray<h1>

#### <h2 id="6">3.3.1 软件下载<h1>
 
网站|网址1|网址2|备注
--|:--:|:--:|---
v2rayNG|https://github.com/2dust/v2rayNG||仅Android
v2rayN|https://github.com/2dust/v2rayN||仅Windows
clash|https://github.com/Dreamacro/clash||支持Windows、Linux
ClashForAndroid|https://github.com/Kr328/ClashForAndroid||仅Android
winXray|https://github.com/TheMRLL/winxray|https://winxray.com/|仅Windows
Trojan|https://trojan-gfw.github.io/trojan/||支持Windows、Linux、MacOS


 停止的项目：
 
- v2ray：
 
 网站|网址
 ---|---
 v2ray官网|[①](https://v2ray.com/) / [②](https://www.v2ray.com/)
 GitHub分流地址|https://github.com/v2ray/v2ray-core
 
 关于 V2Ray社区和V2Ray “进化” 成 V2Fly社区和Xray 的原因：[V2Ray - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/V2Ray)
 
 - ssr：
 
  网站|网址
 ---|---
 electron-ssr-backup|https://github.com/qingshuisiyuan/electron-ssr-backup|
 shadowsocksrr|https://github.com/shadowsocksrr
 
 - Qv2ray: https://qv2ray.net/


#### <h2 id="7">3.3.2 免费节点分享<h1>
网站      |ss                                        |ssr                                                  |v2ray|
--|:--:|:--:|:--:
lncn.org |                                   |[1](https://lncn.org/)
放牧的风|[1](https://www.youneed.win/free-ss)| [2](https://www.youneed.win/free-ssr)                  | [1](https://www.youneed.win/free-v2ray)
免费翻墙网|[2](https://freefq.com/free-ss/)    |[3](https://freefq.com/free-ssr/)                      |[2](https://freefq.com/v2ray/)
翻墙党   |[3](https://fanqiangdang.com/forum-50-1.html)|[4](https://fanqiangdang.com/forum-2-1.html)  |[3](https://fanqiangdang.com/forum-36-1.html)
免费上网账号|                                   |[5](https://free-ss.site/)                            |[4](https://free-ss.site/)
ssrtool  |                                     |[6](https://ssrtool.us/tool/free_ssr)                 |[5](https://ssrtool.us/tool/share_v2ray)
free-v2ray|                                       |                                                    |[6](https://github.com/iwxf/free-v2ray)
[node.umelabs.dev](https://github.com/umelabs/node.umelabs.dev)|√|√|√
[ShadowSocksShare](https://github.com/the0demiurge/ShadowSocksShare)|√|√|×
[Free Proxies](https://smart.zxcyec.top/)|√|√|√
 
 碧海免费节点池：https://proxies.bihai.cf/
 
 kingFu景福：https://kf03.kingfu.cf/
 
 Free Proxies：https://fq.lonxin.net/
 
Free Proxies: https://proxy.leefake.xyz/

2022免费机场公益机场免费vpn合集SSR-V2ray-2022.11更新 - 机场推荐： https://jichangtuijian.com/%E5%85%8D%E8%B4%B9ssr%E5%92%8Cv2ray%E6%9C%BA%E5%9C%BA.html
> 2022.11.9


#### <h2 id="8">3.3.3 机场导航<h1>
网站|备注|点击访问
---|:--:|:--:
翻墙党公益||[1](https://jichang.fanqiangdang.com/)  
我爱白嫖||[2](https://52bp.org/index.html)
灯油||[3](https://iyideng.cloud/)
DuyaoSS||[4](https://www.duyaoss.com/page/1/)


> (跑路机场清单)[https://github.com/limbopro/paolujichang]

#### <h2 id="9">3.3.4 其他相关网站<h1>
网站|备注|点击访问
--|:--:|:--:
月下博客||[1](https://ssrvps.org/)
ssr节点||[2](http://ssssr.net/ssssr)
免费SSR/SS||[3](https://m.ssrtool.us/free_ssr)
SSR中文网||[4](https://ssr.tools/)
奇少部落||[5](https://qsbl.cc/)
V2RaySSR综合网||[6](https://www.v2rayssr.com/)  
网络跳跃||[7](https://hijk.art/)  
V2Ray中文网||[8](https://v2raycn.com/) 
SSRSHARE||[9](https://www.ssrshare.com/)
freegfw  ||[10](https://freegfw.cf/)
我们所向往的||[11](https://gmail.gitbook.io/wmsxwd/)
SSRSpeed||[12](https://github.com/NyanChanMeow/SSRSpeed)
ACL4SSR在线订阅转换||[13](https://acl4ssr-sub.github.io/)

 

### <h1 id="10">4.1 在系统设置里设置VPN或代理<h1>
这种方法不需要下载任何软件就可以实现科学上网。
平台|方法
:-----:|:-----:|
Android（以华为手机为例）|设置——更多连接——VPN——添加VPN网络——。。。
Windows（以Windows 10为例）|设置——网络和Internet——VPN——添加VPN连接——。。。/ 设置——网络和Internet——代理——。。。

后面的步骤根据使用代理设置的不同而不同，以下是提供VPN或代理的网站。
网站|备注|点击访问
--|:--:|:--:
VPN Gate||[1](https://www.vpngate.net/cn/)
Free Proxy List||[2](https://free-proxy-list.net/)
FreeProxy.World||[3](https://www.freeproxy.world/)
Free-Proxy.com||[4](http://free-proxy.cz/zh/)



### <h1 id="11">5.1 搭建服务器<h1>

在YouTube遇到的教程：  
+ ~~[2020年永久免费云服务器VPS（IBM Clould）申请，搭建永久免费VPN！无需信用卡，只需一个邮箱，永久免费部署V2ray科学上网！](https://m.youtube.com/watch?v=aML8c6sqIzI)~~    
有个YouTuber说[IBM不管用了](https://m.youtube.com/watch?v=JcyxZmTagNE)。
+ [仅需一个邮箱，利用heroku免费容器一分钟内零代码快速搭建不熟V2ray，比VPN翻墙安全，科学上网白嫖党千万不要错过了！](https://www.youtube.com/watch?v=XyI4NgjLCUo)
+ [2020年最新永久免费云服务器VPS （HeroKu）申请，搭建免费VPN！无需信用卡，只需一个邮箱，永久免费部署V2ray科学上网！速度4K稳定奔放，已经用一年！ - YouTube](https://www.youtube.com/watch?v=xEewUeWDNeI)
- [翻墙那些你务必要知道的事! 搭建科学上网该如何选择VPS？ | 零度解说 - YouTube](https://www.youtube.com/watch?v=dFaS9Db42Qc)



### <h1 id="12">5.2 搭建路由<h1>
+ [软路由安装教程，闲置笔记本设置旁路由，双臂路由！科学上网更快更稳定！2020 | 零度解说 - YouTube](https://www.youtube.com/watch?v=nEU4hbZYj6c&ab)
+ [（小白也能学会）❤群辉NAS安装软路由，软路由设置，无线AP设置，家庭网络设置，比较详细适合新手【#阿雷科技】 - YouTube](https://www.youtube.com/watch?v=qbWWGEHBowQ&ab)
+ [R2S软路由销量之王！R2S安装openwrt攻略 openwrt软路由设置 - YouTube](https://www.youtube.com/watch?v=ZCmbbnIBD78&ab)
- [软路由加速！Openwrt加速组件 R2S提速40% Openwrt Turbo ACC加速有用吗？ - YouTube](https://www.youtube.com/watch?v=kCBAuHqun3g)

## <h1 id="13">6.1 其他<h1>
网站|备注|点击访问
--|:--:|:--:
Share-SSR-V2ray||[2](https://github.com/selierlin/Share-SSR-V2ray)
new-pac||[3](https://github.com/Alvin9999/new-pac/wiki )
w3-goto-world||[4](w3-goto-world)

## <h1 id="14">6.2 翻墙信息<h1>
网站|备注|点击访问
--|--|:--:
墙外看    |  |[1](https://qiangwaikan.com/)
VPN信息网 |  |[2](https://vpnxxw.com/)
10BEASTS |  |[3](https://10beasts.net/)
翻墙网络  |  |[4](https://fanqiang.network/)
翻墙LIVE  |  |[5](https://www.fanqiang.live/index/index)
VPN时光网 |  |[6](https://vpnsg.net/)
WizCase  |  |[7](https://zh.wizcase.com/blog/)
VPN大大  |  |[8](https://www.vpndada.com/)  
vpnMentor|  |[9](https://zh.vpnmentor.com/)
翻墙软件  |  |[10](https://www.chromeba.net/)   
VPNnice  |   |[11](https://www.vpnnice.com/)  
翻墙党     |  |[12](https://fanqiangdang.com/)  
免费翻墙网 |  |[13](https://freefq.com/)  
爱翻墙    |   |[14](http://greatagent-ifanqiang.github.io/greatagent2-ga/ifanqiang.htm)  
小明VPN   |   |[15](https://www.xiaomingvpn.com/)
世界公民  |   |[16](https://www.49gm.org/)
 VPN PICKS| |[17](https://www.vpnpicks.com/)


## <h1 id="15">6.3 有试用期的VPN<h1>  

VPN|试用时长|备注|官网
--|:----:|:----:|:----:
PronVPN|15天||[1](https://proon.top/)  
VPN Unlimited|7天||[2](https://www.vpnunlimitedapp.com/)
PUREVPN|7天||[3]( https://www.purevpn.com)
VyprVPN|3天||[4](https://0e591b83-f8a0-4a41-addb-3c0ef2141879.netrule.net/zh/)  
兔兔加速|3天||[5](https://v2.558844.xyz/)
坚果VPN|1天||[6](https://nutsvpn.work/)  
光年VPN|1天||[7](https://lightyearapp.club/zh)
快连   |1天||[8](https://letsvpn.world/?hl=zh)
||||
免费翻墙网总结|||[总结](https://freefq.com/vpn/)
 
 
 ## <h1 id="16">6.4 其他软件<h1>
 
 [proxypool](https://github.com/zu1k/proxypool)

 [ProxySU](https://github.com/proxysu/ProxySU)
 
 [netch](https://github.com/netchx/netch)
 
 v2ray-core|https://github.com/v2fly/v2ray-core||支持Windows、Linux、MacOS、Android
