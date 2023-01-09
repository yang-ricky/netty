# Netty Project

Netty is an asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.


## How to build - 2022-12-31在JK8上编译成功, JDK11上Netty/Example编译失败
```bash
mvn clean package -Dmaven.test.skip=true
```