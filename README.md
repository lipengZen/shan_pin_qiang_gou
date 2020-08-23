#### 商品抢购系统

​       基于SpringBoot+Thymeleaf+MyBatis实现一个高并发商品抢购系统。经Jmeter压测，四核CPU在线程数5000循环10次时，QPS为1306/sec，load average达到15. 

​      对系统进行优化，页面动静分离，使用Redis缓存，消息队列RabbitMQ异步下单。压测结果为QPS：2884/sec,load average 为12.

​      同时，隐藏秒杀地址、使用图形验证码、接口限流防刷保障系统安全性。