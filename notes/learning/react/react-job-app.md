# React全家桶+Epxress+MongoDB开发招聘APP

## React基础知识

### React是什么

- 帮助你构建UI的库
  - Facebook出品，专注View层
  - 一切皆为组件
  - 全部使用ES6语法

### 组件之间传递数据

- 组件之间用props传递数据
  - 使用`<组件 key="val">`形式传递
  - 组件里使用this.props获取值
  - 如果组件只有render函数，还可以用函数的形式写组件

### 组件内部state

- 组件内部通过state管理状态
  - JSX本质是JS，所以直接数据`.map`渲染列表
  - Constructor设置初始状态，记得执行super(props)
  - 如State就是一个不可变的对象，使用this.state获取

### 事件

- JSX里，onClick={this.函数名}来绑定事件
- this引用的问题，需要在构造函数里用bind绑定this
- this.setState修改state，记得必须返回新的state，而不是修改

### 生命周期

- React组件有若干钩子函数，在组件不同的状态执行
  - 初始化周期
  - 组件重新渲染生命周期
  - 组件卸载生命周期

![image.png-143.5kB][1]
![image.png-816kB][2]
![image.png-245.9kB][3]

  [1]: http://static.zybuluo.com/szy0syz/wojlnmcp2la4uxv0xe35juec/image.png
  [2]: http://static.zybuluo.com/szy0syz/3a1slmbmhcvnwing382lmxg6/image.png
  [3]: http://static.zybuluo.com/szy0syz/qsypkctj5nxokbgzsibddtgy/image.png