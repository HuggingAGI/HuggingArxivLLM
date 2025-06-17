# # 实证评估  
大型语言模型 (LLMs) 在程序自动修复领域的实证评估

发布时间：2025年06月16日

`LLM应用` `软件工程`

> Empirical Evaluation of Large Language Models in Automated Program Repair

# 摘要

> 软件缺陷日益普遍，自动化程序修复（APR）成为研究热点。大型语言模型（LLMs）为APR带来新机遇，但现有研究多依赖小型早期模型及Java基准测试。现代大规模LLMs在多语言多场景下的修复能力尚待深入探索。为此，我们对CodeLlama、LLaMA、StarCoder和DeepSeek-Coder四个开源LLMs进行了全面研究，涵盖70亿至330亿参数，不同架构与用途。在企业级与算法类缺陷场景、Java、C/C++、Python三种语言及四种提示策略下，分析六个基准测试中60余万条补丁。研究发现：（1）专用模型（如CodeLlama）优于大型通用模型（如LLaMA）；（2）修复性能与模型规模非线性相关；（3）正确补丁常在生成初期出现；（4）提示对结果影响显著。这些发现为设计高效LLM驱动的APR系统提供了实践指导。

> The increasing prevalence of software bugs has made automated program repair (APR) a key research focus. Large language models (LLMs) offer new opportunities for APR, but existing studies mostly rely on smaller, earlier-generation models and Java benchmarks. The repair capabilities of modern, large-scale LLMs across diverse languages and scenarios remain underexplored. To address this, we conduct a comprehensive empirical study of four open-source LLMs, CodeLlama, LLaMA, StarCoder, and DeepSeek-Coder, spanning 7B to 33B parameters, diverse architectures, and purposes. We evaluate them across two bug scenarios (enterprise-grades and algorithmic), three languages (Java, C/C++, Python), and four prompting strategies, analyzing over 600K generated patches on six benchmarks. Key findings include: (1) model specialization (e.g., CodeLlama) can outperform larger general-purpose models (e.g., LLaMA); (2) repair performance does not scale linearly with model size; (3) correct patches often appear early in generation; and (4) prompts significantly affect results. These insights offer practical guidance for designing effective and efficient LLM-based APR systems.

[Arxiv](https://arxiv.org/abs/2506.13186)