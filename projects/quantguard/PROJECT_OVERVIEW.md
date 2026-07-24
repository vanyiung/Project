# QuantGuard 智衡量化交易与风控系统

## 项目背景

QuantGuard 是一个本地自用的量化交易辅助与风控系统，目标是帮助整理长期定投、短期交易、模拟账户、订单、成交和资金流水等业务流程。

## 解决的问题

- 把交易建议、风控审核和模拟交易流程分开。
- 避免策略直接修改账户或绕过风控。
- 用自动化测试验证资金、订单、成交和流水的一致性。

## 当前状态

后端已推进到 V5，完成模拟账户、投资组合、证券标的、持仓、风控、模拟订单、模拟成交、资金流水、事务和并发测试。前端规划中。

## 技术栈

- Java 21
- Spring Boot
- Maven
- MySQL
- MyBatis-Plus
- Validation
- Lombok
- JUnit 5
- Mockito
- Testcontainers MySQL
- GitHub Actions

## 主要功能

- 模拟账户管理。
- 长期和短期投资组合隔离。
- 证券标的和只读持仓结构。
- 风控规则检查。
- 模拟订单创建。
- 模拟成交执行。
- 资金流水审计。
- 事务回滚和并发控制测试。

## 个人负责内容

- 后端架构设计与模块拆分。
- 数据库迁移脚本设计。
- Controller、Service、Mapper、Entity、DTO 分层实现。
- 风控、订单、成交、资金流水核心流程实现。
- 单元测试、WebMvc 测试、Testcontainers 集成测试和 GitHub Actions 配置。

## 技术难点

- 现金冻结、订单、成交和流水需要保持同一事务内一致。
- 同一订单并发执行或取消时，需要避免重复成交或状态错乱。
- 长期投资和短期交易必须在账户、组合和策略层面保持边界。

## 测试情况

- 普通后端测试已通过。
- GitHub Actions 后端 CI 已启用。
- Testcontainers MySQL 集成测试已在 GitHub Ubuntu Runner 上通过。
- V5 集成测试：6 个，Failures 0，Errors 0，Skipped 0。

## 已知限制

- 当前仍是本地模拟交易系统。
- 不接入真实券商。
- 不接入实时行情。
- 不执行真实自动下单。
- 前端尚未开始。

## 源码地址

https://github.com/vanyiung/QuantGuard

## 演示地址

待补充。
