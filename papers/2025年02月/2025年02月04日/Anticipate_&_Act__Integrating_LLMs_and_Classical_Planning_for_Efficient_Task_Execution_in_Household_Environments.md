# 预见与行动：融合大型语言模型与经典规划，打造家庭环境下的高效任务执行方案

发布时间：2025年02月04日

`Agent

理由：这篇论文主要讨论了如何利用辅助代理（Agent）来预测和规划家务任务，以提高效率。虽然提到了使用大型语言模型（LLMs）进行任务预测，但核心内容集中在代理的行为规划和任务执行上，因此更适合归类为Agent。` `家庭服务` `任务规划`

> Anticipate & Act : Integrating LLMs and Classical Planning for Efficient Task Execution in Household Environments

# 摘要

> 辅助代理在执行家务任务（如整理床铺或做早餐）时，通常一次只完成一个任务。然而，通过预测即将到来的任务并计算一个共同完成这些任务的动作序列，可以显著提高效率。现有的任务预测方法依赖于数据驱动的深度网络和大型语言模型（LLMs），但它们主要在高层次任务层面操作，且需要大量训练数据。我们的框架通过少量提示利用LLMs的通用知识进行高层次任务预测，并将这些预测任务作为目标，在经典规划系统中生成更细粒度的动作序列，共同实现这些目标。我们在VirtualHome环境中的现实场景中验证了框架的有效性，结果显示，与不考虑未来任务的系统相比，执行时间减少了31%。

> Assistive agents performing household tasks such as making the bed or cooking breakfast often compute and execute actions that accomplish one task at a time. However, efficiency can be improved by anticipating upcoming tasks and computing an action sequence that jointly achieves these tasks. State-of-the-art methods for task anticipation use data-driven deep networks and Large Language Models (LLMs), but they do so at the level of high-level tasks and/or require many training examples. Our framework leverages the generic knowledge of LLMs through a small number of prompts to perform high-level task anticipation, using the anticipated tasks as goals in a classical planning system to compute a sequence of finer-granularity actions that jointly achieve these goals. We ground and evaluate our framework's abilities in realistic scenarios in the VirtualHome environment and demonstrate a 31% reduction in execution time compared with a system that does not consider upcoming tasks.

[Arxiv](https://arxiv.org/abs/2502.02066)