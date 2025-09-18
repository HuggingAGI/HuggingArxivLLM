# 基于大型语言模型的崩溃报告增强：实证研究

发布时间：2025年09月16日

`Agent` `基础理论`

> Crash Report Enhancement with Large Language Models: An Empirical Study

# 摘要

> 崩溃报告是软件维护的核心，却缺少开发人员高效调试必备的诊断细节。我们探讨了大型语言模型能否通过补充故障位置、根本原因解析及修复建议来完善崩溃报告，并研究了两种增强策略：Direct-LLM（基于堆栈跟踪上下文的单次方法）与Agentic-LLM（通过探索代码库获取额外证据的迭代方法）。在492份真实崩溃报告的数据集上，LLM增强报告将Top-1问题定位准确率从原始报告的10.6%提升至40.2%-43.1%，且生成的建议修复方案与开发人员补丁高度相似（CodeBLEU值约56%-57%）。人工评估与LLM评判结果均显示，Agentic-LLM能提供更深入的根本原因解析和更具实操性的修复建议。16名参与者的用户研究进一步证实，增强后的报告能让崩溃问题更易理解与解决，尤其在修复建议方面改进最为显著。上述结果表明，为LLM提供堆栈跟踪与代码库代码可生成增强版崩溃报告，这类报告对调试工作帮助显著。

> Crash reports are central to software maintenance, yet many lack the diagnostic detail developers need to debug efficiently. We examine whether large language models can enhance crash reports by adding fault locations, root-cause explanations, and repair suggestions. We study two enhancement strategies: Direct-LLM, a single-shot approach that uses stack-trace context, and Agentic-LLM, an iterative approach that explores the repository for additional evidence. On a dataset of 492 real-world crash reports, LLM-enhanced reports improve Top-1 problem-localization accuracy from 10.6% (original reports) to 40.2-43.1%, and produce suggested fixes that closely resemble developer patches (CodeBLEU around 56-57%). Both our manual evaluations and LLM-as-a-judge assessment show that Agentic-LLM delivers stronger root-cause explanations and more actionable repair guidance. A user study with 16 participants further confirms that enhanced reports make crashes easier to understand and resolve, with the largest improvement in repair guidance. These results indicate that supplying LLMs with stack traces and repository code yields enhanced crash reports that are substantially more useful for debugging.

[Arxiv](https://arxiv.org/abs/2509.13535)