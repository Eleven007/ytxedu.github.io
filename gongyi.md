
# vue学习笔记
### vue定义
vue.js是一套构建用户界面的渐进式框架，与其他重量级框架不同是，Vue采用自底向上增量开发的设计。

### 声明式渲染
Vue.js的核心是一个允许采用简洁的模板语法来声明式将数据渲染进DOM系统

### 条件与循环
```vue
<div id="app">
  <p v-if="seen">现在你看到我了</p>
</div>
```
```javascript
var app=new vue({
  el:'#app',
  data:{
    seen:true
  }
})
```
