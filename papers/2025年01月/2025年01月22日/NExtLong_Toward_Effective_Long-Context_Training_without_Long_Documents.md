# NExtLong: 无需长文档，高效训练长上下文

发布时间：2025年01月22日

`LLM应用

**理由**：该论文主要讨论了如何通过合成数据来扩展大型语言模型（LLMs）的上下文窗口，并提出了一个新的框架NExtLong来提升模型对长距离依赖的建模能力。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `机器学习`

> NExtLong: Toward Effective Long-Context Training without Long Documents

# 摘要

> # 摘要
扩展上下文窗口的大型语言模型（LLMs）虽已取得显著进展，但长文档的稀缺性仍是挑战。现有方法多通过合成长上下文数据来应对，却缺乏强化长距离依赖建模的机制。为此，我们提出NExtLong，一种通过负文档扩展合成长上下文数据的新框架。NExtLong将文档分解为多个元块，并通过从预训练语料库中检索的硬负干扰项交错扩展上下文，迫使模型从干扰内容中识别长距离依赖的上下文，从而提升其建模能力。大量实验表明，NExtLong在HELMET和RULER基准上显著优于现有长上下文合成方法及在非合成长文档上训练的领先模型。这些成果表明，NExtLong能有效减少对非合成长文档的依赖，是开发先进长上下文LLMs的有力工具。

> Large language models (LLMs) with extended context windows have made significant strides yet remain a challenge due to the scarcity of long documents. Existing methods tend to synthesize long-context data but lack a clear mechanism to reinforce the long-range dependency modeling. To address this limitation, we propose NExtLong, a novel framework for synthesizing long-context data through Negative document Extension. NExtLong decomposes a document into multiple meta-chunks and extends the context by interleaving hard negative distractors retrieved from pretraining corpora. This approach compels the model to discriminate long-range dependent context from distracting content, enhancing its ability to model long-range dependencies. Extensive experiments demonstrate that NExtLong achieves significant performance improvements on the HELMET and RULER benchmarks compared to existing long-context synthesis approaches and leading models, which are trained on non-synthetic long documents. These findings highlight NExtLong's ability to reduce reliance on non-synthetic long documents, making it an effective framework for developing advanced long-context LLMs.

[Arxiv](https://arxiv.org/abs/2501.12766)