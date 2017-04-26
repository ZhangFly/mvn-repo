# mvn-repo
在 pom.xml 中添加 ZFly 的 maven 仓库

```
<repositories>
    <repository>
    	<id>ZFly</id>
        <url>https://raw.githubusercontent.com/ZhangFly/mvn-repo/master</url>
    </repository>
</repositories>
```

## WTFSocket

### wtfsocket-server

#####  简介：

轻量的 **Tcp/WebSocket** 服务器框架

帮助速搭建需要保持长连接的双工的消息型服务器

适用于消息短且转发频繁的业务场合，不适合大文件的传输

##### 可用版本：

- 1.0.0

```
<dependencies>
	<dependency>
    	<groupId>ZFly</groupId>
        <artifactId>wtfsocket-server</artifactId>
        <version>1.0.0</version>
    </dependency>
</dependencies>
```
### wtfsocket-client-java/android

TO UPLOAD