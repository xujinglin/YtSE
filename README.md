# YtSE
YouTube subscribe extension
* highlight most interesting content, in your subscribe
* user can add keywords to filter content
* length of video to filter
* dim the uninteresting content or make it 50% transpatent

## 2017Dec06
今天被整了。。。permisions。。。不加权限就啥都不干。。。报错也不好好报。。。直接告诉我没权限不行么。。。还不能用optional_permission

## 2017Dec05
* 查找元素，id、标签、类
* navigator.cookieEnabled
* ```js
        var child=document.getElementById("p1");
        child.parentNode.removeChild(child);//傻X吗，打儿子还非得叫上爸爸
  ```
* js单线程运行，setTimeout()会开新进程放到等待队列，然后父线程继续执行到结束，所以不会无限嵌套下去  

看了几个例子，发现光看还不行，明天先把几个例子操练一遍

* bookmark-it 有background script监控网页情况改变图标
* notify-link-clicks-i18n 响应按钮点击

## 2017Dec04
Walked through first two example of firefox webextension. No code uploaded.  

* ```js
        //我发现这段代码的x没有用var声明，虽然在函数内部
        //soga, 向未声明的变量赋值，变量自动作为全局变量，页面关闭时释放
        x=document.getElementById("demo")
        x.innerHTML="Hello JavaScript";//check out what is this
  ```
* case sensitive, what language isn't?  
* 目前感觉基本兼容c/c++语法  
* 字符串的部分像python
* label used in switch...case... can be used in other place
