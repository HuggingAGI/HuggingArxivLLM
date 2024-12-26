# DeepCRCEval：对代码审查评论生成的评估进行重新审视

发布时间：2024年12月24日

`LLM应用` `软件开发` `代码审查`

> DeepCRCEval: Revisiting the Evaluation of Code Review Comment Generation

# 摘要

> 代码审查在软件开发中至关重要，却也要求颇高，这让自动生成审查评论备受关注。传统的评论评估方法主要基于文本相似度，然而面临两大挑战：开源项目中人工编写的评论可靠性参差不齐，且文本相似度与提高代码质量、检测缺陷等目标的关联较弱。
  本研究依据先前研究和开发者访谈得出的一套新准则，对基准评论展开了实证分析。接着，我们也重新审视了现有方法的评估。我们的评估框架 DeepCRCEval 融合了人工评估者和大型语言模型（LLMs），依据所设标准对当前技术进行了全面重评。此外，我们还引入了创新且高效的基线 LLM-Reviewer，借助 LLMs 的少样本学习能力进行有针对性的比较。
  我们的研究凸显了文本相似度指标的局限性，发现不到 10%的基准评论在自动化方面属于高质量。相比之下，DeepCRCEval 能有效区分高质量和低质量评论，是更可靠的评估机制。将 LLMs 评估者纳入 DeepCRCEval 显著提升了效率，分别减少 88.78%的时间和 90.32%的成本。而且，LLM-Reviewer 在评论生成中聚焦任务真实目标方面展现出巨大潜力。

> Code review is a vital but demanding aspect of software development, generating significant interest in automating review comments. Traditional evaluation methods for these comments, primarily based on text similarity, face two major challenges: inconsistent reliability of human-authored comments in open-source projects and the weak correlation of text similarity with objectives like enhancing code quality and detecting defects.
  This study empirically analyzes benchmark comments using a novel set of criteria informed by prior research and developer interviews. We then similarly revisit the evaluation of existing methodologies. Our evaluation framework, DeepCRCEval, integrates human evaluators and Large Language Models (LLMs) for a comprehensive reassessment of current techniques based on the criteria set. Besides, we also introduce an innovative and efficient baseline, LLM-Reviewer, leveraging the few-shot learning capabilities of LLMs for a target-oriented comparison.
  Our research highlights the limitations of text similarity metrics, finding that less than 10% of benchmark comments are high quality for automation. In contrast, DeepCRCEval effectively distinguishes between high and low-quality comments, proving to be a more reliable evaluation mechanism. Incorporating LLM evaluators into DeepCRCEval significantly boosts efficiency, reducing time and cost by 88.78% and 90.32%, respectively. Furthermore, LLM-Reviewer demonstrates significant potential of focusing task real targets in comment generation.

[Arxiv](https://arxiv.org/abs/2412.18291)