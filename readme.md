#模仿Bilibili（Bilibili - ( ゜- ゜)つロ 乾杯~）
> 练习工程 模仿bilibili

##接口

>使用 m.bilibili.com中使用的

###首页接口

* 滚动推荐: http://api.bilibili.com/x/web-show/res/loc?jsonp=jsonp&pf=7&id=1695
* 最近搜索关键词排行 ：http://www.bilibili.com/search?action=hotword&main_ver=v1
* 3天内排行： http://www.bilibili.com/index/ranking-3day.json
* 番剧更新：http://www.bilibili.com/api_proxy?app=bangumi&action=timeline_v2
* 科技区/动画区等各个区的排行：http://m.bilibili.com/index/ding.html
* 直播推荐: http://api.live.bilibili.com/h5/recommendRooms?callback=jQuery17209296492127193972_1494936264824&_=1494936265374

####滚动推荐

>http://api.bilibili.com/x/web-show/res/loc?jsonp=jsonp&pf=7&id=1695

该链接在 m.bilibili.com/index.html 源代码254行产生。


##第三方

* [Alamofire](https://github.com/Alamofire/Alamofire) 网络请求
* [PageMenu](https://github.com/PageMenu/PageMenu) 分页
* [GDPerformanceView](https://github.com/dani-gavrilov/GDPerformanceView-Swift) 显示fps
* [SnapKit](https://github.com/SnapKit/SnapKit) autolayout
* [HandyJSON](https://github.com/alibaba/HandyJSON) json序列化
* [SDWebImage](https://github.com/rs/SDWebImage) image downloader with cache support
* [Refresher](https://github.com/jcavar/refresher) 一个可以简单自定义刷新视图的下拉刷新组件