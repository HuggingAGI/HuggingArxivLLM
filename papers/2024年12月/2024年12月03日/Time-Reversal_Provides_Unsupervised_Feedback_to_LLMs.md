# 时间反转为 LLMs 提供无监督式反馈

发布时间：2024年12月03日

`LLM应用` `模型评估`

> Time-Reversal Provides Unsupervised Feedback to LLMs

# 摘要

> 大型语言模型（LLMs）通常被训练为沿时间正向进行预测。然而，近期研究发现，引导这些模型回顾并审视自身的生成结果，能够产生有用的反馈。受此启发，我们探究了大型语言模型是否能够具备反向思考（预测和评分）的能力，从而提供对正向大型语言模型的补充性无监督反馈。为此，我们引入了时间反转语言模型（TRLMs），它在以响应为条件时能够评分和生成查询，有效地在时间反向发挥作用。另外，为了能在响应到查询的方向上有效推断，我们从零开始以反向标记顺序对语言模型（TRLM-Ba）进行预训练和微调。我们通过实践（以及在一种程式化的设定中从理论上）证明，当用于对给定响应的查询进行评分以对多个正向生成结果重新排序时，时间反转模型确实能够补充正向模型的预测。在广泛使用的 AlpacaEval 排行榜上，相较于使用自我对数困惑度得分的最佳 N 重排序这一强大基线，我们实现了高达 5％的提升。我们进一步表明，TRLM 评分优于给定查询的常规正向响应评分，在引文生成和段落检索等应用中收获了显著成效。接下来，我们借助 TRLM 的生成能力来增强或为大型语言模型的输入安全过滤器提供无监督反馈，在热门的 JailbreakBench 排行榜上针对若干种攻击，展现出假阴性率大幅降低，且对假阳性率的影响微乎其微。

> Large Language Models (LLMs) are typically trained to predict in the forward direction of time. However, recent works have shown that prompting these models to look back and critique their own generations can produce useful feedback. Motivated by this, we explore the question of whether LLMs can be empowered to think (predict and score) backwards to provide unsupervised feedback that complements forward LLMs. Towards this, we introduce Time Reversed Language Models (TRLMs), which can score and generate queries when conditioned on responses, effectively functioning in the reverse direction of time. Further, to effectively infer in the response to query direction, we pre-train and fine-tune a language model (TRLM-Ba) in the reverse token order from scratch. We show empirically (and theoretically in a stylized setting) that time-reversed models can indeed complement forward model predictions when used to score the query given response for re-ranking multiple forward generations. We obtain up to 5\% improvement on the widely used AlpacaEval Leaderboard over the competent baseline of best-of-N re-ranking using self log-perplexity scores. We further show that TRLM scoring outperforms conventional forward scoring of response given query, resulting in significant gains in applications such as citation generation and passage retrieval. We next leverage the generative ability of TRLM to augment or provide unsupervised feedback to input safety filters of LLMs, demonstrating a drastic reduction in false negative rate with negligible impact on false positive rates against several attacks published on the popular JailbreakBench leaderboard.

[Arxiv](https://arxiv.org/abs/2412.02626)