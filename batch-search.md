## 批量搜索

**RunAny除了运行还能搜索，还能批量搜索！**

在菜单中添加搜索网址，先选中任意文字，按<kbd>\`</kbd>后就可以选择想用的搜索，更有一次批量搜索功能。

?> 内置购物、视频、图片、软件、音乐、网盘类等搜索网站，复制需要的到`RunAny.ini`内使用

![RunAny演示批量搜索](/assets/images/RunAny演示批量搜索.gif)

## 搜索网址

**复制以下需要的功能写入`RunAny.ini`文件保存、重启RunAny，然后选中任意文字后打开菜单即可搜索**

<details>
<summary>日常搜索</summary>

```ini
聊天|tencent://message/?uin=QQ号&Site=&menu=yes
百度(&B)|https://www.baidu.com/s?wd=%s
百度指数|http://index.baidu.com/v2/main/index.html#/trend/springboot?words=
谷歌(&G)|https://www.google.com/search?q=%s&gws_rd=ssl
谷歌商店|https://chrome.google.com/webstore/search/%s?hl=zh-CN
谷歌Play|https://play.google.com/store/search?q=%s
翻译(&F)|https://translate.google.cn/#auto/zh-CN/
知乎(&Z)|https://www.zhihu.com/search?type=content&q=%s
github|https://github.com/search?utf8=%E2%9C%93&q=%s&type=
```

</details>
<br>
<details>
<summary>视频搜索</summary>

```ini
-视频(&V)
	A站|http://www.acfun.cn/search/#query=%s
	B站|http://search.bilibili.com/all?keyword=%s
	优酷|http://www.soku.com/search_video/q_%s
	腾讯|http://v.qq.com/x/search/?q=%s
	爱奇艺|http://so.iqiyi.com/so/q_%s
	乐视|http://so.le.com/s?wd=%s
	搜狐|http://so.tv.sohu.com/mts?wd=%s
	360|http://so.360kan.com/index.php?kw=%s
  --
	vimeo|https://vimeo.com/search?q=%s
	youtube|https://www.youtube.com/results?search_query=%s
	nico|http://www.nicovideo.jp/search/%s
```

</details>
<br>
<details>
<summary>购物搜索</summary>

```ini
-购物(&S)
	淘宝(&T)|https://s.taobao.com/search?q=%s
	天猫|http://list.tmall.com/search_product.htm?q=%s
	京东(&D)|http://search.jd.com/Search?keyword=%s&enc=utf-8
	--
	1688|https://s.1688.com/selloffer/offer_search.htm?keywords=%s
	亚马逊|https://www.amazon.cn/s/field-keywords=%s
	当当|http://search.dangdang.com/?key=%s
	苏宁|http://search.suning.com/%s/cityId=110
```

</details>
<br>
<details>
<summary>图片搜索</summary>

```ini
-图片(&P)
	谷歌图片|https://www.google.com/search?tbm=isch&q=%s&safe=off
	yandex|https://yandex.com/images/search?text=%s
	百度图片|http://image.baidu.com/search/index?tn=baiduimage&ie=utf-8&word=%s
	搜狗|http://pic.sogou.com/pics?query=%s
	必应|https://www.bing.com/images/search?q=%s
	好搜|http://image.so.com/i?q=%s
  --
	flickr|https://www.flickr.com/search/?w=all&q=%s
	tumblr|http://www.tumblr.com/search/%s
```

</details>
<br>
<details>
<summary>音乐搜索</summary>

```ini
-音乐(&M)
	网易|http://music.163.com/#/search/m/?s=%s&type=1
	百度音乐|http://music.baidu.com/search?key=%s&ie=utf-8&oe=utf-8
	虾米|http://www.xiami.com/search?key=%s
	QQ音乐|https://y.qq.com/portal/search.html#page=1&w=%s
```

</details>
<br>
<details>
<summary>绿软搜索</summary>

```ini
-绿软(&R)
	小众软件|https://www.appinn.com/?s=%s
	绿盟|http://www.xdowns.com/index.php?ac=search&keyword=%s
	异次元软件|http://www.iplaysoft.com/search/?s=548512288484505211&q=%s
	zd423|http://www.zdfans.com/search.asp?keyword=%s
	软件缘|http://www.appcgn.com/?s=%s
	精品绿色便携|http://so.portablesoft.org/cse/search?q=%s&s=521260595841649407
	;	Portable便携软件|http://forum.portableappc.com/search.php?keywords=%s
```

</details>
<br>
<details>
<summary>网盘搜索</summary>

```ini
-网盘(&W)
	爱挖盘|http://www.iwapan.com/so.aspx?wd=%s
	去转盘网|http://www.quzhuanpan.com/source/search.action?q=%s&currentPage=1
	西林街|http://www.xilinjie.com/s?q=%s
	搜白度盘|http://www.sobaidupan.com/search.asp?wd=%s&so_md5key=06625be22887c8bd0ea3ff47265611b3
	百度云so|http://www.bdyunso.com/search-all-%s-1
	印象|https://impress.pw/search?site=pan.baidu.com&tab=disk&q=%s
	盘搜|http://sou.pansou.com/?q=%s
	;	呆木瓜|http://md5.daimugua.com/search.aspx?q=%s
```

</details>