# TrustJudge：LLM评判者的不一致性及缓解方法

发布时间：2025年09月25日

`LLM应用` `基础理论`

> TrustJudge: Inconsistencies of LLM-as-a-Judge and How to Alleviate Them

# 摘要

> 将大型语言模型（LLMs）用作自动评估器（LLM-as-a-judge）的实践揭示了当前评估框架存在严重的不一致性。我们发现两种核心不一致类型：（1）分数-比较不一致性——即评分较低的回答在两两比较中反而优于评分较高的回答；（2）成对传递性不一致性——表现为循环偏好链（A>B>C>A）与等价矛盾（A=B=C≠A）。我们认为，这些问题源于离散评分系统的信息损失以及两两评估时模糊的平局判定。为此，我们提出了TrustJudge——一个概率框架，通过两项核心创新来克服这些局限：1）分布敏感评分：基于离散评分概率计算连续期望值，保留信息熵以实现更精准的评分；2）似然感知聚合：借助双向偏好概率或困惑度解决传递性违背问题。我们还从理论上阐明了当前LLM-as-a-judge框架的局限性，并论证了TrustJudge组件如何破解这些难题。我们使用数据集并以Llama-3.1-70B-Instruct作为评估器进行测试，结果显示：TrustJudge将分数-比较不一致性降低8.43%（从23.32%降至14.89%），成对传递性不一致性降低10.82%（从15.22%降至4.40%），同时保持了更高的评估准确率。本研究首次系统分析了LLM-as-a-judge范式中评估框架的不一致性，为可靠的自动评估提供了理论洞见与实用方案。该框架在不同模型架构和规模下均展现出稳定的性能提升，无需额外训练或人工标注，即可实现更可信的LLM评估。代码详见https://github.com/TrustJudge/TrustJudge。

> The adoption of Large Language Models (LLMs) as automated evaluators (LLM-as-a-judge) has revealed critical inconsistencies in current evaluation frameworks. We identify two fundamental types of inconsistencies: (1) Score-Comparison Inconsistency, where lower-rated responses outperform higher-scored ones in pairwise comparisons, and (2) Pairwise Transitivity Inconsistency, manifested through circular preference chains (A>B>C>A) and equivalence contradictions (A=B=C\neq A). We argue that these issues come from information loss in discrete rating systems and ambiguous tie judgments during pairwise evaluation. We propose TrustJudge, a probabilistic framework that addresses these limitations through two key innovations: 1) distribution-sensitive scoring that computes continuous expectations from discrete rating probabilities, preserving information entropy for more precise scoring, and 2) likelihood-aware aggregation that resolves transitivity violations using bidirectional preference probabilities or perplexity. We also formalize the theoretical limitations of current LLM-as-a-judge frameworks and demonstrate how TrustJudge's components overcome them. When evaluated with Llama-3.1-70B-Instruct as judge using our dataset, TrustJudge reduces Score-Comparison inconsistency by 8.43% (from 23.32% to 14.89%) and Pairwise Transitivity inconsistency by 10.82% (from 15.22% to 4.40%), while maintaining higher evaluation accuracy. Our work provides the first systematic analysis of evaluation framework inconsistencies in LLM-as-a-judge paradigms, offering both theoretical insights and practical solutions for reliable automated assessment. The framework demonstrates consistent improvements across various model architectures and scales, enabling more trustworthy LLM evaluation without requiring additional training or human annotations. The codes can be found at https://github.com/TrustJudge/TrustJudge.

[Arxiv](https://arxiv.org/abs/2509.21117)