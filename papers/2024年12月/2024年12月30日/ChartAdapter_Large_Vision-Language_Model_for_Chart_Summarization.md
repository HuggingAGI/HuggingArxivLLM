# ChartAdapter：用于图表总结的大型视觉语言模型

发布时间：2024年12月30日

`LLM应用` `数据分析` `图表总结`

> ChartAdapter: Large Vision-Language Model for Chart Summarization

# 摘要

> 图表总结，专注于从图表中提取关键信息并用自然语言加以阐释，对于通过有效且便捷的数据分析来生成和传递见解至关重要。传统的图表理解与总结方法往往依赖多阶段流程，这可能导致视觉和文本信息之间的语义对齐欠佳。相较而言，近期开发的基于 LLM 的方法更依赖于基础图像或语言的能力，却忽视了图表数据的特点及其相关挑战。为应对这些局限，我们提出了 ChartAdapter，这是一种新颖的轻量级变压器模块，旨在填补图表与文本摘要之间的鸿沟。ChartAdapter 运用可学习的查询向量从图表数据中提取隐性语义，并融入了跨模态对齐投影仪以强化视觉到语言的生成式学习。通过将 ChartAdapter 与 LLM 相结合，我们实现了端到端的训练以及高效的图表总结。为进一步优化训练，我们引入了一个三阶段分层训练流程，并开发了一个专为图表总结精心打造的大规模数据集，涵盖 190,618 个样本。在标准的图表转文本测试集上的实验结果显示，我们的方法在生成高质量图表总结方面显著优于包括前沿模型在内的现有方法。消融研究进一步证实了 ChartAdapter 中关键组件的有效性。此项工作凸显了定制的基于 LLM 的方法在推进图表理解方面的潜力，为该领域的未来研究筑牢了根基。

> Chart summarization, which focuses on extracting key information from charts and interpreting it in natural language, is crucial for generating and delivering insights through effective and accessible data analysis. Traditional methods for chart understanding and summarization often rely on multi-stage pipelines, which may produce suboptimal semantic alignment between visual and textual information. In comparison, recently developed LLM-based methods are more dependent on the capability of foundation images or languages, while ignoring the characteristics of chart data and its relevant challenges. To address these limitations, we propose ChartAdapter, a novel lightweight transformer module designed to bridge the gap between charts and textual summaries. ChartAdapter employs learnable query vectors to extract implicit semantics from chart data and incorporates a cross-modal alignment projector to enhance vision-to-language generative learning. By integrating ChartAdapter with an LLM, we enable end-to-end training and efficient chart summarization. To further enhance the training, we introduce a three-stage hierarchical training procedure and develop a large-scale dataset specifically curated for chart summarization, comprising 190,618 samples. Experimental results on the standard Chart-to-Text testing set demonstrate that our approach significantly outperforms existing methods, including state-of-the-art models, in generating high-quality chart summaries. Ablation studies further validate the effectiveness of key components in ChartAdapter. This work highlights the potential of tailored LLM-based approaches to advance chart understanding and sets a strong foundation for future research in this area.

[Arxiv](https://arxiv.org/abs/2412.20715)