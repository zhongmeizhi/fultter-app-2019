# 蘑菇碳的Flutter金融理财App

> 一个功能完整齐全的Bloc模式 SPA型 Flutter App项目。

>> 项目大部分都使用Flutter原生API来完成。使用少量原生插件。喜欢请Star，尽量别 Fork。

### 项目预览
|![1](/preview/1.png)|![2](/preview/2.png)|![3](/preview/3.png)|![4](/preview/4.png)|
|:--:|:--:|:--:|:--:|
![5](/preview/5.png)|![6](/preview/6.png)|![7](/preview/7.png)|![8](/preview/8.png)|
|![9](/preview/9.png)|![update](/preview/update.gif)|![search](/preview/search.gif)|![reorder](/preview/reorder.gif)|
![0](/preview/0.png)|


### 项目计划
* [x] ZFit 屏幕适配
* [x] RouteSetting + 路由数据回传
* [x] 自定义App桌面 图标 + 名称
* [x] 无限轮播图
* [x] EventBus
* [x] koa2 + node 后台服务器
* [x] 封装请求
* [x] Storage 保持登录状态
* [x] 解决页面切换重绘问题
* [x] webview
* [x] 下拉刷新 + 上拉加载
* [x] keepa-live && 缓存Widget
* [x] 搜索功能
* [x] App强制更新
* [x] 局部路由
* [x] 拖动式排序
* [x] 页面侧滑回退
* [x] BLoC模式 实现状态管理
* [x] 一键换肤
* [x] 重写Flutter部分类
* [x] 全局Toast + 全局 Dialog
* [x] 实现 SPA (单页面应用)
* [ ] Bloc模式完善
* [ ] node架构完善



### 目录结构

主目录：
* assets：静态文件
* back-end：mock数据


lib目录：
* config：配置文件
* domain：实体类
* bloc：逻辑模块
* page：页面
* plugin：独立组件/插件
* routes：路由
* service：接口封装 + API地址
* styles: 常用样式类
* utils：工具类
* view：可复用Widget


### Node 后台：
1. 安装`node.js`
2. cd 到项目`back-end`目录下
3. 控制台运行`npm i`
4. 控制台运行`node server.js`
5. 启动服务端成功
6. 记得修改`config`文件下的 baseUrl

附： 如果是本地调试，baseUrl请使用`IP + 端口`


<details>
<summary>End 附：</summary>

* BLoC模式
* 不使用setState就能刷新页面
* 在多个页面中共享状态。

</details>


[Flutter API文档](https://flutter.io/docs/get-started/codelab)
