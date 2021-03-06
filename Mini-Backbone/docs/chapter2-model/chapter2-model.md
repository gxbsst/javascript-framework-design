## Let's build a Backbone!

**推荐资源：**   
官网： http://backbonejs.org/  
带源码注释： http://backbonejs.org/docs/backbone.html

当今前端框架百家争鸣，无论是现在三分天下的react、vue、angular，还是已经快无人提起的backbone，都是为了解决前端数据模型、业务模型不清晰、组件复用性、拓展性差等这些问题，而在多年以前的jquery时代，想让代码更有条理就必须依赖开发者的技术水准和职业素养。这些MVC\MVVM\Flux模式的出现让前端工程化达到了一个新的高度，其中backbone就是一个非常优秀的MVC框架。《Let's build a Backbone!》就是教你一步一步实现一个简易版的backbone，最终用这个backbone来实现一个todo应用，以至于让大家更加深入的了解MVC模式的运行原理。如下图：


![](http://7xl0rs.com1.z0.glb.clouddn.com/backbone.gif)

内容主要分为这几块：  

- 事件Events
- 模型Model
- 集合Collection
- 路由Router
- 视图View和视图template

？因为backbone是强依赖underscore以及jquery，所以一些utils或者helps是自己写还是直接用underscore

###chapter1 - Events
主要实现下面几个api:  

- on()
- off()
- triggle()
- listenTo()
- stopListening()

？lab: 实现一个观察者模式的案例

###chapter2 - Model
###chapter3 - Collection
###chapter4 - Router
###chapter5 - View + template
