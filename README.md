# 使用css实现五星评分的效果

## 效果图

![效果图](https://user-gold-cdn.xitu.io/2019/8/17/16c9d924566238de?imageslim)

## Demo

[https://github.com/jiaoshibo/css-rate](https://github.com/jiaoshibo/css-rate)

## 原理

1. 找一个好看的 `iconfont` ，比如[阿里巴巴矢量图标库](https://www.iconfont.cn/)
2. 借用5个 `radio` 单选框，把默认样式去掉，默认显示星星
3. 用 `checked` 伪类监听用户选中，由默认的星星变成高亮的星星
4. 然后配合 `~` 操作符把当前选中的所有兄弟元素一起高亮
5. 把5个 `radio` 单选框反向排列