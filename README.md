# PROJECT-PORTFOLIO

个人项目成果、架构说明、里程碑记录与作品集材料。
Personal project achievements, architecture documentation, milestone records, and portfolio materials.

## 中文

### 仓库用途

本仓库用于整理个人项目作品集材料，保存项目概览、架构说明、里程碑、简历描述、答辩与面试问答、脱敏截图说明和成果索引。

它不是源码仓库，不保存完整项目代码、数据库、模型权重、大型数据集或真实凭据。

### 当前收录项目

| 项目 | 类型 | 当前状态 | 入口 |
| --- | --- | --- | --- |
| QuantGuard 智衡量化交易与风控系统 | Spring Boot / Vue 3 / 模拟交易 | v1.0.0 已正式发布，前后端 CI 通过 | [projects/quantguard/PROJECT_OVERVIEW.md](projects/quantguard/PROJECT_OVERVIEW.md) |
| 员工工时系统 | Spring Boot / REST API | 已有基础业务模块 | [projects/timesheet-system/PROJECT_OVERVIEW.md](projects/timesheet-system/PROJECT_OVERVIEW.md) |

### 如何查看项目

每个项目目录包含：

- `PROJECT_OVERVIEW.md`：项目概览。
- `ARCHITECTURE.md`：架构和边界。
- `MILESTONES.md`：阶段记录和证据。
- `RESUME_SUMMARY.md`：简历和答辩可用描述。
- `INTERVIEW_QA.md`：面试问答准备。
- `assets/README.md`：截图和图片素材规则。

### 如何添加新项目

1. 复制 `templates/` 下的模板。
2. 新建 `projects/<project-name>/`。
3. 只填写已验证事实，不确定内容写 `待补充`、`待核验` 或 `CHANGE_ME`。
4. 脱敏后再放入截图和演示素材。
5. 提交前按 [docs/PRIVACY_CHECKLIST.md](docs/PRIVACY_CHECKLIST.md) 检查隐私和 Secret。

### 与源码仓库的区别

源码仓库保存可运行代码、测试和工程配置；本仓库保存对外展示和复盘材料。这里可以链接源码仓库，但不批量复制源码。

### 与 CODEX-SKILLS 的区别

`CODEX-SKILLS` 保存 Codex 的可复用工作流能力；本仓库保存人的项目成果展示材料。

### 内容真实性原则

禁止编造用户数量、上线状态、性能数据、准确率、获奖情况、生产应用或未完成模块。不确定内容必须标记为待核验。

### 隐私边界

不要提交手机号、身份证、家庭住址、私人邮箱、未脱敏成绩单、导师私人联系方式、密码、Token、Cookie、私钥或真实账号凭据。

### 资源文件规则

`assets/` 只保存脱敏截图、自己制作的架构图、流程图、小型 GIF 和项目封面。不要保存大型视频、数据库文件、模型权重、大型数据集或未授权图片。

### 当前维护状态

第一版作品集结构已初始化。后续随着项目推进，逐步补充真实截图、演示链接、提交证据和答辩材料。

## English

### Purpose

This repository stores portfolio-ready project materials: overviews, architecture notes, milestone records, resume summaries, interview preparation, sanitized asset guidance, and achievement indexes.

It is not a source-code mirror. It should not contain full source copies, databases, model weights, large datasets, or real credentials.

### Included Projects

| Project | Type | Status | Entry |
| --- | --- | --- | --- |
| QuantGuard | Spring Boot / Vue 3 / simulated trading | v1.0.0 released; backend and frontend CI passing | [projects/quantguard/PROJECT_OVERVIEW.md](projects/quantguard/PROJECT_OVERVIEW.md) |
| Timesheet System | Spring Boot / REST API | Basic business modules recorded | [projects/timesheet-system/PROJECT_OVERVIEW.md](projects/timesheet-system/PROJECT_OVERVIEW.md) |

### How to Use

Use the project folders for portfolio review, resume preparation, interviews, and project defense. Use `templates/` when adding a new project, and follow the privacy checklist before committing.

### Boundaries

Keep facts verifiable, keep personal data out, and link to source repositories instead of copying complete code.
