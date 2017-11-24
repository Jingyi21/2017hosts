<img src="https://camo.githubusercontent.com/af4cf563b43a022ec902562c91c26521d2ed9dbb/68747470733a2f2f7777772e676f6f676c652e636f6d2f6c6f676f732f646f6f646c65732f323031362f686f6c69646179732d323031362d6461792d332d736f75746865726e2d68656d697370686572652d353138353031313932393035353233322d687032782e676966"></a>
#### 提示：所有网站均需要以https方式打开，置顶提醒！tumblr网页版播放视频都是从用户的子域名获取文件的，所以没法播放。<br />
#### 近期更新：2017年7月18日
** 此说明请务必仔细阅读 **

** 请各位网络喷子，网评员，水军等人自觉绕道，左拐不送！**

## 简介

这里更新最新可用的hosts，这里更新的分为手机版和电脑版。

使用本hosts更新源提供的hosts可以获得完美的youtube视频（如果因为重定向超时加载不出来的话刷新一下网页就好了，最新的hosts目前中国大陆多地区实测刷新率降到1%以下，重定向是可以自行重定向的，相关服务器域名也是其他人的hosts里几乎没有的）和其他服务的较完美体验（已经在所有hosts里添加google云端硬盘视频预览域名，电脑版本google+的网页大图预览问题也已经解决，播放视频或许还不完美），请在杀毒软件内添加hosts信任！如果你要想添加什么网址你可以开启一个lssues并清晰地表明你的意愿。本hosts不保证随时可用，但是我会尽我最大努力让它高可用。

手机版则可以访问play商店并下载应用，youtube在设备支持的情况下国内网络带宽足够的情况下可以裸连观看720p或480p,欢迎将本项目分享给更多的人，方便更多人自由上网。 手机版的hosts因为找ip比较麻烦，所以暂时更新较慢，下一步将上ipv6hosts。hosts文件较大，替换后系统读取需要时间，在此期间可能会出现youtube没反应等情况。

## 下载hosts文件（可直接把地址复制，输入第三方下载器，下载好改名为hosts替换进设备）
* [电脑(windows)版](https://raw.githubusercontent.com/wangchunming/2017hosts/master/hosts-pc)

windows替换文件路径  `C:\Windows\System32\drivers\etc\hosts`

* [手机版](https://raw.githubusercontent.com/wangchunming/2017hosts/master/hosts-mobile)

手机替换文件路径 `/etc`  **需root**（在linux平台下同样是这样，只不过是需要通过终端获得root后，再调出gedit或者vim编辑。）
## 维护目的

** 维护hosts不为别的，自己用的同时还有就为方便同时开发者或者学生的你/您，因此本页面也没有像其他某些hosts项目一样的捐款项目，请不要误会。**

** 一万三千余行，这一切只为了更好的体验！已经在发布时100%验证可用性，敬请放心使用，献给所有热爱自由的人们！（如果万一替换后无效请自己手动转文档格式）近期更新频率会有所上升，因为IP被屏蔽的时间会越来越短。**

## 警告

WALL具备刺探TLS的能力（可以知道你访问的URL详细地址并且可以拿到交换的证书也可以检查提交的表单），请大家小心，因此请勿使用直连方式来进行一些私人行为，谢谢，**这不是危言耸听**，一旦触发规则则会返回诸如“*此网站无法提供安全连接*”、“*x处的网页无法链接*”等错误。

## 提示

* 如果你位于中国电信网内，该项目处提供的hosts可能会无法正常使用，因为电信众所周知的出国慢，我也没有解决办法。

* 想要加什么网站（当然需要支持https），尽管拍砖尽管吼哦，毕竟这是方便你和我的好事，不用客气。

* 如果突然连着连着ip就不通了有70%的可能是被运营商反向封了访问权限，只需要重新拨号或者重启手机即可解决，如果无法解决就是ip失效.

* 少数地区的运营商，例如移动或者鹏博士或者爱普，也可能无法正常使用本处提供的hosts。
* Google 等网站请通过 https 方式访问，如 https://www.google.com/ncr 或者 https://www.google.com.hk 避免因响应http请求时的重置连接。这几版的hosts会一直更新，敬请大家留意关注。

## 测试情况：

### 手机

* 客户端可用：play市场，Google搜索，chrome，googleplus,google街景,google报亭,google环聊,google健身,google地图,googleallo,googleDuo,tumblr,twitter,facebook,instragram,duckduckgo,dropbox（...更多20个）
* 客户端不可用：Gmail,telegram（仅两个）
* 功能不可用：查找设备（安卓）【因为纯UDP流量过不了墙，所以无法使用】
* 网页可用：100%可用

### 电脑

2017.7.18 更新：

* **youtube**
发布时测试功能98%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/QQ%E6%88%AA%E5%9B%BE20170121230113.png"></a>

* **Tumblr**
发布时测试功能：50%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/QQ%E6%88%AA%E5%9B%BE20170121230507.png"></a>

* **Google**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/1.png"></a>

* **Facebook**
发布时测试功能99%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/2.png"></a>

* **维基百科**
测试功能正常率100%
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/3.png"></a>
* **Dropbox**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/4.png"></a>

<del>
* **Twitter**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/5.png"></a>
</del>

* **vimeo**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/6.png"></a>

* **github**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/7.png"></a>
* **Bing（HK）**
发布时测试功能100%正常（需要https打开）
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/8.PNG"></a>
