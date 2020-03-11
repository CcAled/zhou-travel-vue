# 运行方式
修改config/index.js下的端口号即可自定义端口号，使用npm run dev启动

# 使用的技术栈
Vue：Vue、Vue-router、Vuex、Vue-cli
插件：vue-awesome-swiper、better-scroll、axios
CSS：stylus

# 具体开发流程结构
## 首页
* iconfont的使用
* 图片轮播组件
* 图标区域轮播组件
* axios 获取数据
* 组件间数据传递
## 城市选择页
* 字母表布局
* better-scroll使用
* 函数节流实现列表性能优化
* 搜索逻辑的实现
* Vuex 实现数据共享
* localstorage 实现页面数据存储
* keep-alive 优化路由性能
## 详情页
* banner布局
* 动态路由配置
* 公用画廊组件独立化
* 递归组件实现详情列表
* transition slot 插槽实现 animation 简单动画效果
