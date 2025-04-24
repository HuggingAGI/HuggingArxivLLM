# 案例研究：优化小型语言模型实现Python代码中准确且私密的CWE检测

发布时间：2025年04月23日

`LLM应用` `软件工程` `信息安全`

> Case Study: Fine-tuning Small Language Models for Accurate and Private CWE Detection in Python Code

# 摘要

> 大型语言模型（LLMs）在识别代码中的安全漏洞（如CWEs）方面表现出色，但其对云基础设施的依赖和高昂计算成本使其难以处理敏感代码。本研究探讨了小型语言模型（SLMs）作为本地漏洞检测工具的潜力。我们尝试将一个3.5亿参数的预训练代码模型（codegen-mono）微调，用于检测Python代码中的MITRE Top 25 CWEs。通过结合LLM生成的合成数据和人工审核，我们构建了一个包含500个示例的训练集。结果显示，基础模型无法检测CWEs，但经过指令微调后，SLM在测试中达到了99%的准确率、98.08%的精确率、100%的召回率和99.04%的F1分数。这表明微调后的SLMs不仅是高效的CWE检测工具，还能在保护隐私的同时，将高级安全分析无缝融入开发流程。

> Large Language Models (LLMs) have demonstrated significant capabilities in understanding and analyzing code for security vulnerabilities, such as Common Weakness Enumerations (CWEs). However, their reliance on cloud infrastructure and substantial computational requirements pose challenges for analyzing sensitive or proprietary codebases due to privacy concerns and inference costs. This work explores the potential of Small Language Models (SLMs) as a viable alternative for accurate, on-premise vulnerability detection. We investigated whether a 350-million parameter pre-trained code model (codegen-mono) could be effectively fine-tuned to detect the MITRE Top 25 CWEs specifically within Python code. To facilitate this, we developed a targeted dataset of 500 examples using a semi-supervised approach involving LLM-driven synthetic data generation coupled with meticulous human review. Initial tests confirmed that the base codegen-mono model completely failed to identify CWEs in our samples. However, after applying instruction-following fine-tuning, the specialized SLM achieved remarkable performance on our test set, yielding approximately 99% accuracy, 98.08% precision, 100% recall, and a 99.04% F1-score. These results strongly suggest that fine-tuned SLMs can serve as highly accurate and efficient tools for CWE detection, offering a practical and privacy-preserving solution for integrating advanced security analysis directly into development workflows.

[Arxiv](https://arxiv.org/abs/2504.16584)