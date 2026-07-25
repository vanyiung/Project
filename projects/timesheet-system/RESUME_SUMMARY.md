# 员工工时系统 Resume Summary

## 一句话版本

基于 Spring Boot、Vue 3 和 MySQL 开发三角色员工工时填报、审批与统计系统。

## 50 字版本

使用 Spring Boot、MyBatis、Vue 3 和 TypeScript 实现员工工时系统，覆盖基础数据、项目分配、工时填报、经理审批和统计分析。

## 100 字版本

员工工时系统采用 Spring Boot 与 Vue 3 前后端分离架构，围绕管理员、经理和员工三个角色，实现部门、用户、项目维护，员工项目分配，工时草稿与批量提交，单条与批量审批，以及个人和部门统计。前端已通过 TypeScript 与 Vite 生产构建。

## 详细版本

项目后端使用 Java、Spring Boot、MyBatis 和 MySQL，按 Controller、Service、Mapper、Entity、DTO、VO 分层；前端使用 Vue 3、TypeScript、Pinia、Vue Router、Element Plus 和 ECharts。核心业务通过 `DRAFT`、`SUBMITTED`、`APPROVED` 状态控制工时修改和审批，并保存审批记录。当前是功能原型，认证仍使用 mock token，完整测试和生产级安全能力尚未完成。

## 后端岗位版本

设计工时填报与审批数据模型，使用 Spring Boot、MyBatis 和 MySQL 实现基础数据、项目分配、工时状态流转、批量审批和统计接口，并通过分层结构隔离接口、业务和数据访问。

## 全栈岗位版本

使用 Spring Boot 和 Vue 3 完成员工工时管理全栈原型，按管理员、经理和员工三个角色组织 API 与页面，实现填报、审批和统计闭环，并验证前端生产构建。

## 答辩介绍版本

项目围绕企业工时管理流程展开：管理员维护组织和项目，经理分配项目并审批工时，员工填写和提交工时，系统最终生成个人与部门统计。当前重点是业务建模和前后端流程实现，认证、测试和部署仍需继续工程化。
