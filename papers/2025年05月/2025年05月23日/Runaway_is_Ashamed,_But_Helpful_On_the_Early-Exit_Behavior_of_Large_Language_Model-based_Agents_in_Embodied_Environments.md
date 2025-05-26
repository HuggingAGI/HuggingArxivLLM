# 逃跑者虽感惭愧，却乐于助人：论大型语言模型智能体在具身环境中的提前退出行为

发布时间：2025年05月23日

`Agent` `人工智能` `智能体`

> Runaway is Ashamed, But Helpful: On the Early-Exit Behavior of Large Language Model-based Agents in Embodied Environments

# 摘要

> 大型语言模型（LLMs）驱动的智能体在复杂环境中表现出色，但在多轮交互中常效率低下，容易陷入重复循环或发出无效指令，导致计算资源浪费。与单纯依赖轨迹学习不同，我们探索基于LLM的智能体的早期退出行为。提出两种互补方法：1. 一种【数学公式】方法，在生成过程中注入退出指令；2. 一种【数学公式】方法，通过验证任务完成情况决定何时终止智能体的试验。我们引入两个指标评估早期退出机制：一个衡量【数学公式】的减少作为积极影响，另一个评估【数学公式】作为消极影响。实验表明，在5个具身环境中使用4种不同LLM，效率显著提升，性能仅略有下降。我们还验证了一种策略：在早期退出智能体之后由更强的智能体接手，从而在相同总步数下实现更好性能。我们将发布代码支持进一步研究。


> Agents powered by large language models (LLMs) have demonstrated strong planning and decision-making capabilities in complex embodied environments. However, such agents often suffer from inefficiencies in multi-turn interactions, frequently trapped in repetitive loops or issuing ineffective commands, leading to redundant computational overhead. Instead of relying solely on learning from trajectories, we take a first step toward exploring the early-exit behavior for LLM-based agents. We propose two complementary approaches: 1. an $\textbf{intrinsic}$ method that injects exit instructions during generation, and 2. an $\textbf{extrinsic}$ method that verifies task completion to determine when to halt an agent's trial. To evaluate early-exit mechanisms, we introduce two metrics: one measures the reduction of $\textbf{redundant steps}$ as a positive effect, and the other evaluates $\textbf{progress degradation}$ as a negative effect. Experiments with 4 different LLMs across 5 embodied environments show significant efficiency improvements, with only minor drops in agent performance. We also validate a practical strategy where a stronger agent assists after an early-exit agent, achieving better performance with the same total steps. We will release our code to support further research.

[Arxiv](https://arxiv.org/abs/2505.17616)