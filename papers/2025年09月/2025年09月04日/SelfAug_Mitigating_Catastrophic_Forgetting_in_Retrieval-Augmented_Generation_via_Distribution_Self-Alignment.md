# # SelfAug：基于分布自对齐缓解检索增强生成中的灾难性遗忘

发布时间：2025年09月04日

`RAG` `基础理论`

> SelfAug: Mitigating Catastrophic Forgetting in Retrieval-Augmented Generation via Distribution Self-Alignment

# 摘要

> 大型语言模型（LLMs）凭借其理解和执行各类任务的卓越能力，近期进展彻底革新了自然语言处理领域。尽管监督微调（尤其是在检索增强生成（RAG）场景中）能有效提升特定任务性能，却常引发灾难性遗忘——模型会丢失先前习得的知识和通用能力。现有解决方案要么依赖通用指令数据，要么在保留模型原始分布上存在局限。为此，我们提出自分布对齐方法SelfAug：通过对齐输入序列的logits以保留模型语义分布，进而减轻灾难性遗忘并提升下游任务性能。大量实验证实，SelfAug在下游学习与通用能力保留之间取得了更优平衡。全面实证分析揭示：RAG场景中，分布偏移与灾难性遗忘的严重程度直接相关，而通用指令微调因缺乏RAG能力，会在微调时引发显著的分布偏移。我们的研究成果不仅加深了对RAG场景下灾难性遗忘的理解，还提供了一种适用于多种微调场景的实用方案。相关代码已开源，地址为https://github.com/USTC-StarTeam/SelfAug。

> Recent advancements in large language models (LLMs) have revolutionized natural language processing through their remarkable capabilities in understanding and executing diverse tasks. While supervised fine-tuning, particularly in Retrieval-Augmented Generation (RAG) scenarios, effectively enhances task-specific performance, it often leads to catastrophic forgetting, where models lose their previously acquired knowledge and general capabilities. Existing solutions either require access to general instruction data or face limitations in preserving the model's original distribution. To overcome these limitations, we propose SelfAug, a self-distribution alignment method that aligns input sequence logits to preserve the model's semantic distribution, thereby mitigating catastrophic forgetting and improving downstream performance. Extensive experiments demonstrate that SelfAug achieves a superior balance between downstream learning and general capability retention. Our comprehensive empirical analysis reveals a direct correlation between distribution shifts and the severity of catastrophic forgetting in RAG scenarios, highlighting how the absence of RAG capabilities in general instruction tuning leads to significant distribution shifts during fine-tuning. Our findings not only advance the understanding of catastrophic forgetting in RAG contexts but also provide a practical solution applicable across diverse fine-tuning scenarios. Our code is publicly available at https://github.com/USTC-StarTeam/SelfAug.

[Arxiv](https://arxiv.org/abs/2509.03934)