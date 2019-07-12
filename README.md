# Vue仿今日头条App

---

### npm run dll (打包一次变不在需要打包了)
### npm run dev 本地开发
### npm run build 打包

**[在线预览地址, 或可通过 chrome 控制台手机模式观看](http://dzblog.cn/cases/vue-toutiao/index.html)**

> [segemntfault](https://segmentfault.com/a/1190000013153782?utm_source=index-newest)

> [博客地址](http://dzblog.cn/article/5a78609ec153997e3417a6d4)


	build: webpack配置
	config: 项目配置参数
	src
	assets: 静态资源文件，存放图片啥的
	components: 常用组件封装
	directive: 常用指令封装
	router: 路由表
	store: 状态管理 vuex
	styles: 样式文件
	utils: 常用工具类封装
	views: 视图页面
	static: 静态文件： 存放 favicon.ico 等等
	此项目用到了 DllPlugin 进行打包处理，所有启动该项目时记得，先执行一次该脚本命令生成配置