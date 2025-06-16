# # 协作式 LLM 推理通过规划实现高效推理

发布时间：2025年06月13日

`LLM应用` `人工智能` `模型协作优化`

> Collaborative LLM Inference via Planning for Efficient Reasoning

# 摘要

> 大型语言模型（LLMs）擅长处理复杂推理任务，但参数规模超过1000亿的模型通常只能通过付费API访问，成本高昂。相比之下，开源的小型LLMs（参数规模低于30亿）免费且易于本地部署（如在8G显存的单GPU上），但推理能力有限。这种取舍引发了一个问题：能否让小型（免费）和大型（昂贵）模型在测试时协作，优势互补？我们提出了一种测试时协作框架，其中规划模型首先生成一个精炼的高层次问题抽象计划。该计划作为轻量级中间件，指导推理模型生成完整解决方案。小型和大型模型轮流担任规划模型和推理模型角色，在多轮级联中交换计划，共同解决复杂任务。我们的方法在准确性上可与强大专有模型单独使用相媲美，同时大幅减少对付费推理的依赖。这些结果表明，规划是现实世界部署约束下编排成本意识跨模型推理的有效先验。


> Large language models (LLMs) excel at complex reasoning tasks, but those with strong capabilities (e.g., whose numbers of parameters are larger than 100B) are often accessible only through paid APIs, making them too costly for applications of frequent use. In contrast, smaller open-sourced LLMs (e.g., whose numbers of parameters are less than 3B) are freely available and easy to deploy locally (e.g., under a single GPU having 8G VRAM), but lack suff icient reasoning ability. This trade-off raises a natural question: can small (free) and large (costly) models collaborate at test time to combine their strengths? We propose a test-time collaboration framework in which a planner model first generates a plan, defined as a distilled and high-level abstraction of the problem.
  This plan serves as a lightweight intermediate that guides a reasoner model, which generates a complete solution. Small and large models take turns acting as planner and reasoner, exchanging plans in a multi-round cascade to collaboratively solve complex tasks. Our method achieves accuracy comparable to strong proprietary models alone, while significantly reducing reliance on paid inference. These results highlight planning as an effective prior for orchestrating cost-aware, cross-model inference under real-world deployment constraints.

[Arxiv](https://arxiv.org/abs/2506.11578)