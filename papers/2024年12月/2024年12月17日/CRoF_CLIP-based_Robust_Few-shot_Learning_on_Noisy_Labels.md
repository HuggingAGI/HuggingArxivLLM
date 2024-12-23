# CRoF：基于 CLIP 的针对噪声标签的鲁棒少样本学习

发布时间：2024年12月17日

`LLM应用` `计算机视觉` `少样本学习`

> CRoF: CLIP-based Robust Few-shot Learning on Noisy Labels

# 摘要

> 嘈杂的标签因其在新领域中的不精确特征，对少样本学习（FSL）的鲁棒性构成威胁。CLIP 作为大规模的视觉语言模型，在基于图像 - 文本嵌入相似性的 FSL 中表现出色，但易受嘈杂标签导致的错误分类影响。如何在 FSL 任务中增强 CLIP 在嘈杂数据上的领域泛化能力，是一项关键挑战。本文提出了一个新颖的观点来减轻嘈杂标签的影响，即基于 CLIP 的鲁棒少样本学习（CRoF）。CRoF 是适用于基于 CLIP 模型的通用插件模块。为避免错误分类和混乱的标签嵌入，我们设计了面向少样本任务的提示生成器，为每个类别提供更具区分性的描述。所提出的提示实现了类间文本嵌入的更大间距。此外，我们并非完全依赖 CLIP 的零样本分类，而是在新领域的嘈杂少样本数据上，采用类似标签平滑的加权策略对 CLIP 进行微调。多个可能正确标签的权重考虑了 CLIP 的先验知识与原始标签信息的关系，以确保可靠性。我们的多标签损失函数进一步支持在此模式下的稳健训练。综合实验表明，作为插件的 CRoF 在不同噪声类型和噪声比率下，都优于经过微调的和原始的 CLIP 模型。

> Noisy labels threaten the robustness of few-shot learning (FSL) due to the inexact features in a new domain. CLIP, a large-scale vision-language model, performs well in FSL on image-text embedding similarities, but it is susceptible to misclassification caused by noisy labels. How to enhance domain generalization of CLIP on noisy data within FSL tasks is a critical challenge. In this paper, we provide a novel view to mitigate the influence of noisy labels, CLIP-based Robust Few-shot learning (CRoF). CRoF is a general plug-in module for CLIP-based models. To avoid misclassification and confused label embedding, we design the few-shot task-oriented prompt generator to give more discriminative descriptions of each category. The proposed prompt achieves larger distances of inter-class textual embedding. Furthermore, rather than fully trusting zero-shot classification by CLIP, we fine-tune CLIP on noisy few-shot data in a new domain with a weighting strategy like label-smooth. The weights for multiple potentially correct labels consider the relationship between CLIP's prior knowledge and original label information to ensure reliability. Our multiple label loss function further supports robust training under this paradigm. Comprehensive experiments show that CRoF, as a plug-in, outperforms fine-tuned and vanilla CLIP models on different noise types and noise ratios.

[Arxiv](https://arxiv.org/abs/2412.12793)