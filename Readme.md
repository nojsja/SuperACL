# SuperACL 
#### 简洁易用的ACL进出网规则 
```

 ____                              _     ____  _
/ ___|  _   _  _ __    ___  _ __  / \   / ___|| |
\___ \ | | | || '_ \  / _ \| '__|/ _ \ | |    | |
 ___) || |_| || |_) ||  __/| |  / ___ \| |___ | |___
|____/  \__,_|| .__/  \___||_| /_/   \_\\____||_____|
              |_|

```
[![HomePAGE](https://img.shields.io/badge/Home-Page-blue.svg?style=flat)](https://powerfulweb.nciyuan.net)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](https://github.com/Windelight/SuperACL/blob/master/License.md)
[![VersionName](https://img.shields.io/badge/Version-108Alpha1Pre4-orange.svg?style=flat)](https://github.com/Windelight/SuperACL/tree/master)
[![ChangeLOG](https://img.shields.io/badge/Change-Log-red.svg?style=flat)](https://github.com/Windelight/SuperACL/blob/master/ChangeLog.md)

**Tip**:[点击/长按此处立刻复制链接](https://raw.githubusercontent.com/Windelight/SuperACL/master/inchina.acl)并粘贴到软件中即可快速开始使用！  

_本项目是 `BitBucket` 和 `Coding` 以及 `GitLab` 上面的备份项目的同步源_

## 简介
 本规则有以下两种模式
 * 大陆出国模式(仅代理中国大陆有访问问题的网站)
 * 海外回国模式(代理范围为中国大陆地区的网站)  

本规则可以帮助您  
- [x] 代理在中国大陆被封锁的网站 (eg. Google、 Facebook、 Twitter)
- [x] 代理在中国大陆访问速度较慢或不稳定的网站 (eg. GitHub、 Amazon AWS)
- [x] 代理在中国大陆有访问限制的网站 (eg. Steam Powered、 Xbox Live)
- [x] 代理其它在中国大陆不能完整访问的网站 (eg. Bing、 Wikipedia、 WordPress)
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
     - Answer: 本项目主要目的是改善网络访问，其中不单单包含各种形式下被软封或自封以及被 GFW 金榜题名的网站，也包括类似你正在用的 GitHub 这样速度数十 KB/s很慢很慢却可以打开的网站，以及 OneDrive 加上 Office 365 这种配套服务而其中一个掉环了，又或者 XDA 安卓开发者论坛中刷不全网页等等不佳的网络情形。经过改善后取决于服务器速度可以做到秒开、快开、完整加载，这样节省了许多时间，所以这才是真正的改善。
 - Ask: 为什么出国版文件中没有某些知名度很高的“真相”网站？
     - Anwser: 亲爱的用户，你想看的话敬请您老人家自己动手，美利坚14188？从结束封建帝制后，中国人一直想谋求国家大统、复兴。其中在复兴的历史上我们遭到了西方部分帝国主义国家全方面打击。而后中华民国在大陆地区走了，台湾省和福建省在蒋总统中正先生和蒋总统经国先生带领下又一次复兴了。大陆在迎来共和国并经过20年红党极左派政治斗争和对人民迫害的结束后终于有了改革开放伟大创举。改革开放后我们不断的进步和超越，终于要富强起来了，大陆在习主席近平先生的带领下实现了不断深化改革，我们国家的国际地位和国际影响力正在不断的提高，美国作为现存的唯一的世界霸主，对中国进行全方位升维打击，而网络是十分关键的一环。而因为网络信息传递速度极快，更多的谣言被发散，并且美国国际声誉大家都知道，自私自利，选边战队，永远希望自己掌控规则并为了自己的利益，中国遵守你的规则并打败了规则制定者，而这个人只想改变规则对自己，网络媒体更这样。你永远不知道编瞎话的人脑洞有多大，自己都能哐哐打脸自己，比如幹话王大纪元时报，你踏马吹牛逼都不带谷歌一下，自己背后有美爹就牛逼坏了？我很奉劝所谓追求所谓真相的大陆白痴，习主席那么多政绩在你眼里一文不值？就算共产党黑历史一本辞海都写不下，就算共产党最下面的搞小帮派区分小阶级一堆一堆，难道你都没看到习主席大力抓反腐败？你们既然都是翻墙的人了，就不能稍微谷歌一下美国的金钱政治学？我们实行现在有仅次于三民主义的可能是世界上第三好的社会主义国家制度难道你们就被黑洞屏蔽了咋滴完全感受不到？天哪你都有谷歌了就不能稍微搜索一下美国的社会是什么的样子？我们的国家多好啊！你们就真的要盲目的信吗？还有轮子家族和自由家族的媒体，就不能学学台湾三立电视台？虽然那么黑大陆但是做起来也不讨厌，BBC和纽约时报时不时收点钱刊登一篇什么文章中共都不搭理，也不会自己砸百年老店招牌，
 
支持列表 (Ver. 1.08-Alpha1-Pre4): 位于 [SupportList.md](https://github.com/Windelight/SuperACL/blob/master/SupportList.md) 文件中  
不会操作或使用吗？建议您先移步本项目 [Wiki](https://github.com/Windelight/SuperACL/wiki) 来获得更多帮助哦!  
遇到了使用问题？欢迎您移步到本项目 [Issue](https://github.com/Windelight/SuperACL/issues) 想我们提交反馈哦! 


## 版权
* Copyright &copy; 2016-2019 NciYuan! Team. Common Rights Statement.
* Copyright &copy; 2019 Guan 'Windelight' MingZheng. All Rights Reserved.  

*** MIT License ***
