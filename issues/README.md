Issues
===

[Fixing issues with Multidex on pre-lollipop devices on Windows](https://www.jimbobbennett.io/fixing-issues-with-multidex-on-pre-lollipop-devices-on-windows/)  

[什么是OOM？如何解决OOM问题!](https://www.jianshu.com/p/41ffbf31b20c)  

[什么是java OOM？如何分析及解决oom问题？](https://www.cnblogs.com/ThinkVenus/p/6805495.html)  

[OOM 内存溢出的原因和处理方法](https://blog.csdn.net/dakaniu/article/details/80747754)  

[Android系统进程Zygote启动过程的源代码分析](https://blog.csdn.net/luoshengyang/article/details/6768304)  

[Android Multidex正确使用方式（你可能也会遇到的坑）](https://www.jianshu.com/p/78f2e2d9484a)  

---------------------


[Android Studio引用另一个模块module的方法](https://blog.csdn.net/lyf970419/article/details/80762821)  

[java（Android）跨Module调用对应类方法需求解决方案](https://blog.csdn.net/sunlit_6/article/details/80942137)  

[Android组件化之不同模块间 交互（activity互相跳转，数据互相传递，互相调用函数）](https://blog.csdn.net/gaolei1201/article/details/77601027)  

----------------------


[Unable to instantiate application 解决办法](https://blog.csdn.net/adobe2000/article/details/78262960)  

[Android打包生成的APK安装包，安装后一打开软件就闪退问题](https://blog.csdn.net/rabbit_ding0810/article/details/78260374)  

[Android java.io.IOException异常情况整理](https://blog.csdn.net/zhufuing/article/details/38312441)  

[Android版本兼容性问题](https://blog.csdn.net/calvin_zhou/article/details/78466800)  

[android 调试崩溃Unable to instantiate application的解决方法](https://www.2cto.com/kf/201803/725461.html)  

[Android应用闪退异常java.lang.RuntimeException: Unable to instantiate application](https://blog.csdn.net/lijueqing/article/details/80854823)  

[MultiDex后java.lang.NoClassDefFoundError异常解决](https://blog.csdn.net/m00123456789/article/details/60767351)  

[android.dexOptions.incremental属性已被弃用](https://www.jianshu.com/p/da861a89ade7)  

[Android报unable to instantiate application怎么解决？](https://www.aliyun.com/jiaocheng/53238.html)  

[OS--›Gradle3.3 修改APK生成路径和文件名(附AAR修改方式以及分析过程)](https://blog.csdn.net/angcyo/article/details/78357512)  


[Android项目该如何选择targetSdkVersion](https://blog.csdn.net/zhangjin12312/article/details/78211328)  
~~~
compileSdkVersion定义应用程序编译选择哪个Android SDK版本，通常compileSDKVersion属性值被设置为最新的API版本
compileSDKVersion的属性值不会影响Android系统运行行为
targetSdkVersion、minSdkVersion和CompileSdkVersion之间的关系:
Android系统平台的行为变更，只有targetSdkVersion的属性值被设置为大于或等于该系统平台的API版本时，才会生效；compileSdkVersion属于Android编译项目时其中的一项配置，主要区别是compileSDKVersion在不会被打包的APK文件中，targetSdkVersion和minSdkVersion将被打包到APK文件中，具体可以解压APK文件后，查看AndroidManifest.xml文件
minSdkVersion <= targetSdkVersion <= compileSdkVersion
~~~

[Android targetSdkVersion你真的了解吗？](https://blog.csdn.net/qq_23062979/article/details/81294550)  