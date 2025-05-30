# 训练语言模型生成高质量代码：借助程序分析反馈

发布时间：2025年05月28日

`LLM应用` `软件工程` `代码生成`

> Training Language Models to Generate Quality Code with Program Analysis Feedback

# 摘要

> 基于大型语言模型（LLMs）的代码生成，即 vibe 编码，在生产环境中广泛应用，但代码质量却难以保障，尤其在安全（如 SQL 注入漏洞）和可维护性（如缺少类型注解）方面表现不佳。现有的监督微调和基于规则的后处理方法，受限于劳动密集型标注或脆性启发式规则，难以实现有效的扩展。我们提出 REAL，一个强化学习框架，通过程序分析引导的反馈机制，激励 LLMs 生成高质量的生产代码。具体而言，REAL 集成了两大自动化信号：（1）程序分析检测安全或可维护性缺陷，（2）单元测试确保功能性正确性。与以往研究不同，REAL 是提示无关且无参考的，可在无需人工干预的情况下实现大规模监督。实验证明，REAL 在功能性和代码质量的综合评估中超越现有最优方法。我们的研究架起了快速原型设计与生产就绪代码之间的桥梁，使 LLMs 在保持生成速度的同时，确保代码质量。

> Code generation with large language models (LLMs), often termed vibe coding, is increasingly adopted in production but fails to ensure code quality, particularly in security (e.g., SQL injection vulnerabilities) and maintainability (e.g., missing type annotations). Existing methods, such as supervised fine-tuning and rule-based post-processing, rely on labor-intensive annotations or brittle heuristics, limiting their scalability and effectiveness. We propose REAL, a reinforcement learning framework that incentivizes LLMs to generate production-quality code using program analysis-guided feedback. Specifically, REAL integrates two automated signals: (1) program analysis detecting security or maintainability defects and (2) unit tests ensuring functional correctness. Unlike prior work, our framework is prompt-agnostic and reference-free, enabling scalable supervision without manual intervention. Experiments across multiple datasets and model scales demonstrate that REAL outperforms state-of-the-art methods in simultaneous assessments of functionality and code quality. Our work bridges the gap between rapid prototyping and production-ready code, enabling LLMs to deliver both speed and quality.

[Arxiv](https://arxiv.org/abs/2505.22704)