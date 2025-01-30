# 技术报告：基于标签信息的逻辑重新分配，提升基础模型在低样本分类中的领域泛化能力。

发布时间：2025年01月29日

`LLM应用

**理由**：这篇论文主要讨论了在基于基础模型的视觉分类任务中，如何通过引入置信度错位惩罚（CMP）机制来改进置信度校准。虽然论文中提到了CLIP模型（一种多模态模型，结合了视觉和语言信息），但核心内容集中在如何通过改进损失函数来优化模型的性能。这属于对现有模型的应用和改进，因此归类为LLM应用。` `计算机视觉` `机器学习`

> Technical report on label-informed logit redistribution for better domain generalization in low-shot classification with foundation models

# 摘要

> 置信度校准时下基于基础模型的视觉分类任务中的一大挑战。由于种种原因，CLIP头部的logit分数无论图像-语言对是否匹配都居高不下。在少样本情况下，这在数据空间中难以解决。我们提出了一种惩罚机制，将其纳入损失目标中，通过在微调过程中每当出现错误分类时，将一定量的对数似然转移到真实类别，惩罚错误分类，转移的量与两个似然的相对幅度相称。我们称之为	extit{置信度错位惩罚（CMP）}。在12个视觉数据集和5个领域泛化数据集上的大量实验表明，CMP在预期校准误差（ECE）上平均提高了6.01\%，最小提高了4.01\%，最大提高了9.72\%，优于现有技术。本文的匿名示例源代码可在以下网址找到：url{https://anonymous.4open.science/r/icml25-C5CB/readme.txt}

> Confidence calibration is an emerging challenge in real-world decision systems based on foundations models when used for downstream vision classification tasks. Due to various reasons exposed, logit scores on the CLIP head remain large irrespective of whether the image-language pairs reconcile. It is difficult to address in data space, given the few-shot regime. We propose a penalty incorporated into loss objective that penalizes incorrect classifications whenever one is made during finetuning, by moving an amount of log-likelihood to the true class commensurate to the relative amplitudes of the two likelihoods. We refer to it as \textit{confidence misalignment penalty (CMP)}. Extensive experiments on $12$ vision datasets and $5$ domain generalization datasets supports the calibration performance of our method against stat-of-the-art. CMP outperforms the benchmarked prompt learning methods, demonstrating average improvement in Expected Calibration Error (ECE) by average $6.01$\%, $4.01$ \% at minimum and $9.72$\% at maximum. Anonymized sample source code for this paper can be found at: url{https://anonymous.4open.science/r/icml25-C5CB/readme.txt}

[Arxiv](https://arxiv.org/abs/2501.17595)