# # UniDetox: 通过数据集蒸馏实现大型语言模型的通用 detoxification

通过数据集蒸馏技术，实现大型语言模型的通用 detoxification。

发布时间：2025年04月29日

`LLM应用` `社会责任`

> UniDetox: Universal Detoxification of Large Language Models via Dataset Distillation

# 摘要

> 我们提出了一种通用方法 UniDetox，旨在解决各种大型语言模型（LLMs）中的毒性问题。与以往仅针对特定模型或模型家族且需要繁琐参数调整的 detoxification 方法不同，UniDetox 提供了一种通用解决方案，无需针对每个模型单独调整。通过创新的对比解码数据蒸馏技术，我们成功将 detoxification 表示转化为合成文本数据，只需通过微调这些蒸馏文本，即可实现对任意 LLM 的 detoxification。实验结果表明，从 GPT-2 蒸馏出的 detoxification 文本能够有效 detoxify OPT、Falcon 和 LLaMA-2 等大型模型。更值得一提的是，UniDetox 实现了“一劳永逸”的超参数配置，一个设置即可通用于所有模型。此外，我们发现 detoxification 文本中政治偏见内容显著减少，这为提升 LLM detoxification 效果提供了重要启示。

> We present UniDetox, a universally applicable method designed to mitigate toxicity across various large language models (LLMs). Previous detoxification methods are typically model-specific, addressing only individual models or model families, and require careful hyperparameter tuning due to the trade-off between detoxification efficacy and language modeling performance. In contrast, UniDetox provides a detoxification technique that can be universally applied to a wide range of LLMs without the need for separate model-specific tuning. Specifically, we propose a novel and efficient dataset distillation technique for detoxification using contrastive decoding. This approach distills detoxifying representations in the form of synthetic text data, enabling universal detoxification of any LLM through fine-tuning with the distilled text. Our experiments demonstrate that the detoxifying text distilled from GPT-2 can effectively detoxify larger models, including OPT, Falcon, and LLaMA-2. Furthermore, UniDetox eliminates the need for separate hyperparameter tuning for each model, as a single hyperparameter configuration can be seamlessly applied across different models. Additionally, analysis of the detoxifying text reveals a reduction in politically biased content, providing insights into the attributes necessary for effective detoxification of LLMs.

[Arxiv](https://arxiv.org/abs/2504.20500)