---
description: 使用原生Minecraft Launcher登录
---

# 使用Minecraft Launcher登录

<mark style="color:red;">**警告：这将使该版本所有验证转向我们指定的验证服务器（红石皮肤站）**</mark>

前往[https://authlib-injector.yushi.moe/](https://authlib-injector.yushi.moe/)下载authlib-injector

假设：

* 你下载到的 authlib-injector JAR 文件名为`authlib-injector.jar`
* 你将其放到了`C:/`

打开Minecraft Launcher，点击**“配置”**

![](../../../.gitbook/assets/AO21\_\[2X1YNP\~L65ISM3\`B0.png)

选择一个版本，鼠标悬浮并点击**“···”**，点击**“编辑”**

![](../../../.gitbook/assets/GTC{CKU38PQ\)5\(3AD2{G16Q.png)

点击**“显示更多选项”**

![](../../../.gitbook/assets/UO{K\(T1K48\`@%Y\[G\[AP\_CSI.png)

在“JVM参数”添加`-javaagent:C:/authlib-injector.jar={验证服务器地址}`

如下方例子

```
// 注意：只是示例，请结合实际
-javaagent:C:/authlib-injector.jar={验证服务器地址} -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
```

![](../../../.gitbook/assets/5D\_8JR2RP%X\_\`]28\~1\[$6RE.png)
