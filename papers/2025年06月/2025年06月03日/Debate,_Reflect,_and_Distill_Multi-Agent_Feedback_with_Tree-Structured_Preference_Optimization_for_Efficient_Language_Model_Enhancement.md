# 辩论、反思与蒸馏：多智能体反馈融合树状结构偏好优化，提升语言模型效能

发布时间：2025年06月03日

`LLM理论

摘要中讨论了模型训练方法和框架的改进，属于模型理论和训练技术的范畴。` `人工智能`

> Debate, Reflect, and Distill: Multi-Agent Feedback with Tree-Structured Preference Optimization for Efficient Language Model Enhancement

# 摘要

> 大型语言模型（LLMs）在知识密集型和复杂推理任务中表现卓越，但其高计算成本限制了实际应用。将大型模型精简为小型模型虽是可行方案，但现有技术如静态知识蒸馏、资源密集型的人类反馈强化学习或有限的自我反思，难以带来显著且持久的性能提升。本文提出了一种创新的“辩论与反思”（D&R）框架，通过小型模型与更强教师模型之间的多轮辩论，提取可操作反馈（如错误分析和纠正策略）来指导学生模型学习。此外，我们引入树状直接偏好优化（T-DPO），高效利用这些辩论记录，将交互组织成层级格式，实现更有效的训练。在多个NLP基准测试中，我们的方法显著提升了小型模型的准确性、稳健性和泛化能力，远超传统基线。

> Large Language Models (LLMs) continue to set new standards in knowledge-intensive and complex reasoning tasks, yet their high computational demands limit widespread adoption. While distilling large models into smaller ones offers a sustainable solution, current techniques--such as static knowledge distillation, resource-intensive reinforcement learning from human feedback, or limited self-reflection--struggle to yield substantial and lasting performance gains. In this paper, we present a novel Debate and Reflect (D&R) framework that orchestrates multi-turn debates between smaller models and stronger teacher models, eliciting actionable feedback (e.g., error analysis, corrective strategies) to guide student models. Further, we introduce Tree-structured Direct Preference Optimization (T-DPO) to efficiently leverage these debate logs, organizing interactions into a hierarchical format for effective training. Empirical evaluations across diverse NLP benchmarks demonstrate that our approach significantly improves smaller-model accuracy, robustness, and generalization, outperforming conventional baselines by a large margin.

[Arxiv](https://arxiv.org/abs/2506.03541)