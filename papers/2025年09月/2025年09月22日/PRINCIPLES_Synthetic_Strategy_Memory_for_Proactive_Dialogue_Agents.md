# # 原则：主动对话智能体的合成策略记忆

发布时间：2025年09月22日

`Agent` `基础理论`

> PRINCIPLES: Synthetic Strategy Memory for Proactive Dialogue Agents

# 摘要

> 基于大型语言模型（LLMs）的对话智能体在主动对话领域展现出良好性能，这类对话需要有效的策略规划。然而，现有的主动对话策略规划方法存在诸多局限：策略覆盖范围较窄、规划过程存在偏好偏差，且依赖成本高昂的额外训练。为解决这些问题，我们提出PRINCIPLES——一种面向主动对话智能体的合成策略记忆机制。PRINCIPLES通过离线自博弈模拟生成，作为可复用知识在推理阶段指导策略规划，无需额外训练和数据标注。我们在情感支持和说服两大领域对PRINCIPLES展开评估，结果显示其相较强大基线模型实现了稳定提升。此外，在扩展且更多样化的评估场景下，PRINCIPLES仍能保持稳健性。项目详情参见：https://huggingface.co/spaces/kimnamssya/Principles。

> Dialogue agents based on large language models (LLMs) have shown promising performance in proactive dialogue, which requires effective strategy planning. However, existing approaches to strategy planning for proactive dialogue face several limitations: limited strategy coverage, preference bias in planning, and reliance on costly additional training. To address these, we propose PRINCIPLES: a synthetic strategy memory for proactive dialogue agents. PRINCIPLES is derived through offline self-play simulations and serves as reusable knowledge that guides strategy planning during inference, eliminating the need for additional training and data annotation. We evaluate PRINCIPLES in both emotional support and persuasion domains, demonstrating consistent improvements over strong baselines. Furthermore, PRINCIPLES maintains its robustness across extended and more diverse evaluation settings. See our project page at https://huggingface.co/spaces/kimnamssya/Principles.

[Arxiv](https://arxiv.org/abs/2509.17459)