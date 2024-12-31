# SecBench：一个用于网络安全领域中LLM的全面多维基准测试数据集

发布时间：2024年12月30日

`LLM应用` `网络安全`

> SecBench: A Comprehensive Multi-Dimensional Benchmarking Dataset for LLMs in Cybersecurity

# 摘要

> 评估大型语言模型（LLMs）对于洞悉其在包括自然语言处理和代码生成等各类应用中的能力与局限至关重要。现有的诸如 MMLU、C-Eval 以及 HumanEval 等基准测试评估了一般的 LLM 性能，然而对于特定的专业领域，比如网络安全，却缺乏关注。以往创建网络安全数据集的尝试存在诸多限制，包括数据量不足以及依赖多项选择题（MCQs）。为了弥补这些不足，我们提出了 SecBench，这是一个用于评估网络安全领域 LLM 的多维基准测试数据集。SecBench 涵盖了多种格式（多项选择题和简答题（SAQs））的问题，处于不同的能力水平（知识留存和逻辑推理），涉及多种语言（中文和英文），并跨越多个子领域。该数据集通过从开源收集高质量数据以及组织网络安全问题设计竞赛构建而成，包含 44,823 个多项选择题和 3,087 个简答题。特别地，我们运用强大且性价比高的 LLM 来（1）标注数据，以及（2）构建用于自动评估简答题的评分代理。对 13 个 SOTA LLM 进行的基准测试结果表明了 SecBench 的可用性，它堪称网络安全领域针对 LLM 的最大且最全面的基准数据集。更多关于 SecBench 的信息可在我们的网站获取，并且可通过工件链接访问该数据集。

> Evaluating Large Language Models (LLMs) is crucial for understanding their capabilities and limitations across various applications, including natural language processing and code generation. Existing benchmarks like MMLU, C-Eval, and HumanEval assess general LLM performance but lack focus on specific expert domains such as cybersecurity. Previous attempts to create cybersecurity datasets have faced limitations, including insufficient data volume and a reliance on multiple-choice questions (MCQs). To address these gaps, we propose SecBench, a multi-dimensional benchmarking dataset designed to evaluate LLMs in the cybersecurity domain. SecBench includes questions in various formats (MCQs and short-answer questions (SAQs)), at different capability levels (Knowledge Retention and Logical Reasoning), in multiple languages (Chinese and English), and across various sub-domains. The dataset was constructed by collecting high-quality data from open sources and organizing a Cybersecurity Question Design Contest, resulting in 44,823 MCQs and 3,087 SAQs. Particularly, we used the powerful while cost-effective LLMs to (1). label the data and (2). constructing a grading agent for automatic evaluation of SAQs.Benchmarking results on 13 SOTA LLMs demonstrate the usability of SecBench, which is arguably the largest and most comprehensive benchmark dataset for LLMs in cybersecurity. More information about SecBench can be found at our website, and the dataset can be accessed via the artifact link.

[Arxiv](https://arxiv.org/abs/2412.20787)