#如何避免回调地狱

###你可以有如下几个方法：

- 模块化：将回调函数分割为独立的函数
- 使用Promises
- 使用yield来计算生成器或Promise
- co yield 
- node8 async await
- async库


**解析：这个问题有很多种答案，取决你使用的场景，例如ES6, ES7，或者一些控制流库。**

#运算错误与程序员错误的区别

运算错误并不是bug，这是和系统相关的问题，例如请求超时或者硬件故障。而程序员错误就是所谓的bug。

**解析：这个题目和Node关系并不大，用于考察面试者的基础知识。**