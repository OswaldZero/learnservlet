# 项目初衷
工作一段时间后发现自己学习的路子学得比较混乱，重新开始学一下。Java基础自己算是学得
还可以（Java日志和Java沙箱还是有点问题，之后慢慢补），暂且不重新开始学习，现在从
Servlet规范学，然后学一下Tomcat，Spring，SpringMVC，以及Spring Boot，本仓
库就从Servlet规范开始学。

# Servlet介绍
广义的Servlet是一套满足JSRXXX的规范，我觉得狭义的话可以理解为就是一套类库（API），
一般的话就是我们把这套类库学懂了，然后在这套类库上写一套自己的东西，像tomcat以及
spring就支持Servlet规范，顺便说一下，还有一种reactivestream规范，这种与
servlet规范不同，但是tomcat和spirng也是支持的。

# 版本
Servlet有很多版本，目前还是3.1比较多，毕竟还有很大部分的服务器不支持http2。大致的
历史改变如下。
[历史改变](src/main/resource/img.png)
