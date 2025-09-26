# 大型语言模型智能体强化学习的树搜索

发布时间：2025年09月25日

`强化学习` `基础理论`

> Tree Search for LLM Agent Reinforcement Learning

# 摘要

> 强化学习（RL）的最新进展极大地提升了大型语言模型（LLMs）的智能体能力。在长期多轮智能体任务中，现有仅依赖结果奖励的方法往往存在监督信号稀疏的问题。为应对这一挑战，我们提出基于树的分组相对策略优化（Tree-GRPO）——一种基于树搜索的分组智能体强化学习方法，树中的每个节点代表智能体完整的交互步骤。通过共享公共前缀，树搜索采样能在固定的token或工具调用预算下生成更多轨迹。此外，我们发现树状轨迹天然支持构建逐步的过程监督信号，即便仅利用结果奖励。基于此，Tree-GRPO在树内与树间层面估计分组相对优势。理论分析表明，树内层面分组相对策略优化的目标与步骤级直接偏好学习的目标等价。在11个数据集和3类问答任务上的实验结果显示，本文提出的基于树的强化学习方法性能优于基于链的强化学习方法。

> Recent advances in reinforcement learning (RL) have significantly enhanced the agentic capabilities of large language models (LLMs). In long-term and multi-turn agent tasks, existing approaches driven solely by outcome rewards often suffer from the problem of sparse supervision. To address the challenge, we propose Tree-based Group Relative Policy Optimization (Tree-GRPO), a grouped agent RL method based on tree search, where each tree node represents the complete agent interaction step. By sharing common prefixes, the tree search sampling increases the number of rollouts achievable within a fixed budget of tokens or tool calls. Moreover, we find that the tree-structured trajectory naturally allows the construction of step-wise process supervised signals even using only the outcome reward. Based on this, Tree-GRPO estimates the grouped relative advantages both on intra-tree and inter-tree levels. Through theoretical analysis, we demonstrate that the objective of intra-tree level group relative policy optimization is equivalent to that of step-level direct preference learning. Experiments across 11 datasets and 3 types of QA tasks demonstrate the superiority of the proposed tree-based RL over the chain-based RL method.

[Arxiv](https://arxiv.org/abs/2509.21240)