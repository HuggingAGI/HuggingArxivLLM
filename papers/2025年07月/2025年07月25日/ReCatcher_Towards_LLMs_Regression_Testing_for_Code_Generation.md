# ReCatcher：探索LLMs代码生成的回归测试

发布时间：2025年07月25日

`LLM应用` `软件工程` `代码生成`

> ReCatcher: Towards LLMs Regression Testing for Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成领域发展迅猛，通过微调、模型合并或新版本发布不断演进。然而，这些更新不仅可能引发正确性问题，还可能影响代码质量和性能。为此，我们推出ReCatcher——一个专注于Python代码生成的回归测试框架。ReCatcher系统性地从逻辑正确性、代码质量和执行性能三大维度，对比分析两个LLM，通常是当前版本与候选更新版本。我们基于CodeLlama、DeepSeek-Coder和GPT-4o，评估了微调、模型合并和新版本发布三种场景下的回归问题。实验结果显示，跨语言数据集的微调会导致语法错误率增加高达12%。与Llama2等通用模型的合并会导致正确性下降高达18%。相比GPT-3.5-turbo，GPT-4o在处理缺失导入时，正确率下降高达50%。而GPT-4o-mini与GPT-4o相比，在执行时间上性能下降高达80%。总体来看，逻辑正确性、性能和错误处理（如语法错误和缺失导入）是最容易出现回归问题的方面。与基线方案相比，ReCatcher在逻辑和性能方面展现了更优且一致的准确性。我们的研究强调了在采用新模型前进行系统性回归评估的重要性，同时帮助研究人员和实践者做出更明智的更新决策。

> Large Language Models (LLMs) for code generation evolve rapidly through fine-tuning, merging, or new model releases. However, such updates can introduce regressions, not only in correctness but also in code quality and performance. To address this, we present ReCatcher, a regression testing framework for Python code generation. ReCatcher systematically compares two LLMs, typically a current model and a candidate update, across three dimensions: logical correctness, static code quality, and execution performance. We apply ReCatcher to assess regressions across three update scenarios, fine-tuning, merging, and model release, using CodeLlama, DeepSeek-Coder, and GPT-4o. Our evaluation shows that fine-tuning with cross-language datasets increases syntax errors by up to 12%. Merging with general-purpose models like Llama2 leads to regressions in correctness by up to 18%. GPT-4o introduces regressions of up to 50% in handling missing imports compared to GPT-3.5-turbo, while GPT-4o-mini suffers up to 80% performance degradation in execution time versus GPT-4o. Overall, logical correctness, performance, and error handling (e.g., syntax errors and missing imports) are the most regression-prone areas. Comparing ReCatcher with baseline solutions, it presents better and consistent accuracy across logical and performance aspects. ReCatcher highlights the importance of systematic regression evaluation before adopting new models, while assisting researchers and practitioners in making more informed update decisions.

[Arxiv](https://arxiv.org/abs/2507.19390)