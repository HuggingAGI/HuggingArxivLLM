# 提升基于转换器的口语理解：自条件CTC与知识转移的应用

发布时间：2025年01月03日

`LLM应用

**解释**：这篇论文主要讨论了通过改进端到端（E2E）口语理解（SLU）模型来提升性能，特别是通过引入联合自条件CTC自动语音识别（ASR）目标，并将声学嵌入与BERT模型对齐。这些技术涉及到使用预训练的语言模型（如BERT）来增强SLU任务的性能，因此可以归类为LLM应用。` `语音识别`

> Improving Transducer-Based Spoken Language Understanding with Self-Conditioned CTC and Knowledge Transfer

# 摘要

> 本文提出了一种改进端到端（E2E）口语理解（SLU）的方法，通过在RNN transducer模型（RNN-T）中引入联合自条件CTC自动语音识别（ASR）目标。我们的模型类似于一个E2E可微分级联模型，依次执行ASR和SLU，并通过CTC自条件确保SLU任务以ASR任务为条件。这种新颖的ASR和SLU联合建模显著提升了SLU性能。我们进一步通过将模型的声学嵌入与语义更丰富的BERT模型对齐来提升性能。提出的知识转移策略利用对齐嵌入上的实体预测层，并将其输出用于基于RNN-T的SLU解码。这些技术在多个强基线上表现出显著改进，且能在参数大幅减少的情况下与Whisper等大型模型媲美。

> In this paper, we propose to improve end-to-end (E2E) spoken language understand (SLU) in an RNN transducer model (RNN-T) by incorporating a joint self-conditioned CTC automatic speech recognition (ASR) objective. Our proposed model is akin to an E2E differentiable cascaded model which performs ASR and SLU sequentially and we ensure that the SLU task is conditioned on the ASR task by having CTC self conditioning. This novel joint modeling of ASR and SLU improves SLU performance significantly over just using SLU optimization. We further improve the performance by aligning the acoustic embeddings of this model with the semantically richer BERT model. Our proposed knowledge transfer strategy makes use of a bag-of-entity prediction layer on the aligned embeddings and the output of this is used to condition the RNN-T based SLU decoding. These techniques show significant improvement over several strong baselines and can perform at par with large models like Whisper with significantly fewer parameters.

[Arxiv](https://arxiv.org/abs/2501.01936)