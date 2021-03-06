## XBlog
基于 [Beetlex.FastHttpApi](https://github.com/IKende/FastHttpApi) 框架构建的个人博客系统

## 技术要点
- 基于`dotnet core`平台，可以运行在windows和linux系统上
- 完全基于[`BeetleX.FastHttpAp`](https://github.com/IKende/FastHttpApi)框架开发
- 前后端分离，完全脱离后端视图引擎；基于vuejs和webapi模式 
- 混合HTTP和Websocket，当浏览器兼容Websocket的情况下请求会使用Websocket.
- 基于javascript前端Markdown,降低文章在服务端解释的损耗
- 支持HTTPS满足安全访问的需求
- javascript async/await
对访问的浏览器要求比较高，旧版本浏览器可能无法查看

### 在线案例
[https://www.ikende.com](https://www.ikende.com)

### 部署
[XBlog介绍和部署](https://www.ikende.com/blog/90.html)

![](https://i.imgur.com/AkHMDam.png)
![](https://i.imgur.com/K9MAypS.png)
![](https://i.imgur.com/1k4vgV8.png)
