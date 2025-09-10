# 人类是否与大型语言模型同样脆弱？

发布时间：2025年09月09日

`LLM理论` `基础理论`

> Are Humans as Brittle as Large Language Models?

# 摘要

> 大型语言模型（LLM）的输出不稳定，这源于两方面：解码过程的非确定性以及提示脆弱性。尽管LLM生成的内在非确定性可能通过输出的分布偏移来模拟人类标注中本就存在的不确定性，但人们普遍认为（却尚未深入研究）提示脆弱性效应是LLM特有的。这就引出了一个问题：人类标注者是否也对指令变化表现出类似的敏感性？如果是，LLM的提示脆弱性是否应被视为问题？或者，有人可能会假设提示脆弱性恰恰反映了人类标注的差异。为填补这一研究空白，我们系统比较了提示修改对LLM的影响与相同指令修改对人类标注者的影响，重点探究人类是否对提示扰动有类似的敏感性。为此，我们让人类和LLM在提示变化的条件下完成一组文本分类任务。研究结果表明，人类和LLM在面对特定类型的提示修改时，都会表现出更高的脆弱性，尤其是涉及替换替代标签集或标签格式的修改。不过，与LLM相比，人类判断的分布受拼写错误和标签顺序颠倒的影响更小。

> The output of large language models (LLM) is unstable, due to both non-determinism of the decoding process as well as to prompt brittleness. While the intrinsic non-determinism of LLM generation may mimic existing uncertainty in human annotations through distributional shifts in outputs, it is largely assumed, yet unexplored, that the prompt brittleness effect is unique to LLMs. This raises the question: do human annotators show similar sensitivity to instruction changes? If so, should prompt brittleness in LLMs be considered problematic? One may alternatively hypothesize that prompt brittleness correctly reflects human annotation variances. To fill this research gap, we systematically compare the effects of prompt modifications on LLMs and identical instruction modifications for human annotators, focusing on the question of whether humans are similarly sensitive to prompt perturbations. To study this, we prompt both humans and LLMs for a set of text classification tasks conditioned on prompt variations. Our findings indicate that both humans and LLMs exhibit increased brittleness in response to specific types of prompt modifications, particularly those involving the substitution of alternative label sets or label formats. However, the distribution of human judgments is less affected by typographical errors and reversed label order than that of LLMs.

[Arxiv](https://arxiv.org/abs/2509.07869)