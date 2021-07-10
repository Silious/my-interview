#### JS

1. 数组的扁平化

   https://juejin.cn/post/6844903870640963592

2. Es6,7,8的新特性

   [1.5万字概括ES6全部特性(已更新ES2020)](https://juejin.cn/post/6844903959283367950#heading-26)

   https://zhuanlan.zhihu.com/p/67492465?utm_source=wechat_timeline&utm_medium=social&utm_oi=776348517688946688&from=timeline

3. js的数据类型,数据类型检测,优缺点   typeof null=='object',通过tostring判断的原理是什么

4. 为什么string作为基本类型,通过Object.prototype.toString.call获取的结果是"[object String]"

5. js继承有哪些方式    es6和es5的继承的区别

   https://mp.weixin.qq.com/s?__biz=MzAxODE2MjM1MA==&mid=2651554700&idx=1&sn=fc906e8518d3109de124723adb8a8d08&chksm=8025544db752dd5baf0b44d8561ce06d76f74746640a71e19239ef236e87c5028088f1a4ad34&scene=0#rd

   https://www.cnblogs.com/ranyonsue/p/11201730.html

6. class的实现原理

   https://blog.csdn.net/qq_40968685/article/details/114642909

7. 数组的哪些遍历方法可中断

   https://blog.csdn.net/weixin_34228387/article/details/88024376

   https://blog.csdn.net/sinat_35538827/article/details/98896138

8. 字符串反转

   https://www.cnblogs.com/hcxwd/p/9350604.html

9. 原型链和原型对象

10. 闭包

    [说说闭包](https://github.com/LuckyWinty/fe-weekly-questions/issues/71)

11. 事件冒泡  事件捕捉,哪个先  

12. 事件委托

13. 代码执行过程中的内存分配

    [理解JavaScript 中的执行上下文和执行栈](https://muyiy.vip/blog/1/1.1.html)

    [JavaScript深入之执行上下文栈和变量对象](https://muyiy.vip/blog/1/1.2.html#%E6%89%A7%E8%A1%8C%E4%B8%8A%E4%B8%8B%E6%96%87)

    [JavaScript深入之内存空间详细图解](https://muyiy.vip/blog/1/1.3.html)

    [JavaScript深入之带你走进内存机制](https://muyiy.vip/blog/1/1.4.html)

14. 进程和线程的区别

15. 数组遍历的方式   findIndex找不到返回-1    find  找不到返回undefined 

16. 实现一个深拷贝  JSON.parse的缺点 怎么处理深拷贝的循环引用问题

17. foreach和map的区别  返回值?

18. 箭头函数和bind(this)的区别,哪个性能好?为什么

19. this绑定方式,区别?

20. 数组哪些循环是可以中断的

21. 数组去重  除了new set ,遍历还有什么其他方式

    https://mp.weixin.qq.com/s/4cWE55z950f2_cpcrTL9eg

22. new Set()转数组有哪些方式

    https://blog.csdn.net/qq_41813695/article/details/84582766

23. 深浅拷贝分别怎么实现   浅拷贝除了扩展运算符还有其他什么方式   JSON.parse(JSON.stringify())对函数,日期等类型的处理结果  undefined还是会忽略掉?

    https://muyiy.cn/blog/4/4.1.html

    忽略

24. setTimeout 0为什么会有延迟

    宏任务   https://www.webhek.com/post/settimeout-sleep-0-second.html

25. 声明一个对象时,怎么让它的某个属性为只读 object.defineProperty

26. const  let  var的区别

27. 怎么解决js大数字精度丢失问题

    https://blog.csdn.net/qq_35271556/article/details/80137474

28. js大数相加怎么实现

    https://blog.csdn.net/weixin_45727472/article/details/117305306

    https://www.cnblogs.com/vickylinj/p/14437786.html

29. 讲下事件冒泡

30. 实现缓存函数memorize

    https://segmentfault.com/a/1190000012505900

31. 说说函数柯里化

32. 拷贝数组有哪些方式

33. JSON.parse JSON.stringify的缺陷

    > 1、会忽略 `undefined`
    >
    > 2、会忽略 `symbol`
    >
    > 3、不能序列化函数
    >
    > 4、不能解决循环引用的对象
    >
    > 5、不能正确处理`new Date()`
    >
    > 6、不能处理正则

34. 实现Promise.all

    https://juejin.cn/post/6844904064820461576

35. Promise.all 遇到异常最后返回结果是什么

    https://blog.csdn.net/Elanenrich123/article/details/88410933

36. Promise有几种状态

    > 1.初始化，状态：pending
    >
    > 2.当调用resolve(成功)，状态：pengding=>fulfilled
    >
    > 3.当调用reject(失败)，状态：pending=>rejected

37. Map,Set了解么,怎么用

38. 箭头函数和普通函数的区别

39. forEach map的区别

40. 说说Promise.all   race  allsettled  怎么实现promise.allsettled   怎么捕获异常

    [Promise.allSettled 的作用，如何自己实现 Promise.allSettled](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/480)

41. 实现promise,then,catch

42. 说说aysc  await

43. 怎么实现深拷贝

44. 说说eventLoop    宏任务和微任务的区别

    https://mp.weixin.qq.com/s/qhkQtRFmgfc7Mx0e1nROcw

45. setTimeout和Promise的执行优先级

46. compose了解么

    https://blog.csdn.net/zxl1990_ok/article/details/90049466

47. 为什么js中函数是一等公民

    https://www.cnblogs.com/fundebug/p/javascript-first-class-function.html

    https://www.cnblogs.com/xiaoxiaokun/p/7090902.html

48. 数组打断顺序  去重  扁平化,  不清楚数组层级时用flat去重传什么参数

49. 说说模块化的历史 说说CMD和AMD

    [前端模块化发展史](https://www.jianshu.com/p/6332cb0f3d7f)

50. 执行多个promise,按顺序输出对应的结果

51. this绑定有哪些

    https://muyiy.cn/blog/3/3.1.html

52. 实时显示日期时间并格式化

53. 有一个li列表,实现点击打印出当前点击的li序号

54. 深浅拷贝的特点

55. 项目中用到哪些设计模式   观察者模式和发布订阅模式的区别

    https://juejin.cn/post/6844904032826294286#heading-76

    https://zhuanlan.zhihu.com/p/51357583

56. 正则:去掉字符串的前后空格     匹配千分位

    https://tool.oschina.net/uploads/apidocs/jquery/regexp.html

57. trim的作用

58. 分片上传,断点续传怎么做的

    https://juejin.cn/post/6844903860327186445#heading-8

59. class继承的原理

    https://www.cnblogs.com/memphis-f/p/12029574.html

60. 为什么会有暂时性死区

61. 实现防抖函数

62. 函数预加载了解么

63. 一个函数直接return this和return一个对象的区别

64. 怎么创建公有属性,私有属性

65. es5和es6的作用域有什么区别

66. 类的构造函数的作用

67. 怎么获取Array.prototype上的方法集合

68. 数组有哪些方法,怎么往数组头部插入一个元素

69. 什么对象没有prototype属性

70. async await怎么捕获异常

71. 实现recude,map

72. 怎么实现axios的接口超时   用promise.race实现

73. 正则匹配url中的参数(手写题)

74. 怎么实现lodash的分组方法

75. es5,es6监听属性的方式分别是什么

76. arguments和形参的区别,形参是什么时候生成的

#### CSS

1. Positon有哪些,三个不同定位,同样大小的div在页面上的效果,层级?

2. CSS3新特性

3. HTML5新特性

4. 一个页面分左侧菜单,头部,内容区域,具体每块css怎么写

5. 清除浮动有哪些办法

6. 重绘和回流,如何避免

   https://developers.google.com/web/fundamentals/performance/critical-rendering-path/

   [如何理解回流和重绘](https://github.com/LuckyWinty/fe-weekly-questions/issues/13)

7. BFC了解么,有什么作用,用来解决什么问题,除了BFC之外,还有哪些布局

   https://mp.weixin.qq.com/s?__biz=MzUyNDYxNDAyMg==&mid=2247484371&idx=1&sn=36f7e8e71c8deaea482b0d28a5ffb882&chksm=fa2be33acd5c6a2c8b83729c196a3488ea48f2702c0032b5bde6d371f6cb836e87e48cccd6e7&mpshare=1&scene=1&srcid=&key=c333a3898be7f86f50b0cbf7cd0288e5a6dbd34eb78a4dff9c5033fb550c242d85448e60a686012d5d51e0745a7dc5e07a3d565c1589f48f46c8b8fabf68e2f65ee569f0defaacfd94f7f8090c139713&ascene=14&uin=MTYxNDYxMzg4&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=jsgDdvHxcrj0G7BrQGjvAnhF6%2FwjUM%2FgqYs21GA3jAc%3D

   [说一下你对CSS 中的 BFC的理解](https://github.com/LuckyWinty/fe-weekly-questions/issues/36)

   [介绍下 BFC、IFC、GFC 和 FFC](https://github.com/LuckyWinty/fe-weekly-questions/issues/83)

8. 水平垂直居中

   https://juejin.cn/post/6844903799446831117

9. 实现双飞翼布局

   https://blog.csdn.net/qq_38128179/article/details/86542447

10. 实现圣杯布局

   https://mp.weixin.qq.com/s/3A1j8ah3CXC3g1BcUy85sw

11. css实现右箭头

12. 3个div水平等比例排列

13. 不定宽高的div水平垂直居中

    https://juejin.cn/post/6844903799446831117

14. css选择器的类型,权重,优先级

    https://juejin.cn/post/6844903894313598989#heading-6

15. cssModule是什么

    http://www.ruanyifeng.com/blog/2016/06/css_modules.html

    https://segmentfault.com/a/1190000014686771

    https://juejin.cn/post/6844903665485119496#heading-11

16. position定位有哪些

    https://juejin.cn/post/6844903894313598989#heading-24

17. a标签有哪几种伪类

18. less里边mixin和function的用法,区别

    https://blog.csdn.net/weixin_34146986/article/details/91430581

19. z-index高的元素反而显示在底下,可能是什么原因

20. css层叠上下文了解么

    [层叠上下文](https://juejin.cn/post/6941206439624966152#heading-22)

21. css盒模型

22. margin-top和tranform:tranlate的区别

23. 绝对定位不设置top等属性是什么效果

24. transform位移和position定位位置有什么区别,性能差异表现在哪里,为什么

    [translate和position的比较](https://www.cnblogs.com/shytong/p/5654142.html)

    [浅谈translate属性与相对定位、绝对定位的区别](https://blog.csdn.net/zhouziyu2011/article/details/71436509)

25. 实现位移动画有哪些方式,css,js

26. Css硬件加速有哪些属性

     [CSS动画原理及硬件加速](https://www.cnblogs.com/shytong/p/5419565.html)

27. 行内块级元素有哪些

    [块级元素，行内元素，行内块级元素都有哪些](https://www.cnblogs.com/zmshare/p/6648038.html)

28. css,多行超出显示点点点

    [CSS多行文字超出隐藏加省略号](https://ailongmiao.com/read/120.html)

29. css动画有哪些

    [css3动画属性有哪些](https://www.cnblogs.com/longhuacong/p/12389422.html)

    [说说你对CSS动画的理解](https://github.com/LuckyWinty/fe-weekly-questions/issues/60)

30. rem和em的区别

31. 获取标签元素中的文本有哪些方式

32. 暗黑模式怎么实现

    [H5 项目如何适配暗黑模式](https://mp.weixin.qq.com/s/Iwuk2z73FB3Zj3cFZC37tA)

33. 主题切换怎么实现

34. 隐藏元素有哪些方式?区别?

    [说说visibility=hidden, opacity=0，display:none的区别](https://github.com/LuckyWinty/fe-weekly-questions/issues/64)

    

#### REACT

1. useRef

   https://zh-hans.reactjs.org/docs/hooks-reference.html#useref

2. 有没有写过自定义hook

   https://zh-hans.reactjs.org/docs/hooks-custom.html

3. useContext

   https://zh-hans.reactjs.org/docs/hooks-reference.html#usecontext

4. hooks组件和高阶组件的区别

   https://github.com/LinDaiDai/niubility-coding-js/blob/master/%E6%A1%86%E6%9E%B6-%E5%BA%93/React/HOC%E7%9C%9F%E7%9A%84%E5%B0%B1%E9%82%A3%E4%B9%88%E9%AB%98%E7%BA%A7%E5%90%97.md

5. 用的react版本

   > 16,17

6. react18有哪些新特性

   https://mp.weixin.qq.com/s/FQV9qfSJxzwcGzjbTnEZiA

7. react17和16的区别

   https://www.w3cschool.cn/article/73903cd7e547af.html

8. react和vue的区别,为什么选react

9. useRef用过么，useCallback有什么用，原理分别是什么，有什么区别

10. react中key的作用,不写会怎样,key可以写索引吗

    [写 React / Vue 项目时为什么要在列表组件中写 key，其作用是什么](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)

    [深入解析为什么 key 是必须的](https://zh-hans.reactjs.org/docs/reconciliation.html#recursing-on-children)

11. react的数据绑定怎么实现的

    https://www.cnblogs.com/wzy0526/p/9361228.html

     https://blog.csdn.net/csdnzlcheng/article/details/102373133

12. 怎么处理浅比较导致不渲染的问题

13. Fiber的中断更新机制具体在什么场景下有用到

    https://blog.csdn.net/qq_41903941/article/details/115216864

14. 高阶组件的实现方式

15. setState什么时候异步 什么时候同步

    https://kaiwu.lagou.com/course/courseInfo.htm?courseId=566#/detail/pc?id=5796

16. 说下虚拟dom

    https://kaiwu.lagou.com/course/courseInfo.htm?courseId=566#/detail/pc?id=5799

    https://mp.weixin.qq.com/s/oAlVmZ4Hbt2VhOwFEkNEhw

    https://mp.weixin.qq.com/s/_jAW4Z3VR-uW0AEnjHgAEw

17. 什么时候会触发组件重新render ?  State  props   context  forceupdate

    https://blog.csdn.net/qq_36461153/article/details/106566369

    https://cloud.tencent.com/developer/article/1549644

18. react组件怎么减少重复渲染

    https://kaiwu.lagou.com/course/courseInfo.htm?courseId=566#/detail/pc?id=5804

19. react自带高阶组件有哪些

    https://github.com/LinDaiDai/niubility-coding-js/blob/master/%E6%A1%86%E6%9E%B6-%E5%BA%93/React/HOC%E7%9C%9F%E7%9A%84%E5%B0%B1%E9%82%A3%E4%B9%88%E9%AB%98%E7%BA%A7%E5%90%97.md

20. react高阶组件和hooks组件有什么区别

    https://juejin.cn/post/6844903993072697352#heading-6

21. 说说react类组件的生命周期

22. 什么情况下会触发useEffect return执行

23. hooks的执行顺序是存在什么地方的

    https://zh-hans.reactjs.org/docs/hooks-faq.html#how-does-react-associate-hook-calls-with-components

24. constructor中super(props)的作用

25. 不在同一个父元素内的2个兄弟元素怎么通信,除了context和第3方状态库呢

26. react怎么做keep-alive

    https://mp.weixin.qq.com/s?__biz=MzkwODIwMDY2OQ==&mid=2247488224&idx=1&sn=780a585cea8507c4922de895be16bd60&source=41#wechat_redirect

    https://www.npmjs.com/package/react-keepalive-router

27. 常用哪些hooks,useEffect,useMemo,useCallback的区别

28. useEffect的第2个参数用来做什么的

29. React.memo怎么用

30. 类组件和函数组件的区别

31. Fiber和之前的diff的区别  Fiber的中断更新用在哪些场景

    https://www.cnblogs.com/qianxiaox/p/14120253.html

    https://www.cnblogs.com/leslie1943/articles/13845114.html

32. react的key的作用,为什么需要key,key为什么不能用index

33. setState同步,异步

34. diff原理   diff具体的比较方式有哪些

    https://blog.csdn.net/qq_43958325/article/details/112315992

    [详解 React 16 的 Diff 策略](https://mp.weixin.qq.com/s/_jAW4Z3VR-uW0AEnjHgAEw)

35. react类组件的生命周期,hooks怎么实现didMount

36. useMemo中能写异步么

37. useEffectLayout中可以获取到dom节点吗

    https://www.jianshu.com/p/5a753e853a19

    https://blog.csdn.net/weixin_45389051/article/details/107701405

38. hooks中多个setState是统一一次更新还是更新多次,有什么办法改成只更新一次

    https://blog.csdn.net/weixin_45416217/article/details/103294738

39. 类组件中有什么办法可以在render前获取到dom节点

    https://blog.csdn.net/dx18520548758/article/details/103855364

40. 要在页面渲染前请求接口获取数据的话,请求应该写在哪

41. willMount中可以写接口请求吗  有什么缺点

    https://mp.weixin.qq.com/s/J0UxE5JKftkpWXcioQAmSQ异步请求可能被触发多次

    https://www.zhihu.com/question/304373773/answer/543646001

    https://www.cnblogs.com/yinhao-jack/p/10571414.html

    > 在React中使用componentWillMount或componentDidMount生命周期函数进行异步请求**实际上，componentDidMount由于两个原因，这是发出调用以获取数据的最佳位置：使用DidMount可以清楚地表明，只有在初始渲染之后才会加载数据。这提醒您正确设置初始状态，以免最终undefined导致出现错误的状态。如果您需要在服务器上呈现您的应用程序，componentWillMount则实际上会被调用两次-一次在服务器上，再一次在客户端上-这可能不是您想要的。放入数据加载代码 componentDidMount将确保仅从客户端获取数据。总结一下不建议在constructor和componentWillMount里写的原因是会阻碍组件的实例化，阻碍组件的渲染如果用setState，在componentWillMount里面触发setState不会重新渲染

42. 说说你觉得react不好用的地方

43. react生命周期方法16版本前后的区别,17版本增加了哪些新特性

    https://mp.weixin.qq.com/s/J0UxE5JKftkpWXcioQAmSQ

44. hooks怎么模拟类组件的生命周期

45. 自定义hooks你们一般怎么用  有用过什么第三方自定义hooks插件么

    https://zh-hans.reactjs.org/docs/hooks-custom.html

    https://blog.csdn.net/weixin_43154931/article/details/105668373

46. 为什么会出现Hooks,相比于类组件的优点,什么场景需要用到Hooks

    https://zh-hans.reactjs.org/docs/hooks-intro.html

    https://mp.weixin.qq.com/s/fF-H3Lr0aP3Ld8jfJrrwQg

47. 类组件和函数组件平时主要用什么

48. hooks为什么不能用在条件循环语句中,有什么办法可以打破这个规则

    https://zh-hans.reactjs.org/docs/hooks-rules.html#explanation

    > 不要在循环，条件或嵌套函数中调用Hook，必须始终在React函数的顶层使用Hook。这是因为React需要利用调用顺序来正确更新相应的状态，以及调用相应的钩子函数。一旦在循环或条件分支语句中调用Hook，就容易导致调用顺序的不一致性，从而产生难以预料到的后果，useRef  存储赋值，可以避免

49. 怎么处理hooks中的闭包问题

    https://mp.weixin.qq.com/s/tl2fhCdU0efaN2j2V1VINQ

50. react高阶组件对应js里哪个特性

    > 高阶函数

51. 实现避免重复请求hook

52. 为什么react16要抛弃willMount,willReceiveProps等生命周期

    > 重复执行

53. 为什么getDerivedStatefromprops是静态方法

    > 导致你无法咋在这个方法内做this.fetch、不合理的this.setState，这类副作用的操作。
    >
    > 意在确保生命周期函数的行为更加可控可预测，从根源上帮开发者避免不合理的编程方式，避免生命周期的滥用

54. Hooks的原理

    [React Hooks 原理与最佳实践](https://mp.weixin.qq.com/s/DS2OjlwWjClboDIgLFuG6A)

55. 项目中有哪些可以封装成自定义hooks

56. 说说react的时间调度

57. useEffect依赖空数组和didMount的区别

    > 对于 `useEffect` 来说，执行的时机是完成所有的 DOM 变更并让浏览器渲染页面后，而 `useLayoutEffect` 和 class 组件中 `componentDidMount`, `componentDidUpdate`一致——在 React 完成 DOM 更新后马上同步调用，会阻塞页面渲染。

58. Fiber的中断更新是怎么实现的,怎么判断任务优先级

59. Hooks里边定时器生成,销毁你怎么写,定时器存到哪

60. react和vue怎么选型

    [React还是Vue：你该如何选择](https://blog.csdn.net/u013291076/article/details/53885604)



#### TypeScript

1. typescript:怎么获取一个函数的参数的类型

   https://lzw.me/a/typescript-parameters-and-returntype.html

2. typescript:怎么将一个type声明的类型转为可选

   https://juejin.cn/post/6962441571018997791

3. ts重载具体怎么写

   https://www.cnblogs.com/Wayou/p/function_overload_in_typescript.html

   https://www.jianshu.com/p/b11e24dec350

4. A<T extends Array>是什么效果,类型约束达到的是什么效果

   https://www.coder.work/article/1324002

   https://segmentfault.com/a/1190000020048160

   https://blog.csdn.net/weixin_43294560/article/details/107464378

5. 说说类型推断

   [类型推论](https://www.tslang.cn/docs/handbook/type-inference.html)

6. 常用的ts特性

7. typescript的extends了解么

   https://juejin.cn/post/6872111128135073806#heading-95

8. 用过哪些ts规则

9. ts的Omit Pick的用法

   https://juejin.cn/post/6905928813452984327

   https://juejin.cn/post/6844903977461514254

   https://blog.csdn.net/diwang_718/article/details/109331973

10. Ts：怎么获取一个类型声明的所有key

11. ts相比js多了哪些数据类型

    https://www.136.la/jingpin/show-67608.html

12. 为什么会出现ts

13. 了解继承,多态,重载么

    > 多态：父类定义一个方法不去实现，让继承他的子类去实现，每一个子类有不同的表现
    >
    > 多态属于继承

    [TypeScript（类—继承—多态）](https://www.cnblogs.com/jing-zhe/p/13061749.html)

    https://blog.csdn.net/handsomezhanghui/article/details/107459931

    http://dditblog.com/itshare_695.html

    https://www.cnblogs.com/mengxiangji/p/10399066.html

14. 说说泛型,函数泛型 怎么使用的

    https://juejin.cn/post/6844904184894980104

15. 声明一个Interface把一个联合类型的属性都改为any类型

16. 实现ts的Pick

17. 怎么实现Array<T>

18. interface,type,class的区别

    [typescript 中的 interface 和 type 到底有什么区别](https://github.com/SunshowerC/blog/issues/7)

19. 说说你对泛型的了解



#### 基建

1. 常用的打包工具

2. webpack原理

   [说说webpack打包的原理](https://github.com/LuckyWinty/fe-weekly-questions/issues/5)

3. webpack的loader和plugin的区别,有没有写过,plugin有哪些钩子

   https://blog.csdn.net/jiang7701037/article/details/98887179

   https://cloud.tencent.com/developer/article/1558870

   [超详细webpack的plugin讲解](https://blog.csdn.net/DengZY926/article/details/105827861)

4. loader的原理  loader转换文件过程具体是怎么做的

   https://www.cnblogs.com/lyraLee/p/12050811.html

   https://cloud.tencent.com/developer/article/1584819

   http://www.babyitellyou.com/details?id=6000f38e0c14081073f63056

5. babel-loader的作用

   https://www.jianshu.com/p/78832d23f176

   https://www.jiangruitao.com/webpack/babel-loader/

6. 怎么提升webpack打包速度

   https://juejin.cn/post/6844904071736852487

   https://cloud.tencent.com/developer/article/1603799

   https://zhuanlan.zhihu.com/p/145012279

7. webpack优化

   [Webpack性能优化你知道哪些](https://github.com/LuckyWinty/fe-weekly-questions/issues/4)

8. babel的原理   jsx到ast的转化具体做了什么,ast了解么

   [回顾 babel 6和7，来预测下 babel 8](https://juejin.cn/post/6956224866312060942)

   [掌握了AST，再也不怕被问babel，vue编译，Prettier等原理](https://juejin.cn/post/6844904019505184776)

9. babel将less转css具体怎么做的

10. 如果兼容ie10,babel需要怎么配置,

   https://blog.csdn.net/relax_go/article/details/107992133

   https://www.cnblogs.com/chun321/p/13070553.html

   https://www.cnblogs.com/niejunchan/p/10764823.html

11. 组件库怎么兼容各浏览器

12. babel-preset了解么

    https://www.cnblogs.com/dapengFly/p/9876915.html

13. publicPath是什么,用在什么场景

    https://runebook.dev/zh-CN/docs/webpack/guides/public-path

    https://champyin.com/2019/12/05/webpack%E4%B8%AD%E7%9A%84publicPath/

14. prettier的作用和lint的区别

    https://juejin.cn/post/6844904065319731208

    https://juejin.cn/post/6844903621805473800

    https://segmentfault.com/a/1190000039026362

15. babel-component-plugin是什么

    https://juejin.cn/post/6844904077634060302

16. babel预设和plugin的区别

    https://github.com/LuckyWinty/fe-weekly-questions/issues/85

    https://blog.csdn.net/qq_37506861/article/details/86591623

    https://www.jianshu.com/p/43063a413cd9

17. antd-design的设计原理

18. 你们脚手架的实现方式

19. 怎么实现异步加载

    https://www.jianshu.com/p/3aa3a3e27417

    https://cloud.tencent.com/developer/article/1573508

    https://segmentfault.com/a/1190000038180453

20. 谈谈组件api设计需要考虑哪些方面,目前用的框架有哪些符合开箱即用的思想,比如webpack

    https://www.jianshu.com/p/c8c092cf8f2f

21. 怎么通过ast过滤代码中的某些指定代码

    https://blog.csdn.net/weixin_39408343/article/details/95984062

    https://blog.csdn.net/qq_36571602/article/details/103533029

22. 了解动态polyfill么

    https://blog.csdn.net/liixnhai/article/details/109279138

23. 有独立搭建过脚手架么

24. style-lint了解么

    https://juejin.cn/post/6844903640549818382

25. 说说你们团队的代码规范

    https://www.cnblogs.com/sk-3/p/14214311.html

     https://blog.csdn.net/qq_26003101/article/details/102816915

26. 在线代码编辑器怎么过滤不安全的代码

    https://blog.csdn.net/weixin_33379878/article/details/117870038

27. 主要写ui组件还是业务组件,怎么管理的

28. tree shaking的原理

    [tree shaking 及其工作原理](https://mp.weixin.qq.com/s/yiAbYvTlzsvUqfRzjyk9Rw)

    [Webpack 实现 Tree shaking 的前世今生](https://mp.weixin.qq.com/s/gSPlJ8zjKSqkOKkI7_AXIQ)

29. 组件库打包成umd,业务上怎么通过import引入你的组件呢

    https://www.jqhtml.com/63324.html

30. peerdependency 和devdependency的区别

    https://blog.csdn.net/weixin_43459866/article/details/112392975

31. 用过哪些单元测试工具

#### NODEJS

1. 有没有用过nodejs

2. nodejs可以做哪些事情  你做过哪些  

   https://mp.weixin.qq.com/s/QtjlRKm6kIb80P36rv4c2Q

3. require引入内置模块,第三方模块,本地模块的原理

   https://mp.weixin.qq.com/s/prbmnVsVxHFDz2dxHsKSrg

4. node中setTimeout  setInterval和js中有什么区别   除这2种之外,还有什么方式做异步   nexttick了解么

   > process.nextTick 是一个独立于 eventLoop 的任务队列。在每一个 eventLoop 阶段完成后会去检查 nextTick 队列，如果里面有任务，会让这部分任务优先于微任务执行。是所有异步任务中最快执行的

   > setTimeout：setTimeout()方法是定义一个回调，并且希望这个回调在我们所指定的时间间隔后第一时间去执行。
   >
   > setImmediate：setImmediate()方法从意义上将是立刻执行的意思，但是实际上它却是在一个固定的阶段才会执行回调，即poll阶段之后。

   https://blog.csdn.net/weixin_34351321/article/details/88975764

5. node读取一个json文件怎么读?

6. node了解多少

#### Mobx&Redux

1. reduce的用法

   https://juejin.cn/post/6844903861941993479

   https://mp.weixin.qq.com/s/JFkd_mnuTXkvquFehWwWZw

2. redux和mobx的区别,了解recoil么

   https://blog.csdn.net/michellezhai/article/details/90783020

   https://blog.csdn.net/weixin_44369568/article/details/90713881

3. 开发过程中应该什么时候考虑性能优化,要考虑哪些方面  宏观上的考量? 提前预设? 针对某个具体页面的性能极致优化要做哪些

   https://kaiwu.lagou.com/course/courseInfo.htm?courseId=566#/detail/pc?id=5803

   https://juejin.cn/post/6904517485349830670

   https://segmentfault.com/a/1190000022018051

4. 说说redux用过哪些api

5. redux的原理

   [Redux实现原理解析及应用](https://www.jianshu.com/p/e984206553c2)

6. mobx的原理

   [Mobx 思想的实现原理](https://blog.csdn.net/sinat_17775997/article/details/83998800)

7. mobx的代理模式怎么兼容到ie9

8. redux的reducer用来做什么的

   [Redux介绍之Reducer](https://www.jianshu.com/p/985d01df5918)

9. redux怎么触发渲染

10. 怎么解决mobx的类数组问题

11. mobx相比于state  context的优点

12. 使用mobx过程中遇到什么问题,为什么要用toJS

    

#### 性能

1. 怎么量化性能指标  有哪些工具

   https://mp.weixin.qq.com/s/g5mNfofLjpKjYQarzzrLCw

2. 做过哪些性能优化

3. 性能优化用户体验有哪些维度可以衡量,怎么量化?分别有哪些具体措施,时间维度上怎么统计,文件体积维度上开发时和运行时分别有哪些措施,怎么统计文件加载时间,文件体积?怎么埋点 页面异常的处理,怎么监听js运行异常,保证页面不白屏,有哪些处理方式,怎么监听文件加载异常?

   性能优化  https://www.cnblogs.com/mengff/p/12890771.html

   页面加载时间 https://blog.csdn.net/weixin_45761317/article/details/103440135

   白屏  https://blog.csdn.net/m0_48076809/article/details/109058909

   异常  http://jartto.wang/2018/11/20/js-exception-handling/

4. 给你大量dom节点,你怎么渲染

   https://blog.csdn.net/running987/article/details/81541599?utm_medium=distribute.pc_relevant_download.none-task-blog-baidujs-1.nonecase&depth_1-utm_source=distribute.pc_relevant_download.none-task-blog-baidujs-1.nonecase

5. 虚拟列表的原理

   https://mp.weixin.qq.com/s/OwlLk7-OvT0fEu6eOUlNIQ

6. 怎么判断可视区域内的第一条数组是整个列表的第1条数据

7. immutablejs了解么

   https://mp.weixin.qq.com/s/lCiN8XVlzhLPoMnvK3IjVw

8. 了解PWA么

   https://mp.weixin.qq.com/s/vlAb24qxklbnZoSZk25rSA

9. 了解Service Worker么

   https://juejin.cn/post/6844904198639714311#heading-22

10. 给你一个10万条数据的列表,你怎么处理

    https://blog.csdn.net/running987/article/details/81541599?utm_medium=distribute.pc_relevant_download.none-task-blog-baidujs-1.nonecase&depth_1-utm_source=distribute.pc_relevant_download.none-task-blog-baidujs-1.nonecase

11. 性能问题怎么排查,怎么优化 性能监控 

12. 怎么按需异步封装echarts

    https://blog.csdn.net/yh8899abc/article/details/107058688

    https://blog.csdn.net/qq_39075021/article/details/105445991

13. 怎么做持久化存储  immutable的原理  怎么实现的  和mutable的区别  有什么缺陷,为什么没在项目中使用

    https://blog.csdn.net/qq_42941302/article/details/111834035

    https://blog.csdn.net/ajpr3120/article/details/101553957?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-5.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-5.control

    https://www.jianshu.com/p/e839d5b9f7cc

    https://cloud.tencent.com/developer/news/7752

    https://www.cnblogs.com/3body/p/6224010.html

     https://www.cnblogs.com/dm428/p/13910473.html

14. 图片压缩有哪些办法,图片格式了解多少

    [前端的图片优化方案你知道多少](https://github.com/LuckyWinty/fe-weekly-questions/issues/34)

15. 按需打包?按需加载?怎么做?区别?

    [Webpack性能优化你知道哪些](https://github.com/LuckyWinty/fe-weekly-questions/issues/4)



#### 路由

1. react-router路由对应的页面渲染有哪些方式?优先级?render  component  children

   https://blog.csdn.net/achenyuan/article/details/80704641

   https://blog.csdn.net/xiaoqingrong/article/details/101055085

2. React-router:分别配置path='/' path='/a' path='/a/b'访问/a,会渲染哪些

   https://juejin.cn/post/6844903640839225358

3. react-router严格匹配是哪个参数

   https://blog.csdn.net/weixin_41530639/article/details/107324961

4. react-router用户权限怎么处理  有权限正常显示  无权限渲染无权限页面

   https://juejin.cn/post/6854573217445740557

5. react-router原理

   https://segmentfault.com/a/1190000016512437

6. 说说hash和history的区别 原理

   https://mp.weixin.qq.com/s/lTW3NIO7iZYmq75_0-mhRQ

#### 网络

1. 有没有用过cdn,cdn了解么  内容分发网络,cdn的回源策略?

   https://mp.weixin.qq.com/s/8IzDE4blQ_yC6z90q55UhA

2. 强缓存 协商缓存  优先级

   https://mp.weixin.qq.com/s/G5FIrWOtsNROHgEKesJcdg

3. 通过什么禁用html缓存,怎么配置

   https://www.cnblogs.com/waisonlong/p/5199908.html

4. 跨域的几种方式  jsonp的缺点 jsonp的方式前端怎么获取到请求的内容

   > 1.前端定义解析函数（例如 jsonpCallback=function(){....}）
   >
   > 2.通过 params 形式包装请求参数，并且声明执行函数(例如 cb=jsonpCallback)
   >
   > 3.后端获取前端声明的执行函数（jsonpCallback），并以带上参数并调用执行函数的方式传递给前端。

   https://juejin.cn/post/6844904126246027278

5. 为什么要封装请求库

   https://blog.csdn.net/weixin_44348028/article/details/108504471

   https://zhuanlan.zhihu.com/p/87985178

6. http2相比http1有哪些优点

   https://mp.weixin.qq.com/s/GICbiyJpINrHZ41u_4zT-A?

7. https的原理  相比http有哪些优点,缺点

   https://mp.weixin.qq.com/s/CU9mOxVixaOann9Hu5MlXQ

   https://www.cnblogs.com/miniSimple/p/12296846.html

8. 使用什么请求库  fetch和axios的区别  为什么会从fetch转成用axios  axios拦截器怎么使用,拦截器的response分别什么情况下成功回调,什么情况下走失败回调

   https://www.jianshu.com/p/8bc48f8fde75

   https://www.cnblogs.com/xbzhu/p/11810384.html

9. websocket用过么

   https://mp.weixin.qq.com/s/OKiVeiAtdZvSG5ZC8jYOzg

   https://blog.csdn.net/yexudengzhidao/article/details/92846600

   https://blog.csdn.net/resilient/article/details/85613446

10. memorycache和diskcache的区别

11. 为什么要有协商缓存

12. 协商缓存中客户端给服务端通信时,Etag是通过哪个字段传递的

13. 浏览器输入一个url地址后的过程,浏览器是怎么请求,解析资源文件的

    [浏览器输入URL后发生了什么](https://github.com/LuckyWinty/fe-weekly-questions/issues/37)

14. 强缓存命中的状态码是?   200

15. 常见的接口响应状态码

16. 一次http请求过程是怎样的

17. ajax请求过程,原理

#### GIT

1. 怎么做代码版本管理?git svn?

   gitlab  +  github  desk

2. git:怎么回退版本,有哪些方式

   https://blog.csdn.net/yxlshk/article/details/79944535

   https://juejin.cn/post/6844903877138087950

3. git revert了解么

4. git add 的用法

5. 怎么合并分支   git merge --no-ff是做什么的?

6. git回滚

7. rebase和merge的区别

8. 怎么合并多个commit信息

   [Git操作：多个commit合并，并修改提交信息](https://blog.csdn.net/u012586326/article/details/112985496)

#### 移动端适配

1. 移动端兼容性问题处理过哪些

   https://mp.weixin.qq.com/s/BPXd-TNHHzb49fjC60NZFg

2. 移动端适配

   https://mp.weixin.qq.com/s/lM65luoAeV7RZTIYFCpVZw

3. 1px问题，为什么会有这个问题，怎么解决

   https://www.jianshu.com/p/7e63f5a32636

4. iphoneX适配

   https://blog.csdn.net/dx18520548758/article/details/80010358

5. 说说jsBridge   原生怎么捕获到h5页面的事件

   https://juejin.cn/post/6844903585268891662

6. 移动端适配怎么做的 字体像素颜色什么的

7. ios的惯性滚动问题了解么

   [iOS与惯性滚动](https://www.cnblogs.com/chris-oil/p/6164966.html)



#### 数据结构&算法

1. 取链表中间节点最优解

   https://blog.csdn.net/weixin_26738395/article/details/108515443

2. 实现二叉树左右结点交换,除了递归,还有什么方法,用栈,队列怎么实现

3. 链表反转

   https://www.jianshu.com/p/4e8e29bda969
   
4. 返回字符串不重复字符长度

5. 找到值最大的树节点(手写题)

6. 了解哪些排序方式?快排和冒泡排序的原理

```
假设有一个集合 ['foo', 'bar', 'hello', 'world']，求这个集合里单词组合起来的所有不同的结果，比如：

foobarhelloworld
barfoohelloworld
...


https://leetcode-cn.com/problems/permutation-i-lcci/
```

```
// 从 arr 中随机取出数字，插入到 group 的子数组内，让每组尽可能一样多，比如：
// 最终得到 group 值为 [[2, 3, 8], [1, 4], [9, 7], [1, 6]]，每组 2 个数字，其实有一组为 3 个数字

var arr = [1,2,3,4,5,6,7,8,9];
var group = [[],[],[],[]];

function split(arr) {

}
split(arr);
console.log(group);
```



#### 其他

1. 前端项目部署到服务器需要做哪些事情,web服务器用什么  nginx反代具体怎么配

   https://segmentfault.com/a/1190000021530126 

   https://blog.csdn.net/sherry_chan/article/details/79055211

3. 前端请求接口容错?

   谁来补充

4. 接到一个新的需求,你需要做哪些事情? 沟通需求,原型,UI,约定接口规范,开发?具体怎么约定接口规范,要考虑哪些

5. 移动端离线包方案怎么做离线包版本管理,怎么保证下载的离线包是最新的,怎么处理离线包异常情况,这个方案落地后达到的效果

   https://juejin.cn/post/6844904031773523976#heading-6

   https://github.com/mcuking/blog/issues/63

6. 工作状态是怎么样的,遇到问题怎么解决

   看报错，谷歌Stack Overflow找答案，谁能更好的吹牛逼

7. 浏览器怎么去加载相应的js文件的

   https://blog.csdn.net/liupeifeng3514/article/details/78998293

   https://www.zhihu.com/question/263866883

   https://www.jianshu.com/p/9267bb6c6006

   https://www.cnblogs.com/jiasm/p/7683930.html

8. 低代码了解么

   https://juejin.cn/post/6961606343442726925

   https://zhuanlan.zhihu.com/p/267844751

   https://zhuanlan.zhihu.com/p/196228385

9. int 8,32,64分别几个字节

   4

10. 通过什么方式学习

11. 用过哪些抓包工具  前端工具

12. 怎么实现移动端列表无限滚动,scoll监听会有什么问题,安卓ios下分别有什么问题

    https://blog.csdn.net/qq_42740797/article/details/111371301

    https://www.cnblogs.com/caominjie/p/11802501.html

    https://mp.weixin.qq.com/s/oAlkEB4G6I5BokZQ02Pvng

13. 分组列表分组吸顶怎么实现

14. 离线包版本更新同步客户端时,同步失败怎么处理

15. 工作中有哪些事情是你主动去做的

17. 你们组件库是怎么做的

24. 了解Taro么

27. xss和csrf分别是?怎么防御?

28. 遇到页面加载空白和页面中被插入了一段广告,你会怎么处理

19. 作用域,原型链,作用域链,作用域链和原型链的区别

    https://www.cnblogs.com/pssp/p/5204324.html

20. 怎么过滤在线代码管理器中的xss脚本

21. ie上常遇到哪些问题

22. localstorage缓存最大能存多少,存入失败会怎么样,存的东西超出限制大小你怎么处理

23. 服务端是怎么主动给客户端发消息的?通过什么方式?

24. 

    

#### 代码执行结果

```
new Promise((rs)=>{
    console.log(1)
    rs()
}).then(()=>{
    console.log(2)
})

setTimeout(()=>{
    new Promise((rs)=>{
        console.log(3)
        rs()
    }).then(()=>{
        console.log(4)
    })
    console.log(5)
})
```

```
new Promise((rs)=>{
    console.log(1)
    rs()
}).then(()=>{
    console.log(2)
})
new Promise((rs)=>{
    console.log(3)
    rs()
}).then(()=>{
    console.log(4)
})
setTimeout(()=>{
    console.log(5)
})
```

```
class Person {
    constructor(name, age) {
      this.name = name;
      this.age = age;
    }
    say() {
      console.log('名字' + this.name + '今年' + this.age);
    }
    run = () => {
      console.log(this.name + '可以run');
    };
    eat() {
      console.log('可以吃');
    }
  }
  
  class CloneMan extends Person {
    say = () => {
      console.log('我叫' + this.name + '今年' + this.age);
    };
    run() {
      console.log(this.name + '真的可以run');
    }
    eat = () => {
      console.log('还可以吃');
    };
  }
  
  const tom = new CloneMan('tom','20')
  tom.say()
  tom.run()
  tom.eat()
```

```
console.log('1')

setTimeout(function() {
  console.log('2')

  new Promise(function(resolve) {
    console.log('4')
    resolve()
  }).then(function() {
    console.log('5')
  })
})

async function async1() {
  console.log('6')
  await async2()
  console.log('7')
}

async function async2() {
  console.log('8')
  await async3()
  console.log('9')
}

async function async3() {
  console.log('10')
}

async1()
new Promise(function(resolve) {
  console.log('11')
  resolve()
}).then(function() {
  console.log('12')
})

setTimeout(function() {
  console.log('13')

  new Promise(function(resolve) {
    console.log('14')
    resolve()
  }).then(function() {
    console.log('15')
  })
})
```

```
var arr = []
setTimeout(()=>{
    arr.push(1)
})
new Promise((rs)=>{
    rs()
}).then(()=>{
    arr.push(2)
})
new Promise((rs)=>{
    arr.push(3)
    rs()
})
async function a(){
    arr.push(4)
    await b()
    arr.push(5)
}
async function b() {
    arr.push(6)
}
a()
arr.push(7)
setTimeout(()=>{
    arr.push(8)
})
setTimeout(()=>{
    console.log(arr.join(''))
},300)

// 输出结果是什么,描述下这段代码执行过程中的内存分配是什么样的,使用promise实现a函数
```

```
if(!('a' in window)){
    var a = 1
}
console.log(a)
```

```
/* *
 * 问题 2. 
 * 对象扁平化
 * 说明：请实现 flatten(input) 函数，input 为一个 javascript 对象（Object 或者 Array），返回值为扁平化后的结果。
 * 示例：
 *   var input = {
 *     a: 1,
 *     b: [ 1, 2, { c: true }, [ 3 ] ],
 *     d: { e: 2, f: 3 },
 *     g: null, 
 *   }
 *   var output = flatten(input);
 *   output如下
 *   {
 *     "a": 1,
 *     "b[0]": 1,
 *     "b[1]": 2,
 *     "b[2].c": true,
 *     "b[3][0]": 3,
 *     "d.e": 2,
 *     "d.f": 3,
 *     // "g": null,  值为null或者undefined，丢弃
 *  }
 */
 
 
 function flatten(input, init, re) {

  let res = re || {}

  if (Object.prototype.toString.call(input) === '[object Object]') {
    Object.keys(input).forEach(item => {
      if (typeof input[item] !== 'object' && input[item]) {
        res[`${init}.item`] = input[item]
      } else if (input[item]) {
        flatten(input[item], `${init}.item`, res)
      }

    })
  }

  if (Object.prototype.toString.call(input) === '[object Array]') {
    input.forEach((item, index) => {
      if (typeof item !== 'object' && item) {
        res[`${init}[${index}]`] = item
      } else if (item) {
        flatten(item, `${init}[${index}]`, res)
      }
    })
  }

  return res;
}
```



#### 提问

1. 主要用什么技术栈
2. 团队规模
3. 这个岗位主要做什么的
4. 工作强度,工作作息
5. 这边主要做什么产品的
6. 薪酬体系
7. 这个岗位成长的空间

#### 抄来的

1. react初始化详细过程
2. react在setState的时候做了哪些事
3. react fiber在中断diff算法的后怎么再去重新开始diff算法的
4. webpack打包过后的chunk,懒加载的包是怎么在浏览器上加载的
5. webpack要怎么打包才能实现按需加载
6. 递归和尾递归的区别
7. webpack热更新原理




