# 中文拼写检查的小模型与大模型结合方法

发布时间：2025年06月07日

`LLM应用` `中文处理`

> Mixture of Small and Large Models for Chinese Spelling Check

# 摘要

> 在大型语言模型时代，中文拼写检查任务出现了多种基于 LLM 的方法，但它们的表现仍不令人满意。相比之下，基于 BERT 的微调模型虽然依赖高质量的领域内数据，展现出卓越的性能，但存在编辑模式过拟合的问题。本文提出了一种新颖的动态混合方法，该方法在束搜索解码阶段有效结合了小模型和 LLMs 的概率分布，实现了小模型精准修正和 LLMs 流畅性的平衡提升。此方法还无需对 LLMs 进行微调，节省了大量时间和资源，同时便于领域适应。全面的实验表明，我们的混合方法显著提升了错误修正能力，在多个数据集上达到了前沿水准。我们的代码可在 https://github.com/zhqiao-nlp/MSLLM 获取。

> In the era of large language models (LLMs), the Chinese Spelling Check (CSC) task has seen various LLM methods developed, yet their performance remains unsatisfactory. In contrast, fine-tuned BERT-based models, relying on high-quality in-domain data, show excellent performance but suffer from edit pattern overfitting. This paper proposes a novel dynamic mixture approach that effectively combines the probability distributions of small models and LLMs during the beam search decoding phase, achieving a balanced enhancement of precise corrections from small models and the fluency of LLMs. This approach also eliminates the need for fine-tuning LLMs, saving significant time and resources, and facilitating domain adaptation. Comprehensive experiments demonstrate that our mixture approach significantly boosts error correction capabilities, achieving state-of-the-art results across multiple datasets. Our code is available at https://github.com/zhqiao-nlp/MSLLM.

[Arxiv](https://arxiv.org/abs/2506.06887)