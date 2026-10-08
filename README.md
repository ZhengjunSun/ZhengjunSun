# SunZhengjun · 工业场景多智能体与大模型应用

关注通信故障分析、炼厂与原油采购决策、可追溯知识应用。
工程重点：任务编排、优化约束、证据检索、评测与人工审批。

Multi-agent & LLM application engineering for industrial workflows.

教育背景：北京邮电大学本科 · 中国人民大学硕士 · 计算机科学与技术。

## 代表方向

| 项目 | 当前实现 | 验证与边界 |
|---|---|---|
| [通信日志](https://github.com/ZhengjunSun/telecom-log-agent) | 日志预处理、规则驱动分析、故障证据报告 | 合成示例与测试；尚非生产根因诊断系统 |
| [炼厂决策](https://github.com/ZhengjunSun/refinery-decision-agents) | 整数批次枚举优化、约束检查、决策说明 | 可运行示例；尚非工业规模求解器 |
| [Agent 记忆评测](https://github.com/ZhengjunSun/agent-memory-bench) | SQLite 事实检索与合成评测 | [报告与局限](https://github.com/ZhengjunSun/agent-memory-bench/blob/main/docs/benchmark.md)；满分不代表真实对话泛化 |

## 工程原型与实验

- [工业 Agent 工作台](https://github.com/ZhengjunSun/industrial-superagent-workbench)：固定规则规划、顺序执行、SQLite 状态与审批、浏览器控制台。单进程原型，不是分布式平台。
- [多模态运维助手](https://github.com/ZhengjunSun/multimodal-ops-copilot)：文件接入、模型适配与进度流；不是完整实时语音系统。
- [法律 RAG](https://github.com/ZhengjunSun/prosecution-legal-rag)：虚构材料上的检索、引用与拒答演示，不提供法律意见。
- [模型网关](https://github.com/ZhengjunSun/llm-gateway-control-plane)、[上下文实验](https://github.com/ZhengjunSun/context-engineering-bench)、[A2A 风格实验](https://github.com/ZhengjunSun/a2a-agent-network)：独立工程练习，能力以代码为准。
- [执行准入策略](https://github.com/ZhengjunSun/secure-agent-sandbox)：检查请求，不提供运行时隔离。
- [LoRA 实验准备](https://github.com/ZhengjunSun/domain-lora-training-lab)：数据与配置准备，尚未提供训练权重及实测提升。

## 当前建设重点（尚未完成）

1. 通信事故端到端回放：规则基线、Agent 对比、失败恢复与审批回归。
2. 炼厂求解器接入：不可行案例与敏感性分析。
3. 记忆困难评测：相似实体、时间更新、无答案问题与逐条失败报告。

## 开源协作

[llmsectest #17](https://github.com/wehnsdaefflae/llmsectest/pull/17)：OWASP 示例标签与回归测试贡献。状态以 PR 页面为准，不将提交等同于合并。

## 实现原则与来源

LLM 负责解释与协调；确定性代码、优化求解和人工审批约束关键决策。
离线测试、真实模型实验与生产验证是不同证据，不互相替代。

这些作品是独立公开技术重建与实验，使用合成或合法公开材料，不包含雇主或客户的代码、数据、内部规则和配置，不代表其生产系统或业务效果。
