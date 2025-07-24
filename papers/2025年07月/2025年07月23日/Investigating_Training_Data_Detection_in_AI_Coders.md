# # 探索AI编码器中的训练数据检测机制
研究AI编码器中的训练数据检测

发布时间：2025年07月23日

`LLM应用` `软件工程` `信息安全`

> Investigating Training Data Detection in AI Coders

# 摘要

> 近年来，代码大型语言模型（CodeLLMs）的突破使其成为现代软件工程中不可或缺的工具。然而，这些模型偶尔会生成包含专有或敏感代码片段的输出，引发了对训练数据潜在非合规使用的担忧，并对隐私和知识产权构成风险。为了确保负责任且合规地部署CodeLLMs，训练数据检测（TDD）已成为一项关键任务。尽管在自然语言环境下，TDD方法显示出潜力，但它们在代码数据上的有效性仍待深入探索。这一差距尤为重要，因为代码具有结构化的语法和与自然语言不同的相似性标准。为此，我们对七种最先进的TDD方法在源代码数据上进行了全面的实证研究，评估它们在八种CodeLLMs中的表现。为了支持这一评估，我们引入了CodeSnitch，这是一个函数级别的基准数据集，包含三种编程语言的9,000个代码样本，每个样本都明确标记为包含或不包含在CodeLLM的训练中。除了在原始CodeSnitch上的评估，我们还设计了有针对性的变异策略，以测试TDD方法在三种不同设置下的鲁棒性。这些变异策略基于已建立的Type-1到Type-4代码克隆检测分类法。我们的研究为当前针对代码的TDD技术提供了系统性的评估，并为未来开发更有效和更 robust 的检测方法提供了宝贵的见解。

> Recent advances in code large language models (CodeLLMs) have made them indispensable tools in modern software engineering. However, these models occasionally produce outputs that contain proprietary or sensitive code snippets, raising concerns about potential non-compliant use of training data, and posing risks to privacy and intellectual property. To ensure responsible and compliant deployment of CodeLLMs, training data detection (TDD) has become a critical task. While recent TDD methods have shown promise in natural language settings, their effectiveness on code data remains largely underexplored. This gap is particularly important given code's structured syntax and distinct similarity criteria compared to natural language. To address this, we conduct a comprehensive empirical study of seven state-of-the-art TDD methods on source code data, evaluating their performance across eight CodeLLMs. To support this evaluation, we introduce CodeSnitch, a function-level benchmark dataset comprising 9,000 code samples in three programming languages, each explicitly labeled as either included or excluded from CodeLLM training. Beyond evaluation on the original CodeSnitch, we design targeted mutation strategies to test the robustness of TDD methods under three distinct settings. These mutation strategies are grounded in the well-established Type-1 to Type-4 code clone detection taxonomy. Our study provides a systematic assessment of current TDD techniques for code and offers insights to guide the development of more effective and robust detection methods in the future.

[Arxiv](https://arxiv.org/abs/2507.17389)