[vue2问题记录](#vue2问题记录)

# vue2问题记录
**1. 启动vue项目过程中有的时候进度到了92%会卡顿一段时间，只需要在vue.config.js文件中把minimize的纸改为false即可**
- [x] *解决*
- 注意:在生产环境改回true
<img src='./assets/1.jpg' />

```javascript
optimization: {
   minimize: false
 }
```
