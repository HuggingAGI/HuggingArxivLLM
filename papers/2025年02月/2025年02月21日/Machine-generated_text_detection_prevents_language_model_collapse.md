# 检测机器生成的文本能防止语言模型崩溃。

发布时间：2025年02月21日

`LLM理论` `内容安全` `生成内容`

> Machine-generated text detection prevents language model collapse

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，它们生成的内容在互联网上泛滥成灾，威胁着未来机器生成内容将稀释人类撰写文本的风险。由于网络数据是LLM预训练的主要资源，未来模型将在一定程度的合成数据上进行训练。这将导致模型坍塌，这是一种退化过程，会使模型自我强化错误并导致性能下降。本研究探讨了解码策略对模型坍塌的影响，分析了递归训练过程中生成数据的特性、其与人类参考文本的相似性以及对模型性能的影响。通过采用导致模型性能下降最显著的解码策略，我们探讨了如何在训练数据来源（人类或合成）未知的情况下避免模型坍塌。我们设计了一种基于从机器生成文本检测器中获取重要性权重来重新采样数据分布的新方法。在两个LLM变体（GPT-2和SmolLM2）的开放文本生成任务上验证了我们的方法，结果表明我们成功防止了模型坍塌，并且当训练数据集中包含足够的人类撰写数据时，我们的方法能够提升模型性能。

> As Large Language Models (LLMs) become increasingly prevalent, their generated outputs are proliferating across the web, risking a future where machine-generated content dilutes human-authored text. Since web data is the primary resource for LLM pretraining, future models will be trained on an unknown portion of synthetic data. This will lead to model collapse, a degenerative process which causes models to reinforce their own errors and experience a drop in model performance. In this study, we investigate the impact of decoding strategy on model collapse, where we analyse the characteristics of the generated data during recursive training, its similarity to human references and the resulting model performance. Using the decoding strategies that lead to the most significant model degradation, we tackle the question: how to avoid model collapse when the origin (human or synthetic) of the training data is unknown. We design a novel methodology based on resampling the data distribution using importance weights from our machine-generated text detector. Our method is validated on two LLM variants (GPT-2 and SmolLM2) on the open-ended text generation task, demonstrating that we can successfully prevent model collapse and when there is enough human-authored data in the training dataset, our method improves model performance.

[Arxiv](https://arxiv.org/abs/2502.15654)