# QuantGuard 智衡量化交易与风控系统

## 项目背景

QuantGuard 是一个本地模拟交易、历史行情与持仓分析系统，用于管理模拟账户、投资组合、证券标的、订单、成交和持仓成本。

项目只处理本地模拟数据，不连接真实券商，不提交真实订单，也不执行真实交易。

## 当前状态

- `v1.0.0` 已于 2026 年 7 月发布；
- 前后端 monorepo 已完成；
- 后端测试 145 个通过；
- 前端 Playwright 浏览器测试 5 个通过；
- Backend CI 与 Frontend CI 均通过；
- GitHub Release 已发布。

## 技术栈

### 后端

- Java 21
- Spring Boot
- Maven
- MySQL
- MyBatis-Plus
- JUnit 5、Mockito、MockMvc
- Testcontainers MySQL

### 前端

- Vue 3
- TypeScript
- Vite
- Pinia
- Axios
- Element Plus
- ECharts
- Playwright

### 工程

- Git monorepo
- GitHub Actions
- Conventional Commits
- GitHub Releases

## 主要功能

- 模拟账户及账户内投资组合管理；
- 证券标的导入、停用、行情清理和安全删除；
- Tushare Token 页面配置和历史日线同步；
- 日 K、成交量、区间缩放和历史价格查看；
- 模拟限价订单创建、执行、取消和成交记录；
- 持仓数量、可用数量和平均成本维护；
- 持仓收益金额、收益率和市值展示；
- 持仓快捷回本测算和独立回本计算器；
- 响应式布局、可收起侧边栏及浅色/深色模式。

## 个人负责内容

- 前后端架构设计和 monorepo 迁移；
- 数据库结构、后端分层和事务流程实现；
- Vue 3 前端页面、状态管理和接口联调；
- K 线交互、持仓收益和回本计算实现；
- 资源停用、清空和硬删除规则设计；
- 单元测试、接口测试、浏览器自动化测试和 GitHub Actions；
- 版本收口、敏感信息检查和 GitHub Release 发布。

## 技术难点

- 在订单执行、取消、成交和持仓变化之间保持事务一致性；
- 区分停用、清空派生行情和永久删除，避免破坏交易数据引用；
- 让 K 线缩放后的最高价、最低价和右侧收盘价随可视范围更新；
- 在账户、投资组合和证券删除后清理前端本地选择状态；
- 使用浏览器自动化覆盖图表交互、硬删除和回本计算。

## 测试与验证

- 后端：145 个测试通过，Failures 0，Errors 0；
- 前端：format、type-check、lint 和 production build 通过；
- 浏览器：5 个 Playwright 测试通过；
- GitHub：前后端 Actions 均通过；
- 版本：`v1.0.0` 指向提交 `f4fa8966ac63a6dadbce2cac31dba21f01fb86a6`。

## 已知限制

- 不接入真实券商或真实交易账户；
- 不提供实时行情；
- 当前只面向本地单用户模拟场景；
- 仍需分别运行前端、后端并配置本地数据库；
- 桌面客户端尚未开发。

## 项目入口

- [源码仓库](https://github.com/vanyiung/QuantGuard)
- [v1.0.0 Release](https://github.com/vanyiung/QuantGuard/releases/tag/v1.0.0)

## 演示地址

当前没有公网演示地址。
