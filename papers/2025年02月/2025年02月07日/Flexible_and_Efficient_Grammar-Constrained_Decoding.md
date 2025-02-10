# 语法约束下的灵活高效解码

发布时间：2025年02月07日

`LLM应用` `算法优化`

> Flexible and Efficient Grammar-Constrained Decoding

# 摘要

> 大型语言模型（LLMs）常需生成遵循精确语法规则的结构化输出，如代码片段或格式化数据。语法约束解码（GCD）通过屏蔽不符合指定上下文无关文法（CFG）的标记，确保LLM输出符合规则。为保证正确性，GCD算法需计算LLM子词分词器与文法标记的对齐，并据此计算标记屏蔽。高效实现这一过程极具挑战，现有GCD算法需数十分钟预处理常见文法。我们提出一种新的GCD算法，其离线预处理速度较现有方法快17.71倍，同时保持在线屏蔽计算的最先进效率。

> Large Language Models (LLMs) are often asked to generate structured outputs that obey precise syntactic rules, such as code snippets or formatted data. Grammar-constrained decoding (GCD) can guarantee that LLM outputs matches such rules by masking out tokens that will provably lead to outputs that do not belong to a specified context-free grammar (CFG). To guarantee soundness, GCD algorithms have to compute how a given LLM subword tokenizer can align with the tokens used
  by a given context-free grammar and compute token masks based on this information. Doing so efficiently is challenging and existing GCD algorithms require tens of minutes to preprocess common grammars. We present a new GCD algorithm together with an implementation that offers 17.71x faster offline preprocessing than existing approaches while preserving state-of-the-art efficiency in online mask computation.

[Arxiv](https://arxiv.org/abs/2502.05111)