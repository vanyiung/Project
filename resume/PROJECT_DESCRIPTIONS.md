# Project Descriptions

这里集中保存简历可用的项目描述。所有内容必须能被项目文档、源码仓库、比赛材料或测试记录支撑。

## QuantGuard 智衡量化交易与风控系统

### 一句话

基于 Spring Boot、Vue 3、TypeScript 和 MySQL 开发本地模拟交易与持仓分析系统，覆盖历史行情、模拟订单、持仓收益和回本测算。

### 简历条目

- 采用 Spring Boot 与 Vue 3 构建前后端 monorepo，完成模拟账户、投资组合、证券标的、历史 K 线、模拟订单、成交和持仓分析。
- 使用 BigDecimal、事务、乐观锁和受影响行数检查处理资金冻结、成交结算和并发竞争，避免重复成交和资金状态不一致。
- 使用 ECharts 实现可缩放历史 K 线，使用 Playwright 覆盖关键浏览器交互，并通过前后端 GitHub Actions 自动验证。

## 员工工时系统

### 一句话

基于 Spring Boot、MySQL 和 MyBatis 实现员工工时管理 REST API，覆盖部门、用户、项目、员工项目分配和工时填报。

### 简历条目

- 使用 Spring Boot、MySQL 和 MyBatis 构建员工工时管理后端。
- 实现部门、用户、项目、员工项目分配和工时填报等基础业务模块。
- 提供 REST API，具体测试和上线状态待补充核验。
