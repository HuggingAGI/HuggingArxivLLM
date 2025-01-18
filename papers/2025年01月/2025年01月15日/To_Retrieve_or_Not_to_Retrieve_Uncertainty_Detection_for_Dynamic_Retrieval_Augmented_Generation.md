# 检索与否？动态检索增强生成中的不确定性检测

发布时间：2025年01月15日

`RAG

理由：这篇论文主要讨论了检索增强生成（Retrieval-Augmented Generation, RAG）技术，特别是如何通过动态检索来优化长篇问答任务中的检索调用。论文探讨了不确定性检测方法在决定何时进行检索中的应用，并展示了这些方法在减少检索调用次数同时保持问答准确率的效果。因此，这篇论文应被分类为RAG。` `问答系统`

> To Retrieve or Not to Retrieve? Uncertainty Detection for Dynamic Retrieval Augmented Generation

# 摘要

> 检索增强生成（Retrieval-Augmented Generation）赋予大型语言模型检索外部知识的能力，从而通过整合超出模型内在能力的信息来减少幻觉。然而，大多数先前的研究集中在确定性调用检索上，这使得它不适合长篇问答等任务。相比之下，仅在底层LLM缺乏所需知识时动态执行检索可能更高效。在此背景下，我们通过探索多种不确定性检测方法，深入探讨了“检索还是不检索？”的问题。我们评估了这些方法在长篇问答任务中的表现，采用动态检索，并展示了比较结果。研究发现，不确定性检测指标，如度矩阵Jaccard和偏心率，可以将检索调用次数减少近一半，而问答准确率仅略有下降。

> Retrieval-Augmented Generation equips large language models with the capability to retrieve external knowledge, thereby mitigating hallucinations by incorporating information beyond the model's intrinsic abilities. However, most prior works have focused on invoking retrieval deterministically, which makes it unsuitable for tasks such as long-form question answering. Instead, dynamically performing retrieval by invoking it only when the underlying LLM lacks the required knowledge can be more efficient. In this context, we delve deeper into the question, "To Retrieve or Not to Retrieve?" by exploring multiple uncertainty detection methods. We evaluate these methods for the task of long-form question answering, employing dynamic retrieval, and present our comparisons. Our findings suggest that uncertainty detection metrics, such as Degree Matrix Jaccard and Eccentricity, can reduce the number of retrieval calls by almost half, with only a slight reduction in question-answering accuracy.

[Arxiv](https://arxiv.org/abs/2501.09292)