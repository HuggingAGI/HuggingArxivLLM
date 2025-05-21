# AgentSGEN: 基于多智能体的 LLM 循环机制实现语义协作与合成数据生成

发布时间：2025年05月07日

`Agent`

> AgentSGEN: Multi-Agent LLM in the Loop for Semantic Collaboration and GENeration of Synthetic Data

# 摘要

> 危险场景数据的稀缺性严重阻碍了AI在安全关键领域的训练，特别是在建筑安全等场景中，伦理和后勤障碍让现实数据收集难上加难。这迫切需要一个端到端的框架来生成合成数据以填补这一空白。现有方法虽然能生成合成场景，但往往缺乏足够的语义深度，影响了实际效果。为此，我们提出了一种开创性的多智能体框架，通过两个智能体的迭代闭环协作来实现：评估器智能体作为基于LLM的裁判，确保语义一致性和安全约束；编辑器智能体根据指导生成和优化场景。借助LLM的强大推理和常识能力，这种协作设计能够生成专门针对安全关键场景的合成图像。实验表明，该框架可以根据实际需求生成实用场景，有效弥补传统方法的不足，实现安全要求与视觉语义的平衡。这一迭代过程不仅有望提供稳健且视觉上合理的模拟，更为解决多媒体安全应用中的数据稀缺性挑战提供了全新思路。

> The scarcity of data depicting dangerous situations presents a major obstacle to training AI systems for safety-critical applications, such as construction safety, where ethical and logistical barriers hinder real-world data collection. This creates an urgent need for an end-to-end framework to generate synthetic data that can bridge this gap. While existing methods can produce synthetic scenes, they often lack the semantic depth required for scene simulations, limiting their effectiveness. To address this, we propose a novel multi-agent framework that employs an iterative, in-the-loop collaboration between two agents: an Evaluator Agent, acting as an LLM-based judge to enforce semantic consistency and safety-specific constraints, and an Editor Agent, which generates and refines scenes based on this guidance. Powered by LLM's capabilities to reasoning and common-sense knowledge, this collaborative design produces synthetic images tailored to safety-critical scenarios. Our experiments suggest this design can generate useful scenes based on realistic specifications that address the shortcomings of prior approaches, balancing safety requirements with visual semantics. This iterative process holds promise for delivering robust, aesthetically sound simulations, offering a potential solution to the data scarcity challenge in multimedia safety applications.

[Arxiv](https://arxiv.org/abs/2505.13466)