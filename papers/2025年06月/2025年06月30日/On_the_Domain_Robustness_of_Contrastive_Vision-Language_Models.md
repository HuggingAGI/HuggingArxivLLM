# # 对比视觉语言模型的跨领域稳健性探索

发布时间：2025年06月30日

`LLM应用` `视觉-语言模型` `计算机视觉`

> On the Domain Robustness of Contrastive Vision-Language Models

# 摘要

> 在视觉-语言的实际应用中，从业者越来越依赖大规模预训练的基础模型，而非定制化方案，尽管这些模型的训练数据和流程仍不透明。虽然这些模型在通用任务上表现优异，但在特定领域变化（如独特成像条件或环境变化）下，其效果可能显著下降。为此，我们提出Deepbench——一个评估视觉-语言模型领域特定鲁棒性的框架。Deepbench借助大规模语言模型，无需标注数据，即可生成针对特定部署领域的现实且语境感知的图像损坏。我们在六个实际领域中评估了多种对比视觉-语言架构及其变体，发现鲁棒性存在显著差异，凸显了进行领域感知评估的必要性。Deepbench已作为开源软件发布，以支持进一步研究领域感知的鲁棒性评估。

> In real-world vision-language applications, practitioners increasingly rely on large, pretrained foundation models rather than custom-built solutions, despite limited transparency regarding their training data and processes. While these models achieve impressive performance on general benchmarks, their effectiveness can decline notably under specialized domain shifts, such as unique imaging conditions or environmental variations. In this work, we introduce Deepbench, a framework designed to assess domain-specific robustness of vision-language models (VLMs). Deepbench leverages a large language model (LLM) to generate realistic, context-aware image corruptions tailored to specific deployment domains without requiring labeled data. We evaluate a range of contrastive vision-language architectures and architectural variants across six real-world domains and observe substantial variability in robustness, highlighting the need for targeted, domain-aware evaluation. Deepbench is released as open-source software to support further research into domain-aware robustness assessment.

[Arxiv](https://arxiv.org/abs/2506.23663)