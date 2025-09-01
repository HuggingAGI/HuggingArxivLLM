# # 事实还是仿作？现代检索模型的事实鲁棒性评估

发布时间：2025年08月28日

`RAG` `基础理论`

> Fact or Facsimile? Evaluating the Factual Robustness of Modern Retrievers

# 摘要

> 密集检索器和重排序器是检索增强生成（RAG）管道的核心，准确检索事实信息对维持系统可信度、防御RAG污染至关重要。然而，这些组件从其依托的大型语言模型（LLMs）中继承或丢失了多少事实能力，目前尚不明确。我们将12个公开的嵌入检查点与其原始基础LLM配对，在事实性基准上对两组模型进行评估。结果显示，所有评估模型中，嵌入变体的准确率均显著低于基础模型，绝对下降幅度达12-43个百分点（中位数28个百分点）；检索器的典型准确率仅为25-35%，而生成模型则可达60-70%。在更严苛的条件下，这种性能衰减进一步加剧：当每个问题的候选池从4个扩展至1000个时，性能最强的检索器top-1准确率从33%降至26%，凸显其对干扰项数量的高度敏感。统计测试进一步证实，各嵌入模型的查询与正确答案间余弦相似度显著高于错误答案（p < 0.01），说明决策主要依赖表面语义接近度，而非事实推理。为探究这一缺陷，我们利用GPT-4.1改写所有正确答案，构建了保留事实但掩盖词汇线索的重写测试集。结果显示，超三分之二的原正确预测翻转为错误，整体准确率降至原水平的约三分之一。综合来看，这些发现揭示了检索器对比学习的系统性权衡：语义检索能力的提升是以参数化事实知识的损失为代价的......

> Dense retrievers and rerankers are central to retrieval-augmented generation (RAG) pipelines, where accurately retrieving factual information is crucial for maintaining system trustworthiness and defending against RAG poisoning. However, little is known about how much factual competence these components inherit or lose from the large language models (LLMs) they are based on. We pair 12 publicly released embedding checkpoints with their original base LLMs and evaluate both sets on a factuality benchmark. Across every model evaluated, the embedding variants achieve markedly lower accuracy than their bases, with absolute drops ranging from 12 to 43 percentage points (median 28 pts) and typical retriever accuracies collapsing into the 25-35 % band versus the 60-70 % attained by the generative models. This degradation intensifies under a more demanding condition: when the candidate pool per question is expanded from four options to one thousand, the strongest retriever's top-1 accuracy falls from 33 % to 26 %, revealing acute sensitivity to distractor volume. Statistical tests further show that, for every embedding model, cosine-similarity scores between queries and correct completions are significantly higher than those for incorrect ones (p < 0.01), indicating decisions driven largely by surface-level semantic proximity rather than factual reasoning. To probe this weakness, we employed GPT-4.1 to paraphrase each correct completion, creating a rewritten test set that preserved factual truth while masking lexical cues, and observed that over two-thirds of previously correct predictions flipped to wrong, reducing overall accuracy to roughly one-third of its original level. Taken together, these findings reveal a systematic trade-off introduced by contrastive learning for retrievers: gains in semantic retrieval are paid for with losses in parametric factual knowledge......

[Arxiv](https://arxiv.org/abs/2508.20408)