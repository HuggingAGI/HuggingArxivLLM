# MARS：一个结合苏格拉底式引导的多智能体框架，实现自动提示优化

发布时间：2025年03月21日

`LLM应用` `问答系统`

> MARS: A Multi-Agent Framework Incorporating Socratic Guidance for Automated Prompt Optimization

# 摘要

> 大型语言模型的基本问答流程是输入提示并获得回答，提示的质量直接影响回答的效果。自动提示优化（APO）的目标是突破手动设计提示的认知局限，探索更广阔的提示设计空间。然而，现有APO方法存在固定模板灵活性差和提示空间搜索效率低的两大问题。为此，我们提出结合苏格拉底式指导的多智能体框架MARS，该框架采用多智能体融合技术实现自动规划，辅以逐步持续优化和评估。具体而言，MARS由七个功能各异的智能体组成，它们自主运用规划器设计灵活的优化路径。此外，MARS采用教师-批评者-学生式的苏格拉底对话模式，在有效搜索中迭代优化提示。我们在多种数据集上进行了大量实验验证方法有效性，并通过额外分析实验评估模型进展和可解释性。

> The basic question-answering format of large language models involves inputting a prompt and receiving a response, and the quality of the prompt directly impacts the effectiveness of the response. Automated Prompt Optimization (APO) aims to break free from the cognitive biases of manually designed prompts and explores a broader design space for prompts. However, existing APO methods suffer from limited flexibility of fixed templates and inefficient search in prompt spaces as key issues. To this end, we propose a Multi-Agent framework Incorporating Socratic guidance (MARS), which utilizes multi-agent fusion technology for automatic planning, with gradual continuous optimization and evaluation. Specifically, MARS comprises seven agents, each with distinct functionalities, which autonomously use the Planner to devise an optimization path that ensures flexibility. Additionally, it employs a Teacher-Critic-Student Socratic dialogue pattern to iteratively optimize the prompts while conducting effective search. We conduct extensive experiments on various datasets to validate the effectiveness of our method, and perform additional analytical experiments to assess the model's advancement as well as the interpretability.

[Arxiv](https://arxiv.org/abs/2503.16874)