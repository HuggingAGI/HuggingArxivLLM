# 基于大型语言模型的通用自动化程序修复实证研究

发布时间：2025年06月03日

`LLM应用

摘要讨论了大型语言模型在自动程序修复中的应用，评估了不同模型的表现，并探讨了跨语言修复的挑战，属于LLM的实际应用研究。` `软件工程` `自动程序修复`

> Empirical Evaluation of Generalizable Automated Program Repair with Large Language Models

# 摘要

> 自动程序修复 (APR) 通过提供修复建议，助力开发者维护软件。当前研究的前沿主要聚焦于利用大型语言模型 (LLMs)，充分挖掘其理解自然语言规范和生成程序代码的强大能力。近期研究表明，LLMs 可以有效生成修复方案。然而，尽管过去十年中 APR 在研究和行业应用中取得了显著进展，但其广泛适用性仍显不足。本研究对 LLMs 生成补丁的能力进行了深入评估，涵盖 13 个近期模型，包括开源模型（如 Llama 3.3、Qwen 2.5 Coder 和 DeepSeek R1（分布式））和闭源模型（如 o3-mini、GPT-4o、Claude 3.7 Sonnet 和 Gemini 2.0 Flash）。我们基于 Java（如 Defects4J）、JavaScript（如 BugsJS）、Python（如 BugsInPy）和 PHP（如 BugsPHP）的基准测试，探索了语言无关的修复方法。除了评估不同语言和补丁复杂度层次上的泛化能力外，我们还研究了缺陷定位 (FL) 作为预处理步骤的影响，并对比了开源与闭源模型的表现。我们的评估结果揭示了最新 LLMs 的修复能力。主要发现包括：(1) 不同 LLMs 在不同语言上表现最佳，跨平台修复技术的开发面临挑战。 (2) 不同模型的组合在修复独特错误方面具有独特价值，专家模型组成的委员会值得考虑。 (3) 在缺陷定位不完美的现实假设下，与传统使用完美 FL 的方法相比，准确率显著下降。这些研究发现和见解将助力研究人员和从业者开发更可靠、更通用的 APR 技术，并在现实和公平的环境中进行评估。

> Automated Program Repair (APR) proposes bug fixes to aid developers in maintaining software. The state of the art in this domain focuses on using LLMs, leveraging their strong capabilities to comprehend specifications in natural language and to generate program code. Recent works have shown that LLMs can be used to generate repairs. However, despite the APR community's research achievements and several industry deployments in the last decade, APR still lacks the capabilities to generalize broadly. In this work, we present an intensive empirical evaluation of LLMs for generating patches. We evaluate a diverse set of 13 recent models, including open ones (e.g., Llama 3.3, Qwen 2.5 Coder, and DeepSeek R1 (dist.)) and closed ones (e.g., o3-mini, GPT-4o, Claude 3.7 Sonnet, Gemini 2.0 Flash). In particular, we explore language-agnostic repairs by utilizing benchmarks for Java (e.g., Defects4J), JavaScript (e.g., BugsJS), Python (e.g., BugsInPy), and PHP (e.g., BugsPHP). Besides the generalization between different languages and levels of patch complexity, we also investigate the effects of fault localization (FL) as a preprocessing step and compare the progress for open vs closed models. Our evaluation represents a snapshot of the current repair capabilities of the latest LLMs. Key results include: (1) Different LLMs tend to perform best for different languages, which makes it hard to develop cross-platform repair techniques with single LLMs. (2) The combinations of models add value with respect to uniquely fixed bugs, so a committee of expert models should be considered. (3) Under realistic assumptions of imperfect FL, we observe significant drops in accuracy from the usual practice of using perfect FL. Our findings and insights will help both researchers and practitioners develop reliable and generalizable APR techniques and evaluate them in realistic and fair environments.

[Arxiv](https://arxiv.org/abs/2506.03283)