# # **EvaLearn：通过逐步问题求解评估LLMs的学习能力与效率**

发布时间：2025年06月03日

`LLM应用` `人工智能`

> EvaLearn: Quantifying the Learning Capability and Efficiency of LLMs via Sequential Problem Solving

# 摘要

> 我们推出 EvaLearn，一个开创性的基准测试，专注于评估大型语言模型（LLMs）在挑战性任务中的学习能力和效率，这一关键但尚未充分探索的领域。EvaLearn 包含648个跨六种任务类型的问题，分为182个序列，每个序列专注于一个任务类型。与大多数现有并行评估基准不同，EvaLearn 要求模型按顺序解决问题，使其能够利用之前经验。EvaLearn 提供五个全面的自动化指标，用于评估模型并量化其学习能力与效率。我们对九个前沿模型进行了广泛测试，发现显著的性能差异：Claude-3.7-sonnet 等模型初始性能中等但学习能力强，而部分模型难以有效利用经验，甚至可能出现负迁移。此外，我们在两种学习设置下研究了模型表现，发现实例级评分标准和教师-模型反馈能进一步促进学习。值得注意的是，目前静态能力更强的LLMs在所有任务中并未展现出明显的学习优势，这表明EvaLearn揭示了模型性能的新维度。我们希望EvaLearn能为评估LLM潜力提供新视角，帮助理解模型与人类能力的差距，推动更深入和动态的评估方法发展。本文所有数据集、自动评估框架及结果均可在GitHub仓库中获取。

> We introduce EvaLearn, a pioneering benchmark designed to evaluate large language models (LLMs) on their learning capability and efficiency in challenging tasks, a critical, yet underexplored aspect of model potential. EvaLearn contains 648 challenging problems across six task types, grouped into 182 sequences, each sequence dedicated to one task type. Diverging from most existing benchmarks that evaluate models in parallel, EvaLearn requires models to solve problems sequentially, allowing them to leverage the experience gained from previous solutions. EvaLearn provides five comprehensive automated metrics to evaluate models and quantify their learning capability and efficiency. We extensively benchmark nine frontier models and observe varied performance profiles: some models, such as Claude-3.7-sonnet, start with moderate initial performance but exhibit strong learning ability, while some models struggle to benefit from experience and may even show negative transfer. Moreover, we investigate model performance under two learning settings and find that instance-level rubrics and teacher-model feedback further facilitate model learning. Importantly, we observe that current LLMs with stronger static abilities do not show a clear advantage in learning capability across all tasks, highlighting that EvaLearn evaluates a new dimension of model performance. We hope EvaLearn provides a novel evaluation perspective for assessing LLM potential and understanding the gap between models and human capabilities, promoting the development of deeper and more dynamic evaluation approaches. All datasets, the automatic evaluation framework, and the results studied in this paper are available at the GitHub repository.

[Arxiv](https://arxiv.org/abs/2506.02672)