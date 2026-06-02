# 文档索引

这个目录按“能不能直接帮你做判断”来组织，而不是按名词堆目录。

## 核心文档

| 文档 | 解决的问题 |
| --- | --- |
| [技术栈选择矩阵](./01-tech-stack-decision.md) | 什么场景该用什么后端、前端、数据库、缓存、队列、搜索和对象存储 |
| [高并发与 Python 多线程误区](./02-high-concurrency.md) | Python 是不是不能高并发、GIL 到底影响什么、扩容路线怎么走 |
| [容灾与生产可靠性](./03-reliability-disaster-recovery.md) | 高可用、容灾、RTO/RPO、备份、恢复、限流、熔断、监控怎么做 |
| [产品级项目从 0 到 1](./04-product-from-zero-to-one.md) | 需求、MVP、技术选型、数据模型、测试、上线和增长的工程路线 |
| [上线前 50 项检查](./05-launch-checklist.md) | 一个项目上线前最容易漏掉的 50 个检查点 |
| [高星 GitHub 项目包装](./06-open-source-playbook.md) | README、仓库结构、topics、发布和传播怎么做得可信 |
| [资料来源](./99-sources.md) | 官方文档、可靠性资料和同类高星知识库参考 |

## 推荐阅读顺序

如果你正在做一个新项目：

1. 先看 [一页速查表](../CHEATSHEET.md)。
2. 再看 [技术栈选择矩阵](./01-tech-stack-decision.md)。
3. 项目快上线时看 [产品级项目从 0 到 1](./04-product-from-zero-to-one.md) 和 [上线前 50 项检查](./05-launch-checklist.md)。
4. 流量或稳定性开始成为问题时看 [高并发](./02-high-concurrency.md) 和 [容灾](./03-reliability-disaster-recovery.md)。
5. 如果你要把这个知识库或自己的项目发到 GitHub，看 [开源包装](./06-open-source-playbook.md)。

如果你用 AI 写代码：

1. 先用 [技术栈选择矩阵](./01-tech-stack-decision.md) 判断 AI 给的方案是不是过度设计。
2. 用 [高并发](./02-high-concurrency.md) 检查 AI 有没有把 Python、多线程、异步、队列说错。
3. 用 [容灾](./03-reliability-disaster-recovery.md) 检查 AI 是否漏了超时、重试、幂等、备份和监控。
4. 用 [上线检查](./05-launch-checklist.md) 做最后验收。
