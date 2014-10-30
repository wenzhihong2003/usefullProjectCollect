usefullProjectCollect
=====================

github上一些觉得对自己工作有用的项目收集

## 技能类
+ [markdown语法中文说明] (http://wowubuntu.com/markdown/basic.html)


## 全文检索
+ [elasticsearch] (https://github.com/elasticsearch/elasticsearch)

+ [bigdesk] (https://github.com/lukas-vlcek/bigdesk)
elasticsearch管理插件


## nosql
+ [mapdb] (https://github.com/jankotek/MapDB)
支持亿级别map, list, 支持事务. 可考虑做为缓存使用

## 前端js类


## nodejs类

## javaweb框架类
+ [play1] (https://github.com/playframework/play1/)
颠覆javaee的概念写的一个全栈式的web框架. 里面的很多概念可以借鉴

+ [play2] (https://github.com/playframework/playframework)
scala的web框架, 更加擅长于编写长连接推送型并发量大的web应用, 可以说是现在的手机web类的应用.

+ [ninjaframework] (https://github.com/ninjaframework/ninja)
Ninja is a full stack web framework for Java. Rock solid, fast and super productive. 完全使用java来编写,maven构建,从play上借鉴了很多的东西.

+ [generator-jhipster] (https://github.com/jhipster/generator-jhipster)
Hipster stack for Java developers. Yeoman + Maven + Spring + AngularJS in one handy generator. [网站](http://jhipster.github.io/)

Our goal is to generate for you a complete and modern Web app, unifying
 1. A high-performance and robust Java stack on the server side with Spring Boot
 2. A sleek, modern, mobile-first front-end with AngularJS and Bootstrap 
 3. A powerful workflow to build your application with Yeoman, Bower, Grunt and Maven

## orm
+ [ebean] (https://github.com/ebean-orm)
是我理想中的orm框架,支持半生对象,bean对象转json.感觉作者是从一线开发人员, 跟hibernate相比少了很多高大尚的理念.
使用maven,ant在编译进行字节码增强. 其字节码增强这块很值得学习.
这边要去注意一下java的命令行参数 **-javaagent**

+ [avaje-metric] (https://github.com/avaje-metric) 
ebean作者的另外一个项目, 也是使用字节码增强加入性能监测代码


## java
+ [boon] (https://github.com/boonproject/boon)
提供日常java开发的工具类,如json,并发消息处理. 及提供一些语法上的便利

+ [guava] (https://code.google.com/p/guava-libraries/)
提供java集合,并发操作一些常用的工具类及数据结构,要是开发java程序,请一定要使用它, 跟上面的 **boon** 有些重合

+ [vert.x] (https://github.com/eclipse/vert.x/)
The scalable polyglot application platform for the JVM. java上的nodejs, 支持多语言编写模块.引入eventbus,使用单线程简化并发开发

+ [atmoshpere] (https://github.com/Atmosphere/atmosphere)
Realtime Client Server Framework for the JVM, supporting WebSockets and Cross-Browser Fallbacks Support. websocket的支持,及在浏览器不支持websocket时,退化到别的方式支持. 如commet,long-pull等, 无需改服务端代码

+ [nettosphere] (https://github.com/Atmosphere/nettosphere)
A Java WebSocket/HTTP server based on the Atmosphere and Netty Framework

+ [Vibe] (https://github.com/vibe-project/) [网站] (http://vibe-project.github.io/)
atmoshpere的下一代. A real-time web application framework
The Vibe is a new web framework to write low-latency, event-driven, real-time web application and service based on its own protocol built over HTTP and WebSocket which is available to any language and platform. A Vibe focuses on providing reliable full duplex connection and making the best use of it for modern web application development so that teams can focus on event handling without unnecessary ties to low-level details like transport mechanisms and message loss


