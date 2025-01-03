# CLEAR: 文本与视觉模态中的角色遗忘

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了机器遗忘（MU）在大型多模态语言模型（MLLMs）中的应用，特别是多模态遗忘（MMU）的挑战和方法。论文提出了一个新的基准CLEAR，用于评估MMU方法，并测试了多种MU方法在多模态环境下的表现。这些内容涉及到如何在实际应用中提升模型的隐私和安全性，属于LLM应用的范畴。` `隐私保护` `多模态学习`

> CLEAR: Character Unlearning in Textual and Visual Modalities

# 摘要

> # 摘要
机器遗忘（MU）在提升深度学习模型的隐私和安全性方面扮演着关键角色，尤其是在大型多模态语言模型（MLLMs）中，通过剔除特定敏感或有害信息。尽管MU在文本和视觉领域已取得显著进展，但多模态遗忘（MMU）仍是一片待开发的蓝海，部分原因在于缺乏合适的开源基准。为此，我们推出了CLEAR，一个专为评估MMU方法而设计的新基准。CLEAR囊括了200个虚构人物及3,700张与问答对紧密相连的图片，为跨模态的深度评估铺平了道路。我们测试了10种MU方法，将其调整以适应MMU，并揭示了多模态遗忘特有的新难题。此外，我们证明了在LoRA权重上应用简单的$\ell_1$正则化能有效缓解灾难性遗忘，确保模型在保留数据上的表现不受影响。数据集现已开放，访问地址：https://huggingface.co/datasets/therem/CLEAR。

> Machine Unlearning (MU) is critical for enhancing privacy and security in deep learning models, particularly in large multimodal language models (MLLMs), by removing specific private or hazardous information. While MU has made significant progress in textual and visual modalities, multimodal unlearning (MMU) remains significantly underexplored, partially due to the absence of a suitable open-source benchmark. To address this, we introduce CLEAR, a new benchmark designed to evaluate MMU methods. CLEAR contains 200 fictitious individuals and 3,700 images linked with corresponding question-answer pairs, enabling a thorough evaluation across modalities. We assess 10 MU methods, adapting them for MMU, and highlight new challenges specific to multimodal forgetting. We also demonstrate that simple $\ell_1$ regularization on LoRA weights significantly mitigates catastrophic forgetting, preserving model performance on retained data. The dataset is available at https://huggingface.co/datasets/therem/CLEAR

[Arxiv](https://arxiv.org/abs/2410.18057)