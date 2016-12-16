PHP 扩展个人学习笔记
============

这是我在学习PHP扩展开发时，通过网上参考资料个人整理的一份笔记。笔记做的有些水，会有一些问题。但还是希望能对大伙有所帮助。


PHP版本
-----

PHP 7.0.9

笔记中的PHP源码都是PHP 7.0.9的源码（注意：PHP7与PHP5在源码上有许多不同）。

参考文档
----

[从零开始编写第一个PHP扩展](http://wiki.swoole.com/wiki/page/238.html) ：

swoole扩展的作者韩天峰为大伙录制的一份PHP扩展开发教程，可以说这是学习PHP开发非常重要的一个环节。建议大伙先把这个视频看完再看下面的资料。

[PHP扩展开发及内核应用](http://www.cunmou.com/phpbook/preface.md) ：

举的例子很不错，非常适合入门。但是个别例子有小bug，但不影响学习。我主要通过它来学习php扩展开发的。

[深入理解PHP内核](http://www.php-internals.com) ：

不错的文档，写的很详细。似乎还没写完。

IDE
---

Eclipse:

可能是目前对PHP扩展开发支持最好的一款编辑器了，就是不够潮流。这也是我的学习PHP扩展开发的主力编辑器。

Clion:

最潮流的，对用户十分友好的编辑器。但现在和PHP扩展开发匹配的不是太好，而且在我的Mac电脑上加载PHP7的源码非常吃内存。虽然我十分喜欢这款编辑器，但目前在我这里只是起到辅助作用。


参考书籍
----
[《C和指针》](https://www.amazon.cn/C%E5%92%8C%E6%8C%87%E9%92%88-Pointers-On-C-Kenneth-A-Reek/dp/B00163LU68/ref=sr_1_1?ie=UTF8&qid=1481866902&sr=8-1&keywords=c%E5%92%8C%E6%8C%87%E9%92%88) ：

非常经典的书。可以拿来学习和复习C的语法。怎么说呢，这本书就像高中学神的课堂笔记。所以你懂了吧。

[《C Primer Plus》](https://www.amazon.cn/C-Primer-Plus-%E6%99%AE%E6%8B%89%E5%A1%94/dp/B001171NQ6/ref=sr_1_3?ie=UTF8&qid=1481867050&sr=8-3&keywords=c) ：

又是一本经典读物。但是呢这本书的内容十分庞大，很多知识点用的几率太小。所以拿来当参考手册是不错的。这本书的就是C语言中的新华字典。

推荐
---
[风雪之隅-PHP源码分析](http://www.laruence.com/php-internal) ：

鸟哥的博客。