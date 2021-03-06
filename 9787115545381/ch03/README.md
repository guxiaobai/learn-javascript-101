# 第 3 章 语言基础

|本期版本| 上期版本
|:---:|:---:
`Mon Jan 17 23:29:40 CST 2022` |

## 3.3 变量

### 3.3.1 var 关键字

* 使用 var 操作符定义的变量会成为包含它的函数的局部变量
* 会自动提升到函数作用域顶部


### 3.3.2 let 声明

* `let` 声明的范围是块作用域， 而 `var` 声明的范围是函数作用域。
* `let` 也不允许同一个块作用域中出现冗余声明
* 就是 `let` 声明的变量不会在作用域中被提升
* 使用 let 在全局作用域中声明的变量不会成为 window 对象的属性

### 3.3.3 const 声明

* 用它声明变量时必须同时初始化变量，且 尝试修改 const 声明的变量会导致运行时错误。

## 3.4 数据类型

### 3.4.6  String 类型

**4. 模版字面量**

* 保留换行字符，可以跨行定义字符串

**5. 字符串插值**

* 模板字面量不是字符串，而是一种特殊的 JavaScript 句法表达式，只不过求值后得到的 是字符串
* 字符串插值通过在`${}`中使用一个 JavaScript 表达式实现

### 3.4.7 Symbol 类型 @TODO

* 符号是原始值，且符号实例是唯一、不可变的

**1. 符号的基本用法**

* 符号需要使用 `Symbol()` 函数初始化
* `Symbol()` 函数不能与 new 关键字一起作为构造函数使用

**2. 使用全局符号注册表**

* `Symbol.for()`
* 即使采用相同的符号描述，在全局注册表中定义的符号跟使用 Symbol()定义的符号也并不等同
* 还可以使用 Symbol.keyFor()来查询全局注册表

**3. 使用符号作为属性**

* 凡是可以使用字符串或数值作为属性的地方， 都可以使用符号




## Ref

* [HTML 5：你必须知道的data属性](https://segmentfault.com/a/1190000002445964)
