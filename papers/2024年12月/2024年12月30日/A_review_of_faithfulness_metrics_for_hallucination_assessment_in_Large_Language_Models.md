# 大型语言模型幻觉评估的忠实度指标综述

发布时间：2024年12月30日

`RAG

理由：论文摘要中提到了“检索增强生成（RAG）”作为一种有效减少幻觉的方法，并且讨论了其在开放式摘要生成、问答和机器翻译任务中的应用。因此，这篇论文主要关注的是RAG技术及其在LLM中的应用，适合归类为RAG。` `人工智能`

> A review of faithfulness metrics for hallucination assessment in Large Language Models

# 摘要

> 本文综述了开放式摘要生成、问答和机器翻译任务中忠实度的评估方法。我们发现，使用LLMs作为忠实度评估器通常与人类判断高度相关。其他研究通过检索增强生成（RAG）和提示框架等方法有效减少了幻觉，并提出了进一步的改进建议。忠实度研究对LLMs的广泛应用至关重要，因为不忠实的响应可能带来重大风险。此外，开放式生成评估比传统的多项选择基准测试更能全面衡量LLM性能，有助于提升对LLMs的信任。

> This review examines the means with which faithfulness has been evaluated across open-ended summarization, question-answering and machine translation tasks. We find that the use of LLMs as a faithfulness evaluator is commonly the metric that is most highly correlated with human judgement. The means with which other studies have mitigated hallucinations is discussed, with both retrieval augmented generation (RAG) and prompting framework approaches having been linked with superior faithfulness, whilst other recommendations for mitigation are provided. Research into faithfulness is integral to the continued widespread use of LLMs, as unfaithful responses can pose major risks to many areas whereby LLMs would otherwise be suitable. Furthermore, evaluating open-ended generation provides a more comprehensive measure of LLM performance than commonly used multiple-choice benchmarking, which can help in advancing the trust that can be placed within LLMs.

[Arxiv](https://arxiv.org/abs/2501.00269)