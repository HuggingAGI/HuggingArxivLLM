# 专用大型语言模型作为密集检索器的比较研究

发布时间：2025年07月05日

`LLM应用` `文本检索` `代码检索`

> A Comparative Study of Specialized LLMs as Dense Retrievers

# 摘要

> 尽管大型语言模型（LLMs）越来越多地被用作密集检索器，但它们在领域特定专门化方面对检索效果的影响仍未被充分研究。本研究系统性地探讨了LLMs在任务特定适应方面如何影响其检索能力，这是迈向开发能够处理文本、代码、图像和多模态内容的统一检索器的重要一步。我们使用八种Qwen2.5 7B LLMs进行了广泛实验，包括基础模型、指令微调模型、数学/代码专用模型、长推理模型和视觉-语言模型，分别在零样本检索设置和监督设置下进行测试。在零样本检索设置中，我们从BEIR基准中进行文本检索，从CoIR基准中进行代码检索。此外，为了评估监督性能，所有LLMs都在MS MARCO数据集上进行了微调。研究发现，数学专门化和长推理能力在三个设置中均导致性能下降，这表明数学推理与语义匹配之间存在冲突。视觉-语言模型和代码专用LLMs在零样本设置下表现优于其他LLMs，甚至在代码检索任务上超越了BM25，并且在监督设置下与基础LLMs保持了相当的性能。这些发现为利用跨域和跨模态融合的统一检索任务提供了有前景的研究方向。

> While large language models (LLMs) are increasingly deployed as dense retrievers, the impact of their domain-specific specialization on retrieval effectiveness remains underexplored. This investigation systematically examines how task-specific adaptations in LLMs influence their retrieval capabilities, an essential step toward developing unified retrievers capable of handling text, code, images, and multimodal content. We conduct extensive experiments with eight Qwen2.5 7B LLMs, including base, instruction-tuned, code/math-specialized, long reasoning, and vision-language models across zero-shot retrieval settings and the supervised setting. For the zero-shot retrieval settings, we consider text retrieval from the BEIR benchmark and code retrieval from the CoIR benchmark. Further, to evaluate supervised performance, all LLMs are fine-tuned on the MS MARCO dataset. We find that mathematical specialization and the long reasoning capability cause consistent degradation in three settings, indicating conflicts between mathematical reasoning and semantic matching. The vision-language model and code-specialized LLMs demonstrate superior zero-shot performance compared to other LLMs, even surpassing BM25 on the code retrieval task, and maintain comparable performance to base LLMs in supervised settings. These findings suggest promising directions for the unified retrieval task leveraging cross-domain and cross-modal fusion.

[Arxiv](https://arxiv.org/abs/2507.03958)