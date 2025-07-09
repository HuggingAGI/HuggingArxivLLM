# 基于自举的有根据思维链在多模态大语言模型中的数据高效适配研究

发布时间：2025年07月03日

`LLM应用

摘要讨论了多模态大型语言模型在专业视觉任务中的应用，提出了一种改进方法（GCoT）来提升其性能，属于LLM的应用层面研究。` `数据分析` `计算机视觉`

> Bootstrapping Grounded Chain-of-Thought in Multimodal LLMs for Data-Efficient Model Adaptation

# 摘要

> 多模态大型语言模型（MLLMs）在自然语言图像理解方面表现卓越，但若不借助大规模数据集进行再训练，这类模型难以胜任专业视觉任务，如图表理解。这一局限源于预训练数据与下游任务数据的不匹配：预训练数据主要关注场景和物体，而对图表等专业非物体图像的描述却十分有限。本文揭示了一个有趣的现象，即通过思维链（CoT）推理数据训练MLLM，能够有效提升其在专业视觉任务中的适应能力，尤其在数据稀缺场景下表现突出。然而，我们发现从预训练MLLM中提取的CoT数据存在严重问题：推理步骤中常包含事实性错误。为此，我们提出了一种基于自举方法的Grounded Chain-of-Thought（GCoT），旨在通过向CoT数据注入接地信息（即边界框），使推理过程更贴近输入图像的真实内容。我们在涵盖图表、表格、收据和报告等多种视觉格式的五个专业任务上验证了该方法。结果表明，在数据受限条件下，GCoT显著超越了传统的微调和蒸馏方法。


> Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in interpreting images using natural language. However, without using large-scale datasets for retraining, these models are difficult to adapt to specialized vision tasks, e.g., chart understanding. This problem is caused by a mismatch between pre-training and downstream datasets: pre-training datasets primarily concentrate on scenes and objects but contain limited information about specialized, non-object images, such as charts and tables. In this paper, we share an interesting finding that training an MLLM with Chain-of-Thought (CoT) reasoning data can facilitate model adaptation in specialized vision tasks, especially under data-limited regimes. However, we identify a critical issue within CoT data distilled from pre-trained MLLMs, i.e., the data often contains multiple factual errors in the reasoning steps. To address the problem, we propose Grounded Chain-of-Thought (GCoT), a simple bootstrapping-based approach that aims to inject grounding information (i.e., bounding boxes) into CoT data, essentially making the reasoning steps more faithful to input images. We evaluate our approach on five specialized vision tasks, which cover a variety of visual formats including charts, tables, receipts, and reports. The results demonstrate that under data-limited regimes our approach significantly improves upon fine-tuning and distillation.

[Arxiv](https://arxiv.org/abs/2507.02859)