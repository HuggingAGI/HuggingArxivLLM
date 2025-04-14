# 语言指导的影响：可复现性研究

发布时间：2025年04月10日

`其他` `机器学习` `自监督学习`

> Impact of Language Guidance: A Reproducibility Study

# 摘要

> 现代深度学习架构需要海量数据才能达到顶尖水准，然而标注这些数据耗时费力、成本高昂且容易出错。近期自监督学习的突破让我们无需显式标注即可训练大型模型。对比学习作为自监督学习的热门范式，近期研究如SimCLR和CLIP依赖图像增强或直接最小化图像与文本的跨模态损失。班尼等人（2023年）提出用语言指导采样视图对，声称语言能更好实现概念相似性，消除视觉变异影响。我们复现实验验证其主张，却发现其数据集RedCaps描述质量欠佳。我们用现成的图像描述模型BLIP-2替换描述提升性能，并设计新指标基于可解释性方法评估自监督模型的语义能力。

> Modern deep-learning architectures need large amounts of data to produce state-of-the-art results. Annotating such huge datasets is time-consuming, expensive, and prone to human error. Recent advances in self-supervised learning allow us to train huge models without explicit annotation. Contrastive learning is a popular paradigm in self-supervised learning. Recent works like SimCLR and CLIP rely on image augmentations or directly minimizing cross-modal loss between image and text. Banani et al. (2023) propose to use language guidance to sample view pairs. They claim that language enables better conceptual similarity, eliminating the effects of visual variability. We reproduce their experiments to verify their claims and find that their dataset, RedCaps, contains low-quality captions. We use an off-the-shelf image captioning model, BLIP-2, to replace the captions and improve performance, and we also devise a new metric to evaluate the semantic capabilities of self-supervised models based on interpretability methods.

[Arxiv](https://arxiv.org/abs/2504.08140)