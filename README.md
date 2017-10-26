# LiveTemplates
Android Studio的LiveTemplates，自定义了一些使用模版

使用方法：

1. 找到C:\Users\Administrator\.AndroidStudio3.0\config\templates目录，不同平台自己对比改下目录，没有templates可以自己新建一个
2. 在templates目录下git clone https://github.com/foxleezh/LiveTemplates
3. 将LiveTemplates的所有内容，包括.git，剪切到templates目录下
4. 重新打开Android Studio，在代码中输入foo，就会有代码提示

![](http://upload-images.jianshu.io/upload_images/3387045-9602ea148b89046c.gif?imageMogr2/auto-orient/strip)

如果你想扩展，可以Ctrl+Alt+S打开设置，搜索Live Templates进行修改

![](http://upload-images.jianshu.io/upload_images/3387045-70430e08a3002096.gif?imageMogr2/auto-orient/strip)

具体怎么修改可以参考我定义的Custom开头的一些配置，我的配置基本以foo_开头，自动生成的代码很多与项目相关，大家可以根据自己情况修改。