[![zico](https://raw.githubusercontent.com/zoomla/zico/master/lib/logo512x512.png "一个专为中国开发者而生的跨平台图标解决方案-Powered by zoomla!逐浪CMS团队")](http://ico.z01.com "一个专为中国开发者而生的跨平台图标解决方案")

# 一个专为中国开发者而生的跨平台图标解决方案

zio是一个非常优秀的webfont与svg图标展示系统，它的目标是让全栈开发者与用户可以自由的任何页面引用矢量级的图标。

随着计算机软件技术的进步，人们无论是在开发传统客户端软件、移动APP软件、微信公众号、微信小程序、Facebokk内页，或从事web网站系统的开发，都需要用到图标。

可以说，一个UI交互界面，除了颜色、字体之外，最重要的就是图标系统了，一个好的图标可以让人们对界面（应用）一目了然，并提升业务能力。
当前版本：1.0


# 获得zico程序包
zico是免费开源的，我们提供了多种便利的安装使用方法
1. 载离线程序包
你可以点击这里下载最新官方发布程序包
[zico官方程序包](http://ico.z01.com/zio.zip "zio官方程序包")
我们会不断更新此程序包，以保证其是最新更新，而且它是一个袖珍文件，很快就能下载完成。
下载后，解压开即可使用。

2. 通过Npm安装
全球流行的Npm安装方式自然是非常简单了，其命令是：
`npm i zico`
这需要你的系统安装了nodeJS，这有一个快速教程：
<video src="http://ico.z01.com/UploadFiles/gtizio.mp4" poster="http://ico.z01.com/Template/zicon/style/Images/logo512x512.png" controls="controls" width="920"> 
  
3. 通过Github安装
我们还在全球最大的源码开放平台Github上发布,zio源码仓库的访问地址是
[https://github.com/zoomla/zico](https://github.com/zoomla/zico "https://github.com/zoomla/zico")

4. CDN引用
如果你不想下载和安装，也可以直接CDN引用，只要在网页和应用中中置入zico的CDN源地址即可，其URL请求源为：
`http://ico.z01.com/zico.min.css`
这个网址同时支持SSL，你也可以采用
`https://ico.z01.com/zico.min.css`
以及自便应模式
`//code.z01.com/zico.min.css`
都是合法的。

# 引用文件
由于zio可以在多种场合（如网页开发、app、小程序、客户端、传统设计）中引用，所以不同的软件引用方法各不相同，这里仅以在网页上引用为例，其引用规范为：
`<link rel="stylesheet" href="css/zico.min.css" >`
注意上面文件的路径真实可在，其完整源码结构应该如下图所示：
css/
fonts/

# 在任何你要引用图标的web(移动页面)应用图标 
推荐的引用方法是：
`<i class="zi zi_music"></i>`

当然，你也可以使用其它任意你想要的用的标签，如：
`<span class="zi zi_music"></span>`
`<div class="zi zi_music"></div>`
`<p class="zi zi_music"></p>`
`<a href="#" class="zi zi_music"></a>`
上面的方法都是完全适用，而且同样可以输出结果的，是不是很方便^_^

如果你是一个高级web开发者，熟悉Emmet语法，还可以直接用简写的方式，即
`.zi.zi_music`
形式展开，就能完成快速的应用zico图标。
如下图所示：
![](/uploadfiles/180531.gif)

接下来，我们将引导讲解一系列深度的应用技巧，其中包括：
1. 在微信开发中引用zico
2. 美化zico
3. 赋予zio动作
4. 一些优秀的应用技巧




# 轮子
前辈们说，不要重复制造轮子。
问题是：如果从来没有轮子呢？

那个在半夜三分抠着脚用着外文工具的抠脚大汉，很能成就一个复兴强国的开发重任-当然我们身边更多的是勤奋的中国开发者。

# 弥补缺位的文化
中国文化大国，以CJK为代表东方文化，有着其独特的文明与传承体系，然而，目前网上没有一个完全以中国人出发、中国人设计、或为中国人设计的web图标应用集（即使是阿里的ICO系统也是零碎的设计师作品集合），无法实现Npm引用，基于SVG的JS输出解决方案也没有。
所以，致力于中国基础软件研发的[Zoomla!逐浪软件](http://www.z01.com/corp "Zoomla!逐浪软件")团队着力开发了这一系统。

# 中国的元素
纯粹引用外国的，造成很多缺位。
比如八仙桌，方桌。
比如馒头、碗
比如长城，公安局，全都没有。
> 既拥抱国际、又体现东方之美我们的定位就是开发一个既拥抱国际、又体现东方之美的ICON图标集。
用程序员的思路、服务于程序和全栈，甚至是普通的公文写作、AI设计、图形描绘也能用上这一套工具，所以我们有了CSS引用、JS输出、桌面引用三套方法。



习近平主席说：一个国家和民族，不能总用别人的昨天来装扮自己的明天。
一个强盛的民族，应该有自己的图标集和开发工具。

# 特色图标
zico图标系统还加簇了中国五百强，包括美的、格力、小米。
我们认为中国的知名企业能够担当起这一份殊荣，以后WEB开发者们在引用知名企业图标时，可以借助zico方便的引用。
（否则靠外国图标靠，是不可能支持包括京东、中国银行、格力、小米这些企业图标的）。
系统同步支持拼音检索、拼简首字母检索、汉字检索、英语检索。


zico基于逐浪图标的元素，力求改变这一目标！
中国技术不能受制于人，文化也同样不应受制于人。

# 五大特色

我们的图标集特色：
1、覆盖主流图标集
2、有中国元素
3、更好的使用
4、中国服务器引用更快
5、免费开放


# 对比表格
你一定关心zico图标系统有何不同，这里我们罗列了一些我们与同类产品的对比。
![](http://ico.z01.com/uploadfiles/image/10.jpg)


# 效率对比
我们以微软公司Visual Studio软件为例，来对比两种输入状态的效率，zico在这方面遥遥领先：
![](http://ico.z01.com/uploadfiles/image/10.gif)


# 与华文领域排名第一的Zoomla!逐浪CMS结合使用
作为web全栈图标引用工具，与CMS结合开发是首要之义。

Zoomla!逐浪CMS是一款基于dotNET技术构建的高端CMS，也是目前华文领域alexa排名第一的web建站产品，不同于国内一众CMS只满足于生产“垃圾流量网站”，逐浪软件产品定位于服务企业级产品，集成电商、APP、微信、OA、办公流、在线组卷等功能，并且是免费开放的。
得益于微软平台黑科技，Zoomla!逐浪CMS的性能也是强大的，其TB级SQL SERVER数据库，是与纽约证券交易所同级别的应用。
逐浪CMS官网：[www.z01.com](http://www.z01.com "www.z01.com")
点击就能免费下载这款功能强大、完全免费的CMS产品，用于构建您的WEB、移动、全栈应用。

# 引用逐浪CMS标签
部署好Zoomla!逐浪CMS后，您只要引用
`{Z L:Boot4()/ }`
标签，就能在模板中输出zico文件。



其引用如下图：
![](http://ico.z01.com/uploadfiles/image/05.jpg)


在模板中，只要放入标签，如下图：
![](http://ico.z01.com/uploadfiles/image/06.jpg)


即能在浏览器引用逐浪CMS内置的zico图标，如下：
![](http://ico.z01.com/uploadfiles/image/07.jpg)


其头代码结构：
```html

<!DOCTYPE html>
<html lang="zh-cn">
<head>
<meta charset="utf-8">
<meta name="msapplication-TileColor" content="#1A0066"/>
<meta name="msapplication-TileImage" content="/images/win8_symbol_140x140.png"/>
<title>逐浪CMS_首页</title>
<meta name="Keywords" content="META关键字">
<meta name="Description" content="META网页描述">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="renderer" content="webkit|ie-comp|ie-stand">
<link href="/dist/css/bootstrap4.min.css" rel="stylesheet"/>
<link href="/dist/css/zico.min.css" rel="stylesheet"/>
<script src="/JS/jquery.min.js" ></script>
<script src="/dist/js/popper.min.js"></script>
<script src="/dist/js/bootstrap4.min.js"></script>

```


每一个Zoomla!逐浪CMS都会集成当时最新的zico源码，值得体验。


真正开放，Github、Npm同步开发，展现中国人的的创造力和产生能力！


# 捐赠支持
欢迎给我们捐赠，我们珍重并感谢您的回报。

![](http://ico.z01.com/UploadFiles/Image/pay.png)

请用微信扫上方赞助码给予我们支持！
如果你需要进一步的联络以及商业赞助，欢迎点此[联系我们](http://ico.z01.com/Item/1402.aspx "联系我们")

# 捐赠回报
由于zico是开源项目，我们本身没有收益，但我们真诚渴望您的支持，对于赞助者：
1、提供我们站群资源的链接SEO支持。
2、提供专业的项目管理咨询
3、提供一定的技术指导
4、可于社区公开捐赠名单，以兹表扬。
5、对于企业级大额捐赠，开具发票，并提供超额的商业回报。


# 鸣谢名单（排名不分先后|且不保证为最新披露）
我要买房网&福居百汇（中国威海）孙总 [www.5yaomaifang.com](http://www.5yaomaifang.com "www.5yaomaifang.com")
