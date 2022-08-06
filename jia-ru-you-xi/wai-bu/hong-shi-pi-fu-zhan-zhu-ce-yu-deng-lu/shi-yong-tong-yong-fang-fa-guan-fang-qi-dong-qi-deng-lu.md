# 使用通用方法登录

<mark style="color:red;">**警告：这将使所有验证转向我们指定的验证服务器（红石皮肤站）**</mark>

前往[https://authlib-injector.yushi.moe/](https://authlib-injector.yushi.moe/)下载authlib-injector

假设：

* 你下载到的 authlib-injector JAR 文件名为`authlib-injector.jar`
* 你将其放到了`C:/`
* 你的客户端 JAR 名称为`client.jar`

打开你的启动器，修改启动参数，在`java` 命令后方添加`-javaagent:C:/authlib-injector.jar={验证服务器地址}`

```
// 注意：只是示例，切勿直接复制粘贴下方启动参数，否则将无法启动
java -javaagent:C:/authlib-injector.jar={验证服务器地址} ... -jar client.jar
```





[本站由免费云加速（FreeCDN）提供网站加速和攻击防御服务](http://www.freecdn.pw/?zzwz)
