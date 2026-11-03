# 可复用模板

[首页](../README.md) · [AI 工作流](../docs/engineering/AI-WORKFLOW.md)

这些是可以改写后放入自己工程的起点。具体契约与工具需要由自己的项目实现，复制模板不会自动获得验证和授权。

| 模板 | 用途 |
| --- | --- |
| [项目入口](agent-entry.md) | 确定任务路由、不可降级规则和真实验证入口 |
| [任务卡](task-brief.md) | 保存跨步骤目标、范围、验收与真正未决项 |
| [当前交接](current-context.md) | 保留有效事实与下一步，替换旧状态 |
| [验证报告](verification-report.md) | 区分通过、失败、跳过和未运行 |
| [设计决策](design-decision.md) | 说明具体收益、代价、证据与重审条件 |

先看 [上下文组织建议](../docs/engineering/CONTEXT.md)，再按自己的流程删改，将占位内容替换为具体目标、约束和验证入口。

本文档仓库的维护入口是 [AGENTS.md](../AGENTS.md)。
