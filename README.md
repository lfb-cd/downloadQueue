# downloadQueue

`NSOperationQueue` + `ASIHTTPRequest` 实现的文件下载

[简书同步地址：]（http://www.jianshu.com/p/05bde6766e90）

##主要思路

对每一个下载任务 生成一个 `Request` 添加到 `NSOperationQueue` 队列 中，同时 在下载过程中做监听，对相应任务做出相应的暂停，取消，恢复，存档等操作。界面更新 则使用 `block` 做监听

##浏览 
![](https://github.com/lfb-cd/downloadQueue/blob/master/downloadQueue.gif)

##[核心代码](https://github.com/lfb-cd/downloadQueue/blob/master/code/article.md)

代码不能完全开源，[关键代码]((https://github.com/lfb-cd/downloadQueue/blob/master/code/article.md))供学习交流

欢迎 **Star** 没准儿哪天就开源了 ^_^
