Jupiter release notes
------------------------

### 2017-05-06:

- 存在addAndGet场景时, 不使用jupiter自带的Atomic*FieldUpdater, 使用jdk默认的实现, 1.8后续版本jdk使用了intrinsics后更快

### 2017-04-18: version 1.2.4

- 升级Netty版本到4.1.9.Final
- 默认注册中心实现 jupiter-registry-default 序列化/反序列化方式改为可配置的方式
- 不再支持udt
- 简化spring配置 [\#14](https://github.com/fengjiachun/Jupiter/issues/14)

### 2017-03-11: version 1.2.3

- 优化JServiceLoader实现, 使其可按名字查找实现类