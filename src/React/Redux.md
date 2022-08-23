## Redux

### State 状态

```
DomainState: 服务器返回的State
UI State: 关于当前组件的State
APP State: 全局的State
```

### Action事件
```
本质就是一个JS对象
必须要包含type属性
只是描述了有事情要发生，并没有描述如何去更新state
```

### Reducer
```
本质就是函数
相应发送过来的action
函数接收两个参数，第一个是初始化state，第二个是发送过来的action
必须要有return返回值
```

### Store
```
用来把action和reducer关联到一起的
通过createStore来构建store
通过subscribe来注册监听
通过dispatch来发送action
```