# 分治法在长上下文LLM中何时奏效？噪声分解框架为您解答。

发布时间：2025年06月19日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在处理长文本时的理论框架，分析了其失败模式，并提出了多智能体分块处理的有效性。论文的重点在于理论分析和框架构建，而非具体的应用实例，因此归类为LLM理论。` `大型语言模型` `信息处理`

> When Does Divide and Conquer Work for Long Context LLM? A Noise Decomposition Framework

# 摘要

> 我们深入探讨了将大型语言模型（LLMs）应用于长文本的挑战，并提出了一种理论框架，将长上下文任务的失败模式分为三类：跨块依赖（任务噪声）、随着上下文大小增长的混淆（模型噪声），以及部分结果整合不完美的问题（聚合器噪声）。通过分析，我们明确了在何种情况下使用多智能体分块处理最为有效，即把长序列分割成更小的块，并整合每个块的处理结果。我们的实验结果在检索、问答和总结等任务上证实了理论分析以及有利于多智能体分块的条件。通过研究模型噪声随着输入长度的超线性增长，我们进一步解释了为何对于大规模输入，配置了分块处理的较弱模型能够超越单次应用的更先进模型，如GPT4o。总体而言，我们提出了一种基于原理的理解框架，研究结果强调了通过精心管理分块和聚合器策略来处理LLMs长上下文的直接路径。

> We investigate the challenge of applying Large Language Models (LLMs) to long texts. We propose a theoretical framework that distinguishes the failure modes of long context tasks into three categories: cross-chunk dependence (task noise), confusion that grows with context size (model noise), and the imperfect integration of partial results (aggregator noise). Under this view, we analyze when it is effective to use multi-agent chunking, i.e., dividing a length sequence into smaller chunks and aggregating the processed results of each chunk. Our experiments on tasks such as retrieval, question answering, and summarization confirm both the theoretical analysis and the conditions that favor multi-agent chunking. By exploring superlinear model noise growth with input length, we also explain why, for large inputs, a weaker model configured with chunk-based processing can surpass a more advanced model like GPT4o applied in a single shot. Overall, we present a principled understanding framework and our results highlight a direct pathway to handling long contexts in LLMs with carefully managed chunking and aggregator strategies.

[Arxiv](https://arxiv.org/abs/2506.16411)