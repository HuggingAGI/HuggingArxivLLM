# # EPIC：高效提示交互用于文本图像分类

发布时间：2025年07月10日

`其他` `计算机视觉`

> EPIC: Efficient Prompt Interaction for Text-Image Classification

# 摘要

> 近年来，大规模预训练多模态模型（LMMs）整合视觉与语言模态，在文本-图像分类等任务中取得了显著成功。然而，模型规模的扩大导致微调成本激增。为应对这一挑战，我们提出了一种高效提示交互策略——EPIC。该方法通过在中间层引入时间提示，并结合基于相似度的模态交互，实现了高效的跨模态信息交换。与传统微调方法相比，EPIC显著降低了计算资源消耗和参数量（仅为基础模型的1%）。实验结果表明，EPIC在UPMC-Food101和SNLI-VE数据集上表现优异，而在MM-IMDB数据集上也达到了与现有方法相当的性能。

> In recent years, large-scale pre-trained multimodal models (LMMs) generally emerge to integrate the vision and language modalities, achieving considerable success in multimodal tasks, such as text-image classification. The growing size of LMMs, however, results in a significant computational cost for fine-tuning these models for downstream tasks. Hence, prompt-based interaction strategy is studied to align modalities more efficiently. In this context, we propose a novel efficient prompt-based multimodal interaction strategy, namely Efficient Prompt Interaction for text-image Classification (EPIC). Specifically, we utilize temporal prompts on intermediate layers, and integrate different modalities with similarity-based prompt interaction, to leverage sufficient information exchange between modalities. Utilizing this approach, our method achieves reduced computational resource consumption and fewer trainable parameters (about 1\% of the foundation model) compared to other fine-tuning strategies. Furthermore, it demonstrates superior performance on the UPMC-Food101 and SNLI-VE datasets, while achieving comparable performance on the MM-IMDB dataset.

[Arxiv](https://arxiv.org/abs/2507.07415)