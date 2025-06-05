# 无标签数据助力多模态大语言模型提升细粒度图像零样本分类效果。

发布时间：2025年06月01日

`LLM应用` `计算机视觉`

> Unlabeled Data Improves Fine-Grained Image Zero-shot Classification with Multimodal LLMs

# 摘要

> 尽管多模态大型语言模型（MLLMs）在通用零样本图像分类任务中表现优异，但细粒度图像分类仍面临挑战。这类任务需要关注细微的视觉细节，以区分视觉上极为相似的子类别，而MLLMs在缺乏明确指导时往往容易忽略这些细节。为此，我们提出了AutoSEP，一个迭代的自监督提示学习框架，旨在以完全无监督的方式提升MLLMs的细粒度分类能力。

我们的核心思路是利用未标记数据学习一个描述提示，引导MLLMs识别图像中的关键判别特征，从而提升分类精度。基于实例级分类评分函数，我们开发了AutoSEP框架，通过未标记数据迭代优化描述提示。AutoSEP仅需对MLLMs进行黑盒访问，无需任何训练或微调。

我们在多个细粒度分类数据集上验证了AutoSEP的性能。实验结果表明，AutoSEP在所有无监督基线中表现最优，充分证明了我们的自监督优化框架的有效性。值得注意的是，AutoSEP的平均分类准确率比标准零样本分类高出13%，比最佳基线高出5%。项目代码已开源，访问链接：https://github.com/yq-hong/AutoSEP

> Despite Multimodal Large Language Models (MLLMs) showing promising results on general zero-shot image classification tasks, fine-grained image classification remains challenging. It demands precise attention to subtle visual details to distinguish between visually similar subcategories--details that MLLMs may easily overlook without explicit guidance. To address this, we introduce AutoSEP, an iterative self-supervised prompt learning framework designed to enhance MLLM fine-grained classification capabilities in a fully unsupervised manner. Our core idea is to leverage unlabeled data to learn a description prompt that guides MLLMs in identifying crucial discriminative features within an image, and boosts classification accuracy. We developed an automatic self-enhancing prompt learning framework called AutoSEP to iteratively improve the description prompt using unlabeled data, based on instance-level classification scoring function. AutoSEP only requires black-box access to MLLMs, eliminating the need for any training or fine-tuning. We evaluate our approach on multiple fine-grained classification datasets. It consistently outperforms other unsupervised baselines, demonstrating the effectiveness of our self-supervised optimization framework. Notably, AutoSEP on average improves 13 percent over standard zero-shot classification and 5 percent over the best-performing baselines. Code is available at: https://github.com/yq-hong/AutoSEP

[Arxiv](https://arxiv.org/abs/2506.03195)