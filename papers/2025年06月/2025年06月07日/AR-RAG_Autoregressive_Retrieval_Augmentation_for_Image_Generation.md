# AR-RAG：图像生成中的自回归检索增强方法

发布时间：2025年06月07日

`RAG` `计算机视觉` `生成式AI`

> AR-RAG: Autoregressive Retrieval Augmentation for Image Generation

# 摘要

> 我们提出了一种创新的图像生成范式——自回归检索增强（AR-RAG）。与传统方法在生成前仅进行一次静态检索不同，AR-RAG在每个生成步骤中，利用已生成的补丁作为查询，自适应地检索并整合最相关的视觉参考，从而有效避免了传统方法中过度复制和风格偏差等问题。为了实现这一范式，我们设计了两个并行框架：（1）分布增强解码（DAiD），这是一种即插即用的解码策略，无需额外训练，直接融合模型预测补丁与检索补丁的分布；（2）特征增强解码（FAiD），这是一种参数高效的微调方法，通过多尺度卷积操作优化检索补丁的特征，并将其融入生成过程。我们在Midjourney-30K、GenEval和DPG-Bench等基准数据集上进行了实验，结果表明AR-RAG显著超越了现有最先进的图像生成模型。

> We introduce Autoregressive Retrieval Augmentation (AR-RAG), a novel paradigm that enhances image generation by autoregressively incorporating knearest neighbor retrievals at the patch level. Unlike prior methods that perform a single, static retrieval before generation and condition the entire generation on fixed reference images, AR-RAG performs context-aware retrievals at each generation step, using prior-generated patches as queries to retrieve and incorporate the most relevant patch-level visual references, enabling the model to respond to evolving generation needs while avoiding limitations (e.g., over-copying, stylistic bias, etc.) prevalent in existing methods. To realize AR-RAG, we propose two parallel frameworks: (1) Distribution-Augmentation in Decoding (DAiD), a training-free plug-and-use decoding strategy that directly merges the distribution of model-predicted patches with the distribution of retrieved patches, and (2) Feature-Augmentation in Decoding (FAiD), a parameter-efficient fine-tuning method that progressively smooths the features of retrieved patches via multi-scale convolution operations and leverages them to augment the image generation process. We validate the effectiveness of AR-RAG on widely adopted benchmarks, including Midjourney-30K, GenEval and DPG-Bench, demonstrating significant performance gains over state-of-the-art image generation models.

[Arxiv](https://arxiv.org/abs/2506.06962)