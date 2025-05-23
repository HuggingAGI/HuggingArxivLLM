# R1-Compress：实现长链式思考压缩，通过分块压缩与搜索

发布时间：2025年05月22日

`LLM应用

理由：论文讨论了如何优化大型语言模型（LLMs）在长链式推理（Long-CoT）中的计算效率，提出了R1-Compress方法，属于对LLM的应用优化。` `人工智能`

> R1-Compress: Long Chain-of-Thought Compression via Chunk Compression and Search

# 摘要

> 链式思维（CoT）推理通过支持逐步解决问题增强了大型语言模型（LLMs），但将其扩展到长链式推理（Long-CoT）时，由于令牌长度增加，带来了显著的计算开销。现有的压缩方法——实例级和令牌级——要么牺牲了如反思等重要的局部推理信号，要么导致输出不连贯。为了解决这些问题，我们提出了R1-Compress，这是一种两阶段的分块级压缩框架，能够同时保留局部信息和连贯性。我们的方法将长链式推理分割成可管理的块，应用基于LLM的块内压缩，并采用块间搜索机制来选择简短且连贯的序列。在Qwen2.5-Instruct模型上进行的MATH500、AIME24和GPQA-Diamond实验表明，R1-Compress在显著减少令牌使用的同时，保持了与长链式推理基线相当的推理准确性。在MATH500数据集上，R1-Compress达到了92.4%的准确率，与长链式推理基线相比仅下降了0.6%，同时将令牌使用量减少了约20%。源代码将在https://github.com/w-yibo/R1-Compress上提供。


> Chain-of-Thought (CoT) reasoning enhances large language models (LLMs) by enabling step-by-step problem-solving, yet its extension to Long-CoT introduces substantial computational overhead due to increased token length. Existing compression approaches -- instance-level and token-level -- either sacrifice essential local reasoning signals like reflection or yield incoherent outputs. To address these limitations, we propose R1-Compress, a two-stage chunk-level compression framework that preserves both local information and coherence. Our method segments Long-CoT into manageable chunks, applies LLM-driven inner-chunk compression, and employs an inter-chunk search mechanism to select the short and coherent sequence. Experiments on Qwen2.5-Instruct models across MATH500, AIME24, and GPQA-Diamond demonstrate that R1-Compress significantly reduces token usage while maintaining comparable reasoning accuracy. On MATH500, R1-Compress achieves an accuracy of 92.4%, with only a 0.6% drop compared to the Long-CoT baseline, while reducing token usage by about 20%. Source code will be available at https://github.com/w-yibo/R1-Compress

[Arxiv](https://arxiv.org/abs/2505.16838)