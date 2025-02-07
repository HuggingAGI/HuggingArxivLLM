# 工具遗忘：工具增强型LLM的新挑战

发布时间：2025年02月03日

`LLM应用

理由：这篇论文讨论了工具增强的大型语言模型（LLMs）及其“工具遗忘”能力，提出了ToolDelete方法来解决工具遗忘问题。这涉及到LLMs在实际应用中的使用和优化，属于LLM应用的范畴。` `人工智能` `数据安全`

> Tool Unlearning for Tool-Augmented LLMs

# 摘要

> # 工具增强的LLMs通常通过查询-响应对数据集训练，将工具或API的使用能力直接嵌入模型参数中。然而，由于安全漏洞、隐私法规或工具废弃等原因，这些模型需要具备“工具遗忘”能力。目前，这一领域尚未被深入研究。我们提出了ToolDelete，首个针对工具增强LLMs的工具遗忘方法。它通过三个关键特性应对知识移除、高成本优化和评估指标等挑战，并引入新的成员推理攻击（MIA）模型进行评估。实验表明，ToolDelete能有效遗忘随机选择的工具，同时保留未删除工具的知识，并维持一般任务的性能。

> Tool-augmented large language models (LLMs) are often trained on datasets of query-response pairs, which embed the ability to use tools or APIs directly into the parametric knowledge of LLMs. Tool-augmented LLMs need the ability to forget learned tools due to security vulnerabilities, privacy regulations, or tool deprecations. However, ``tool unlearning'' has not been investigated in unlearning literature. We introduce this novel task, which requires addressing distinct challenges compared to traditional unlearning: knowledge removal rather than forgetting individual samples, the high cost of optimizing LLMs, and the need for principled evaluation metrics. To bridge these gaps, we propose ToolDelete, the first approach for unlearning tools from tool-augmented LLMs. It implements three key properties to address the above challenges for effective tool unlearning and introduces a new membership inference attack (MIA) model for effective evaluation. Extensive experiments on multiple tool learning datasets and tool-augmented LLMs show that ToolDelete effectively unlearns randomly selected tools, while preserving the LLM's knowledge on non-deleted tools and maintaining performance on general tasks.

[Arxiv](https://arxiv.org/abs/2502.01083)