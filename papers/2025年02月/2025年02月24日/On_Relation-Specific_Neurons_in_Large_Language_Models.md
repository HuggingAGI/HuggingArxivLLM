# 大型语言模型中的关系特定神经元探讨

发布时间：2025年02月24日

`LLM理论` `神经科学` `人工智能`

> On Relation-Specific Neurons in Large Language Models

# 摘要

> 在大型语言模型（LLMs）中，特定的神经元能够存储预训练过程中学习到的不同知识片段。虽然知识通常表现为关系与实体的结合，但目前尚不清楚是否有神经元专门关注关系本身——独立于任何实体。我们假设这些神经元能够检测输入文本中的关系，并指导涉及该关系的生成过程。为了研究这一假设，我们采用基于统计的方法，以选定的一组关系为研究对象，对 Llama-2 模型家族进行了分析。实验结果表明存在特定关系的神经元。我们通过选择性地禁用与特定关系 【数学公式】r 相关的候选神经元，测量了这一操作对 LLM 处理以下两类事实能力的影响：(1) 关系为 【数学公式】r 的事实；(2) 关系为其他关系 【数学公式】r' ≠ 【数学公式】r 的事实。就关系信息编码能力而言，我们为特定关系神经元的以下三个特性提供了证据。$	extbf{(i) 神经元累积性。}$ 关系 【数学公式】r 的神经元表现出累积效应，即禁用更多的这些神经元会导致更多与 【数学公式】r 相关的事实生成能力下降。$	extbf{(ii) 神经元通用性。}$ 神经元可以在多个紧密相关或不太相关的不同关系之间共享。某些关系神经元甚至可以跨语言迁移。$	extbf{(iii) 神经元干扰性。}$ 禁用特定于某一关系的神经元可能会提高 LLM 对其他关系事实的生成性能。我们的代码将在 https://github.com/cisnlp/relation-specific-neurons 上公开发布。


> In large language models (LLMs), certain neurons can store distinct pieces of knowledge learned during pretraining. While knowledge typically appears as a combination of relations and entities, it remains unclear whether some neurons focus on a relation itself -- independent of any entity. We hypothesize such neurons detect a relation in the input text and guide generation involving such a relation. To investigate this, we study the Llama-2 family on a chosen set of relations with a statistics-based method. Our experiments demonstrate the existence of relation-specific neurons. We measure the effect of selectively deactivating candidate neurons specific to relation $r$ on the LLM's ability to handle (1) facts whose relation is $r$ and (2) facts whose relation is a different relation $r' \neq r$. With respect to their capacity for encoding relation information, we give evidence for the following three properties of relation-specific neurons. $\textbf{(i) Neuron cumulativity.}$ The neurons for $r$ present a cumulative effect so that deactivating a larger portion of them results in the degradation of more facts in $r$. $\textbf{(ii) Neuron versatility.}$ Neurons can be shared across multiple closely related as well as less related relations. Some relation neurons transfer across languages. $\textbf{(iii) Neuron interference.}$ Deactivating neurons specific to one relation can improve LLM generation performance for facts of other relations. We will make our code publicly available at https://github.com/cisnlp/relation-specific-neurons.

[Arxiv](https://arxiv.org/abs/2502.17355)