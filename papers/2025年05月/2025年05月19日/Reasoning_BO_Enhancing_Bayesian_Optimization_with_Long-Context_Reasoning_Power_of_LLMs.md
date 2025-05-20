# # 推理增强BO：结合LLMs的长上下文推理能力优化贝叶斯方法
贝叶斯优化作为一种高效的黑箱函数优化技术，如今通过融合大型语言模型（LLMs）的长上下文推理能力，展现出更强大的优化潜力。这种方法不仅提升了优化效率，还在复杂问题处理上表现出色。

发布时间：2025年05月19日

`LLM应用`

> Reasoning BO: Enhancing Bayesian Optimization with Long-Context Reasoning Power of LLMs

# 摘要

> 在科学与工业领域，优化复杂且昂贵的黑箱函数是许多现实应用的核心需求。贝叶斯优化（BO）为此类问题提供了一个高效的解决方案框架。然而，传统BO方法存在两个主要局限：容易陷入局部最优，且缺乏可解释性。为突破这些限制，本研究提出了一种创新的推理BO框架，通过结合推理模型、多智能体系统和知识图谱，实现优化过程中的实时知识积累与策略优化。借助大型语言模型（LLMs）强大的推理与上下文理解能力，我们为BO过程注入了更智能的指导机制。随着优化的深入，推理BO不仅实时推荐采样位置，还能基于科学理论提供关键见解，从而在搜索空间中更高效地发现优质解。通过在10个涵盖合成函数与复杂工业场景的任务中进行系统测试，我们验证了该框架的优势：它能够通过实时推理与假设迭代逐步优化采样策略，精准定位高潜力探索区域。这一成果充分展现了LLMs在优化问题中的强大推理与学习潜力。例如，在直接芳基化任务中，我们的方法将产率显著提升至60.7%，而传统BO仅能达到25.2%。此外，研究还发现，经过强化学习微调的小型LLMs同样能够达到与大型模型相当的性能水平。这一突破为实现更高效、更具可行性的自动化科学研究提供了新的可能性。


> Many real-world scientific and industrial applications require the optimization of expensive black-box functions. Bayesian Optimization (BO) provides an effective framework for such problems. However, traditional BO methods are prone to get trapped in local optima and often lack interpretable insights. To address this issue, this paper designs Reasoning BO, a novel framework that leverages reasoning models to guide the sampling process in BO while incorporating multi-agent systems and knowledge graphs for online knowledge accumulation. By integrating the reasoning and contextual understanding capabilities of Large Language Models (LLMs), we can provide strong guidance to enhance the BO process. As the optimization progresses, Reasoning BO provides real-time sampling recommendations along with critical insights grounded in plausible scientific theories, aiding in the discovery of superior solutions within the search space. We systematically evaluate our approach across 10 diverse tasks encompassing synthetic mathematical functions and complex real-world applications. The framework demonstrates its capability to progressively refine sampling strategies through real-time insights and hypothesis evolution, effectively identifying higher-performing regions of the search space for focused exploration. This process highlights the powerful reasoning and context-learning abilities of LLMs in optimization scenarios. For example, in the Direct Arylation task, our method increased the yield to 60.7%, whereas traditional BO achieved only a 25.2% yield. Furthermore, our investigation reveals that smaller LLMs, when fine-tuned through reinforcement learning, can attain comparable performance to their larger counterparts. This enhanced reasoning capability paves the way for more efficient automated scientific experimentation while maintaining computational feasibility.

[Arxiv](https://arxiv.org/abs/2505.12833)