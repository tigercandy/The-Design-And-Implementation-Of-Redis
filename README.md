> 《Redis设计与实现》(第二版)  Git版本.



## 目录

- [第一部分：数据结构与对象](#数据结构与对象)
  - [简单动态字符串](#简单动态字符串)
  - [链表](#链表)
  - [字典](#字典)
  - [跳跃表](#跳跃表)
  - [整数集合](#整数集合)
  - [压缩列表](#压缩列表)
  - [对象](#对象)

- [第二部分：单机数据库的实现](docs/单机数据库的实现.md)
  - [数据库](#数据库)
  - [RDB持久化](#RDB持久化)
  - [AOF持久化](#AOF持久化)
  - [事件](#事件)
  - [客户端](#客户端)
  - [服务端](#服务端)
- [第三部分：多机数据库的实现](docs/多机数据库的实现.md)
  - 复制
  - Sentinel
  - 集群
- [第四部分：独立功能的实现](docs/独立功能的实现.md)
  - 发布订阅
  - 事件
  - Lua脚本
  - 排序
  - 二进制位数组
  - 慢查询日志
  - 监视器
- [致谢](#致谢)

##  数据结构与对象

#### 简单动态字符串

- [SDS的含义](docs/part-1/SDS的含义.md)
- [SDS与C字符串的区别](docs/part-1/SDS与C字符串的区别.md)
- [SDS API](docs/part-1/SDSAPI.md)
- [Redis重点回顾](docs/part-1/Redis重点回顾.md)
- [Redis参考资料](docs/part-1/Redis参考资料.md)

#### 链表

- [Redis链表和链表节点的实现](docs/part-1/Redis链表和链表节点的实现.md)
- [Redis链表和链表节点的API](docs/part-1/Redis链表和链表节点的API.md)
- [Redis重点回顾](docs/part-1/Redis重点回顾2.md)

#### 字典

- [Redis字典的实现](docs/part-1/Redis字典的实现.md)
- [Redis哈希算法](docs/part-1/Redis哈希算法.md)
- [Redis解决键冲突](docs/part-1/Redis解决键冲突.md)
- [Redis rehash](docs/part-1/RedisRehash.md)
- [Redis渐进式rehash](docs/part-1/Redis渐进式rehash.md)
- [Redis字典API](docs/part-1/Redis字典API.md)
- [Redis重点回顾](docs/part-1/Redis重点回顾3.md)

#### 跳跃表

- [Redis跳跃表的实现](docs/part-1/Redis跳跃表的实现.md)
- [Redis跳跃表API](docs/part-1/Redis跳跃表API.md)
- [Redis重点回顾](docs/part-1/Redis重点回顾4.md)

#### 整数集合

- [Redis整数集合的实现](docs/part-1/Redis整数集合的实现.md)
- [Redis升级](docs/part-1/Redis升级.md)
- [Redis升级的好处](docs/part-1/Redis升级的好处.md)
- [Redis降级](docs/part-1/Redis降级.md)
- [Redis整数集合API](docs/part-1/Redis整数集合API.md)
- [Redis重点回顾](docs/part-1/Redis重点回顾5.md)

#### 压缩列表

- [Redis 压缩列表的构成](docs/part-1/Redis压缩列表的构成.md)
- [Redis 压缩列表节点的构成](docs/part-1/Redis压缩列表节点的构成.md)
- [Redis 连锁更新](docs/part-1/Redis连锁更新.md)
- [Redis 压缩列表 API](docs/part-1/Redis压缩列表API.md)
- [Redis 重点回顾](docs/part-1/Redis重点回顾6.md)

## 致谢

我要感谢 hoterran 和 iammutex 这两位良师益友， 他们对我的帮助和支持贯穿整本书从概念萌芽到正式出版的整个阶段， 也感谢他们抽出宝贵的时间为本书审稿。

我要感谢吴怡编辑给了我创作并出版这本新版《Redis 设计与实现》的机会， 以及她在写作过程中对我的悉心指导。

我要感谢 TimYang 在百忙之中抽空为本书审稿， 并耐心地给出了详细的意见。

我要感谢 Redis 之父 Salvatore Sanfilippo ， 如果不是他创造了 Redis 的话， 这本书也不会出现了。

我要感谢所有阅读了《Redis 设计与实现》第一版的读者， 他们的意见和建议帮助我更好地完成这本新版《Redis 设计与实现》。

最后， 我要感谢我的家人和朋友， 他们的关怀和鼓励使得本书得以顺利完成。