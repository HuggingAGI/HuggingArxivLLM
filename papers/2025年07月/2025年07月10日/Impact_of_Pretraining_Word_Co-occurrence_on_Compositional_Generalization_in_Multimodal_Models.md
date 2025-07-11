# 预训练词共现对多模态模型组合泛化能力的影响

发布时间：2025年07月10日

`LLM应用` `多模态模型` `模型泛化`

> Impact of Pretraining Word Co-occurrence on Compositional Generalization in Multimodal Models

# 摘要

> CLIP 和大型多模态模型（LMMs）在处理训练数据中高度表示的概念时表现出更高的准确性。然而，关于训练数据中概念组合对组合泛化能力的影响，目前仍 largely unclear。例如，当一个常见对象与另一个对象以不常见的方式配对时，准确性会如何变化？在这篇论文中，我们研究了预训练数据集中的词共现统计（作为视觉概念共现的代理）如何影响 CLIP/LMM 的性能。为了将词共现频率与单词频率的影响区分开来，我们使用点互信息（PMI）来衡量共现情况，它通过两个词独立共现的概率对两个词共同出现的联合概率进行了标准化。通过使用包含各种概念对的合成生成图像，我们展示了 CLIP 预训练数据中的 PMI 与在 LAION-400M 数据集上训练的 CLIP 模型的零样本准确率之间存在很强的相关性（r=0.97，PMI 值最高的 5% 和最低的 5% 的图像之间的准确率差距为 14%），这表明即使是常见概念的准确性，也会受到图像中概念组合的影响。利用这一发现，我们通过对自然图像进行编辑以包含不同 PMI 的概念对，再现了这一效果，结果得到了 r=0.75 的相关性。最后，我们证明了这种行为在 CLIP 中可以迁移到基于 CLIP 构建的 LMMs 中（TextVQA 的 r=0.70，VQAv2 的 r=0.62）。我们的研究发现强调了需要开发改进多模态模型组合泛化能力的算法和架构，而无需对训练数据进行组合扩展。我们的代码可在 https://github.com/helenqu/multimodal-pretraining-pmi 获取。

> CLIP and large multimodal models (LMMs) have better accuracy on examples involving concepts that are highly represented in the training data. However, the role of concept combinations in the training data on compositional generalization is largely unclear -- for instance, how does accuracy vary when a common object appears in an uncommon pairing with another object? In this paper, we investigate how word co-occurrence statistics in the pretraining dataset (a proxy for co-occurrence of visual concepts) impacts CLIP/LMM performance. To disentangle the effects of word co-occurrence frequencies from single-word frequencies, we measure co-occurrence with pointwise mutual information (PMI), which normalizes the joint probability of two words co-occurring by the probability of co-occurring independently. Using synthetically generated images with a variety of concept pairs, we show a strong correlation between PMI in the CLIP pretraining data and zero-shot accuracy in CLIP models trained on LAION-400M (r=0.97 and 14% accuracy gap between images in the top and bottom 5% of PMI values), demonstrating that even accuracy on common concepts is affected by the combination of concepts in the image. Leveraging this finding, we reproduce this effect in natural images by editing them to contain pairs with varying PMI, resulting in a correlation of r=0.75. Finally, we demonstrate that this behavior in CLIP transfers to LMMs built on top of CLIP (r=0.70 for TextVQA, r=0.62 for VQAv2). Our findings highlight the need for algorithms and architectures that improve compositional generalization in multimodal models without scaling the training data combinatorially. Our code is available at https://github.com/helenqu/multimodal-pretraining-pmi.

[Arxiv](https://arxiv.org/abs/2507.08000)