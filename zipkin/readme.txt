史上最简单的SpringCloud教程 | 第九篇: 服务链路追踪(Spring Cloud Sleuth)(Finchley版本)

4.1 构建server-zipkin
在spring Cloud为F版本的时候，已经不需要自己构建Zipkin Server了，只需要下载jar即可，下载地址：

https://dl.bintray.com/openzipkin/maven/io/zipkin/java/zipkin-server/

也可以在这里下载：

链接: https://pan.baidu.com/s/1w614Z8gJXHtqLUB6dKWOpQ 密码: 26pf

下载完成jar 包之后，需要运行jar，如下：

java -jar zipkin-server-2.10.1-exec.jar

访问浏览器localhost:9494
---------------------
作者：方志朋
来源：CSDN
原文：https://blog.csdn.net/forezp/article/details/81041078
版权声明：本文为博主原创文章，转载请附上博文链接！