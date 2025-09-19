# 知识驱动的大型语言模型（LLMs）自适应协作：增强医疗决策的新路径

发布时间：2025年09月18日

`Agent` `医疗健康`

> A Knowledge-driven Adaptive Collaboration of LLMs for Enhancing Medical Decision-making

# 摘要

> 医疗决策往往需要整合多个临床专科的知识，这通常通过多学科团队协作完成。受这种协作模式的启发，近期研究将大型语言模型（LLMs）应用于多智能体协作框架，以模拟专家团队协作。尽管这些方法通过智能体交互增强了推理能力，但静态预分配的角色限制了它们的适应性和动态知识整合能力。为解决这些问题，我们提出KAMAC——一种知识驱动的自适应多智能体协作框架，它能让LLM智能体根据不断变化的诊断情境动态组建和扩展专家团队。KAMAC从一个或多个专家智能体起步，通过知识驱动的讨论识别知识空白，并根据需要招募更多专家来填补这些空白。这使得在复杂临床场景中实现灵活、可扩展的协作成为可能，决策则通过审查智能体的最新评论最终确定。在两个真实世界医疗基准数据集上的实验显示，KAMAC显著优于单智能体和先进多智能体方法，尤其在需要动态跨专科专业知识的复杂临床场景（如癌症预后）中表现突出。我们的代码已公开，地址为：https://github.com/XiaoXiao-Woo/KAMAC。

> Medical decision-making often involves integrating knowledge from multiple clinical specialties, typically achieved through multidisciplinary teams. Inspired by this collaborative process, recent work has leveraged large language models (LLMs) in multi-agent collaboration frameworks to emulate expert teamwork. While these approaches improve reasoning through agent interaction, they are limited by static, pre-assigned roles, which hinder adaptability and dynamic knowledge integration. To address these limitations, we propose KAMAC, a Knowledge-driven Adaptive Multi-Agent Collaboration framework that enables LLM agents to dynamically form and expand expert teams based on the evolving diagnostic context. KAMAC begins with one or more expert agents and then conducts a knowledge-driven discussion to identify and fill knowledge gaps by recruiting additional specialists as needed. This supports flexible, scalable collaboration in complex clinical scenarios, with decisions finalized through reviewing updated agent comments. Experiments on two real-world medical benchmarks demonstrate that KAMAC significantly outperforms both single-agent and advanced multi-agent methods, particularly in complex clinical scenarios (i.e., cancer prognosis) requiring dynamic, cross-specialty expertise. Our code is publicly available at: https://github.com/XiaoXiao-Woo/KAMAC.

[Arxiv](https://arxiv.org/abs/2509.14998)