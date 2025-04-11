# 相关性并非全部：利用多准则重排序技术在推理阶段扩展RAG系统规模

发布时间：2025年03月13日

`RAG` `人工智能`

> Relevance Isn't All You Need: Scaling RAG Systems With Inference-Time Compute Via Multi-Criteria Reranking

# 摘要

> 现代 LLM 系统普遍采用检索增强生成（RAG），旨在聚合生成响应所需的上下文。这些系统通常专注于检索与查询高度相关的上下文。然而，传统理论指出，仅追求上下文相关性而不考虑其他标准的检索系统可能引发信息瓶颈。我们在当今 LLM 时代重现了这一发现：标准 RAG 管道中，仅最大化上下文相关性可能损害下游响应质量。为此，我们评估了现有 RAG 方法，这些方法兼顾上下文相关性和答案质量。这些评估揭示了一个新发现：现有 RAG 系统在推理时间计算资源使用上扩展性不佳。我们提出“REBEL（RErank BEyond reLevance）”，通过链式思维提示（可选多轮对话）注入多标准优化，使 RAG 系统能够随推理时间计算资源增加而扩展。这实现了性能与速度的新权衡曲线，让 RAG 系统在推理时间增加时，既能提升检索上下文相关性，又能优化答案质量。我们方法在 llama-index 中的实现代码可在以下链接找到：https://github.com/run-llama/llama_index/pull/17590。使用此实现运行实验的代码可在 https://github.com/microsoft/REBEL 找到。

> Modern Large Language Model (LLM) systems typically rely on Retrieval Augmented Generation (RAG) which aims to gather context that is useful for response generation. These RAG systems typically optimize strictly towards retrieving context that is maximally relevant to the query. However, conventional theory suggests that retrieval systems which seek to maximize context relevance without any additional explicit criteria can create information bottlenecks. We reaffirm this finding in the modern age of LLM's by showing that in standard RAG pipelines, maximizing for context relevance alone can degrade downstream response quality. In response, we show evaluations of existing RAG methods which account for both context relevance and answer quality. These evaluations introduce a novel finding that existing RAG systems scale poorly with inference time compute usage when considering our combined metric. We introduce "RErank BEyond reLevance (REBEL)", which enables RAG systems to scale with inference-time compute via injection of multi-criteria optimization using Chain-of-Thought prompting (and optionally Multi-Turn dialogue). Ultimately, this enables a new performance/speed tradeoff curve, where RAG systems are able to achieve both higher relevance of retrieved contexts and superior answer quality as inference time increases. Code for the implementation of our method in llama-index can be found at the following PR: https://github.com/run-llama/llama_index/pull/17590. Code for running experiments using this llama-index implementation can be found at https://github.com/microsoft/REBEL.

[Arxiv](https://arxiv.org/abs/2504.07104)