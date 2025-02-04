# CondAmbigQA: 条件性模糊问答的基准与数据集

发布时间：2025年02月03日

`RAG

理由：这篇论文主要讨论了在模糊问答（QA）任务中，如何通过引入“条件”概念来解决模糊性问题，并提出了一个包含条件感知评估指标的基准（CondAmbigQA）。论文特别强调了基于检索的标注策略，利用维基百科片段来识别查询的可能解释作为条件，并通过这些条件标注答案。这种方法与检索增强生成（RAG）系统密切相关，因为RAG系统通常依赖于外部知识库（如维基百科）来增强生成答案的准确性和相关性。因此，这篇论文的核心内容与RAG技术密切相关，应归类为RAG。` `问答系统`

> CondAmbigQA: A Benchmark and Dataset for Conditional Ambiguous Question Answering

# 摘要

> # 摘要
大型语言模型（LLMs）在回答模糊问题时容易产生幻觉。用户常误以为LLMs能理解他们的认知背景，导致查询中遗漏关键信息。然而，LLMs的回答基于可能与用户意图不符的假设，这种不一致可能被视为幻觉。因此，识别这些隐含假设对解决QA中的模糊性至关重要。以往的研究，如AmbigQA，通过人工标注来减少模糊性，但这种方法在实际应用中不可行。ASQA则将AmbigQA的简短回答扩展为长篇回答，但未能避免人类偏见，且无法明确区分答案的逻辑差异。我们提出了条件模糊问答（CondAmbigQA），这是一个包含200个模糊查询和条件感知评估指标的基准。我们首次在模糊QA任务中引入“条件”概念，条件即解决模糊性的上下文约束或假设。基于检索的标注策略利用维基百科片段识别查询的可能解释作为条件，并通过这些条件标注答案，从而减少标注者知识水平差异带来的偏见。通过固定检索结果，CondAmbigQA评估了RAG系统如何利用条件解决模糊性。实验显示，考虑条件的模型性能提升了20%，当条件明确提供时，性能再提升5%。这些结果凸显了条件推理在QA中的重要性，为研究人员提供了评估模糊性解决的严谨工具。

> Large language models (LLMs) are prone to hallucinations in question-answering (QA) tasks when faced with ambiguous questions. Users often assume that LLMs share their cognitive alignment, a mutual understanding of context, intent, and implicit details, leading them to omit critical information in the queries. However, LLMs generate responses based on assumptions that can misalign with user intent, which may be perceived as hallucinations if they misalign with the user's intent. Therefore, identifying those implicit assumptions is crucial to resolve ambiguities in QA. Prior work, such as AmbigQA, reduces ambiguity in queries via human-annotated clarifications, which is not feasible in real application. Meanwhile, ASQA compiles AmbigQA's short answers into long-form responses but inherits human biases and fails capture explicit logical distinctions that differentiates the answers. We introduce Conditional Ambiguous Question-Answering (CondAmbigQA), a benchmark with 200 ambiguous queries and condition-aware evaluation metrics. Our study pioneers the concept of ``conditions'' in ambiguous QA tasks, where conditions stand for contextual constraints or assumptions that resolve ambiguities. The retrieval-based annotation strategy uses retrieved Wikipedia fragments to identify possible interpretations for a given query as its conditions and annotate the answers through those conditions. Such a strategy minimizes human bias introduced by different knowledge levels among annotators. By fixing retrieval results, CondAmbigQA evaluates how RAG systems leverage conditions to resolve ambiguities. Experiments show that models considering conditions before answering improve performance by $20\%$, with an additional $5\%$ gain when conditions are explicitly provided. These results underscore the value of conditional reasoning in QA, offering researchers tools to rigorously evaluate ambiguity resolution.

[Arxiv](https://arxiv.org/abs/2502.01523)