# 点击率驱动的广告图像生成：基于多模态大语言模型的研究

发布时间：2025年02月05日

`LLM应用` `电子商务` `广告行业`

> CTR-Driven Advertising Image Generation with Multimodal Large Language Models

# 摘要

> 在网页数据中，广告图片对于吸引用户注意和提升广告效果至关重要。然而，现有方法在为产品生成背景时，大多侧重于美学质量，这可能无法达到令人满意的线上表现。为了解决这一局限，我们探索利用多模态大型语言模型（MLLMs）通过优化点击率（CTR）为主要目标来生成广告图片。

首先，我们构建了针对性的预训练任务，并借助大规模电子商务多模态数据集，赋予MLLMs初步生成广告图片的能力。为了进一步提升生成图片的点击率，我们提出了一种新型奖励模型，通过强化学习（RL）对预训练的MLLMs进行微调，该模型能够综合运用多模态特征并准确反映用户点击偏好。同时，我们开发了一种以产品为中心的偏好优化策略，确保微调后生成的背景内容与产品特性相契合，从而提升广告图片的整体相关性和有效性。

大量实验表明，我们的方法在在线和离线指标上均达到了当前最优水平。我们的代码和预训练模型已公开发布于：https://github.com/Chenguoz/CAIG。


> In web data, advertising images are crucial for capturing user attention and improving advertising effectiveness. Most existing methods generate background for products primarily focus on the aesthetic quality, which may fail to achieve satisfactory online performance. To address this limitation, we explore the use of Multimodal Large Language Models (MLLMs) for generating advertising images by optimizing for Click-Through Rate (CTR) as the primary objective. Firstly, we build targeted pre-training tasks, and leverage a large-scale e-commerce multimodal dataset to equip MLLMs with initial capabilities for advertising image generation tasks. To further improve the CTR of generated images, we propose a novel reward model to fine-tune pre-trained MLLMs through Reinforcement Learning (RL), which can jointly utilize multimodal features and accurately reflect user click preferences. Meanwhile, a product-centric preference optimization strategy is developed to ensure that the generated background content aligns with the product characteristics after fine-tuning, enhancing the overall relevance and effectiveness of the advertising images. Extensive experiments have demonstrated that our method achieves state-of-the-art performance in both online and offline metrics. Our code and pre-trained models are publicly available at: https://github.com/Chenguoz/CAIG.

[Arxiv](https://arxiv.org/abs/2502.06823)