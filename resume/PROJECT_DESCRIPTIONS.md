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

基于 Spring Boot、Vue 3、TypeScript 和 MySQL 实现三角色员工工时管理系统，覆盖填报、审批、项目分配和统计分析。

### 简历条目

- 采用 Spring Boot、MyBatis 和 MySQL 构建工时管理后端，设计部门、用户、项目、员工项目分配、工时和审批记录数据模型。
- 使用 Vue 3、TypeScript、Pinia、Element Plus 和 ECharts 实现管理员、经理和员工三类工作台。
- 实现草稿填报、批量提交、单条与批量审批、驳回和个人/部门统计；前端生产构建已通过。

## TypeWriter

### 一句话

使用 AutoHotkey v2 开发 Windows 文本模拟输入工具，为禁止粘贴的输入场景提供可调速、可延迟的逐字符输入。

### 简历条目

- 使用 AutoHotkey v2 构建 Windows GUI 和系统托盘工具，实现普通输入、延迟输入、进度反馈及文本编辑操作。
- 支持自定义快捷键、输入速度和延迟时间，并通过 INI 与注册表实现置顶偏好和开机自启。
- 发布 MIT 许可源码和独立可执行程序，当前源码版本为 v1.0.0。

## KMNZ 资料站

### 一句话

使用原生 HTML、CSS 和 JavaScript 构建响应式多页面资料站，覆盖成员资料、主题切换、账户原型和媒体封面管理。

### 简历条目

- 构建首页、成员资料、历程、登录注册、个人中心和歌回封面等 12 个静态页面。
- 使用原生 JavaScript 实现成员数据渲染、轮播、浅深色主题、localStorage 状态及可选 Firebase 认证。
- 对全部 JavaScript 文件执行语法检查并验证站内本地链接，检查结果均通过。
