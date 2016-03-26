#主要思路

对每一个下载任务 生成一个 *Request* 添加到 *NSOperationQueue* 队列 中，同时 在下载过程中做监听，对相应任务做出相应的暂停，取消，恢复，存档等操作。界面更新 则使用 *block* 做监听

#关键代码

##NSOperationQueue 下载队列

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/data.png)

###1、 addDownloadMisson 添加下载队列

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/addDownloadMisson.png)

###2、cancelDownloadMisson 取消下载队列

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/cancelDownloadMisson.png)

###3、suspendDownloadMisson 暂停下载队列

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/suspendDownloadMisson.png)

###4、resumeDownloadMisson 恢复下载队列

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/resumeDownloadMisson.png)

###5、addListener 添加监听

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/addListener.png)

##ASIFormDataRequest 下载请求

![](https://github.com/lfb-cd/downloadQueue/blob/master/code/downloadFile-1.png)
![](https://github.com/lfb-cd/downloadQueue/blob/master/code/downloadFile-2.png)
![](https://github.com/lfb-cd/downloadQueue/blob/master/code/downloadFile-3.png)
![](https://github.com/lfb-cd/downloadQueue/blob/master/code/downloadFile-4.png)