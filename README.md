# tim-objc
Tim聊天客户端ios实现

Tim项目介绍:
tim是一个分布式聊天服务器，采用thrift双向传输，有良好的拓展性

1.支持im的基本功能。 
2.支持群聊。 
3.支持用户状态信息推送，"在线","离开"等。 
4.支持消息回执.消息不丢失。 
5.支持离线信息，聊天信息等存储与拉取。 
6.通过协议拓展，可以支持视频，音频等通讯。 
7.支持心跳检测异常断开的客户端，检测客户端验证超时等。 
8.支持可配置的同一账号多客户端同时登陆。 
9.可以配置关联其他数据库用户系统，tim可以独立于业务之外。 
10.支持无数据库模式，此模式无法保存数据。 
11.支持自定义消息类型，如发送位置，分享购物信息等。 
12.支持分布式部署，服务器横向拓展。 
13.支持TLS安全传输层协议。 
14.支持hbase存储消息数据。 

而这里就是ios客户端objc的一个实现
