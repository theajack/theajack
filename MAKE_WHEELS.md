<!--
 * @Author: chenzhongsheng
 * @Date: 2023-06-16 21:30:27
 * @Description: Coding something
-->
# [这些年造过的一些轮子记录](https://github.com/theajack/theajack/blob/master/MAKE_WHEELS.md)

by - [theajack](https://github.com/theajack) 【2023/06/16 晚】

一晃眼，毕业从事前端也有4年时间了，如果从大三实习开始算起，那就是8年时间了。也算是比较久了，不过惭愧自认为没有什么大的建树。

做一个阶段性的回顾和反思吧，也就是流水列举一下这么些年做过的一些东西。以免年纪大了记忆模糊了[doge]

## 2014年-2016年 [实习+本科]

2014年：大三暑假在一个学长的创业公司实习，大学期间学习的东西就是各种都学点零散的皮毛。相当于从头开始学习前端。

### 微信墙

印象比较深刻的是做了一个微信墙，带弹幕带抽奖功能的。花了很多心思，做的也不错，得到了一笔实习工资之外的奖励。

那时候的主要使用的还是 jQuery、Notepad++、Bootstrap

### C# 3d俄罗斯

另外印象比较深的时候就是在校期间做的一些小游戏。印象最深的是这款C#写的[3d俄罗斯](https://download.csdn.net/download/yanxiaomu/8337227?spm=1001.2014.3001.5503)。老师上机课上当堂表扬了像是'专业团队的作品'，回想起来还是很有成就感的。

### 毕业设计

毕设也是做的游戏。当时爱玩部落冲突，想着能做一款类似的游戏，于是从设计、美工、变成一步一步地完成了一款名为突破防线的建造类游戏，使用 Java 开发的安卓应用。

比较傻瓜的单机APP，没有使用引擎，全靠原生一个什么组件的API绘制出来，组件名字我不太记得了。。。

另外帮同学做了一款套安卓壳子的H5应用，也就是后来流行起来的 Hybrid App 模式。这个[代码仓库](https://github.com/theajack/stone-finance)保留了下来

### 关于AI的思考

当时曾经有一个异想天开的想法，用程序写一个可以像婴儿一样自己成长的程序，通过与人的交互来自己学习，变得可以与人交流，有思考能力。但是这个想法确实与当时自己的能力和执行力严重不匹配，也就是想了想而已。

知道ChatGPT一夜爆火，突然当时的这个想法在内心深处点了我一下：如果当时深究这个想法，去了解，学习，然后从事AI方向，不知道想在会不会成为一个比较成功的自己。

## 2016-2019 研究生阶段

### 2048Plus

2048这款小游戏那段时间莫名的或，然后我研究生的暑假期间做了一款2048的升级版本，支持最高6阶、可保存进度、使用四种道具。使用的也是Java。

### BikeShare

ofo火遍了每一个校园，且那个时候每辆车的车牌和密码是一一对应的，萌生了一些不好的想法。做了一个记录和分享单车密码的网站（我有罪，好在基本没人用），前端用的还是jQuery，后端是用的C#。

### 外包项目

与同学合作接了一些外包，也是在这个时间学习了Vue和React，并且在外包项目中应（lian）用（shou）了。影响比较深的是某珠宝公司的官网、某学院的学生考试系统...，赚了点零花钱。

初次之外学习使用了Git，也开始使用Github写一些自认为有意思的东西。开始了造轮子之路

### [jetterjs](https://github.com/theajack/stone-finance)

低配版jQuery，对其jQuery封装了DOM操作，也就是这个项目中算是夯实了js基础。

### [BQL](https://github.com/theajack/bql)

最近改名迁移到 [Selon](https://github.com/theajack/selon)了

包含JQL和BQL两个东西，JQL是 Json Query Language，想SQL一样操作Json

BQL是Bind Query Language，将JQL与UI结合起来，数据改变了直接更改UI，底层是基于jetterjs来做UI操作的

### [jetee](https://github.com/theajack/jetee)

学习了Vue的原理之后，觉得很有意思，也想写一个类似的东西，于是有了这个东西，耗费了大量时间做了周边很多基础设置，包含Router、国际化等，甚至整了一个ui组件库 JUI 和 完整的文档。

由于没有认真学习Vue源码，现在回过头看代码实现非常糟糕。。但是也就是这么个东西在毕业面试的时候给我提供了很大的吹牛空间【doge】

### [打字打飞机游戏](https://github.com/theajack/type)

无意间玩到一个英文打字消除飞机的游戏，觉得很有意思，萌生了做一个汉字打字的游戏，但是需要查汉字拼音的功能。于是有了下面这个现在 1.9k star的代码仓库

### [cnchar](https://github.com/theajack/cnchar)

始于上面的打飞机游戏，一直维护到现在，经历了no-bundle 到 webpack 到 monorepo rollup，代码从js迁移到ts，文档从readme到vuepress。逐渐发展为一款功能全面的汉字工具库。

### [bombbattle](https://github.com/theajack/bombbattle)

又是一款纯canvas撸出来的游戏。印象比较深的是熬夜做了很多碰撞体积计算和性能优化。

### [tc-editor](https://github.com/theajack/tc-editor)

又是一款纯canvas撸出来的游戏。印象比较深的是熬夜做了很多碰撞体积计算和性能优化。

### 奔跑的柴柴

一款微信小游戏，累计用于应该是有 2w多，靠广告收入了应该有几百块，小游戏刚出来那会广告收入是真的高。

### 抢票加速互助

那个时候流行抢票互助二维码，于是做了一个可以发布二维码互相帮忙的社区类小程序。后端是白嫖的小程序云开发。前不久免费配置取消了，目前改小程序不可用了。

### 友评价

仿QQ坦白说的微信小游戏，就是微信好友之间互相评价。为什么要用小游戏不是小程序，因为只有小游戏可以使用微信好友关系链数据。同样白嫖的小程序云开发。

## 2019-2022 [第一份工作期间]

工作期间业余时间在家也会写一些有意思的东西。从此之后的基本全都是用ts来写了

### [disable-devtool](https://github.com/theajack/disable-devtool)

star数第二多的仓库，防止通过任何方式打开开发者工具的工具。很多黑科技，也被浏览器升级和兼容问题折磨的够呛。目前还是会有一些浏览器不起效。

### [jsbox](https://github.com/theajack/jsbox)

基于vue和monaco的在线代码和执行环境，后面我的所有项目演示demo都放在这个上面了。

留了一个支持文件系统和多文件编辑的坑。可以节后后面做的webos填一把坑。

### [idb-logger](https://github.com/theajack/logger)

webworker + indexeddb 做的本地日志存储方案，支持localstorage降级使用等。感觉是一个比较有前景的方向。

### [string-worker](https://github.com/theajack/string-worker)

解决worker文件需要使用cdn地址的问题，直接可以使用字符串创建worker

### [tc-image](https://github.com/theajack/tc-image)

挖的一个还没填完的大坑，使用AssemblyScript来做图片操作，实现了高斯模糊、裁剪、基础滤镜等效果。

### [webos-term](https://github.com/theajack/webos)

一个更大的坑，不管算是填的比较完整的一个坑了。基于HTMLFileSystem做的web命令行界面，模拟了基础的linux命令，实现了文件系统，webos-module可以直接运行es6，支持import引入npm包。

### [macos](https://github.com/theajack/mac)

一个更更大的坑。基于webos-term做的仿Macos的web应用，目前只做了基础的ui，使用的vue3

### [pixi-vue](https://github.com/theajack/pixi-vue)

又是一个大坑，vue3提供了自定义渲染，于是结合pixi，希望可以将vue3运行canvas上，最终目标是希望运行在小游戏上用vue3做ui。只完成了基础功能

### [canvas-render-html](https://github.com/theajack/canvas-render-html)

这是最大的一个坑了。既然vue3可以，那为什么vue2不行？为什么react不可以？于是便想着直接抛弃vue3自定义渲染，直接将HTML代码通过pixi渲染到canvas上，那么不就可以在上层使用任何框架在canvas上写ui了吗？目前只是发布了一个beta版本。

### [alins](https://github.com/alinsjs/alins)

或许是觉得上的jetee写的太烂了，于是重新搞了一个alins框架，目标是all in js，html、css都是响应式的，无vdom、html、css，无编译。拿起来就能用。

### [ebuild-cli](https://github.com/theajack/ebuild-cli)

每次想写一个新轮子的时候都得复制很多工程代码，于是有了这个用来快速启动一个新项目的cli工具。包含了webpack、rollup、npm包、vue、nodejs等模板。

### [dingdong-node](https://github.com/theajack/dingdong-node)

疫情期间封控在家写的叮咚买菜nodejs下单脚本。抢到过几次菜

### [corss-window-message](https://github.com/theajack/corss-window-message)

跨窗口通信方案。自认为功能很强大很酷。。

### [tc-event](https://github.com/theajack/disable-devtool)

烂大街的事件仓库

### [qrcodejs](https://github.com/theajack/qrcode)

二维码编码解码的仓库。封装的第三方库

### [css图标库](https://github.com/theajack/easy-icon)

easy-icon：一个很丰富的css图标库

### [easy-test-lib](https://github.com/theajack/easy-test-lib)

一个简单地单元测试工具

### [miniapp-mixin](https://www.github.com/theajack/mp-mixin)

微信小程序的mixin工具，可以解决跨页面状态共享的问题

### [评论回复框组件](https://www.github.com/theajack/tc-comment)

tc-comment：支持markdown、emoji，支持实时预览的评论组件。同时搭配了评论列表和回复。配有后端接口免费试用

### [留言板](https://www.github.com/theajack/message-board)

message-board：基于tc-comment的一个免费开发使用的留言板。只需要给个appid即可零代码免费接入

### [dom操作库](https://www.github.com/theajack/easy-dom)

easy-dom：封装了基本的dom操作。算是jetterjs的升级和简化版本吧。

### [简单的ui库](https://www.github.com/theajack/tacl-ui)

tacl-ui：基于easy-dom做的简单的ui，仅包含toast、confirm、loading、pop四个组件。

### [pure-v](https://github.com/theajack/pure-v)

一个很纯粹简单的表单校验工具。

### [laya-game](https://github.com/theajack/laya-game)

仿合成大西瓜做的合成大篮球。第一款完整使用游戏引擎做的游戏，基于的是layabox。

### [count-code-line](https://github.com/theajack/count-code-line)

一个计算项目有多少行代码、多少字符的命令行工具。用nodejs写的

### [util](https://github.com/theajack/util)

开发常用功能代码片段合集

### [salary-caculator](https://github.com/theajack/salary)

工资计算器。跳槽的时候算工资涨幅的时候写的。

### [university](https://github.com/theajack/university)

高考期间看到一个新闻，有大学生填志愿报到了野鸡大学。于是有了这个可以查询大学的工具。

### [landscape-simulator](https://github.com/theajack/landscape-simulator)

移动端横屏模拟器。用来在竖屏的时候自动模拟横屏的效果。

### [tcon](https://github.com/theajack/tcon)

类似eruda的移动端调试工具

### [piano-type](https://github.com/theajack/piano)

一个钢琴打字游戏

### [magic](https://github.com/theajack/magic)

一个读心魔术小游戏

### [tools](https://github.com/theajack/tool)

小工具合集

## 2022-至今（2023/6/16） [第二份工作期间]

### [eveit](https://github.com/theajack/eveit)

又是一款烂大街的事件仓库，为什么要再造一个？因为之前的太大了，且ts类型支持不友好。

### [sener](https://github.com/theajack/sener)

一款nodejs服务端框架。想做一个社区APP，觉得现有的express、egg等不好用，自己撸了一个，数据库用的mongodb

### [3D键盘](https://github.com/theajack/keyboard)

keyboard: 一个很有意思的3d键盘。主要功能是用来查询keycode

### [粒子绘画器](https://github.com/theajack/particle-drawer)

particle-drawer：一款很有意思的粒子绘画器。可以绘制文本和图片。可以基于此在业务层绘制视频的动图。

### [AI nodejsSDK](https://github.com/theajack/spark-node)

spark-node：讯飞星火认知大模型openAPI的nodejsSDK。官方没有提供nodejs版本，于是撸了一个

## 结语

活到老，撸到老。总的来算这些年做的大都是一些面向开发的东西，没有大的成就，也没有什么收益。后续可能希望更多的做一些独立应用，能搞点副业收入是比较好的。

当然之前没有填完的坑还是会继续填一填。过几年再更新。