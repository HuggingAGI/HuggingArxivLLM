# FLOW：一个能同时提升推荐效果和用户代理表现的反馈循环框架

发布时间：2024年10月25日

`Agent` `智能体`

> FLOW: A Feedback LOop FrameWork for Simultaneously Enhancing Recommendation and User Agents

# 摘要

> 由大型语言模型驱动的智能体展现出了非凡的推理和执行能力，吸引着研究人员在推荐领域挖掘其潜力。以往的研究多侧重于单独提升推荐智能体或用户智能体的能力，却未考虑二者之间的交互与协作。为此，我们提出了一个名为 FLOW 的新颖框架，借由引入反馈回路来达成推荐智能体与用户智能体的协作。具体来说，推荐智能体通过剖析用户智能体对先前推荐项目的反馈，来优化对用户偏好的理解；而用户智能体则借助推荐项目，深挖用户潜在兴趣。这一迭代优化过程增强了推荐智能体和用户智能体的推理能力，得以实现更精确的推荐和更精准的用户行为模拟。为了验证反馈回路的有效性，我们在三个广泛应用的推荐领域数据集中，对推荐性能和用户模拟性能进行了评估。实验结果显示，反馈回路能够同步提升推荐智能体和用户智能体的性能。

> Agents powered by large language models have shown remarkable reasoning and execution capabilities, attracting researchers to explore their potential in the recommendation domain. Previous studies have primarily focused on enhancing the capabilities of either recommendation agents or user agents independently, but have not considered the interaction and collaboration between recommendation agents and user agents. To address this gap, we propose a novel framework named FLOW, which achieves collaboration between the recommendation agent and the user agent by introducing a feedback loop. Specifically, the recommendation agent refines its understanding of the user's preferences by analyzing the user agent's feedback on previously suggested items, while the user agent leverages suggested items to uncover deeper insights into the user's latent interests. This iterative refinement process enhances the reasoning capabilities of both the recommendation agent and the user agent, enabling more precise recommendations and a more accurate simulation of user behavior. To demonstrate the effectiveness of the feedback loop, we evaluate both recommendation performance and user simulation performance on three widely used recommendation domain datasets. The experimental results indicate that the feedback loop can simultaneously improve the performance of both the recommendation and user agents.

[Arxiv](https://arxiv.org/abs/2410.20027)