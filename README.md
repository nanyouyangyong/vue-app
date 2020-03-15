### 基于vue2.0构建的在线电影网【film】，webpack + vue + vuex + vue-loader + keepAlive + muse-ui + cordova 全家桶，cordova 打包成APP

 
 

### 主要特色：

1. 组件化开发
2. 下拉刷新
3. 无限加载
4. 浏览历史
5. 响应式布局
6. 缓存数据
8. 收藏
9. 视频播放
10. md风格模式
11. 主题更换
12. 长按删除
13. 开发中...

### 目录结构
```
# web目录结构

├─build                 # build配置目录
├─config                # 相关配置
├─screenshot            # 屏幕截图
├─src                   # 项目源码主目录	
│  ├─assets             # 资源
│  │  └─less            # less通用文件目录
│  ├─components         # 页面及其组件
│  ├─router             # 路由
│  └─vuex               # vuex，其中包含了全局api，状态管理器
│      └─modules        # moduless
├─static                # 外部资源引入
│  ├─css                # 外部样式
│  │  ├─font            # 字体图标
│  │  └─woff            # 字体图标
│  └─js                 # 外部js	
└─test                  # 测试用，不用管这个
    ├─e2e
    │  ├─custom-assertions
    │  └─specs
    └─unit
        └─specs

```

> A Vue.js project

### 运行 

```
npm install

npm run dev

npm run build

```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

   
### License

[MIT](https://opensource.org/licenses/MIT)
