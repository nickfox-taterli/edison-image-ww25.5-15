# Intel Edison 再生源说明

------

因为Intel Edison乃古董且EOL产品,受委托要做个这么的源码包,就做了,很多原始连接已经失效,毕竟这是个5年前的东西啊!下面有几点特别注意!

> * 由于部分软件全网都找不到源码了,所以只能放弃,请在local.conf追加:IMAGE_INSTALL_remove += "iotkit-agent iotkit-comm-js"
> * 编译参考:https://qiita.com/kentegrate/items/83ef6bc5f38def27b58e
> * 编译只能用Ubuntu 12.04,推荐在Linux(不能是虚拟机)下使用Platform Flash Tool Lite最新版烧录,烧录的系统可以是最新的Ubuntu.
> * 这个项目是不会维护的,除非再受人所托.

其他内容请自行谷歌了.
