# es6面试题
> 鼓励PR，持续更新

## 历史题目
> 最新：2019.10.05

[es6](#es6) | [es7](#es7)

### es6
- [举例说明setImmediate有什么作用？]()
- [请分析如下promise执行的结果并解释原因[代码]]()
```javascript
console.log(1);
const promise = new Promise((resolve, reject) => {
  console.log(2)
  resolve()
  console.log(3)
})
promise.then(() => {
  console.log(4)
})
console.log(5)
```
- [es6对函数做了哪些优化？](https://github.com/haizlin/fe-interview/issues/1309)
- [说说你对async/await的理解？](https://github.com/haizlin/fe-interview/issues/1310)
- [Generator函数是什么？它有什么应用场景？](https://github.com/haizlin/fe-interview/issues/1319)
- [Object.is()和比较操作符"="的区别是什么？](https://github.com/haizlin/fe-interview/issues/1320)
- [说说你对Iterator的理解](https://github.com/haizlin/fe-interview/issues/1321)
- [Reflect是什么，有什么应用场景？](https://github.com/haizlin/fe-interview/issues/1322)
- [Proxy是什么，有什么应用场景？](https://github.com/haizlin/fe-interview/issues/1323)
- [es6对es5有哪些方面的优化呢？](https://github.com/haizlin/fe-interview/issues/1324)
- [举例说明你对es6的extends的理解](https://github.com/haizlin/fe-interview/issues/1325)
- [举例说明你对es6的class的理解](https://github.com/haizlin/fe-interview/issues/1326)
- [你喜欢es6的哪些特性？](https://github.com/haizlin/fe-interview/issues/1327)
- [举例说明拓展运算符有什么用途？](https://github.com/haizlin/fe-interview/issues/1328)
- [es6的模板字符串有什么新的特性？]()
- [使用es6怎么快速给一个数组去重？]()
- [TypedArray有什么应用场景？]()
- [Set和WeakSet有什么区别？]()
- [Map和WeakMap有什么区别？]()
- [如何让一个对象具有私有属性？]()
- [Symbol有什么作用？]()
- [for…of和for…in有什么区别？]()
- [es6新增了哪些数据类型？]()
- [说下var、let和const有什么区别？]()
- [使用箭头函数应该需要注意什么？]()
- [箭头函数与普通函数有什么区别？它有哪些新的特性？](https://github.com/haizlin/fe-interview/issues/1308)
- [let和const的区别是什么](https://github.com/haizlin/fe-interview/issues/1307)
- [说说你对set数据结构的理解](https://github.com/haizlin/fe-interview/issues/1306)
- [说说你对class的理解](https://github.com/haizlin/fe-interview/issues/1305)
- [es6函数的rest参数你有了解吗？](https://github.com/haizlin/fe-interview/issues/1304)
- [说说你对Babel的了解？](https://github.com/haizlin/fe-interview/issues/1303)
- [module、export、import分别有什么作用？](https://github.com/haizlin/fe-interview/issues/1302)
- [谈谈你对es6的module体系的理解](https://github.com/haizlin/fe-interview/issues/1301)

### es7
- [你知道es7新增了哪些新的特性吗？]()