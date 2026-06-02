# 资料来源

本项目优先使用官方文档、经典可靠性资料和公开高星项目作为依据。技术判断会随生态变化而变化，具体项目落地前仍应结合团队、业务、预算和生产指标验证。

## Python、GIL 和并发

- [Python Glossary: Global Interpreter Lock](https://docs.python.org/3/glossary.html#term-global-interpreter-lock)
- [Python threading documentation](https://docs.python.org/3/library/threading.html)
- [Python concurrent.futures documentation](https://docs.python.org/3/library/concurrent.futures.html)
- [Python multiprocessing documentation](https://docs.python.org/3/library/multiprocessing.html)

## 可靠性、容灾和 SLO

- [Google SRE Book: Service Level Objectives](https://sre.google/sre-book/service-level-objectives/)
- [Google SRE Workbook: Alerting on SLOs](https://sre.google/workbook/alerting-on-slos/)
- [AWS Well-Architected Reliability Pillar: Plan for Disaster Recovery](https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/plan-for-disaster-recovery-dr.html)
- [Microsoft Azure reliability documentation](https://learn.microsoft.com/en-us/azure/reliability/)

## 数据库、缓存、队列、搜索和对象存储

- [PostgreSQL documentation](https://www.postgresql.org/docs/)
- [MySQL documentation](https://dev.mysql.com/doc/)
- [SQLite documentation](https://www.sqlite.org/docs.html)
- [Redis documentation](https://redis.io/docs/latest/)
- [Apache Kafka introduction](https://kafka.apache.org/intro)
- [RabbitMQ documentation](https://www.rabbitmq.com/documentation.html)
- [Amazon SQS documentation](https://docs.aws.amazon.com/sqs/)
- [OpenSearch documentation](https://opensearch.org/docs/)
- [Elasticsearch documentation](https://www.elastic.co/docs)
- [ClickHouse documentation](https://clickhouse.com/docs)
- [Amazon S3 documentation](https://docs.aws.amazon.com/s3/)
- [Cloudflare R2 documentation](https://developers.cloudflare.com/r2/)

## 高星知识库项目参考

以下 star 数通过 GitHub API 于 2026-06-02 查询，仅作为当日快照：

| 项目 | Stars | 参考点 |
| --- | ---: | --- |
| [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | 510,507 | 强学习承诺，项目名和内容高度一致 |
| [public-apis/public-apis](https://github.com/public-apis/public-apis) | 438,524 | 资源型项目入口清晰，适合收藏 |
| [nilbuild/developer-roadmap](https://github.com/nilbuild/developer-roadmap) | 355,898 | 路线图结构让用户知道从哪里开始 |
| [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | 351,378 | 系统设计主题聚焦，面向明确需求 |
| [trimstray/the-book-of-secret-knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) | 226,090 | 短知识条目和“secret knowledge”定位适合检索 |

## 使用提醒

- 官方文档适合确认概念、API 和边界。
- 高星项目适合学习结构、README、入口和传播方式。
- 不要照抄 star 项目的形式，先确认你的目标用户和使用场景。
- 所有“推荐技术栈”都不是永久答案，生产落地前要用真实负载、预算和团队能力验证。
