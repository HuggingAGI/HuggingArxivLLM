# # 基于统一DeepStochLog的有效文本到SQL生成
通过基于统一方法的DeepStochLog实现有效的文本到SQL生成

发布时间：2025年03月17日

`LLM应用` `数据库`

> Valid Text-to-SQL Generation with Unification-based DeepStochLog

# 摘要

> 大型语言模型能够将自然语言问题转化为SQL查询，但在缺乏严格句法和模式约束的情况下，偶尔会产生无法执行的无效查询，这限制了其实际应用。为此，我们提出了一种基于统一基定言句法和模式约束的神经符号框架，确保生成的查询始终有效。我们的框架还构建了与语言模型的双向接口，以充分利用其自然语言理解能力。在SQL语法子集上的评估结果显示，所有输出查询均有效。这是迈向基于统一基语法扩展语言模型的第一步，我们证明这种扩展显著提升了语言模型的有效性、执行准确性和与真实结果的一致性。我们的代码已在GitHub上开源，地址为https://github.com/ML-KULeuven/deepstochlog-lm。

> Large language models have been used to translate natural language questions to SQL queries. Without hard constraints on syntax and database schema, they occasionally produce invalid queries that are not executable. These failures limit the usage of these systems in real-life scenarios. We propose a neurosymbolic framework that imposes SQL syntax and schema constraints with unification-based definite clause grammars and thus guarantees the generation of valid queries. Our framework also builds a bi-directional interface to language models to leverage their natural language understanding abilities. The evaluation results on a subset of SQL grammars show that all our output queries are valid. This work is the first step towards extending language models with unification-based grammars. We demonstrate this extension enhances the validity, execution accuracy, and ground truth alignment of the underlying language model by a large margin. Our code is available at https://github.com/ML-KULeuven/deepstochlog-lm.

[Arxiv](https://arxiv.org/abs/2503.13342)