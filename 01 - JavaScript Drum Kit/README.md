## 实现效果

按下键盘上的ASDFGHJKL这几个键，页面上对应的按钮变大变亮，同时响起对应的声音。

## 监听键盘事件

参考资料: JavaScript语言入门教程 09. 事件  - 阮一峰

可以使用addEventListener(type, listener, useCapture),绑定事件的监听函数。比如 `addEventListener('keydown', dosth(), false)` ：按下键盘会触发执行 `dosth()` 函数。

参数:
> type : 事件名称，大小写敏感。
> 
> listener : 监听函数。事件发生时，会调用该监听函数。
> 
> useCaption: 布尔值。 该参数可选，默认值为false。
>   - false : [默认值] 监听函数将在捕获阶段触发。
>   - true : 监听函数将在冒泡阶段被触发。


## 模板字符串

[地址](https://developer.mozilla.org/zh-CN/docs/web/javascript/reference/template_literals)

> 模板字面量 是允许嵌入表达式的字符串字面量。你可以使用多行字符串和字符串插值功能。它们在ES2015规范的先前版本中被称为“模板字符串”。

语法
```javascript
let x = '123';
let a = `abcd${x}`;
console.log(a);
// 输出
// abcd123
```
## 其他
[html5中的audio标签](https://blog.csdn.net/alongken2005/article/details/44569981/)

[querySelector()](https://www.runoob.com/jsref/met-element-queryselector.html)

[CSS3中的transition和transform](https://www.jianshu.com/p/80f6051389bd)