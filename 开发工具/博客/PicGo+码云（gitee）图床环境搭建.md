# PicGo+码云（gitee）图床环境搭建

# 注意：

:exclamation:目前已经不使用gitee当图床了，担心哪一天图片访问不了了，目前使用的是PicGO+OOS 方案存储，掏几块钱，心里安全不少

## 前言

本地写markdown使用Typora因为图片在本地，上传到其他博客上的时候，图片处理实在麻烦，之前也不知道什么是图床，今天无意间看到特地尝试一把，把我这个小白遇到的问题记录一下，顺便分享下自己的解决方案

### 1.需要准备的软件

1.PicGO

​	获取方式：

百度搜码云：进入后

​	![](https://gitee.com/liushuming/image/raw/master/img/20200326165756.png)

进入后向下滑，找到下面的下载安装



![](https://gitee.com/liushuming/image/raw/master/img/20200326170030.png)

下面就跳转到GitHub下载，

tips：感觉这样进去，会快一点，直接进GitHub，总是在转圈圈，要是有大佬知道的，欢迎评论

进入后向下滑动

![](https://gitee.com/liushuming/image/raw/master/img/20200326170445.png)

点击上面的箭头，直接下载，点击安装就好了（一定要闭着眼安装哟）

tips：GitHub有时候还是不能进，我会在文章末尾放上网盘链接

2.node.js

这里是我的一个坑，

之前没有安装node.js,导致后面安装gitee插件装不上，我也不会node.js

具体按照步骤可以看[菜鸟教程](![](https://gitee.com/liushuming/image/raw/master/img/20200326170445.png))

最后提示一点：按照完node.js一定要重启电脑，



### 码云的准备：

创建仓库：

![](https://gitee.com/liushuming/image/raw/master/img/20200326172416.png)-----------------------------------------------------------------------------------------------------------------------------------------------------------

![](https://gitee.com/liushuming/image/raw/master/img/20200326174021.png)-----------------------------------------------------------------------------------------------------------------------------------------------------------

创建服务![创建服务](https://gitee.com/liushuming/image/raw/master/img/20200326174229.png)

------

 点击启动

![](https://gitee.com/liushuming/image/raw/master/img/20200326174338.png)

------

### PicGo设置

安装gitte

![](https://gitee.com/liushuming/image/raw/master/img/20200326174929.png)

配置Gitee图床

![](https://gitee.com/liushuming/image/raw/master/img/20200326175354.png)



## ![](https://gitee.com/liushuming/image/raw/master/img/20200326181320.png)



![](https://gitee.com/liushuming/image/raw/master/img/20200326175859.png)

![](https://gitee.com/liushuming/image/raw/master/img/20200326180221.png)



提交后会验证你的密码，最后生成下面的

![](https://gitee.com/liushuming/image/raw/master/img/20200326180405.png)

把复制的私人令牌粘贴到图床的 taken位置

![](https://gitee.com/liushuming/image/raw/master/img/20200326175354.png)

最后点击确定。

重新启动到PicGo



开始使用

把图片直接拖动到上传区，或者把复制的图片点击右下角的剪切板图片上传

![](https://gitee.com/liushuming/image/raw/master/img/20200326180933.png)

点击对应图片的按钮复制

![](https://gitee.com/liushuming/image/raw/master/img/20200326180959.png)

复制完直接在 typora粘贴即可