# Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development
# 协作节约：资源敏感型多智能体协作在软件开发中的应用

发布时间：2025年05月27日

`Agent

理由：这篇论文专注于多智能体系统的优化，特别是资源感知的多智能体系统，探讨了如何通过经验知识提升效率。虽然提到了LLMs，但核心在于多智能体协作，因此归类为Agent。` `软件开发`

> Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development

# 摘要

> 大型语言模型（LLMs）和自主代理在多个领域展现出卓越的能力。然而，独立的代理在处理复杂任务时往往面临限制，尤其是在需要大量交互和计算资源的情况下。尽管多智能体系统（MAS）通过任务分解、迭代沟通和角色专业化等机制缓解了部分限制，但它们通常缺乏资源意识，导致效率低下。为了解决这些问题，我们提出了一种资源感知的多智能体系统——Co-Saving（意为多个代理协同参与资源节约活动），通过利用经验知识提升效率和解决方案质量。我们的创新在于引入了“捷径”——从历史成功轨迹中学习得到的指令转换，跳过冗余推理代理并加速问题解决。实验表明，与现有方法相比，我们的方法在软件开发任务中具有显著优势。具体而言，与最先进的MAS ChatDev相比，我们减少了50.85%的token使用量，并将整体代码质量提升了10.06%。

> Recent advancements in Large Language Models (LLMs) and autonomous agents have demonstrated remarkable capabilities across various domains. However, standalone agents frequently encounter limitations when handling complex tasks that demand extensive interactions and substantial computational resources. Although Multi-Agent Systems (MAS) alleviate some of these limitations through collaborative mechanisms like task decomposition, iterative communication, and role specialization, they typically remain resource-unaware, incurring significant inefficiencies due to high token consumption and excessive execution time. To address these limitations, we propose a resource-aware multi-agent system -- Co-Saving (meaning that multiple agents collaboratively engage in resource-saving activities), which leverages experiential knowledge to enhance operational efficiency and solution quality. Our key innovation is the introduction of "shortcuts" -- instructional transitions learned from historically successful trajectories -- which allows to bypass redundant reasoning agents and expedite the collective problem-solving process. Experiments for software development tasks demonstrate significant advantages over existing methods. Specifically, compared to the state-of-the-art MAS ChatDev, our method achieves an average reduction of 50.85% in token usage, and improves the overall code quality by 10.06%.

[Arxiv](https://arxiv.org/abs/2505.21898)