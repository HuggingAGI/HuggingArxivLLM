# CASTLE：面向静态代码分析器与大型语言模型的CWE检测基准数据集

发布时间：2025年03月12日

`LLM应用` `软件工程`

> CASTLE: Benchmarking Dataset for Static Code Analyzers and LLMs towards CWE Detection

# 摘要

> 源代码漏洞识别在关键软件组件中至关重要。当前用于检测安全缺陷的方法包括静态分析、动态分析、形式验证和大型语言模型。本文介绍了CASTLE框架，用于评估不同方法的漏洞检测能力。我们使用包含250个微基准程序的数据集，评估了13种静态分析工具、10种LLM和2种形式验证工具，覆盖25种常见CWE漏洞。我们提出了CASTLE评分作为新型评估指标，确保公平比较。结果显示：ESBMC在减少误报方面表现优异，但在处理弱加密或SQL注入等复杂漏洞时效果有限。静态分析工具误报率高，增加了开发人员的验证负担。LLMs在小型代码片段的漏洞识别上表现出色，但随着代码规模增长，准确性和可靠性有所下降。这表明LLMs在未来安全解决方案中具有潜力，特别是在代码补全框架中提供实时指导以防止漏洞。数据集可在GitHub获取。

> Identifying vulnerabilities in source code is crucial, especially in critical software components. Existing methods such as static analysis, dynamic analysis, formal verification, and recently Large Language Models are widely used to detect security flaws. This paper introduces CASTLE (CWE Automated Security Testing and Low-Level Evaluation), a benchmarking framework for evaluating the vulnerability detection capabilities of different methods. We assess 13 static analysis tools, 10 LLMs, and 2 formal verification tools using a hand-crafted dataset of 250 micro-benchmark programs covering 25 common CWEs. We propose the CASTLE Score, a novel evaluation metric to ensure fair comparison. Our results reveal key differences: ESBMC (a formal verification tool) minimizes false positives but struggles with vulnerabilities beyond model checking, such as weak cryptography or SQL injection. Static analyzers suffer from high false positives, increasing manual validation efforts for developers. LLMs perform exceptionally well in the CASTLE dataset when identifying vulnerabilities in small code snippets. However, their accuracy declines, and hallucinations increase as the code size grows. These results suggest that LLMs could play a pivotal role in future security solutions, particularly within code completion frameworks, where they can provide real-time guidance to prevent vulnerabilities. The dataset is accessible at https://github.com/CASTLE-Benchmark.

[Arxiv](https://arxiv.org/abs/2503.09433)