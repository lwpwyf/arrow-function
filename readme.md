## 怎么用
只有一个参数时，可以省略（）
只有一条语句的时候 可以省略{} return

## 注意
参数箭头之间不能换行
返回一个对象时候

## arguments
- 所有函数里面都可以用的变量
- [arg1,arg2,arg3]

## 区别
- 箭头函数不支持重复的名字的形参,普通函数可以
- 箭头函数不能使用call apply等方法改变 this
- 箭头函数没有 this 它的this指向定义时所处的上下文(外部函数)的this
- 箭头函数没有原型对象 .prototype
- 箭头函数不能作为构造函数
- 箭头函数没有arguments 如果嵌套进普通函数，则可调用普通函数的上下文环境中的argument


## new target
- es6 引进的 返回的 new作用的那个构造函数(构造函数之中)
