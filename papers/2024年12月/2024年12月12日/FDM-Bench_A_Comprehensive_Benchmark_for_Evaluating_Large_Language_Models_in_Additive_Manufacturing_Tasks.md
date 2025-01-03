# FDM-Bench: 增材制造任务中大型语言模型的综合评估基准

发布时间：2024年12月12日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决熔融沉积成型（FDM）中的设计和生产问题，并提出了一个基准数据集FDM-Bench来评估LLMs在该领域的表现。论文的核心是LLMs在特定应用场景（FDM）中的使用和评估，因此应归类为LLM应用。` `增材制造` `大型语言模型`

> FDM-Bench: A Comprehensive Benchmark for Evaluating Large Language Models in Additive Manufacturing Tasks

# 摘要

> # 摘要
熔融沉积成型（FDM）作为一种灵活且经济的增材制造技术，广泛应用于医疗、航空航天等领域。近年来，FDM设备的普及降低了使用门槛，吸引了更多用户。然而，FDM的设计、规划和生产过程涉及复杂的跨学科知识，参数管理和打印缺陷的解决仍是难题。这些技术壁垒阻碍了非技术背景用户甚至跨领域工程师参与AM设计与制造。大型语言模型（LLMs）凭借其强大的文本和代码处理能力，为解决FDM中的挑战提供了新思路。然而，现有研究多局限于特定用例，缺乏跨模型和任务的全面评估。为此，我们推出了FDM-Bench基准数据集，旨在评估LLMs在FDM任务中的表现。FDM-Bench涵盖了不同经验水平的用户查询和多样化的G代码异常样本，支持全面评估。我们对两个闭源模型（GPT-4o和Claude 3.5 Sonnet）和两个开源模型（Llama-3.1-70B和Llama-3.1-405B）进行了测试，并由FDM专家团队详细评估了模型对用户查询的响应。结果显示，闭源模型在G代码异常检测上表现更优，而Llama-3.1-405B在用户查询响应上略胜一筹。这些发现表明，FDM-Bench有望成为推动LLM在FDM领域研究的重要工具。

> Fused Deposition Modeling (FDM) is a widely used additive manufacturing (AM) technique valued for its flexibility and cost-efficiency, with applications in a variety of industries including healthcare and aerospace. Recent developments have made affordable FDM machines accessible and encouraged adoption among diverse users. However, the design, planning, and production process in FDM require specialized interdisciplinary knowledge. Managing the complex parameters and resolving print defects in FDM remain challenging. These technical complexities form the most critical barrier preventing individuals without technical backgrounds and even professional engineers without training in other domains from participating in AM design and manufacturing. Large Language Models (LLMs), with their advanced capabilities in text and code processing, offer the potential for addressing these challenges in FDM. However, existing research on LLM applications in this field is limited, typically focusing on specific use cases without providing comprehensive evaluations across multiple models and tasks. To this end, we introduce FDM-Bench, a benchmark dataset designed to evaluate LLMs on FDM-specific tasks. FDM-Bench enables a thorough assessment by including user queries across various experience levels and G-code samples that represent a range of anomalies. We evaluate two closed-source models (GPT-4o and Claude 3.5 Sonnet) and two open-source models (Llama-3.1-70B and Llama-3.1-405B) on FDM-Bench. A panel of FDM experts assess the models' responses to user queries in detail. Results indicate that closed-source models generally outperform open-source models in G-code anomaly detection, whereas Llama-3.1-405B demonstrates a slight advantage over other models in responding to user queries. These findings underscore FDM-Bench's potential as a foundational tool for advancing research on LLM capabilities in FDM.

[Arxiv](https://arxiv.org/abs/2412.09819)