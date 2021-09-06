纯函数： 相同的输入，总会得到相同的输出，并且执行过程中没有副作用  
好处：
 > 更容易进行测试，结果只依赖输入  
 >更容易维护和重构  
 >更容易调用
 >结果可以缓存


# Redux
<https://tuture.co/2019/11/28/1fe175a/>  
一个用来管理状态（数据）的框架

redux适用场景： 多交互，多数据源

###  Store
store 是存数据的地方，整个应用只有一个store。
createStore() - 用来生成store

### Reducer
负责更新store中状态的js函数


### Provider - 这个组件能使整个APP都能获取到store中的数据  
- Provider包裹在组件最外层，使所有的子组件都可以拿到state 
- Provider接收store作为props, 然后通过context往下传递， 这样react中任何组件都可以通过context获取到store
- 解决了容器组件可能存在很深的层级，防止一层一层去传递state

### connect - 这个方法能够使组件跟store进行关联
- provider内部组件如果想要使用到state中的数据，就必须要connect进行一层包裹封装


# Hooks
<https://reactjs.org/docs/hooks-intro.html>  
组件尽量写纯函数，如果需要外部功能和副作用，就用钩子把外部代码钩进来  
钩子一律使用use前缀命名  
四个最常用的钩子
> - useState()
> - useContext()
> - useReducer()
> - useEffect()

### useState() 状态钩子
用于为函数组件引入状态(state), 纯函数不能有状态，所以状态放钩子里面 


### useContext() 共享状态钩子
如果需要在组件之间共享状态

### useReducer() action钩子


### useEffect() 副作用钩子
引入具有副作用的操作，最常见的就是向服务器请求数据


# Router 
<https://www.ruanyifeng.com/blog/2016/05/react_router.html>
