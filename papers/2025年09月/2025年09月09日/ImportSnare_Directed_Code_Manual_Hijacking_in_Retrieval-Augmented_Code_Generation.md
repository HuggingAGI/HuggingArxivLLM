# ImportSnare：检索增强代码生成中的定向“代码手册”劫持

发布时间：2025年09月09日

`RAG` `基础理论`

> ImportSnare: Directed "Code Manual" Hijacking in Retrieval-Augmented Code Generation

# 摘要

> 代码生成已成为大型语言模型（LLMs）的核心能力，为不同技能水平的程序员带来了开发效率的革命性提升。但由于数据结构和算法逻辑的复杂性，生成代码常存在功能缺陷与安全漏洞，最终沦为需大量手动调试的原型代码。检索增强生成（RAG）虽能借助外部代码手册提升代码的正确性与安全性，却也埋下了新的安全隐患。
  本文首次深入探索检索增强代码生成（RACG）的攻击面，聚焦恶意依赖劫持问题。我们发现，包含隐藏恶意依赖项（如matplotlib_safe）的恶意文档可利用双重信任链——LLM对RAG的依赖与开发者对LLM建议的盲目信任——实现对RACG的攻击。为此，我们提出新型攻击框架ImportSnare，通过两种协同策略构建恶意文档：1）位置感知束搜索优化隐藏排序序列，提升恶意文档在检索结果中的排名；2）多语言诱导建议生成越狱序列，诱导LLM推荐恶意依赖项。在Python、Rust和JavaScript上的实验表明，ImportSnare总体攻击成功率显著（对matplotlib、seaborn等热门库超过50%），即便投毒比例低至0.01%，针对自定义及真实恶意包仍能成功攻击。研究结果揭示了LLM驱动开发中的重大供应链风险，暴露出代码生成任务在安全对齐方面的严重缺陷。为助力后续研究，我们将开源多语言基准套件与数据集，项目主页：https://importsnare.github.io。

> Code generation has emerged as a pivotal capability of Large Language Models(LLMs), revolutionizing development efficiency for programmers of all skill levels. However, the complexity of data structures and algorithmic logic often results in functional deficiencies and security vulnerabilities in generated code, reducing it to a prototype requiring extensive manual debugging. While Retrieval-Augmented Generation (RAG) can enhance correctness and security by leveraging external code manuals, it simultaneously introduces new attack surfaces.
  In this paper, we pioneer the exploration of attack surfaces in Retrieval-Augmented Code Generation (RACG), focusing on malicious dependency hijacking. We demonstrate how poisoned documentation containing hidden malicious dependencies (e.g., matplotlib_safe) can subvert RACG, exploiting dual trust chains: LLM reliance on RAG and developers' blind trust in LLM suggestions. To construct poisoned documents, we propose ImportSnare, a novel attack framework employing two synergistic strategies: 1)Position-aware beam search optimizes hidden ranking sequences to elevate poisoned documents in retrieval results, and 2)Multilingual inductive suggestions generate jailbreaking sequences to manipulate LLMs into recommending malicious dependencies. Through extensive experiments across Python, Rust, and JavaScript, ImportSnare achieves significant attack success rates (over 50% for popular libraries such as matplotlib and seaborn) in general, and is also able to succeed even when the poisoning ratio is as low as 0.01%, targeting both custom and real-world malicious packages. Our findings reveal critical supply chain risks in LLM-powered development, highlighting inadequate security alignment for code generation tasks. To support future research, we will release the multilingual benchmark suite and datasets. The project homepage is https://importsnare.github.io.

[Arxiv](https://arxiv.org/abs/2509.07941)