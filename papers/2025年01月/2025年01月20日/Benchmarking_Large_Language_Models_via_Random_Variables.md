# 基于随机变量的大型语言模型基准测试

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要关注的是如何评估大型语言模型（LLMs）在数学推理领域的表现，并提出了一个新的评估框架RV-Bench。这属于LLM在实际应用中的表现评估，因此归类为LLM应用。`

> Benchmarking Large Language Models via Random Variables

# 摘要

> 随着大型语言模型（LLMs）在数学推理领域的持续进步，评估其在这一领域的表现已成为研究热点。然而，近期研究指出当前数学基准存在设计简单和数据泄露等问题，可靠性存疑。因此，构建一个能有效评估LLMs数学推理真实能力的可靠基准仍是一大挑战。为此，我们提出了RV-Bench，一个通过随机变量评估LLMs数学推理能力的框架。RV问题的背景内容与现有标准基准中的原始问题一致，但变量组合被随机化。LLMs需完全理解原始问题的解题过程，才能正确回答不同变量组合的RV问题。因此，LLMs在RV-Bench上的准确性反映了其数学推理的真实能力。我们对29个代表性LLMs进行了900多个RV问题的实验，并通过RV-Bench排行榜对这些模型进行了排名。进一步分析表明，当前LLMs在处理复杂数学推理问题时仍面临挑战。

> With the continuous advancement of large language models (LLMs) in mathematical reasoning, evaluating their performance in this domain has become a prominent research focus. Recent studies have raised concerns about the reliability of current mathematical benchmarks, highlighting issues such as simplistic design and potential data leakage. Therefore, creating a reliable benchmark that effectively evaluates the genuine capabilities of LLMs in mathematical reasoning remains a significant challenge. To address this, we propose RV-Bench, a framework for Benchmarking LLMs via Random Variables in mathematical reasoning. Specifically, the background content of a random variable question (RV question) mirrors the original problem in existing standard benchmarks, but the variable combinations are randomized into different values. LLMs must fully understand the problem-solving process for the original problem to correctly answer RV questions with various combinations of variable values. As a result, the LLM's genuine capability in mathematical reasoning is reflected by its accuracy on RV-Bench. Extensive experiments are conducted with 29 representative LLMs across 900+ RV questions. A leaderboard for RV-Bench ranks the genuine capability of these LLMs. Further analysis of accuracy dropping indicates that current LLMs still struggle with complex mathematical reasoning problems.

[Arxiv](https://arxiv.org/abs/2501.11790)