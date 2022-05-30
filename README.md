# Vue.js

什么是vue.js?

*vue.js允许您使用称为指令的属性扩展HTML

vue.js指令为HTML应用程序提供功能
vue.js提供内置指令和用户定义指令


vue.js指令
Vue.js使用双括号{{}}作为数据的占位符。
Vue.js是带有前缀的HTML属性v-

Vue示例
在下面的示例中，使用new Vue()创建一个（新的Vue对象）

属性el：将（新的Vue对象）绑定到id="app"的HTML元素。
<!DOCTYPE html>
<html>
<script>
  src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js">
 </script>
<body>
<div id="app">
  <h1>{{message}}</h1>
 </div>
 
<script>
  var myObject = new Vue(
  {
  el:"#app",
  data:{message:'Hello Vue!'}
  }
  )
</script>
  </body
  </html>
  
  输出：Hello Vue!
  
  
  once more:
  
  <!DOCTYPE html>
  <html>
    <script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"><script>
      <body>
        <div id="app">
          <h1>{{message}}</h1>
          </h1>
        <script>
          var myObject=new Vue({
          el:"#app",    //el属性将将新的VUE对象绑定到HTML元素上
          data:{message: 'Hello Vue!'}
          })
        </script>
      </body>
      </html>
      
      
      <!DOCTYPE html>
<html>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
<body>

<div id="app">
  <h1>{{ message }}</h1>
</div>

<div id="ap">
  <h1>{{ message2 }}</h1>
</div>

<script>
var myObject = new Vue({
  el: '#app',
  data: {message: 'Hello Vue!'}
})
</script>

<script>
var myObject = new Vue({
  el: '#ap',
  data: {message2: 'Hello again Vue!'}
})
</script>


</body>
</html>
      
输出：
Hello Vue!
Hello again Vue!
  
      Vue.js双向绑定：
      
      Vue.js循环绑定：
