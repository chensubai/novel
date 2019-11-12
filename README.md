# 小说精品屋

#### 背景介绍
小说精品屋是一个功能完善的小说弹幕网站，包含精品小说专区和轻小说专区。包括小说分类、小说搜索、小说排行、完本小说、小说评分、小说在线阅读、小说书架、阅读记录、小说下载、小说弹幕、小说自动爬取、小说内容自动分享到微博、邮件自动推广、链接自动推送到百度搜索引擎等功能。包含电脑端、移动端、微信小程序等多个平台，现已开源web端、安卓端、小程序端源码，大家可以用于学习或者商用。

该项目来源于个人真实运营项目，因为没去做SEO，所以用户注册量不大，但是依然有一批用户一直都在支持着，自己也没去接入广告赚钱，因为这样网站的体验就差了。自己已经没有太大精力运营下去了，所以就把源码开源一下，把机会留给有兴趣搞小说网站的朋友们。只要你的硬盘足够大，爬虫程序理论上是可以无限制地爬取网络小说的，大家可以根据自己的需求去修改，有什么问题或者好的有趣的需求也可以和我提，有时间我还是会继续维护这份源码的。大家可以根据自己是想真实运营还是学习的需求去使用爬虫程序吧，如果只是想演示一下的话，运行爬虫程序几分钟数据就足够了 。

#### 软件架构
Springboot+Mybatis+Mysql+Ehcache+Thymeleaf+Layui


#### 安装教程

1. 数据准备，拉取小说爬虫程序，按照说明文件爬取网络小说到数据库中。（[点击获取爬虫程序](https://gitee.com/xiongxyang/crawl-book)）

2. 修改项目application.yml配置文件中的数据库配置。

   ![](./assets/database_config.png)

3. 修改项目application.yml配置文件中的首页本站推荐小说配置（修改的小说需要在数据库中存在）。

   ![](./assets/index_config.png)

4. 根据需求，修改项目application.yml配置文件中的爬取小说最低分配置。

   ![](./assets/score_config.png)

5. 本地直接运行或使用maven插件打包成jar文件上传到服务器上。

6. `http://ip:port`访问首页。

7. `http://ip:port/books`访问精品小说模块。

8. `http://ip:port/book/searchSoftBook.html`访问轻小说模块。

#### 项目截图

1. 电脑端（首页）

   ![index](./assets/精品小说楼.png)

2. 移动端（首页）

   ![index](./assets/QQ图片20191018162208.jpg)

3. 移动端（轻小说专区）

   ![index](./assets/QQ图片20191018161330.jpg)

4. 移动端（小说详情页）

   ![微信图片_20190904181558](./assets/微信图片_20190904181558.png)

   

5. 移动端（目录页）

   ![QQ图片20191018161901](./assets/QQ图片20191108022250.png)

6. 移动端（小说阅读页）

   ![QQ图片20191018161901](./assets/QQ图片20191018161901.png)

7. 小程序

![mini4](./assets/mini4.png)

##### 演示地址1

[点击前往](https://www.zinglizingli.xyz)

##### 演示地址2（备用）

[点击前往](http://47.106.243.172)

#### 小程序二维码

![mini-code](./assets/mini-code.png)

#### 代码仓库

 Gitee仓库地址：  https://gitee.com/xiongxyang/fiction_house 

 GitHub仓库地址：  https://github.com/201206030/fiction_house 

#### QQ交流群

![mini-code](./assets/小说精品屋开源项目交流群群聊二维码.png)

#### 捐赠支持

开源项目不易，若此项目能得到你的青睐，可以捐赠支持作者持续开发与维护。 

![mini-code](./assets/jk.png)

##### 捐赠名单 

| 捐赠者 | 金额     | 时间                        |
| ------ | -------- | --------------------------- |
| **海   | ￥ 15.00 | 2019年11月11日 上午7点45分  |
| *鹏飞  | ￥5.00   | 2019年11月11日 上午0点14分  |
| *沐    | ￥10.00  | 2019年11月10日 上午12点09分 |



