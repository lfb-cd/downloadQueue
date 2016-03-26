# downloadQueue

##主要思路

对每一个下载任务 生成一个 *Request* 添加到 *NSOperationQueue* 队列 中，同时 在下载过程中做监听，对相应任务做出相应的暂停，取消，恢复，存档等操作。界面更新 则使用 *block* 做监听

##浏览 
![](https://github.com/lfb-cd/downloadQueue/blob/master/downloadQueue.gif)
