# 回答长度对长文本事实准确性的影响

发布时间：2025年05月29日

`LLM应用` `信息检索` `数据质量`

> How Does Response Length Affect Long-Form Factuality

# 摘要

> 大型语言模型 (LLMs) 在长文本生成领域应用广泛，但其响应中的事实错误可能影响可靠性。尽管 LLM 的事实准确性受到越来越多的关注，但响应长度对事实准确性的影响仍未得到充分研究。本研究通过引入一个自动化的双层级长文本事实准确性评估框架，系统地探讨了这一关系。该框架不仅与人工标注高度一致，还具有较高的成本效益。基于此框架，我们进行了受控实验，发现较长的响应在事实精度上表现较低，证实了长度偏见的存在。为了阐释这一现象，我们实证检验了三个假设：错误传播、长上下文和事实耗尽。研究结果表明，事实耗尽——即模型逐渐耗尽更可靠的知识——是事实准确性下降的主要原因，而非其他两个假设。

> Large language models (LLMs) are widely used for long-form text generation. However, factual errors in the responses would undermine their reliability. Despite growing attention to LLM factuality, the effect of response length on factuality remains underexplored. In this work, we systematically investigate this relationship by first introducing an automatic and bi-level long-form factuality evaluation framework, which achieves high agreement with human annotations while being cost-effective. Using this framework, we conduct controlled experiments and find that longer responses exhibit lower factual precision, confirming the presence of length bias. To explain this phenomenon, we empirically examine three hypotheses: error propagation, long context, and facts exhaustion. Our results reveal that facts exhaustion, where the model gradually exhausts more reliable knowledge, is the primary cause of factual degradation, rather than the other two hypotheses.

[Arxiv](https://arxiv.org/abs/2505.23295)