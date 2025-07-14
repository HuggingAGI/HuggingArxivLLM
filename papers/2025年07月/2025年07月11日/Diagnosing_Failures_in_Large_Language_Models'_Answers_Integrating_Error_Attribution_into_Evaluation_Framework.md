# 大型语言模型回答失败的深入解析：全面整合错误归因到评估框架中

发布时间：2025年07月11日

`LLM应用` `人工智能` `数据科学`

> Diagnosing Failures in Large Language Models' Answers: Integrating Error Attribution into Evaluation Framework

# 摘要

> 大型语言模型（LLMs）在各领域广泛应用，主流平台每天产生海量用户-模型交互数据。为了高效分析模型性能并诊断错误，建立一个系统分类和归属错误的自动化框架至关重要。然而，现有评估模型缺乏这一能力。本研究构建了包含6个主要类别和15个次要类别的综合错误归属框架，以支持深入分析。基于此框架，我们推出AttriData数据集，专门用于错误归属，包含归属结果、评分和反馈。同时，我们开发了MisAttributionLLM，这是首个通用评判模型，能够在生成评分的同时提供错误归属和反馈。通过大量实验和分析，我们验证了该方法的有效性和稳定性。

> With the widespread application of Large Language Models (LLMs) in various tasks, the mainstream LLM platforms generate massive user-model interactions daily. In order to efficiently analyze the performance of models and diagnose failures in their answers, it is essential to develop an automated framework to systematically categorize and attribute errors. However, existing evaluation models lack error attribution capability. In this work, we establish a comprehensive Misattribution Framework with 6 primary and 15 secondary categories to facilitate in-depth analysis. Based on this framework, we present AttriData, a dataset specifically designed for error attribution, encompassing misattribution, along with the corresponding scores and feedback. We also propose MisAttributionLLM, a fine-tuned model on AttriData, which is the first general-purpose judge model capable of simultaneously generating score, misattribution, and feedback. Extensive experiments and analyses are conducted to confirm the effectiveness and robustness of our proposed method.

[Arxiv](https://arxiv.org/abs/2507.08459)