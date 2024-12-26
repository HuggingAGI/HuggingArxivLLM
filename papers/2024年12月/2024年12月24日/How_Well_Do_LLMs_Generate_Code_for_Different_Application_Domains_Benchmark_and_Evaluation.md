# LLM 为不同应用领域生成代码的效果究竟怎样？基准与评估

发布时间：2024年12月24日

`LLM应用` `软件开发` `代码生成`

> How Well Do LLMs Generate Code for Different Application Domains? Benchmark and Evaluation

# 摘要

> 近来，越来越多由代码 LLMs 驱动的 AI 编程助手融入了各类真实的软件开发环境，大幅提升了开发者的生产力。然而，现有的代码生成基准多聚焦于通用场景，致使 LLMs 在特定应用领域的代码生成表现很大程度上不为人知。本文中，我们推出新基准 MultiCodeBench 来填补这一空缺。MultiCodeBench 涵盖 2400 个编程任务，涉及 12 个热门软件开发领域和 15 种编程语言。具体而言，我们深入探究以确定这 12 个应用领域。鉴于每个领域可能牵涉多个技术框架，且不同框架在编码过程中存在不同挑战，我们对每个领域内常用的框架和平台予以分类。接着，我们从与这些子领域相关的 GitHub 库中抽取编程问题。为保证任务质量并降低数据泄露风险，我们邀请标注员为 MultiCodeBench 中的每个任务重写文档字符串。此外，我们构建了基于静态分析的依赖解析工具，提取每个任务真实情况中的依赖关系，以便进行更深入的性能分析。通过在 MultiCodeBench 上针对 11 个有代表性的主流 LLMs 开展广泛实验，我们揭示了 LLMs 在不同应用领域的代码生成性能，为下游领域的开发者选择 LLMs 提供了实用参考。而且，我们剖析了模型在完成软件应用开发任务时失败的缘由，为模型开发者增强特定领域代码生成能力提供了指引。

> Recently, an increasing number of AI-driven programming assistants powered by code LLMs have been integrated into various real-world software development environments, significantly boosting developer productivity. However, existing code generation benchmarks primarily focus on general-purpose scenarios, leaving the code generation performance of LLMs for specific application domains largely unknown. In this paper, we introduce a new benchmark, MultiCodeBench, to fill this gap. MultiCodeBench comprises 2,400 programming tasks, covering 12 popular software development domains and 15 programming languages. Specifically, we perform in-depth research to identify these 12 application domains. Given that each domain may involve multiple technical frameworks, and that different frameworks present distinct challenges in the coding process, we categorize the commonly used frameworks and platforms within each domain. We then sample programming problems from GitHub repositories related to these subdomains. To ensure the quality of the tasks and mitigate data leakage issues, we invite annotators to rewrite the docstrings for each task in MultiCodeBench. Additionally, we build a static analysis-based dependency parsing tool to extract the dependencies in the ground truth for each task, enabling deeper performance analysis. Through extensive experiments on MultiCodeBench with eleven representative mainstream LLMs, we reveal the code generation performance of the LLMs across different application domains, providing practical insights for developers in downstream fields when selecting LLMs. Furthermore, we analyze the reasons behind the models' failures in completing software application development tasks, offering guidance for model developers to enhance domain-specific code generation capabilities.

[Arxiv](https://arxiv.org/abs/2412.18573)