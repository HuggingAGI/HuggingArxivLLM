# AutoMisty：一个多智能体 LLM 框架，专为 Misty 社交机器人设计的自动化代码生成工具

发布时间：2025年03月09日

`Agent` `社交机器人` `人工智能`

> AutoMisty: A Multi-Agent LLM Framework for Automated Code Generation in the Misty Social Robot

# 摘要

> 社交机器人的开放API为用户提供了自定义开放领域交互的能力。然而，这一功能对编程经验不足的用户来说仍然难以触及。本研究推出AutoMisty——首个基于大型语言模型（LLMs）的多智能体协作框架，通过自然语言指令即可轻松生成可执行的Misty机器人代码。AutoMisty由四个专门的智能体模块构成，分别负责任务分解、分配、问题解决和结果合成。每个智能体均采用双层优化机制，结合自我反思实现迭代优化，并通过人工介入确保与用户偏好高度契合。AutoMisty的透明推理过程让用户能够通过自然语言反馈逐步完善任务，确保精准执行。为验证AutoMisty的效果，我们设计了一个涵盖四个复杂度级别的基准任务集，并在真实Misty机器人环境中进行了实验。大量评估结果表明，AutoMisty不仅能够持续生成高质量代码，还能实现精准的代码控制，其性能远超直接使用ChatGPT-4o和ChatGPT-o1进行推理。所有代码、优化后的API及实验视频将通过以下网页公开发布：https://wangxiaoshawn.github.io/AutoMisty.html

> The social robot's open API allows users to customize open-domain interactions. However, it remains inaccessible to those without programming experience. In this work, we introduce AutoMisty, the first multi-agent collaboration framework powered by large language models (LLMs), to enable the seamless generation of executable Misty robot code from natural language instructions. AutoMisty incorporates four specialized agent modules to manage task decomposition, assignment, problem-solving, and result synthesis. Each agent incorporates a two-layer optimization mechanism, with self-reflection for iterative refinement and human-in-the-loop for better alignment with user preferences. AutoMisty ensures a transparent reasoning process, allowing users to iteratively refine tasks through natural language feedback for precise execution. To evaluate AutoMisty's effectiveness, we designed a benchmark task set spanning four levels of complexity and conducted experiments in a real Misty robot environment. Extensive evaluations demonstrate that AutoMisty not only consistently generates high-quality code but also enables precise code control, significantly outperforming direct reasoning with ChatGPT-4o and ChatGPT-o1. All code, optimized APIs, and experimental videos will be publicly released through the webpage: https://wangxiaoshawn.github.io/AutoMisty.html

[Arxiv](https://arxiv.org/abs/2503.06791)