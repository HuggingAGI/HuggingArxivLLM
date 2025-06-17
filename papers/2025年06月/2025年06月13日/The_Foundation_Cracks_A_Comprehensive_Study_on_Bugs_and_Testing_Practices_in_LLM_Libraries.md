# 基础动摇：全面解析大型语言模型库中的漏洞与测试实践

发布时间：2025年06月13日

`LLM应用

论文摘要讨论了大型语言模型（LLM）库在不同场景下的应用，并分析了这些库中的漏洞特征和测试实践。研究重点在于提升LLM库的质量保证，属于LLM在实际应用中的工程问题，因此归类为LLM应用。` `软件工程`

> The Foundation Cracks: A Comprehensive Study on Bugs and Testing Practices in LLM Libraries

# 摘要

> 大型语言模型（LLM）库作为AI革命的基石，支撑着LLM在部署、推理优化、微调和生产服务等多场景下的应用。然而，这些库频繁出现的质量问题和漏洞严重威胁了基于它们构建的AI系统的可靠性。为填补这一知识空白，我们首次对现代LLM库中的漏洞特征和测试实践进行了全面的实证研究。我们分析了从HuggingFace Transformers和vLLM这两个广泛应用的LLM库中提取的313个修复提交。通过严格的分析，我们建立了全面的分类法，将漏洞症状分为5种类型，将根本原因分为14个不同的类别。我们的主要发现表明，API误用已成为最常见的根本原因（32.17%-48.19%），这标志着从传统深度学习框架中以算法为中心的缺陷转向以接口为导向的问题。此外，我们审查了7,748个测试函数，识别出当前测试方法中使用的7种不同的测试预言类别，其中最常见的策略是使用预定义的预期输出（如特定的张量和文本字符串）。我们的评估表明，由于测试用例不足（41.73%）、缺乏测试驱动程序（32.37%）以及弱测试预言（25.90%），大多数漏洞未被检测到。基于这些发现，我们提出了一些建议，以提升LLM库的质量保证。

> Large Language Model (LLM) libraries have emerged as the foundational infrastructure powering today's AI revolution, serving as the backbone for LLM deployment, inference optimization, fine-tuning, and production serving across diverse applications. Despite their critical role in the LLM ecosystem, these libraries face frequent quality issues and bugs that threaten the reliability of AI systems built upon them. To address this knowledge gap, we present the first comprehensive empirical investigation into bug characteristics and testing practices in modern LLM libraries. We examine 313 bug-fixing commits extracted across two widely-adopted LLM libraries: HuggingFace Transformers and vLLM.Through rigorous manual analysis, we establish comprehensive taxonomies categorizing bug symptoms into 5 types and root causes into 14 distinct categories.Our primary discovery shows that API misuse has emerged as the predominant root cause (32.17%-48.19%), representing a notable transition from algorithm-focused defects in conventional deep learning frameworks toward interface-oriented problems. Additionally, we examine 7,748 test functions to identify 7 distinct test oracle categories employed in current testing approaches, with predefined expected outputs (such as specific tensors and text strings) being the most common strategy. Our assessment of existing testing effectiveness demonstrates that the majority of bugs escape detection due to inadequate test cases (41.73%), lack of test drivers (32.37%), and weak test oracles (25.90%). Drawing from these findings, we offer some recommendations for enhancing LLM library quality assurance.

[Arxiv](https://arxiv.org/abs/2506.12320)