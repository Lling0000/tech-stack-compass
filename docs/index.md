# 文档索引

这里是《TechStack Compass》的书籍目录。完整目录也可以看根目录的 [SUMMARY.md](../SUMMARY.md)。

## Part 0 先建立判断力

| 章节 | 主题 |
| --- | --- |
| [前言：为什么 AI 时代更需要技术栈判断力](./00-preface.md) | 说明这本书为什么存在，以及它不是资料合集 |
| [第 1 章 第一性原理：技术选型到底在选什么](./01-first-principles.md) | 用计算、状态、反馈速度、风险、成本和团队能力解释技术选择 |

## Part 1 技术栈怎么选

| 章节 | 主题 |
| --- | --- |
| [第 2 章 技术栈选择矩阵](./02-tech-stack-decision.md) | 后端、前端、数据库、缓存、队列、搜索、对象存储怎么选，以及为什么 |

## Part 2 系统怎么扛住真实世界

| 章节 | 主题 |
| --- | --- |
| [第 3 章 高并发与 Python 多线程误区](./03-high-concurrency.md) | GIL、I/O、CPU、瓶颈、扩容、缓存、队列、限流 |
| [第 4 章 容灾与生产可靠性](./04-reliability-disaster-recovery.md) | 高可用、RTO/RPO、备份恢复、熔断降级、监控告警 |

## Part 3 产品怎么从 0 到 1 上线

| 章节 | 主题 |
| --- | --- |
| [第 5 章 产品级项目从 0 到 1](./05-product-from-zero-to-one.md) | 需求、MVP、技术选型、数据模型、权限、测试、上线和增长 |
| [第 6 章 上线前 50 项检查](./06-launch-checklist.md) | 能直接拿去对照的上线前检查清单 |

## Part 4 真实项目里的隐性知识

| 章节 | 主题 |
| --- | --- |
| [第 7 章 隐性知识：没人明说但很关键的工程判断](./07-hidden-knowledge.md) | 技术栈、高并发、数据库、缓存、队列、容灾、AI、上线和团队协作暗坑 |

## Appendix

| 文档 | 主题 |
| --- | --- |
| [资料来源](./99-sources.md) | 官方文档、可靠性资料和同类高星知识库参考 |
| [一页速查表](../CHEATSHEET.md) | 快速决策入口 |

## 推荐阅读方式

如果你正在做一个新项目：

1. 先读 [第 1 章 第一性原理](./01-first-principles.md)。
2. 再看 [第 2 章 技术栈选择](./02-tech-stack-decision.md)。
3. 项目快上线时看 [第 5 章 从 0 到 1](./05-product-from-zero-to-one.md) 和 [第 6 章 上线清单](./06-launch-checklist.md)。
4. 流量或稳定性开始成为问题时看 [第 3 章 高并发](./03-high-concurrency.md) 和 [第 4 章 容灾](./04-reliability-disaster-recovery.md)。

如果你用 AI 写代码：

1. 用 [第 1 章](./01-first-principles.md) 检查 AI 的技术建议是不是过度设计。
2. 用 [第 7 章](./07-hidden-knowledge.md) 检查 AI 有没有漏掉生产暗坑。
3. 用 [第 6 章](./06-launch-checklist.md) 做交付前验收。
