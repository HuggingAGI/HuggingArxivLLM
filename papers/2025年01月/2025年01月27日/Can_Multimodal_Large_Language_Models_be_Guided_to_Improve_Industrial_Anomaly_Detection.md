# 多模态大语言模型能否助力工业异常检测的提升？

发布时间：2025年01月27日

`LLM应用

理由：这篇论文讨论了如何利用多模态大型语言模型（MLLMs）来改进工业异常检测（IAD）任务。论文提出了一个名为Echo的多专家框架，旨在提升MLLM在IAD中的表现。这表明论文主要关注的是如何将大型语言模型应用于具体的工业场景中，以解决实际问题，因此应归类为“LLM应用”。` `异常检测`

> Can Multimodal Large Language Models be Guided to Improve Industrial Anomaly Detection?

# 摘要

> 在工业环境中，精准的异常检测是保障产品质量和操作安全的关键。传统工业异常检测（IAD）模型在灵活性和适应性上常显不足，尤其是在动态生产环境中，新缺陷和操作变化层出不穷。多模态大型语言模型（MLLMs）的最新进展，通过融合视觉与文本信息处理能力，有望突破这些局限。MLLMs凭借在多样化大数据集上的训练，在通用视觉理解上表现出色，但缺乏行业特定知识，如缺陷容忍度，这限制了其在IAD任务中的效能。为此，我们推出Echo，一个创新的多专家框架，旨在提升MLLM在IAD中的表现。Echo整合了四大专家模块：参考提取器通过检索相似正常图像建立上下文基线，知识指南注入领域专长，推理专家支持复杂查询的逐步推理，决策者则综合各模块信息，输出精准且情境感知的响应。在MMAD基准测试中，Echo在适应性、精确度及鲁棒性上均取得显著提升，向满足实际工业异常检测需求迈进了一大步。

> In industrial settings, the accurate detection of anomalies is essential for maintaining product quality and ensuring operational safety. Traditional industrial anomaly detection (IAD) models often struggle with flexibility and adaptability, especially in dynamic production environments where new defect types and operational changes frequently arise. Recent advancements in Multimodal Large Language Models (MLLMs) hold promise for overcoming these limitations by combining visual and textual information processing capabilities. MLLMs excel in general visual understanding due to their training on large, diverse datasets, but they lack domain-specific knowledge, such as industry-specific defect tolerance levels, which limits their effectiveness in IAD tasks. To address these challenges, we propose Echo, a novel multi-expert framework designed to enhance MLLM performance for IAD. Echo integrates four expert modules: Reference Extractor which provides a contextual baseline by retrieving similar normal images, Knowledge Guide which supplies domain-specific insights, Reasoning Expert which enables structured, stepwise reasoning for complex queries, and Decision Maker which synthesizes information from all modules to deliver precise, context-aware responses. Evaluated on the MMAD benchmark, Echo demonstrates significant improvements in adaptability, precision, and robustness, moving closer to meeting the demands of real-world industrial anomaly detection.

[Arxiv](https://arxiv.org/abs/2501.15795)