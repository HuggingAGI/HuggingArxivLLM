# 探讨LLM生成的逻辑程序及其推理执行方法

发布时间：2025年02月13日

`LLM理论

摘要中讨论了从LLMs中提取知识的方法，如逻辑程序形式，并研究了推理方法和执行技术，属于理论层面的探讨。` `人工智能` `知识提取`

> On LLM-generated Logic Programs and their Inference Execution Methods

# 摘要

> 大型语言模型（LLMs）经过海量数据（以拍字节计）训练，压缩存储了迄今为止积累和提炼的大量知识。本文研究了以几种逻辑程序形式提取这些知识的技术，包括命题Horn子句、对偶Horn子句、关系三元组和确定性子句文法。通过将知识以逻辑程序形式提取，我们可以采用可靠的推理方法，验证LLM输出与预期用途的一致性，并扩展其推理能力。我们还研究了生成程序的新执行方法，包括将可 abduction 事实与存储在向量数据库中的LLM生成内容进行软统一，以及支持大型LLM生成程序推理的GPU加速极小模型计算。

> Large Language Models (LLMs) trained on petabytes of data are highly compressed repositories of a significant proportion of the knowledge accumulated and distilled so far. In this paper we study techniques to elicit this knowledge in the form of several classes of logic programs, including propositional Horn clauses, Dual Horn clauses, relational triplets and Definite Clause Grammars. Exposing this knowledge as logic programs enables sound reasoning methods that can verify alignment of LLM outputs to their intended uses and extend their inference capabilities.  We study new execution methods for the generated programs, including soft-unification of abducible facts against LLM-generated content stored in a vector database as well as GPU-based acceleration of minimal model computation that supports  inference with large LLM-generated programs.

[Arxiv](https://arxiv.org/abs/2502.09209)