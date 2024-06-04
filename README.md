[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=evilbutcher)](https://github.com/anuraghazra/github-readme-stats)

# Quantumult X 脚本和规则整理

#### [English Version](https://github.com/evilbutcher/QuantumultX/blob/master/README_EN.md)

绝大多数代码都用到了@chavyleung 的 Env.js 和@Peng-YM 的 OpenAPI.js，感谢！

### 如果实际使用下载速度太慢推荐"加速器"：[GLaDOS](https://glados.space/landing/3JRG4-KSGZJ-8QPXF-8PPOO)（3JRG4-KSGZJ-8QPXF-8PPOO）

## 脚本合集

### 【BoxJs】订阅

https://raw.githubusercontent.com/evilbutcher/QuantumultX/master/evilbutcher.boxjs.json

### 【Quantumult X】脚本订阅合集+自己写的去广告

https://raw.githubusercontent.com/evilbutcher/QuantumultX/master/QuantumultX.rewrite.conf
https://raw.githubusercontent.com/evilbutcher/QuantumultX/master/QuantumultX.task.json

### 【Surge】脚本订阅合集

https://raw.githubusercontent.com/evilbutcher/QuantumultX/master/Surge.tasks.sgmodule
https://raw.githubusercontent.com/evilbutcher/QuantumultX/master/Surge.cookies.sgmodule

### 【Loon】脚本订阅合集

https://raw.githubusercontent.com/evilbutcher/QuantumultX/master/Loon.scripts.conf

## 脚本

### [微博超话（单账号）](https://github.com/evilbutcher/QuantumultX/tree/master/check_in/weibo)

#### 功能特点

1. 自动获取最新超话列表。
2. 自动签到。
3. 如果超话数量大于 100，可以先检查签到情况，未签到才会执行，更好解决签到频繁问题。
4. 支持 BoxJs。

### [自用签到](https://github.com/evilbutcher/QuantumultX/tree/master/check_in/glados)

#### 功能特点

1. 自动签到。
2. 查看流量信息。
3. 支持 BoxJs。
4. checkin_env.js 修改自@Neurogram-R，增加了多平台支持。

### [公众号监控](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/wechatsubs/wechatsubs.js)

#### 功能特点

1. 设定关键词监控公众号推送。
2. 可自定关键词推送间隔。

### [热门监控](https://github.com/evilbutcher/QuantumultX/tree/master/check_in/hotsearch/hot.js)

#### 功能特点

1. 可以选择性监控榜单。
2. 可以分别设定每个榜单的最热内容数量。
3. 可以选择是否附带话题链接。
4. 可以自定每个榜单是匹配关键词还是获取最新内容。
5. 可以自定每个榜单内容独立推送还是合并推送。
6. 一些榜单单独推送时支持封面。
7. 支持 BoxJs。
8. 监控微博热搜关键词。
9. 监控知乎热榜关键词。
10. 监控百度风云榜关键词。
11. 监控 B 站日榜关键词（对应关系：0 全站，1 动画，3 音乐，4 游戏，5 娱乐，36 科技，119 鬼畜，129 舞蹈）。
12. 监控豆瓣电影关键词。
13. 监控抖音视频关键词。
14. 监控 36 氪关键词。
15. 监控 Kindle 图书关键词。
16. 监控 RSSHub 订阅，感谢@api-evangelist-[rss2json](https://github.com/api-evangelist/rss2json)。
17. ~~监控人人影视最新上传，配合捷径[磁力离线](https://www.icloud.com/shortcuts/cfad8390798e459db458d6233d229209)可实现磁力下载，解锁追剧新姿势。~~
18. 可自定关键词推送间隔。

### [App 价格监控](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/appstore/AppMonitor.js)

#### 功能特点

1. pp 可单独设置区域，未单独设置区域，则采用 reg 默认区域。
2. 设置区域方式“1443988620:hk，1443988620/us，1443988620-uk，1443988620_jp，1443988620 au”。
3. 支持 BoxJs by evilbutcher。

### [NASA 每日一图](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/nasa/nasapic.js)

#### 功能特点

1. 首先前往https://api.nasa.gov/ 申请一个 API，秒通过。
2. 将申请好的 API 填入 BoxJs。
3. 可以选择输出中文还是英文。
4. 点击通知可以打开浏览器图片-保存。

### [iDaily 每日环球视野](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/idaily/idaily.js)

#### 功能特点

1. 可选择随机 or 最新内容。

### [Funboat](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/funboat/funboat.js)

#### 功能特点

1. 喜欢 funko 可以关注该微信小程序。

### [九木杂物社](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/jiumu/jiumu.js)

#### 功能特点

1. 九木杂物社自动签到。

### [酷乐潮玩](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/klcw)

#### 功能特点

1. 酷乐潮玩小程序、App 自动签到。

### [信息查询](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/wechatsubs)

#### 功能特点

1. 支持事业单位招聘监控。
2. 支持高校人才网监控。

### [彩票查询](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/ssq/ssq.js)

#### 功能特点

1. 支持双色球、大乐透、福彩 3D、七乐彩。
2. 支持仅查询当日开奖的彩票。

### [华住会](https://github.com/evilbutcher/QuantumultX/blob/master/check_in/hzh/hzh.js)

#### 功能特点

1. 自动签到。
2. 领取奖励（开发中）。

## 规则类

### [去广告](https://github.com/evilbutcher/QuantumultX/tree/master/remove_ad)

#### 功能特点

[Readme](https://github.com/evilbutcher/QuantumultX/tree/master/remove_ad/README.md)

### 免责声明

1. 此脚本仅用于学习研究，不保证其合法性、准确性、有效性，请根据情况自行判断，本人对此不承担任何保证责任。
2. 由于此脚本仅用于学习研究，您必须在下载后 24 小时内将所有内容从您的计算机或手机或任何存储设备中完全删除，若违反规定引起任何事件本人对此均不负责。
3. 请勿将此脚本用于任何商业或非法目的，若违反规定请自行对此负责。
4. 此脚本涉及应用与本人无关，本人对因此引起的任何隐私泄漏或其他后果不承担任何责任。
5. 本人对任何脚本引发的问题概不负责，包括但不限于由脚本错误引起的任何损失和损害。
6. 如果任何单位或个人认为此脚本可能涉嫌侵犯其权利，应及时通知并提供身份证明，所有权证明，我们将在收到认证文件确认后删除此脚本。
7. 所有直接或间接使用、查看此脚本的人均应该仔细阅读此声明。本人保留随时更改或补充此声明的权利。一旦您使用或复制了此脚本，即视为您已接受此免责声明。

### 访问量

![](http://profile-counter.glitch.me/evilbutcher/count.svg)
