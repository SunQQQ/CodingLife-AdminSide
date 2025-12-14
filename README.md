## 🎪 CodingLife.online
>此项目为码语人生（CodingLife Online）开源网站的管理后台源码，管理端体验地址为：https://codinglife.online/admin，用户端体验地址：https://codinglife.online

码语人生（CodingLife Online）是面向开发者的技术人文社区，记录代码背后的思考、分享技术人的成长故事，在代码中见人生。

网站管理端基于Vue2.0开发，使用媒体查询适配PC端和移动端，主要对网站做内容管理。管理后台对外开放，可快捷注册体验。且用户端与管理后台token互通，登录任何一端可实现两端通行。

网站分为[用户端](https://github.com/SunQQQ/CodingLife-UserSide)/管理后台/[服务端](https://github.com/SunQQQ/CodingLife-ServerSide)三套代码组成，此套代码为管理后台部分。管理后台使用ElementUI，并封装了token鉴权、登录注册等组件。网站整体架构如下：

![整体架构](https://i-blog.csdnimg.cn/direct/afa19d825a2b4871a8aece4c0f887768.png)

## 🔀 Branches

master (production)

├── v1.0 (老版本，技术栈为Vue+Node.js+MongoDB)

├── v2.0 (当前版本的测试环境)

## 🚀 Quick Start

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## 🌿 About Me
如果有吐槽或者建议、可在博客留言板联系我。也可通过添加微信13213074006，进入开发交流群，与众多同行分享代码与人生。

个人开源项目维护不易，跪求一个点赞✨ !，您的鼓励是俺不断更新的动力![fighting.png](https://res.wx.qq.com/mpres/htmledition/images/icon/emotion/100.gif)，
手动比心!

我还用原生JS写了一个贪吃蛇小游戏，欢迎来玩：https://codinglife.online/snake


## 🖥️ Website Preview
![TagList.png](https://github.com/SunQQQ/SunQBlog-AdminSide/blob/master/static/ReadMeImg/TagList.png)

![CreateArticle](https://github.com/SunQQQ/SunQBlog-AdminSide/blob/master/static/ReadMeImg/CreateArticle.png)

![EditHeartFelt](https://github.com/SunQQQ/SunQBlog-AdminSide/blob/master/static/ReadMeImg/EditHeartFelt.png)

![ArticleList](https://github.com/SunQQQ/SunQBlog-AdminSide/blob/master/static/ReadMeImg/ArticleList.jpg)

