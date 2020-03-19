# 30-seconds-of-interviews-cn
30-seconds-of-interviews中文， [英文原版 30-seconds-of-interviews 地址](https://github.com/30-seconds/30-seconds-of-interviews)

## 目录
---

### JavaScript

<details>
<summary>查看内容</summary>

* [创建一个 `batches` 函数，该函数返回可以从配方中烹制的最大批数。](#创建一个-batches-函数该函数返回可以从配方中烹制的最大批数)
* [什么是大 O 符号？](#什么是大-o-符号)
* [创建一个在功能上等效于 Function.prototype.bind 方法的独立函数 `bind`。](#创建一个在功能上等效于-functionprototypebind-方法的独立函数-bind)
* [如何避免回调地狱？](#如何避免回调地狱)
* [用回调函数作为 `setState` 的参数目的是什么？](#用回调函数作为-setstate-的参数目的是什么)
* [回调 `refs` 和 `findDOMNode()` 之间的首选选项是什么？](#回调-refs-和-finddomnode-之间的首选选项是什么)
* [什么是回调？请举一个例子？](#什么是回调请举一个例子)
* [什么是 `children` 属性？](#什么是-children-属性)
* [如何在 JavaScript 中克隆一个对象？](#如何在-javascript-中克隆一个对象)
* [什么是闭包？请举一个例子？](#什么是闭包请举一个例子)
* [如何比较两个 JavaScript 中的对象？](#如何比较两个-javascript-中的对象)
* [什么是 `context`？](#什么是-context)
* [什么是 `CORS`？](#什么是-cors)
* [什么是 `DOM`？](#什么是-dom)
* [运算符 `==` 和 `===` 有什么区别？](#运算符--和--有什么区别)
* [React 中 element 和 component 有什么区别？](#react-中-element-和-component-有什么区别)
* [什么是事件委派？为什么有用？请举例说明如何使用？](#什么是事件委派为什么有用请举例说明如何使用)
* [什么是事件驱动编程？](#什么是事件驱动编程)
* [JavaScript 中的表达式和语句有什么区别？](#javascript-中的表达式和语句有什么区别)
* [JavaScript 中真假值是什么？](#javascript-中真假值是什么)
* [生成一个包含斐波那契序列的数组，直到第 n 个项。](#生成一个包含斐波那契序列的数组直到第-n-个项)
* [`0.1 + 0.2 === 0.3` 的结果是什么？](#01--02--03-的结果是什么)
* [数组方法 `map()` 和 `forEach()` 有什么区别？](#数组方法-map-和-foreach-有什么区别)
* [什么是 fragments？](#什么是-fragments)
* [什么是函数式编程？](#什么是函数式编程)
* [在此示例中控制台将输出什么？](#在此示例中控制台将输出什么)
* [提升如何在 JavaScript 中工作？](#提升如何在-javascript-中工作)
* [HTML 和 React 事件处理之间有什么区别？](#html-和-react-事件处理之间有什么区别)
* [将 JavaScript 源文件的全部内容包装在立即调用的函数中的原因是什么？](#将-javascript-源文件的全部内容包装在立即调用的函数中的原因是什么)
* [解释命令式和声明式编程之间的区别。](#解释命令式和声明式编程之间的区别)
* [什么是内联条件表达式？](#什么是内联条件表达式)
* [什么是 key，在列表中使用它有什么好处？](#什么是-key在列表中使用它有什么好处)
* [词汇作用域和动态作用域有什么区别？](#词汇作用域和动态作用域有什么区别)
* [创建一个函数，该函数用 # 掩盖一串字符最后四个字符除外。](#创建一个函数该函数用--掩盖一串字符最后四个字符除外)
* [什么是记忆化？](#什么是记忆化)
* [如何确保方法在 React 组件类中 `this` 具有正确的上下文？](#如何确保方法在-react-组件类中-this-具有正确的上下文)
* [什么是 MIME 类型？它的用途是什么？](#什么是-mime-类型它的用途是什么)
* [对比可变值和不可变值，变异与非变异方法。](#对比可变值和不可变值变异与非变异方法)
* [在 JavaScript 中唯一不等于自身的值是什么？](#在-javascript-中唯一不等于自身的值是什么)
* [NodeJS 经常使用回调模式，如果执行过程中遇到错误，此错误将作为第一个参数传递给回调。这种模式有什么优势？](#nodejs-经常使用回调模式如果执行过程中遇到错误此错误将作为第一个参数传递给回调这种模式有什么优势)
* [Node.js 中的事件循环是什么？](#nodejs-中的事件循环是什么)
* [`null` 和 `undefined` 有什么区别？](#null-和-undefined-有什么区别)
* [描述创建对象的不同方法。什么时候应该首选某些方法？](#描述创建对象的不同方法什么时候应该首选某些方法)
* [parameter 和 argument 有什么区别？](#parameter-和-argument-有什么区别)
* [JavaScript 是按值传递还是引用传递？](#javascript-是按值传递还是引用传递)
* [如何将参数传递给事件处理程序或者回调？](#如何将参数传递给事件处理程序或者回调)
* [创建一个函数 `pipe`，该函数管道通过返回接受一个参数的函数来执行从左到右的函数编写。](#创建一个函数-pipe该函数管道通过返回接受一个参数的函数来执行从左到右的函数编写)
* [React 中的 portals 是什么？](#react-中的-portals-是什么)
* [`i++` 和 `++i` 运算符有什么区别？](#i-和-i-运算符有什么区别)
* [什么是 Promise？](#什么是-promise)
* [Promise 可以在哪些状态下进行？](#promise-可以在哪些状态下进行)
* [原型继承和经典继承有何不同？](#原型继承和经典继承有何不同)
* [什么是纯函数？](#什么是纯函数)
* [什么是递归？什么时候有用？](#什么是递归什么时候有用)
* [以下代码的输出是什么？](#以下代码的输出是什么)
* [React 中 refs 是什么？什么时候需要使用它们？](#react-中-refs-是什么什么时候需要使用它们)
* [以下函数返回什么？](#以下函数返回什么)
* [JavaScript 是否需要分号？](#javascript-是否需要分号)
* [什么是 JavaScript 中的短路评估？](#什么是-javascript-中的短路评估)
* [React 中的有状态组件是什么？](#react-中的有状态组件是什么)
* [什么是无状态组件？](#什么是无状态组件)
* [解释静态方法和实例方法的区别。](#解释静态方法和实例方法的区别)
* [JavaScript 中的同步代码和异步代码有什么区别？](#javascript-中的同步代码和异步代码有什么区别)
* [`this` 关键字是什么？它如何工作？](#this-关键字是什么它如何工作)
* [以下代码的计算结果是什么？](#以下代码的计算结果是什么)
* [什么是 JavaScript 的数据类型？](#什么是-javascript-的数据类型)
* [JavaScript UI库/框架，例如 React、Vue、Angular、Hyperapp 等的目的是什么？](#javascript-ui库框架例如-reactvueangularhyperapp-等的目的是什么)
* [`use strict` 有什么作用，使用它有哪些好处？](#use-strict-有什么作用使用它有哪些好处)
* [`var`、`let`、`const` 和无关键字语句有什么区别？](#varletconst-和无关键字语句有什么区别)
* [什么是虚拟 DOM？为什么在库/框架中使用它？](#什么是虚拟-dom为什么在库框架中使用它)
* [什么是跨站点脚本攻击(XSS)，如何防止它？](#什么是跨站点脚本攻击xss如何防止它)
</details>

<br>[⬆ 回到顶部](#目录)
### 创建一个 `batches` 函数，该函数返回可以从配方中烹制的最大批数。
```js
/**
它接受两个对象作为参数：第一个对象是食物配方，而第二个对象是可用成分。
每种成分的值都是一个数字，表示有多少单位。

`batches(recipe, available)`
*/

// 可以制作 0 份
batches(
  { milk: 100, butter: 50, flour: 5 },
  { milk: 132, butter: 48, flour: 51 }
)
batches(
  { milk: 100, flour: 4, sugar: 10, butter: 5 },
  { milk: 1288, flour: 9, sugar: 95 }
)

// 可以制作 1 份
batches(
  { milk: 100, butter: 50, cheese: 10 },
  { milk: 198, butter: 52, cheese: 10 }
)

// 可以制作 2 份
batches(
  { milk: 2, sugar: 40, butter: 20 },
  { milk: 5, sugar: 120, butter: 500 }
)
```

<details>
<summary>查看答案</summary>

我们必须拥有配方中所有可用的成分，并且其数量必须大于或等于所需的单位数量。
如果只有一种成分不可用或低于所需的成分，我们将无法批量生产。
使用 `Object.keys()` 以数组的形式返回配方的成分，然后使用 `Array.prototype.map()` 将每种成分映射到可用单位与配方所需量的比率。
如果配方所需的成分之一根本不可用，则该比率的值为 `NaN`，因此在这种情况下可以使用逻辑 OR 运算符回退为 `0`。

使用延展 `...` 运算符将所有成分比率的数组输入到 `Math.min()` 中，以确定最低比率。
将整个结果传递到 `Math.floor()` 中将向下舍入以返回整个批次的最大数量。

```js
const batches = (recipe, available) =>
  Math.floor(
    Math.min(...Object.keys(recipe).map(k => available[k] / recipe[k] || 0))
  );
```

#### 很高兴听到

##### 附加链接

</details>


<br>[⬆ 回到顶部](#目录)
### 什么是大 O 符号？

<details>
<summary>查看答案</summary>
  
Big O 表示法在计算机科学中用于描述算法的时间复杂度。
最好的算法将以最快的速度执行，并且具有最简单的复杂度。
算法并不总是执行相同的，并且可能会根据所提供的数据而有所不同。
尽管在某些情况下它们将快速执行，但在另一些情况下，即使要处理相同数量的元素，它们也将缓慢执行。
在这些示例中，基本时间为 1 个元素 = 1ms。

##### O(1)

```js
arr[arr.length - 1]
```

* 1000 elements = 1ms

恒定的时间复杂度。无论数组有多少个元素，理论上执行（不包括实际变化）所花费的时间都是相同的。

##### O(N)

```js
arr.filter(fn)
```

* 1000 elements = 1000ms

线性时间复杂度。执行时间将随着数组中元素的数量线性增加。如果数组有 1000 个元素，
并且该函数需要 1ms 的执行时间，则 7000 个元素将需要 7ms 的执行时间。
这是因为函数必须在返回结果之前遍历数组的所有元素。

##### O([1, N])

```js
arr.some(fn)
```

* 1000 elements = 1ms <= x <= 1000ms

执行时间取决于提供给函数的数据，它可能返回得很早或很晚。最好的情况是 O(1)，最坏的情况是 O(N)。


##### O(NlogN)

```js
arr.sort(fn)
```

* 1000 elements ~= 10000ms

浏览器通常为 `sort()` 方法实现 quicksort 算法，并且 quicksort 的平均时间复杂度为 O(NlgN)。
这对于大型馆藏非常有效。

##### O(N^2)

```js
for (let i = 0; i < arr.length; i++) {
  for (let j = 0; j < arr.length; j++) {
    // ...
  }
}
```

* 1000 elements = 1000000ms

执行时间与元素数量成正比增加。通常是嵌套循环的结果。

##### O(N!)

```js
const permutations = arr => {
  if (arr.length <= 2) return arr.length === 2 ? [arr, [arr[1], arr[0]]] : arr
  return arr.reduce(
    (acc, item, i) =>
      acc.concat(
        permutations([...arr.slice(0, i), ...arr.slice(i + 1)]).map(val => [
          item,
          ...val
        ])
      ),
    []
  )
}
```

* 1000 elements = Infinity (practically) ms

只需向阵列添加 1 个，执行时间就会非常快地增加。

#### 很高兴听到

* 警惕嵌套循环，因为执行时间呈指数增长。

##### 附加链接

* [Big O Notation in JavaScript](https://medium.com/cesars-tech-insights/big-o-notation-javascript-25c79f50b19b)

</details>


<br>[⬆ 回到顶部](#目录)
### 创建一个在功能上等效于 `Function.prototype.bind` 方法的独立函数 `bind`。

```js
function example() {
  console.log(this)
}
const boundExample = bind(example, { a: true })
boundExample.call({ b: true }) // logs { a: true }
```

<details>
<summary>查看答案</summary>
  
通过使用 rest `...` 运算符收集参数来返回接受任意数量参数的函数。
从该函数返回使用 `Function.prototype.apply` 调用 `fn` 的结果，以将上下文和参数数组应用于该函数。
  
```js
const bind = (fn, context) => (...args) => fn.apply(context, args)
```

#### 很高兴听到

##### 附加链接

</details> 



<br>[⬆ 回到顶部](#目录)
### 如何避免回调地狱？

```js
getData(function(a) {
  getMoreData(a, function(b) {
    getMoreData(b, function(c) {
      getMoreData(c, function(d) {
        getMoreData(d, function(e) {
          // ...
        })
      })
    })
  })
})
```

<details>
<summary>查看答案</summary>

重构函数以返回 promises 并使用 `async/await` 通常是最佳选择。
它们没有向函数提供导致深度嵌套的回调，而是返回可以等待并在数据到达后将被解决的 promise，从而允许以类似同步的方式执行下一行代码。

上面的代码可以像这样重组：

```js
async function asyncAwaitVersion() {
  const a = await getData()
  const b = await getMoreData(a)
  const c = await getMoreData(b)
  const d = await getMoreData(c)
  const e = await getMoreData(d)
  // ...
}
```

有很多方法可以解决回调地狱的问题：

* 模块化：将回调分为独立的函数
* 使用控制流库，例如 async
* 与 Promise 一起使用生成器
* 使用 async/await（从v7开始）

#### 很高兴听到

* 作为高效的 JavaScript 开发人员，您必须避免缩进级别的不断提高，产生清晰易读的代码，并能够处理复杂的流程。

##### 附加链接

* [Avoiding Callback Hell in Node.js](http://stackabuse.com/avoiding-callback-hell-in-node-js/)
* [Asynchronous JavaScript: From Callback Hell to Async and Await](https://blog.hellojs.org/asynchronous-javascript-from-callback-hell-to-async-and-await-9b9ceb63c8e8)

</details>



<br>[⬆ 回到顶部](#目录)
### 用回调函数作为 `setState` 的参数目的是什么?

<details>
<summary>查看答案</summary>

`setState` 完成并呈现组件后，将调用回调函数。由于 `setState` 是异步的，因此回调函数可用于任何后期操作。

```js
setState({ name: "sudheer" }, () => {
  console.log("The name has updated and component re-rendered")
})
```

#### 很高兴听到

* setState 完成后将调用回调函数，该回调函数用于任何后期操作。
* 建议使用生命周期方法而不是此回调函数。

##### 附加链接

* [React docs on setState](https://reactjs.org/docs/react-component.html#setstate)

</details>



<br>[⬆ 回到顶部](#目录)
### 回调 `refs` 和 `findDOMNode()` 之间的首选选项是什么？

<details>
<summary>查看答案</summary>

由于 `findDOMNode()` 将来会阻止 React 的某些改进，因此回调引用比 `findDOMNode()` API 更可取。

```jsx
// 使用findDOMNode（）的传统方法
class MyComponent extends Component {
  componentDidMount() {
    findDOMNode(this).scrollIntoView()
  }

  render() {
    return <div />
  }
}

// 推荐使用回调引用的方法
class MyComponent extends Component {
  componentDidMount() {
    this.node.scrollIntoView()
  }

  render() {
    return <div ref={node => (this.node = node)} />
  }
}
```

#### 很高兴听到

* 回调引用优于 `findDOMNode()`。

##### 附加链接

* [React docs on Refs and the DOM](https://reactjs.org/docs/refs-and-the-dom.html#exposing-dom-refs-to-parent-components)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是回调？请举一个例子？

<details>
<summary>查看答案</summary>

回调是在事件发生或特定任务完成后作为参数传递给另一个函数的函数，通常在异步代码中使用。
回调函数稍后由一段代码调用，但可以在初始化时声明而不调用它们。

例如，事件侦听器是异步回调，仅在发生特定事件时才执行。

```js
function onClick() {
  console.log("The user clicked on the page.")
}
document.addEventListener("click", onClick)
```

但是，回调也可以是同步的。
以下map函数采用一个回调函数，该回调函数在循环的每次迭代（数组元素）中均被同步调用。

```js
const map = (arr, callback) => {
  const result = []
  for (let i = 0; i < arr.length; i++) {
    result.push(callback(arr[i], i))
  }
  return result
}
map([1, 2, 3, 4, 5], n => n * 2) // [2, 4, 6, 8, 10]
```

#### 很高兴听到

* 函数是 JavaScript 中的特殊对象
* Callbacks vs Promises

##### 附加链接

* [MDN docs for callbacks](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function)

</details>


<br>[⬆ 回到顶部](#目录)
### 什么是 `children` 属性？

<details>
<summary>查看答案</summary>

`children` 是传递给组件的 props 对象的一部分，该对象允许将组件作为数据传递给其他组件，
从而能够干净地组成组件。React API 中有许多方法可以与此道具一起使用，例如 `React.Children.map`，
`React.Children.forEach`，`React.Children.count`，`React.Children.only` 和 
`React.Children.toArray`。children props 的一个简单用法示例如下：

```jsx
function GenericBox({ children }) {
  return <div className="container">{children}</div>
}

function App() {
  return (
    <GenericBox>
      <span>Hello</span> <span>World</span>
    </GenericBox>
  )
}
```

#### 很高兴听到

* Children 是一种允许组件作为数据传递到其他组件的属性。
* React API 提供了与此属性一起使用的方法。

##### 附加链接

* [React docs on Children](https://reactjs.org/docs/jsx-in-depth.html#children-in-jsx)

</details>



<br>[⬆ 回到顶部](#目录)
### 如何在 JavaScript 中克隆一个对象？

<details>
<summary>查看答案</summary>

使用对象散布运算符 `...`，可以将对象自身的可枚举属性复制到新对象中。
这将创建对象的浅表克隆。

```js
const obj = { a: 1, b: 2 }
const shallowClone = { ...obj }
```

使用这种技术，原型将被忽略。
此外，不会克隆嵌套对象，而是会复制其引用，因此嵌套对象仍引用与原始对象相同的对象。
为了有效地克隆可能嵌套在对象中的任何类型的对象（日期，RegExp，函数，集合等），深克隆要复杂得多。

其他替代方案包括：

* `JSON.parse(JSON.stringify(obj))` 可用于深度克隆一个简单的对象，
但它占用大量 CPU 且仅接受有效的 JSON（因此，它会剥离函数且不允许循环引用）。
* `Object.assign({}, obj)` 是另一种选择。
* `Object.keys(obj).reduce((acc, key) => (acc[key] = obj[key], acc), {})` 
是另一个更冗长的替代方案，它更深入地显示了该概念。

#### 很高兴听到

* JavaScript 通过引用传递对象，这意味着嵌套对象将复制其引用而不是其值。
* 可以使用相同的方法合并两个对象。

##### 附加链接

* [MDN docs for Object.assign()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
* [Clone an object in vanilla JS](http://voidcanvas.com/clone-an-object-in-vanilla-js-in-depth/)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是闭包？请举一个例子？

<details>
<summary>查看答案</summary>

闭包是在另一个函数内部定义的一个函数，即使在其词法范围之外执行时也可以访问其词法范围。
闭包可以访问三个范围的变量：

* 在其自身范围内声明的变量
* 在父函数范围内声明的变量
* 在全局范围内声明的变量

在 JavaScript 中，所有函数都是闭包，因为它们可以访问外部范围，但是大多数函数没有利用闭包的作用：
状态的持久性。因此，闭包有时也称为有状态函数。

另外，闭包是存储私有数据的唯一方法，这些私有数据无法从外部使用 JavaScript 进行访问。
它们是 UMD（通用模块定义）模式的关键，该模式通常在仅公开公共 API 但将实现细节保密的库中使用，
以防止与其他库或用户自己的代码发生名称冲突。


#### 很高兴听到

* 闭包很有用，因为它们使您可以将数据与对该数据进行操作的功能相关联。
* 闭包只能用一种方法替代对象。
* 闭包可用于模拟私有属性和方法。

##### 附加链接

* [MDN docs for closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
* [What is a closure](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36)
* [I never understood JavaScript closures](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8)

</details>



<br>[⬆ 回到顶部](#目录)
### 如何比较两个 JavaScript 中的对象？

<details>
<summary>查看答案</summary>

即使两个不同的对象可以具有相同的属性且具有相等的值，但是使用 == 或 === 比较时，它们并不被视为相等。
这是因为它们是通过参考（在内存中的位置）进行比较，而不是通过值进行比较的原始值。

为了测试两个对象的结构是否相等，需要一个辅助函数。
它将遍历每个对象的自身属性以测试它们是否具有相同的值，包括嵌套对象。
可选地，也可以通过传递 true 作为第三个参数来测试对象的原型是否等效。

注意：此技术不会尝试测试除普通对象，数组，函数，日期和原始值以外的数据结构的等效性。

```js
function isDeepEqual(obj1, obj2, testPrototypes = false) {
  if (obj1 === obj2) {
    return true
  }

  if (typeof obj1 === "function" && typeof obj2 === "function") {
    return obj1.toString() === obj2.toString()
  }

  if (obj1 instanceof Date && obj2 instanceof Date) {
    return obj1.getTime() === obj2.getTime()
  }

  if (
    Object.prototype.toString.call(obj1) !==
      Object.prototype.toString.call(obj2) ||
    typeof obj1 !== "object"
  ) {
    return false
  }

  const prototypesAreEqual = testPrototypes
    ? isDeepEqual(
        Object.getPrototypeOf(obj1),
        Object.getPrototypeOf(obj2),
        true
      )
    : true

  const obj1Props = Object.getOwnPropertyNames(obj1)
  const obj2Props = Object.getOwnPropertyNames(obj2)

  return (
    obj1Props.length === obj2Props.length &&
    prototypesAreEqual &&
    obj1Props.every(prop => isDeepEqual(obj1[prop], obj2[prop]))
  )
}
```

#### 很高兴听到

* 字符串和数字之类的基元通过它们的值进行比较
* 另一方面，对象通过引用进行比较（内存中的位置）

##### 附加链接

* [Object Equality in JavaScript](http://adripofjavascript.com/blog/drips/object-equality-in-javascript.html)
* [Deep comparison between two values](https://30secondsofcode.org/object#equals)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 context？

<details>
<summary>查看答案</summary>

Context 提供了一种通过组件树传递数据的方法，而不必在每个级别手动传递道具。
例如，许多组件需要在应用程序中访问经过身份验证的用户，区域设置首选项，UI 主题。

```jsx
const { Provider, Consumer } = React.createContext(defaultValue)
```

#### 很高兴听到

* Context 提供了一种通过 React 组件树传递数据的方法，而无需手动传递道具。
* Context 被设计为共享被认为是 React 组件树的全局数据。

##### 附加链接

* [React docs on Context](https://reactjs.org/docs/context.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 CORS？

<details>
<summary>查看答案</summary>

跨域资源共享或 CORS 是一种机制，该机制使用其他 HTTP 标头来授予浏览器访问权限，以从服务器访问与网站来源不同的来源的资源。

跨域请求的一个示例是从 http://mydomain.com 提供的 Web 应用程序，该应用程序使用 AJAX 发出对 http://yourdomain.com 的请求。

出于安全原因，浏览器限制了 JavaScript 发起的跨域 HTTP 请求。
 XMLHttpRequest 和 fetch 遵循同源策略，这意味着使用这些 API 的 Web 应用程序只能从访问该应用程序的同一来源请求 HTTP 资源，
除非来自其他来源的响应包括正确的 CORS 标头。

#### 很高兴听到

* CORS 行为不是错误，这是一种保护用户的安全机制。
* CORS 旨在防止用户可能无意访问的恶意网站向合法网站发出请求以读取其个人数据或违背其意愿采取行动。

##### 附加链接

* [MDN docs for CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

</details>


<br>[⬆ 回到顶部](#目录)
### 什么是 DOM？

<details>
<summary>查看答案</summary>

DOM（文档对象模型）是一种跨平台的 API，它将 HTML 和 XML 文档视为由节点组成的树形结构。
这些节点（例如元素和文本节点）是可以通过编程方式操作的对象，对其进行的任何可见更改都会实时反映在文档中。
在浏览器中，此 API 可用于 JavaScript，在 JavaScript 中，可以操纵 DOM 节点来更改其样式，内容，在文档中的位置或通过事件侦听器进行交互。

#### 很高兴听到

* DOM 被设计为独立于任何特定的编程语言，从而使文档的结构表示可从单个一致的 API 获得。
* DOM 是在页面加载时在浏览器中逐步构建的，这就是为什么脚本通常位于页面底部，具有 `defer` 属性的 `<head>` 中或 `DOMContentLoaded` 事件侦听器内部的原因。
  应该在构造 DOM 之后运行操纵 DOM 节点的脚本，以避免错误。
* `document.getElementById()` 和 `document.querySelector()` 是用于选择 DOM 节点的常用函数。
* 将 `innerHTML` 属性设置为新值将通过 HTML 解析器运行字符串，从而提供了一种将动态 HTML 内容附加到节点的简便方法。

##### 附加链接

* [MDN docs for DOM](https://developer.mozilla.org/en-US/docs/DOM)

</details>



<br>[⬆ 回到顶部](#目录)
### 运算符 `==` 和 `===` 有什么区别？

<details>
<summary>查看答案</summary>

三重等于（===）检查严格相等，这意味着类型和值必须相同。
另一方面，双等于（==）首先执行类型强制，以使两个操作数属于同一类型，然后应用严格比较。

#### 很高兴听到

* 只要有可能，请使用三重等于测试相等性，因为宽松等于 == 可能会产生不直观的结果。
* 类型强制表示将值转换为相同类型。
* 提及虚假的价值观及其比较。

##### 附加链接

* [MDN docs for comparison operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators)

</details>



<br>[⬆ 回到顶部](#目录)
### React 中 element 和 component 有什么区别？

<details>
<summary>查看答案</summary>

元素是表示DOM节点或组件的普通 JavaScript 对象。元素是纯净的，永不变异，而且创建起来很轻量。

组件是函数或类。组件可以具有状态并以 props 作为输入，而可以将元素树作为输出（
尽管它们可以表示通用容器或包装器，而不必发出 DOM）。
组件可能会在生命周期方法中引发副作用（例如 AJAX 请求，DOM 突变，与第三方库的接口），
并且创建起来可能会很昂贵。

```jsx
const Component = () => "Hello"
const componentElement = <Component />
const domNodeElement = <div />
```

#### 很高兴听到

* 元素是不可变的普通对象，用于描述您要呈现的DOM节点或组件。
* 组件可以是类或函数，它们以 props 作为输入，并返回一个元素树作为输出。

##### 附加链接

* [React docs on Rendering Elements](https://reactjs.org/docs/rendering-elements.html)
* [React docs on Components and Props](https://reactjs.org/docs/components-and-props.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是事件委派？为什么有用？请举例说明如何使用？

<details>
<summary>查看答案</summary>

事件委托是一种将事件委派给单个共同祖先的技术。
由于事件冒泡，事件通过在每个祖先元素上逐步执行任何处理程序直至可能正在侦听它的根，从而在 DOM 树上“冒泡”。

DOM 事件提供有关通过 `Event.target` 发起事件的元素的有用信息。
这允许父元素处理行为，就好像目标元素正在侦听事件一样，而不是父元素的所有子元素或父元素本身。

这提供了两个主要好处：

* 它只需要注册一个事件侦听器来处理潜在的数千个元素，即可提高性能并减少内存消耗。
* 如果将元素动态添加到父元素，则无需为其注册新的事件侦听器。

代替：

```js
document.querySelectorAll("button").forEach(button => {
  button.addEventListener("click", handleButtonClick)
})
```

事件委托涉及使用条件来确保子目标匹配我们所需的元素：

```js
document.addEventListener("click", e => {
  if (e.target.closest("button")) {
    handleButtonClick()
  }
})
```

#### 很高兴听到

* 事件冒泡和捕获之间的区别

##### 附加链接

* [Event Delegation](https://davidwalsh.name/event-delegate)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是事件驱动编程？

<details>
<summary>查看答案</summary>

事件驱动的编程是一种范式，涉及构建发送和接收事件的应用程序。
当程序发出事件时，程序将通过运行注册到该事件和上下文的任何回调函数进行响应，并将相关数据传递给该函数。
使用这种模式，即使没有订阅任何功能，事件也可以被释放而不会引发错误。

一个常见的示例是侦听DOM事件（例如 `click` 和 `mouseenter`）的元素模式，其中在事件发生时运行回调函数。

```js
document.addEventListener("click", function(event) {
  // This callback function is run when the user
  // clicks on the document.
})
```

如果没有 DOM 上下文，则模式可能如下所示：

```js
const hub = createEventHub()
hub.on("message", function(data) {
  console.log(`${data.username} said ${data.text}`)
})
hub.emit("message", {
  username: "John",
  text: "Hello?"
})
```

通过此实现，on 是预订事件的方式，而 send 是发布事件的方式。

#### 很高兴听到

* 遵循发布-订阅模式。
* 通过运行预订该事件的任何回调函数来响应发生的事件。
* 展示如何使用 JavaScript 创建简单的 `pub-sub` 实现。

##### 附加链接

* [MDN docs on Events and Handlers](https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Overview_of_Events_and_Handlers)
* [Understanding Node.js event-driven architecture](https://medium.freecodecamp.org/understanding-node-js-event-driven-architecture-223292fcbc2d)

</details>



<br>[⬆ 回到顶部](#目录)
### JavaScript 中的表达式和语句有什么区别？

<details>
<summary>查看答案</summary>

JavaScript中有两个主要的语法类别：表达式和语句。
第三个是在一起，称为表达式语句。
它们大致概括为：

* 表达式(Expression)：产生一个值
* 声明(Statement)：执行一个动作
* 表达式语句(Expression statement)：产生一个值并执行一个动作

一般经验法则：

> 如果您可以打印它或将其分配给变量，则它是一个表达式。如果不能的话，那就是声明。

##### 表达式(Expressions)

表达式产生一个值。可以将它们传递给函数，因为解释器将它们替换为要解析的值。

```js
5 + 5 // => 10

lastCharacter("input") // => "t"

true === true // => true
```


##### 声明(Statements)

```js
let x = 0

function declaration() {}

if (true) {
}
```

语句显示为可以执行某些操作但不会产生值的指令。

```js
// 将x分配给y的绝对值。
var x
if (y >= 0) {
  x = y
} else {
  x = -y
}
```

上面的代码中唯一的表达式是 `y >= 0`，它产生一个值为 `true` 或 `false` 的值。
代码的其他部分不会产生值。


##### 表达式语句(Expression statements)

之前使用条件运算符作为表达式的语句集具有等效版本：

```js
// 将 “x” 指定为 “y” 的绝对值。
var x = y >= 0 ? y : -y
```

这既是表达式又是语句，因为我们将变量 x（声明）声明为评估（表达式）。

#### 很高兴听到

* 函数声明与函数表达式

##### 附加链接

* [What is the difference between a statement and an expression?](https://stackoverflow.com/questions/12703214/javascript-difference-between-a-statement-and-an-expression)

</details>



<br>[⬆ 回到顶部](#目录)
### JavaScript 中真假值是什么？

<details>
<summary>查看答案</summary>

值是真实的还是虚假的，具体取决于在布尔上下文中如何对其求值。虚假代表虚假，真实代表虚假。
本质上，它们是在执行某些操作时被强制为 `true` 或 `false` 的值。

JavaScript 中有 6 个伪造的值。他们是：

* `false`
* `undefined`
* `null`
* `''` (空字符串)
* `NaN`
* `0` (包含 `+0` 和 `-0`)

其他所有值都被认为是真实的。

可以通过将值传递给 `Boolean` 函数来检查其真实性。

```js
Boolean("") // false
Boolean([]) // true
```

有一个使用逻辑 NOT 的快捷方式 `!` 操作符。
使用 `!` 一旦将值转换为其反布尔等效值（即 not false 为 true），并且 `!`
再次将转换回去，从而有效地将值转换为布尔值。

```js
!!"" // false
!![] // true
```

#### 很高兴听到

##### 附加链接

* [Truthy on MDN](https://developer.mozilla.org/en/docs/Glossary/Truthy)
* [Falsy on MDN](https://developer.mozilla.org/en-US/docs/Glossary/Falsy)

</details>



<br>[⬆ 回到顶部](#目录)
### 生成一个包含斐波那契序列的数组，直到第 n 个项。

<details>
<summary>查看答案</summary>

初始化一个长度为 `n` 的空数组。
使用 `Array.prototype.reduce（）` 将值添加到数组中，使用前两个值（前两个值除外）的和。

```js
const fibonacci = n =>
  [...Array(n)].reduce(
    (acc, val, i) => acc.concat(i > 1 ? acc[i - 1] + acc[i - 2] : i),
    []
  )
```

#### 很高兴听到

##### 附加链接

* [Similar problem](https://github.com/Chalarangelo/30-seconds-of-code/blob/master/snippets_archive/fibonacciUntilNum.md)

</details>



<br>[⬆ 回到顶部](#目录)
### `0.1 + 0.2 === 0.3` 的结果是什么？

<details>
<summary>查看答案</summary>

因为 JavaScript 使用 Math 的 IEEE 754 标准并且使用 64 位浮点数，所以它的值为 false。
简而言之，这会导致精度错误，这是由于计算机在 Base 2 中工作而十进制是 Base 10。

```js
0.1 + 0.2 // 0.30000000000000004
```

解决此问题的方法是使用一个函数，该函数通过定义两个值之间的差应小于的误差幅度（ε）值来确定两个数是否近似相等。

```js
const approxEqual = (n1, n2, epsilon = 0.0001) => Math.abs(n1 - n2) < epsilon
approxEqual(0.1 + 0.2, 0.3) // true
```

#### 很高兴听到

* 这个问题的简单解决方案

##### 附加链接

* [A simple helper function to check equality](https://github.com/Chalarangelo/30-seconds-of-code#approximatelyequal)
* [Fix "0.1 + 0.2 = 0.300000004" in JavaScript](http://blog.blakesimpson.co.uk/read/61-fix-0-1-0-2-0-300000004-in-javascript)

</details>



<br>[⬆ 回到顶部](#目录)
### 数组方法 `map()` 和 `forEach()` 有什么区别？

<details>
<summary>查看答案</summary>

两种方法都遍历数组的元素。`map()` 通过在每个元素上调用回调函数并返回一个新数组，
将每个元素映射到一个新元素。另一方面，`forEach()` 为每个元素调用回调函数，但不返回新数组。
当在每次迭代中引起副作用时，通常使用 `forEach()`，而 `map()` 是一种常见的函数编程技术。

#### 很高兴听到

* 如果您需要遍历数组并导致元素突变而无需返回值以生成新数组，请使用 `forEach()`。
* 如果原始数组的每个值都映射到新数组，则 `map()` 是保持数据不变的正确选择。

##### 附加链接

* [MDN docs for forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
* [MDN docs for map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* [JavaScript — Map vs. ForEach](https://codeburst.io/javascript-map-vs-foreach-f38111822c0f)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 fragments？

<details>
<summary>查看答案</summary>

Fragments 通过对子项进行分组而无需向 DOM 添加额外的元素，从而使 React 组件无需包装即可返回多个元素。
片段可提供更好的性能，更低的内存使用量，更整洁的 DOM，并可帮助处理某些 CSS 机制（例如表格，Flexbox 和 Grid）。

```jsx
render() {
  return (
    <React.Fragment>
      <ChildA />
      <ChildB />
      <ChildC />
    </React.Fragment>
  );
}

// Babel 7支持的短语法
render() {
  return (
    <>
      <ChildA />
      <ChildB />
      <ChildC />
    </>
  );
}
```

#### 很高兴听到

* 片段对从组件返回的多个元素进行分组，而不在其周围添加 DOM 元素。

##### 附加链接

* [React docs on Fragments](https://reactjs.org/docs/fragments.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是函数式编程？

<details>
<summary>查看答案</summary>

函数式编程是一种范例，其中使用避免共享状态和可变数据的纯函数以声明的方式构建程序。
对于相同的输入始终返回相同值且不会产生副作用的函数是函数式编程的基础。
许多程序员认为这是软件开发的最佳方法，因为它减少了错误和认知负担。

#### 很高兴听到

* 更清洁，更简洁的开发经验
* 简单的功能组成
* 支持功能性编程（`.map`，`.reduce` 等）的 JavaScript 功能
* JavaScript 是多范式编程语言（面向对象的编程和函数式编程融为一体）

##### 附加链接

* [Javascript and Functional Programming: An Introduction](https://hackernoon.com/javascript-and-functional-programming-an-introduction-286aa625e26d)
* [Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)

</details>



<br>[⬆ 回到顶部](#目录)
### 在此示例中控制台将输出什么？

```js
var foo = 1
var foobar = function() {
  console.log(foo)
  var foo = 2
}
foobar()
```

<details>
<summary>查看答案</summary>

由于提升，将在调用 `console.log` 方法之前声明局部变量 `foo`。
这意味着将局部变量 `foo` 作为参数传递给 `console.log()`，而不是在函数外部声明的全局变量。
但是，由于该值未随变量声明悬挂，因此输出将是 `undefined`，而不是 `2`。

#### 很高兴听到

* 提升 JavaScript 将声明移到顶部的默认行为
* 提到 `strict` 模式

##### 附加链接

* [MDN docs for hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)

</details>



<br>[⬆ 回到顶部](#目录)
### 提升如何在 JavaScript 中工作？

<details>
<summary>查看答案</summary>

提升是一种 JavaScript 机制，其中在编译阶段将变量和函数的声明放入内存中。
这意味着无论在何处声明函数和变量，无论它们的作用域是全局的还是局部的，它们都将移至其作用域的顶部。

但是，该值不随声明一起使用。

以下代码段：

```js
console.log(hoist)
var hoist = "value"
```

等效于：

```js
var hoist
console.log(hoist)
hoist = "value"
```

因此，记录 `hoist` 的输出 `undefined` 到控制台，而不是 `“value”`。

提升还允许您在函数声明在程序中似乎被声明之前调用它。

```js
myFunction()  // No error; logs "hello"
function myFunction() {
  console.log("hello")
}
```

但是要警惕分配给变量的函数表达式：

```js
myFunction() // Error: `myFunction` is not a function
var myFunction = function() {
  console.log("hello")
}
```

#### 很高兴听到

* 提升是 JavaScript 将声明移到顶部的默认行为
* 函数声明先于变量声明

##### 附加链接

* [MDN docs for hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
* [Understanding Hoisting in JavaScript](https://scotch.io/tutorials/understanding-hoisting-in-javascript)

</details>



<br>[⬆ 回到顶部](#目录)
### HTML 和 React 事件处理之间有什么区别？

<details>
<summary>查看答案</summary>

在 HTML 中，属性名称全部使用小写字母，并为字符串提供了调用某个地方定义的函数的字符串：

```html
<button onclick="handleClick()"></button>
```

在 React 中，属性名称为 camelCase 并在花括号内传递了函数引用：

```jsx
<button onClick={handleClick} />
```

在 HTML 中，可以返回 `false` 来防止默认行为，而在 React 中，必须显式调用 `preventDefault`。

```html
<a href="#" onclick="console.log('The link was clicked.'); return false" />
```
```js
function handleClick(e) {
  e.preventDefault()
  console.log("The link was clicked.")
}
```


#### 很高兴听到

* HTML 使用小写字母，React 使用 camelCase。

##### 附加链接

* [React docs on Handling Events](https://reactjs.org/docs/handling-events.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 将 JavaScript 源文件的全部内容包装在立即调用的函数中的原因是什么？

<details>
<summary>查看答案</summary>

此技术在 JavaScript 库中非常常见。
它围绕文件的所有内容创建了一个闭包，从而创建了一个私有的命名空间，从而帮助避免了不同 JavaScript 模块和库之间潜在的名称冲突。
立即调用该函数，以便为命名空间（库名）分配函数的返回值。

```js
const myLibrary = (function() {
  var privateVariable = 2
  return {
    publicMethod: () => privateVariable
  }
})()
privateVariable // ReferenceError
myLibrary.publicMethod() // 2
```

#### 很高兴听到

* 在许多流行的 JavaScript 库中使用
* 创建一个私有名称空间

##### 附加链接

* [MDN docs for closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

</details>



<br>[⬆ 回到顶部](#目录)
### 解释命令式和声明式编程之间的区别。

<details>
<summary>查看答案</summary>

这两种编程类型可以大致概括为：

* 解释命令式(Imperative): 如何实现目标
* 声明式(Declarative): 应该实现什么

声明式编程的一个常见示例是 CSS。开发人员指定 CSS 属性来描述外观，而不是如何实现。浏览器将 “how” 抽象化。

另一方面，命令式编程涉及实现某些目标所需的步骤。在 JavaScript 中，可以将差异进行对比，如下所示：

解释命令式(Imperative)

```js
const numbers = [1, 2, 3, 4, 5]
const numbersDoubled = []
for (let i = 0; i < numbers.length; i++) {
  numbersDoubled[i] = numbers[i] * 2
}
```

我们手动遍历数组的数字，并在数字翻倍时分配新的索引。

声明式(Declarative)

```js
const numbers = [1, 2, 3, 4, 5]
const numbersDoubled = numbers.map(n => n * 2)
```

我们声明将新数组映射到一个新数组，其中每个值都加倍。


#### 很高兴听到

* 声明式编程通常与函数和表达式一起使用。
  命令式编程经常使用语句，并依赖于导致突变的低级功能，而声明式编程则非常注重抽象和纯净性。
* 声明式编程更加简洁，一目了然。

##### 附加链接

* [Declarative vs Imperative Programming](https://codeburst.io/declarative-vs-imperative-programming-a8a7c93d9ad2)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是内联条件表达式？

<details>
<summary>查看答案</summary>

由于 JSX 元素树是一个大表达式，因此您不能在其中嵌入语句。条件表达式可以代替在树中使用的语句。

例如，这将不起作用：

```jsx
function App({ messages, isVisible }) {
  return (
    <div>
      if (messages.length > 0) {
        <h2>You have {messages.length} unread messages.</h2>
      } else {
        <h2>You have no unread messages.</h2>
      }
      if (isVisible) {
        <p>I am visible.</p>
      }
    </div>
  )
}
```

逻辑 AND `&&` 和三进制 `? :` 运算符替换 `if` / `else` 语句。

```jsx
function App({ messages, isVisible }) {
  return (
    <div>
      {messages.length > 0 ? (
        <h2>You have {messages.length} unread messages.</h2>
      ) : (
        <h2>You have no unread messages.</h2>
      )}
      {isVisible && <p>I am visible.</p>}
    </div>
  )
}
```

#### 很高兴听到

##### 附加链接

* [React docs on Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 key，在列表中使用它有什么好处？

<details>
<summary>查看答案</summary>

Keys 是一个特殊的字符串属性，可帮助 React 识别哪些项目已被更改，添加或移除。
在渲染数组元素以使其具有稳定的标识时使用它们。
每个元素的键都必须是唯一的（例如，数据的 ID 或索引是万不得已的）。

```jsx
const todoItems = todos.map(todo => <li key={todo.id}>{todo.text}</li>)
```

* 如果项目的顺序可能更改，则不建议将索引用作键，因为这可能会对性能产生负面影响，并可能导致组件状态出现问题。
* 如果将列表项提取为单独的组件，则将键应用于列表组件而不是 `<li>` 标记。

#### 很高兴听到

* 键使集合中的元素具有稳定的标识，并帮助React识别更改。
* 如果项目的顺序可能更改，则应避免将索引用作键。
* 如果您将列表项提取为组件，则应将键提升到组件而不是 `<li>` 元素。

##### 附加链接

* [React docs on Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 词汇作用域和动态作用域有什么区别？

<details>
<summary>查看答案</summary>

词法作用域是指函数定义的位置确定您有权访问的变量。
另一方面，动态作用域使用函数调用的位置来确定哪些变量可用。


#### 很高兴听到

* 词法作用域也称为静态作用域。
* JavaScript 中的词法作用域支持闭包的概念。
* 大多数语言都使用词法作用域，因为它倾向于推广更容易理解的源代码。

##### 附加链接

* [Mozilla Docs Closures & Lexical Scoping](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

</details>



<br>[⬆ 回到顶部](#目录)
### 创建一个函数，该函数用 # 掩盖一串字符最后四个字符除外。

```js
mask("123456789") // "#####6789"
```

<details>
<summary>查看答案</summary>

> 解决此问题的方法有很多，这只是其中之一。

使用 `String.prototype.slice()`，我们可以通过传递 `-4` 作为参数来捕获字符串的最后 4 个字符。
然后，使用 `String.prototype.padStart()`，我们可以使用重复的掩码字符将字符串填充到原始长度。

```js
const mask = (str, maskChar = "#") => str.slice(-4).padStart(str.length, maskChar)
```

#### 很高兴听到

* 如果问题是有效的，则应首选简短的一线功能性解决方案

##### 附加链接

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是记忆化？

<details>
<summary>查看答案</summary>

记忆化是对函数调用的输出进行缓存以使后续调用更快的过程。
使用相同的输入再次调用该函数将返回缓存的输出，而无需再次进行计算。

JavaScript 的基本实现如下所示：

```js
const memoize = fn => {
  const cache = new Map()
  return value => {
    const cachedResult = cache.get(value)
    if (cachedResult !== undefined) return cachedResult
    const result = fn(value)
    cache.set(value, result)
    return result
  }
}
```

#### 很高兴听到

* 即使该函数可以接受多个参数，上述技术也会返回一元函数。
* 由于调用缓存的结果是否存在并在返回值之前设置结果会产生开销，因此第一个函数调用的速度将比平时慢。
* 记忆化可提高后续函数调用的性能，但仍需要在第一次调用时进行工作。

##### 附加链接

* [Implementing memoization in JavaScript](https://www.sitepoint.com/implementing-memoization-in-javascript/)

</details>



<br>[⬆ 回到顶部](#目录)
### 如何确保方法在 React 组件类中 `this` 具有正确的上下文？

<details>
<summary>查看答案</summary>

在 JavaScript 类中，默认情况下不绑定方法。
这意味着可以更改其上下文（对于事件处理程序，可以更改为正在侦听事件的元素），并且不会引用组件实例。
为了解决这个问题，可以使用 `Function.prototype.bind()` 将 `this` 上下文强制为组件实例。

```jsx
constructor(props) {
  super(props);
  this.handleClick = this.handleClick.bind(this);
}

handleClick() {
  // Perform some logic
}
```

* `bind` 方法可能很冗长，并且需要定义一个构造函数，因此通常首选新的公共类字段语法：

```jsx
handleClick = () => {
  console.log('this is:', this);
}

render() {
  return (
    <button onClick={this.handleClick}>
      Click me
    </button>
  );
}
```

* 您还可以使用内联箭头功能，因为保留了词法此（指组件实例）：

```jsx
<button onClick={e => this.handleClick(e)}>Click me</button>
```

请注意，使用此技术可能会产生额外的重新渲染，因为在渲染上会创建一个新的函数引用，
该函数引用会传递给子组件，并会破坏 `shouldComponentUpdate` / `PureComponent` 浅层相等性检查，
以防止不必要的重新渲染。在性能很重要的情况下，最好在构造函数中使用 `bind`，
或者使用公共类字段语法方法，因为函数引用保持不变。

#### 很高兴听到

* 您可以将方法绑定到构造函数中的组件实例上下文，可以使用公共类字段语法，也可以使用嵌入式箭头函数。

##### 附加链接

* [React docs on Handling Events](https://reactjs.org/docs/handling-events.html)
* [React docs on Passing Functions to Components](https://reactjs.org/docs/faq-functions.html#how-do-i-bind-a-function-to-a-component-instance)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 MIME 类型？它的用途是什么？

<details>
<summary>查看答案</summary>

`MIME` 是多功能 Internet 邮件扩展(`Multi-purpose Internet Mail Extensions`)的首字母缩写。
它用作 Internet 上对文件类型进行分类的标准方法。

#### 很高兴听到

* 一个 `MIME type` 实际上包含两部分：类型和子类型，由斜杠（/）分隔。
  例如，Microsoft Word 文件的 `MIME type` 为 `application/msword`（即 type 为 application 而子类型为 msword）。

##### 附加链接

* [MIME Type MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types)

</details>



<br>[⬆ 回到顶部](#目录)
### 对比可变值和不可变值，变异与非变异方法。

<details>
<summary>查看答案</summary>

这两个术语可以对比为：

* 可变(Mutable)：可调整的
* 不可变(Immutable)：不能改变

在 JavaScript 中，对象是可变的，而原始值是不可变的。
这意味着对对象执行的操作可以某种方式更改原始参考，而对原始值执行的操作则无法更改原始值。

所有 `String.prototype` 方法对原始字符串均无效，并返回新的字符串。
另一方面，虽然 `Array.prototype` 的某些方法不会使原始数组引用发生突变并产生新的数组，但某些方法会引起突变。

```js
const myString = "hello!"
myString.replace("!", "") // returns a new string, cannot mutate the original value

const originalArray = [1, 2, 3]
originalArray.push(4) // mutates originalArray, now [1, 2, 3, 4]
originalArray.concat(4) // returns a new array, does not mutate the original
```

#### 很高兴听到

* 可变和不可变数组方法列表

##### 附加链接

* [Mutating vs non-mutating array methods](https://lorenstewart.me/2017/01/22/javascript-array-methods-mutating-vs-non-mutating/)

</details>



<br>[⬆ 回到顶部](#目录)
### 在 JavaScript 中唯一不等于自身的值是什么？

<details>
<summary>查看答案</summary>

与任何比较运算符进行比较时，`NaN`（非数字）是唯一不等于其自身的值。
`NaN` 通常是无意义的数学计算的结果，因此将两个 `NaN` 值视为相等是没有意义的。

#### 很高兴听到

* `isNaN()` 和 `Number.isNaN()` 之间的区别
* `const isNaN = x => x !== x`

##### 附加链接

* [MDN docs for NaN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN)

</details>



<br>[⬆ 回到顶部](#目录)
### NodeJS 经常使用回调模式，如果执行过程中遇到错误，此错误将作为第一个参数传递给回调。这种模式有什么优势？

```js
fs.readFile(filePath, function(err, data) {
  if (err) {
    // handle the error, the return is important here
    // so execution stops here
    return console.log(err)
  }
  // use the data object
  console.log(data)
})
```

<details>
<summary>查看答案</summary>

优势包括：

* 如果甚至不需要引用数据就不需要处理数据
* 拥有一致的 API 会导致更多采用
* 轻松适应回调模式的能力，这将导致更易于维护的代码

从下面的示例中可以看到，如果没有错误，则以 `null` 作为第一个参数调用回调。
但是，如果发生错误，则创建一个 Error 对象，该对象随后成为回调的唯一参数。
回调功能使用户可以轻松地知道是否发生错误。

这种做法也称为 Node.js 错误约定，这种回调实现称为错误优先回调。

```js
var isTrue = function(value, callback) {
  if (value === true) {
    callback(null, "Value was true.")
  } else {
    callback(new Error("Value is not true!"))
  }
}

var callback = function(error, retval) {
  if (error) {
    console.log(error)
    return
  }
  console.log(retval)
}

isTrue(false, callback)
isTrue(true, callback)

/*
  { stack: [Getter/Setter],
    arguments: undefined,
    type: undefined,
    message: 'Value is not true!' }
  Value was true.
*/
```

#### 很高兴听到

* 这只是一个约定。但是您应该坚持下去。

##### 附加链接

* [The Node.js Way Understanding Error-First Callbacks](http://fredkschott.com/post/2014/03/understanding-error-first-callbacks-in-node-js/)
* [What are the error conventions?](https://docs.nodejitsu.com/articles/errors/what-are-the-error-conventions)

</details>



<br>[⬆ 回到顶部](#目录)
### Node.js 中的事件循环是什么？

<details>
<summary>查看答案</summary>

事件循环处理所有异步回调。
回调在循环中排队，而其他代码在运行，并且在收到每个回调的响应时将一个接一个地运行。

#### 很高兴听到

* 事件循环允许Node.js执行非阻塞I / O操作，尽管JavaScript是单线程的

##### 附加链接

* [Node.js docs on event loop, timers and process.nextTick()](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)

</details>



<br>[⬆ 回到顶部](#目录)
### `null` 和 `undefined` 有什么区别？

<details>
<summary>查看答案</summary>

在 JavaScript 中，两个值离散地代表什么 - `undefined` 和 `null`。
它们之间的具体区别是 `null` 是显式的，而 `undefined` 是隐式的。
当属性不存在或未给变量赋值时，该值是不确定的。
将 `null` 设置为明确表示“无值”的值。
本质上，在什么都不知道的情况下使用 `undefined`，在什么都不知道的情况下使用 `null`。

#### 很高兴听到

* `typeof undefined` 的输出结果为 `“undefined”`。
* `typeof null` 输出结果为 `“object”`。但是，它仍然是原始值，在 JavaScript 中被视为实现错误。
* `undefined == null` 输出结果为 `true`。

##### 附加链接

* [MDN docs for null](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null)
* [MDN docs for undefined](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)

</details>



<br>[⬆ 回到顶部](#目录)
### 描述创建对象的不同方法。什么时候应该首选某些方法？

<details>
<summary>查看答案</summary>

##### 简单对象

通常用于存储一次数据。

```js
const person = {
  name: "John",
  age: 50,
  birthday() {
    this.age++
  }
}
person.birthday() // person.age === 51
```

##### 构造函数

通常在需要创建一个对象的多个实例时使用，每个实例都具有自己的数据，而该数据不会受到该类的其他实例的影响。
在调用构造函数之前必须使用 `new` 运算符，否则全局对象将发生突变。

```js
function Person(name, age) {
  this.name = name
  this.age = age
}
Person.prototype.birthday = function() {
  this.age++
}
const person1 = new Person("John", 50)
const person2 = new Person("Sally", 20)
person1.birthday() // person1.age === 51
person2.birthday() // person2.age === 21
```

##### 工厂函数

创建类似于构造函数的新对象，但可以使用闭包存储私有数据。
在调用函数或 `this` 关键字之前也不需要使用 `new`。
工厂函数通常会放弃原型的想法，并将所有属性和方法保留为对象的自身属性。

```js
const createPerson = (name, age) => {
  const birthday = () => person.age++
  const person = { name, age, birthday }
  return person
}
const person = createPerson("John", 50)
person.birthday() // person.age === 51
```

##### `Object.create()`

设置新创建对象的原型。

```js
const personProto = {
  birthday() {
    this.age++
  }
}
const person = Object.create(personProto)
person.age = 50
person.birthday() // person.age === 51
```

还可以向 `Object.create()` 提供第二个参数，该参数充当要定义的新属性的描述符。

```js
Object.create(personProto, {
  age: {
    value: 50,
    writable: true,
    enumerable: true
  }
})
```

#### 很高兴听到

* 原型是其他对象继承其属性和方法的对象。
* 工厂函数通过闭包提供私有属性和方法，但作为折衷方案增加了内存的使用，而类没有私有属性或方法，但是通过重用单个原型对象来减少对内存的影响。

##### 附加链接

</details>



<br>[⬆ 回到顶部](#目录)
### parameter 和 argument 有什么区别？

<details>
<summary>查看答案</summary>

Parameters 是函数定义的变量名，而 arguments 是调用函数时赋予函数的值。

```js
function myFunction(parameter1, parameter2) {
  console.log(arguments[0]) // "argument1"
}
myFunction("argument1", "argument2")
```

#### 很高兴听到

* `arguments` 是一个类似数组的对象，其中包含有关提供给调用函数的参数的信息。
* `myFunction.length` 描述函数的稀疏性（无论提供多少参数，它具有多少个参数）。

##### 附加链接

</details>



<br>[⬆ 回到顶部](#目录)
### JavaScript 是按值传递还是引用传递？

<details>
<summary>查看答案</summary>

JavaScript 总是按值传递。但是，对于对象，该值是对对象的引用。

#### 很高兴听到

* 值传递和引用传递之间的区别

##### 附加链接

* [JavaScript Value vs Reference](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18)

</details>



<br>[⬆ 回到顶部](#目录)
### 如何将参数传递给事件处理程序或者回调？

<details>
<summary>查看答案</summary>

您可以使用箭头函数来包装事件处理程序并传递参数，这等效于调用 `bind`：

```jsx
<button onClick={() => this.handleClick(id)} />
<button onClick={this.handleClick.bind(this, id)} />
```

#### 很高兴听到

##### 附加链接

* [React docs on Handling Events](https://reactjs.org/docs/handling-events.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 创建一个函数 `pipe`，该函数管道通过返回接受一个参数的函数来执行从左到右的函数编写。

```js
const square = v => v * v
const double = v => v * 2
const addOne = v => v + 1
const res = pipe(square, double, addOne)
res(3) // 19; addOne(double(square(3)))
```

<details>
<summary>查看答案</summary>

使用 rest 运算符收集所有提供的参数 `...`，并返回一元函数，该函数使用 `Array.prototype.reduce()` 在返回最终值之前，通过一系列函数运行该值。

```js
const pipe = (...fns) => x => fns.reduce((v, fn) => fn(v), x)
```

#### 很高兴听到

* 函数组合是将两个或多个函数组合以产生新函数的过程。

##### 附加链接

* [What is function composition?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-function-composition-20dfb109a1a0)

</details>



<br>[⬆ 回到顶部](#目录)
### React 中的 portals 是什么？

<details>
<summary>查看答案</summary>

建议使用 Portal 将子级呈现到父组件的 DOM 层次结构之外的 DOM 节点中。

```js
ReactDOM.createPortal(child, container)
```

第一个参数（`child`）是任何可渲染的 React 子级，例如元素，字符串或片段。
第二个参数（`container`）是一个 DOM 元素。

#### 很高兴听到

##### 附加链接

* [React docs on Portals](https://reactjs.org/docs/portals.html)

</details>



<br>[⬆ 回到顶部](#目录)
### `i++` 和 `++i` 运算符有什么区别？

<details>
<summary>查看答案</summary>

两者都将变量值加 1。差异是它们求和的结果。

后缀增量运算符将求值为增量之前的值。

```js
let i = 0
i++ // 0
// i === 1
```

前缀递增运算符将对值进行递增后求值。

```js
let i = 0
++i // 1
// i === 1
```

#### 很高兴听到

##### 附加链接

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 Promise？

<details>
<summary>查看答案</summary>

`Promise` 对象表示异步操作的最终完成（或失败）及其结果值。
下面的代码段就是一个示例，该代码段在 100ms 后将结果字符串打印到标准输出中。
另外，请注意可用于错误处理的陷阱。`Promise` 是可链式调用的。

```js
new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve("result")
  }, 100)
})
  .then(console.log)
  .catch(console.error)
```

#### 很高兴听到

* 查看有关 `Promise` 的其他问题！

##### 附加链接

* [Master the JavaScript Interview: What is a Promise?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e772618)

</details>



<br>[⬆ 回到顶部](#目录)
### Promise 可以在哪些状态下进行？

<details>
<summary>查看答案</summary>

`Promise` 处于以下状态之一：

* 待定(pending)：初始状态，既未完成也不被拒绝。
* 完成(fulfilled)：表示操作成功完成。
* 拒绝(rejected)：表示操作失败。

未完成的 promise 可以通过值来实现，也可以通过原因（错误）来拒绝。
这些选项中的任何一个发生时，都将调用由 promise 的 then 方法排队的关联处理程序。

#### 很高兴听到

##### 附加链接

* [Official Web Docs Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

</details>



<br>[⬆ 回到顶部](#目录)
### 原型继承和经典继承有何不同？

<details>
<summary>查看答案</summary>

在经典继承范例中，对象实例从类继承其属性和功能，该类充当对象的蓝图。
对象实例通常使用构造函数和 `new` 关键字创建。

在原型继承范例中，对象实例直接从其他对象继承，并且通常使用工厂函数或 `Object.create()` 创建。

#### 很高兴听到

##### 附加链接

* [MDN docs for inheritance and the prototype chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是纯函数？

<details>
<summary>查看答案</summary>

纯函数是满足以下两个条件的函数：

* 给定相同的输入，函数将返回相同的输出。
* 函数不会在函数范围之外引起副作用（即，对函数外部的数据进行突变或提供给函数的数据）。

只要满足上述两个条件，纯函数就可以对函数内的本地数据进行突变。

##### Pure

```js
const a = (x, y) => x + y
const b = (arr, value) => arr.concat(value)
const c = arr => [...arr].sort((a, b) => a - b)
```

##### Impure

```js
const a = (x, y) => x + y + Math.random()
const b = (arr, value) => (arr.push(value), arr)
const c = arr => arr.sort((a, b) => a - b)
```

#### 很高兴听到

* 纯函数由于其可靠性而更易于推论。
* 除非明确引起副作用，否则所有函数都应为纯函数（即 `setInnerHTML`）。
* 如果函数不返回值，则表明它正在引起副作用。

##### 附加链接

* [Pure functions in JavaScript](http://www.nicoespeon.com/en/2015/01/pure-functions-javascript/)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是递归？什么时候有用？

<details>
<summary>查看答案</summary>

递归是过程的重复应用。
在 JavaScript 中，递归涉及重复调用自己的函数，直到达到基本条件为止。
基本条件脱离了递归循环，因为否则该函数将无限期地调用自身。
当使用包含嵌套（深度级别未知）的数据结构时，递归非常有用。

例如，您可能有一个从数据库返回的注释线程，这些注释存在于平面数组中，但需要嵌套才能在 UI 中显示。
每个评论要么是顶级评论（无父），要么是对父评论的回复。
评论可以是回复的回复...我们事先不知道评论的层次数。
这是递归可以提供帮助的地方。

```js
const nest = (items, id = null, link = "parent_id") =>
  items
    .filter(item => item[link] === id)
    .map(item => ({ ...item, children: nest(items, item.id) }))

const comments = [
  { id: 1, parent_id: null, text: "First reply to post." },
  { id: 2, parent_id: 1, text: "First reply to comment #1." },
  { id: 3, parent_id: 1, text: "Second reply to comment #1." },
  { id: 4, parent_id: 3, text: "First reply to comment #3." },
  { id: 5, parent_id: 4, text: "First reply to comment #4." },
  { id: 6, parent_id: null, text: "Second reply to post." }
]

nest(comments)
/*
[
  { id: 1, parent_id: null, text: "First reply to post.", children: [...] },
  { id: 6, parent_id: null, text: "Second reply to post.", children: [] }
]
*/
```

在上面的示例中，如果 `filter()` 返回一个空数组，则满足基本条件。
链接的 `map()` 不会调用包含递归调用的回调函数，从而中断循环。

#### 很高兴听到

* 当使用包含未知数量的嵌套结构的数据结构时，递归非常有用。
* 递归必须满足一个打破循环的基本条件，否则它将无限期地调用自身。

##### 附加链接

* [In plain English, what is recursion?](https://softwareengineering.stackexchange.com/questions/25052/in-plain-english-what-is-recursion)

</details>



<br>[⬆ 回到顶部](#目录)
### 以下代码的输出是什么？

```js
const a = [1, 2, 3]
const b = [1, 2, 3]
const c = "1,2,3"

console.log(a == c)
console.log(a == b)
```

<details>
<summary>查看答案</summary>

第一个 `console.log` 输出 `true`，因为 JavaScript 的编译器执行类型转换，因此它通过字符串的值与字符串进行比较。
另一方面，第二个 `console.log` 输出 `false`，因为数组是对象，并且对象通过引用进行比较。

#### 很高兴听到

* JavaScript 执行自动类型转换
* 通过引用比较对象
* 比较原始值

##### 附加链接

* [JavaScript Value vs Reference](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18)

</details>



<br>[⬆ 回到顶部](#目录)
### React 中 refs 是什么？什么时候需要使用它们？

<details>
<summary>查看答案</summary>

Refs 提供了一种方法，可以访问在 render 方法中创建的 DOM 节点或 React 元素。
Refs 应该谨慎使用，但是有一些很好的 refs 用例，例如：

* 管理焦点，文本选择或媒体播放。
* 触发命令式动画。
* 与第三方 DOM 库集成。

使用 `React.createRef()` 方法创建 Refs，并通过 `ref` 属性将其附加到 React 元素。
为了在整个组件中使用 `ref`，请将 `ref` 分配给构造函数中的 instance 属性：

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props)
    this.myRef = React.createRef()
  }

  render() {
    return <div ref={this.myRef} />
  }
}
```

Refs 也可以在闭包的帮助下用于函数组件。

#### 很高兴听到

* Refs 用于返回对元素的引用。
* Refs 不应被过度使用。
* 您可以使用 `React.createRef()` 创建一个引用，并通过 `ref` 属性连接到元素。

##### 附加链接

* [React docs on Refs and the DOM](https://reactjs.org/docs/refs-and-the-dom.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 以下函数返回什么？

```js
function greet() {
  return
  {
    message: "hello"
  }
}
```

<details>
<summary>查看答案</summary>

由于 JavaScript 的自动分号插入（ASI），编译器将分号放在 `return` 关键字之后，因此它返回 `undefined` 且不会引发错误。

#### 很高兴听到

* 自动分号放置会导致耗时的错误

##### 附加链接

* [Automatic semicolon insertion in JavaScript](http://2ality.com/2011/05/semicolon-insertion.html)

</details>



<br>[⬆ 回到顶部](#目录)
### JavaScript 是否需要分号？

<details>
<summary>查看答案</summary>

有时。由于 JavaScript 自动插入分号，因此解释程序会将分号放在大多数语句之后。
这意味着在大多数情况下可以省略分号。

但是，在某些情况下需要使用它们。
在块的开头不需要它们，但是如果它们遵循一行并且：

1. 该行以 [ 开始

```js
const previousLine = 3
;[1, 2, previousLine].map(n => n * 2)
```

2. 该行以 ( 开始

```js
const previousLine = 3
;(function() {
  // ...
})()
```

在上述情况下，解释器不会在 3 之后插入分号，因此它将 3 视为尝试访问对象属性或作为函数调用，这将引发错误。

#### 很高兴听到

* 分号在 JavaScript 中通常是可选的，但在某些情况下需要使用分号。
* 如果您不使用分号，则 Prettier 之类的工具会在需要保存在文本编辑器中的地方插入分号，以防止错误。

##### 附加链接

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 JavaScript 中的短路评估？

<details>
<summary>查看答案</summary>

短路评估涉及从左到右评估并尽早停止的逻辑运算。

```js
true || false
```

在上述使用逻辑 OR 的示例中，JavaScript 不会将第二个操作数视为 `false`，因为无论如何表达式都将计算为 `true`。
这称为短路评估。

这也适用于逻辑 AND。

```js
false && true
```

这意味着您可以拥有一个表达式，如果对其求值，该表达式将引发错误，并且不会引起问题。

```js
true || nonexistentFunction()
false && nonexistentFunction()
```

由于从左到右的评估，对于多个操作来说仍然如此。

```js
true || nonexistentFunction() || window.nothing.wouldThrowError
true || window.nothing.wouldThrowError
true
```

此行为的常见用例是设置默认值。
如果第一个操作数为假，则将评估第二个操作数。

```js
const options = {}
const setting = options.setting || "default"
setting // "default"
```

另一个常见用例是仅在第一个操作数为真时才对表达式求值。

```js
// Instead of:
addEventListener("click", e => {
  if (e.target.closest("button")) {
    handleButtonClick(e)
  }
})

// You can take advantage of short-circuit evaluation:
addEventListener(
  "click",
  e => e.target.closest("button") && handleButtonClick(e)
)
```

在上述情况下，如果 `e.target` 不是或不包含与 `“button”` 选择器匹配的元素，则不会调用该函数。
这是因为第一个操作数将是错误的，从而导致第二个操作数不被执行。

#### 很高兴听到

* 除非操作数评估为布尔值，否则逻辑运算不会产生布尔值。

##### 附加链接

* [JavaScript: What is short-circuit evaluation?](https://codeburst.io/javascript-what-is-short-circuit-evaluation-ff22b2f5608c)

</details>



<br>[⬆ 回到顶部](#目录)
### React 中的有状态组件是什么？

<details>
<summary>查看答案</summary>

有状态组件是其行为取决于其状态的组件。
这意味着，与纯功能组件不同，如果给定相同的道具，则组件的两个单独实例不一定会呈现相同的输出。

```js
// Stateful class component
class App extends Component {
  constructor(props) {
    super(props)
    this.state = { count: 0 }
  }
  render() {
    // ...
  }
}

// Stateful function component
function App() {
  const [count, setCount] = useState(0)
  return // ...
}
```

#### 很高兴听到

* 有状态组件具有它们所依赖的内部状态。
* 有状态组件是使用有状态挂钩的类组件或功能组件。
* 有状态组件的状态在构造函数中或使用 `useState()`初始化。

##### 附加链接

* [React docs on State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是无状态组件？

<details>
<summary>查看答案</summary>

无状态组件是其行为不依赖于其状态的组件。
无状态组件可以是功能组件，也可以是类组件。
无状态功能组件易于维护和测试，因为在给定相同道具的情况下，它们可以保证产生相同的输出。
当不需要使用生命周期挂钩时，应首选无状态功能组件。

#### 很高兴听到

* 无状态组件独立于其状态。
* 无状态组件可以是类或功能组件。
* 无状态功能组件完全避免使用 `this` 关键字。

##### 附加链接

* [React docs on State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

</details>



<br>[⬆ 回到顶部](#目录)
### 解释静态方法和实例方法的区别。

<details>
<summary>查看答案</summary>

静态方法属于一个类，并且不作用于实例，而实例方法属于该类的原型，该原型由该类的所有实例继承并对其起作用。

```js
Array.isArray // static method of Array
Array.prototype.push // instance method of Array
```

在这种情况下，`Array.isArray` 方法作为数组的实例方法没有意义，因为我们已经知道使用该值是一个数组。

从技术上讲，实例方法可以用作静态方法，但是提供了更简短的语法：

```js
const arr = [1, 2, 3]
arr.push(4)
Array.push(arr, 4)
```

#### 很高兴听到

* 如何使用 ES2015 类语法创建静态方法和实例方法

##### 附加链接

* [Classes on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

</details>



<br>[⬆ 回到顶部](#目录)
### JavaScript 中的同步代码和异步代码有什么区别？

<details>
<summary>查看答案</summary>

同步意味着每个操作必须等待上一个操作完成。

异步是指一个操作可以在另一个操作仍在处理时发生。

在 JavaScript 中，由于其单线程性质，所有代码都是同步的。
但是，不属于程序一部分的异步操作（例如 XMLHttpRequest 或 setTimeout）在主线程之外进行处理，
因为它们由本机代码（浏览器 API）控制，但是程序的回调部分仍将同步执行。

#### 很高兴听到

* JavaScript 具有基于 “event loop” 的并发模型。
* 诸如 alert 之类的功能会阻塞主线程，以便在用户关闭主输入之前不会注册任何用户输入。

##### 附加链接

</details>



<br>[⬆ 回到顶部](#目录)
### `this` 关键字是什么？它如何工作？

<details>
<summary>查看答案</summary>

`this` 关键字是一个对象，代表执行函数的上下文。
常规函数可以使用方法 `call()`，`apply()` 和 `bind()` 更改其 `this` 值。
箭头函数隐式绑定了此对象，因此无论它的上下文是否使用 `call()` 进行了显式设置，它都引用其词法环境的上下文。

以下是一些有关其工作原理的常见示例：

##### 简单对象

如果对象在函数调用之前，则它是指对象本身在常规函数中。

设置为 `this` 属性不引用该对象。

```js
var myObject = {
  property: this,
  regularFunction: function() {
    return this
  },
  arrowFunction: () => {
    return this
  },
  iife: (function() {
    return this
  })()
}
myObject.regularFunction() // myObject
myObject["regularFunction"]() // my Object

myObject.property // NOT myObject; lexical `this`
myObject.arrowFunction() // NOT myObject; lexical `this`
myObject.iife // NOT myObject; lexical `this`
const regularFunction = myObject.regularFunction
regularFunction() // NOT myObject; lexical `this`
```

##### 事件监听器

`this` 是指侦听事件的元素。

```js
document.body.addEventListener("click", function() {
  console.log(this) // document.body
})
```


##### 构造函数

`this` 是指新创建的对象。

```js
class Example {
  constructor() {
    console.log(this) // myExample
  }
}
const myExample = new Example()
```

##### 手动

对于 `call()` 和 `apply()`，`this` 是指作为第一个参数传递的对象。

```js
var myFunction = function() {
  return this
}
myFunction.call({ customThis: true }) // { customThis: true }
```

##### 不需要 `this`

因为 `this` 可以根据范围而变化，所以在使用常规函数时它可能具有意外的值。

```js
var obj = {
  arr: [1, 2, 3],
  doubleArr() {
    return this.arr.map(function(value) {
      // this is now this.arr
      return this.double(value)
    })
  },
  double() {
    return value * 2
  }
}
obj.doubleArr() // Uncaught TypeError: this.double is not a function
```

#### 很高兴听到

* 在非严格模式下，global `this` 是全局对象（浏览器中的 `window`），而在严格模式下 global `this` 是 `undefined`。
* `Function.prototype.call` 和 `Function.prototype.apply` 将正在执行的函数的 `this` 上下文设置为第一个参数，随后call接受可变数量的参数，然后将接受的数组作为第二个参数应用到函数中易变的方式。
* `Function.prototype.bind` 返回一个新函数，该函数强制将此上下文作为第一个参数，其他函数无法更改。
* 如果函数要求根据调用方式更改其上下文，则必须使用 `function` 关键字。
  当您希望 `this` 成为环境的（词汇）上下文时，请使用箭头功能。

##### 附加链接

* [`this` on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)

</details>



<br>[⬆ 回到顶部](#目录)
### 以下代码的计算结果是什么？

```js
typeof typeof 0
```

<details>
<summary>查看答案</summary>

它的计算结果为 `"string"`

`typeof 0` 的计算结果是字符串 `“number”`，因此 `typeof “number”` 的计算结果为 `“string”`。

#### 很高兴听到

##### 附加链接

* [MDN docs for typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是 JavaScript 的数据类型？

<details>
<summary>查看答案</summary>

最新的 ECMAScript 标准定义了 7 种数据类型，其中 6 种是基本数据类型：`Boolean`，`Null`，`Undefined`，`Number`，`String`，`Symbol` 和一种非基本数据类型：`Object`。

#### 很高兴听到

* 提及新添加的 `Symbol` 数据类型
* `Array`， `Date` 和 `function` 都是对象类型
* JavaScript 中的函数是具有可调用功能的对象

##### 附加链接

* [MDN docs for data types and data structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
* [Understanding Data Types in JavaScript](https://www.digitalocean.com/community/tutorials/understanding-data-types-in-javascript)

</details>



<br>[⬆ 回到顶部](#目录)
### JavaScript UI库/框架，例如 React、Vue、Angular、Hyperapp 等的目的是什么？

<details>
<summary>查看答案</summary>

主要目的是避免直接操作 DOM，并使应用程序的状态轻松与 UI 保持同步。
另外，它们提供了创建具有相似功能但具有微小差异的组件时可以重用的功能，从而避免了在需要更新在多个位置重用的组件的结构时需要进行多次更改的重复。

当使用 jQuery 之类的 DOM 操作库时，应用程序的数据通常以类名或数据属性的形式保存在 DOM 本身中。
操纵 DOM 来更新 UI 涉及许多额外的步骤，并且随着时间的推移会引入细微的错误。
当状态改变时，保持状态分离并让框架处理 UI 更新可以减少认知负担。
说您要让 UI 在状态为某个值时看起来是某种方式，这是创建应用程序的声明方式，而不是手动更新 UI 以反映新状态的必要方式。

#### 很高兴听到

* 虚拟 DOM 以纯对象的形式表示真实 DOM 树，它允许库编写代码，就好像整个文档都被扔掉并根据每次更改重建一样，而真实 DOM 仅更新需要更改的内容。
  将新的虚拟 DOM 与先前的虚拟 DOM 进行比较可以提高效率，因为与重新计算虚拟 DOM 相比，更改实际 DOM 节点的成本很高。
* JSX 是 JavaScript 的扩展，它提供了类似于 XML 的语法来创建虚拟 DOM 对象，该对象被编译器转换为函数调用。
  与标记的模板文字相比，它简化了控制流（if 语句/三元表达式）。

##### 附加链接

* [Virtual DOM in Hyperapp](https://github.com/hyperapp/hyperapp#view)

</details>



<br>[⬆ 回到顶部](#目录)
### `use strict` 有什么作用，使用它有哪些好处？

<details>
<summary>查看答案</summary>

在 JavaScript 源文件的开头包含 `use strict`，将启用严格模式，该模式强制执行更严格的 JavaScript 代码解析和错误处理。
这被认为是一种很好的做法，并提供了很多好处，例如：

* 由于消除了无提示错误，因此调试更加容易。
* 禁止重新定义变量。
* 防止意外的全局变量。
* 通常，与未在严格模式下运行的相同代码相比，可以提高性能。
* 简化 `eval()` 和 `arguments`。
* 帮助使 JavaScript 更安全。

#### 很高兴听到

* 消除了 `this` 强制性，当它引用 `null` 或 `undefined` 值时抛出错误。
* 在 `delete` 的无效用法上引发错误。
* 禁止将来的 ECMAScript 版本中可能定义的某些语法

##### 附加链接

* [MDN docs for strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)

</details>



<br>[⬆ 回到顶部](#目录)
### `var`、`let`、`const` 和无关键字语句有什么区别？

<details>
<summary>查看答案</summary>

##### 无关键字

如果在变量分配之前不存在关键字，则它要么分配全局变量（如果不存在），要么重新分配已经声明的变量。
在非严格模式下，如果尚未声明变量，则它将变量分配为全局对象的属性（浏览器中的 `window`）。
在严格模式下，它将引发错误以防止创建不需要的全局变量。

##### var

`var` 是在 ES2015 之前声明变量的默认语句。
它创建了一个函数范围的变量，可以重新分配和重新声明它。
但是，由于缺少块作用域，如果在包含异步回调的循环中重用该变量，可能会引起问题，因为该变量将继续存在于块作用域之外。

下面，在执行 `setTimeout` 回调时，循环已经完成，并且 `i` 变量为 `10`，因此所有十个回调均引用函数范围中可用的同一变量。

```js
for (var i = 0; i < 10; i++) {
  setTimeout(() => {
    // logs `10` ten times
    console.log(i)
  })
}

/* Solutions with `var` */
for (var i = 0; i < 10; i++) {
  // Passed as an argument will use the value as-is in
  // that point in time
  setTimeout(console.log, 0, i)
}

for (var i = 0; i < 10; i++) {
  // Create a new function scope that will use the value
  // as-is in that point in time
  ;(i => {
    setTimeout(() => {
      console.log(i)
    })
  })(i)
}
```

##### let

`let` 是在 `ES2015` 中引入的，是声明变量的新的首选方法，该变量将在以后重新分配。
再次尝试重新声明变量将引发错误。
它是块作用域的，因此在循环中使用它将使它的作用域限于迭代。

```js
for (let i = 0; i < 10; i++) {
  setTimeout(() => {
    // logs 0, 1, 2, 3, ...
    console.log(i)
  })
}
```

##### const

`const` 是在 ES2015 中引入的，它是一种新的首选默认方式，用于声明所有变量（如果以后不会对其进行重新分配），即使对于那些将被突变的对象（只要对该对象的引用不变）也是如此。
它是块作用域的，无法重新分配。

```js
const myObject = {}
myObject.prop = "hello!" // No error
myObject = "hello" // Error
```

#### 很高兴听到

* 所有声明都放置在其作用域的顶部。
* 但是，对于 `let` 和 `const`，有一个概念称为时间盲区（TDZ）。
  虽然仍然悬挂着声明，但是在进入作用域和声明范围之间有一段期间，无法访问它们。
* 通过使用 `var` 展示一个常见问题，让我们来解决它，以及保留 `var` 的解决方案。
* 应该尽可能避免使用 `var`，并且最好将 `const` 作为所有变量的默认声明语句，除非稍后将它们重新分配，然后使用 `let`。

##### 附加链接

* [let vs const](https://wesbos.com/let-vs-const/)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是虚拟 DOM？为什么在库/框架中使用它？

<details>
<summary>查看答案</summary>

虚拟 DOM（VDOM）以纯 JavaScript 对象的形式表示真实 DOM。
这些对象具有描述它们所代表的实际 DOM 节点的属性：节点名称，其属性和子节点。

```html
<div class="counter">
  <h1>0</h1>
  <button>-</button>
  <button>+</button>
</div>
```

上面标记的虚拟 DOM 表示可能如下所示：

```json5
{
  nodeName: "div",
  attributes: { class: "counter" },
  children: [
    {
      nodeName: "h1",
      attributes: {},
      children: [0]
    },
    {
      nodeName: "button",
      attributes: {},
      children: ["-"]
    },
    {
      nodeName: "button",
      attributes: {},
      children: ["+"]
    }
  ]
}
```

库/框架使用虚拟 DOM 作为提高性能的手段。
当应用程序的状态发生变化时，实际的 DOM 需要更新以反映它。
但是，与重新计算虚拟 DOM 相比，更改实际 DOM 节点的开销很大。
通过比较，可以非常快速地将先前的虚拟 DOM 与新的虚拟 DOM 进行比较。

一旦框架的差异引擎已计算出旧的 VDOM 与新的 VDOM 之间的变化，便可以在最短的时间内高效地修补实际的 DOM，以匹配应用程序的新状态。

#### 很高兴听到

* 为什么访问 DOM 的成本可能很高。

##### 附加链接

* [The difference between Virtual DOM and DOM](http://reactkungfu.com/2015/10/the-difference-between-virtual-dom-and-dom/)

</details>



<br>[⬆ 回到顶部](#目录)
### 什么是跨站点脚本攻击(XSS)，如何防止它？

<details>
<summary>查看答案</summary>

XSS 是指客户端代码注入，其中，攻击者将恶意脚本注入到合法的网站或 Web 应用程序中。
当应用程序不验证用户输入并自由注入动态 HTML 内容时，通常可以实现此目的。

例如，如果评论系统未验证或逃避用户输入，则将面临风险。
如果注释包含未转义的 HTML，则注释可以将 `<script>` 标记注入网站，其他用户将根据他们的知识执行该标记。

* 恶意脚本可以访问 Cookie，这些 Cookie 通常用于存储会话令牌。
  如果攻击者可以获取用户的会话 Cookie，则他们可以冒充该用户。
* 该脚本可以任意操纵脚本在其中执行的页面的 DOM，从而使攻击者可以插入似乎是网站真正部分的内容。
* 该脚本可以使用 AJAX 将具有任意内容的 HTTP 请求发送到任意目标。

#### 很高兴听到

* 在客户端上，使用 textContent 而不是 innerHTML 可以防止浏览器通过将在其中执行脚本的 HTML 解析器运行字符串。
* 在服务器上，转义 HTML 标记将阻止浏览器将用户输入解析为实际 HTML，因此将不执行脚本。

##### 附加链接

* [Cross-Site Scripting Attack (XSS)](https://www.acunetix.com/websitesecurity/cross-site-scripting/)

</details>
