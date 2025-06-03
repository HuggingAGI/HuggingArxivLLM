# CC-Tuning：优化多语言监督微调的跨语言连接机制

发布时间：2025年06月01日

`LLM理论` `语言学`

> CC-Tuning: A Cross-Lingual Connection Mechanism for Improving Joint Multilingual Supervised Fine-Tuning

# 摘要

> 当前大型语言模型（LLMs）由于其以英语为中心的训练语料库，常常表现出不均衡的多语言能力。为了解决这一问题，现有的在数据层面进行操作的微调方法（例如通过数据增强或蒸馏）通常会引入隐式的跨语言对齐，却忽视了更深刻、潜在层面的跨语言交互的可能性。在这项研究中，我们提出了CC-Tuning，一种全新的多语言微调范式，它在潜在层面显式地建立跨语言连接机制。在训练过程中，CC-Tuning融合了来自英语和非英语输入的前馈激活，使模型能够同时受益于这两种语言资源。这一过程借助了一个可训练的决策者来识别有益的激活。此外，在推理阶段，通过使用变换矩阵对潜在表示进行转换，CC-Tuning能够在单语设置下模拟跨语言连接。我们在涵盖22种语言的六个基准测试上的实验表明，CC-Tuning超越了标准的SFT方法，并为数据层面的增强方法提供了一个强大的潜在层面的替代方案。进一步的分析也凸显了CC-Tuning的实际应用价值，以及潜在层面的跨语言交互在提升LLMs多语言性能方面的潜力。

> Current large language models (LLMs) often exhibit imbalanced multilingual capabilities due to their English-centric training corpora. To address this, existing fine-tuning approaches operating at the data-level (e.g., through data augmentation or distillation) typically introduce implicit cross-lingual alignment, overlooking the potential for more profound, latent-level cross-lingual interactions. In this work, we propose CC-Tuning, a novel multilingual fine-tuning paradigm that explicitly establishes a cross-lingual connection mechanism at the latent level. During training, CC-Tuning fuses the feed forward activations from both English and non-English inputs, enabling the model to benefit from both linguistic resources. This process is facilitated with a trainable Decision Maker that identifies beneficial activations. Furthermore, during inference, a Transform Matrix is utilized to simulate the cross-lingual connection under monolingual setting through representation transformation. Our experiments on six benchmarks covering 22 languages show that CC-Tuning outperforms vanilla SFT and offers a strong latent-level alternative to data-level augmentation methods. Further analysis also highlights the practicality of CC-Tuning and the potential of latent-level cross-lingual interactions in advancing the multilingual performance of LLMs.

[Arxiv](https://arxiv.org/abs/2506.00875)