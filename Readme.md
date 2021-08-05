# MasterACL 
#### 简洁易用的ACL进出网规则 
```

 __  __              _                _     ____  _
|  \/  |  __ _  ___ | |_  ___  _ __  / \   / ___|| |
| |\/| | / _` |/ __|| __|/ _ \| '__|/ _ \ | |    | |
| |  | || (_| |\__ \| |_|  __/| |  / ___ \| |___ | |___
|_|  |_| \__,_||___/ \__|\___||_| /_/   \_\\____||_____|

```
[![HomePAGE](https://img.shields.io/badge/Home-Page-blue.svg?style=flat)](https://powerfulweb.nciyuan.net)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](https://github.com/Windelight/SuperACL/blob/master/License.md)
[![VersionName](https://img.shields.io/badge/Version-1.09_Ver.1-orange.svg?style=flat)](https://github.com/Windelight/SuperACL/tree/master)
[![ChangeLOG](https://img.shields.io/badge/Change-Log-red.svg?style=flat)](https://github.com/Windelight/SuperACL/blob/master/ChangeLog.md)

**Tip**: [点击/长按此处立刻复制链接](https://raw.githubusercontent.com/Windelight/SuperACL/master/inchina.acl)并粘贴到软件中即可快速开始使用！  

_本项目是 `BitBucket` 和 `Coding` 以及 `GitLab` 上面的备份项目的同步源_

**前排提示: 因本作者现已开学，所以本项目除主要文件外其他文件全部 Delay 更新，但两份规则文件仍会保持每周更新！**  
**终止时间: 2019年2月17日 终止版本号: 1.08-Alpha1-Pre4 （不再继续累加版本，停止同步，但文件持续更新）**  

# 武漢加油！Wu Han Chia You！  
# 中國加油！Chung Kuo Chia You！  

## 简介
 本规则有以下两种模式
 * 大陆出国模式(仅代理中国大陆有访问问题的网站)
 * 海外回国模式(代理范围为中国大陆地区的限制境外访问网站)  

本规则可以帮助您  
- [x] 代理在中国大陆被封锁的网站 (eg. Google、Facebook、Twitter)
- [x] 代理在中国大陆访问速度较慢或不稳定的网站 (eg. GitHub、Amazon AWS)
- [x] 代理在中国大陆有访问限制的网站 (eg. Steam Powered、Disney+)
- [x] 代理其它在中国大陆不能完整访问的网站 (eg. Bing、Wikipedia、WordPress)
- [ ] 回国模式则反之亦然，欢迎海外华人使用哦 (*σ´∀`)σ
> 但同时也请您注意：  
> 1. 我们不会主动去屏蔽广告和国内域名，所以本规则不具有主动屏蔽广告的功能，也不会代理任何 `.cn` 域名哦
> 2. 我们的项目不基于 `GFWList` 以及 `ChinaList`，并且更加严格，所以我们不会添加法轮功等实在是看不下去的网站
> 3. 我们会尽可能多地完善这份列表，但是仍然可能会存在失效、过期和疏漏，欢迎您通过PR或者Issue来反馈

## 使用
适用的软件平台 (已测试):
- [x] Shadowsocks for Android
- [x] Shadowsocks-RSS for Android  
- [ ] ~~Shadowsocks-Qt~~
- [ ] ~~Shadowsocks-Libev~~

文件内容:
- `inchina.acl` <u>适用于出国代理</u>  
  - 实时更新地址: https://raw.githubusercontent.com/Windelight/SuperACL/master/inchina.acl
- `inforeign.acl` <u>适用于回国代理</u>
  - 实时更新地址: https://raw.githubusercontent.com/Windelight/SuperACL/master/inforeign.acl  

使用方法 (via [Shadowsocks for Android](https://github.com/shadowsocks/shadowsocks-android)):
 1. 打开您的桌面/启动器上的 `影梭` 
 2. 从屏幕左侧边缘向右滑动，在侧栏上点击 `自定义规则` 
 3. 再点击位于右上角的添加规则图标并在下拉栏中点击手动设置
 4. 在对话框中点击下拉栏并选择 `在线规则文件URL` 
 5. 粘贴本规则的文件地址并点按确定
 6. 回到 `配置文件` 主界面点击笔按钮修改需要的配置项目现状
 7. 将配置中的 `功能设置` -> `路由` 更改为 `自定义规则` 并点击右上角 √ 保存  
 
简易 FAQ:
 - Ask: 为什么两份文件中有些地址明明可以直接访问却仍被添加上？
     - Answer: 本项目主要目的是改善网络访问，其中包括各种自和谐和封锁。比如你正在使用的 GitHub，访问出奇的慢(数十 KByte/s)却仍然可以访问，导致体验实在是差。所以我们也会添加一些这样的域名来改善网络体验。
 - Ask: 为什么使用过后反而觉得网络有些变慢了？
     - Answer: 本项目出国版文件中包含了部分一般情况下可以正常打开的网站，比如必应中国等。这样的网站由于自我和谐的原因导致有用的资料无法检索，所以会被添加。如果您正在使用一些免费服务或者网络不是很好的服务器，导致代理流量速度过慢（推荐速度不小于10Mbps），您就会感觉到网速被"拖慢了"。
     
     
支持列表 (Ver. 1.08-Alpha1-Pre4): 位于 [SupportList.md](https://github.com/Windelight/SuperACL/blob/master/SupportList.md) 文件中  
不会操作或使用吗？建议您先移步本项目 [Wiki](https://github.com/Windelight/SuperACL/wiki) 来获得更多帮助哦!  
遇到了使用问题？欢迎您移步到本项目 [Issue](https://github.com/Windelight/SuperACL/issues) 想我们提交反馈哦! 


## 版权
* Copyright &copy; 2021 Guan 'Windelight' MingZheng. All Rights Reserved.  
* Copyright &copy; 2016-2021 NciYuan! Team. Common Rights Statement.

*** MIT License ***
