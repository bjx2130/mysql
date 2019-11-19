# mysql
mysql服务器性能优化


### MySQL连接处理方式及最佳并发连接数设置：
  TPS不再增长，反而出现下降，响应时间则会出现跳跃式的增长，此时则可以认为MySQL已经达到了当前配置的最大性能一般的原则是最大并发连接数等于CPU逻辑核心数的4倍。
  https://baijiahao.baidu.com/s?id=1637478110856031714&wfr=spider&for=pc
