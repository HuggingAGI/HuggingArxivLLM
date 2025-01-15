# CWEval: 以结果为导向的 LLM 代码生成功能与安全性评估

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在代码生成和辅助编写方面的应用，特别是如何评估生成代码的功能正确性和安全性。论文提出了一个新的评估框架CWEval，旨在提升LLM生成安全代码的评估效果。这属于LLM在实际应用中的具体问题，因此分类为LLM应用。` `软件开发` `网络安全`

> CWEval: Outcome-driven Evaluation on Functionality and Security of LLM Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成和辅助编写方面为开发者提供了巨大帮助，显著提升了生产力。然而，尽管识别错误代码相对容易，检测功能正确代码中的漏洞却更为复杂，尤其是对安全知识有限的开发者而言。这带来了使用LLM生成代码的安全隐患，凸显了评估功能正确性和安全性的重要性。现有基准如CyberSecEval和SecurityEval虽试图解决这一问题，但因规范不明确且不切实际，未能准确评估功能与安全性。为此，我们推出了CWEval，一个创新的结果驱动评估框架，旨在通过高质量的任务规范和结果驱动的测试预言，提升LLM生成安全代码的评估效果。结合多语言、安全关键的编码基准CWEval-bench，CWEval为LLM生成代码提供了严格的实证安全评估，克服了以往基准的不足。我们的评估显示，CWEval成功识别了大量功能正确但不安全的代码，并揭示了之前评估的严重偏差，为安全代码生成领域做出了重要贡献。我们已在https://github.com/Co1lin/CWEval开源了相关工具。

> Large Language Models (LLMs) have significantly aided developers by generating or assisting in code writing, enhancing productivity across various tasks. While identifying incorrect code is often straightforward, detecting vulnerabilities in functionally correct code is more challenging, especially for developers with limited security knowledge, which poses considerable security risks of using LLM-generated code and underscores the need for robust evaluation benchmarks that assess both functional correctness and security. Current benchmarks like CyberSecEval and SecurityEval attempt to solve it but are hindered by unclear and impractical specifications, failing to assess both functionality and security accurately. To tackle these deficiencies, we introduce CWEval, a novel outcome-driven evaluation framework designed to enhance the evaluation of secure code generation by LLMs. This framework not only assesses code functionality but also its security simultaneously with high-quality task specifications and outcome-driven test oracles which provides high accuracy. Coupled with CWEval-bench, a multilingual, security-critical coding benchmark, CWEval provides a rigorous empirical security evaluation on LLM-generated code, overcoming previous benchmarks' shortcomings. Through our evaluations, CWEval reveals a notable portion of functional but insecure code produced by LLMs, and shows a serious inaccuracy of previous evaluations, ultimately contributing significantly to the field of secure code generation. We open-source our artifact at: https://github.com/Co1lin/CWEval .

[Arxiv](https://arxiv.org/abs/2501.08200)