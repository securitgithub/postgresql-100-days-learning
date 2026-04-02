# PostgreSQL 100 天学习计划

> 从零基础到精通 PostgreSQL 的系统化学习路径，每天一个主题，循序渐进。

---

## 学习资源

| 类别 | 资源 |
|------|------|
| 官方文档 | [PostgreSQL 官方文档](https://www.postgresql.org/docs/) |
| 书籍 | 《PostgreSQL: Up and Running》 by Regina O. Obe & Leo S. Hsu |
| 在线课程 | [Udemy](https://www.udemy.com/) · [Coursera](https://www.coursera.org/) · [edX](https://www.edx.org/) · [bilibili](https://www.bilibili.com/) |
| 博客教程 | [DigitalOcean](https://www.digitalocean.com/community/tags/postgresql) · [Medium](https://medium.com/tag/postgresql) |
| 社区论坛 | [Stack Overflow](https://stackoverflow.com/questions/tagged/postgresql) · [Reddit r/PostgreSQL](https://www.reddit.com/r/PostgreSQL/) |

---

## 阶段总览

| 阶段 | 天数 | 主题 | 目标 |
|------|------|------|------|
| 第一阶段 | Day 001–020 | 基础入门 | 掌握安装、基本 SQL、数据类型、表操作 |
| 第二阶段 | Day 021–040 | SQL 进阶与数据建模 | 掌握复杂查询、函数、触发器、数据建模 |
| 第三阶段 | Day 041–060 | 管理与运维 | 掌握用户管理、备份恢复、监控、日志 |
| 第四阶段 | Day 061–080 | 性能优化与高级特性 | 掌握索引优化、查询调优、分区、JSON |
| 第五阶段 | Day 081–100 | 高可用、扩展与实战 | 掌握复制、高可用、扩展开发、综合项目 |

---

## 第一阶段：基础入门（Day 001–020）

| Day | 主题 |
|-----|------|
| [Day 001](days/day001.md) | 认识 PostgreSQL — 历史、特点、架构概览 |
| [Day 002](days/day002.md) | 安装与环境配置 |
| [Day 003](days/day003.md) | psql 命令行工具与 pgAdmin |
| [Day 004](days/day004.md) | 数据库与模式（Schema） |
| [Day 005](days/day005.md) | 数据类型（一）— 数值与字符串 |
| [Day 006](days/day006.md) | 数据类型（二）— 日期、布尔与特殊类型 |
| [Day 007](days/day007.md) | 创建与管理表 |
| [Day 008](days/day008.md) | 主键与外键 |
| [Day 009](days/day009.md) | INSERT 语句与批量导入 |
| [Day 010](days/day010.md) | SELECT 基础查询 |
| [Day 011](days/day011.md) | 排序与分页 |
| [Day 012](days/day012.md) | 聚合函数与 GROUP BY |
| [Day 013](days/day013.md) | UPDATE 与 DELETE |
| [Day 014](days/day014.md) | JOIN 查询（一）— 内连接与外连接 |
| [Day 015](days/day015.md) | JOIN 查询（二）— 高级连接 |
| [Day 016](days/day016.md) | 子查询 |
| [Day 017](days/day017.md) | 视图与物化视图 |
| [Day 018](days/day018.md) | 索引入门 |
| [Day 019](days/day019.md) | 事务基础与 ACID |
| [Day 020](days/day020.md) | 第一阶段回顾与综合练习 |

## 第二阶段：SQL 进阶与数据建模（Day 021–040）

| Day | 主题 |
|-----|------|
| [Day 021](days/day021.md) | 集合操作 — UNION / INTERSECT / EXCEPT |
| [Day 022](days/day022.md) | CASE 表达式与条件逻辑 |
| [Day 023](days/day023.md) | 字符串函数 |
| [Day 024](days/day024.md) | 日期时间函数 |
| [Day 025](days/day025.md) | 数学与类型转换函数 |
| [Day 026](days/day026.md) | 窗口函数（一）— 基础 |
| [Day 027](days/day027.md) | 窗口函数（二）— 进阶 |
| [Day 028](days/day028.md) | 窗口函数（三）— 聚合窗口 |
| [Day 029](days/day029.md) | CTE 公用表表达式与递归查询 |
| [Day 030](days/day030.md) | 高级 DML 操作 |
| [Day 031](days/day031.md) | 函数基础 — SQL 函数 |
| [Day 032](days/day032.md) | PL/pgSQL 基础 |
| [Day 033](days/day033.md) | PL/pgSQL 进阶 |
| [Day 034](days/day034.md) | 存储过程（Procedure） |
| [Day 035](days/day035.md) | 触发器（Trigger） |
| [Day 036](days/day036.md) | 数据建模基础 |
| [Day 037](days/day037.md) | 数据建模实践 |
| [Day 038](days/day038.md) | 数组与复合类型 |
| [Day 039](days/day039.md) | JSON 与 JSONB 基础 |
| [Day 040](days/day040.md) | 第二阶段回顾与综合项目 |

## 第三阶段：管理与运维（Day 041–060）

| Day | 主题 |
|-----|------|
| [Day 041](days/day041.md) | 用户与角色管理 |
| [Day 042](days/day042.md) | 权限深入 |
| [Day 043](days/day043.md) | 行级安全策略（RLS） |
| [Day 044](days/day044.md) | 连接与认证配置 |
| [Day 045](days/day045.md) | 配置调优（一）— 内存参数 |
| [Day 046](days/day046.md) | 配置调优（二）— WAL、并发与日志 |
| [Day 047](days/day047.md) | VACUUM 与 MVCC |
| [Day 048](days/day048.md) | Autovacuum 深入 |
| [Day 049](days/day049.md) | 备份策略（一）— 逻辑备份 |
| [Day 050](days/day050.md) | 备份策略（二）— 物理备份与 PITR |
| [Day 051](days/day051.md) | 恢复实战 |
| [Day 052](days/day052.md) | 日志管理与分析 |
| [Day 053](days/day053.md) | 监控（一）— 系统视图 |
| [Day 054](days/day054.md) | 监控（二）— 锁与等待 |
| [Day 055](days/day055.md) | 监控（三）— 工具与仪表盘 |
| [Day 056](days/day056.md) | 表空间与存储管理 |
| [Day 057](days/day057.md) | 扩展（Extension）管理 |
| [Day 058](days/day058.md) | 国际化与字符集 |
| [Day 059](days/day059.md) | 升级与迁移 |
| [Day 060](days/day060.md) | 第三阶段回顾与实战 |

## 第四阶段：性能优化与高级特性（Day 061–080）

| Day | 主题 |
|-----|------|
| [Day 061](days/day061.md) | EXPLAIN 与查询计划（一） |
| [Day 062](days/day062.md) | EXPLAIN 与查询计划（二） |
| [Day 063](days/day063.md) | 索引深入（一）— B-tree 与 Hash |
| [Day 064](days/day064.md) | 索引深入（二）— GiST、GIN、BRIN |
| [Day 065](days/day065.md) | 索引深入（三）— 索引策略 |
| [Day 066](days/day066.md) | 查询优化技巧 |
| [Day 067](days/day067.md) | 统计信息与查询规划器 |
| [Day 068](days/day068.md) | 表分区（一）— 声明式分区 |
| [Day 069](days/day069.md) | 表分区（二）— 分区管理 |
| [Day 070](days/day070.md) | 全文搜索（一） |
| [Day 071](days/day071.md) | 全文搜索（二） |
| [Day 072](days/day072.md) | JSONB 高级操作 |
| [Day 073](days/day073.md) | 范围类型与排他约束 |
| [Day 074](days/day074.md) | 事务隔离级别 |
| [Day 075](days/day075.md) | 并发控制与锁 |
| [Day 076](days/day076.md) | 应用集成（一）— 连接池 |
| [Day 077](days/day077.md) | 应用集成（二）— 应用开发 |
| [Day 078](days/day078.md) | 应用集成（三）— FDW |
| [Day 079](days/day079.md) | 安全加固 |
| [Day 080](days/day080.md) | 第四阶段回顾与优化实战 |

## 第五阶段：高可用、扩展与实战（Day 081–100）

| Day | 主题 |
|-----|------|
| [Day 081](days/day081.md) | 流复制基础 |
| [Day 082](days/day082.md) | 流复制实战 |
| [Day 083](days/day083.md) | 逻辑复制 |
| [Day 084](days/day084.md) | 高可用方案（一）— Patroni |
| [Day 085](days/day085.md) | 高可用方案（二）— 其他方案 |
| [Day 086](days/day086.md) | 读写分离 |
| [Day 087](days/day087.md) | Docker 部署 PostgreSQL |
| [Day 088](days/day088.md) | Kubernetes 部署 PostgreSQL |
| [Day 089](days/day089.md) | Citus — 分布式 PostgreSQL |
| [Day 090](days/day090.md) | PostGIS — 地理空间数据 |
| [Day 091](days/day091.md) | TimescaleDB — 时序数据 |
| [Day 092](days/day092.md) | PostgreSQL 与数据分析 |
| [Day 093](days/day093.md) | PostgreSQL 与 Python |
| [Day 094](days/day094.md) | PostgreSQL 与 Web 开发 |
| [Day 095](days/day095.md) | 编程扩展开发与 pgvector |
| [Day 096](days/day096.md) | 综合项目（一）— 需求分析与设计 |
| [Day 097](days/day097.md) | 综合项目（二）— 实现 |
| [Day 098](days/day098.md) | 综合项目（三）— 优化 |
| [Day 099](days/day099.md) | 综合项目（四）— 运维 |
| [Day 100](days/day100.md) | 总结与展望 |

---

## 每日学习建议

- **学习时间**：每天 1–2 小时，保持稳定节奏
- **理论与实践**：理论学习和动手实践各占 50%
- **笔记记录**：每天记录学习笔记，积累个人知识库
- **代码管理**：将所有练习 SQL 文件用 Git 管理
- **问题解决**：遇到问题先查官方文档，再到 Stack Overflow / Reddit 搜索
- **社区参与**：定期浏览 r/PostgreSQL 和相关博客，了解行业动态
- **复习回顾**：每个阶段结束后做综合回顾，查漏补缺

---

## License

MIT License
