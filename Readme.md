# The Third Day

### 使用RegExp对象
一个预定义了属性和方法的正则表达式对象    
`test()`-返回true  
`exec()`-用于检索字符串中正则表达式的匹配，返回数组存放匹配的结果，未找到返回`null`.  
### Javascript错误-throw，try和catch
`try语句`-测试代码块的错误     
`catch语句`-处理错误    
`throw语句`-创建自定义错误    
try和catch成对出现    
语法    
`try{
	...
}catch(err){
	
}`   
throw,try和catch一起使用能够控制程序流并生成自定义的错误信息    
### 调试 
设置断点  
#### debugger关键字
用于停止执行Javascript并调用调试函数，无调试函数debugger语句无法工作  
### Javascript变量提升
函数声明和变量声明总是会被解释器悄悄地提升到方法体的最顶部，初始化的变量不会被提升。
### 严格模式（"use strict"）
* 不允许使用未定义的变量
* 只运行出现在脚本或函数的开头    
### Javascript注意事项
* 对浮点型数据的精确度都是很难确定的 
* 字符串断行，使用反斜杠\
* 默认在最后一行自动结束
* 对象使用名字作为索引
* `null`用于对象，`undefined`用于变量，属性和方法。
* 对象只有被定义才有可能为`null`，否则为`undefined`，先检测对象是否已定义
* 一般各个代码块的作用域都是全局的
### 表单验证
HTML表单验证可以通过Javascript来完成。