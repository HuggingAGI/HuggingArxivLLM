# # 智能体 SLMs：精准捕捉测试异味

发布时间：2025年04月09日

`LLM应用` `软件工程`

> Agentic SLMs: Hunting Down Test Smells

# 摘要

> 测试异味会影响测试套件的可靠性和软件维护。虽然检测测试异味的方法不少，但去除异味的方案却很少。传统方法多依赖静态分析或机器学习，需要大量工作和专业知识。本研究评估了LLAMA 3.2 3B、GEMMA 2 9B、DEEPSEEK-R1 14B和PHI 4 14B这四个小型开源语言模型，通过基于智能体的工作流来自动化检测和重构测试异味。我们测试了包含1个、2个和4个智能体的工作流，在从真实Java项目中提取的150个实例的5种常见测试异味类型上进行了实验。与以往方法不同，我们的方法通过自然语言定义即可轻松扩展到新的测试异味，并支持Python和Golang语言。所有模型都检测到了几乎所有的测试异味实例（4个智能体的pass@5为96%），其中PHI 4 14B的重构准确性最高（pass@5为75.3%）。分析过程计算成本低廉，能在消费级硬件上高效运行。值得注意的是，PHI 4 14B搭配4个智能体的性能与O1-MINI、O3-MINI-HIGH和GEMINI 2.5 PRO EXPERIMENTAL等专有模型（使用单个智能体）相比仅相差5%。多智能体设置在5种测试异味类型中的3种表现优于单智能体设置，这表明它们在提高软件质量方面的能力，同时仅需极小的开发人员干预。然而，对于Assertion Roulette这种测试异味，单个智能体的表现更好。为了评估实际应用价值，我们向开源项目提交了10个由PHI 4 14B生成的代码的拉取请求。其中5个被合并，1个被拒绝，4个仍在审核中，这证明了该方法在实际应用中的有效性。

> Test smells can compromise the reliability of test suites and hinder software maintenance. Although several strategies exist for detecting test smells, few address their removal. Traditional methods often rely on static analysis or machine learning, requiring significant effort and expertise. This study evaluates LLAMA 3.2 3B, GEMMA 2 9B, DEEPSEEK-R1 14B, and PHI 4 14B - small, open language models - for automating the detection and refactoring of test smells through agent-based workflows. We explore workflows with one, two, and four agents across 150 instances of 5 common test smell types extracted from real-world Java projects. Unlike prior approaches, ours is easily extensible to new smells via natural language definitions and generalizes to Python and Golang. All models detected nearly all test smell instances (pass@5 of 96% with four agents), with PHI 4 14B achieving the highest refactoring accuracy (pass@5 of 75.3%). Analyses were computationally inexpensive and ran efficiently on a consumer-grade hardware. Notably, PHI 4 14B with four agents performed within 5% of proprietary models such as O1-MINI, O3-MINI-HIGH, and GEMINI 2.5 PRO EXPERIMENTAL using a single agent. Multi-agent setups outperformed single-agent ones in three out of five test smell types, highlighting their potential to improve software quality with minimal developer effort. For the Assertion Roulette smell, however, a single agent performed better. To assess practical relevance, we submitted 10 pull requests with PHI 4 14B - generated code to open-source projects. Five were merged, one was rejected, and four remain under review, demonstrating the approach's real-world applicability.

[Arxiv](https://arxiv.org/abs/2504.07277)