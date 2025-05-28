# 明天它依然真实吗？多语言常青问题分类助力可信问答

发布时间：2025年05月27日

`LLM应用` `问答系统`

> Will It Still Be True Tomorrow? Multilingual Evergreen Question Classification to Improve Trustworthy QA

# 摘要

> 大型语言模型（LLMs）在问答任务中容易产生幻觉，而一个关键但尚未被充分探索的因素是问题的时间性——即问题是否为“常青”（答案随时间保持稳定）或“可变”（答案会变化）。为此，我们推出了首个带有长期稳定标签的多语言问答数据集EverGreenQA，支持评估和训练。通过这一数据集，我们对12个现代LLMs进行了全面基准测试，评估它们是否能通过显式的语言化判断或隐式的不确定性信号来明确编码问题的时间性。此外，我们还开发了一个轻量级的多语言分类器EG-E5，在该任务中达到了当前最优性能。最后，我们展示了常青分类在三个实际应用场景中的实用价值：提升自我知识估计、过滤问答数据集以及解释GPT-4o的检索行为。

> Large Language Models (LLMs) often hallucinate in question answering (QA) tasks. A key yet underexplored factor contributing to this is the temporality of questions -- whether they are evergreen (answers remain stable over time) or mutable (answers change). In this work, we introduce EverGreenQA, the first multilingual QA dataset with evergreen labels, supporting both evaluation and training. Using EverGreenQA, we benchmark 12 modern LLMs to assess whether they encode question temporality explicitly (via verbalized judgments) or implicitly (via uncertainty signals). We also train EG-E5, a lightweight multilingual classifier that achieves SoTA performance on this task. Finally, we demonstrate the practical utility of evergreen classification across three applications: improving self-knowledge estimation, filtering QA datasets, and explaining GPT-4o retrieval behavior.

[Arxiv](https://arxiv.org/abs/2505.21115)