# QuantGuard Resume Summary

## 一句话版本

基于 Spring Boot、Vue 3 和 MySQL 开发本地模拟交易与持仓分析系统，并完成前后端 CI 和浏览器自动化测试。

## 50 字版本

使用 Java 21、Spring Boot、Vue 3、TypeScript 和 MySQL 构建模拟交易系统，实现历史 K 线、订单成交、持仓收益和回本计算。

## 100 字版本

QuantGuard 是本地模拟交易与历史行情分析系统。项目采用 Spring Boot 与 Vue 3 monorepo，完成账户、组合、证券、K 线、订单、成交、持仓收益和回本计算，并通过 145 个后端测试、5 个 Playwright 浏览器测试及前后端 GitHub Actions 验证。

## 详细版本

QuantGuard 使用 Java 21、Spring Boot、MySQL、MyBatis-Plus、Vue 3、TypeScript、Pinia 和 ECharts 构建。后端采用 Controller、Service、Mapper、Entity、DTO 分层结构，处理模拟账户、订单、成交和持仓等业务；前端提供历史 K 线、模拟下单、收益展示和回本计算。项目针对资源生命周期设计停用、行情清空和安全硬删除，并使用 JUnit、MockMvc、Testcontainers 与 Playwright 覆盖后端事务和关键浏览器交互。`v1.0.0` 已通过前后端 GitHub Actions 并正式发布。

## 后端岗位版本

设计并实现 Spring Boot 模拟交易后端，重点处理金额精度、事务边界、并发更新、异常响应和资源生命周期，通过 JUnit、MockMvc 和 Testcontainers 验证核心业务一致性。

## 全栈岗位版本

使用 Spring Boot、Vue 3、TypeScript、Pinia、Element Plus 和 ECharts 完成模拟交易系统前后端开发，构建历史 K 线、订单成交、持仓收益和回本测算流程，并使用 Playwright 与 GitHub Actions 自动验证关键交互。

## 答辩介绍版本

本项目用于本地模拟交易和历史行情分析，不连接真实券商。系统从证券行情、模拟账户和投资组合出发，形成订单、成交、持仓和收益分析闭环，并针对交易事务、资源删除和图表交互建立自动化测试。首个正式版本已发布到 GitHub。
