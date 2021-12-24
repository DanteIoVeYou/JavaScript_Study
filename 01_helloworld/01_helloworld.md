JavaScript

- 运行在客户端的脚本语言

- 不需要编译，运行过程中有js解释器逐行进行解释并执行
- 现在也可以基于Node.js技术进行服务器端编程



1-4.浏览器执行JS

浏览器分为两部分：

- 渲染引擎：解析HTML和CSS，俗称内核
- JS引擎：读取网页中的JS代码，对其处理后运行，也叫JS解释器。逐行解释，脚本语言



1-5.JS的组成

- ECMAScript：JS语法
- DOM：页面文档对象模型
- BOM：浏览器对象模型

1.6-JS初体验

3种书写位置

- 行内

  ```js
  <input type="button" value="123" onclick="alert('456')">
  ```

- 内嵌

  ```js
  <script>
  alert('123');
  </script>
  ```

- 外部

  test.js

  ```js
  alert('123');
  ```

  test.html

  ```js
  <script src="test.js"></script>
  ```

  

1.7-JS的注释

- 单行注释: ctrl /

  ```js
  // code
  ```

- 多行注释 ctrl shift a

  ```js
  /*code*/
  ```

1.8-JS中的输入输出语句

| prompt      | 用户输入框                   |
| ----------- | ---------------------------- |
| alert       | 弹出警示框                   |
| console.log | 程序员在控制台测试时候看到的 |

