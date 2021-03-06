title: 说说自己写PHP框架的一些感受
---
##个人感受

我以前觉得，造一个框架，不是很难，其实我现在也是这么认为的，不是说我到底有多么厉害，其实我仅仅是觉得，造出来不难，恰恰是造出来之后，你要去 “养育” 它，这对我来说，则是最难的，我现在正是体会到了。

不知不觉，我已经写过3个框架，其实都均已模仿他人框架为主的，然后肯定没有对方的好，当然有自己的一些想法融入里面了。然而，目前还存活的还剩下最后一个，他就是 [FastD](https://github.com/JanHuang/fastD)，不去总结不知道，这个东西喔已经 “养”了快一年了，感觉还不错，算是3个框架下来，比较 “好” 的了。

FD第一次拿出来的时候如果我没有记错的话是 2015年的新年后的第一个工作周，当时拿了出来演示了给部门的同事看，大家的反应都不错，这让我激情四射啊。😂

其实说老实话，我觉得自己也是一枚菜鸟及新手。造这个框架的初衷仅仅是想尝试下，然后进而发展到，让其他人都用上，目前算是实现了目标吧，因受 `Symfony` 框架的影响哈。

----

##个人看法

然后我说说自己对当前PHP框架的一些看法吧。

我觉得现在市面上充斥着很多的 php 框架，其实每个框架上，都有自己好的一面，也就是可以参考的地方。其实我偶尔会在一些群上看到 "xxx是世界上最好的框架，没有之一"，额，这到底对 xxx 框架有多狂热呀，和 “xxx是世界上最好的语言，没有之一” 一样，虽然说是老梗了，但其实是毫无意义的，包括有一些工作久的也会犯这些毛病。额，不好说吧，唉，自己顺手就好。

我接触的框架也不算多，也就几个，寥寥可数啊。但其实细心可以发现一个很基础的点就是：**路由是一个框架灵魂**，这么说不是没有道理的，目前咱们看到的框架，大部分都是只处理 “一个” 事情，`Http` 请求。而这个请求，看来则是一个由 “控制器” 及 “方法” 组成的指定地址而已，也就是咱们开发中所说的 **路由**，每个请求都是一个 **路由**，第一时间经过的，一定是路由，由路由负责解析到指定的方法。那剩下的就是处理了，至于是MVC还是其他，自定定制吧。

嗯嗯，还有，顺便提醒一下咱们这些搞PHP的，**一定要学好面向对象** **一定要学好面向对象** **一定要学好面向对象**

好了骚年，继续努力吧。

我个人推荐学习的有几款框架:

1. [Symfony](http://symfony.com)  / [社区](https://forum.symfony.cn)
2. [Laravel](http://www.golaravel.com/)
3. [Yaf](http://www.laruence.com/manual/)

顺便推广一下 [Swoole](http://www.swoole.com/)

PHP比你想象中的要牛逼。