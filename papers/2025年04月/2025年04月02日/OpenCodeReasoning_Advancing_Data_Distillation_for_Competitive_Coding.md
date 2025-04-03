# # 开放代码推理：提升数据蒸馏在竞赛编程中的应用

发布时间：2025年04月02日

`LLM应用` `代码生成`

> OpenCodeReasoning: Advancing Data Distillation for Competitive Coding

# 摘要

> 自基于推理的大型语言模型诞生以来，研究者们通过将推理能力蒸馏到学生模型中取得了巨大成功。这些技术显著缩小了推理能力和标准LLM在编码任务上的差距。然而，许多关于推理模型蒸馏的进展仍然受到专有数据集的限制，或缺乏对数据整理、过滤和后续训练的详细说明。为解决这一问题，我们构建了一个更优质的监督微调（SFT）数据集，并在不同规模的模型中实现了最先进的编码能力结果。我们的蒸馏模型仅通过SFT在LiveCodeBench上达到了61.8%的准确率，在CodeContests上达到了24.6%，超过了基于强化学习训练的替代模型。随后，我们对构建数据集所用的数据来源、代码执行过滤的影响以及指令/解决方案多样性的重要性进行了分析。我们发现，执行过滤对基准准确性产生了负面影响，因此我们优先考虑指令多样性而非解决方案正确性。最后，我们还分析了这些模型所利用的token效率和推理模式。我们将开源这些数据集和蒸馏模型供社区使用。

> Since the advent of reasoning-based large language models, many have found great success from distilling reasoning capabilities into student models. Such techniques have significantly bridged the gap between reasoning and standard LLMs on coding tasks. Despite this, much of the progress on distilling reasoning models remains locked behind proprietary datasets or lacks details on data curation, filtering and subsequent training. To address this, we construct a superior supervised fine-tuning (SFT) dataset that we use to achieve state-of-the-art coding capability results in models of various sizes. Our distilled models use only SFT to achieve 61.8% on LiveCodeBench and 24.6% on CodeContests, surpassing alternatives trained with reinforcement learning. We then perform analysis on the data sources used to construct our dataset, the impact of code execution filtering, and the importance of instruction/solution diversity. We observe that execution filtering negatively affected benchmark accuracy, leading us to prioritize instruction diversity over solution correctness. Finally, we also analyze the token efficiency and reasoning patterns utilized by these models. We will open-source these datasets and distilled models to the community.

[Arxiv](https://arxiv.org/abs/2504.01943)