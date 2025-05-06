# 基于生成式手语描述提示和多正对比学习的手语识别方法

发布时间：2025年05月04日

`LLM应用` `计算机视觉`

> Generative Sign-description Prompts with Multi-positive Contrastive Learning for Sign Language Recognition

# 摘要

> 手语识别 (SLR) 面临创建准确注释的根本性挑战，这源于手语中同时存在的手动和非手动信号的复杂性。我们自豪地呈现首个将生成式大型语言模型 (LLMs) 引入 SLR 任务的研究。提出了一种创新的 Generative Sign-description Prompts Multi-positive Contrastive learning (GSP-MC) 方法，该方法结合检索增强生成 (RAG) 技术和领域特定的 LLMs，通过多步骤提示工程和专家验证的手语语料库，生成精确的多部分描述。GSP-MC 方法采用双编码器架构，通过概率匹配实现层次化骨架特征与多种文本描述（全局、同义词和部件级别）的双向对齐。我们的方法巧妙结合全局和部件级别的损失，通过优化 KL 散度确保所有相关文本-骨架对的稳健对齐，同时捕捉到手势级别的语义和详细的部件动态。在中文 SLR500 数据集上达到 97.1% 的准确率，在土耳其 AUTSL 数据集上达到 97.07% 的准确率，证明了该方法相较于现有方法的最先进性能。该方法的跨语言有效性凸显了其在开发包容性通信技术方面的巨大潜力。

> Sign language recognition (SLR) faces fundamental challenges in creating accurate annotations due to the inherent complexity of simultaneous manual and non-manual signals. To the best of our knowledge, this is the first work to integrate generative large language models (LLMs) into SLR tasks. We propose a novel Generative Sign-description Prompts Multi-positive Contrastive learning (GSP-MC) method that leverages retrieval-augmented generation (RAG) with domain-specific LLMs, incorporating multi-step prompt engineering and expert-validated sign language corpora to produce precise multipart descriptions. The GSP-MC method also employs a dual-encoder architecture to bidirectionally align hierarchical skeleton features with multiple text descriptions (global, synonym, and part level) through probabilistic matching. Our approach combines global and part-level losses, optimizing KL divergence to ensure robust alignment across all relevant text-skeleton pairs while capturing both sign-level semantics and detailed part dynamics. Experiments demonstrate state-of-the-art performance against existing methods on the Chinese SLR500 (reaching 97.1%) and Turkish AUTSL datasets (97.07% accuracy). The method's cross-lingual effectiveness highlight its potential for developing inclusive communication technologies.

[Arxiv](https://arxiv.org/abs/2505.02304)