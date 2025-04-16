# 探索大型语言模型的跨语言上下文检索能力：它的表现如何，背后原因何在？

发布时间：2025年04月15日

`LLM应用` `机器学习`

> Understanding LLMs' Cross-Lingual Context Retrieval: How Good It Is And Where It Comes From

# 摘要

> 跨语言上下文检索能力是大型语言模型（LLMs）跨语言对齐的核心要素，具体指模型根据一种语言的请求提取另一种语言的上下文信息。尽管这一能力在实际应用中具有重要意义，但目前尚未对最先进的模型进行充分研究。本文通过跨语言机器阅读理解（xMRC）这一典型场景，评估了12种语言环境下40多个LLMs的跨语言上下文检索能力，以探究该能力的来源。我们的研究结果表明，一些经过微调的小规模开源LLMs展现了与闭源LLMs（如GPT-4o）相当的跨语言上下文检索能力，且其估计的最优性能在微调后得到了显著提升。通过可解释性分析，我们发现跨语言上下文检索过程主要分为两个阶段：问题编码和答案检索，这两个阶段分别在预训练和微调过程中形成。阶段稳定性与xMRC性能密切相关，且xMRC的瓶颈出现在第二阶段的模型深层，此处能够明显观察到微调的效果。我们的研究还表明，更大规模的预训练并不能提升xMRC性能。相反，大型LLMs需要进一步的多语言微调，才能充分释放其跨语言上下文检索的潜力。我们的代码和资源可在https://github.com/NJUNLP/Cross-Lingual-Context-Retrieval获取。


> The ability of cross-lingual context retrieval is a fundamental aspect of cross-lingual alignment of large language models (LLMs), where the model extracts context information in one language based on requests in another language. Despite its importance in real-life applications, this ability has not been adequately investigated for state-of-the-art models. In this paper, we evaluate the cross-lingual context retrieval ability of over 40 LLMs across 12 languages to understand the source of this ability, using cross-lingual machine reading comprehension (xMRC) as a representative scenario. Our results show that several small, post-trained open LLMs show strong cross-lingual context retrieval ability, comparable to closed-source LLMs such as GPT-4o, and their estimated oracle performances greatly improve after post-training. Our interpretability analysis shows that the cross-lingual context retrieval process can be divided into two main phases: question encoding and answer retrieval, which are formed in pre-training and post-training, respectively. The phasing stability correlates with xMRC performance, and the xMRC bottleneck lies at the last model layers in the second phase, where the effect of post-training can be evidently observed. Our results also indicate that larger-scale pretraining cannot improve the xMRC performance. Instead, larger LLMs need further multilingual post-training to fully unlock their cross-lingual context retrieval potential. Our code and is available at https://github.com/NJUNLP/Cross-Lingual-Context-Retrieval

[Arxiv](https://arxiv.org/abs/2504.10906)