# 检测对比语言图像预训练中的后门样本

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了对比语言-图像预训练（CLIP）模型在安全方面的脆弱性，特别是后门攻击的问题。虽然CLIP本身是一个多模态模型，但论文的重点在于如何检测和防御针对CLIP模型的后门攻击，这属于对现有模型的应用和安全性改进的研究。因此，将其归类为LLM应用是合适的。` `网络安全` `机器学习`

> Detecting Backdoor Samples in Contrastive Language Image Pretraining

# 摘要

> 对比语言-图像预训练（CLIP）被发现易受投毒后门攻击，攻击者仅需污染0.01%的训练数据即可在CLIP模型上实现近乎完美的攻击成功率。这引发了人们对当前使用CLIP在未经审查的网络数据上预训练大规模模型的安全担忧。我们分析了CLIP模型学习的后门污染样本表示，发现它们在局部子空间中表现出独特特征，即局部邻域比干净样本稀疏得多。基于此，我们系统研究了CLIP后门攻击的检测，发现传统基于密度比的局部异常检测器可轻松高效地检测到这些攻击，而现有后门样本检测方法则无法做到。实验还揭示，原始CC3M数据集中已存在一个无意的后门，并被训练到OpenCLIP发布的一个流行开源模型中。基于我们的检测器，可在15分钟内使用4个Nvidia A100 GPU高效清理百万规模的网络数据集（如CC3M）。代码已公开在我们的\href{https://github.com/HanxunH/Detect-CLIP-Backdoor-Samples}{GitHub仓库}中。

> Contrastive language-image pretraining (CLIP) has been found to be vulnerable to poisoning backdoor attacks where the adversary can achieve an almost perfect attack success rate on CLIP models by poisoning only 0.01\% of the training dataset. This raises security concerns on the current practice of pretraining large-scale models on unscrutinized web data using CLIP. In this work, we analyze the representations of backdoor-poisoned samples learned by CLIP models and find that they exhibit unique characteristics in their local subspace, i.e., their local neighborhoods are far more sparse than that of clean samples. Based on this finding, we conduct a systematic study on detecting CLIP backdoor attacks and show that these attacks can be easily and efficiently detected by traditional density ratio-based local outlier detectors, whereas existing backdoor sample detection methods fail. Our experiments also reveal that an unintentional backdoor already exists in the original CC3M dataset and has been trained into a popular open-source model released by OpenCLIP. Based on our detector, one can clean up a million-scale web dataset (e.g., CC3M) efficiently within 15 minutes using 4 Nvidia A100 GPUs. The code is publicly available in our \href{https://github.com/HanxunH/Detect-CLIP-Backdoor-Samples}{GitHub repository}.

[Arxiv](https://arxiv.org/abs/2502.01385)