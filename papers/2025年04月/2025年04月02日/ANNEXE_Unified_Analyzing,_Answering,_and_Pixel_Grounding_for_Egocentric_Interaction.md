# 附录：统一分析、回答与像素定位在自我中心交互中的应用

发布时间：2025年04月02日

`LLM应用` `计算机视觉` `人工智能`

> ANNEXE: Unified Analyzing, Answering, and Pixel Grounding for Egocentric Interaction

# 摘要

> 自我中心交互感知作为研究人与环境交互的重要分支，为下一代智能系统的开发奠定了基础。然而，现有方法在根据用户查询同时生成连贯文字和像素级响应方面存在局限性，难以满足多样化应用需求。为此，本文提出了一项名为自我中心交互推理与像素定位（Ego-IRG）的全新任务。该任务以自我中心图像和查询为输入，通过分析、回答和像素定位三个关键步骤，首次实现了流畅文字与精细像素级响应的生成。现有数据集无法满足这一任务需求，因此我们创建了Ego-IRGBench数据集，包含20,000余张自我中心图像、160万个查询及相关多模态交互响应。此外，我们设计了统一的ANNEXE模型，利用多模态大型语言模型生成文本与像素级输出，实现对自我中心交互的全面理解。实验结果表明，ANNEXE模型在Ego-IRGBench上表现优异，显著优于现有方法。

> Egocentric interaction perception is one of the essential branches in investigating human-environment interaction, which lays the basis for developing next-generation intelligent systems. However, existing egocentric interaction understanding methods cannot yield coherent textual and pixel-level responses simultaneously according to user queries, which lacks flexibility for varying downstream application requirements. To comprehend egocentric interactions exhaustively, this paper presents a novel task named Egocentric Interaction Reasoning and pixel Grounding (Ego-IRG). Taking an egocentric image with the query as input, Ego-IRG is the first task that aims to resolve the interactions through three crucial steps: analyzing, answering, and pixel grounding, which results in fluent textual and fine-grained pixel-level responses. Another challenge is that existing datasets cannot meet the conditions for the Ego-IRG task. To address this limitation, this paper creates the Ego-IRGBench dataset based on extensive manual efforts, which includes over 20k egocentric images with 1.6 million queries and corresponding multimodal responses about interactions. Moreover, we design a unified ANNEXE model to generate text- and pixel-level outputs utilizing multimodal large language models, which enables a comprehensive interpretation of egocentric interactions. The experiments on the Ego-IRGBench exhibit the effectiveness of our ANNEXE model compared with other works.

[Arxiv](https://arxiv.org/abs/2504.01472)