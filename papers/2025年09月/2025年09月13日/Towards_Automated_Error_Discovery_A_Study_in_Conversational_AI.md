# 面向自动化错误发现：对话AI中的一项研究

发布时间：2025年09月13日

`LLM应用` `基础理论`

> Towards Automated Error Discovery: A Study in Conversational AI

# 摘要

> 尽管基于大型语言模型（LLM）的对话代理流畅度和连贯性出色，但它们仍会产生不良行为（错误），这些错误在部署时难以避免触达用户。近期研究利用大型语言模型（LLMs）检测错误，并指导响应生成模型改进。然而，现有LLM难以识别指令中未明确说明的错误，例如因响应生成模型更新或用户行为变化而产生的错误。在本研究中，我们引入了Automated Error Discovery（一种用于对话式AI错误检测与定义的框架），并提出SEEED（基于编码器的软聚类扩展错误检测）作为其基于编码器的实现方案。我们通过放大负样本的距离权重增强了软最近邻损失，并引入基于标签的样本排序，以选择高对比度示例来优化表示学习。在多个带错误标注的对话数据集上，SEEED性能优于包括GPT-4o和Phi-4在内的调整后基线模型，将未知错误检测准确率提升了多达8个百分点，并在未知意图检测任务中展现出强大的泛化能力。

> Although LLM-based conversational agents demonstrate strong fluency and coherence, they still produce undesirable behaviors (errors) that are challenging to prevent from reaching users during deployment. Recent research leverages large language models (LLMs) to detect errors and guide response-generation models toward improvement. However, current LLMs struggle to identify errors not explicitly specified in their instructions, such as those arising from updates to the response-generation model or shifts in user behavior. In this work, we introduce Automated Error Discovery, a framework for detecting and defining errors in conversational AI, and propose SEEED (Soft Clustering Extended Encoder-Based Error Detection), as an encoder-based approach to its implementation. We enhance the Soft Nearest Neighbor Loss by amplifying distance weighting for negative samples and introduce Label-Based Sample Ranking to select highly contrastive examples for better representation learning. SEEED outperforms adapted baselines -- including GPT-4o and Phi-4 -- across multiple error-annotated dialogue datasets, improving the accuracy for detecting unknown errors by up to 8 points and demonstrating strong generalization to unknown intent detection.

[Arxiv](https://arxiv.org/abs/2509.10833)