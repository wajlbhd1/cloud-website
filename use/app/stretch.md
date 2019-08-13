# 伸缩

> 伸缩是对该应用所启动的pods数量进行一个控制。

同样进入应用的详情页页，在右上角找到**“伸缩”**按钮并点开。

在弹出来的对话框中选择启动的POD数量，如下图：

![](http://source.qiniu.cnd.nsini.com/images/2019/08/02/4e/a0/20190813-7b6792212c7a0219a7a80d684ed0232a.jpeg?imageView2/2/w/1280/interlace/0/q/70)

提交之后若数量大于之前的数量，则会启动缺少的POD数量，若小于之前的值，将会逐步减少应用的POD。

目前给的最大值是8个pod，资源可使用的内存是16G，若您的应用超过我们所设定的最大值。想办法优化吧，64核128G内存都不够用，这种级别的应用不适合用Docker。

这种级别的应用最好是拆了吧。