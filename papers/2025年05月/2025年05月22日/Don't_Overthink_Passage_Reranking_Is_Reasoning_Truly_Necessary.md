# 别对段落重排序想太多：推理真的不可或缺吗？

发布时间：2025年05月22日

`LLM应用` `信息检索`

> Don't "Overthink" Passage Reranking: Is Reasoning Truly Necessary?

# 摘要

> 随着推理模型在复杂自然语言任务中的成功，信息检索 (IR) 领域的研究人员开始探索如何将类似的推理能力整合到基于大型语言模型 (LLM) 的段落重排器中。这些方法通常使用 LLM 生成明确的、逐步推理过程，最终得出相关性预测。然而，推理能力真的能提升重排的准确性吗？在这篇论文中，我们深入探讨了这一问题，通过在相同训练条件下比较基于推理的点式重排器 (ReasonRR) 和标准的非推理点式重排器 (StandardRR)，发现 StandardRR 通常优于 ReasonRR。进一步研究推理对 ReasonRR 的重要性时，我们禁用了其推理过程 (ReasonRR-NoReason)，发现 ReasonRR-NoReason 竟然表现更佳。通过分析这一结果的原因，我们发现，基于推理的重排器受到 LLM 推理过程的限制，倾向于极端相关性得分，从而忽略了段落的部分相关性，而这正是点式重排器准确性的重要因素。

> With the growing success of reasoning models across complex natural language tasks, researchers in the Information Retrieval (IR) community have begun exploring how similar reasoning capabilities can be integrated into passage rerankers built on Large Language Models (LLMs). These methods typically employ an LLM to produce an explicit, step-by-step reasoning process before arriving at a final relevance prediction. But, does reasoning actually improve reranking accuracy? In this paper, we dive deeper into this question, studying the impact of the reasoning process by comparing reasoning-based pointwise rerankers (ReasonRR) to standard, non-reasoning pointwise rerankers (StandardRR) under identical training conditions, and observe that StandardRR generally outperforms ReasonRR. Building on this observation, we then study the importance of reasoning to ReasonRR by disabling its reasoning process (ReasonRR-NoReason), and find that ReasonRR-NoReason is surprisingly more effective than ReasonRR. Examining the cause of this result, our findings reveal that reasoning-based rerankers are limited by the LLM's reasoning process, which pushes it toward polarized relevance scores and thus fails to consider the partial relevance of passages, a key factor for the accuracy of pointwise rerankers.

[Arxiv](https://arxiv.org/abs/2505.16886)