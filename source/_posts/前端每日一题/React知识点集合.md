---
type: blog
title: React知识点集合
categories:
  - 前端
tags:
  - 面试题
  - React
abbrlink: 13437c1d
date: 2021-03-07
---

### React

- 什么时候使用状态管理器？
- render函数中return如果没有使用()会有什么问题？
- componentWillUpdate可以直接修改state的值吗？
- 说说你对React的渲染原理的理解
- 什么渲染劫持？
- React Intl是什么原理？
- 你有使用过React Intl吗？
- 怎么实现React组件的国际化呢？
- 说说Context有哪些属性？
- 怎么使用Context开发组件？
- 为什么React并不推荐我们优先考虑使用Context？
- 除了实例的属性可以获取Context外哪些地方还能直接获取Context呢？
- childContextTypes是什么？它有什么用？
- contextType是什么？它有什么用？
- Consumer向上找不到Provider的时候怎么办？
- 有使用过Consumer吗？
- 在React怎么使用Context？
- React15和16别支持IE几以上？
- 说说你对windowing的了解
- 举例说明React的插槽有哪些运用场景？
- 你有用过React的插槽(Portals)吗？怎么用？
- React的严格模式有什么用处？
- React如何进行代码拆分？拆分的原则是什么？
- React组件的构造函数有什么作用？
- React组件的构造函数是必须的吗？
- React中在哪捕获错误？
- React怎样引入svg的文件？
- 说说你对Relay的理解
- 在React中你有经常使用常量吗？
- 为什么说React中的props是只读的？
- 你有使用过formik库吗？说说它的优缺点
- 你有用过哪些React的表单库吗？说说它们的优缺点
- 如果组件的属性没有传值，那么它的默认值是什么？
- 可以使用TypeScript写React应用吗？怎么操作？
- `super()`和`super(props)`有什么区别？
- 你有使用过loadable组件吗？它帮我们解决了什么问题？
- 你有使用过suspense组件吗？它帮我们解决了什么问题？
- 怎样动态导入组件？
- 如何给非控组件设置默认的值？
- 怎么在React中引入其它的UI库，例如Bootstrap
- 怎样将事件传递给子组件？
- 怎样使用Hooks获取服务端数据？
- 使用Hooks要遵守哪些原则？
- render方法的原理你有了解吗？它返回的数据类型是什么？
- useEffect和useLayoutEffect有什么区别？
- 在React项目中你用过哪些动画的包？
- React必须使用JSX吗？
- 自定义组件时render是可选的吗？为什么？
- 需要把keys设置为全局唯一吗？
- 怎么定时更新一个组件？
- React根据不同的环境打包不同的域名？
- 使用webpack打包React项目，怎么减小生成的js大小？
- 在React中怎么使用async/await？
- 你阅读了几遍React的源码？都有哪些收获？你是怎么阅读的？
- 什么是React.forwardRef？它有什么作用？
- 写个例子说明什么是JSX的内联条件渲染
- 在React中怎么将参数传递给事件？
- React的事件和普通的HTML事件有什么不同？
- 在React中怎么阻止事件的默认行为？
- 你最喜欢React的哪一个特性（说一个就好）？
- 在React中什么时候使用箭头函数更方便呢？
- 你最不喜欢React的哪一个特性（说一个就好）？
- 说说你对React的reconciliation（一致化算法）的理解
- 使用PropTypes和Flow有什么区别？
- 怎样有条件地渲染组件？
- 在JSX中如何写注释？
- constructor和getInitialState有不同？
- 写例子说明React如何在JSX中实现for循环
- 为什么建议Fragment包裹元素？它的简写是什么？
- 你有用过React.Fragment吗？说说它有什么用途？
- 在React中你有遇到过安全问题吗？怎么解决？
- React中如何监听state的变化？
- React什么是有状态组件？
- React v15中怎么处理错误边界？
- React Fiber它的目的是解决什么问题？
- React为什么不要直接修改state？如果想修改怎么做？
- create-react-app有什么好处？
- 装饰器(Decorator)在React中有什么应用？
- 使用高阶组件(HOC)实现一个loading组件
- 如何用React实现滚动动画？
- 说出几点你认为的React最佳实践
- 你是如何划分React组件的？
- 举例说明如何在React创建一个事件
- 如何更新组件的状态？
- 怎样将多个组件嵌入到一个组件中？
- React的render中可以写{if else}这样的判断吗？
- React为什么要搞一个Hooks？
- React Hooks帮我们解决了哪些问题？
- 使用React的memo和forwardRef包装的组件为什么提示children类型不对？
- 有在项目中使用过Antd吗？说说它的好处
- 在React中如果去除生产环境上的sourcemap？
- 在React中怎么引用sass或less？
- 组件卸载前，加在DOM元素的监听事件和定时器要不要手动清除？为什么？
- 为什么标签里的for要写成htmlFor呢？
- 状态管理器解决了什么问题？什么时候用状态管理器？
- 状态管理器它精髓是什么？
- 函数式组件有没有生命周期？为什么？
- 在React中怎么引用第三方插件？比如说jQuery等
- React的触摸事件有哪几种？
- 路由切换时同一组件无法重新渲染的有什么方法可以解决？
- React16新特性有哪些？
- 你有用过哪些React的UI库？它们的优缺点分别是什么？
- `单击`和`单击`有什么区别？
- 在React中如何引入图片？哪种方式更好？
- 在React中怎么使用字体图标？
- React的应用如何打包发布？它的步骤是什么？
- ES6的语法'...'在React中有哪些应用？
- 如何封装一个React的全局公共组件？
- 在React中组件的props改变时更新组件的有哪些方法？
- immutable的原理是什么？
- 你对immutable有了解吗？它有什么作用？
- 如何提高组件的渲染效率呢？
- 在React中如何避免不必要的render？
- render在什么时候会被触发？
- 写出React动态改变class切换组件样式
- React中怎么操作虚拟DOM的Class属性？
- 为什么属性使用className而不是class呢？
- 请说下react组件更新的机制是什么？
- 怎么在JSX里属性可以被覆盖吗？覆盖的原则是什么？
- 怎么在JSX里使用自定义属性？
- 怎么防止HTML被转义？
- 经常用React，你知道React的核心思想是什么吗？
- 在React中我们怎么做静态类型检测？都有哪些方法可以做到？
- 在React中组件的state和setState有什么区别？
- React怎样跳过重新渲染？
- React怎么判断什么时候重新渲染组件呢？
- 什么是React的实例？函数式组件有没有实例？
- 在React中如何判断点击元素属于哪一个组件？
- 在React中组件和元素有什么区别？
- 在React中声明组件时组件名的第一个字母必须是大写吗？为什么？
- 举例说明什么是高阶组件(HOC)的反向继承？
- 有用过React Devtools吗？说说它的优缺点分别是什么？
- 举例说明什么是高阶组件(HOC)的属性代理？
- React的isMounted有什么作用？
- React组件命名推荐的方式是哪个？为什么不推荐使用displayName？
- React的displayName有什么作用？
- 说说你对React的组件命名规范的理解
- 说说你对React的项目结构的理解
- React16废弃了哪些生命周期？为什么？
- 怎样在React中开启生产模式？
- React中getInitialState方法的作用是什么？
- React中你知道creatClass的原理吗？
- React中验证props的目的是什么？
- React中你有使用过getDefaultProps吗？它有什么作用？
- React中你有使用过propType吗？它有什么作用？
- React中怎么检验props？
- React.createClass和extends Component的区别有哪些？
- 高阶组件(HOC)有哪些优点和缺点？
- 给组件设置很多属性时不想一个个去设置有什么办法可以解决这问题呢？
- React16跟之前的版本生命周期有哪些变化？
- 怎样实现React组件的记忆？原理是什么？
- 创建React动画有哪些方式？
- 为什么建议不要过渡使用Refs？
- 在React使用高阶组件(HOC)有遇到过哪些问题？如何解决？
- 在使用React过程中什么时候用高阶组件(HOC)？
- 说说React diff的原理是什么？
- React怎么提高列表渲染的性能？
- 使用ES6的class定义的组件不支持mixins了，那用什么可以替代呢？
- 为何说虚拟DOM会提高性能？
- React的性能优化在哪个生命周期？它优化的原理是什么？
- 你知道的React性能优化有哪些方法？
- 举例说明在React中怎么使用样式？
- React有哪几种方法来处理表单输入？
- 什么是浅层渲染？
- 你有做过React的单元测试吗？如果有，用的是哪些工具？怎么做的？
- 在React中什么是合成事件？有什么用？
- 使用React写一个todo应用，说说你的思路
- React16的reconciliation和commit分别是什么？
- React的函数式组件有没有生命周期？
- useState和this.state的区别是什么？
- 请说说什么是useImperativeHandle？
- 请说说什么是useReducer？
- 请说说什么是useRef？
- 请说说什么是useEffect？
- 举例说明useState
- 请说说什么是useState？为什么要使用useState？
- 请描述下你对React的新特性Hooks的理解？它有哪些应用场景？
- 说说你对Error Boundaries的理解
- 说说你对Fiber架构的理解
- 说说你是怎么理解React的业务组件和技术组件的？
- 为什么建议setState的第一个参数是callback而不是一个对象呢？
- 展示组件和容器组件有什么区别？
- Mern和Yeoman脚手架有什么区别？
- 你有在项目中使用过Yeoman脚手架吗？
- 你有在项目中使用过Mern脚手架吗？
- shouldComponentUpdate方法是做什么的？
- 怎样在React中使用innerHTML？
- 你有写过React的中间件插件吗？
- React的中间件机制是怎么样的？这种机制有什么作用？
- React中你用过哪些第三方的中间件？
- 不用脚手架，你会手动搭建React项目吗？
- 请说说React中Portal是什么？
- React中修改prop引发的生命周期有哪几个？
- React多个setState调用的原理是什么？
- React中调用setState会更新的生命周期有哪几个？
- React中setState的第二个参数作用是什么呢？
- React中的setState是同步还是异步的呢？为什么state并不一定会同步更新？
- React中的setState批量更新的过程是什么？
- React中的setState执行机制是什么呢？
- 在React中遍历的方法有哪些？它们有什么区别呢？
- 请说说你对React的render方法的理解
- props.children.map和js的map有什么区别？为什么优先选择React的？
- 有用过React的严格模式吗？
- React中的setState和replaceState的区别是什么？
- React中的setState缺点是什么呢？
- 有用过React的Fragment吗？它的运用场景是什么？
- React组件间共享数据方法有哪些？
- React的状态提升是什么？使用场景有哪些？
- 简单描述下你有做过哪些React项目？
- 在构造函数中调用super(props)的目的是什么？
- 你是如何学习React的？
- 从旧版本的React升级到新版本的React有做过吗？有遇到过什么坑？
- 你用过React版本有哪些？
- 有用过React的服务端渲染吗？怎么做的？
- React的mixins有什么作用？适用于什么场景？
- React怎么拿到组件对应的DOM元素？
- 请描述下事件在React中的处理方式是什么？
- JSX和HTML有什么区别？
- React的书写规范有哪些？
- create-react-app创建新运用怎么解决卡的问题？
- 使用React的方式有哪几种？
- 说说你对reader的context的理解
- 同时引用这三个库React.js、React-dom.js和babel.js它们都有什么作用？
- 你知道Virtual DOM的工作原理吗？
- 你阅读过React的源码吗？简要说下它的执行流程
- React中怎样阻止组件渲染？
- React非兄弟组件如何通信？
- React兄弟组件如何通信？
- React非父子组件如何通信？
- React父子组件如何通信？
- React组件间的通信有哪些？
- 类组件和函数式组件有什么区别？
- React自定义组件你写过吗？说说看都写过哪些？
- React组件的state和props两者有什么区别？
- React有几种构建组件的方式？可以写出来吗？
- React中遍历时为什么不用索引作为唯一的key值？
- React中的key有什么作用？
- React中除了在构造函数中绑定this,还有别的方式吗？
- 在React中页面重新加载时怎样保留数据？
- 请描述下React的事件机制
- 怎样在React中创建一个事件？
- 在React中无状态组件有什么运用场景？
- 描述下在React中无状态组件和有状态组件的区别是什么？
- 写一个React的高阶组件(HOC)并说明你对它的理解
- React中可以在render访问refs吗？为什么？
- React中refs的作用是什么？有哪些应用场景？
- 请描述你对纯函数的理解？
- 受控组件和非受控组件有什么区别？
- React中什么是非控组件？
- React中什么是受控组件？
- React中发起网络请求应该在哪个生命周期中进行？为什么？
- 说说React的生命周期有哪些？
- 说说你对“在React中，一切都是组件”的理解
- 写React你是用es6还是es5的语法？有什么区别？
- 浏览器为什么无法直接JSX？怎么解决呢？
- 在使用React过程中你都踩过哪些坑？你是怎么填坑的？
- 说说你喜欢React的原因是什么？它有什么优缺点？
- 如何解决引用类型在pureComponent下修改值的时候，页面不渲染的问题？
- createElement与cloneElement两者有什么区别？
- 解释下React中Element 和Component两者的区别是什么？
- 解释下React中component和pureComponent两者的区别是什么？
- React的虚拟DOM和vue的虚拟DOM有什么区别？
- 你觉得React上手快不快？它有哪些限制？
- 说说你对声明式编程的理解？
- React与angular、vue有什么区别？
- React是哪个公司开发的？
- React是什么？它的主要特点是什么？
- 简要描述下你知道的React工作原理是什么？
- 在React中怎样改变组件状态，以及状态改变的过程是什么？
- 在React中你是怎么进行状态管理的？
- React声明组件有哪几种方法，各有什么不同？

