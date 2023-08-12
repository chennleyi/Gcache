# Gcache
一个go语言实现的键值对分布式缓存

### 实现功能

* LRU的缓存淘汰策略，能安全的进行并发操作
* 实现一致性哈希，添加虚拟节点，可减少缓存雪崩和数据倾斜问题
* 实现分布式节点，节点之间进行http通信
* 实现singleflight,  使得多个并发请求下只需处理一个

### ![image-20230812101945410](README.assets/image-20230812101945410.png)





