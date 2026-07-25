# QuantGuard Milestones

| 时间 | 阶段目标 | 已完成内容 | 验证方式 | 证据 |
| --- | --- | --- | --- | --- |
| 2026-07 | 后端基础 | Spring Boot、数据库连接、统一响应、账户和投资组合 | 单元测试、接口测试 | QuantGuard 提交历史 |
| 2026-07 | 模拟交易闭环 | 证券、订单、成交、持仓、资金流水、事务与并发控制 | JUnit、MockMvc、Testcontainers | 后端 CI |
| 2026-07 | monorepo 迁移 | 后端迁入 `quant-guard-backend/`，保留历史和回滚标签 | 本地测试、Git 检查 | `e2de2b2` |
| 2026-07 | 前端第一阶段 | Vue 3 前端、账户、组合、持仓和真实接口联调 | type-check、lint、build | `d73d74e` |
| 2026-07 | 行情与 K 线 | 股票导入、Tushare、历史日线、K 线和区间交互 | 浏览器联调、前端 CI | `792c996`、`aa07415` |
| 2026-07 | 安全生命周期 | 账户、组合、证券和持仓资源管理，停用、清空和硬删除 | 后端测试、浏览器验证 | `81f4aaf`、`fe7a72c` |
| 2026-07 | 页面收口 | 页面整合、深色模式、响应式布局、回本计算和 Playwright | 145 个后端测试、5 个浏览器测试 | `69f98b1` |
| 2026-07 | v1.0.0 发布 | 计算器布局收口、版本标签和 GitHub Release | 前后端 CI 均通过 | `f4fa896`、`v1.0.0` |

## 当前基线

- Release：`v1.0.0`
- Commit：`f4fa8966ac63a6dadbce2cac31dba21f01fb86a6`
- Backend CI：通过
- Frontend CI：通过
- 工作区：发布时干净

## 下一阶段

- 桌面客户端技术验证；
- 前端桌面壳；
- Spring Boot 后端随客户端自动启停；
- 嵌入式数据库和 Windows 安装包。
