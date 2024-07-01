# 仓颉三方库资源汇总

本文收集了一些已经发布在Cangjie-TPC组织上的三方组件资源，欢迎开发者参考和使用

## 网络

[hyperion](https://gitcode.com/Cangjie-TPC/hyperion/overview)——仓颉语言实现的TCP通信框架，支持添加自定义编解码器，积木式添加IoFilter处理入栈出栈消息。仓颉redis-sdk和activemq4cj项目使用了该框架。

## 数据库驱动

[redis-sdk](https://gitcode.com/Cangjie-TPC/redis-sdk/overview)——仓颉语言实现的Redis客户端SDK。接口设计兼容jedis接口语义，支持RESP2和RESP3协议，支持发布订阅模式，支持哨兵模式和集群模式。

