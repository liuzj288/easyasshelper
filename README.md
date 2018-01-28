版权所有，转载请注明出处

最新帮助地址：[简书](https://www.jianshu.com/p/f3615e8036a2)

![](http://upload-images.jianshu.io/upload_images/7734354-fa5f061ecf9d735a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

首先，要申明一点，过去与现在，电影的字幕都不是问题。并且，网络如此自由，未来也不是问题。只是分享的平台不会一家独大，分享的途径方式也会多种多样。

电影院看电影可享受视听体验，不过由于种种原因，一些电影在电影院只能观看阉割版，另外引进电影官方字幕有时候真的坑爹，使用字幕组的优质字幕可以弥补这个缺陷，有的凶残字幕组也会带来一些惊喜！

![](http://upload-images.jianshu.io/upload_images/7734354-608ecc630325bb4f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)


对于喜欢追剧又有外语学习需求的朋友，双语字幕不可或缺，本软件可从字幕组和字幕库等多个网站批量下载整季乃至所有字幕，并支持自动解压，方便从中选择最好的字幕，值得你尝试。

![](http://upload-images.jianshu.io/upload_images/7734354-b0450ae47182e33a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)



# 支持网站与网址

字幕库  [http://www.zimuku.cn/](http://www.zimuku.cn/)
字幕组  [http://www.zimuzu.tv/](http://www.zimuzu.tv/)
163字幕  [https://163sub.com](https://163sub.com)
射手(伪)  [http://assrt.net/](http://assrt.net/)
唧唧 [http://www.jijidown.com](http://www.jijidown.com)
btbaocai http://www.btbaocai.me/
btbit http://cn.btbit.xyz/
verycd http://www.verycd.com/



# 版本说明

## 2.0.42
1.新增残留临时文件自动清理功能(非正常情况退出只需要重启软件即可自动清理)
2.修复磁力搜索"找不到magnet.txt的错误"

## 2.0.4
1.新增影视搜索功能(bt搜索)
2.支持bt包菜搜索
3.支持btbit
4.支持电驴
5.支持自动复制磁力链到剪切板

![](http://upload-images.jianshu.io/upload_images/7734354-031f4e322209c192.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)


## 2.0.3
1.新增弹幕下载功能
2.优化调整了界面
3.优化计时

![](http://upload-images.jianshu.io/upload_images/7734354-a355561f8ee205d7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

## 2.0.2
1.新增字幕库网站
2.添加自动检查新版本功能
3.修复少量错误

![](http://upload-images.jianshu.io/upload_images/7734354-96e9b1f6d60b8d17.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

## 2.0.1
1.支持自动解压
2.支持拖拽操作
3.支持批量处理
4.支持字幕组
5.支持163sub
6.支持射手网(伪)

# 使用教程

软件是用bat写的程序，采用主程序加插件的架构，直接从网页获取信息，主要用于影视剧字幕的批量下载。操作流程设计的应该还算比较简洁了，这里简单做点下介绍

## 软件下载与安装

为了支持自动更新，我把软件放在Github，虽然软件自身比较小，但是由于封装aria2c，curl等工具，实际打包后也有将10MB了，考虑到有的朋友上github龟速，我也在国内网盘上放置备份（不保证最新），软件自身自带aria2c支持自动更新（虽然这么说，但不是某些软件的强制更新，也需要你按[u]确定）

跟大多数软件要求一样，下载完毕请把软件放到非中文路径，如"D:\Programs\Easyasshelper\"

软件是绿色便携版软件，主体为bat脚本，使用Quick Batch File Compiler打包为exe，不需要放在C盘，也不写入注册表，只是在查询中会**在软件目录写入临时文件**（为了调试方便没有写入临时文件夹或隐藏目录），这些临时文件在下载结束会自动删除。

个别国产安慰软件可能会误报，这里我提供virscan和virustotal的查毒报告供参考，介意慎下：

viruscan报告：
[http://r.virscan.org/report/3a5e157c06e9846476012eff0182960c](http://r.virscan.org/report/3a5e157c06e9846476012eff0182960c)

virustotal报告：
[https://www.virustotal.com/#/file/251cacbc220b3628449d482bb0a33fa5f532212829c9a48a1492f08feeb4592b/detection](https://www.virustotal.com/#/file/251cacbc220b3628449d482bb0a33fa5f532212829c9a48a1492f08feeb4592b/detection)

连误杀之最卡巴都没报毒，某数字这是来搞笑的么？

![](http://upload-images.jianshu.io/upload_images/7734354-eaa53b3c3e887e5f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

## 软件使用【字幕】

软件有三个工作模式：

![](http://upload-images.jianshu.io/upload_images/7734354-43d706e9c66f3769.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

### 1.关键词模式

与一般软件使用别无二致，直接双击打开软件，在提示栏中输入查询关键词后回车，再根据提示选择字幕库，然后去喝杯茶等待下载完成即可。

![](http://upload-images.jianshu.io/upload_images/7734354-4eef63283906aedf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

**说明**

软件使用的是网页接口，和浏览器登陆网站查询结果是一致的，所以能否匹配到字幕就跟关键词有关，多个关键词不需要是用空格分割。

电影推荐名称加年份，如"X战警3+2006"

电视剧推荐名称加季数，如"神盾局特工S02"

关于数据库的选择比较自由，电影可用字幕库，射手（伪），字幕组的电影字幕比较缺页比较老；电视剧可用字幕组，字幕库；当然你也可以选择把几个网站的所有字幕都下载下来，便于比较字幕质量选择最优字幕。

### 2.文件名模式
双击打开软件，在提示栏中拖入视频文件，回车后选择字幕库，软件将把文件名作为关键词进行查询，然后等待下载完成即可。

![](http://upload-images.jianshu.io/upload_images/7734354-3eac8a8c87bb67bf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

**说明：**
这里是直接使用文件名作为关键词，能否匹配到字幕九不一定了，但是一旦匹配到字幕那就是视频发布组发布的字幕了，时间轴准确度也是最好的，所以其实可以先用文件名查一下是否有匹配，没有的话再手动输入关键词查询。

### 3.自动模式
不用打开软件，拖动视频文件到程序图标上即可，软件将自动完成查询（首先查询字幕库1，没有字幕则查询字幕库2，依此类推）。

![](http://upload-images.jianshu.io/upload_images/7734354-4e94d822735a69b4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/240)

**说明：**

由于软件启动是需要时间的，我提供了直接把文件拖拽到程序图标上获取文件名作为关键词的功能，也为此选择了还算卡哇伊的程序ico，还算比较方便

这种方法唯一的缺点就是文件名和路径不要有空格等特殊字符，否则可能会报错，如果遇到这种情况，使用模式一或者去掉特殊符号均可。

### 注意事项

1.关于关键词

软件使用的是网页接口，和浏览器登陆网站查询结果是一致的，所以能否匹配到字幕就跟关键词有关，多个关键词不需要是用空格分割。

电影推荐名称加年份，如"X战警3+2006"

电视剧推荐名称加季数，如"神盾局特工S02"

一般来说，英文名称搜索的结果应该更多。

2.关于准确度

软件和网站的显示是一致的，影响准确度的只有关键词，模式二和模式三由于直接采用文件名作为关键词，识别率有所下降，这时候只要提取名称+年份用模式一重新搜索即可。不过如果你是从网上直接下载的原文件名的话，使用模式二和三有可能匹配到更准确的字幕。

3.字幕位置

模式一：软件目录

模式二：软件目录

模式三：视频文件目录\关键词_sub\

![](http://upload-images.jianshu.io/upload_images/7734354-92ddad689116b4d2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)


### 4.查询实例1：神盾局特工S02

关键词：“神盾局特工S02”

字幕库选择 [2]字幕组

![](http://upload-images.jianshu.io/upload_images/7734354-4aa3e533471bafd4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

输入后回车再按2，很简单吧！

![](http://upload-images.jianshu.io/upload_images/7734354-d5508f922df16f57.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

出去喝杯茶，等待下载完毕

![](http://upload-images.jianshu.io/upload_images/7734354-165294ed4a3bf10a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

这是下载后的原始字幕压缩包

![](http://upload-images.jianshu.io/upload_images/7734354-a824384c06eeccb6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

这是解压后的字幕，我默认设置自动提取语言为简体&英文的字幕

![](http://upload-images.jianshu.io/upload_images/7734354-ba19cfe50232a3b6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

这样就把神盾局特工第二季所有字幕下载完毕了，想想手动的工作量~~

## 软件使用【弹幕】

虽然已经出现了挺长时间，但还是简单做个回顾。

“弹幕”本是军事用语，指炮火密集射击时，炮弹像在天空张开一张弹幕的景象，所以“弹”读dàn而不是tán。

![](http://upload-images.jianshu.io/upload_images/7734354-2517886ae426b93e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

由于在动画导演富野由悠季的一系列动画作品，如《圣战士丹拜因》、《机动战士Z高达》中，“左舷弹幕太薄了！”作为一句名台词反复出现，“弹幕”才逐渐由专业的军事术语，变成了二次元流行词，进而流行开来。

弹幕之所以成功一方面是伟大拯救人类孤独，另一方面也为观影增添了额外的乐趣。

每天公交地铁仍然没有座位，打卡机的时间总比你快一分钟，KPI仍遥遥无期看到boss只想逃，给喜欢的人发的微信再一次石沉大海。又是孤独有点尴尬，差不多的一天。回家看视频时，萌点、泪点、帅点、槽点也无人理解、无人分享。很多人都曾生活在这样的孤独中，直到Ta的出现。

人类发明的各种语言表达工具中，没有任何一种能比弹幕更诚实、透明地反映集体心理。而且弹幕本身就是对视频的二次创作，很多本身略显无聊的镜头有了弹幕加持，反而变成了经典的搞笑镜头。

示例1：无缝接台词

![](http://upload-images.jianshu.io/upload_images/7734354-85dc51aa7ba10ca5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

示例2：有槽必须吐

![](http://upload-images.jianshu.io/upload_images/7734354-1531acb804ed9a5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

示例3：交流

![](http://upload-images.jianshu.io/upload_images/7734354-3ac97e55bbae7b86.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

总之弹幕有自己的发笑机制。它让一群有相同笑点，互相能get到梗的人聚集到了一起，给了年轻人一个抵抗、调侃、戏谑主流文化的平台。毕竟，不是谁都能幸运地在每段现实生活中，遇到志趣相投的朋友。空虚寂寞没人撩时，打开视频，开启弹幕，看着上面滚滚而过，正如自己所思所想的话语，这种瞬间被理解的感觉，就像鸦片一样令人欲罢不能。

当然弹幕也是一把双刃剑，过多弹幕乃至低质量弹幕将极大影响观感，下面是两个负面示例

示例1：弹幕过多

![](http://upload-images.jianshu.io/upload_images/7734354-8a52d0d0eafbe9f4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

示例2：质量低

![](http://upload-images.jianshu.io/upload_images/7734354-7155541857a8bad8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

这时候就可以使用正则匹配过滤弹幕。

### 1.弹幕搜索
由于B站弹幕存在分P，补丁等问题，虽然我也写了直接下载到本地的程序，但是这里还是使用唧唧down的搜索功能，输入关键词后将跳转到唧唧主站的搜索页面，例如输入"变相怪杰1994"回车后将弹出搜索页面

![](http://upload-images.jianshu.io/upload_images/7734354-6aac260e0297bf60.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

这是搜索页面

![](http://upload-images.jianshu.io/upload_images/7734354-2e4e1f45c007dbaf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

然后点击弹幕文件

![](http://upload-images.jianshu.io/upload_images/7734354-5e358828e8499bac.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

选择下载xml弹幕 （ass弹幕需要由xml转换）

![](http://upload-images.jianshu.io/upload_images/7734354-d0071f7280627d17.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

### 2.av号

av号依旧使用唧唧down的网页，同上

### 3.cid号

cid号可以说是弹幕文件的身份证号，但是难以逆向查看匹配的视频信息，好处是直接输入即可下载。

### 4.弹幕播放

xml格式需要播放器支持，这里推荐dandanplay

ass格式(其实就是字幕)所有播放器均支持

### 5.弹幕过滤

弹幕正则过滤，推荐直接导入现成规则

### 6.分P弹幕合并

推荐使用bililocal

### 7.弹幕同步(时间轴调整)

推荐使用bililocal

## 软件使用【其他】

### 1.软件更新

当左上角提示有新版本时，按[U]启动更新即可

![](http://upload-images.jianshu.io/upload_images/7734354-759aa039fcb8ae32.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

更新完毕会询问是否打开网址反馈，为了软件的健康更新，希望你及时反馈遇到的问题，当然如果你喜欢本软件，也不吝表扬，一定要过来踩一下哦~~~（以后版本会逐渐关闭此项）

### 2.查看帮助

按[H]可查看最新帮助

### 3.软件退出

软件正常运行不会产生垃圾文件

软件报错可强行关闭，然后在软件目录删除后缀名为空和*.temp的临时文件

### 4.使用反馈

软件虽然比较简单但功能还算实用，由于水平有限，难免会出现诸多BUG，如果你喜欢本软件，还请及时反馈，多多反馈你遇到的问题。

![](http://upload-images.jianshu.io/upload_images/7734354-9cc5607428d48b56.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

如果你喜欢此软件，那更应该过来踩踩，你的肯定才是软件更新和维护的动力，甚至你还可以捐赠此软件！（嗯，我考虑下是否加入打赏功能）

52破解：[https://www.52pojie.cn/thread-692462-1-1.html](https://www.52pojie.cn/thread-692462-1-1.html)

简书：[http://www.jianshu.com/p/f3615e8036a2](http://www.jianshu.com/p/f3615e8036a2)

Github：[https://github.com/liuzj288/easyasshelper](https://github.com/liuzj288/easyasshelper)

以上3个是我目前在用和维护的，其他地方发布的一律是盗版，请谨慎下载与使用。

![](http://upload-images.jianshu.io/upload_images/7734354-c6f381d9c4d70485.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)


## 字幕使用

防止还有人不知道如何加载字幕，再说明一下。

### 改文件名

将.srt、.ass、.ssa等字幕文件名改成与前面与电影视频名一样（后缀扩展名不改），放在同文件夹下。大部分播放器都支持此种方法自动加载（目前百度网盘在线播放也支持此种方法）。 

如视频：Under.the.Skin.2013.BluRay.720p.DTS.x264-CHD.mkv 

字幕文件为：Under.the.Skin.2013.BluRay.720p.DTS.x264-CHD.srt 

或改成这样：

Under.the.Skin.2013.BluRay.720p.DTS.x264-CHD简体.ass 

【推荐】推荐这种方案，"简体"为播放器字幕轨界面现实的字幕名称，而且有多个字幕可以共存，如

Under.the.Skin.2013.BluRay.720p.DTS.x264-CHD简体&英文.ass 

Under.the.Skin.2013.BluRay.720p.DTS.x264-CHD英文.ass 

这也是字幕组规范的命名方式

![](http://upload-images.jianshu.io/upload_images/7734354-bc79b011da16f452.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/500)

**说明：**

ass、ssa扩展名的是特效字幕，带有颜色、大小等特效，srt字幕无特效，三者均可用记事本打开、编辑。 

### 直接拖拽
在播放视频时，将字幕文件直接“拖”到播放窗口。这种方法不需要放置在同一文件夹，也不会自动加载，可以在比较字幕时使用。

说了这么多，一句话总结

![](http://upload-images.jianshu.io/upload_images/7734354-4a307d8d850cc89c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/600)



# 下载地址

Github：https://github.com/liuzj288/easyasshelper

