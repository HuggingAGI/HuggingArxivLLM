# 数据漂移对 CoT 的伤害：理论研究探讨

发布时间：2025年06月12日

`LLM应用` `机器学习`

> Data Shifts Hurt CoT: A Theoretical Study

# 摘要

> 思维链 (CoT) 在各类大型语言模型 (LLMs) 中得到广泛应用，并证实能有效提升输出质量。近期研究表明，从表达能力维度，transformers 存在绝对上限，因而无法解决诸多计算难题。然而，借助 CoT，transformers 能够有效攻克部分难题，如 $k$-parity 问题。不过，这些研究基于两个关键假设：(1) 训练与测试分布一致，以及 (2) 训练数据无污染且推理步骤准确。但在现实场景中，这些假设未必成立。尽管数据偏移的风险已引起关注，但据我们所知，本研究是首个系统探究此类偏移对模型性能确切损害的研究。聚焦于 $k$-parity 问题，本研究深入分析了分布偏移与数据中毒两种数据偏移对通过 CoT 分解训练模型质量的综合影响。除揭示 CoT 在学习奇偶性方面逊于直接预测这一令人意外的现象外，我们的研究还从机制层面系统阐述了这一现象的根本原因。

> Chain of Thought (CoT) has been applied to various large language models (LLMs) and proven to be effective in improving the quality of outputs. In recent studies, transformers are proven to have absolute upper bounds in terms of expressive power, and consequently, they cannot solve many computationally difficult problems. However, empowered by CoT, transformers are proven to be able to solve some difficult problems effectively, such as the $k$-parity problem. Nevertheless, those works rely on two imperative assumptions: (1) identical training and testing distribution, and (2) corruption-free training data with correct reasoning steps. However, in the real world, these assumptions do not always hold. Although the risks of data shifts have caught attention, our work is the first to rigorously study the exact harm caused by such shifts to the best of our knowledge. Focusing on the $k$-parity problem, in this work we investigate the joint impact of two types of data shifts: the distribution shifts and data poisoning, on the quality of trained models obtained by a well-established CoT decomposition. In addition to revealing a surprising phenomenon that CoT leads to worse performance on learning parity than directly generating the prediction, our technical results also give a rigorous and comprehensive explanation of the mechanistic reasons of such impact.

[Arxiv](https://arxiv.org/abs/2506.10647)