### ReactNative

- 如何在React Native中设置环境变量？
- 请描述下Code Push的原理是什么？
- React Native怎样查看日记？
- React Native怎样测试？
- React Native怎样调试？
- React Native和React有什么区别？
- 有做过React Native项目吗？

### React-Router

- React-Router怎么获取历史对象？
- React-Router怎么获取URL的参数？
- 在history模式中push和replace有什么区别？
- React-Router怎么设置重定向？
- React-Router 4中``组件有几种类型？
- React-Router 3和React-Router 4有什么变化？添加了什么好的特性？
- React-Router的实现原理是什么？
- React-Router 4的switch有什么用？
- React-Router的路由有几种模式？
- React-Router 4怎样在路由变化时重新渲染同一个组件？
- React-Router的``标签和``标签有什么区别？
- React的路由和普通路由有什么区别？
- 请你说说React的路由的优缺点？
- 请你说说React的路由是什么？

### Redux/Mobox

- 你有了解Rxjs是什么吗？它是做什么的？
- 在Redux中怎么发起网络请求？
- Redux怎样重置状态？
- Redux怎样设置初始状态？
- Context api可以取代Redux吗？为什么？
- 推荐在reducer中触发Action吗？为什么？
- Redux怎么添加新的中间件？
- redux-saga和redux-thunk有什么本质的区别？
- 在React中你是怎么对异步方案进行选型的？
- 你知道redux-saga的原理吗？
- 你有使用过redux-saga中间件吗？它是干什么的？
- Redux中异步action和同步action最大的区别是什么？
- Redux和vuex有什么区别？
- Redux的中间件是什么？你有用过哪些Redux的中间件？
- 说说Redux的实现流程
- Mobx的设计思想是什么？
- Redux由哪些组件构成？
- Mobx和Redux有什么区别？
- 在React项目中你是如何选择Redux和Mobx的？说说你的理解
- 你有在React中使用过Mobx吗？它的运用场景有哪些？
- Redux的thunk作用是什么？
- Redux的数据存储和本地储存有什么区别？
- 在Redux中，什么是reducer？它有什么作用？
- 举例说明怎么在Redux中定义action？
- 在Redux中，什么是action？
- 在Redux中，什么是store？
- 为什么Redux能做到局部渲染呢？
- 说说Redux的优缺点分别是什么？
- Redux和Flux的区别是什么？
- Redux它的三个原则是什么？
- 什么是单一数据源？
- 什么是Redux？说说你对Redux的理解？有哪些运用场景？

### Flux

- 请说说点击按钮触发到状态更改，数据的流向？
- 请描述下Flux的思想
- 什么是Flux？说说你对Flux的理解？有哪些运用场景？

### 面试题

https://www.cnblogs.com/dcyd/p/12989422.html

https://zhuanlan.zhihu.com/p/76909668

https://zhuanlan.zhihu.com/p/24856035

https://www.jianshu.com/p/84ce8d9f5391

https://www.cnblogs.com/zhuxinpeng-looking/p/11283015.html



### 更多题目

https://github.com/haizlin/fe-interview