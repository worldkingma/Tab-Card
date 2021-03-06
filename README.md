# Tab-Card类封装
- prototype
> 面向对象的基础就是基于原型链的继承。
- 配置参数（Tab组件基本配置参数讲解及扩展）
> 类的行为是可控的，可预期的，但也是可以默认的。
- 对象（操作对象获取、事件绑定、交互功能函数实现）
    - 根据参数绑定不同的事件、交互行为
> JS中万物皆对象。
# 前置知识点
- 具备原生JS编程能力（运用面向过程的方式写一下Tab）
- 有一定的JS OOP（对象化编程）思想
    - 了解类的封装方式，工厂模式下、原型模式（prototype）、混合模式（原型+构造函数）...
    - This、Prototype、New等关键词意义。构造函数、继承、闭包等概念的意义...

-----

封装一个tab需要注意的点：
1. 一个配置对象需要一个配置参数，（当使用一个类时，不会去关注内部的代码是如何编写的，而是想通过配置参数的形式去改变一下最终需要的展示行为）
2. 一个页面也许会有许多相同的组件，那么这些组件势必要通过人工来给它一个配置参数去展示不同的交互行为和展示效果，那么一个通过面向对象的方式开发出来的组件配置参数是必不可少的这是其一，这个对象就是把一个页面里面要出现的多个组件，把相同的对象形式抽象出来，给他封装在一个类里面，无非就是在这个对象里面去获取一些参数。