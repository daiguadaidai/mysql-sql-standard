# Schema设计规范

Schema是数据设计中非常重要的一个部分。在该部分设计中，最好遵循先ER图初步审核，再遵循下面文档约束下，编写文档，输出Schema SQL文件，最好按表分别存放。

## Schema设计的目标

进行Schema设计有两个目标： 
1. 更快速的实现业务支撑&数据更好维护
2. 在线上业务压力增大的情况，或是要支撑更大的并发时，知道怎么做能获得最佳的实践。

## Schema设计的原则
1. 尽量小的原则，不浪费
2. 为了高并发，禁止使用外键
3. 每个表必须有主键
4. 字符集和库级保持一致。不单独定义字段字符集。




