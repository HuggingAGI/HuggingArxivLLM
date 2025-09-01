# 无需优质答案也能鼓励良好过程：面向LLM智能体规划的强化学习

发布时间：2025年08月27日

`Agent` `基础理论`

> Encouraging Good Processes Without the Need for Good Answers: Reinforcement Learning for LLM Agent Planning

# 摘要

> 大型语言模型（LLM）智能体的功能主要取决于两大核心能力：行动规划与答案总结。其中行动规划作为核心能力，直接决定智能体的性能表现。但当前主流训练范式多采用端到端多目标优化，将这两种能力联合训练。该范式存在两大痛点：优化目标分配失衡与可验证数据匮乏，导致智能体的规划能力难以提升。为应对这些问题，我们提出工具使用奖励强化学习（RLTR）——一种通过解耦训练过程，实现规划模块聚焦式单目标优化的全新框架。其核心创新在于，RLTR引入基于工具使用完整性的奖励信号，可直接衡量工具调用序列的质量。相比评估最终响应内容，该方法能提供更直接可靠的训练信号，因此不再依赖可验证数据。实验结果显示，与端到端基线模型相比，RLTR的规划性能提升了8%-12%。更重要的是，规划能力的增强进一步推动整个智能体系统的最终响应质量提升5%-6%。

> The functionality of Large Language Model (LLM) agents is primarily determined by two capabilities: action planning and answer summarization. The former, action planning, is the core capability that dictates an agent's performance. However, prevailing training paradigms employ end-to-end, multi-objective optimization that jointly trains both capabilities. This paradigm faces two critical challenges: imbalanced optimization objective allocation and scarcity of verifiable data, making it difficult to enhance the agent's planning capability. To address these challenges, we propose Reinforcement Learning with Tool-use Rewards (RLTR), a novel framework that decouples the training process to enable a focused, single-objective optimization of the planning module. Crucially, RLTR introduces a reward signal based on tool-use completeness to directly evaluate the quality of tool invocation sequences. This method offers a more direct and reliable training signal than assessing the final response content, thereby obviating the need for verifiable data. Our experiments demonstrate that RLTR achieves an 8%-12% improvement in planning performance compared to end-to-end baselines. Moreover, this enhanced planning capability, in turn, translates to a 5%-6% increase in the final response quality of the overall agent system.

[Arxiv](https://arxiv.org/abs/2508.19598)