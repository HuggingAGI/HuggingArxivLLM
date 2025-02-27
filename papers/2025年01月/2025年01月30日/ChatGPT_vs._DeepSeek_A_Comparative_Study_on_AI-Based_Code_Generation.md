# ChatGPT 与 DeepSeek 对比研究：基于 AI 的代码生成能力评估

发布时间：2025年01月30日

`LLM应用` `软件开发` `人工智能`

> ChatGPT vs. DeepSeek: A Comparative Study on AI-Based Code Generation

# 摘要

> # 背景
AI驱动的代码生成正引领软件开发的革命，大型语言模型（LLMs）如 OpenAI 的 Codex、GPT-4 以及 DeepSeek 通过海量代码和自然语言数据实现这一目标。然而，尽管技术进步显著，代码质量、正确性以及复杂任务的管理仍面临挑战，亟需系统性评估。

# 方法
本研究通过在线编程挑战，对比 ChatGPT（版本 o1）与 DeepSeek（版本 R1）在 Python 代码生成方面的表现。评估维度包括正确性（基于在线评测系统判决结果，最多三次提交机会）、代码质量（采用 Pylint/Flake8 工具）以及效率（涵盖执行时间和内存占用）。

# 结果
DeepSeek 在正确性方面表现更优，尤其在算法任务中，往往一次提交即获“通过”判定。相比之下，ChatGPT 偶尔需多次尝试或面临失败。值得注意的是，ChatGPT 在代码质量上表现更佳，内存使用量持平或略低，执行时间更短，且代码行数更少。

# 结论
DeepSeek 在 Python 代码生成的正确性上展现出显著优势，尤其在算法问题解决中更具优势。两者在执行效率和内存占用方面表现相近。本研究为开发者选择 AI 代码助手提供了重要参考，同时也为未来 AI 驱动的软件开发研究指明了方向。


> Background: AI-powered code generation, fueled by Large Language Models (LLMs), is revolutionizing software development. Models like OpenAI's Codex and GPT-4, alongside DeepSeek, leverage vast code and natural language datasets. However, ensuring code quality, correctness, and managing complex tasks remains challenging, necessitating thorough evaluation. Methodology: This research compares ChatGPT (version o1) and DeepSeek (version R1) for Python code generation using online judge coding challenges. It evaluates correctness (online judge verdicts, up to three attempts), code quality (Pylint/Flake8), and efficiency (execution time/memory usage). Results: DeepSeek demonstrated higher correctness, particularly on algorithmic tasks, often achieving 'Accepted' on the first attempt. ChatGPT sometimes requires multiple attempts or failures. ChatGPT encountered fewer issues, used comparable or slightly less memory, consumed less execution times and wrote fewer lines of code. Conclusion: DeepSeek exhibited superior correctness in Python code generation, often requiring fewer attempts, suggesting an advantage in algorithmic problem-solving. Both models showed almost similar efficiency in execution time and memory use. Finally, this research provides insights for developers choosing AI coding assistants and informs future AI-driven software development research.

[Arxiv](https://arxiv.org/abs/2502.18467)