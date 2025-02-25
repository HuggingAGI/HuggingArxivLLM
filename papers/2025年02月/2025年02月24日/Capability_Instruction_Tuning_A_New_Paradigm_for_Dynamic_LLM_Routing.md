# 动态LLM路由新范式：能力指令微调

发布时间：2025年02月24日

`LLM应用` `人工智能`

> Capability Instruction Tuning: A New Paradigm for Dynamic LLM Routing

# 摘要

> 大型语言模型（LLMs）展现出类似人类的指令遵循能力，尤其在超过1000亿参数的模型中表现尤为突出。一些较小规模但资源高效的LLMs的综合能力可以处理大多数大型LLMs擅长的指令。我们研究了如何为每个指令路由表现最佳的LLM，以实现整体性能的提升。我们开发了一种新的范式，通过模型能力表示、用户指令和性能查询提示来构建能力指令，从而评估模型性能。为了从能力指令中学习，我们引入了一种新的端到端框架，称为基于能力测试的模型选择（Model-SAT），该框架根据不同模型擅长或难以处理的内容生成正负样本。Model-SAT采用了一种模型能力编码器，将其模型表示扩展到轻量级LLM。实验结果显示，Model-SAT能够理解候选模型的性能维度，并提供它们处理各种指令的能力概率。此外，在部署过程中，新模型可以在50个任务上快速推断其能力测试结果，每个任务包含20个样本。Model-SAT在无需候选推理的情况下实现了最先进的模型路由，并在现实世界中新模型发布场景中表现出色。代码可在https://github.com/Now-Join-Us/CIT-LLM-Routing获取

> Large Language Models (LLMs) have demonstrated human-like instruction-following abilities, particularly those exceeding 100 billion parameters. The combined capability of some smaller, resource-friendly LLMs can address most of the instructions that larger LLMs excel at. In this work, we explore how to route the best-performing LLM for each instruction to achieve better overall performance. We develop a new paradigm, constructing capability instructions with model capability representation, user instruction, and performance inquiry prompts to assess the performance. To learn from capability instructions, we introduce a new end-to-end framework called Model Selection with Aptitude Test (Model-SAT), which generates positive and negative samples based on what different models perform well or struggle with. Model-SAT uses a model capability encoder that extends its model representation to a lightweight LLM. Our experiments show that Model-SAT understands the performance dimensions of candidate models and provides the probabilities of their capability to handle various instructions. Additionally, during deployment, a new model can quickly infer its aptitude test results across 50 tasks, each with 20 shots. Model-SAT performs state-of-the-art model routing without candidate inference and in real-world new model-released scenarios. The code is available at https://github.com/Now-Join-Us/CIT-LLM-Routing

[Arxiv](https://arxiv.org/abs/2502.17282)