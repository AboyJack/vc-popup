# vc-popup [Demo](https://deepkolos.github.io/vc-popup/)

[![Build Status](https://travis-ci.org/deepkolos/vc-popup.svg?branch=master)](https://travis-ci.org/deepkolos/vc-popup)

> popup components 

# 特点

> 0. 支持`返回键`, 可以按浏览器返回按钮关闭popup
> 1. 可以写出小复杂的`过度动画`, 比如磁贴按压效果[在popUpMenu可看到~]
> 2. 支持css动画库, 比如animation.css, 使用的时候自行添加依赖就好了
> 3. 提供了几个比较好的popup组件, calendar, picker, imgViewer
> 4. `行为定义相对标准`, 这一点比较重要的, 前端行为定义犹如算法的输入定义一样, 比如触发关闭之后, 结束动画未结束之前, popup会拦截所有的输入事件, popup属于`不可交互状态`
> 5. 拓展也比较方便~
> 6. 差点忘说了, 强大的**定位支持**, 有`居中`, `clickRelative`, `domRelative`, 其中`domRelative` 支持25个位置

> `注:` 因为这是之前给一个组件库贡献的, 现在把`popup系列`提取出来, 部分组件从那个组件库中拿来, 比如example用到的`cell`, `group`, `buttom`, `picker-view`是我优化过的, 其余都是`自己写哒`~ 

> `popup-calendar`耗时4天, 3天建造, 1天完善~
 

## 预览

<div>
  <img src="https://raw.githubusercontent.com/deepkolos/vc-popup/master/static/popup-calendar.gif" width = "230" alt="图片名称" style="display:inline-block;"/>
  <img src="https://raw.githubusercontent.com/deepkolos/vc-popup/master/static/popup-picker.gif" width = "230" alt="图片名称" style="display:inline-block;"/>
  <img src="https://raw.githubusercontent.com/deepkolos/vc-popup/master/static/popup-img-viewer.gif" width = "230" alt="图片名称" style="display:inline-block;"/>
  <img src="https://raw.githubusercontent.com/deepkolos/vc-popup/master/static/domRelative-25-location.png" width = "230" alt="图片名称" style="display:inline-block;"/>
</div>

## 安装

``` bash
# install dependencies 正常
npm install || cnpm i --by=npm

# serve with hot reload at localhost:8080, 正常
npm run dev

# build for production with minification, 正常
npm run build

# build for production and view the bundle analyzer report 未测试
npm run build --report

# run unit tests, 有问题
npm run unit

# run all tests 未测试
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
