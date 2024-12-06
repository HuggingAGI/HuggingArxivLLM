# 对 LVLMs 进行判别式微调

发布时间：2024年12月05日

`LLM应用` `视觉语言模型` `判别式学习`

> Discriminative Fine-tuning of LVLMs

# 摘要

> 像 CLIP 这样经过对比训练的视觉语言模型（VLMs）已成为判别式视觉语言表示学习的主流方法。不过，这些模型在语言理解方面能力有限，常常呈现出“词袋”式的表现。与此同时，将视觉编码器与大型语言模型（LLMs）相结合的大型视觉语言模型（LVLMs）虽能进行细致的视觉语言推理，但其自回归特性使其不太适用于判别任务。
    在本研究中，我们提出要做到“两全其美”：一种用于 LVLMs 判别式微调的新训练方法，能带来强大的判别和组合能力。实质上，我们的方法把生成式的 LVLM 转变为判别式，释放其强大的图像 - 文本判别能力，并增强语言理解。
    我们的贡献有：（1）精心设计了训练/优化框架，利用不同长度和粒度的图像 - 文本对，通过对比和下一个标记预测损失来训练模型。同时还进行了消融研究，以证明我们框架组件的必要性。（2）采用了软提示和 LoRA 适配器相结合的参数高效适配方法。（3）在类似大小的最先进的类似 CLIP 模型上取得了显著改进，包括在标准的图像 - 文本检索基准方面，以及在组合性上有明显提升。

> Contrastively-trained Vision-Language Models (VLMs) like CLIP have become the de facto approach for discriminative vision-language representation learning. However, these models have limited language understanding, often exhibiting a "bag of words" behavior. At the same time, Large Vision-Language Models (LVLMs), which combine vision encoders with LLMs, have been shown capable of detailed vision-language reasoning, yet their autoregressive nature renders them less suitable for discriminative tasks.
  In this work, we propose to combine "the best of both worlds": a new training approach for discriminative fine-tuning of LVLMs that results in strong discriminative and compositional capabilities. Essentially, our approach converts a generative LVLM into a discriminative one, unlocking its capability for powerful image-text discrimination combined with enhanced language understanding.
  Our contributions include: (1) A carefully designed training/optimization framework that utilizes image-text pairs of variable length and granularity for training the model with both contrastive and next-token prediction losses. This is accompanied by ablation studies that justify the necessity of our framework's components. (2) A parameter-efficient adaptation method using a combination of soft prompting and LoRA adapters. (3) Significant improvements over state-of-the-art CLIP-like models of similar size, including standard image-text retrieval benchmarks and notable gains in compositionality.

[Arxiv](https://arxiv.org/abs/2412.04378)