## Rotor Engine

Ad-hoc 查询引擎，基于 XQL 多源混算支持，专门为分钟级别延迟查询定制。

### Feature
基于 Spark 引擎实现的即席查询服务，提供以下功能：

- 代替 Hiveserver/Hiveserver2 和 Spark thfritserver，通过 XQL 对外提供统一的 DSL。
- 负载均衡，多引擎切换，服务自动发现。
- 多源异构数据源接入，包括File/HDFS(Text,  JSON, CSV, Parquet, ORC, Carbondata, Avro), Hive, JDBC(Mysql, PG), ES, Hbase, ClickHouse等数据源。
- 任务及资源管理。