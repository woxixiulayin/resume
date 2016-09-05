###刘智刚
 - 求职意向：**前端开发（杭州）**
 -  联系方式：**13162101930**  /    **zhigang7536308@163.com**
 - github传送门：[https://github.com/woxixiulayin](https://github.com/woxixiulayin)
 - 工作年限：2年（安卓相关，目前离职转行前端）

----
####教育经历
> - 2011.9 - 2014.6  **东南大学**---------**机械电子** ---------------------------**硕士**
> - 2007.9 - 2011.6  **东南大学**---------**机械设计制造及其自动化**---------**本科**

----
####专业技能
> - 语言：**JS/HTML/CSS、C、Python、shell**
> - 前端框架：jQuery、vue
> - 前端工具：gulp、webpack
> - 版本管理： git
> - 开发环境：**linux、mac-os**

之前主要从事手机/电视等安卓系统底层相关工作，因为工作内容比较杂，基本都是改bug，不怎么写代码，感觉离软件开发的工作很远，遂萌生转行想法，业余时间学习前端。希望进入一家前端受重视的互联网公司学习，和公司一起成长。

---
####前端项目（个人）


######[vue做的flappy bird](http://keep-writing-codes.github.io/woxixiulayin/example/vflappybird/index.html)(vue、ES6) [http://keep-writing-codes.github.io/woxixiulayin/example/vflappybird/index.html](http://keep-writing-codes.github.io/woxixiulayin/example/vflappybird/index.html)
- 采用vue的模块化方式编写组件（src/componets/），各游戏组件比较清晰，容易修改;
- game.js采用event机制，是游戏的事件中心，提供事件操作函数，各组件内部监听游戏事件响应动作；
- store.js中统一维护公有state，集中管理，对外提供操作函数；
- world.js用于更新页面动画，组件通过world.listeners.add/remove注册监听函数，一旦添加监听就开始更新动画；
- [github传送门](https://github.com/woxixiulayin/vflappybird)

######[Dota直播信息导航](http://123.56.17.200:8083)(Node、koa、ES6、vue、gulp、webpack) [http://123.56.17.200:8083](http://123.56.17.200:8083)
- 一个直播信息爬取网站，开始用的jQuery，后来为了学习vue，前端部分用vue进行了重构
- 后端写了一个通用的spider类，各具体网站爬虫类用它作为原型，定制各自的爬虫策略，方便扩展为爬取其他类型的直播信息
- 利用promise，等所有异步爬取的数据完成后发送给前端
- 前端使用vue.js根据传过来的JSON数据更新页面
- [github传送门](https://github.com/woxixiulayin/vue-livedota)

######[拉勾网职位搜索](http://123.56.17.200:8082)(Node、koa、mongodb、jQuery、gulp) [http://123.56.17.200:8082](http://123.56.17.200:8082)
- 利用爬虫搜索拉勾网上的职位，显示各地区的职位数量
- 为了减少爬取次数，后端用mongodb存储查过的信息，如果所要查询的数据超过24小时没更新，则爬取新信息存储
- 将数据转成JSON发送给前端，用Echart生成饼图展示
- [github传送门](https://github.com/woxixiulayin/lagou_spider)

######[前端练手项目集合](http://keep-writing-codes.github.io/woxixiulayin/)(js/html/css, jQuery) [http://keep-writing-codes.github.io/woxixiulayin/](http://keep-writing-codes.github.io/woxixiulayin/)
- 刚开始学前端做的练手项目，依照[百度前端技术学院](http://ife.baidu.com/task/all)的题目边学边练
- [github传送门](https://github.com/keep-writing-codes/woxixiulayin)


######[百度贴吧爬虫](http://123.56.17.200:8081)(koa，bootstrap，gulp，react) [http://123.56.17.200:8081/](http://123.56.17.200:8081) 
- 基于Koa开发，套用bootstrap和react搭建页面
- 爬取指定贴吧上符合条件的帖子，集中展示，比如快速找出10业内回复量大于1000的热门帖子
- [github传送门](https://github.com/woxixiulayin/tiebadig_node)



----

####工作经历
##### 2016.1 - 2016.6  [微鲸科技有限公司](http://www.lagou.com/gongsi/103191.html)| BSP开发 | [系统软件开发工程师](http://www.whaley.cn/recruit/)
###### 智能电视行业搅局者(16年中国好声音赞助商) | 民营 | 互联网硬件创业公司 | 规模：500+人
- 公司主要做家庭娱乐产品，包括自主品牌的智能电视、音响、微投、VR设备
- 本人负责电视工厂测试软件从底层到应用层的开发维护、制定测试标准文档、测试软件的自动化
- 工作内容比较杂，需要处理安卓应用和底层、linux、上位机相关的内容，偶尔出差，出差期间需要迅速定位相关软硬问题。由于工作比较负责，积极推动生产问题按时解决，部门经理对我的工作还挺认可。

#####2014.7 - 2015.11 [上海华勤通讯技术有限公司](http://www.lagou.com/gongsi/27970.html) | 研发部门 | [驱动软件开发](http://job.huaqin.com/recruitment/index/jt/1/jt2/3)
######手机ODM行业前二 | 民营 | 规模：2000人
- 公司客户主要包括华为、联想、小米、亚马逊，其低端手机“外包”给我司开发
- 本人负责手机外设驱动调试、系统bug追踪、底层功能定制，如有需要会出差到工厂产线解决突发生产问题
- 15年负责亚马逊一款6寸[平板项目](https://www.amazon.cn/dp/B01GEW5890/ref=sa_menu_firetab_l2_kindle)，我作为驱动开发被外派到亚马逊北京总部工作6个月，期间与亚马逊工作人员对接（偶尔用英文沟通），接触到一线国际互联网公司专业的工作和开发流程
